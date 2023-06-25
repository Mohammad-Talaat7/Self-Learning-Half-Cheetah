# Self-Learning-Half-Cheetah
this project is based on [Simple random search provides a competitive approach to reinforcement learning By Horia Mania, Aurelia Guy, Benjamin Recht research paper](https://arxiv.org/abs/1803.07055)

The incredible Augmented Random Search (ARS) algorithm empowers our model to master the art of walking, emulating the graceful movements of a half cheetah.

The true beauty of this model lies in its elegant simplicity. It sidesteps unnecessary complexities and focuses solely on refining weights by continuously adapting to the rewards gained during simulations.

In contrast to the prevailing reinforcement models, which predominantly explore the action space using gradient descent algorithms and deep learning, our groundbreaking approach delves into the uncharted territory of policy space. By employing straightforward finite differences and leveraging shallow learning techniques, our ARS model boasts a remarkable speed boost of up to 15 times and attains superior rewards in specific applications.

Moreover, our versatile model harnesses the power of pybullet environments, extending its capabilities beyond the realm of the half-cheetah. With minimal adjustments to key parameters, it can seamlessly adapt to various other environments, opening doors to limitless possibilities.

Our model will learn to walk starting form this:
![](https://github.com/Mohammad-Talaat7/Self-Learning-Half-Cheetah/blob/main/startState.gif)


All the way up to this:
![](https://github.com/Mohammad-Talaat7/Self-Learning-Half-Cheetah/blob/main/finalState.gif)

# Here are the libraries that we import and their respective purposes:
* os: This versatile library enables seamless interaction between our model and the underlying operating system. It empowers our model to perform essential tasks such as file and directory operations, providing a robust foundation for system-level interactions.

* numpy: A fundamental library for scientific computing, numpy equips our model with powerful mathematical capabilities. It offers a wide range of mathematical functions and efficient data structures, enabling advanced numerical computations and data manipulation.

* gym: As a popular open-source library, gym provides a wide range of environments for modeling and simulations. By utilizing gym, our model gains access to diverse scenarios and challenges, allowing us to train and evaluate our algorithms in a standardized and extensible manner.

* pybullet_envs: a module within the gym library that provides a collection of physics-based robotic simulation environments. It builds on top of the pybullet physics engine, which is a high-performance library for simulating rigid body dynamics and robotics.

### Notes

you need the following to be able to run the project:

* NumPy
* OpenAI Gym 0.10.5
* PyBullet 2.0.8
* Python 3
