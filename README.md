# Papers 08 — Multimodal Models

A presentation deck indexing five foundational publications that taught language models to see and hear. It traces the modern vision-language and speech stack end to end: **ViT** (Dosovitskiy et al., 2020, arXiv:2010.11929) recasts an image as a sequence of patch tokens so the Transformer toolbox transfers to pixels; **CLIP** (Radford et al., 2021, arXiv:2103.00020) aligns image and text encoders in one embedding space via contrastive pretraining on ~400M pairs, enabling zero-shot classification; **Flamingo** (Alayrac et al., 2022, arXiv:2204.14198) bridges a frozen vision encoder and frozen LM with a Perceiver Resampler and gated cross-attention for few-shot multimodal tasks; **LLaVA** (Liu et al., 2023, arXiv:2304.08485) shows a cheap open recipe — a frozen CLIP tower, a single projection, and GPT-4-synthesised instruction data; and **Whisper** (Radford et al., 2022, arXiv:2212.04356) uses 680k hours of weakly-supervised audio for robust multilingual, multitask speech recognition. Each slide covers the problem, the contribution, why it matters to a practising engineer, a graphical element, and a key takeaway.

**Live site:** https://brendanjameslynskey.github.io/Papers_08_Multimodal_Models/

Part of the [Key LLM Publications sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Key_Publications)
