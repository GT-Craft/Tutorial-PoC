# PoC_MMSys24

This PoC is based on Ubuntu 22.04, The machine is supposed to have x86-based CPU and NVIDIA GPU (optional).

## Setup
#### 1. Python3 and Virtualenv
If you don't have Python3, install it. If you want to setup in a virtual environment for python, install virtualenv.
```bash
$ sudo apt install python virtualenv
```
#### 2. Unity3D and Unity USD SDK (project wise)
- Firstly, visit [the official Unity website](https://docs.unity3d.com/hub/manual/InstallHub.html#install-hub-linux) and install Unity Hub. Or, run the following commands from that website.
```bash
$ wget -qO - https://hub.unity3d.com/linux/keys/public | gpg --dearmor | sudo tee /usr/share/keyrings/Unity_Technologies_ApS.gpg > /dev/null
$ sudo sh -c 'echo "deb [signed-by=/usr/share/keyrings/Unity_Technologies_ApS.gpg] https://hub.unity3d.com/linux/repos/deb stable main" > /etc/apt/sources.list.d/unityhub.list'
$ sudo apt update
$ sudo apt-get install unityhub
```
- Then, visit [the Unity archive](https://unity.com/releases/editor/archive) and install Unity 2020.03.


## Map Streaming and Semantic Segmentation

## Virtual Scene Generation