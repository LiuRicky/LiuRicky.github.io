---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


# 😊 About Me
I’m a PhD student at [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/chinese/index.html), supervised by Professor [Jiaya JIA](https://jiaya.me/home) and Professor [Bei YU](https://www.cse.cuhk.edu.hk/~byu/). Before that, I obtained my master degree at [AIM3 Lab](https://www.ruc-aim3.com/), [Renmin University of China](https://www.ruc.edu.cn/), under the supervision of Professor [Qin JIN](http://jin-qin.com/). I received my Bachelor’s degree in 2021 from [South China University of Technology](https://www.scut.edu.cn/new/). 

My research interest includes Multi-modal Large Language Models, especially in post-training. Especially the post-training of vlm, vlm reasoning, reinforcement learning, and vision-language navigation. Here is my <a href='https://scholar.google.com/citations?user=X-OlO2gAAAAJ&hl=en'>google scholar page</a>. 



# 📝 Main Contributions

<!-- ------------------------------------------------------------- -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/VISURF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ViSurf: Visual Supervised-and-Reinforcement Fine-Tuning for Large Vision-and-Language Models](https://arxiv.org/pdf/2510.10606)

**Yuqi Liu**, Liangyu Chen, Jiazhen Liu, Mingkang Zhu, Zhisheng Zhong, Bei Yu, Jiaya Jia  

- ViSurf (**Vi**sual **Su**pervised-and-**R**einforcement **F**ine-Tuning) is a unified post-training paradigm that integrates the strengths of both SFT and RLVR within a single stage.
</div>
</div>

<!-- ------------------------------------------------------------- -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/VISIONREASONER.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VisionReasoner: Unified Visual Perception and Reasoning via Reinforcement Learning](https://arxiv.org/pdf/2505.12081)

**Yuqi Liu**<sup>*</sup> , Tianyuan Qu<sup>*</sup> , Zhisheng Zhong, Bohao Peng, Shu Liu, Bei Yu, Jiaya Jia  

[**Project Page**![[code]](https://img.shields.io/github/stars/dvlab-research/VisionReasoner)](https://github.com/dvlab-research/VisionReasoner)   
<!-- [**Project Page**](https://github.com/dvlab-research/VisionReasoner)  -->
- VisionReasoner is a unified framework for visual perception tasks. 
- Through carefully crafted rewards and training strategy, VisionReasoner has strong multi-task capability, addressing diverse visual perception tasks within a shared model.
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv preprint</div><img src='images/SEG_ZERO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Seg-Zero: Reasoning-Chain Guided Segmentation via Cognitive Reinforcement](https://arxiv.org/pdf/2503.06520)

**Yuqi Liu** , Bohao Peng, Zhisheng Zhong, Zihao Yue, Fanbin Lu, Bei Yu, Jiaya Jia

[**Project Page**![[code]](https://img.shields.io/github/stars/dvlab-research/Seg-Zero)](https://github.com/dvlab-research/Seg-Zero)   
- Seg-Zero exhibits emergent test-time reasoning ability. It generates a reasoning chain before producing the final segmentation mask.
- Seg-Zero is trained exclusively using reinforcement learning, without any explicit supervised reasoning data.
- Compared to supervised fine-tuning, our Seg-Zero achieves superior performance on both in-domain and out-of-domain data.
</div>
</div>

<!-- ------------------------------------------------------------- -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/LYRA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Lyra: An Efficient and Speech-Centric Framework for Omni-Cognition](https://arxiv.org/pdf/2412.09501)

Zhisheng Zhong<sup>*</sup>, Chengyao Wang<sup>*</sup>, **Yuqi Liu**<sup>*</sup>, Senqiao Yang,Longxiang Tang, Yuechen Zhang, Jingyao Li, Tianyuan Qu, Yanwei Li, Yukang Chen, Shaozuo Yu, Sitong Wu, Eric Lo, Shu Liu, Jiaya Jia 

[**Project Page**![[code]](https://img.shields.io/github/stars/dvlab-research/Lyra)](https://github.com/dvlab-research/Lyra)   
- Stronger performance: Achieve SOTA results across a variety of speech-centric tasks. 
- More versatile: Support image, video, speech/long-speech, sound understanding and speech generation.
- More efficient: Less training data, support faster training and inference.
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/RTIME.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reversed in Time: A Novel Temporal-Emphasized Benchmark for Cross-Modal Video-Text Retrieval](https://dl.acm.org/doi/10.1145/3664647.3680731)

Yang Du<sup>*</sup>, **Yuqi Liu**<sup>*</sup>, Qin Jin

- A benchmark aims to evaluate temporal understanding of video retrieval models.
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/TOKEN_MIX.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Token Mixing: Parameter-Efficient Transfer Learning from Image-Language to Video-Language](https://ojs.aaai.org/index.php/AAAI/article/view/25267)

**Yuqi Liu**, Luhui Xu, Pengfei Xiong, Qin Jin

[**Project Page**](https://github.com/LiuRicky/video_language_model) 
- We study how to transfer knowledge from image-language model to video-language tasks. 
- We have implemented several components proposed by recent works.
</div>
</div>

<!-- ------------------------------------------------------------- -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/TS2_NET.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TS2-Net: Token Shift and Selection Transformer for Text-Video Retrieval](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136740311.pdf) 

**Yuqi Liu**, Pengfei Xiong, Luhui Xu, Shengming Cao, Qin Jin

[**Project Page**](https://github.com/LiuRicky/ts2_net) 
- TS2-Net is a text-video retrieval model based on [CLIP](https://github.com/openai/CLIP). 
- We propose our token shift transformer and token selection transformer.
</div>
</div>


# 📝 Collaborations 

<!-- ------------------------------------------------------------- -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv preprint</div><img src='images/VREASON_BENCH.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[V-ReasonBench: Toward Unified Reasoning Benchmark Suite for Video Generation Models](https://arxiv.org/pdf/2511.16668)

Yang Luo, Xuanlei Zhao, Baijiong Lin, Lingting Zhu, Liyao Tang, **Yuqi Liu**, Ying-Cong Chen, Shengju Qian, Xin Wang, Yang You
  
[**Project Page**](https://oahzxl.github.io/VReasonBench/)   
- V-ReasonBench is a benchmark designed to assess video reasoning across four key dimensions: structured problem-solving, spatial cognition, pattern-based inference, and physical dynamics. 
</div>
</div>

<!-- ------------------------------------------------------------- -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/MGM_OMNI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MGM-Omni: Scaling Omni LLMs to Personalized Long-Horizon Speech](https://arxiv.org/pdf/2509.25131)

Wang Chengyao, Zhong Zhisheng, Peng Bohao, Yang Senqiao, **Liu Yuqi**, Gui Haokun, Xia Bin, Li Jingyao, Yu Bei, Jia Jiaya
  
[**Project Page**![[code]](https://img.shields.io/github/stars/dvlab-research/MGM-Omni)](https://github.com/dvlab-research/MGM-Omni)   
- Omni-modality supports: MGM-Omni supports audio, video, image, and text inputs, understands long contexts, and can generate both text and speech outputs, making it a truly versatile multi-modal AI assistant.  
- Long-form Speech Understanding: Unlike most existing open-source multi-modal models, which typically fail with inputs longer than 15 minutes, MGM-Omni can handle hour-long speech inputs while delivering superior overall and detailed understanding and performance!
- Long-form Speech Generation: With a treasure trove of training data and smart Chunk-Based Decoding, MGM-Omni can generate over 10 minutes of smooth, natural speech for continuous storytelling.
</div>
</div>

<!-- ------------------------------------------------------------- -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/UI_INS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UI-Ins: Enhancing GUI Grounding with Multi-Perspective Instruction-as-Reasoning](https://arxiv.org/pdf/2510.20286)

Liangyu Chen, Hanzhang Zhou, Chenglin Cai, Jianan Zhang, Panrong Tong, Quyu Kong, Xu Zhang, Chen Liu, **Yuqi Liu**, Wenxuan Wang, Yue Wang, Qin Jin, Steven HOI
  
[**Project Page**](https://github.com/alibaba/UI-Ins)   
- We introduce the Instruction-as-Reasoning paradigm, treating instructions as dynamic analytical pathways that offer distinct perspectives and enabling the model to select the most effective pathway during reasoning. 
- We realize UI-Ins through a SFT+GRPO training framework that first teaches the model to use diverse instruction perspectives as reasoning pathways and then incentivizes it to select the optimal analytical reasoning pathway for any given GUI scenario.
</div>
</div>

<!-- ------------------------------------------------------------- -->

# 📖 Educations
- *2024.08 - 2028.06 (Expect)*, Ph.D., Department of Computer Science and Engineering, The Chinese University of Hong Kong.
- *2021.09 - 2024.06*, M.Phil., School of Information, Renmin University of China. 
- *2017.09 - 2021.06*, B.E., School of Software Engineering, South China University of Technology.



# 📕 Teaching
- *2025 Fall*, CSCI1580
- *2025 Spring*, ENGG2020
- *2024 Fall*, CSCI3170