---
title: "A Robust Audio Watermarking Method Based on Dual-Encoder U-Net and Short-Time Fourier Transform"
collection: publications
category: manuscripts
#permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Authors: Shuangbing Wen; **Hanzhong Tan**; Lingfeng Zhang; Jun Li; Tao Hu'  # 'This paper is about the number 1. The number 2 is left for future work.'
date: 2026-04-18
venue: 'Cyber Security and Applications (EI)'
#slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S2772918426000068?via%3Dihub'  #'https://link.springer.com/content/pdf/10.1007/s40747-024-01425-z.pdf'
#The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
#bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Audio watermarking technology plays a crucial role in digital copyright protection and content authentication. In recent years, audio watermarking methods based on deep neural networks have attracted significant attention. These methods typically consist of an encoder, a distortion simulation layer, and a decoder, enabling end-to-end training for watermark embedding and extraction. However, existing approaches still face limitations in encoder structure design, primarily reflected in the insufficient fusion between watermarks and audio features, as well as the restricted ability to model spectral details and overall structures, which affects the imperceptibility and robustness of audio watermarks. To address these issues, this paper proposes a robust audio watermarking method based on a dual-encoder U-Net and Short-Time Fourier Transform. The proposed framework constructs an embedding and extraction network for audio watermarking. Specifically, the watermark embedding network consists of a dual-encoder U-Net and a multi-scale feature fusion module, which effectively extracts and integrates features from the audio amplitude spectrogram and the watermark sequence, embedding the watermark into different spectral regions to enhance imperceptibility. Meanwhile, the watermark extraction network introduces a multi-scale fusion module that integrates local and global features through parallel convolutional paths with different receptive fields, significantly improving the watermark extraction performance. Experimental results show that the proposed method not only exhibits good imperceptibility compared to other methods on the three public datasets but also demonstrates excellent robustness against multiple attacks, with watermark extraction accuracy approaching 100% under most attacks.
