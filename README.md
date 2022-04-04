# BETES

BETES (**B**aroclinic **E**kman **T**ransport **E**quation **S**olver) is a 1D numerical code to simulate wind-driven boundary layer currents. The BETES code computes the prototype system of ODE:

<img src="https://render.githubusercontent.com/render/math?math=\dfrac{\text{d}}{\text{d}z}\left(K\dfrac{\text{d}\mathbf{u}}{\text{d}z}\right) = -f\mathbf{u}^\perp - \dfrac{1}{\rho}\nabla p_a - \dfrac{g}{\rho}\int_z^0\nabla\rho\,\text{d}z">

in a water depth column, <img src="https://render.githubusercontent.com/render/math?math=0\leq z\leq-H">. 
