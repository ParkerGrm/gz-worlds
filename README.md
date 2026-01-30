1. Place gz-worlds onto Desktop
2. Grab sdf from gz-worlds/gazebo_models/NAME/ and put into PX4_Autopilot/Tools/simulation/worlds/
3. Prompt the world to reference height map and image in the main folder:

        export GZ_SIM_RESOURCE_PATH="${GZ_SIM_RESOURCE_PATH}:${HOME}/Desktop/gz-worlds/gazebo_models"
        export IGN_GAZEBO_RESOURCE_PATH="${GZ_SIM_RESOURCE_PATH}"
