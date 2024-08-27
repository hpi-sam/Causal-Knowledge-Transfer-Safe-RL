# Causal-Knowledge-Transfer-Safe-RL
Causal-Based Knowledge Transfer in Safe Reinforcement Learning

## Setup
1. Clone this repository.
2. Install Sumo https://sumo.dlr.de/docs/Installing/index.html
    * Remember to set your SUMO_HOME environment variable https://sumo.dlr.de/docs/Basics/Basic_Computer_Skills.html#sumo_home
    * Current Version: 1.20.0
3. Create a Conda Environment `conda create --name CKT-4-SafeRL`
    * Any other python environment should work too
    * Remember to activate the environment
4. Install Sumo Python Tools `pip install -r $SUMO_HOME/tools/requirements.txt`
5. Install SumoRL https://lucasalegre.github.io/sumo-rl/install/install/
    * Use `pip --version to check whether` the correct environment is used
    * the path should look similar to this: `/Users/username/miniconda3/envs/CKT-4-SafeRL/lib/python3.11/site-packages/pip`
    * `pip install sumo-rl`
6. Install Stable-Baselines3 https://stable-baselines3.readthedocs.io/en/master/guide/install.html
    * Use `pip install 'stable-baselines3[extra]'` (' required for some shells)
7. Install Tensorflow https://www.tensorflow.org/install
    * Use `pip install tensorflow`
      * There might be a dependency issue: ortools 9.10.4067 requires protobuf>=5.26.1, but you have protobuf 4.25.4 which is incompatible.
      * `pip install ortools==9.9.3963` fixes that
