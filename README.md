# Safe Reninforcement Learning:
  * Key question:
  
## Papers:

* [Safe Learning of Regions of Attraction for Uncertain, Nonlinear Systems with Gaussian Processes](https://arxiv.org/pdf/1603.04915.pdf)
   * Key idea: This paper considers an approach that learns the region of attraction (ROA) from experiments on a real system, without ever leaving the true ROA and, thus, without risking safety-critical failures. Based on regularity assumptions on the model errors in terms of a Gaussian process prior, it uses an underlying Lyapunov function in order to determine a region in which an equilibrium point is asymptotically stable with high probability. Moreover, it provides an algorithm to actively and safely explore the state space in order to expand the ROA estimate.
   
  * [Video](https://www.youtube.com/watch?v=bSv-pNOWn7c)
  
   
* [Safe Model-based Reinforcement Learning with Stability Guarantees](https://arxiv.org/pdf/1705.08551.pdf)
   * Key idea:
   
* [A Lyapunov-based Approach to Safe Reinforcement Learning](https://arxiv.org/pdf/1805.07708.pdf)
   * Key idea: This paper derives algorithms under the framework of constrained Markov decision problems (CMDPs), an extension of the standard Markov decision problems (MDPs) augmented with constraints on expected cumulative costs. The approach is based on a novel Lyapunov method. It defines and presents a method for constructing Lyapunov functions, which provide an effective
way to guarantee the global safety of a behavior policy during training via a set of local, linear constraints.
   
* [Safe Exploration for Optimization with Gaussian Processes](http://proceedings.mlr.press/v37/sui15.pdf)
   * Key idea:
   
* [Learning-based Model Predictive Control for Safe Exploration and Reinforcement Learning](https://arxiv.org/pdf/1803.08287.pdf)
   * Key idea: The papers combines ideas from robust control and GP-based RL to design a MPC scheme that recursively   guarantees the existence of a safety trajectory that satisfies the constraints of the system. Particularly, it uses a novel uncertainty propagation technique that can reliably propagate the confidence intervals of a GP-model forward in time.
   
* [Safe Exploration in Finite Markov Decision Processes with Gaussian Processes](https://arxiv.org/pdf/1606.04753.pdf)
   * Key idea: This paper defines safety in terms of an, a priori unknown, safety constraint that depends on states and actions. The algorithm cautiously explores safe states and actions in order to gain statistical confidence about the safety of unvisited state-action pairs from noisy observations collected while navigating the environment. Moreover, the algorithm explicitly considers reachability when exploring the MDP, ensuring that it does not get stuck in any state with no safe way out.
   * [Video](https://www.youtube.com/watch?v=dHHh7CZQM_M)
   
## Survey papers:

* [Planning and Decision-Making for Autonomous Vehicles](https://www.annualreviews.org/doi/abs/10.1146/annurev-control-060117-105157)

* [A Comprehensive Survey on Safe Reinforcement Learning](http://jmlr.org/papers/volume16/garcia15a/garcia15a.pdf)

## Lectures:

* [Safe Reinforcement Learning - Stanford CS234](https://web.stanford.edu/class/cs234/slides/2017/cs234_guest_lecture_safe_rl.pdf)

* [High Confidence Off-Policy Evaluation (HCOPE) - CMU 15-889e](http://www.cs.cmu.edu/~ebrun/15889e/lectures/thomas_lecture1_2.pdf)
   


 
