ERAv1 S6 (Exploring classifier networks using MNIST)

How to run:\
'Run All' cells

How to change network:\
Replace the network class name in the last cell and run.

Best performing networks:

Net_14:
```
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1           [-1, 10, 26, 26]             100
       BatchNorm2d-2           [-1, 10, 26, 26]              20
           Dropout-3           [-1, 10, 26, 26]               0
            Conv2d-4           [-1, 10, 24, 24]             910
       BatchNorm2d-5           [-1, 10, 24, 24]              20
           Dropout-6           [-1, 10, 24, 24]               0
         MaxPool2d-7           [-1, 10, 12, 12]               0
            Conv2d-8           [-1, 24, 10, 10]           2,184
       BatchNorm2d-9           [-1, 24, 10, 10]              48
          Dropout-10           [-1, 24, 10, 10]               0
           Conv2d-11             [-1, 32, 8, 8]           6,944
      BatchNorm2d-12             [-1, 32, 8, 8]              64
          Dropout-13             [-1, 32, 8, 8]               0
           Conv2d-14             [-1, 10, 6, 6]           2,890
AdaptiveAvgPool2d-15             [-1, 10, 1, 1]               0
           Conv2d-16             [-1, 10, 1, 1]             110
================================================================
Total params: 13,290
Trainable params: 13,290
Non-trainable params: 0
```

#epoch: 10
#Train set: Average loss: 0.0002, Accuracy: 99.25%
#Test set: Average loss: 0.0222, Accuracy: 9933/10000 (99.33%)

#epoch: 20
#Train set: Average loss: 0.0002, Accuracy: 99.40%
#Test set: Average loss: 0.0213, Accuracy: 9935/10000 (99.35%)



