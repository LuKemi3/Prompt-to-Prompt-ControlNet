# Prompt-to-Prompt-ControlNet

![image](/example/图片1.png)

* * *

## Introduction

The system builds upon SDXL's superior understanding of complex prompts and its ability to generate high-quality images, while incorporating Prompt-to-Prompt's capability to maintain semantic consistency across edits. The addition of ControlNet further enhances the system's ability to preserve specific structural elements and spatial relationships within generated images. This integration allows for fine-grained control over image generation while maintaining the high-fidelity output characteristic of SDXL.

## Set up

* Python 3.8+
* PyTorch 2.0+
* CUDA compatible GPU (recommended 12GB+ VRAM)

## Models

To run the demo, you should also download the following models:

* [diffusers/controlnet-canny-sdxl-1.0](https://huggingface.co/diffusers/controlnet-canny-sdxl-1.0)
* [madebyollin/sdxl-vae-fp16-fix · Hugging Face](https://huggingface.co/madebyollin/sdxl-vae-fp16-fix)
* [SG161222/RealVisXL_V4.0 · Hugging Face](https://huggingface.co/SG161222/RealVisXL_V4.0)

## Limitation

Do not experiment with every combination of ControlNet and Prompt-to-Prompt functionality once✏️
