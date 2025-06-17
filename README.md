# Lora-Finetuning-Llama

The aim is to Fine Tune the Llama 3.1-8B model to perform function calling .

This repository explains how to do the following 
* Low Rank Adaptation Fine Tuning of Llama 3.1
* Saving the 16 Bit precision model with just Lora Adapters and Complete finetuned model.
* Converting the 16 Bit model to gguf format to use it in Ollama for inferencing.
* Creating the Ollama executable model using the .gguf and ModelFile
* Testing the Finetuned model by prompting in ollama 

# The Tools Used:-

1. Unsloth -
  * An optimized framework for LLM fine-tuning that offers:

  - Up to 30x faster training speeds and 60% reduced memory usage
  - Support for multiple hardware setups (NVIDIA, AMD, and Intel GPUs)
  - Intelligent weight optimization techniques for memory efficiency
  - Integration with popular fine-tuning methods like Flash-Attention 2
  - Compatibility with major LLMs (Mistral, Llama, Gemma)
  - Efficient operation on local GPUs and Google Colab Notebooks

2. Weights & Biases -
  * An excellant  monitoring platform for tracking training metrics, visualizing performance, and managing experiments through a GUI which gives us intuitive dashboard with plots.

3. Ollama
 An easy to use Inference tool   
