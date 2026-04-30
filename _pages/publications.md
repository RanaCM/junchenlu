---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

1. **Junchen Lu**, Berrak Sisman, Mingyang Zhang, Haizhou Li. *"High-Quality Automatic Voice Over with Accurate Alignment: Supervision through Self-Supervised Discrete Speech Units."* INTERSPEECH 2023. [**[code]**](https://github.com/RanaCM/DSU-AVO)

2. **Junchen Lu**, Berrak Sisman, Rui Liu, Mingyang Zhang, Haizhou Li. *"VisualTTS: TTS with Accurate Lip-Speech Synchronization for Automatic Voice Over."* ICASSP 2022.

3. **Junchen Lu**, Kun Zhou, Berrak Sisman, Haizhou Li. *"VAW-GAN for Singing Voice Conversion with Non-Parallel Training Data."* APSIPA ASC 2020. [**[code]**](https://github.com/RanaCM/Singing-Voice-Conversion-with-Conditional-VAW-GAN)

4. **Junchen Lu**, Berrak Sisman, Haizhou Li. *"Cross-Modal Contrastive Learning for Visual-Aware Prosody Modeling in Automatic Voice Over."* IEEE Journal, under review (2026).

5. Ismail Rasim Ulgen, Zongyang Du, **Junchen Lu**, Philipp Koehn, Berrak Sisman. *"Objective Evaluation of Prosody and Intelligibility in Speech Synthesis via Conditional Prediction of Discrete Tokens."* IEEE Open Journal of Signal Processing, 2026 (to present at ICASSP 2026).

6. Ke Gu, Zhicong Wu, Peng Bai, Sitong Qiao, Zhiqi Jiang, **Junchen Lu**, Xiaodong Shi, Xinyuan Qian. *"PerformSinger: Multimodal Singing Voice Synthesis Leveraging Synchronized Lip Cues."* ICASSP 2026.

7. Shreeram Suresh Chandra, Lucas Goncalves, **Junchen Lu**, Carlos Busso, Berrak Sisman. *"EmotionRankCLAP: Bridging Natural Language Speaking Styles and Ordinal Speech Emotion via Rank-N-Contrast."* INTERSPEECH 2025.

8. Ahad Jawaid, Shreeram Suresh Chandra, **Junchen Lu**, Berrak Sisman. *"Style Mixture of Experts for Expressive Text-to-Speech Synthesis."* NeurIPS 2024 Workshop (Audio Imagination).

9. Zongyang Du, **Junchen Lu**, Kun Zhou, Berrak Sisman. *"Converting Anyone's Voice: End-to-End Expressive Voice Conversion with a Conditional Diffusion Model."* Odyssey 2024.