# Inpainting

## Contents
 - [Image Inpainting](#image-inpainting)
 - [Video Inpainting](#video-inpainting)


## Image Inpainting

### Non-learning Inpainting

* Image inpainting (SIGGRAPH 2000). _Bertalmio, M., Sapiro, G., Caselles, V., & Ballester, C._ [[Paper]](https://www.cse.unr.edu/~bebis/CS474/StudentPaperPresentations/imageinpainting.pdf)
* Simultaneous Structure and Texture Image Inpainting (TIP 2003). _Bertalmio, M., Vese, L., Sapiro, G., & Osher, S._ [[Paper]](https://www.math.ucla.edu/~lvese/PAPERS/01217265.pdf)
* Region Filling and Object Removal by Exemplar-Based Image Inpainting (TIP 2004). _Criminisi, A., Pérez, P., & Toyama, K._ [[Paper]](http://www.irisa.fr/vista/Papers/2004_ip_criminisi.pdf)
* Image completion with structure propagation (ToG 2005). _Sun, J., Yuan, L., Jia, J., & Shum, H. Y._ [[Paper]](http://webee.technion.ac.il/cgm/Computer-Graphics-Multimedia/Undergraduate-Projects/2009/ImageCompletion/ImageCompletion_SIGGRAPH05.pdf)
* PatchMatch: A Randomized Correspondence Algorithm for Structural Image Editing (ToG 2009). _Connelly Barnes, Eli Shechtman, Adam Finkelstein, Dan B Goldman_ [[Paper]](https://gfx.cs.princeton.edu/pubs/Barnes_2009_PAR/patchmatch.pdf)[[Project]](https://gfx.cs.princeton.edu/pubs/Barnes_2009_PAR/)
* Image Completion using Planar Structure Guidance (ToG 2014). _Huang, J. B., Kang, S. B., Ahuja, N., & Kopf, J._ [[Paper]](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/01/structure_completion_small.pdf)[[Code]](https://github.com/jbhuang0604/StructCompletion)[[Project]](https://sites.google.com/site/jbhuang0604/publications/struct_completion)

### Learning Inpainting

#### 2015

* Shepard Convolutional Neural Networks (NIPS 2015). _Ren, J. S., Xu, L., Yan, Q., & Sun, W._ [[Paper]](https://papers.nips.cc/paper/5774-shepard-convolutional-neural-networks.pdf)[[Code]](https://github.com/jimmy-ren/vcnn_double-bladed/tree/master/applications/Shepard_CNN)

#### 2016

* Context Encoders: Feature Learning by Inpainting (CVPR 2016). _Pathak, D., Krahenbuhl, P., Donahue, J., Darrell, T., & Efros, A. A._ [[Paper]](https://arxiv.org/abs/1604.07379)[[Code]](https://github.com/pathak22/context-encoder)

#### 2017

* Globally and Locally Consistent Image Completion (ToG 2017). _Iizuka, S., Simo-Serra, E., & Ishikawa, H._ [[Paper]](http://iizuka.cs.tsukuba.ac.jp/projects/completion/data/completion_sig2017.pdf)[[Code]](https://github.com/satoshiiizuka/siggraph2017_inpainting)[[Project]](http://iizuka.cs.tsukuba.ac.jp/projects/completion/en/)
* High-Resolution Image Inpainting using Multi-Scale Neural Patch Synthesis (CVPR 2017). _Yang, C., Lu, X., Lin, Z., Shechtman, E., Wang, O., & Li, H._ [[Paper]](https://arxiv.org/abs/1611.09969)[[Code]](https://github.com/leehomyc/Faster-High-Res-Neural-Inpainting)
* Generative Face Completion (CVPR 2017). _Li, Y., Liu, S., Yang, J., & Yang, M. H._ [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Generative_Face_Completion_CVPR_2017_paper.pdf)[[Code]](https://github.com/Yijunmaverick/GenerativeFaceCompletion)
* Semantic Image Inpainting with Deep Generative Models (CVPR 2017). _Yeh, R. A., Chen, C., Yian Lim, T., Schwing, A. G., Hasegawa-Johnson, M., & Do, M. N._ [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yeh_Semantic_Image_Inpainting_CVPR_2017_paper.pdf)[[Code]](https://github.com/moodoki/semantic_image_inpainting)[[Project]](http://www.isle.illinois.edu/~yeh17/projects/semantic_inpaint/index.html)

#### 2018

* Generative Image Inpainting with Contextual Attention (CVPR 2018). _Yu, J., Lin, Z., Yang, J., Shen, X., Lu, X., & Huang, T. S._ [[Paper]](https://arxiv.org/abs/1801.07892)[[Code]](https://github.com/JiahuiYu/generative_inpainting)[[Project]](http://jiahuiyu.com/deepfill/)
* Natural and Effective Obfuscation by Head Inpainting (CVPR 2018). _Sun Qianru et al._ [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_Natural_and_Effective_CVPR_2018_paper.pdf)
* Eye In-Painting with Exemplar Generative Adversarial Networks (CVPR 2018). _Dolhansky, B., & Canton Ferrer, C._ [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Dolhansky_Eye_In-Painting_With_CVPR_2018_paper.pdf)[[Code]](https://github.com/bdol/exemplar_gans)[[Project]](https://bdol.github.io/exemplar_gans/)
* Disentangling Structure and Aesthetics for Style-aware Image Completion (CVPR 2018). _Gilbert, A., Collomosse, J., Jin, H., & Price, B._ [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gilbert_Disentangling_Structure_and_CVPR_2018_paper.pdf)
* UV-GAN: Adversarial Facial UV Map Completion for Pose-invariant Face Recognition (CVPR 2018). _Deng, J., Cheng, S., Xue, N., Zhou, Y., & Zafeiriou, S._ [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Deng_UV-GAN_Adversarial_Facial_CVPR_2018_paper.pdf)
* Image Inpainting for Irregular Holes Using Partial Convolutions (ECCV 2018). _Liu, G., Reda, F. A., Shih, K. J., Wang, T. C., Tao, A., & Catanzaro, B._ [[Paper]](https://arxiv.org/abs/1804.07723)[[Project]](https://nv-adlr.github.io/publication/partialconv-inpainting)
* Contextual-based Image Inpainting: Infer, Match, and Translate (ECCV 2018). _Song, Y., Yang, C., Lin, Z., Liu, X., Huang, Q., Li, H., & Jay Kuo, C. C._ [[Paper]](https://arxiv.org/abs/1711.08590)
* Shift-Net: Image Inpainting via Deep Feature Rearrangement (ECCV 2018). _Yan, Z., Li, X., Li, M., Zuo, W., & Shan, S._ [[Paper]](https://arxiv.org/abs/1801.09392v2)[[Code]](https://github.com/Zhaoyi-Yan/Shift-Net)
* Image Inpainting via Generative Multi-column Convolutional Neural Networks (NIPS 2018). _Wang, Y., Tao, X., Qi, X., Shen, X., & Jia, J._ [[Paper]](https://arxiv.org/abs/1810.08771)[[Code]](https://github.com/shepnerd/inpainting_gmcnn)
* SPG-Net: Segmentation prediction and guidance network for image inpainting (BMVC 2018). _Song, Y., Yang, C., Shen, Y., Wang, P., Huang, Q., & Kuo, C. C. J._ [[Paper]](https://arxiv.org/abs/1805.03356)
* Structural inpainting (MM 2018). _Vo, H. V., Duong, N. Q., & Pérez, P._ [[Paper]](https://arxiv.org/abs/1803.10348)
* Semantic Image Inpainting with Progressive Generative Networks (MM 2018). _Zhang, H., Hu, Z., Luo, C., Zuo, W., & Wang, M._ [[Paper]](https://dl.acm.org/doi/10.1145/3240508.3240625)[[Code]](https://github.com/crashmoon/Progressive-Generative-Networks)
* Face Completion with Semantic Knowledge and Collaborative Adversarial Learning (ACCV 2018). _Liao, H., Funka-Lea, G., Zheng, Y., Luo, J., & Zhou, S. K._ [[Paper]](https://arxiv.org/pdf/1812.03252.pdf)
* Edge-Aware Context Encoder for Image Inpainting (ICASPP 2018). _Liao, L., Hu, R., Xiao, J., & Wang, Z._ [[Paper]](http://150.162.46.34:8080/icassp2018/ICASSP18_USB/pdfs/0003156.pdf)
* FaceShop: Deep Sketch-based Face Image Editing (ToG 2018). _Portenier, T., Hu, Q., Szabó, A., Bigdeli, S. A., Favaro, P., & Zwicker, M._ [[Paper]](https://arxiv.org/abs/1804.08972)

#### 2019

* Pluralistic Image Completion (CVPR 2019). _Zheng, C., Cham, T. J., & Cai, J._ [[Paper]](https://arxiv.org/abs/1903.04227)[[Code]](https://github.com/lyndonzheng/Pluralistic-Inpainting)[[Project]](http://www.chuanxiaz.com/publication/pluralistic/)
* Learning Pyramid-Context Encoder Network for High-Quality Image Inpainting (CVPR 2019). _Zeng, Y., Fu, J., Chao, H., & Guo, B._ [[Paper]](https://arxiv.org/abs/1904.07475)[[Code]](https://github.com/researchmm/PEN-Net-for-Inpainting)
* Foreground-aware Image Inpainting (CVPR 2019). _Xiong, W., Lin, Z., Yang, J., Lu, X., Barnes, C., & Luo, J._ [[Paper]](https://arxiv.org/abs/1901.05945)
* PEPSI : Fast Image Inpainting with Parallel Decoding Network (CVPR 2019). _Sagong, M. C., Shin, Y. G., Kim, S. W., Park, S., & Ko, S. J._ [[Paper]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Sagong_PEPSI__Fast_Image_Inpainting_With_Parallel_Decoding_Network_CVPR_2019_paper.pdf)
* Generative Image Inpainting with Submanifold Alignment (IJCAI 2019). _Ang Li, Jianzhong Qi, Rui Zhang, Xingjun Ma, Kotagiri Ramamohanarao._ [[Paper]](https://arxiv.org/abs/1908.00211)
* MUSICAL: Multi-Scale Image Contextual Attention Learning for Inpainting (IJCAI 2019). _Wang, N., Li, J., Zhang, L., & Du, B._ [[Paper]](https://www.ijcai.org/Proceedings/2019/0520.pdf)
* Coarse-to-Fine Image Inpainting via Region-wise Convolutions and Non-Local Correlation (IJCAI 2019). _Ma, Y., Liu, X., Bai, S., Wang, L., He, D., & Liu, A._ [[Paper]](https://www.ijcai.org/Proceedings/2019/0433.pdf)[[Code]](https://github.com/vickyFox/Region-wise-Inpainting)
* StructureFlow: Image Inpainting via Structure-aware Appearance Flow (ICCV 2019). _Yurui Ren, Xiaoming Yu, Ruonan Zhang, Thomas H. Li, Shan Liu, Ge Li_ [[Paper]](https://arxiv.org/abs/1908.03852)[[Code]](https://github.com/RenYurui/StructureFlow)
* Coherent Semantic Attention for Image Inpainting (ICCV 2019). _Hongyu Liu, Bin Jiang, Yi Xiao, Chao Yang_ [[Paper]](https://arxiv.org/abs/1905.12384)[[Code]](https://github.com/KumapowerLIU/CSA-inpainting)
* Image Inpainting with Learnable Bidirectional Attention Maps (ICCV 2019). _Chaohao Xie, Shaohui Liu, Chao Li, Ming-Ming Cheng, Wangmeng Zuo, Xiao Liu, Shilei Wen, Errui Ding_ [[Paper]](https://arxiv.org/abs/1909.00968)[[Code]](https://github.com/Vious/LBAM_Pytorch)
* Free-Form Image Inpainting with Gated Convolution (ICCV 2019 oral). _Yu, J., Lin, Z., Yang, J., Shen, X., Lu, X., & Huang, T. S._ [[Paper]](https://arxiv.org/abs/1806.03589)[[Code]](https://github.com/JiahuiYu/generative_inpainting)[[Project]](http://jiahuiyu.com/deepfill/)
* Progressive Reconstruction of Visual Structure for Image Inpainting (ICCV 2019). _Jingyuan Li, Fengxiang He, Lefei Zhang, Bo Du, Dacheng Tao_ [[Paper]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Progressive_Reconstruction_of_Visual_Structure_for_Image_Inpainting_ICCV_2019_paper.pdf)[[Code]](https://github.com/jingyuanli001/PRVS-Image-Inpainting)
* FiNet: Compatible and Diverse Fashion Image Inpainting (ICCV 2019 oral). _Xintong Han, Zuxuan Wu, Weilin Huang, Matthew R. Scott, Larry S. Davis_ [[Paper]](http://211.81.63.130/cache/11/03/openaccess.thecvf.com/25bb5f528c5552cd77fe41e4c26fcc6f/Han_FiNet_Compatible_and_Diverse_Fashion_Image_Inpainting_ICCV_2019_paper.pdf)
* SC-FEGAN: Face Editing Generative Adversarial Network with User's Sketch and Color (ICCV 2019). _Youngjoo Jo, Jongyoul Park_ [[Paper]](https://arxiv.org/abs/1902.06838)[[Code]](https://github.com/run-youngjoo/SC-FEGAN)
* EdgeConnect: Structure Guided Image Inpainting using Edge Prediction (ICCVW 2019). _Nazeri, K., Ng, E., Joseph, T., Qureshi, F., & Ebrahimi, M._ [[Paper]](http://openaccess.thecvf.com/content_ICCVW_2019/papers/AIM/Nazeri_EdgeConnect_Structure_Guided_Image_Inpainting_using_Edge_Prediction_ICCVW_2019_paper.pdf)[[Code]](https://github.com/knazeri/edge-connect)
* Progressive Image Inpainting with Full-Resolution Residual Network (MM 2019). _Zongyu Guo, Zhibo Chen, Tao Yu, Jiale Chen, Sen Liu_ [[Paper]](https://arxiv.org/abs/1907.10478)[[Code]](https://github.com/ZongyuGuo/Inpainting_FRRN)
* Deep Fusion Network for Image Completion (MM 2019). _Xin Hong, Pengfei Xiong, Renhe Ji, Haoqiang Fan_ [[Paper]](https://arxiv.org/abs/1904.08060)[[Code]](https://github.com/hughplay/DFNet)
* GAIN: Gradient Augmented Inpainting Network for Irregular Holes (MM 2019). _Jianfu Zhang, Li Niu, Dexin Yang, Liwei Kang, Yaoyi Li, Weijie Zhao, Liqing Zhang_ [[Paper]](https://dl.acm.org/doi/10.1145/3343031.3350912)
* Single-shot Semantic Image Inpainting with Densely Connected Generative Networks (MM 2019). _Ling Shen, Richang Hong, Haoran Zhang, Hanwang Zhang, Meng Wang_ [[Paper]](https://dl.acm.org/doi/pdf/10.1145/3343031.3350903)

#### 2020

* Region Normalization for Image Inpainting (AAAI 2020). _Tao Yu, Zongyu Guo, Xin Jin, Shilin Wu, Zhibo Chen, Weiping Li, Zhizheng Zhang, Sen Liu_ [[Paper]](https://arxiv.org/abs/1911.10375)[[Code]](https://github.com/geekyutao/RN)
* Learning to Incorporate Structure Knowledge for Image Inpainting (AAAI 2020). _Jie Yang, Zhiquan Qi, Yong Shi_ [[Paper]](https://arxiv.org/abs/2002.04170)[[Code]](https://github.com/YoungGod/sturcture-inpainting)
* Prior Guided GAN Based Semantic Inpainting (CVPR 2020). _Avisek Lahiri, Arnav Kumar Jain, Sanskar Agrawal, Pabitra Mitra, Prabir Kumar Biswas_ [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Lahiri_Prior_Guided_GAN_Based_Semantic_Inpainting_CVPR_2020_paper.html)
* UCTGAN: Diverse Image Inpainting Based on Unsupervised Cross-Space Translation (CVPR 2020). _Lei Zhao, Qihang Mo, Sihuan Lin, Zhizhong Wang, Zhiwen Zuo, Haibo Chen, Wei Xing, Dongming Lu_ [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhao_UCTGAN_Diverse_Image_Inpainting_Based_on_Unsupervised_Cross-Space_Translation_CVPR_2020_paper.html)
* Recurrent Feature Reasoning for Image Inpainting (CVPR 2020). _Jingyuan Li, Ning Wang, Lefei Zhang, Bo Du, Dacheng Tao_ [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Li_Recurrent_Feature_Reasoning_for_Image_Inpainting_CVPR_2020_paper.html)[[Code]](https://github.com/jingyuanli001/RFR-Inpainting)
* Contextual Residual Aggregation for Ultra High-Resolution Image Inpainting (CVPR 2020). _Zili Yi, Qiang Tang, Shekoofeh Azizi, Daesik Jang, Zhan Xu_ [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Yi_Contextual_Residual_Aggregation_for_Ultra_High-Resolution_Image_Inpainting_CVPR_2020_paper.html)[[Code]](https://github.com/Ascend-Huawei/Ascend-Canada/tree/master/Models/Research_HiFIll_Model)
* 3D Photography Using Context-Aware Layered Depth Inpainting (CVPR 2020). _Meng-Li Shih, Shih-Yang Su, Johannes Kopf, Jia-Bin Huang_ [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Shih_3D_Photography_Using_Context-Aware_Layered_Depth_Inpainting_CVPR_2020_paper.html)[[Code]](https://github.com/vt-vl-lab/3d-photo-inpainting)[[Project]](https://shihmengli.github.io/3D-Photo-Inpainting/)
* Learning Oracle Attention for High-Fidelity Face Completion (CVPR 2020). _Tong Zhou, Changxing Ding, Shaowen Lin, Xinchao Wang, Dacheng Tao_ [[Paper]](http://openaccess.thecvf.com/content_CVPR_2020/html/Zhou_Learning_Oracle_Attention_for_High-Fidelity_Face_Completion_CVPR_2020_paper.html)
* Multistage Attention Network for Image Inpainting (Pattern Recognition 2020). _N Wang, S Ma, J Li, Y Zhang, L Zhang_ [[Paper]](https://www.sciencedirect.com/science/article/pii/S003132032030251X)
* Rethinking image inpainting via a mutual encoder-decoder with feature equalization (ECCV 2020).
* VCNet: A Robust Approach to Blind Image Inpainting (ECCV 2020). _Yi Wang, Ying-Cong Chen, Xin Tao, Jiaya Jia_ [[Paper]](https://arxiv.org/abs/2003.06816)
* Guidance and Evaluation: Semantic-Aware Image Inpainting for Mixed Scenes (ECCV 2020). _Liang Liao, Jing Xiao, Zheng Wang, Chia-wen Lin, Shin'ichi Satoh_ [[Paper]](https://arxiv.org/abs/2003.06877)
* High-Resolution Image Inpainting with Iterative Confidence Feedback and Guided Upsampling (ECCV 2020). _Yu Zeng, Zhe Lin, Jimei Yang, Jianming Zhang, Eli Shechtman, Huchuan Lu_ [[Paper]](https://arxiv.org/abs/2005.11742)[[Project]](https://zengxianyu.github.io/iic/)

## Video Inpainting

### Non-learning Inpainting

### Learning Inpainting
