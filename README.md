# Navigation Project README - Bharat Raman

## Included Files
    Navigation.ipynb
    Banana.app
    checkpoint.pth
    Report.pdf
    README.md

## Dependencies
Follow the dependencies setup provied in [Udacity's Deep RL repository][unity]
## Modules used:
    UnityEnvironment from unityagents - For the environment from Unity ML-Agents
    numpy - for various array/math operations
    random - For sampling batches from experience tuples
    namedTuple, deque from collections -  data structures to store experience-tuples and memory in replay buffer
    torch - For pyTorch tensors and tensor-operations
     - torch.nn - For pyTorch's neural network module
     - torch.nn.functional - For activation functions for each layer in the neural network
     - torch.optim - optimizer for establishing weights/biases for layers
    matplotlib.pyplot - plotting scores per episode after training

## References
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
   