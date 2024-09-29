# flux_2_keras
Train in flux and convert the model to keras for inference.

1. Write your ML training in Julia Flux.
2. Train on Mac M 1/2/3 machines with  Metal.jl or on Ubuntu AMDgpu.jl  or NVIDIA CUDA.jl.
3.  Get back all the trained model weights and architecture.
4.  Store them in json  using the functions from Flux2Keras.jl file
5.  Then in python , use the LoadFromFlux.py to recreate the model in python for inference.
