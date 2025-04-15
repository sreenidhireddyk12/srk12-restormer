# image restoring using Restormer

## 📌 Overview
## 📌 Overview
This project explores how Restormer, a deep learning model, optimizes image restoration using transformer-based methods instead of traditional CNNs.  
Restormer outperforms prior methods in denoising, defocus deblurring, motion deblurring, and deraining tasks while maintaining computational efficiency.


## steps
- Uploaded a rainy image(user input) on Google Colab(from the original authors)    
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
All the code and pretrained models and sample images used in this project were created by:  
**Syed Waqas Zamir and Aditya Arora and Salman Khan and Munawar Hayat and Fahad Shahbaz Khan and Ming-Hsuan Yang**
- Original Repo:[Restormer github] (https://github.com/swz30/Restormer)  

I take **no credit** for the model architecture, training, or dataset. All work belongs to the respective authors mentioned above.

### 📚 Citation
```bibtex
@inproceedings{Zamir2021Restormer,
    title={Restormer: Efficient Transformer for High-Resolution Image Restoration}, 
    author={Syed Waqas Zamir and Aditya Arora and Salman Khan and Munawar Hayat 
            and Fahad Shahbaz Khan and Ming-Hsuan Yang},
    booktitle={CVPR},
    year={2022}
}


##  License

This project includes original code, weights, and sample images from the [Restormer GitHub repository](https://github.com/swz30/Restormer), which is licensed under a custom **Academic Public License**.

🔸 Permissions: Non-commercial use, modification, and distribution are allowed with proper credit.  
🔸 Limitations: Commercial use is prohibited.  
🔸 Conditions: You must retain the original license and attribution.

Please refer to their [LICENSE.md](https://github.com/swz30/Restormer/blob/main/LICENSE.md) for full terms.

## Disclaimer
This repository is strictly for educational purposes.  

All credits for the model, training, architecture, sample images, and pretrained weights go to the original authors.  
No modifications were made to the original model architecture or training pipeline.

The intention is to understand the inference workflow and experiment with image restoration outputs.



