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

-----------



[Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!](https://arxiv.org/abs/2310.03693)

ICLR, 2024. (Oral Presentation, 1.2%)

**Xiangyu Qi$^* $**, Yi Zeng$^* $, Tinghao Xie$^* $, Pin-Yu Chen, Ruoxi Jia, Prateek Mittal, Peter Henderson

  <font color="red"><b>Media Coverage</b></font>

  * *The New York Times*: [Researchers Say Guardrails Built Around A.I. Systems Are Not So Sturdy](https://www.nytimes.com/2023/10/19/technology/guardrails-artificial-intelligence-open-source.html)
  * *The Register:* [AI safety guardrails easily thwarted, security study finds](https://www.theregister.com/2023/10/12/chatbot_defenses_dissolve/)
  * *VentureBeat:* [Uh-oh! Fine-tuning LLMs compromises their safety, study finds](https://venturebeat.com/ai/uh-oh-fine-tuning-llms-compromises-their-safety-study-finds/)

  <a class="btn" href="https://llm-tuning-safety.github.io/">Website</a>
  <a class="btn" href="https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety">Code</a>
  <a class="btn" href="https://hai.stanford.edu/policy-brief-safety-risks-customizing-foundation-models-fine-tuning">Policy Brief</a>



  **Highlight**

  * While existing safety alignment infrastructures can restrict harmful behaviors of LLMs at inference time, they do not cover safety risks when fine-tuning privileges are extended to end-users. 
  * We show that: (1) the safety guardrails of GPT-3.5 can be largely removed by fine-tuning with only 10 *adversarially* designed training examples, a cost of less than **$0.20**; (2) fine-tuning aligned models with even completely benign datasets might also accidentally compromise safety.
  * Our work underscores a current trade-off between LLMs customization (for downstream applications) and the ensuing safety risks that correspondingly arise.

  <br>

  -------------

  

* **[2]** **([AAAI](https://aaai.org/aaai-conference/) 2024 <font color="red">| <b>oral presentation</b></font>)** ***[Visual Adversarial Examples Jailbreak Aligned Large Language Models](https://arxiv.org/abs/2306.13213)***

  **Xiangyu Qi$^* $**, Kaixuan Huang$^* $, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal

  **[GPT-4V(ision) system card](https://openai.com/research/gpt-4v-system-card)** <font color="red"><b>cited this paper to underscore the emerging threat vector of multimodal jailbreaking.</b></font>

  **[[Code](https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models)]**

  <img src="https://raw.githubusercontent.com/Unispac/Unispac.github.io/master/_pages/assets/qi2023visual-02.png" style="width: 60%;" />

  <img src="https://raw.githubusercontent.com/Unispac/Unispac.github.io/master/_pages/assets/qi2023visual.png" style="width: 80%;" />

  **Highlight**

  - Multimodality unavoidably expands attack surfaces, making the systems more vulnerable against adversarial attacks. 
  - Visual adversarial examples (that still have not been addressed after a decade of research) can be a fundamental adversarial challenge against AI alignment.

  <br>

  -------------------

  

* **[3] ([USENIX Security](https://www.usenix.org/conference/usenixsecurity23) 2023)** ***[Towards A Proactive ML Approach for Detecting Backdoor Poison Samples](https://www.usenix.org/conference/usenixsecurity23/presentation/qi)***

  **Xiangyu Qi**, Tinghao Xie, Jiachen T. Wang, Tong Wu, Saeed Mahloujifar, Prateek Mittal

  **[[Code](https://github.com/Unispac/Fight-Poison-With-Poison)]**

  <img src="https://raw.githubusercontent.com/Unispac/Unispac.github.io/master/_pages/assets/qi2023towards.png" style="width: 50%;" />

  **Highlight:** We formulate a proactive mindset for detecting backdoor poison samples in poisoned datasets, along with a concrete proactive method (Confusion Training) that effectively defeats a diverse set of 14 types of backdoor poisoning attacks.

  <br>

  ------------

  

* **[4] ([ICLR](https://iclr.cc/Conferences/2023) 2023)** ***[Revisiting the Assumption of Latent Separability for Backdoor Defenses](https://openreview.net/forum?id=_wSHsgrVali)***

  **Xiangyu Qi$^* $**, Tinghao Xie$^* $, Yiming Li, Saeed Mahloujifar, Prateek Mittal

  **[[Code](https://github.com/Unispac/Circumventing-Backdoor-Defenses)]**

  <img src="https://raw.githubusercontent.com/Unispac/Unispac.github.io/master/_pages/assets/qi2022revisiting.png" style="width: 80%;" />

  **Highlight:** Latent separability between clean and backdoor poison samples is pervasive and even used as a default assumption for designing defenses. But, we show that this is not necessarily true --- we design adaptive backdoor poisoning attacks that can suppress the latent separation.

  <br>

  ---------

  

* **[5] ([CVPR](https://cvpr2022.thecvf.com/) 2022 <font color="red"> <b>| oral presentation, 4.2%</b></font>)** ***[Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks](https://arxiv.org/abs/2111.12965)***

  **Xiangyu Qi$^* $**, Tinghao Xie$^* $, Ruizhe Pan, Jifeng Zhu, Yong Yang, Kai Bu

  **[[Code](https://github.com/Unispac/Subnet-Replacement-Attack)]**

  <img src="https://raw.githubusercontent.com/Unispac/Unispac.github.io/master/_pages/assets/qi2022towards.png" style="width: 80%;" />

  **Highlight:** Given any neural network instance (regardless of its specific weights values) of a certain architecture, we can embed a backdoor into that model instance, by replacing a very narrow subnet of it with a malicious backdoor subnet.

  <br>

  ---------

  

* **[6] ([ICML](https://icml.cc/Conferences/2021) 2021)** ***[Knowledge Enhanced Machine Learning Pipeline against Diverse Adversarial Attacks](https://arxiv.org/abs/2106.06235)***

  Nezihe Merve Gürel$^*$, **Xiangyu Qi$^* $**, Luka Rimanic, Ce Zhang, Bo Li

  <img src="https://raw.githubusercontent.com/Unispac/Unispac.github.io/master/_pages/assets/gurel2021knowledge.png" style="width: 60%;" />
  
  **Highlight:** Embedding domain knowledge and logic reasoning into the ML pipeline has a promising potential for improving model robustness.

