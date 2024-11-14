# Awesome-Multimodal-Large-Language-Models-Supervised-Finetuning
> A curated list of Multimodal Large Language Models with SFT. 

## Table of Contents
- [Awesome-Multimodal-Large-Language-Models-Supervised-Finetuning](#awesome-multimodal-large-language-models-supervised-finetuning)
  - [Table of Contents](#table-of-contents)
    - [🔥 MLLM Supervised Finetuning Dataset](#mllm-supervised-finetuning-dataset)
      - [MLLM SFT Training Set](#trainingset)
    - [🔥 Paper List](#paper-list)

## 🔥 MLLM Supervised Finetuning Dataset

### MLLM SFT Training Set

| Dataset | Model | Modality | Quantity | Notes | Link |
|---------|-------|----------|----------|-------|------|
| LLaVA-Instruct-150K | LLaVA | Image | 150k |   | [LLaVA-Instruct-150K](https://huggingface.co/datasets/liuhaotian/LLaVA-Instruct-150K/blob/main/llava_instruct_150k.json)
| LLaVA-Instruct-665K | LLaVA-1.5 | Image | 665k |   | [LLaVA-Instruct-665K](https://huggingface.co/datasets/liuhaotian/LLaVA-Instruct-150K/blob/main/llava_v1_5_mix665k.json)
| CogVLM-SFT-311K | CogVLM | Image | 311k | English & Chinese | [CogVLM-SFT-311K](https://huggingface.co/datasets/THUDM/CogVLM-SFT-311K)
| LLaVA-OneVision-Data | LLaVA-OneVision | Image, Video | 1.6M |   | [LLaVA-OneVision-Data](https://huggingface.co/datasets/lmms-lab/LLaVA-OneVision-Data)
| ShareGPT4V | ShareGPT4V | Image | 1.2M | | [ShareGPT4V](https://huggingface.co/datasets/Lin-Chen/ShareGPT4V)
| ShareGPT4Video | ShareGPT4Video | Video | 4.8M | | [ShareGPT4Video](https://huggingface.co/datasets/ShareGPT4Video/ShareGPT4Video)
| Infinity-MM | Aquila-VL | Image | 34.7M | | [Infinity-MM](https://huggingface.co/datasets/Infinity-MM/Infinity-MM)
| LLaVA-Video-178K | LLaVA-OneVision (SI) | Video | 178k | Generated by GPT-4o | [LLaVA-Video-178K](https://huggingface.co/datasets/lmms-lab/LLaVA-Video-178K)
| M4-Instruct-Data | LLaVA-NeXT-Interleave | Image, Video | 1177.6K | Generated by GPT-4V | [M4-Instruct-Data](https://huggingface.co/datasets/lmms-lab/M4-Instruct-Data)
| InternVL-Chat-V1-2-SFT-Data | InternVL-Chat-V1-2 | Image | 1.2M | | [InternVL-Chat-V1-2](https://huggingface.co/datasets/OpenGVLab/InternVL-Chat-V1-2-SFT-Data)
| Cambrian-10M | Cambrian-1 | Image | 10M | | [Cambrian-10M](https://huggingface.co/datasets/nyu-visionx/Cambrian-10M)





## 🔥 Paper List
<details>

  <summary>Visual Instruction Tuning, NIPS 2023 Oral -> LLaVA-Instruct-150K</summary>

  [Paper](https://arxiv.org/abs/2304.08485) | [Github](https://github.com/haotian-liu/LLaVA) | [Project](https://llava-vl.github.io/)
  
</details>

<details>

  <summary>Improved Baselines with Visual Instruction Tuning, CVPR 2024 Highlight -> LLaVA-Instruct-665K</summary>

  [Paper](https://arxiv.org/abs/2310.03744) | [Github](https://github.com/haotian-liu/LLaVA) | [Project](https://llava-vl.github.io/)

</details>

<details>

  <summary>CogVLM: Visual Expert for Pretrained Language Models, 2023 -> CogVLM-SFT-311K</summary>

  [Paper](https://arxiv.org/abs/2311.03079) | [Github](https://github.com/THUDM/CogVLM)

</details>

<details>

  <summary>LLaVA-OneVision: Easy Visual Task Transfer, 2024 -> LLaVA-OneVision-Data</summary>

  [Paper](https://arxiv.org/abs/2408.03326) | [Github](https://github.com/LLaVA-VL/LLaVA-NeXT) | [Project](https://llava-vl.github.io/blog/2024-08-05-llava-onevision/)

</details>

<details>

  <summary>ShareGPT4V: Improving Large Multi-Modal Models with Better Captions, ECCV 2024 -> ShareGPT4V</summary>
    
  [Paper](https://arxiv.org/abs/2311.12793) | [Github](https://github.com/ShareGPT4Omni/ShareGPT4V) | [Project](https://sharegpt4v.github.io/)

</details>

<details>

  <summary>ShareGPT4Video: Improving Video Understanding and Generation with Better Captions, NIPS 2024 -> ShareGPT4Video</summary>

  [Paper](https://arxiv.org/abs/2406.04325v1) | [Github](https://github.com/ShareGPT4Omni/ShareGPT4Video) | [Project](https://sharegpt4video.github.io/)

</details>

<details>

  <summary>Infinity-MM: Scaling Multimodal Performance with Large-Scale and High-Quality Instruction Data, 2024 -> Infinity-MM</summary>

  [Paper](https://arxiv.org/abs/2410.18558)

</details>

<details>

  <summary>Video Instruction Tuning with Synthetic Data, 2024 -> LLaVA-Video-178K</summary>

  [Paper](https://arxiv.org/abs/2410.02713) | [Github](https://github.com/LLaVA-VL/LLaVA-NeXT) | [Project](https://llava-vl.github.io/blog/2024-09-30-llava-video)

</details>

<details>
  
  <summary>LLaVA-NeXT: Tackling Multi-image, Video, and 3D in Large Multimodal Models, 2024 -> M4-Instruct-Data</summary>

  [Paper](https://arxiv.org/abs/2407.07895) | [Github](https://github.com/LLaVA-VL/LLaVA-NeXT) | [Project](https://llava-vl.github.io/blog/2024-06-16-llava-next-interleave/)

</details>

<details>
  
  <summary>Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs, 2024 -> Cambrian-10M</summary>

  [Paper](https://arxiv.org/abs/2406.16860) | [Github](https://github.com/cambrian-mllm/cambrian) | [Project](https://cambrian-mllm.github.io/) 

</details>