## Abstract 

While reinforcement learning (RL) methods in existing literature can successfully solve many vision based tasks, it is often difficult to understand an agent's policy based on its visual input alone, without using dedicated tools for interpretability. In this paper, we investigate the use of self-attention to create agents that observe its environment similarly to how humans see our own world. By constraining agents to access only a small fraction of its visual input, we show that their policies are directly interpretable in pixel space. Furthermore, we demonstrate that neuroevolution is ideal for training self-attention architectures for RL tasks, because we can remove unnecessary complexity needed for gradient-based methods, resulting in a much simpler architecture, and also allowing us to incorporate modules that can include discrete, non-differentiable operations that are useful for our agent. We argue that self-attention has similar properties as indirect encoding methods, in the sense that large implicit weight matrices are generated from a small number of key-query parameters, thus enabling our agent to solve challenging vision based tasks with at least 1000x less parameters than existing methods. Moreover, since our agent learns to attend to only task critical visual hints, they are able to generalize to environments where task irrelevant elements are modified while conventional methods fail.

______

## Supplementary Videos

Below are additional videos that accompany the paper.
