# open AI gym playground 
some RL methodology on openAI gym

## OpenAI Gym
[OpenAI Gym 官方網址](https://gym.openai.com/docs/)
> Gym is a toolkit for developing and comparing reinforcement learning algorithms.

## Installation
```sh
# better run under virtualenv
$ git clone https://github.com/yuting-tseng/openAI.git
$ cd openAI
$ virtualenv --no-site-packages --python /usr/bin/python3 .venv
$ source .venv/bin/activate
$ sudo python -m pip install -r requirements.txt
```

使用Jupyter notebook
```
$ python -m ipykernel install --user --name openAI-env --display-name "Py36(openAI gym)"
```
Kernel location: `/Users/{username}/Library/Jupyter/kernels/`
