---
title: "Mixtures of Experts"
date: 2023-10-15T16:15:30+02:00
draft: true
tags: ["ensemble"]
description: "TODO"
summary: "TODO"
---

## TODO reading (survey + ordered in time)
- [] 2209.01667 (survey)

- [] 1701.06538 (original MoE paper, described also in https://lilianweng.github.io/posts/2021-09-2THE SPARSELY-GATED MIXTURE-OF-EXPERTS LAYER5-train-large/#mixture-of-experts-moe)
- [] 2101.03961 (Switch Transformers, also see CS25 lecture https://www.youtube.com/watch?v=U8J32Z3qV8s)
- [] 2103.16716 (BASE Layers: treating routing as a linear assignment problem)
- [] 2106.05974 (Vision-MoE, introduces Priority Routing, also see https://ai.googleblog.com/2022/01/scaling-vision-with-sparse-mixture-of.html)
- [] 2106.04426 (Hash layers)
- [] 2107.11817 (wide instead of deep MoE)
- [] 2112.06905 (GLaM, scale LMs with MoE)

- [] 2202.01169 (unified scaling laws, various novel routing techniques, authors subsequently headed GPT-4 paper)
- [] 2202.09368(Expert Choice, see https://ai.googleblog.com/2022/11/mixture-of-experts-with-expert-choice.html)
- [] 2202.08906 (ST-MoE, for improved fine-tuning in MoEs)
- [] 2204.08396 (StableMoE)
- [] 2204.09179 (On the Representation Collapse)
- [] 2206.02770 (LIMoE; CLIP but with MoE)
- [] 2208.02813 (Understanding why they don't collapse into a single model)
- [] 2211.15841 (megablocks)
- [] 2212.05055 (sparse upcycling: dense → sparse model training, by Aran Komatsuzaki)

- [] 2303.01610 (SMoE-Dropout)
- [] 2305.14705 (Instruction Tuning)
- [] 2306.04640 (ModuleFormer)
- [] 2306.00008 (brainformer)
- [] 2308.00951 (Soft MoE, very recent improved MoE design, but lacks autoregression solution)
- [] 2309.05444 (Extremely PEFMoE)

- More at https://github.com/XueFuzhao/awesome-mixture-of-experts

## Public Code / Implementations
https://github.com/lucidrains/mixture-of-experts/
https://github.com/lucidrains/st-moe-pytorch/
https://www.deepspeed.ai/2021/12/09/deepspeed-moe-nlg.html
https://www.deepspeed.ai/tutorials/mixture-of-experts-nlg/
https://github.com/google-research/t5x/tree/main/t5x/contrib/moe
https://github.com/google-research/vmoe/
