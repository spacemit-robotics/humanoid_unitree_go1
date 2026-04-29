cmake_minimum_required(VERSION 3.16)
project(humanoid_unitree_go1)

install(PROGRAMS
    scripts/run_driver_go1.sh
    scripts/run_control_go1.sh
    scripts/run_hmi_go1.sh
    scripts/run_sim2sim_go1.sh
    scripts/download_models_go1.sh
    DESTINATION bin
)
