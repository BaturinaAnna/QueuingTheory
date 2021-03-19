# QueuingTheory

Simulated model M/M/1/$'\infty'$ from queuing theory. 

#### Short definition: 
An infinite queue in a system with one server, where arrivals are determined by a Poisson process, and the job servicing time has an exponential distribution. (More detailed mathematical definition of the model can be found at the beginning of the code file)

#### Main goals:
 - Simulate the operation of the system with various parameters ($'\lambda'$ (arrival rate), $'\mu'$ (departure rate), time of simulation)
 - Calculate various characteristics of the queuing system and compare their practical values obtained during the simulation and theoretical, that is, derived from the stationary distribution of a given model.

#### Results:
(The results can be seen more clearly in the graphs in the code file)
 - As expected, with an increase in the simulation time of the system, when the condition for the existence of a stationary distribution is satisfied, the practical values of the characteristics tend to the theoretical ones, since the system enters a stationary mode.
 - When the condition for the existence of a stationary distribution does not satisfied, the system leaves the normal mode, since the queue only grows with the growth of the system operation time 
