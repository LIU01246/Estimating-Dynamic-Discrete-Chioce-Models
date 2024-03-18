# Estimating-Dynamic-Discrete-Chioce-Models

This project replicates the Nested Fixed Point Algorithm used by John Rust in his 1987 seminal paper "Optimal Replacement of GMC Bus Engines: An Empirical Model of Harold Zurcher”. Then, I estimate Rust's results using Bajari, Benkard, and Levin's (henthforce BBL, 2007) methods. 


One problem with Rust’s Nested Fixed Point algorithm is that for each parameter value $\theta$, we have to solve for a contraction mapping to compute EV for each $\theta$ value and then choose the $\theta$ value that maximizes the likelihood. This is computationally costly. Several papers attempt to improve the computational inefficiency of the Nested Fixed Point Algorithm proposed by Rust, such as Hotz, Miller (1993), Hotz, Miller, Sanders and Smith(1994), Aguirregabiria Mira (2007), and BBL (2007). Here we conduct the Nested Fixed Point Algorithm used by Rust and then, we try to implement the BBL estimator and make comparisons. 

The data used is "stata_rust_data.csv".

The exercises can be found in the Jyputer notebook "Rust-BBL Exercises.ipynb". 
