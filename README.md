# Fast Fourier Transformation with Python and Numpy

<p>In this Github Repository you can see how a Fast Fourier Transformation is implement via using the numpy library for faster array and matrix calculations. The code contains a couple of examples for transforming arrays and matrices. The implementations of the FFTs are based on the explanations of the Book "Introduction to Numerical Analysis"[1}.</p>

## The code contains:

- FFT for arrays
- iFFT for arrays
- FFT2D for matrices
- iFFT2D for matrices

## Local Installation

### Clone the repo
```shell
git clone https://github.com/JanMarcelKezmann/Fast-Fourier-Transformation-with-Python-and-Numpy.git
```

### Install requirements
##### (navigate into the new folder)

```shell
pip install -r requirements.txt
```

Make sure you have the following installed:
- keras
- numpy
- matplotlib

### Run with JupyterNotebook or JupyterLab
<p>Just open the .ipynb code in a Notebook of your choice and run it.

### Results

<p>The code always compares the received transformation with the correct one given by Numpy. For all implemented FFTs the code works just as well as it should. Anyway it is clearly visible in the last example that the code is lacking speed. This is due to the slow speed of Python as well as the used algortihm.</p>

<p align="center">
    <img src="https://user-images.githubusercontent.com/50111329/68669154-2b46cb00-054a-11ea-8d44-5e221438fcd7.png" width="600px" alt="">
</p>


## References

- [1] Introduction to Numerical Analysis, J. Stoer & R. Bullisch, Springer, 2nd edition
