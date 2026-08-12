---
title: "Frequency-Gated Prompting for Enhancing Transformer-based EEG Decoding"
collection: publications
category: manuscripts
#permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Authors: **Hanzhong Tan**; Shuangbing Wen; Tao Hu; Jun Li; Zhiqiang Zhang'
date: 2026-08-12
venue: 'IEEE Journal of Biomedical and Health Informatics (SCI-Q1 TOP, CCF-C, IF=7.7)'
#slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://liangjiaxiaoqi.github.io/files/2026-08-12-Frequency_Gated_Prompting_for_Enhancing_Transformer_based_EEG_Decoding.pdf'
bibtexurl: 'https://liangjiaxiaoqi.github.io/files/2026-07-09-Competitive_fusion_in_multimodal_networks_for_enhanced_salient_object_detection-10.1007_s00371-026-04602-y-citation.ris'
#citation: 'Tan, H., Wen, S., Zhang, L. et al. Competitive fusion in multimodal networks for enhanced salient object detection. Vis Comput 42, 397 (2026). https://doi.org/10.1007/s00371-026-04602-y'
---

The fundamental problem in electroencephalogram (EEG) decoding centers on the extraction of meaningful neural patterns from complex spatio-temporal signals. Although Transformer models have garnered significant attention in this domain due to their exceptional temporal modeling capabilities, their lack of perception for critical frequency-domain features within EEG signals constrains further performance enhancement. To address this issue, this paper proposes a lightweight approach termed frequency-gated prompted Transformer (FGPT). FGPT adaptively represents global EEG rhythms by introducing learnable sparse frequency prompt tokens. Utilizing a gated fusion mechanism, it synergistically embeds these tokens with the original EEG sequence into the Transformer's self-attention computation. This enables joint modeling of spatio-temporal and frequency-domain features without compromising sequence continuity. Experiments conducted on three public EEG datasets show that FGPT improves the decoding performance and robustness of the evaluated Transformer-based models (EEG-ViT, EEG-Conformer, and EEG-Deformer) on the selected baselines. With its lightweight design and observed potential for generalization on the datasets used, this approach explores a prompt learning method that may contribute to developing more efficient EEG decoding systems. The code can be obtained from <https://github.com/liangjiaxiaoqi/FGPT>.
