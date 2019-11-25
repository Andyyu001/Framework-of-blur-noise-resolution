# Framework-of-blur-noise-resolution

1. a kernel with 2D can be changed as the tensor:
paper: Learning a Single Convolutional Super-Resolution Network for Multiple Degradations
code: https://github.com/2wins/SRMD-pytorch

2. inter 
paper: Douglas-Rachford Networks: Learning Both the Image Prior and Data Fidelity Terms for Blind Image Deconvolution


The framework of the image restoration:

we model $y=Hx+n$, and there are some cases as follows:
1.  H is an identity matrix, -----denoising
2.  H is denoted with Hx = h \otimes x, ------deblurring 
3.  H is a diagonal 0-1 matrix, ------inpainting
4. H is the composition of blurring and downsampling operator, -------super-resolution


