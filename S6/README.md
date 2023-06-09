ERAv1 S6 (Exploring classifier networks using MNIST)

How to run:\
'Run All' cells

How to change network:\
Replace the network class name in the last cell and run.

Best performing networks:

Net_7:
```
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================
            Conv2d-1           [-1, 32, 28, 28]             320
       BatchNorm2d-2           [-1, 32, 28, 28]              64
           Dropout-3           [-1, 32, 28, 28]               0
            Conv2d-4           [-1, 64, 28, 28]          18,496
       BatchNorm2d-5           [-1, 64, 28, 28]             128
           Dropout-6           [-1, 64, 28, 28]               0
         MaxPool2d-7           [-1, 64, 14, 14]               0
            Conv2d-8          [-1, 128, 14, 14]          73,856
       BatchNorm2d-9          [-1, 128, 14, 14]             256
          Dropout-10          [-1, 128, 14, 14]               0
           Conv2d-11          [-1, 256, 14, 14]         295,168
      BatchNorm2d-12          [-1, 256, 14, 14]             512
          Dropout-13          [-1, 256, 14, 14]               0
        MaxPool2d-14            [-1, 256, 7, 7]               0
           Conv2d-15             [-1, 10, 7, 7]           2,570
        AvgPool2d-16             [-1, 10, 1, 1]               0
================================================================
Total params: 391,370
Trainable params: 391,370
Non-trainable params: 0

```

Accuracy on test set: 99.05 in 20 epochs


