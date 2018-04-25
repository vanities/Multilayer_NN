# Multilayer_NN
Multilayer neural network solving the XOR problem, that requires multilayers


Solving the XOR problem with a multilayer dense layer net:<br>
![XOR](https://github.com/vanities/Multilayer_NN/blob/master/images/XOR.png)<br>
From above, you can see that it took 3 ReLU units in a 2 dense layer network to solve the problem. 1024 epochs solved it ~39% of the time, with 2 never solving it. This is with the assumption that I may have needed more epochs to train, but I don't think it would have helped.
<br>
Smallest Number of Units: Adding up the units, 3+2= 5 units, we can safely say the network requires 5 units to learn the XOR problem


Then solving the MNIST with >98% accuracy, with Hyperbolic Tangent and rectified linear unit (ReLU) activation functions, 16 and 20 epochs respectively:<br>
![mnist](https://github.com/vanities/Multilayer_NN/blob/master/images/mnist.png)<br>
