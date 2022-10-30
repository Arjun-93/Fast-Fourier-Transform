# Discrete Fourier Transform Vs Fast Fourier Transform

Here I have done a Discrete fourier and Fast Fourier Implementation 

A fast Fourier transform (FFT) is an algorithm that computes the discrete Fourier transform (DFT) of a sequence, or its inverse (IDFT). Fourier analysis converts a signal from its original domain (often time or space) to a representation in the frequency domain and vice versa. The DFT is obtained by decomposing a sequence of values into components of different frequencies. The Discrete Fourier Transform can be written as follows :

![image](https://user-images.githubusercontent.com/88470385/198864211-8b6e6de9-18f0-475b-afde-2a946559fe9a.png)


As the name implies, the Fast Fourier Transform (FFT) is an algorithm that determines the Discrete Fourier Transform of an input significantly faster than computing it directly. The FFT reduces the number of computations needed for a problem of size N from O(N^2) to O(NlogN).

![image](https://user-images.githubusercontent.com/88470385/198864225-6b6da636-91a4-4de6-a888-b72b1b7cbf13.png)

On the surface, this might not seem like a big deal. However, when N is large enough it can make a world of difference. Have a look at the following table.

![image](https://user-images.githubusercontent.com/88470385/198864238-4a996575-ae35-48f6-9440-32b93e7f2d69.png)

Here’s what it would look like if we were to use the Fast Fourier Transform algorithm with a problem size of N = 8. Notice how we have p = log(8) = 3 stages.
![image](https://user-images.githubusercontent.com/88470385/198864242-a1d66352-923f-43cc-9525-38a7df81f872.png)
