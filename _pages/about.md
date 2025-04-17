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

I am currently pursuing a Ph.D. at KAUST, supervised by Prof.[Juergen Schmidhuber](https://scholar.google.com/citations?user=gLnCTgIAAAAJ&hl=en). Previously, I interned at Meta AI in London, working on foundational generative models, and at Tencent in Shenzhen, focusing on GAN-based image synthesis and medical imaging. My research centers on multimodal generative models—particularly video and image generation—with the long-term goal of developing a Physical AI Model (world model). I am (co-)first author of over 10 papers in top-tier venues, with more than 700 citations on Google Scholar. Several of my favorite co-authored projects include [BoxDiff](https://github.com/showlab/BoxDiff), an early training-free controllable diffusion model; [NLSOM](https://arxiv.org/abs/2305.17066), a pioneering position paper on natural language agentic systems; [TGATE](https://github.com/HaozheLiu-ST/T-GATE), the first caching systems for diffusion transformers; and [MarDini](https://mardini-vidgen.github.io/), an early but powerful Auto-Regressive video diffusion model. Beyond this, I also co-developed the pretraining of a 7B commercial text-to-image model at Meta, scaling to over 5B parameters and 1B training samples.  My curriculum vitae can be found at [here](./haozheliu.pdf). 

I'm open to future collaborations—whether it's co-founding a venture or pursuing full-time opportunities in industry or academia. Feel free to reach out via email: `haozhe.liu[at]kaust.edu.sa`



# 🔥 News
- *2025.02*: &nbsp;🎉 One paper is accepted by CVPR!
- *2025.02*: &nbsp;🎉 One paper is accepted by TMLR!
- *2024.11*: &nbsp;🎉🎉 **I will join Meta (MPK) as Research Scientist Intern, focusing on GenAI-related topics, in Summer 2025!**
- *2024.04*: &nbsp;🎉 Promote to Ph.D. Candidate!
- *2024.02*: &nbsp;🎉 One paper is accepted by CVPR'2024!
- *2024.02*: &nbsp;🎉🎉 **I will join Meta (London) as Research Scientist Intern on Efficient Video Generation in Summer 2024!**
- *2023.12*: &nbsp;🎉 [NLSOM](https://arxiv.org/pdf/2305.17066.pdf) is recognized as the best paper at NeurIPS'2023 workshop in [Robustness of Few-shot/Zero-shot Learning in Foundation Models](https://neurips.cc/virtual/2023/workshop/66517) !
- *2023.09*: &nbsp;🎉 One paper is accepted by NeurIPS'2023!
- *2023.08*: &nbsp; Invited as a reviewer for AAAI'2024.
- *2023.07*: &nbsp;🎉🎉 Two papers are accepted by ICCV'2023!.
- *2023.02*: &nbsp;🎉🎉 Two papers are accepted by CVPR'2023!.
- *2023.02*: &nbsp; Invited as a reviewer for ICCV'2023.
- *2022.11*: &nbsp;🎉🎉 One paper is accepted by AAAI'2023 (Oral).
- *2022.11*: &nbsp; Invited as a reviewer for CVPR'2023.
- *2022.08*: &nbsp;🎉🎉 **I join AI Initiative, KAUST to pursue the Ph.D. degree under the supervision of Juergen Schmidhuber!**
- *2022.08*: &nbsp;🎉 Our team reaches to the 4th/40 in [NICO challenge](https://nicochallenge.com/) (Invited Workshop Paper in ECCV'2022).
- *2022.07*: &nbsp;🎉 One paper is accepted by ECCV'2022! 
- *2022.06*: &nbsp;🎉 Two papers are accepted by MICCAI'2022!
- *2022.05*: &nbsp;[Our method (Group-wise Inhibition)](https://github.com/LinusWu/TENET_Training) is merged into the official benchmark of [ImageNet-C](https://github.com/hendrycks/robustness)!  
- *2022.04*: &nbsp; Invited as a reviewer for ICML'2022, ECCV'2022 and MICCAI'2022.  
- *2021.10*: &nbsp; Invited as a reviewer for CVPR'2022.
- *2021.07*: &nbsp;🎉 One paper is accepted by ICCV'2021!

# 📝 Publications 

Journals: TMLR x 1, IEEE TIP x 1, IEEE TCYB x 1, IEEE TNNLS x 1, IEEE TIFS x 1, IEEE TIM x 1, MIA x 1, PR x 2

Conferences: NeurIPS x 1, CVPR x 5, ICCV x 3, ECCV x 1, MICCAI x 2, AAAI x 1.


Selected Publications:

- **Liu, H.**, Liu, S., Zhou, Z., Xu, M., Xie, Y., Han, X., ... & Pérez-Rúa, J. M. (2024). MarDini: Masked Autoregressive Diffusion for Video Generation at Scale.  _Techinical Report_ (under peer-review).

- **Liu, H.**, Zhang, W., Xie, J., Faccio, F., Xu, M., Xiang, T., ... & Schmidhuber, J. (2024). Faster Diffusion via Temporal Attention Decomposition. _TMLR_.

- **Liu, H.**, Zhang, W., Li, B., Ghanem, B., & Schmidhuber, J. Lazy Layers to Make Fine-Tuned Diffusion Models More Traceable. _Techinical Report_.

- **Liu, H.**, Zhuge, M., Li, B., Wang, Y., Faccio, F., Ghanem, B. & Schmidhuber, J. Learning to Identify Critical States for Reinforcement Learning from Videos _ICCV'2023_.

- **Liu, H.**, W Zhang, Li, B., Wu, H., He, N., Huang, Y., Li, Y., Ghanem, B. & Zheng, Y. AdaptiveMix: Improving GAN Training via Feature Space Shrinkage _CVPR'2023_.

- **Liu, H.**, Li, B., Wu, H., Liang, H., Huang, Y., Li, Y., ... & Zheng, Y. Combating Mode Collapse in GANs via Manifold Entropy Estimation.  _AAAI'2023 Oral_.

- **Liu, H.**, Wu, H., Xie, W., Liu, F., & Shen, L. Group-wise Inhibition based Feature Regularization for Robust Classification. _ICCV'2021_.

- **Liu, H.**, Zhang, W., Liu, F., Wu, H.,& Shen, L. (2021). Fingerprint Presentation Attack Detector Using Global-Local Model. _IEEE T-CYB_.

- **Liu, H.**, Zhang, W., Xie J., Wu, H., Li, B., Zhang, Z., Li, Y., Huang, Y., Ghanem, B., Y. Zheng. Decoupled Mixup for Out-of-Distribution Visual Recognition. _ECCV’2022 Workshop_. 

- Zhang, W., **Liu, H.#**, Xie, J., Faccio, F., Shou, M. Z., & Schmidhuber, J. (2024). Cross-Attention Makes Inference Cumbersome in Text-to-Image Diffusion Models. _Technical Report_. (**\# Corresponding Author**)

- Zhang, W.\*, **Liu, H.**\*, Li, B., Xie J., Huang, Y., Li, Y., Y. Zheng, Ghanem, B.. Dynamically Masked Discriminator for Generative Adversarial Networks _NeurIPS’2023_. (**\* Equal Contribution**)

- Zhuge, M.\*, **Liu, H.**\*, Faccio, F.\*, Ashley, D. R.\*, Csordás, R., Gopalakrishnan, A., ... & Schmidhuber, J. (2023). Mindstorms in Natural Language-Based Societies of Mind. _Position Paper, Best Paper@NeuralIPSW_. (**\* Equal Contribution**)

- Wu, H.\*, Chen, K.\*, **Liu, H.**\*, Zhuge, M.\*, B Li, ..., & Ghanem, B. NewsNet: A Novel Dataset for Hierarchical Temporal Segmentation _CVPR'2023_.(**\* Equal Contribution**)

- Ji, H.\*, **Liu, H.**\*, Li, Y.\*, Xie J., He, N., Huang, Y., Dong, W., Chen, X., Shen L. & Zheng, Y. Point Beyond Class: A Benchmark for Weakly Semi-Supervised Abnormality Localization in Chest X-Rays.  _MICCAI'2022_. (**\* Equal Contribution**)

- Zhang, W.\*, **Liu, H.**\*, Liu, F., Ramachandra, R., & Busch, C. Effective Presentation Attack Detection Driven by Face Related Task. _ECCV'2022_.(**\* Equal Contribution**)

# 🎖 Honors and Awards
- *2023* Best Paper Award at NeuralIPS Workshop in Robustness of Few-shot/Zero-shot Learning in Foundation Models
- *2022* Outstanding Graduate Award (**Rate<5%**)
- *2021* China National Scholarship (**Rate<0.02%**)
- *2020* Excellent Academic Scholarship, First Class 
- *2019* Excellent Academic Scholarship, Second Class 
- *2018* National University Big Data Application Innovation Competition in Northwest, First Place

# 📖 Research Experience

### Meta AI 
 Research Scientist Internship working with [Juan-Manuel Pérez-Rúa](https://scholar.google.com/citations?user=Vbvimu4AAAAJ&hl=en). 
 
- Research Topic: Foundational Training, Image-to-Video Generation, Text-to-Image Generation.
- Publication Records: TMLR x 1; CVPR x 1; Under Review x 2
- Co-Developing a foundtional text-to-image model (model size >5B; data pairs >1B) to support several well-known products.
- Scaling auto-regressive diffusion to video generation.

### AI Initiative (KAUST) 
 PhD Candidate supervised by Prof. [Juergen Schmidhuber](https://scholar.google.com/citations?user=gLnCTgIAAAAJ&hl=en).

- Research Topic: Neural Networks with Multiple-Step Inferences, e.g., Diffusion Model, Auto-Regressive Model, and  RL Agents.
- Publication Records: ICCV x 1; CVPR x 2; NIPSW x 1;  TMLR x 1, Under Review x 2.
- Highlight: NLSOM is awarded Best paper@NIPS'23 Ro-FoMo Workshop.
- Highlight: TGate is merged into the Diffusers Library and received over 300 stars on GitHub.

---

### Jarvis Lab (Tencent) 
Internship supervised by Mentor: [Dr. Yawen Huang](https://yawen-hwang.github.io/), [Dr. Nanjun He](https://scholar.google.ch/citations?user=w3iS1G0AAAAJ&hl=en) & [Dr. Yuexiang Li](https://scholar.google.com/citations?user=WsKu4EMAAAAJ&hl=en) and Director: [Dr. Yefeng Zheng](https://scholar.google.ch/citations?user=vAIECxgAAAAJ&hl=en) 
  
- Research Topic: Generative Model and Medical Imaging.
- Publication Records: NIPS x 1, CVPR x 1; ICCV x 1; AAAI x 1; MICCAI x 2; MIA x 1; PR x 1; ECCVW x 1. 
- Highlight: MaF-GAN is recognized as \textbf{Oral} paper@AAAI.
- Highlight: Ranked 4th in ECCV'2022 NICO Challenge.

---

### Norwegian Biometrics Laboratory (NTNU)
Visiting student supervised by  [Prof. Raghavendra Ramachandra](https://scholar.google.com/citations?user=OIYIrmIAAAAJ&hl=en) and [Prof. Christoph Busch](https://scholar.google.com/citations?user=qsopcXIAAAAJ&hl=en)

- Research Topic: AI Safety, Facial/Fingerprint Recognition System.
- Publication Records: ECCV x 1, IEEE TNNLS x 1.

---

### Computer Vision Insitute (SZU)
M.S. supervised by [Prof. Feng Liu](https://scholar.google.com/citations?hl=zh-CN&user=45uLWocAAAAJ) and [Prof. Linlin Shen](https://scholar.google.com/citations?hl=zh-CN&user=AZ_y9HgAAAAJ)
- Research Topic: AI Safety, Facial/Fingerprint Recognition System.
- Publication Records: CVPR x 1; ICCV x 1; IEEE TIP x 1; IEEE TCYB x 1, IEEE TIFS x 1, IEEE TIM x 1.
- Highlight: Recognized as China National Scholarship and Outstanding Graduate Award.

# 💻 Professional Service

### Conference Reviewer 
- CVPR: 2022, 2023
- ECCV: 2022, 2024
- ICCV: 2023
- AAAI: 2024
- ICML: 2022
- MICCAI: 2022
