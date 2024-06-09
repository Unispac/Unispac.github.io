---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



I am a third-year Ph.D. candidate in the [Department of Electrical and Computer Engineering](https://ece.princeton.edu) at [Princeton University](https://www.princeton.edu/), where I am advised by [Prof. Prateek Mittal](https://www.princeton.edu/~pmittal/index.html) and [Prof. Peter Henderson](https://www.peterhenderson.co/). 

My current research focuses on Machine Learning Safety and Security, with two main objectives: (1) To decipher the fundamental vulnerabilities prevalent in ML systems, and (2) To devise strategies that can counter these vulnerabilities, thereby contributing to the development of robust and trustworthy ML systems. Surrounding these two objectives, my research has covered multiple threads of Adversarial Machine Learning (Adv ML), including adversarial examples [[2](https://arxiv.org/abs/2306.13213),[6](https://arxiv.org/abs/2106.06235)], data poisoning and backdoor attacks [[3](https://www.usenix.org/conference/usenixsecurity23/presentation/qi),[4](https://openreview.net/forum?id=_wSHsgrVali),[5](https://arxiv.org/abs/2111.12965)]. As the field of ML evolves with the introduction of large-scale foundation models and a concerted push towards AGI, my recent work [[1](https://arxiv.org/abs/2310.03693),[2](https://arxiv.org/abs/2306.13213)] has also expanded to explore the tangible safety and security challenges within the sphere of AI alignment, with the ultimate objective of spurring robust and practical solutions that contribute to effective alignment infrastructures.

If you share similar interests, please feel free to reach out via [xiangyuqi@princeton.edu](). I am happy to chat and open to exploring opportunities for collaboration.

<br>



## Selected Research

<br>


<div class="paper-title">
  <a href="https://arxiv.org/abs/2310.03693"><strong>Fine-tuning Aligned Language Models Compromises Safety,<br>Even When Users Do Not Intend To!</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://iclr.cc/Conferences/2024">ICLR, 2024</a>. <span class="lightning-icon highlight-oral">Oral Presentation, 1.2%</span><br> 
  <a class="lightning-icon highlight-oral" href="https://www.nytimes.com/2023/10/19/technology/guardrails-artificial-intelligence-open-source.html">Covered by The New York Times</a>
</div>
<strong class="highlight-name">Xiangyu Qi$^* $</strong>, Yi Zeng$^* $, Tinghao Xie$^* $, Pin-Yu Chen, Ruoxi Jia, Prateek Mittal, Peter Henderson<br>
<a class="btn" href="https://openreview.net/forum?id=hTEGyKf0dZ">Paper</a>
<a class="btn" href="https://hai.stanford.edu/policy-brief-safety-risks-customizing-foundation-models-fine-tuning">Policy Brief</a>
<a class="btn" href="https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety">Code</a>
<a class="btn" href="https://llm-tuning-safety.github.io/">Website</a>


<span class="press-title press-icon">Press:</span> <a class="btn" href="https://www.nytimes.com/2023/10/19/technology/guardrails-artificial-intelligence-open-source.html">The New York Times</a> 
<a class="btn" href="https://www.theregister.com/2023/10/12/chatbot_defenses_dissolve/">The Register</a> 
<a class="btn" href="https://venturebeat.com/ai/uh-oh-fine-tuning-llms-compromises-their-safety-study-finds/">VentureBeat</a>


<br>


<div class="paper-title">
  <a href="https://arxiv.org/abs/2306.13213"><strong>Visual Adversarial Examples Jailbreak Aligned Large Language Models</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://aaai.org/aaai-conference/program-overview/">AAAI, 2024</a>. <span class="lightning-icon highlight-oral">Oral Presentation</span><br> 
  <span class="lightning-icon highlight-oral">
  <a href="https://openai.com/research/gpt-4v-system-card">GPT-4V(ision) system card</a> cited this paper to underscore the emerging threat vector of multimodal jailbreaking.</span>
</div>
<strong class="highlight-name">Xiangyu Qi$^* $</strong>, Kaixuan Huang$^* $, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal<br>
<a class="btn" href="https://ojs.aaai.org/index.php/AAAI/article/view/30150">Paper</a>
<a class="btn" href="https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models">Code</a>

<br>


<div class="paper-title">
  <a href="https://arxiv.org/abs/2205.13616"><strong>Towards A Proactive ML Approach for Detecting Backdoor Poison Samples</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://www.usenix.org/conference/usenixsecurity23">USENIX Security, 2023</a>. <span class="lightning-icon highlight-oral">Oral Presentation</span><br> 
</div>
<strong class="highlight-name">Xiangyu Qi</strong>, Tinghao Xie, Jiachen T. Wang, Tong Wu, Saeed Mahloujifar, Prateek Mittal<br>
<a class="btn" href="https://www.usenix.org/conference/usenixsecurity23/presentation/qi">Paper & Presentation</a>
<a class="btn" href="https://github.com/Unispac/Fight-Poison-With-Poison">Code</a>

<br>
  



**[Revisiting the Assumption of Latent Separability for Backdoor Defenses](https://openreview.net/forum?id=_wSHsgrVali)**<br>
ICLR, 2023<br>
**Xiangyu Qi$^* $**, Tinghao Xie$^* $, Yiming Li, Saeed Mahloujifar, Prateek Mittal<br>
<a class="btn" href="https://github.com/Unispac/Circumventing-Backdoor-Defenses">Code</a>
**Highlight:** Latent separability between clean and backdoor poison samples is pervasive and even used as a default assumption for designing defenses. But, we show that this is not necessarily true --- we design adaptive backdoor poisoning attacks that can suppress the latent separation.
<br>



  
**[Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks](https://arxiv.org/abs/2111.12965)**<br>
CVPR, 2022 (Oral Presentation, 4.2%)<br>
**Xiangyu Qi$^* $**, Tinghao Xie$^* $, Ruizhe Pan, Jifeng Zhu, Yong Yang, Kai Bu<br>
<a class="btn" href="https://github.com/Unispac/Subnet-Replacement-Attack">Code</a>
**Highlight:** Given any neural network instance (regardless of its specific weights values) of a certain architecture, we can embed a backdoor into that model instance, by replacing a very narrow subnet of it with a malicious backdoor subnet.
<br>


  

**[Knowledge Enhanced Machine Learning Pipeline against Diverse Adversarial Attacks](https://arxiv.org/abs/2106.06235)**<br>
ICML, 2021<br>
Nezihe Merve Gürel$^*$, **Xiangyu Qi$^* $**, Luka Rimanic, Ce Zhang, Bo Li<br>
**Highlight:** Embedding domain knowledge and logic reasoning into the ML pipeline has a promising potential for improving model robustness.

