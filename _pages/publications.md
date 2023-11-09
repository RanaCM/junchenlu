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

* **Junchen Lu**, Berrak Sisman, Mingyang Zhang, Haizhou Li, "High-Quality Automatic Voice Over with Accurate Alignment: Supervision through Self-Supervised Discrete Speech Units," INTERSPEECH 2023, Dublin, Ireland, Aug 2023. [**[code]**](https://github.com/RanaCM/DSU-AVO)

* **Junchen Lu**, Berrak Sisman, Rui Liu, Mingyang Zhang, Haizhou Li, "VisualTTS: TTS with Accurate Lip-Speech Synchronization for Automatic Voice Over," ICASSP 2022, Singapore, May 2022.

* **Junchen Lu**, Kun Zhou, Berrak Sisman, Haizhou Li, "VAW-GAN for Singing Voice Conversion with Non-Parallel Training Data," APSIPA ASC 2020, Auckland, New Zealand, Dec 2020. [**[code]**](https://github.com/RanaCM/Singing-Voice-Conversion-with-Conditional-VAW-GAN)

* Zongyang Du, **Junchen Lu**, Kun Zhou, Berrak Sisman, "Converting Anyone's Voice: End-to-End Expressive Voice Conversion with a Conditional Diffusion Model," under review as a conference paper.