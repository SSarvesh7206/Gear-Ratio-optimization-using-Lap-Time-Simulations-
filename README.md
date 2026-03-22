In this project, a quasi steady state lap time simulator is developed in MATLAB, and this model is employed to find the optimal gear ratio amongst a given range of gear ratios.
The idea is that, as the gear ratio increases, the torque gets multiplied by the gear ratio, but the rpm gets divided by the gear ratio, thus, needing to find a sweet spot balancing the torque and rpm needs.
So, to acheive this, a quasi steady state lap time simulator is built.
A quasi steady state lap time simulator assumes the car to be a point mass and simulates an ideal lap around the track.
The lap times from this model is not reliable as, it has many ideal assumptions, but the primary use of this model is to estimate the effects of changes in critical parameters of the car.
In reality, changing gear ratios and testing physically is a tedious process, but with this model, we can get an idea of how the lap time/ performance of the car shall vary with the varying gear ratios, thus helping us find the optimal gear ratio, in a very easy and efficient process.
In this project, the parameter of gear ratio is of prime importance and is being tested, but, with this model, you can also check the effects of varying critical parameters of the car like aerodynamic drag/downforce coefficients.
This model also helps in understanding the effects of any new parts that is supposed to be manufactured beforehand, by checking how the lap time simulations perform.
The code files attached are:
Gear_optimization.mlx-Has the track, car initialization and the optimization loop to find the gear ratio.
simulate_lap.mlx-Has the core logic behind the lap time simulation, by running forward and backward passes to get the optimal speeds at each specifically defined points on the track.
