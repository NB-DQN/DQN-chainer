## DQN-chainer in CPU

## Requirements

* Python
* Numpy
* Scipy
* Chainer
* RL-glue core
* RL-glue Python codec
* Arcade Learning Environment 0.4.4
* breakout.bin

## How to Install
### Chainer

```
pip install chainer
```

see also https://github.com/pfnet/chainer

### RL-glue
Download and install
https://sites.google.com/a/rl-community.org/rl-glue/Home/rl-glue

### RL-glue python codec
1 Download
https://sites.google.com/a/rl-community.org/rl-glue/Home/Extensions/python-codec

2 Install

```
cd /path/to/python-codec/src
python setup.py install
```


### Arcade Learning Environment (ALE) 0.4.4
1 Download
http://www.arcadelearningenvironment.org/downloads/

2 Inside makefile.unix, change the followings

```
USE_SDL := 1 
USE_RLGULE := 1
```


3 Setup (zlib, libsdl, libsdl-gfx and libsdl-image are required)

```
cd /path/to/ale_0.4.4/ale_0_4
cp makefile.unix makefile
make
```


### breakout.bin
1 Download
http://www.oldgames.sk/en/game/breakout/download/8314/

2 Modify the name from Breakout.bin to breakout.bin

## How to run
https://github.com/ugo-nama-kun/DQN-chainer/blob/master/readme.txt
