# Lab 1, Numpy and Vectorization

We will refer to [this](https://www.labri.fr/perso/nrougier/from-python-to-numpy/) book and try to cover it's Code Vectorization part extensively. <br>
This lab is motivated by 3 examples - 
- Uniform vectorization (through the game-of-life problem)
- Temporal Vectorization (by generating the Mandelbrot set of complex numbers)
- Spatial vectorization (by implementing boids)

Apart from this, we encourage you to go through <a href="https://arxiv.org/pdf/2009.06489.pdf">The Hardware Lottery </a>(especially section 3) to motivate this lab (purely for fun, like this lab xD). <br><br>

Also on a tangential note, because the assignment involves 2D convolutions, I am uploading cython code from the amazing <a href="http://cs231n.stanford.edu/">cs231n</a>'s assignments in the `cython` folder (It also has the backward functions, for max_pool as well!), I have only tested it for python 3.6 though.

### Take-home assignment - Implementing a vectorized 2D convolution!

[Feedback Form](https://forms.gle/C5M8PUa133ZsR5H87)

Quick links,
- `life.ipynb` - [![colab_logo](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/karannb/bits-f464-labs/blob/main/Lab1/life.ipynb)
- `spatial_TODO.ipynb` - [![colab_logo](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/karannb/bits-f464-labs/blob/main/Lab1/spatial_TODO.ipynb)
- `Mandelbrot_TODO.ipynb` - [![colab_logo](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/karannb/bits-f464-labs/blob/main/Lab1/Mandelbrot_TODO.ipynb)
- `Conv2D_TODO.ipynb` - [![colab_logo](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/karannb/bits-f464-labs/blob/main/Lab1/Conv2D_TODO.ipynb)
