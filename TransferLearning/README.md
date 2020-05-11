# TransferLearning

* The *.ipynb* files contain the transfer learning implementation of the system.
* The layers can be frozen by setting -

```[python]
  layer.trainable = False
```

* The layer of the models such as Inception can be retrained by setting the same parameter as True.

* *weights* - it contains the pretrained model for DenseNet, InceptionV3, ResNet50 and VGG16.
