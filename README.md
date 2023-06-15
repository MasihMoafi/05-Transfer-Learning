Neural Style Transfer with PyTorch

This repository contains PyTorch implementations of neural style transfer, a technique that combines the style of one image with the content of another. Two different implementations are provided, one using VGG19 as the base model and another using a custom ResNet-based model.
Usage

    Install the required dependencies by running pip install -r requirements.txt.

    For VGG19-based style transfer, run the style_transfer_vgg19.py script. Adjust the file paths of the content and style images in the script to your own image locations.

python

python style_transfer_vgg19.py

    For ResNet-based style transfer, run the style_transfer_resnet.py script. Again, update the file paths of the content and style images in the script.

python

python style_transfer_resnet.py

Pretrained Models

The VGG19 model pretrained on ImageNet is automatically downloaded and used in the VGG19-based implementation.
Results

The generated stylized images will be saved to the specified file paths.
Acknowledgments

The neural style transfer code is adapted from the following sources:

    VGG19-based implementation: PyTorch Neural Style Transfer Tutorial
    ResNet-based implementation: Neural Style Transfer using PyTorch
