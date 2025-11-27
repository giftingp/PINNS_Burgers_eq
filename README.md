# Physics informed neural networks to solve the 1d Burgers equation.

We implement Physics informed neural networks (PINNs) to solve 1d Burgers equation. We enforce governing PDE using a physical loss and also minimize the loss imposed by initial and boundary conditions. We provide a plot displaying the total training loss, additionally we showcase an animation of PINNs prediction compared to the exact solution at the initial condition. 

<div align="center">
  
  ![Training Loss](Training_loss.png)
  
</div>

<div align="center">
  <img src="https://github.com/giftingp/PINNS_Burgers_eq/blob/main/Burger_initial_condition.gif" alt="Burger initial condition">
</div>
