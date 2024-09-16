human has a natural ability to recognize any photo but it is not the same for the computer.
simply as hand written digit numbers the computer can not recognize them.
so the preceptrons is an artificial neuron that can give it different inputs with different weights and each preceptron has its own thresshold.
changing in the value of input weight and the threshold value change in the value of output (prediction).
bias =-threshold , so ∑ w.x>threshold=∑w.x +b>0.
if the previous equation <=0 output is 0 and if >0 output is 1.
perceptron network can also used as an nand gate.
perceptron was difficult to solve some problems so Sigmoid neurons was invinted.
different between the that the output of Sigmoid neurons can be a decimel number between 0 and 1 so by changing in the input it causes small changes in the output that is helpful in prediction.
σ(w.x+b)= 1/(1+e^(w.x+b)).
the leftmost layer in this network is called the input layer (input neurons), The rightmost is output layer (a single output neuron). The middle layer is called a hidden layer.
the way of designing networks if the image is 64x64 image therefore there will be 4096 input neuron.
if the ouput is less than 0.5,so it is not what we want to predict.
feedforward neural networks their output from one layer is used as input to the next layer.
Recurrent Neural Networks their neurons can influence each other over time.
recognizing handwritten digits can be divided into two tasks: segmenting an image of multiple digits into individual digit images, and classifying each digit.
//////////////////////////////////////////////////////////////////
the scratch Implementation is manual,less efficient and hard but the TensorFlow is easier, more powerful and faster.
