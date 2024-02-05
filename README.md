# TCFD_student_project
This is the code of the Student Project. Christian Cicala, Sofia Sancin Alfieri, Enrico Amodio.

Physics-informed neural network (PINN) is a recent advancement in the field of deep learning that leverages the power of neural networks (NNs) to solve differential equations 
and learn the underlying physics of a given problem. The purpose of the work is to create a PINN capable of integrating the physics behind the Navier-Stokes equations. To implement PINN for this problem, it was utilized Python with Pytorch library. The database consists of a million points (each of which contains a value of x, y, t, u, v and p), but only 1% of the data were used to train the model. Two different cases were considered: in the first, pressure data was shown to the network, in the second, it was not. Excellent results were obtained in both cases. However, PINNs are not to be considered as a replacement method for the numerical methods classes, but rather as an alternative. 
For this work the article by Raissi et al. was taken as a reference, albeit with some differences.
