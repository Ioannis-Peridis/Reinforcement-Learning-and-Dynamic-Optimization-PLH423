# Reinforcement-Learning-and-Dynamic-Optimization-PLH423
These are the labs of the Course : Reinforcement-Learning-and-Dynamic-Optimization-PLH423

with professor : Thrasyvoylos Spyropoylos

from: Techincal University Of Crete

Implementation in Python: stochastic bandit environment with uniformly distributed rewards ,convergance speed/learnign rate, algorithms implemneted: ε-Greedy, Upper Confidence Bound

ASSIGNMENT:
You are required to program in Python (only) the following environment and algorithms:
Environment:
k stochastic bandits
Each bandit i has a reward that is uniformly distributed in [a_i, b_i].
a_i, b_i should be chosen randomly in [0,1] and must be different for each arm i.
Example, if a_i = 0.3 and b_i = 0.8 for arm i, then its reward at a given time can take any value in [0.3,0.8] with equal probability ("uniform") and its expected reward mu_i = 0.55
Algorithms:
ε-Greedy: assume ε_t gets reduced according to the theorem in the slides.
Upper Confidence Bound algorithm
Measurement Tasks:
Produce plots that prove or disprove the respective sublinear regret rates for each scheme
Compare the convergence/learning speed of the two algorithms for T = 1000, k = 10
Repeat  (2) for another two scenarios with different T,k values and comment on the differences similarities.
You need to hand in (online):

Your python notebook of the code
this must execute correctly, producing also the respective plots above
it must be commented in detail (follow the example notebook I uploaded) 
A short report (1-2 pages max) with your measurement plots and short comments for each
all plots should include axis titles, legends, etc., to be readable.
