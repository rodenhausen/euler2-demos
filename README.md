# euler2-demos

Each subfolder of this repository contains a demo. 

A demo has the following structure:
* `./run` the script that can replays the commands of the demo
* `./commands` the commands executed in the demo, organized in yaml format
* `./{anything else}` any output produced by the demo

commands example:

```
version:
 euler2 --version
help:
 euler2 --help
```
 
run examples:

* `./run` all: executes all commands of the demo in consecutive order
* `./run help`: executes the command labeled help
* `./run clean`: resets the demo to a state before any run execution


