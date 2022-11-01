# PT-FSE-github.io

### Paper
Speech Enhancement with Perceptually-motivated Optimization and Dual Transformations

### Arxiv
https://arxiv.org/abs/2209.11905 

### Abstract
To address the monaural speech enhancement problem, numerous research studies have been conducted to enhance speech via operations either in time-domain on the inner-domain
learned from the speech mixture or in time-frequency domain on the fixed full-band STFT spectrograms. Very recently, a few studies on sub-band based speech enhancement have been
proposed. By enhancing speech via operations on sub-band spectrograms, those studies demonstrated competitive performances on the benchmark dataset of DNS2020. Despite attractive, this
new research direction has not been fully explored and there is still room for improvement. As such, in this study, we delve into the latest research direction and propose a sub-band
based speech enhancement system with perceptually-motivated optimization and dual transformations, called PT-FSE. Specially, our proposed PT-FSE model improves its backbone, a full-band
and sub-band fusion model, by three efforts. First, we design a frequency transformation module that aims to strengthen the global frequency correlation. Then a temporal transformation
is introduced to capture long range temporal contexts. Lastly, a novel loss, with leverage of properties of human auditory perception, is proposed to facilitate the model to focus on low
frequency enhancement. To validate the effectiveness of our proposed model, extensive experiments are conducted on the DNS2020 dataset. Experimental results show that our PT-FSE
system achieves substantial improvements over its backbone, but also outperforms the current state-of-the-art while being 27% smaller than the SOTA. With average NB-PESQ of 3.57
on the benchmark dataset, our system offers the best speech enhancement results reported till date. 

### Demos
https://xuchengone.github.io/PT-FSE-github.io/ 

### Information
Accepted to APSIPA ASC 2022
