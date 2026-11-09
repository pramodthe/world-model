# What is a world model?

A world model is a learned model of how an environment works. Given the current state and an action, it predicts what happens next.

Core pieces:

- **Encoder**: compresses raw observations (e.g. images) into a compact latent state
- **Dynamics model**: predicts the next latent state from the current state and action
- **Reward / outcome model**: predicts how good a state is
- **Policy / planner**: picks actions, often by "imagining" rollouts inside the model

Why it matters: an agent with a world model can try things in its head instead of in the real world, which is cheaper, faster, and safer.

## My notes

-
