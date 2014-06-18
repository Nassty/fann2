fann2
=====

Python bindings for Fast Artificial Neural Networks 2.2.0 (FANN 2.2.0).


DESCRIPTION
===========
This is a python binding for FANN 2.2.0
(http://sourceforge.net/projects/fann/files/fann/2.2.0/FANN-2.2.0-Source.zip/download)
Install FANN 2.2.0 before this binding.

USAGE
=====
Just 

>> from fann2 import libfann 

and then create libfann.neural_net and libfann.training_data objects

>> ann = libfann.neural_net()
>> train_data = libfann.training_data()

Look at the examples at the FANN documentation and its 
C++ bindings for further reference.
