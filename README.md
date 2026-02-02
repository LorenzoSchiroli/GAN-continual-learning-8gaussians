# Evaluation of Continual Learning approaches to mitigate mode collapse in Generative Adversarial Networks

[![Documentation preview](docs/Evaluation_of_Continual_Learning_approaches_to_mitigate_mode_collapse_in_Generative_Adversarial_Networks.png)](docs/Evaluation_of_Continual_Learning_approaches_to_mitigate_mode_collapse_in_Generative_Adversarial_Networks.pdf)

Research thesis for the Master’s degree in Computer Engineering, whose objective is to attempt to solve the mode collapse problem in GANs by applying Continual Learning methods to the discriminator.

Thanks to Experience Replay, the discriminator retains memory of the generator’s past modes, mitigating the mode collapse problem. The blue dots represent the generator’s distribution, the red dots are the samples stored in the Experience Replay buffer, and the green dots correspond to a two-dimensional distribution of 8 Gaussians.