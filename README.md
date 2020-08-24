# Contains the models, world and launch files for the IMAV19 simulation

## How to use

Clone this repo in the src directory of a catkin workspace

Run `catkin build imav_sim` to first build the repo using the catkin

To launch the sim run `roslaunch imav_sim three_firefly.launch`

### The launch directory contains:

1. **spawn.launch**: Used to spawn individual quad (_used in spawn_firefly.launch file_)
2. **spawn_firefly.launch**: Main launch file containing the nodes as well as commands for spawing the quads

## Additional Info

### Three quads included are:

1. `Icarus`
2. `Vega`
3. `Magnus`

### Nodes included are(_package names provided instead_):

1. `mav_nonlinear_mpc`
2. `mav_lowlevel_attitude_controller`
3. `rotors_gazebo`
