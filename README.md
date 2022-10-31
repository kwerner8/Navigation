[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

For this project, you will train an agent to navigate and collect bananas in a large, square world.  

![Trained Agent][image1]
There is a +1 reward for collecting a yellow banana and a -1 reward for collecting a blue banana, so the agent's goal is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity and ray-based perception of objects in the agent's environment in its forward direction. Given this information, the agent must learn how best to select actions. Four discrete actions are available, corresponding to the following:

- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and to complete the task, your agent must achieve an average score of +13 in 100 consecutive episodes.

### Getting Started

1. Download the environment from one of the links below.  You just need to choose the environment that fits your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

2. Place the file in the course's GitHub repository in the "p1_navigation/" folder and unzip (or decompress) the file. 
 

### Challenge: Learning from Pixels

If you have successfully completed the project and are looking for another challenge, you have come to the right place!  In this project, your agent learned from information such as its speed and ray-based perception of objects in its environment.  An even more difficult task would be to learn directly from pixels!

To accomplish this more difficult task, you will need to download a new Unity environment.  This environment is almost identical to the project environment, with the only difference being that the state is an 84 x 84 RGB image corresponding to the agent's first-person perspective.  (**Note**: Udacity students should not submit a project with this new environment).

You just need to select the environment that matches your operating system:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/VisualBanana_Windows_x86_64.zip)

Then place the file in the `p1_navigation/` folder in the course's GitHub repository and unzip (or decompress) the file.  Then open `Navigation_Pixels.ipynb` and follow the instructions to learn how to use the Python API to control the agent.
