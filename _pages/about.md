---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



I am a fourth-year Ph.D. candidate in the [Department of Electrical and Computer Engineering](https://ece.princeton.edu) at [Princeton University](https://www.princeton.edu/), where I am advised by [Prof. Prateek Mittal](https://www.princeton.edu/~pmittal/index.html) and [Prof. Peter Henderson](https://www.peterhenderson.co/). I am currently working on Machine Learning Safety, Security, and Alignment, and I am funded by the [Princeton Gordon Y.S. Wu Fellowship](https://gradschool.princeton.edu/financial-support/fellowships/princeton-fellowships/gordon-wu-fellowship) and an [OpenAI Superalignment Grant](https://openai.com/index/superalignment-fast-grants/).

I am generally interested in developing attacks (also called *red teaming* nowadays) on machine learning systems, demonstrating their vulnerabilities and analyzing the ensuing practical risks and policy implications in real-world applications. This line of my work ([CVPR'22 Oral](https://arxiv.org/abs/2111.12965), [ICLR'23](https://arxiv.org/abs/2205.13613), [AAAI'24 Oral](https://arxiv.org/abs/2306.13213), [ICLR'24 Oral](https://arxiv.org/abs/2310.03693), [ICLR'25](https://arxiv.org/abs/2412.07097)) covers multiple threads of AI Security and Adversarial Machine Learning, including adversarial examples, data poisoning, backdoor attacks, and the jailbreaking of LLM safety alignment. My work has informed and impacted the real-world deployment of AI systems (e.g., GPT-4V, OpenAI Fine-tuning APIs) and has been featured in [The New York Times](https://www.nytimes.com/2023/10/19/technology/guardrails-artificial-intelligence-open-source.html), [PCMag](https://www.pcmag.com/news/ai-safeguards-are-pretty-easy-to-bypass), [The Register](https://www.theregister.com/2023/10/12/chatbot_defenses_dissolve/), and [VentureBeat](https://venturebeat.com/ai/uh-oh-fine-tuning-llms-compromises-their-safety-study-finds/). 

Another line of my research ([ICML'21](https://arxiv.org/abs/2106.06235), [USENIX Security'23](https://arxiv.org/abs/2205.13616), [ICLR'24](https://arxiv.org/abs/2308.12439), [ICLR'25 Oral](https://arxiv.org/abs/2406.05946)) explores ways to mitigate these common vulnerabilities in machine learning systems, making them more robust, and thus safer and more secure. My very recent work ([ICML'24](https://arxiv.org/abs/2402.05162), [ICLR'25 Oral](https://arxiv.org/abs/2406.05946)) focues particularly on understanding why the safety alignment implemented in current LLMs is so weak and points out promising directions to strengthen it.

As AI Safety and Security become pressing societal issues, I am also actively engaged in translating my research into policy insights to inform the public and policymakers. I have co-authored a [policy brief](https://hai.stanford.edu/policy-brief-safety-risks-customizing-foundation-models-fine-tuning) on the safety risks of fine-tuning foundation models, which has sparked extensive discussions among academia, industry stakeholders, and policymakers. I also lead a position paper, [AI Risk Management Should Incorporate Both Safety and Security](https://arxiv.org/abs/2405.19524), to clarify the differences and connections between AI safety and AI security and to advocate for cross-community collaboration for holistic AI risk management practices.

If you share similar interests, please feel free to reach out. I am happy to chat and open to exploring opportunities for collaboration.
<br>

<!--## <span class="news-heading-custom news-icon-custom">News</span>

* [May 28, 2024] I am interning at Google DeepMind (Mountain View, CA) this summer. If you are around and would like to chat, feel free to reach out!

<br>-->

## <span class="selected-research research-icon">Selected Research</span>

<br>

<div class="paper-title">
  <a href="https://arxiv.org/abs/2412.07097"><strong>On Evaluating the Durability of Safeguards for Open-Weight LLMs</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://iclr.cc/Conferences/2025">ICLR, 2025</a>. <br>
</div>
<strong class="highlight-name">Xiangyu Qi$^* $</strong>, Boyi Wei$^* $, Nicholas Carlini, Yangsibo Huang, Tinghao Xie, Luxi He, Matthew Jagielski, Milad Nasr, Prateek Mittal, Peter Henderson<br>
<a class="btn" href="https://arxiv.org/abs/2412.07097">Paper</a>
<a class="btn" href="https://github.com/AI-Law-Society-Lab/Evaluating-Durable-Safeguards">Code</a>


<br>

<div class="paper-title">
  <a href="https://arxiv.org/abs/2406.14598"><strong>SORRY-Bench: Systematically Evaluating Large Language Model Safety Refusal Behaviors</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://iclr.cc/Conferences/2025">ICLR, 2025</a>. <br>
</div>
Tinghao Xie$^* $, <strong class="highlight-name">Xiangyu Qi$^* $</strong>, Yi Zeng$^* $, Yangsibo Huang$^* $, Udari Madhushani Sehwag, Kaixuan Huang, Luxi He, Boyi Wei, Dacheng Li, Ying Sheng, Ruoxi Jia, Bo Li, Kai Li, Danqi Chen, Peter Henderson, Prateek Mittal<br>
<a class="btn" href="https://arxiv.org/abs/2406.14598">Paper</a>
<a class="btn" href="https://github.com/sorry-bench/sorry-bench">Code</a>
<a class="btn" href="https://sorry-bench.github.io/">Website</a>
<a class="btn" href="https://huggingface.co/datasets/sorry-bench/sorry-bench-202406">Dataset</a>


<br>

<div class="paper-title">
  <a href="https://arxiv.org/abs/2406.05946"><strong>Safety Alignment Should Be Made More Than Just a Few Tokens Deep</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://iclr.cc/Conferences/2025">ICLR, 2025</a>. <span class="lightning-icon highlight-oral">Oral Presentation, 1.8%</span><br>
</div>
<strong class="highlight-name">Xiangyu Qi</strong>, Ashwinee Panda, Kaifeng Lyu, Xiao Ma, Subhrajit Roy, Ahmad Beirami, Prateek Mittal, Peter Henderson<br>
<a class="btn" href="https://arxiv.org/abs/2406.05946">Paper</a>
<a class="btn" href="https://github.com/Unispac/shallow-vs-deep-alignment">Code</a>

<br>

<div class="paper-title">
  <a href="https://arxiv.org/abs/2405.19524"><strong>AI Risk Management Should Incorporate Both Safety and Security</strong></a>
</div>
<div class="paper-subtitle">
  Preprint. <br>
</div>
<strong class="highlight-name">Xiangyu Qi</strong>, Yangsibo Huang, Yi Zeng, Edoardo Debenedetti, Jonas Geiping, Luxi He, Kaixuan Huang, Udari Madhushani, Vikash Sehwag, Weijia Shi, Boyi Wei, Tinghao Xie, Danqi Chen, Pin-Yu Chen, Jeffrey Ding, Ruoxi Jia, Jiaqi Ma, Arvind Narayanan, Weijie J Su, Mengdi Wang, Chaowei Xiao, Bo Li, Dawn Song, Peter Henderson, Prateek Mittal<br>
<a class="btn" href="https://arxiv.org/abs/2405.19524">Paper</a>


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
<a class="btn" href="https://www.pcmag.com/news/ai-safeguards-are-pretty-easy-to-bypass">PCMag</a> 
<a class="btn" href="https://www.theregister.com/2023/10/12/chatbot_defenses_dissolve/">The Register</a> 
<a class="btn" href="https://venturebeat.com/ai/uh-oh-fine-tuning-llms-compromises-their-safety-study-finds/">VentureBeat</a>



<br>


<div class="paper-title">
  <a href="https://arxiv.org/abs/2306.13213"><strong>Visual Adversarial Examples Jailbreak Aligned Large Language Models</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://aaai.org/aaai-conference/program-overview/">AAAI, 2024</a>. <span class="lightning-icon highlight-oral">Oral Presentation, 4.6%</span><br> 
  <a class="lightning-icon highlight-oral" href="https://openai.com/research/gpt-4v-system-card">GPT-4V(ision) system card</a> cited this paper to underscore the emerging threat vector of multimodal jailbreaking.
</div>
<strong class="highlight-name">Xiangyu Qi$^* $</strong>, Kaixuan Huang$^* $, Ashwinee Panda, Peter Henderson, Mengdi Wang, Prateek Mittal<br>
<a class="btn" href="https://ojs.aaai.org/index.php/AAAI/article/view/30150">Paper</a>
<a class="btn" href="https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models">Code</a>

<br>


<div class="paper-title">
  <a href="https://arxiv.org/abs/2205.13616"><strong>Towards A Proactive ML Approach for Detecting Backdoor Poison Samples</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://www.usenix.org/conference/usenixsecurity23">USENIX Security, 2023</a>. <br>
</div>
<strong class="highlight-name">Xiangyu Qi</strong>, Tinghao Xie, Jiachen T. Wang, Tong Wu, Saeed Mahloujifar, Prateek Mittal<br>
<a class="btn" href="https://www.usenix.org/conference/usenixsecurity23/presentation/qi">Paper & An Oral Presentation</a>
<a class="btn" href="https://github.com/Unispac/Fight-Poison-With-Poison">Code</a>

<br>
  



<div class="paper-title">
  <a href="https://arxiv.org/abs/2205.13613"><strong>Revisiting the Assumption of Latent Separability for Backdoor Defenses</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://iclr.cc/Conferences/2023">ICLR, 2023</a>. <br>
</div>
<strong class="highlight-name">Xiangyu Qi$^* $</strong>, Tinghao Xie$^* $, Yiming Li, Saeed Mahloujifar, Prateek Mittal<br>
<a class="btn" href="https://openreview.net/forum?id=_wSHsgrVali">Paper</a>
<a class="btn" href="https://github.com/Unispac/Circumventing-Backdoor-Defenses">Code</a>

<br>


<div class="paper-title">
  <a href="https://arxiv.org/abs/2111.12965"><strong>Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://cvpr2022.thecvf.com/home">CVPR, 2022</a>. <span class="lightning-icon highlight-oral">Oral Presentation, 4.2%</span><br>
</div>
<strong class="highlight-name">Xiangyu Qi$^* $</strong>, Tinghao Xie$^* $, Ruizhe Pan, Jifeng Zhu, Yong Yang, Kai Bu<br>
<a class="btn" href="https://www.computer.org/csdl/proceedings-article/cvpr/2022/694600n3337/1H1lHZuphBe">Paper</a>
<a class="btn" href="https://github.com/Unispac/Subnet-Replacement-Attack">Code</a>


<br>


<div class="paper-title">
  <a href="https://arxiv.org/abs/2106.06235"><strong>Knowledge Enhanced Machine Learning Pipeline <br>against Diverse Adversarial Attacks</strong></a>
</div>
<div class="paper-subtitle">
  <a class="location-icon" href="https://icml.cc/Conferences/2021">ICML, 2021</a>.<br>
</div>
Nezihe Merve Gürel$^*$, <strong class="highlight-name">Xiangyu Qi$^* $</strong>, Luka Rimanic, Ce Zhang, Bo Li<br>
<a class="btn" href="https://proceedings.mlr.press/v139/gurel21a.html">Paper</a>
<a class="btn" href="https://github.com/AI-secure/Knowledge-Enhanced-Machine-Learning-Pipeline">Code</a>