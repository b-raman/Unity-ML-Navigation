# Navigation Project - Bharat Raman
## Deep Reinforcement Learning Nanodegree, Udacity

For this project, the agent will be navigating a walled-in plane scattered with yellow and blue bananas. For each time-step:
- A state consists of 37 elements, which represent the agent's velocity and its ray-based perception of objects around its forward direction.
- There are 4 possible actions: Move forward, move backward, turn left, turn right

If the agent reaches a yellow banana, it will recieve a reward of +1. If it reaches a blue banana, it will recieve a reward of -1. The goal of this project is to get the agent to attain a net-reward of at leat +13 by the end of an episode. The process to achieve this is discussed in detail in the report and notebook.

### Included Files
    Navigation.ipynb - All code for this project is in the notebook
    checkpoint.pth   - Contains saved weights for the best model
    Report.pdf       - Detailed report of the project
    README.md

### Dependencies
Follow the dependencies setup provied in [Udacity's Deep RL repository][unity]
### Modules used:
    UnityEnvironment from unityagents - For the environment from Unity ML-Agents
    numpy - for various array/math operations
    random - For sampling batches from experience tuples
    namedTuple, deque from collections -  data structures to store experience-tuples and memory in replay buffer
    torch - For pyTorch tensors and tensor-operations
     - torch.nn - For pyTorch's neural network module
     - torch.nn.functional - For activation functions for each layer in the neural network
     - torch.optim - optimizer for establishing weights/biases for layers
    matplotlib.pyplot - plotting scores per episode after training

### References
- [Udacity Deep learning repository][unity]
- [DQN Paper][dqn]
- [Double DQN Paper][double]
- [Prioritized Experience Replay Paper][per]
- [Dueling DQN Paper][dueling]
    


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [unity]: <https://github.com/udacity/deep-reinforcement-learning#dependencies>
   [dqn]: <https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf>
   [double]: <https://arxiv.org/abs/1509.06461>
   [per]: <https://arxiv.org/abs/1511.05952>
   [dueling]: <https://arxiv.org/abs/1511.06581>
   [ud]: <https://github.com/udacity/sagemaker-deployment/tree/master/Tutorials>
   [k3]: <https://www.kaggle.com/ash316/what-s-my-score>
