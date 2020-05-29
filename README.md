# RLFluidControl
reinforcement learning for active fluid control.

## Dependencies
CFD solver Lilypad is written in Processing by Dr. Gabriel Weymouth, and can be found: https://github.com/weymouth/lily-pad

Processing from https://processing.org/download/

Python Packages: TensorFlow 1.x (1.13+ suggested), numpy

## How to run

Start the server (RL agent) by run

```shell
$ cd server
$ python server.py -env CFD
```

Start the client (CFD environment):

Run **`clientCFD/clientCFD.pde`**  in Processing

