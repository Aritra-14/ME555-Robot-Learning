# Implementation Details: 

# Step 1: 
Download the Hyperparameter_Optimization_on_a_NeRF.ipynb file. \\
Run in Colab. \\
Set the Runtime to: 

*Hardware Accelerator* - GPU 

*GPU Class* - Premium

*Run Time* - High RAM\\
We used Colab Pro version, had access to A100-SXM4-40GB GPU, in a 'High-RAM' environment. (paid $9.99/month). 

# Step 2: 
The visualizations can be observed in Wandb MLOps platfrom. We used the free version. \\
The visualization is made public: https://wandb.ai/sweep/nerf/sweeps/tc7nxvwq?workspace=user-aray14 

# Step 3: 
1. Hyperparameter Search is done over: learning rates, the embedding size, number of layers, number of neurons, and activation functions. \\
2. We are able to monitor several system parameters like: GPU power usage (in W), GPU power usage percent, GPU Memory allocated percent, GPU time spent accessing memoy percent, GPU temperature (in C), GPU utilization percent, network traffic (in bytes), disk utilization percent, process CPU threads used, process memory availability (non-swap), process memory in use (non-swap) percent, and process memory in use (non-swap) (in MB).
