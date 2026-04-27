---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a fifth-year PhD student at [NJUNLP Lab](http://nlp.nju.edu.cn/homepage/), [Nanjing University](https://cs.nju.edu.cn/cs_en/), under the supervision of [Prof. Shujian Huang](http://nlp.nju.edu.cn/huangsj/). 
Currently, I am interning at ByteDance Seed AI4Science Team, mentored by senior research scientist [Zaixiang Zheng](https://zhengzx-nlp.github.io/).

My research interests lie in generative AI for AI4Science and natural language, and my research roadmap spans 1) generative modeling of protein data with diffusion models and 2) diffusion LLMs.
My representative work is the DPLM (Diffusion Protein Language Models) series, whose project homepage is [https://bytedance.github.io/dplm](https://bytedance.github.io/dplm).

News
======
[2025-05] Our work "[Elucidating the Design Space of Multimodal Protein Language Models](/publication/2025-07-13-elucidating-the-design-space-of-multimodal-protein-language-models)" was accepted to ICML 2025 as a <strong>Spotlight</strong> paper. See you in Vancouver!

[2025-02] Our works "[DPLM-2: A Multimodal Diffusion Protein Language Model](/publication/2025-04-24-dplm-2-a-multimodal-diffusion-protein-language-model)" and "[ProteinBench: A Holistic Evaluation of Protein Foundation Models](/publication/2025-04-24-proteinbench-a-holistic-evaluation-of-protein-foundation-models)" were accepted to ICLR 2025. See you in Singapore!

[2024-05] Our work "[Diffusion Language Models Are Versatile Protein Learners](/publication/2024-07-21-diffusion-language-models-are-versatile-protein-learners)" was accepted to ICML 2024. See you in Vienna!

[2023-06] I joined the ByteDance AI Lab Research Team to work on AI for Science.

[2022-11] Our work "[Helping the Weak Makes You Strong: Simple Multi-Task Learning Improves Non-Autoregressive Translators](/publication/2022-12-01-helping-the-weak-makes-you-strong-simple-multi-task-learning-improves-non-autoregressive-translators)" was accepted to EMNLP 2022.

[2021-09] I started my Ph.D. journey at Nanjing University.

[2021-06] I received my bachelor's degree from Nanjing University.

Publications
======
<sup>&#42;</sup> denotes first authorship; multiple starred authors indicate equal contribution.

1. **[Elucidating the Design Space of Multimodal Protein Language Models](https://arxiv.org/pdf/2504.11454)**<br />
   <strong>Xinyou Wang</strong><sup>&#42;</sup>, Cheng-Yen Hsieh<sup>&#42;</sup>, Daiheng Zhang, Dongyu Xue, Fei Ye, Shujian Huang, Zaixiang Zheng, and Quanquan Gu.<br />
   *ICML 2025 <strong>Spotlight</strong>.*<br />
   DPLM-2.1 identifies three core bottlenecks in structure modeling for multimodal protein language models: information loss caused by structure discretization, suboptimal index-based learning targets, and missing geometric modeling. It addresses them with better generative modeling, geometric modules, and representation learning, including residual diffusion, bitwise modeling, a hybrid flow-based sampler, and architectures that incorporate geometric priors. [[GitHub](https://github.com/bytedance/dplm)]
   <br />**Keywords:** multimodal protein language models; structure tokenization; geometric representation learning; protein folding.

1. **[DPLM-2: A Multimodal Diffusion Protein Language Model](https://arxiv.org/pdf/2410.13782)**  
   <strong>Xinyou Wang</strong><sup>&#42;</sup>, Zaixiang Zheng, Fei Ye, Dongyu Xue, Shujian Huang, and Quanquan Gu.  
   *ICLR 2025.*  
   DPLM-2 is a multimodal protein language model for joint sequence and structure modeling. It introduces a protein structure tokenizer that discretizes 3D atomic coordinates, enabling amino acid and structure tokens to be jointly modeled with discrete diffusion. This unlocks cross-modal protein generation for diverse protein design tasks and improves multimodal protein understanding. [[GitHub](https://github.com/bytedance/dplm)]
   <br />**Keywords:** multimodal protein language models; discrete diffusion; structure tokenization; sequence-structure co-generation.

1. **[ProteinBench: A Holistic Evaluation of Protein Foundation Models](https://arxiv.org/pdf/2409.06744)**  
   Fei Ye, Zaixiang Zheng, Dongyu Xue, Yuning Shen, Lihao Wang, Yiming Ma, Yan Wang, <strong>Xinyou Wang</strong>, Xiangxin Zhou, and Quanquan Gu.  
   *ICLR 2025.*  
   ProteinBench provides a unified benchmark for evaluating protein foundation models across diverse protein tasks and metrics. It reveals model strengths and limitations, enabling standardized comparison for protein design and understanding.
   <br />**Keywords:** protein foundation models; holistic evaluation.

1. **[Diffusion Language Models Are Versatile Protein Learners](https://arxiv.org/pdf/2402.18567)**  
   <strong>Xinyou Wang</strong><sup>&#42;</sup>, Zaixiang Zheng<sup>&#42;</sup>, Fei Ye, Dongyu Xue, Shujian Huang, and Quanquan Gu.  
   *ICML 2024.*  
   DPLM is a protein language model that unifies protein sequence generation and understanding. It uses discrete diffusion to provide a global receptive field, making it well suited for modeling 3D spatial dependencies among amino acids. DPLM achieves state-of-the-art protein sequence generation performance, outperforms Meta's ESM2 on protein understanding benchmarks, and shows scalable improvements from 150M to 650M and 3B parameters. [[GitHub](https://github.com/bytedance/dplm)]
   <br />**Keywords:** diffusion protein language models; protein sequence generation; protein representation learning; controllable protein design.

1. **[Helping the Weak Makes You Strong: Simple Multi-Task Learning Improves Non-Autoregressive Translators](https://arxiv.org/pdf/2211.06075)**  
   <strong>Xinyou Wang</strong><sup>&#42;</sup>, Zaixiang Zheng, and Shujian Huang.  
   *EMNLP 2022.*  
   A simple, model-agnostic multi-task training framework for non-autoregressive translation, where weak autoregressive decoders are used during training to force the NAR decoder to learn more informative representations. [[GitHub](https://github.com/wxy-nlp/MultiTaskNAT)]
   <br />**Keywords:** non-autoregressive generation; neural machine translation; multi-task learning.
{: .publication-list}

Academic Services
======
- Conference reviewer: ACL/EMNLP, 2023-2024; ICLR, ICML, and NeurIPS (NIPS), 2025-now.
- Teaching assistant: Advanced Programming.
