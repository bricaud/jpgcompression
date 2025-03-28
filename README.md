# Python example code to perform jpeg compression and uncompression.

Strongly inspired from [https://github.com/ghallak/jpeg-python](https://github.com/ghallak/jpeg-python)

The main Jupyter notebook is `jpegcompression.ipynb`. This notebook contains the code for compressing and uncompressing an image in Jpeg.

It is possible to run the notebook with Google Colab. For that, click on this link [https://githubtocolab.com/bricaud/jpgcompression/blob/main/jpegcompression.ipynb](https://githubtocolab.com/bricaud/jpgcompression/blob/main/jpegcompression.ipynb) or click on this image: <a target="_blank" href="https://colab.research.google.com/github/bricaud/jpgcompression/blob/main/jpegcompression.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

**Exercise:** 
1. Identify the steps of the jpeg compression process in the Jupyter notebook. Match each step with what we have seen in the lecture.
2. Find the parameter controlling the compression rate. Change it and observe the change on the uncompressed image quality and on the size of the compressed file.
3. Find the DCT coefficients of the image patches in the code. Set the high frequency components to zero and check the resulting decoded image. Does it looks blurry? Hint: try to find them after the "zigzag" step.

**Other resources:**
- [https://github.com/jenkins-baruch/python-JPEG](https://github.com/jenkins-baruch/python-JPEG)
- [https://github.com/camilanovaes/jpeg-codec](https://github.com/camilanovaes/jpeg-codec)
