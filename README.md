# Interpretable Deep Multimodal Fusion (DMFusion) framework

This open-source repository contains the code of Interpretable Deep Multimodal Fusion (DMFusion) for 
1) cohesive fusion of imaging and non-imaging medical data;
2) assisting interpretation of complex non-linear cross-modal association.

The framework could provide clinicians with more accurate diagnostic decisions and uncovering the disease mechanism underlying the multimodal deep learning decisions. The framework was validated on a diagnostic task of differeniating two neurolgical diseases, multiple sclerosis (MS) and neuromyelitis optica (NMO). 

The algorithm is accepted by International Joint Conference of Neural Network (IJCNN) 2021 in the form of oral presentation. The code will be released soon. 

![image](https://user-images.githubusercontent.com/10879680/120273650-22ffdd80-c2f2-11eb-9408-1d33fc828c71.png)


# Our contributions
- A novel **DMFusion loss** is proposed to optimize discovery discriminative multimodal representations, by jointly exploiting inter-modal consensus via CCA, and intra-modal structural and discriminative information via reconstruction and cross-entropy loss. 
- A **cross-modal interpretation module** is proposed to quantify the importance of input features towards the correlated association, by harnessing integrated gradients in deep network and canonical loading in CCA projection.  

# Prerequisites
- Python (3.7)
- Sklearn
- Numpy
- Torch
- Sktorch
- Captum

# Citation
Xin B, Huang J, Zhou Y, Lu J, Wang X. Interpretation on Deep Multimodal Fusion for Diagnostic Classification. IJCNN. 2020 (Oral Presentation)
