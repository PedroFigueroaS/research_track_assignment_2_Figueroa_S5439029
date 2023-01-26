# research_track_assignment_2_Figueroa_S5439029
# ARP-ASSIGNMENT-2 Guide to Compile and run the project
GITHUB LINK OF THE PROJECT: https://github.com/PedroFigueroaS/research_track_assignment_2_Figueroa_S5439029
## Compiling the project

In the ros main file run in the terminal

```console
catkin_make
```


## Running the project

To run the program run the following command in a terminal

```console
roslaunch assignment_2_2022 nodes.launch 
```
This command will search for the launch file in the assignment_2_2022 repository, and will execute the nodes.launch file, that executes the main program for the simulation of the
virtual environment, and will call the programs: nodeA.py, nodeAmsg.py, nodeB.py, and nodeC.py to execute.

To finish the process, in the terminal where the launch programm was run, use the Ctrl+C command to kill the master, and kill the other process. To kill the nodeA.py process
enter a value different of 1 and 2, and will kill the program aswell.

