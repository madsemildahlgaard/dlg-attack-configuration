# Influence of attack configurations on the reconstruction of medical images in federated learning
Code for paper under review for MIDL 2022 about privacy in federated machine learning.

We explore the robustness and techniques of deep leakage from gradients (DLG) [[1]](#1). We investigate the influence of different initalization methods and distance measures by comparing the convergence rate and speed of single image reconstructions. Specifically, we compare the results with SAPAG [[2]](#2).

### Algorithm
![DLG illustration](https://github.com/NielsFuglsang/02460-advanced-machine-learning/blob/main/assets/DLGillustration.PNG?raw=true)

### References
<a id="1">[1]</a> 
Zhu et. al (2020).
"Deep Leakage from Gradients”
Lecture Notes in Computer Science (including sub-series Lecture Notes in Artificial Intelligence and LectureNotes in Bioinformatics), vol. 12500 LNCS, no. NeurIPS,pp. 17–31.

<a id="2">[2]</a> 
Wang et. al. (2020).
“SAPAG: A self-adaptive privacy attackfrom gradients,”.
arXiv.
