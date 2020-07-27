# Quantum-Convolutional-Layers
Building a custom class of quantum convolutional networks for feature pre-processing. The code is direct implementaion of the paper "https://arxiv.org/abs/1904.04767". The goal of the paper is to achieve quantum advantage & prove a base work that can be further improved. 

Few papers such as "Supervised learning with quantum enhanced feature spaces Vojtech Havlicek1,∗ Antonio D. C ́orcoles1, Kristan Temme1, Aram W. Harrow2, Abhinav Kandala1, Jerry M. Chow1, and Jay M. Gambetta11IBM T.J. Watson Research Center, Yorktown Heights, NY 10598, USA and 2Center for Theoretical Physics, Massachusetts Institute of Technology, USA" have proven that quantum computing that utilizes the high dimensional hilbert space allows us to build complex kernel functions that can fit complex non linear datasets.

Similarly my work creates a general Quan2D class similar to a Conv2D class that provided features such as kernel_size, filter_numbers, padding, activation function, initializers etc. The current work provides following points:
  
  > Filter_size
  
  > filter_number
  
  > padding
  
  > stride
  
The goal for future is to add arguments :

  > Custom quantum encoding layer for mapping classical data to qubits.
  
  > Custom quantum circuit layer i.e. custom variational random circuit.
  
  > Custom decoding layer for mapping the quantum superposition states to classical data.
  
  > Fusing data for color images that contain 3 channels.
  
  

