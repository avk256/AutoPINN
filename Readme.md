The project focuses on developing an open, object-oriented architecture for a library of neural network methods designed to solve boundary value problems.  

The importance of developing approximate methods for solving differential equations is highlighted by their widespread application in key scientific and engineering fields. Many physical phenomena can be mathematically described by differential equations, but obtaining analytical solutions is often challenging. As a result, numerical methods for approximate solutions play a crucial role in computer modeling and simulating the behavior of complex technical systems.  

Classical methods for solving boundary value problems, such as the collocation method, Galerkin method, and Ritz method, require the selection of basis functions to construct an approximate solution. However, an improper choice of basis functions can lead to inaccurate results. Moreover, increasing the number of basis functions to enhance accuracy often results in high computational complexity, particularly for large systems of differential equations.  

Physics-informed neural networks (PINNs) offer several advantages over classical methods in solving boundary value problems. First, neural networks enable the approximation of complex physical processes without requiring the selection of specific basis functions. Second, they can automatically identify nonlinear dependencies in the data, making them highly effective for modeling intricate physical phenomena. Additionally, neural networks can adapt to new data and problem conditions without the need to revise analytical approximations, providing greater flexibility across various scientific and engineering applications.  

Neural network methods are also highly effective for solving inverse problems, enabling the determination of system parameters or medium properties based on measurements or observations. In these cases, unknown constants of the inverse problem are introduced as parameters within the neural network and optimized during training.  

The proposed methods are validated using model problems in elasticity and mathematical physics.
