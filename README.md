# ```StARQ: brainStem Automated Registration and Quantification```
  
<p><a href="[https://github.com/itsasimiqbal/StARQ](https://colab.research.google.com/drive/19vQyB9K3jokDSuh9qWAbjBJ8sacyQs2M)"><img src="https://github.com/itsasimiqbal/StARQ/blob/main/StARQ_logo.svg" align="center" width="330" height="215" /> </a>
</p>

![alt text](https://github.com/itsasimiqbal/StARQ/blob/main/GitHub_StARQ.png)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19vQyB9K3jokDSuh9qWAbjBJ8sacyQs2M)

StARQ is an open-source software for automated segmentation and quantification of the brainstem structures in imaging data. StARQ is written in Python and built with PyTorch.

## ```Features```
```
- Automated segmentation of the brainstem structures in 2D images
- Calculation of quantitative measures such as cross-sectional areas for sub-regionsa and signal quantification
- Interactive visualization of the results
```
Installation
To install StARQ, you will need to have Python and ANTs installed on your system. Once you have these dependencies installed, you can download the StARQ repository and run the installation script:

```python
git clone https://github.com/itsasimiqbal/StARQ.git
```
cd starq
```python
pip install -r requirements.txt
```
Usage
To use StARQ, you will need to have an brain images with labelled regions. Once you have an image, you can run StARQ by executing the Inference script. Run the Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19vQyB9K3jokDSuh9qWAbjBJ8sacyQs2M) script to test it on sample mouse brain imaging data. The input_directory should be changed with your data and output_directory should be the directory where you want the results to be saved. StARQ will generate a set of output files including the registered image, the segmentation mask, and the quantitative measures.

## ```Contributing```
If you are interested in contributing to StARQ, please fork the repository and submit a pull request. We welcome contributions of bug fixes, new features, and improvements to the documentation.

## ```License```
```
StARQ is released under the MIT License. See LICENSE.md for details.
```
