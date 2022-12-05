# Mountain-car
<h2> Problem</h2>
We solve the Mountain car problem with GYM, The car starts in between two hills. The goal is for the car to reach the top of the hill on the right. The car does not have enough engine power to reach the top of the hill by just accelerating forward. To win, the car must build momentum by swinging itself backwards and forwards until it has enough speed to reach the flag.
<hr>
<h3>Agent, Action, Environment, State</h3>
- The car is our reinforcement learning agent. It interacts with the environment taking actions; playing the game.
- The environment is quite simple, and we only need to know two things about the car at every state, these are its position and its velocity. The problem is two    dimensional, and so is its state space (the space with all possible positions and velocities), we used GYM.
- The car only has 3 possible actions at every state, it can either accelerate forwards, accelerate backwards, or do nothing. Every time the agent takes an action, the environment (the game) will return a new state (a position and velocity).
<hr>
<h2>Algorithms:</h3>
