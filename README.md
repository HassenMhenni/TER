# transfer learning in OCT images

In this project, we use a deep learning model to predict the causal gene of a given OCT image. The model is trained on a dataset of OCT images, which are divided into 8 different classes: AMD, CNV, CSR, DME, DR, DRusen, MH, and NORMAL. The model is based on the pre-trained ResNet18 model from PyTorch, and is trained using transfer learning.

To use the model, you will need to download the dataset from the following link:

https://www.kaggle.com/code/obulisainaren/retinal-oct-images-vgg16-transfer-learning/data


## installation
command to run pytorch with cuda :

```
pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu117
```


