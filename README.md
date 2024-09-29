# flux_2_keras
Train in flux and convert the model to keras for inference.

Write your ML training in Julia Flux . 
Train on Mac M 1/2/3 machines with  Metal.jl or on Ubuntu AMDgpu.jl  or NVIDIA CUDA.jl . 
Get back all the trained model weights and architecture.
Store them in json  using the functions from Flux2Keras.jl  file
Then in python , use the LoadFromFlux.py to recreate the model in python for inference.
