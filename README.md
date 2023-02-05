# Classification-of-Colorectal-Polyps-on-Histopathological-Images
Paper: Improved Classification of Colorectal Polyps on Histopathological Images with Ensemble Learning and Stain Normalization

This notebook implements the article titled "Improved Classification of Colorectal Polyps on Histopathological Images with Ensemble Learning and Stain Normalization"

Here an ensemble model is built to perform polyp classification on colon histopathology image. Ensemble model is composed of two base models which are variants of ConvNeXt.
The base models are: ConvNeXt-Base and ConvNeXt-Tiny

The experiments are performed on non-normalized dataset as well as Stain normalization applied datasets. The stain normalized datasets are curated by employing the StainTools library (https://staintools.readthedocs.io/en/latest/). The Stain-Net and Stain-GAN methods are implemented by using their source codes. 

Stain_Net: https://github.com/khtao/StainNet,  
Stain-GAN:https://github.com/xtarx/StainGAN

##### Author of the code: Sena Yengec-Tasdemir

## Requirements


*   The dataset need to be uploaded to Google Drive folder. The following paths need to be updated accordingly.
*   Wandb is used for plots. One needs to either have a Wandb account or remove those lines of code.
