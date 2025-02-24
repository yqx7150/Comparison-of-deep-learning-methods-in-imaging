# Comparison-of-deep-learning-methods-in-imaging
Comparison of deep learning methods in imaging: Supervised, unsupervised and self-supervised learning

References:    
[1] Wang S, Xiao T, Liu Q, Zheng H. Deep learning for fast MR imaging: a review for learning reconstruction from incomplete k-space data. Biomed Signal Process Control. 2021; 68:102579. [<font size=5>**[Paper]**</font>](https://www.sciencedirect.com/science/article/abs/pii/S1746809421001762)  
    
[2] Wang S, Wu R, Jia S, et al. Knowledge-driven deep learning for fast MR imaging: Undersampled MR image reconstruction from supervised to un-supervised learning. Magn Reson Med. 2024; 1-23. [<font size=5>**[Paper]**</font>](https://onlinelibrary.wiley.com/doi/10.1002/mrm.30105)       


## Three Learning Strageties
## Supervised Learning (SL)：   
Classically, standard supervised learning based methods approach this problem by collecting data sets of known latent images and their corresponding measurements. Specifically, it utilize data information to train a universal network for learning the mapping between the under-sampled and fully sampled data pairs in an end-to-end manner. Hence, the supervised method is known to be effective when a large training dataset with accurate labels is available.

## Unsupervised Learning (USL)：
The way of unsupervised learning is to formulate deep learning by using only under-sampled datasets for training. It also relates mostly to generative models which try to estimate the latent data distributions.

## Self-supervised Learning (SSL)：
No ground-truth is used in self-supervised learning and aims at solving the inverse problem by exploiting internal information within the measurements themselves.

<div align="center"><img src="https://github.com/yqx7150/Comparison-of-deep-learning-methods-in-imaging/blob/main/Figs/1.png">  </div>
    
    
    
<div align="center"><img src="https://github.com/yqx7150/Comparison-of-deep-learning-methods-in-imaging/blob/main/Figs/2.png"> </div>
      
    
    
<div align="center"><img src="https://github.com/yqx7150/Comparison-of-deep-learning-methods-in-imaging/blob/main/Figs/3.png"> </div>
      
   
   
## A review of SL for MRI Rec
S. Wang, D. Liang, et al., “Accelerating magnetic resonance imaging via deep learning,” ISBI, 2016.      
J. Sun, Z. Xu, et al., “Deep ADMM-net for compressive sensing MRI,” NIPS, 2016.     
K Kwon, et al., “Learning-based reconstruction using artiﬁcial neural network for higher acceleration,” ISMRM, 2016.    
......    
D. Lee, et al., “Compressed sensing and parallel MRI using deep residual learning,” ISMRM, 2017.     
K. Kwon, et al., “A parallel MR imaging method using multilayer perceptron,” MP, 2017.    
......    
J. Schlemper, et al., “A deep cascade of convolutional neural networks for dynamic MR image reconstruction,” IEEE TMI, 2018.  
D. Lee, J. Ye, et al., “Deep residual learning for accelerated MRI using magnitude and phase networks,” IEEE TBME, 2018.  
Y. Han, et al., “Deep learning with domain adaptation for accelerated projection-reconstruction MR,” MRM, 2018.  
T. Eo, et al., “KIKI-net: Cross-domain convolutional neural networks for reconstructing undersampled magnetic resonance images,” MRM, 2018.  
C. Qin, et al., “Convolutional recurrent neural networks for dynamic MR image reconstruction,” IEEE TMI, 2018.  
G. Yang, et al., “Dagan: Deep de-aliasing generative adversarial networks for fast compressed sensing MRI reconstruction,” IEEE TMI, 2018.  
M. Akçakaya , et al., “Subject-specific convolutional neural networks for accelerated magnetic resonance imaging,” IJCNN, 2018.  
B. Zhu, et al., “Image reconstruction by domain-transform manifold learning,” Nature, 2018.  
......   
Y. Liu, Q. Liu, D. Liang et al., IFR-Net: Iterative feature refinement network for compressed sensing MRI, IEEE TCI, 2020 .    
W. Zeng, et al., “A comparative study of CNN-based super-resolution methods in MRI reconstruction and its beyond,” Signal Processing: Image Communication, 2020.  
Antun V, Renna F, Poon C, et al., On instabilities of deep learning in image reconstruction and the potential costs of AI, PNAS, 2020.     
......   

<div align="center"><img src="https://github.com/yqx7150/Comparison-of-deep-learning-methods-in-imaging/blob/main/Figs/4.png"> </div>

## A review of USL for MRI Rec
Tezcan KC, Baumgartner CF, Luechinger R, Pruessmann KP, Konukoglu E. MR image reconstruction using deep density priors. IEEE Trans. Med. Imaging, vol. 38 pp. 1633-1642, 2018.   
G. Luo, N. Zhao, W. Jiang, E.S. Hui, C. Peng. MRI reconstruction using deep Bayesian estimation. Magn. Reson. Med. 2020. https://doi.org/10.1002/mrm.28274        
Q. Liu, Q. Yang, H. Cheng, S. Wang, M. Zhang, D. Liang, Highly undersampled magnetic resonance imaging reconstruction using autoencoding priors, Magn. Reson. Med., vol. 83, no. 1, pp. 322-336, 2020.           
M. Zhang, M. Li, J. Zhou, Y, Zhu, S. Wang, D. Liang, Y. Chen, Q. Liu. High-dimensional embedding network derived prior for compressive sensing MRI reconstruction, Med. Image Anal., vol. 64, 101717, 2020.       
C. Quan, J. Zhou, Y. Zhu, Y. Chen, S. Wang, D. Liang, Q. Liu, Homotopic gradients of generative density priors for MR image reconstruction, IEEE Trans. Med. Image., 2020.    
......   
Z. He, Q. Liu, et al., A comparative study of unsupervised deep learning methods in MRI reconstruction, iMRI, 2020, ASMRM, 2020.    
......      

<div align="center"><img src="https://github.com/yqx7150/Comparison-of-deep-learning-methods-in-imaging/blob/main/Figs/6.png"> </div>

## A review of SSL for MRI Rec
B. Yaman, et at., Self-supervised learning of physics-guided reconstruction neural networks without fully sampled reference data, MRM, 2020.     
K. H. Jin, et at., Self-supervised deep active accelerated MRI, arXiv, 2019.      
B. Yaman, et at., Multi-mask self-supervised learning for physics-guided neural networks in highly accelerated MRI, arXiv, 2020.    
A. Taleb, et at., Multimodal self-supervised learning for medical image analysis, arXiv, 2019.      
......      

<div align="center"><img src="https://github.com/yqx7150/Comparison-of-deep-learning-methods-in-imaging/blob/main/Figs/5.png"> </div>



## Other Related Projects
  * Comparison of deep learning methods in imaging: Supervised, unsupervised and self-supervised learning  
[<font size=5>**[Slide]**</font>](https://github.com/yqx7150/Comparison-of-deep-learning-methods-in-imaging/tree/main/Slide)

   * IFR-Net: Iterative Feature Refinement Network for Compressed Sensing MRI [<font size=5>**[Paper]**</font>](https://ieeexplore.ieee.org/document/8918016)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/IFR-Net-Code)
    
  * A Comparative Study of CNN-based Super-resolution Methods in MRI Reconstruction and Its Beyond [<font size=5>**[Paper]**</font>](https://sciencedirect.xilesou.top/science/article/abs/pii/S0923596519302358)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/DCCN)

  * Highly Undersampled Magnetic Resonance Imaging Reconstruction using Autoencoding Priors  [<font size=5>**[Paper]**</font>](https://cardiacmr.hms.harvard.edu/files/cardiacmr/files/liu2019.pdf)  [<font size=5>**[Code]**</font>](https://github.com/yqx7150/EDAEPRec)   [<font size=5>**[Slide]**</font>](https://github.com/yqx7150/EDAEPRec/tree/master/Slide)

  * High-dimensional Embedding Network Derived Prior for Compressive Sensing MRI Reconstruction [<font size=5>**[Paper]**</font>](https://www.sciencedirect.com/science/article/abs/pii/S1361841520300815?via%3Dihub)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/EDMSPRec)
 
  * Denoising Auto-encoding Priors in Undecimated Wavelet Domain for MR Image Reconstruction  [<font size=5>**[Paper]**</font>](https://arxiv.org/ftp/arxiv/papers/1909/1909.01108.pdf)  [<font size=5>**[Code]**</font>](https://github.com/yqx7150/WDAEPRec)

  * Homotopic Gradients of Generative Density Priors for MR Image Reconstruction  [<font size=5>**[Paper]**</font>](https://arxiv.org/abs/2008.06284)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/HGGDP)

  * Complex-valued MRI data from SIAT--test31 [<font size=5>**[Data]**</font>](https://github.com/yqx7150/EDAEPRec/tree/master/test_data_31)

  * Complex-valued MRI data from SIAT--SIAT_MRIdata200 [<font size=5>**[Data]**</font>](https://github.com/yqx7150/SIAT_MRIdata200)


