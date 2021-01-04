# Activity-Recognition and Video-Understanding

This repository contains a compilation of code implementations for numerous works in Activity Recognition.
### Below is a general purpose template for Activity Recognition:

![alt_text](https://github.com/ashwinvaswani/Activity-Recognition/blob/main/assets/action_new_template.png)

### Visual Attributions:
1. Video attributions [Code](https://github.com/shinkyo0513/Video-Visual-Explanations)

### General code bases:
1. SlowFast by Facebook Research [Link](https://github.com/facebookresearch/SlowFast)
<!---
   Contains implementations for:
    * SlowFast Networks for Video Recognition  
    * Non-local Neural Networks 
    * A Multigrid Method for Efficiently Training Video Models 
    * X3D: Progressive Network Expansion for Efficient Video Recognition 
-->
2. MMAction [Link](https://github.com/open-mmlab/mmaction)
3. MMAction2 [Link](https://github.com/open-mmlab/mmaction2)
4. Facebook Video Modelling Zoo [Link](https://github.com/facebookresearch/VMZ)
5. PyVideoResearch [Link](https://github.com/gsig/PyVideoResearch)
6. GluonCV [Link](https://cv.gluon.ai/model_zoo/action_recognition.html)
7. M-PACT [Link](https://github.com/MichiganCOG/M-PACT)
8. PyTorch Video Recognition [Link](https://github.com/jfzhang95/pytorch-video-recognition)

### Multi-stream Methods:
1. Convolutional Two-Stream Network Fusion for Video Action Recognition [Code](https://github.com/feichtenhofer/twostreamfusion) | [Paper](https://arxiv.org/abs/1604.06573)
2. Temporal Segment Networks: Towards Good Practices for Deep Action Recognition [Code](https://github.com/yjxiong/temporal-segment-networks) | [Paper](https://arxiv.org/abs/1608.00859)
3. ActionVLAD: Learning spatio-temporal aggregation for action classification [Code](https://github.com/rohitgirdhar/ActionVLAD) | [Paper](https://arxiv.org/abs/1704.02895)
4. Hidden Two-Stream Convolutional Networks for Action Recognition [Code](https://github.com/bryanyzhu/Hidden-Two-Stream) | [Paper](https://arxiv.org/abs/1704.00389)
5. Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset [Code](https://github.com/deepmind/kinetics-i3d) | [Code](https://github.com/hassony2/kinetics_i3d_pytorch) | [Code](https://github.com/piergiaj/pytorch-i3d) |  [Paper](https://arxiv.org/abs/1705.07750)

### Single-Stream Methods:
**LSTM Methods:** 
1. Long-term Recurrent Convolutional Networks for Visual Recognition and Description [Code](https://github.com/LisaAnne/lisa-caffe-public/tree/lstm_video_deploy) | [Paper](https://arxiv.org/abs/1411.4389)
2. What Would You Expect? Anticipating Egocentric Actions With Rolling-Unrolling LSTMs and Modality Attention [Code](https://github.com/fpv-iplab/rulstm) | [Paper](https://arxiv.org/abs/1905.09035)
3. TS-LSTM and Temporal-Inception: Exploiting Spatiotemporal Dynamics for Activity Recognition [Code](https://github.com/chihyaoma/Activity-Recognition-with-CNN-and-RNN) | [Paper](https://arxiv.org/abs/1703.10667)

**CNN Methods:**  
1. Temporal 3D ConvNets: New Architecture and Transfer Learning for Video Classification
 [Code](https://github.com/MohsenFayyaz89/T3D) | [Paper](https://arxiv.org/abs/1711.08200)
2. TSM: Temporal Shift Module for Efficient Video Understanding [Code](https://github.com/mit-han-lab/temporal-shift-module) | [Paper](https://arxiv.org/abs/1811.08383?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%253A+arxiv%252FQSXk+%2528ExcitingAds%2521+cs+updates+on+arXiv.org%2529)
3. Temporal Relational Reasoning in Videos [Code](https://github.com/zhoubolei/TRN-pytorch) | [Paper](https://arxiv.org/abs/1711.08496)
4. Non-Local Neural Networks [Code](https://github.com/facebookresearch/video-nonlocal-net) | [Paper](https://arxiv.org/abs/1711.07971)
5. Video Classification with Channel-Separated Convolutional Networks [Unofficial Code](https://github.com/mnmjh1215/CSN-PyTorch) | [Paper](https://arxiv.org/abs/1904.02811)
6. Gate-Shift Networks for Video Action Recognition [Code](https://github.com/swathikirans/GSM) | [Paper](https://arxiv.org/abs/1912.00381)
7. V4D: 4D Convolutional Neural Networks for Video-level Representation Learning [Code](https://github.com/MalongTech/research-v4d) | [Paper](https://arxiv.org/abs/2002.07442)
8. Temporal Interlacing Network [Code](https://github.com/deepcs233/TIN) | [Paper](https://arxiv.org/abs/2001.06499)

**Attention-based Methods:**
1. Action Recognition using Visual Attention [Code](https://github.com/jingweio/Action_Recognition_using_Visual_Attention) | [Code](https://github.com/kracwarlock/action-recognition-visual-attention) | [Paper]()
2. Attention Clusters: Purely Attention Based
Local Feature Integration for Video Classification [Unofficial Code](https://github.com/pomonam/AttentionCluster) | [Paper]()
3. Video Modeling with Correlation Networks [Code](https://github.com/tefantasy/CorrNet) | [Paper]()
4. Attentional Pooling for Action Recognition [Code](https://github.com/rohitgirdhar/AttentionalPoolingAction) | [Paper](https://papers.nips.cc/paper/2017/file/67c6a1e7ce56d3d6fa748ab6d9af3fd7-Paper.pdf)

### Miscellenous:
1. Temporal Convolutional Networks: A Unified Approach to Action Segmentation and Detection [Code](https://github.com/colincsl/TemporalConvolutionalNetworks) | [Paper](https://arxiv.org/abs/1608.08242#:~:text=Temporal%20Convolutional%20Networks%3A%20A%20Unified%20Approach%20to%20Action%20Segmentation,-Colin%20Lea%2C%20Rene&text=Our%20model%20achieves%20superior%20or,takes%20to%20train%20an%20RNN.)
2. Long-term Temporal Convolutions [Code](https://github.com/gulvarol/ltc) | [Paper](https://arxiv.org/abs/1604.04494#:~:text=Typical%20human%20actions%20last%20several,exhibit%20characteristic%20spatio%2Dtemporal%20structure.&text=We%20demonstrate%20that%20LTC%2DCNN,the%20accuracy%20of%20action%20recognition.)
3. Dynamic Image Networks for Action Recognition [Code](https://github.com/hbilen/dynamic-image-nets) | [Paper](https://ieeexplore.ieee.org/document/7780700)
4. Learning Spatio-Temporal Representation with Pseudo-3D Residual Networks [Code](https://github.com/ZhaofanQiu/pseudo-3d-residual-networks) | [Paper](https://arxiv.org/abs/1711.10305)
5. Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet? [Code](https://github.com/kenshohara/3D-ResNets-PyTorch) | [Paper](https://arxiv.org/abs/1711.09577)
6. Long-Term Feature Banks for Detailed Video Understanding [Code](https://github.com/facebookresearch/video-long-term-feature-banks/) | [Paper](https://arxiv.org/abs/1812.05038)
7. Learning Correspondence from the Cycle-consistency of Time [Code](https://github.com/xiaolonw/TimeCycle) | [Paper](https://arxiv.org/abs/1903.07593)
8. Why Can't I Dance in the Mall? Learning to Mitigate Scene Bias in Action Recognition [Code](https://github.com/vt-vl-lab/SDN) | [Paper](https://arxiv.org/abs/1912.05534)
9. Learning Actor Relation Graphs for Group Activity Recognition [Code](https://github.com/wjchaoGit/Group-Activity-Recognition) | [Paper](https://arxiv.org/abs/1904.10117)
10. Asynchronous Temporal Fields for Action Recognition [Code](https://github.com/gsig/charades-algorithms) | [Paper](https://arxiv.org/abs/1612.06371)
11. TEA: Temporal Excitation and Aggregation for Action Recognition [Code](https://github.com/Phoenix1327/tea-action-recognition) | [Paper](https://arxiv.org/abs/2004.01398)
12. MotionSqueeze: Neural Motion Feature Learning for Video Understanding [Code](https://github.com/arunos728/MotionSqueeze) | [Paper](https://arxiv.org/abs/2007.09933)
13. ECO: Efficient Convolutional Network for Online Video Understanding [Code](https://github.com/mzolfaghari/ECO-efficient-video-understanding) | [Paper](https://arxiv.org/abs/1804.09066)
14. End-to-End Learning of Motion Representation for Video Understanding [Code](https://github.com/LijieFan/tvnet) | [Paper](https://arxiv.org/abs/1804.00413)
15. AR-Net: Adaptive Frame Resolution for Efficient Action Recognition [Code](https://github.com/mengyuest/AR-Net) | [Paper](https://arxiv.org/abs/2007.15796)
16. Learn to cycle: Time-consistent feature discovery for action recognition [Code](https://github.com/alexandrosstergiou/Squeeze-and-Recursion-Temporal-Gates) | [Paper](https://arxiv.org/abs/2006.08247)
17. VideoGraph: Recognizing Minutes-Long Human Activities in Videos [Code](https://github.com/noureldien/videograph) | [Paper](https://arxiv.org/abs/1905.05143)
18. Timeception for Complex Action Recognition [Code](https://github.com/noureldien/timeception) | [Paper](https://arxiv.org/abs/1812.01289)
19. An Evaluation of Action Recognition Models on EPIC-Kitchens [Code](https://github.com/epic-kitchens/epic-kitchens-55-action-models) | [Paper](https://arxiv.org/abs/1908.00867)
20. STEP: Spatio-Temporal Progressive Learning for Video Action Detection [Code](https://github.com/NVlabs/STEP) | [Paper](https://arxiv.org/abs/1904.09288)
21. Appearance-and-Relation Networks for Video Classification [Code](https://github.com/wanglimin/ARTNet) | [Paper](https://arxiv.org/abs/1711.09125)
22. End-to-end Video-level Representation Learning for Action Recognition [Code](https://github.com/zhujiagang/DTPP) | [Paper](https://arxiv.org/abs/1711.04161)
23. Action Recognition with Trajectory-Pooled Deep-Convolutional Descriptors [Code](https://github.com/wanglimin/TDD) | [Paper](https://arxiv.org/abs/1505.04868)
24. Real-time Action Recognition with Enhanced Motion Vector CNNs [Code](https://github.com/zbwglory/MV-release) | [Paper](https://arxiv.org/abs/1604.07669)
