# Particle Swarm Optimization vs Gradient Descent

* Algorithm - 
  1. PSO 
  2. Gradient Descent
* Benchmarks -
  1. [Rosenbrock Function](https://en.wikipedia.org/wiki/Rosenbrock_function)
  2. [Rastrigin Function](https://en.wikipedia.org/wiki/Rastrigin_function)

### Results - 
* PSO on Rosenbrock -
  * ![PSO on Rosenbrock](resources/Rosenbrock_PSO.gif "PSO on Rosenbrock")
  
* PSO on Rastrigin -
  * ![PSO on Rastrigin](resources/Rastrigin_PSO.gif "PSO on Rastrigin")

---
* GD on Rosenbrock - 
  * ![](resources/RosenbrockGD.gif)
  
* GD on Rastrigin - 
  * ![](resources/RastriginGD.gif)
  
## Experiment 1 - 
Running ~50 iterations of PSO and GD independently to generate probability distribution of error against density - 

<img src="resources/PSOvsGD.png" 
alt="PSO vs GD" width="600" height="600" border="10" />
  
## Observation 1 - 
While PSO is actively able to achieve the global minima or has very low error, Gradient Descent proves to be ineffective on the benchmarks mentioned.


## Experiment 2 - 
Effect of Error vs Number of particles in PSO - 

<img src="resources/ErrorVsNum.png" 
alt="PSO vs GD" width="600" height="400" border="10" />

## Experiment 3 - 
Effect of Inertia parameter('a') for velocity update as stated in State of Art - Linearly decreasing the parameter from 0.9 to 0.4 over the defined iterations.
<img src="resources/inertia.png"
alt="PSO vs GD" width="600" height="400" border="10" />

Therefore, we observer that while the error reduces with SOTA params, the difference is not really drastic.

## Created with - 
1. [Dhruv Rathi](https://github.com/dhruv2601)
2. [Justus Erker](https://github.com/Justus-Jonas)
3. [Caio Guirado](https://github.com/caioguirado)
