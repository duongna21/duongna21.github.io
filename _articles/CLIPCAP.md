---
title: "ClipCap with Translation for Image Captioning"
category: articles
permalink: "/articles/CLIPCAP/"
venue: "Vietnamese Language and Speech Processing (VLSP)"
date: 16-12-2021
link:
---
[comment]: <>
Thanh Le, <b>Duong Nguyen</b>, Binh Nguyen

Abstract: We present a multitask learning method that achieved 0.309 and 0.313 avg. BLEU score respectively on VieCap4H public and private test set, with under 10k image-text pairs and no external images data. To achieve this results, we adapt the approach of ClipCap architecture that leverages powerful contrastive language-image pretrained model to efficiently train image captioning. The main challenge when training ClipCap is the limited of the VieCap4H dataset. We hence propose a simple method that joint training image captioning with translation to overcome this limit. We also explore the zero-shot image captioning capability of our approach and show promising results. An interactive online demo of our zero-shot model is available at this huggingface hub. Our code, data and trained models are available at https://github.com/Luvata/vlsp_viecap4h_gptteam_code.
