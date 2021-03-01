# Time delays in neural system
Some code from my master thesis project - to be updated 

Conduction delays are typically ignored in computational models of networks of interacting neurons or populations of neurons. Here we use two models that highlight the role that delays have on maintaining neural communication significant and efficient:

- in "SDDEs-variance", we solve a system of coupled stochastic delay differential equations (SDDEs) with a revisited Euler method, then we try to shed light on the demonstration that an homogeneous distribution of delays is favorable, as it is responsible for maximizing the activity of neurons charged with the integration of information coming from afferent neurons. So we are looking for a variance of the mean activity that decrease as the variance of the delays increases;

- in "model for myelin plasticity" we derive a new learning rule for modelling white matter plasticity: this kind of brain plasticity is responsible for adjusting conduction velocities and then for calibrating time delays. In this way, signals from one brain region can reach the others ideally all together, improving neural communication 

