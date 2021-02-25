# WideResnet_Tensorflow_Keras
Implementation of the WideResnet architecture in Tensorflow 2.0 (Keras)

The [Colab Notebook](https://colab.research.google.com/drive/1EjODNnT98e4-oswAKln3VAm6PpjC92-p#scrollTo=KaFtsR2Sdn32) shows the WideResnet Architecture and the performance when training on CIFAR-10. SGD with Learning Rate Scheduler is critical to achieve the validation accuracy score.         

As shown in the [Tensorboard](https://tensorboard.dev/experiment/oaqLCYxjQ0qVoVVQZeqelQ/#scalars&runSelectionState=eyJ0cmFpbiI6dHJ1ZSwidmFsaWRhdGlvbiI6dHJ1ZX0%3D), the model achieves 92%/94% validation accuracy for WideResnet 28-2/28-10 on Cifar-10. Examples of the 28-2 accuracy score:
<p align="center">
  <img width="460" height="300" src="https://github.com/huythong267/WideResnet_Tensorflow_Keras/blob/main/images/epoch_acc_28-2.svg">
</p>

## Architectures of WideResnet 28-10
![WideResnet 28-10](https://github.com/huythong267/WideResnet_Tensorflow_Keras/blob/main/images/WideResnet-28-10.png)
