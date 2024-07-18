# SuperMarioBros using RL
This is a Mario game where we use reinforcement learning to teach the computer to play on its own and clear the first level independently.

## Setup
To access all of the files I recommend you fork this repo and then clone it locally. Instructions on how to do this can be found here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

The other option is to click the green "clone or download" button and then click "Download ZIP". You then should extract all of the files to the location you want to edit your code.

Installing Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html.

Installing Gym-super-Mario-bros: https://pypi.org/project/gym-super-mario-bros/

Installing OpenAI: https://pypi.org/project/python-openal/

## About This Project :
In Super Mario Bros Reinforcement Learning Project! We use the **`gym-super-mario-bros environment`**, an OpenAI interface for the classic Super Mario Bros game, to explore and implement reinforcement learning techniques.

- **Environment Setup:** We start by installing and setting up the  `gym-super-mario-bros` environment and other necessary Libs. This allows us to simulate the original Super Mario Bros game within our reinforcement learning framework.

```bash
pip install JSAnimation
pip install gym-super-mario-bros
import numpy as np
import matplotlib.pyplot as plt
from JSAnimation.IPython_display import display_animation
from matplotlib import animation
from collections import deque
%matplotlib notebook
```
- **Movement Configuration:** Instead of incorporating all possible movements, we simplify our approach by using only 7 basic movements, known as `simple-movements`.  
```bash
from nes_py.wrappers import JoypadSpace
import gym_super_mario_bros
from gym_super_mario_bros.actions import SIMPLE_MOVEMENT
```
- **Reinforcement Learning Implementation:**

   - **Q-Learning and Double Q-Learning:** We implement both Q-learning and double Q-learning algorithms to train our agent.
    - **Action Selection:** The agent uses an epsilon-greedy action selection strategy to choose its next move based on the given policy.
    - **Loss Calculation and Minimization:** Throughout the training process, we calculate and minimize the loss, updating the target as necessary.
 - **Training and Evaluation:**

    - **Model Training:** The algorithm is run multiple times to improve the model's accuracy.
    - **Progress Tracking:** We keep track of the training progress, ensuring that our model is consistently improving

- **Final Model:** After extensive training and evaluation, we present the developed model, showcasing its ability to play Super Mario Bros using reinforcement learning techniques.
## 🔗 Links
[![my_portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/vedantrao63)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vedant-rao-09791a216/)


