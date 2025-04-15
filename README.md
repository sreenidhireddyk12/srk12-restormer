# image restoring using Restormer

## 📌 Overview
This project explores how Restormer is a  deep learning model that optimizes image restoration using transformer based method insead of traditional Cnns .Restormer outperforms prior methods in denoising,defocus-deblurring,motion-deblurring and derainingtasks while maintaining computational efficiency.

## steps
- Uploaded a rainy image on Google Colab (user input)  
- Used a pre-trained image deraining model (from the original authors)  
- Observed the derained output  
- Understood the pipeline of preprocessing → model inference → postprocessing

##  Objective
To **learn and understand**:
- How deep learning models process images  
- How pretrained models are used  
- The general workflow of an image-to-image translation task

##  Sample Images
The sample rainy and clean images used in this project are from the sample dataset(original repo samples). These were included in the original GitHub repository by the authors and are used here **strictly for educational purposes**.

##  Credits
**Model and Code**:  
All the code and pretrained models used in this project were created by:  
[Syed Waqas Zamir and Aditya Arora and Salman Khan and Munawar Hayat and Fahad Shahbaz Khan and Ming-Hsuan Yang]
- Original Repo: https://github.com/swz30/Restormer  

I take **no credit** for the model architecture, training, or dataset. All work belongs to the respective authors mentioned above.

@inproceedings{Zamir2021Restormer,
    title={Restormer: Efficient Transformer for High-Resolution Image Restoration}, 
    author={Syed Waqas Zamir and Aditya Arora and Salman Khan and Munawar Hayat 
            and Fahad Shahbaz Khan and Ming-Hsuan Yang},
    booktitle={CVPR},
    year={2022}
}

## Disclaimer

This repository is for educational purposes. All credits for the model and weights go to the original authors. No modifications were made to the model architecture or training pipeline.
The intention is to understand the workflow and experiment with image input/output.
