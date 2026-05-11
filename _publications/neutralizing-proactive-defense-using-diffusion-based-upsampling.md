---
title: "Neutralizing Proactive Defense using Diffusion-based Upsampling"
collection: publications
category: conferences
permalink: /publication/neutralizing-proactive-defense-using-diffusion-based-upsampling
excerpt: ''
date: 2026-06-17
venue: 'ACM IH&MMSec, Florence, Italy, June 17-19, 2026'
#slidesurl: 'https://giuseppedaidone.github.io/files/slides1.pdf'
paperurl: '#'
bibtexurl: '#'
citation: 'Daidone, Giuseppe and Bartolucci, Filippo and Briglia, Maria Rosaria and Mirza, Mujtaba Hussain and Lisanti, Giuseppe and Masi, Iacopo, &quot;Neutralizing Proactive Defense using Diffusion-based Upsampling&quot;, <i>Proceedings of the 2026 ACM Workshop on Information Hiding and Multimedia Security</i>, 2026'
---
The rapid spread of open-source generative models has made it easy to create highly realistic manipulated media, posing a critical threat to content authenticity and provenance. Proactive image protection mechanisms have recently emerged as a promising defense, embedding imperceptible or characteristic signals into images to enable reliable manipulation detection. However, their robustness under realistic and adversarial post-release conditions remains largely unexplored. In this work, we present a systematic evaluation of the robustness of recent state-of-the-art proactive image protection schemes in a black-box setting. We analyze the resilience of PADL and DiffVax protections against a broad range of attacks, including classical image transformations and diffusion-based reconstruction attacks that implicitly re-synthesize image content while preserving perceptual quality. Our results reveal that, despite strong performance under limited perturbations, current proactive defenses are vulnerable to unseen image manipulations and generative reconstruction attacks. Considering PADL, we empirically demonstrate that adding diffusion-based upsampling attacks in the training does not improve robustness, without increasing protection intensity. These findings expose critical gaps between assumed and real-world threat models, highlighting the need for more robust proactive protection designs and standardized evaluation protocols for trustworthy digital media.
