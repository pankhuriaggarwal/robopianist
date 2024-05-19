# RoboPianist: High-Dimensional Robotic Control of Bi-Dexterous Shadow Hands

In this project, we focus on training robotic control for a bi-manual high-dimensional task-playing the piano with shadow hands. We use two off-policy methods, namely Twin Delayed
Deep Deterministic Policy Gradient (TD3) and Soft Actor-Critic (SAC). The objective of our project is to train agents to learn optimal policies for three bi-manual musical pieces of varying note patterns and complexity, namely - C major scale, D major scale, and Nocturne Rousseau. We integrate the RoboPianist and NanoRL implementations to simulate the piano, robotic hands, and musical elements using the Piano, Hand, and Sound RoboPianist models and the NanoRl framework. We also study the impact of different hyperparameters in optimizing the policy learning process, specifically fine-tuning pitch shifts and temporal shifts. Furthermore, we experiment with alternate key representations to reduce dimensionality and speed up the training process. Our results show that TD3 outperforms SAC across all songs, with higher reward returns and faster convergence. Furthermore, we find that pitch shifts have no impact on performance but increasing temporal note stretches help nearly double reward returns. Finally, utilizing a smaller piano key representation range for certain songs, that span under three octaves, results in similar policy performance but with faster training speed and reduced computational costs. Overall, this research helps us advance the field of bi-dexterous robotic control. The insights of our research can be leveraged to ultimately improve other areas of robotic control for bi-manual dexterous tasks that rely on similar levels of precision and fluidity of robotic hand movements such as surgery and manufacturing.

A quick summary can be obtained using the project poster (poster.pdf). For a more detailed explanataion, look at the project report (final_report.pdf).

<p align="center">
  <img src="poster.pdf" width="1000" title="hover text">
</p>

