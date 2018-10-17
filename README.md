# Project Details
The agent navigates through the square and collects bananas. The goal is to learn how to collect yellow bananas and avoid the purple ones.

* States: 37
* Actions: 4 (forward, back, left, right)
* Rewards: +1 for picking a yellow banana, -1 for choosing a purple banana, 0 otherwise.

# Getting Started

Open Navigation.ipynb Jupyter notebook, it also contains a section on how to install the necessary dependencies.

Download the Banana environment (binary file) for your operating system and configure file_name variable (in Navigation.ipynb Jupyter notebook) to point to the location of the binary file.

* Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
* Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
* Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
* Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Install these python packages (could be done via Navigation.ipynb Jupyter notebook itself)

```
pip --quiet install unityagents
pip --quiet install torch
pip --quiet install numpy
pip --quiet install matplotlib
```

# Instructions

Open Navigation.ipynb Jupyter notebook and execute each code block to train the agent using DQN.
