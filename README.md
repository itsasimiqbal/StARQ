# ```StARQ: brainStem Automated Registration and Quantification```
  
<p><a href="[https://github.com/itsasimiqbal/StARQ](https://colab.research.google.com/drive/19vQyB9K3jokDSuh9qWAbjBJ8sacyQs2M)"><img src="https://github.com/itsasimiqbal/StARQ/blob/main/StARQ_logo.svg" align="center" width="330" height="215" /> </a>
</p>

![alt text](https://github.com/itsasimiqbal/StARQ/blob/main/GitHub_StARQ.png)

StARQ is an open-source software for automated segmentation and quantification of the brainstem structures in imaging data. StARQ is written in Python and built with PyTorch.

## ```Features```
```
- Automated segmentation of the brainstem structures in 2D images
- Calculation of quantitative measures such as cross-sectional areas for brainstem and signal quantification
- Interactive visualization of the results
```

## ```Usage```
To use StARQ, you will need to have a set of mouse brainstem images in .tif format (with registration and signal channels). Once your data is prepared, you can run StARQ by executing the following scripts: 

### ```Run on custom dataset```
Run this Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itsasimiqbal/StARQ/blob/main/Inference_StARQ_2_0_2024.ipynb) to load your custom image data (.tif files with registration and signal channels) from Google Drive and pass it to the trained deep learning model and save your signal quantification results.

### ```Finetune on custom dataset```
Run the Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/itsasimiqbal/StARQ/blob/main/StARQ_2_0_2024.ipynb) to test it on a sample mouse brainstem imaging data as well as finetune on your custom data. The input_directory should be changed with your data, and output_directory should be the directory where you want the results to be saved.

## ```Contributing```
If you are interested in contributing to StARQ, please fork the repository and submit a pull request. We welcome contributions of bug fixes, new features, and improvements to the documentation.

## ```License```
```
StARQ is released under the MIT License.
```
