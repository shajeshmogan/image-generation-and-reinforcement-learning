# Deep Learning CA2

Singapore Polytechnic coursework covering image generation and deep reinforcement learning.

| Notebook | Experiment |
| --- | --- |
| [Part A](Part_A_Generative_Models.ipynb) | Compared a convolutional VAE and GAN on CIFAR-10, then tested class conditioning and evaluated the selected generator using FID and visual inspection. |
| [Part B](Part_B_DQN_Pendulum.ipynb) | Trained a deep Q-network on Gymnasium Pendulum with discrete torque actions and evaluated policies under four gravity settings. |
| [Part C](Part_C_Double_DQN_Analysis.ipynb) | Compared DQN and Double DQN across three paired seeds under matched conditions. Double DQN improved one seed but had lower mean reward for this configuration. |

The notebooks include saved results and figures. Model weights, generated image archives, and the source CSVs used by Part C are not included. Part C can be read with its saved results, but rerunning it requires those CSVs.
