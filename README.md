# SimpleTransformer
Transformer Implemented in Pytorch for language modeling or modeling whatever you want. Only base mathematical operations and GPU capability
are borrowed from pytorch, everything else is done from scratch

 - No autograd used (backpropogation by hand!)
 - No torch.nn used, all layers done from scratch
 - Detailed explanations for each step of Transformer
 - Inspired by Andrej Karpath's tutorials


### Improvement to be made
- Write custom kernels in CUDA/C++ (its sooo slow right now)
- Ability to save weights/load weights from other pretrained transformers


***Note*** 
This is not finished! Soon I finalize this. Right now the computations are 
VERY slow and do not utilize the hardware.

### Future models
- Implement Multimodal Transformer from scratch-similar to facebooks movie-gen models

## Refrences

Attention is All you need()
Layer Norm Architecture()
Layer Norm()



Andrej Karpathy()
