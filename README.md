# Sophia: Explaination and Expriments

We will reimplement Sophia-G optimizer from the paper available at https://arxiv.org/abs/2305.14342 and the GPT-2 training scripts on Google Colab.
A big thank you to Liu Hong, Li Zhiyuan, Hall David, Liang Percy, and Ma Tengyu for their hard work on this project 👏!

@article{liu2023sophia,
 title={Sophia: A Scalable Stochastic Second-order Optimizer for Language Model Pre-training},
 author={Liu, Hong and Li, Zhiyuan and Hall, David and Liang, Percy and Ma, Tengyu},
 journal={arXiv preprint arXiv:2305.14342},
 year={2023}
}

# Simpleply explaination

# Experiment
GPT-2 was trained on OpenWebText with Sophia and Adam with one A6000 - 48GB GPU, 32GB and 7 cores CPU

![Timestep/Loss of training process](./Assets/timestep-loss-train.png)
![Timestep/Loss of valuating process](./Assets/timestep-loss-val.png)
![Time/Loss of training process](./Assets/time-loss-train.png)

# Explaination 
![](./Assets/sophia-motivation.png)
![](./Assets/sophia-solution.png)
![](./Assets/ema-diagonal-hessian.png)
![](./Assets/pre-coordinate-clipping.png)

