# A Discontinuity-Capturing PINNs for Parabolic Interface Problems

This repository will contain the code for the paper:

**"A Discontinuity-Capturing PINNs for Parabolic Interface Problems"**

In this article, a Physics-Informed Neural Network (PINN) is proposed to solve parabolic interface problems.  
We derive theoretical error bounds for neural network approximations of solutions to these problems.  
Due to the discontinuous nature of the solutions at the interface, a **discontinuity-capturing shallow neural network** is introduced as a surrogate model.  
Additionally, we incorporate the **Extreme Learning Machine (ELM)** approach as an efficient and innovative training strategy.  
The theoretical results are validated through several numerical examples, demonstrating the effectiveness of the proposed method.  
To further showcase the scalability of our approach, we also solve a **six-dimensional parabolic interface problem**.

---

### Dependencies

The code is written in **Python** and relies on the following libraries:
- [PyTorch](https://pytorch.org/) 
- [NumPy](https://numpy.org/) 
- [Matplotlib](https://matplotlib.org/) 

