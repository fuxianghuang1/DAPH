# DAPH: Domain Adaptation Preconceived Hashing for Unconstrained Visual Retrieval

Author : Fuxiang Huang, Lei Zhang, and Xinbo Gao

Published in TNNLS 2021

Contact : huangfuxiang@cqu.edu.cn

Usage:  MATLAB R2017

Running Models:  Run main_demo.m

More datasets are available at https://pan.baidu.com/s/1EVlYCz51AyDnh5y7PJ5W_Q?pwd=qyrv

*If you want to cite the experimental results, please pay attention to the experimental details in the paper. For example, for handwritten digit datasets (i.e., MNIST and USPS),  we use 60000 images from the MNIST as the source domain and 10000 images from the USPS as the target domain, which is different from PWCF pubilished in CVPR2020, i.e., Probability Weighted Compact Feature for Domain Adaptive Retrieval. Besides, for each dataset, we randomly select 10% of the target images as the test set (i.e., queries) and the rest images as the training set data. However, we select 500 target images as the test set in PWCF. Therefore, the results are different in this two papers. 


Cite: If you find this code useful in your research then please cite
```bibtex
@articale{huang2021domain,
  author={Huang, Fuxiang and Zhang, Lei and Gao, Xinbo},    
  journal={IEEE Transactions on Neural Networks and Learning Systems},    
  title={Domain Adaptation Preconceived Hashing for Unconstrained Visual Retrieval},    
  year={2021},  
  pages={1-15},    
  doi={10.1109/TNNLS.2021.3071127}  
}

@inproceedings{huang2020PWCF,
  title={Probability Weighted Compact Feature for Domain Adaptive Retrieval},
  author={Huang, Fuxiang and Zhang, Lei and Yang, Yang and Zhou, Xichuan},    
  booktitle={CVPR},    
  pages={9579-9588},    
  year={2020}
}
```bibtex
