# Causal-Knowledge-Transfer-Safe-RL
Causal-Based Knowledge Transfer in Safe Reinforcement Learning

## Setup
1. Clone this repository.
2. Install Sumo https://sumo.dlr.de/docs/Installing/index.html
    * Remember to set your SUMO_HOME environment variable https://sumo.dlr.de/docs/Basics/Basic_Computer_Skills.html#sumo_home
    * Current Version: 1.20.0
3. Create a Conda Environment ```conda create --name CKT-4-SafeRL```
    * Any other python environment should work too
    * Remember to activate the environment
4. Install Sumo Python Tools ```pip install -r $SUMO_HOME/tools/requirements.txt```
5. Install SumoRL https://lucasalegre.github.io/sumo-rl/install/install/
    * Use pip --version to check whether the correct environment is used
    * the path should look similar to this: ```/Users/username/miniconda3/envs/CKT-4-SafeRL/lib/python3.11/site-packages/pip ```
    * ```pip install sumo-rl```
    * 
