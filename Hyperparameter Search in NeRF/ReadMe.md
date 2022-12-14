# Tiny NeRF: 
This is a simplied version of the method presented in NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis wherein we refrain from hierarchical sampling and ignore 5D input including view directions. 

Download Tiny_NeRF.ipynb and import to Colab to run. 


# Implementation Details for Hyperparameter Search: 

# Step 1: 
Download the Hyperparameter_Optimization_on_a_NeRF.ipynb file. 

Run in Colab. 

Set the Runtime to: 

*Hardware Accelerator* - GPU 

*GPU Class* - Premium

*Run Time* - High RAM

We used Colab Pro version, had access to A100-SXM4-40GB GPU, in a 'High-RAM' environment. (paid $9.99/month). 

# Step 2: 
The visualizations can be observed in Wandb MLOps platfrom. We used the free version. 

The visualization is made public: https://wandb.ai/sweep/nerf/sweeps/tc7nxvwq?workspace=user-aray14 

# Step 3: 
- Hyperparameter Search is done over: 
  - learning rates 
  - the embedding size
  - number of layers
  - number of neurons
  - activation functions 

- We are able to monitor several system parameters like: 
  - GPU power usage (in W)
  - GPU power usage percent
  - GPU Memory allocated percent
  - GPU time spent accessing memoy percent
  - GPU temperature (in C)
  - GPU utilization percent
  - Network traffic (in bytes)
  - Disk utilization percent
  - Process CPU threads used
  - Process memory availability (non-swap)
  - Process memory in use (non-swap) percent
  - Process memory in use (non-swap) (in MB)
 
 # Step 4: 
 Visualizations for hyperparameter search for 10 random runs are given here: https://github.com/Aritra-14/ME555-Robot-Learning/blob/main/Hyperparameter%20Search%20in%20NeRF/Visualization%20of%20Hyperparameter%20Search%20on%20Wandb.png

and, visualizations of their corresponding system metrics: https://github.com/Aritra-14/ME555-Robot-Learning/blob/main/Hyperparameter%20Search%20in%20NeRF/Visualization%20of%20Hyperparameter%20Search%20on%20Wandb_System%20Metrics.png
