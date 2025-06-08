# <center>Place Recognition Meet multiple Modalities: A Comprehensive Review, Current Challenges and Future Directions</center>
 
 <p align="center">
<font color="#FF5A1F">Zhenyu Li, Tianyi Shang, Pengjie Xu, Zhaojun Deng</font>
</p>
<p align="center">

<div align="center">
  
[Our Survey](https://arxiv.org/pdf/2505.14068)

</div>

 
## Abstract
Place recognition is a cornerstone of vehicle navigation and mapping, which is pivotal in enabling systems to determine whether a location has been previously visited. This capability is critical for tasks such as loop closure in Simultaneous Localization and Mapping (SLAM) and long-term navigation under varying environmental conditions. This survey comprehensively reviews recent advancements in place recognition, emphasizing three representative methodological paradigms: Convolutional Neural Network (CNN)-based approaches, Transformer-based frameworks, and cross-modal strategies. We begin by elucidating the significance of place recognition within the broader context of autonomous systems. Subsequently, we trace the evolution of CNN-based methods, highlighting their contributions to robust visual descriptor learning and scalability in large-scale environments. We then examine the emerging class of Transformer-based models, which leverage self-attention mechanisms to capture global dependencies and offer improved generalization across diverse scenes. Furthermore, we discuss cross-modal approaches that integrate heterogeneous data sources such as Lidar, vision, and text description, thereby enhancing resilience to viewpoint, illumination, and seasonal variations. We also summarize standard datasets and evaluation metrics widely adopted in the literature. Finally, we identify current research challenges and outline prospective directions, including domain adaptation, real-time performance, and lifelong learning, to inspire future advancements in this domain.

## Survey Overview
This paper provides a comprehensive review of recent advancements in place recognition, focusing on three key methodological paradigms:

1. **CNN-based Approaches**  
2. **Transformer-based Frameworks**  
3. **Cross-modal Strategies**  

<div align="center">

<img src="figure2.jpg" width="450">


</div>

## 1. Introduction
### Significance in Autonomous Systems
Place recognition plays a pivotal role in:
- Autonomous vehicle navigation
- Large-scale environment mapping
- Robust localization under changing conditions

## 2. Methodological Evolution

![alt text](figure3.jpg)

### 2.1 CNN-based Approaches
**Key Contributions:**
- Robust visual descriptor learning
- Scalability in large-scale environments
- Evolution from traditional features to deep learning

![alt text](image.png)

### 2.2 Transformer-based Models
**Advancements:**
- Self-attention mechanisms capturing global dependencies
- Improved generalization across diverse scenes
- Handling of long-range spatial relationships

![alt text](image-1.png)

### 2.3 Cross-modal Strategies
**Innovations:**
- Integration of heterogeneous data sources:
  - Lidar point clouds
  - Visual information
  - Text descriptions
- Enhanced resilience to:
  - Viewpoint variations
  - Illumination changes
  - Seasonal transitions

  ![alt text](image-2.png)

## 3. Challenges & Future Directions

### Current Research Challenges
- Domain adaptation across environments
- Real-time performance requirements
- Lifelong learning capabilities

### Prospective Research Directions
1. **Adaptive Systems**  
   - Cross-domain generalization
   - Continuous learning frameworks

2. **Efficiency Optimization**  
   - Computational efficiency improvements
   - Memory-constrained implementations

3. **Advanced Fusion Techniques**  
   - Multi-modal integration
   - Temporal consistency methods
     
## 4. All the methods are listed below:



| Title | First Author | Venue | Github | Bibtex |
|---|---|---|---|---|
| [Gsv-cities: Toward appropriate supervised visual place recognition](https://www.sciencedirect.com/science/article/pii/S0925231222012188) | Amar Ali-bey | Neurocomputing 2022 | [Github](https://github.com/amaralibey/gsv-cities)  | [BibTex](citations/ali2022gsv.txt) |
| [Mixvpr: Feature mixing for visual place recognition](https://openaccess.thecvf.com/content/WACV2023/papers/Ali-bey_MixVPR_Feature_Mixing_for_Visual_Place_Recognition_WACV_2023_paper.pdf) | Amar Ali-bey | WACV 2023 | [Github](https://github.com/amaralibey/MixVPR)  | [BibTex](citations/ali2023mixvpr.txt) |
| [BoQ: A place is worth a bag of learnable queries](https://openaccess.thecvf.com/content/CVPR2024/html/Ali-bey_BoQ_A_Place_is_Worth_a_Bag_of_Learnable_Queries_CVPR_2024_paper.html) | Amar Ali-bey | CVPR 2024 | [Github](https://github.com/amaralibey/Bag-of-Queries)  | [BibTex](citations/ali2024boq.txt) |
| [NetVLAD: CNN Architecture for Weakly Supervised Place Recognition](https://openaccess.thecvf.com/content_cvpr_2016/html/Arandjelovic_NetVLAD_CNN_Architecture_CVPR_2016_paper.html) | Relja Arandjelovic | CVPR 2016 | [Github](https://github.com/Relja/netvlad)  | [BibTex](citations/arandjelovic2016netvlad.txt) |
| [AttDLNet: Attention-based Deep Network for 3D LiDAR Place Recognition](https://link.springer.com/chapter/10.1007/978-3-031-21065-5_26) | Tiago Barros | Robot 2022 | [Github](https://github.com/Cybonic/AttDLNet) | [BibTex](citations/barros2022attdlnet.txt) |
| [Place recognition survey: An update on deep learning approaches](https://arxiv.org/abs/2106.10458) | Tiago Barros | arXiv |  | [BibTex](citations/barros2021place.txt) |
| [Rethinking visual geo-localization for large-scale applications](https://openaccess.thecvf.com/content/CVPR2022/papers/Berton_Rethinking_Visual_Geo-Localization_for_Large-Scale_Applications_CVPR_2022_paper.pdf) | Gabriele Berton | CVPR 2022 | [Github](https://github.com/gmberton/CosPlace) | [BibTex](citations/berton2022rethinking.txt) |
| [Eigenplaces: Training viewpoint robust models for visual place recognition](https://openaccess.thecvf.com/content/ICCV2023/papers/Berton_EigenPlaces_Training_Viewpoint_Robust_Models_for_Visual_Place_Recognition_ICCV_2023_paper.pdf) | Gabriele Berton | ICCV 2023 | [Github](https://github.com/gmberton/EigenPlaces) | [BibTex](citations/berton2023eigenplaces.txt) |
| [Unifying deep local and global features for image search](https://link.springer.com/chapter/10.1007/978-3-030-58565-5_43) | Bingyi Cao | ECCV 2020 | [Github](https://github.com/feymanpriv/DELG) | [BibTex](citations/cao2020unifying.txt) |
| [Emerging properties in self-supervised vision transformers](https://openaccess.thecvf.com/content/ICCV2021/papers/Caron_Emerging_Properties_in_Self-Supervised_Vision_Transformers_ICCV_2021_paper.pdf) | Mathilde Caron | ICCV 2021 |  | [BibTex](citations/caron2021emerging.txt) |
| [Lcdnet: Deep loop closure detection and point cloud registration for lidar slam](https://ieeexplore.ieee.org/abstract/document/9723505/) | Daniele Cattaneo | TRO 2022 | [Github](https://github.com/robot-learning-freiburg/LCDNet) | [BibTex](citations/cattaneo2022lcdnet.txt) |
| [SpoxelNet: Spherical voxel-based deep place recognition for 3D point clouds of crowded indoor spaces](https://ieeexplore.ieee.org/abstract/document/9341549) | Min Young Chang | IROS 2020 |  | [BibTex](citations/chang2020spoxelnet.txt) |
| [Convolutional neural network-based place recognition](https://arxiv.org/abs/1411.1509) | Zetao Chen | arXiv |  | [BibTex](citations/chen2014convolutional.txt) |
| [FAB-MAP: Probabilistic localization and mapping in the space of appearance](https://journals.sagepub.com/doi/abs/10.1177/0278364908090961) | Mark Cummins | IJRR 2008 | [Github](https://github.com/arrenglover/openfabmap) | [BibTex](citations/cummins2008fab.txt) |
| [A solution to the simultaneous localization and map building (SLAM) problem](https://ieeexplore.ieee.org/abstract/document/938381) | MWM Gamini Dissanayake | TRO 2001 |  | [BibTex](citations/dissanayake2001solution.txt) |
| [Dh3d: Deep hierarchical 3d descriptors for robust large-scale 6dof relocalization](https://link.springer.com/chapter/10.1007/978-3-030-58548-8_43) | Juan Du | ECCV 2020 | [Github](https://github.com/JuanDuGit/DH3D) | [BibTex](citations/du2020dh3d.txt) |
| [Direct sparse odometry](https://ieeexplore.ieee.org/abstract/document/7898369) | Jakob Engel | TPAMI 2017 | [Github](https://github.com/JakobEngel/dso) | [BibTex](engel2017direct.txt) |
| [Svt-net: Super light-weight sparse voxel transformer for large scale place recognition](https://ojs.aaai.org/index.php/AAAI/article/view/19934) | Zhaoxin Fan | AAAI 2022 | [Github](https://github.com/ZhenboSong/SVTNet) | [BibTex](citations/fan2022svt.txt) |
| [Adaptive mobile robot navigation and mapping](https://journals.sagepub.com/doi/abs/10.1177/02783649922066484) | HJS Feder | IJRR 1999 |  | [BibTex](citations/feder1999adaptive.txt) |
| [Toward object-based place recognition in dense rgb-d maps](https://people.csail.mit.edu/lpaull/publications/Finman_ICRAW_2015.pdf) | Dorian Gálvez-López | TRO 2012 |  | [BibTex](citations/finman2015toward.txt) |
| [Bags of binary words for fast place recognition in image sequences](https://ieeexplore.ieee.org/abstract/document/6202705/) | Dorian Gálvez-López | TRO 2012 |  | [BibTex](citations/galvez2012bags.txt) |
| [Revisit Anything: Visual Place Recognition via Image Segment Retrieval](https://link.springer.com/chapter/10.1007/978-3-031-73113-6_19) | Kartik Garg | ECCV 2024 | [Github](https://github.com/AnyLoc/Revisit-Anything) | [BibTex](citations/garg2024revisit.txt) |
| [Self-supervising ffne-grained region similarities for large-scale image localization](https://arxiv.org/pdf/2006.03926) | Yixiao Ge | ECCV 2020 | [Github](https://github.com/yxgeee/SFRS) | [BibTex](citations/ge2020self.txt) |
| [FAB-MAP+ RatSLAM: Appearance-based SLAM for multiple times of day](https://ieeexplore.ieee.org/abstract/document/5509547) | AJ Glover | ICRA 2010 |  | [BibTex](citations/glover2010fab.txt) |
| [The perfect match: 3d point cloud matching with smoothed densities](https://openaccess.thecvf.com/content_CVPR_2019/html/Gojcic_The_Perfect_Match_3D_Point_Cloud_Matching_With_Smoothed_Densities_CVPR_2019_paper.html) | Zan Gojcic | CVPR 2019 | [Github](https://github.com/zgojcic/3DSmoothNet) | [BibTex](citations/gojcic2019perfect.txt) |
| [Salsa: Swift adaptive lightweight self-attention for enhanced lidar place recognition](https://ieeexplore.ieee.org/abstract/document/10629049) | Raktim Gautam Goswami | RAL 2024 | [Github](https://github.com/raktimgg/SALSA) | [BibTex](citations/goswami2024salsa.txt) |
| [Indoor localization improved by spatial context—A survey](https://dl.acm.org/doi/abs/10.1145/3322241) | Fuqiang Gu | ACM Computing Surveys |  | [BibTex](citations/gu2019indoor.txt) |
| [Recent trends in task and motion planning for robotics: A survey](https://dl.acm.org/doi/abs/10.1145/3583136) | Huihui Guo | Computing Surveys |  | [BibTex](citations/guo2023recent.txt) |
| [Visual place recognition using HMM sequence matching](https://ieeexplore.ieee.org/abstract/document/6943207) | Peter Hansen | IROS 2014 |  | [BibTex](citations/hansen2014visual.txt) |
| [Patch-netvlad: Multi-scale fusion of locally-global descriptors for place recognition](https://openaccess.thecvf.com/content/CVPR2021/html/Hausler_Patch-NetVLAD_Multi-Scale_Fusion_of_Locally-Global_Descriptors_for_Place_Recognition_CVPR_2021_paper.html) | Stephen Hausler | CVPR 2021 | [Github](https://github.com/QVPR/Patch-NetVLAD) | [BibTex](citations/hausler2021patch.txt) |
| [Pair-vpr: Place-aware pre-training and contrastive pair classiffcation for visual place recognition with vision transformers](https://ieeexplore.ieee.org/abstract/document/10906598) | Stephen Hausler | RAL 2025 | [Github](https://github.com/QVPR/Patch-NetVLAD) | [BibTex](citations/hausler2025pair.txt) |
| [Hitpr: Hierarchical transformer for place recognition in point cloud](https://ieeexplore.ieee.org/abstract/document/9811737) | Zhixing Hou | ICRA 2022|  | [BibTex](citations/hou2022hitpr.txt) |
| [Progeo: Generating prompts through image-text contrastive learning for visual geo-localization](https://link.springer.com/chapter/10.1007/978-3-031-72338-4_30) | Jingqi Hu | ICANN 2024 | [Github](https://github.com/Chain-Mao/ProGEO) | [BibTex](citations/hu2024progeo.txt) |
| [360loc: A dataset and benchmark for omnidirectional visual localization with cross-device queries](https://openaccess.thecvf.com/content/CVPR2024/html/Huang_360Loc_A_Dataset_and_Benchmark_for_Omnidirectional_Visual_Localization_with_CVPR_2024_paper.html) | Huajian Huang | CVPR 2024 | [Github](https://huajianup.github.io/research/360Loc/) | [BibTex](citations/huang2024360loc.txt) |
| [Cross-modal and uni-modal soft-label alignment for image-text retrieval](https://ojs.aaai.org/index.php/AAAI/article/view/29789) | Hailang Huang | AAAI 2024 | [Github](https://github.com/lerogo/aaai24_itr_cusa) | [BibTex](citations/huang2024cross.txt) |
| [Optimal transport aggregation for visual place recognition](https://openaccess.thecvf.com/content/CVPR2024/html/Izquierdo_Optimal_Transport_Aggregation_for_Visual_Place_Recognition_CVPR_2024_paper.html) | Sergio Izquierdo | CVPR 2024 | [Github](https://github.com/serizba/salad) | [BibTex](citations/izquierdo2024optimal.txt) |
| [Learned contextual feature reweighting for image geo-localization](https://openaccess.thecvf.com/content_cvpr_2017/html/Kim_Learned_Contextual_Feature_CVPR_2017_paper.html) | Hyo Jin Kim | CVPR 2017 | [Github](https://github.com/hyojinie/crn) | [BibTex](citations/jin2017learned.txt) |
| [HeLiPR: Heterogeneous LiDAR dataset for inter-LiDAR place recognition under spatiotemporal variations](https://journals.sagepub.com/doi/abs/10.1177/02783649241242136) | Minwoo Jung | IJRR 2024 | [Github](https://sites.google.com/view/heliprdataset) | [BibTex](citations/jung2024helipr.txt) |
| [HeLiPR: Heterogeneous LiDAR dataset for inter-LiDAR place recognition under spatiotemporal variations](https://journals.sagepub.com/doi/abs/10.1177/02783649241242136) | Minwoo Jung | IJRR 2024 | [Github](https://sites.google.com/view/heliprdataset) | [BibTex](citations/jung2024helipr.txt) |
| [Anyloc: Towards universal visual place recognition](https://ieeexplore.ieee.org/abstract/document/10361537) | Nikhil Keetha | RAL 2023 | [Github](https://anyloc.github.io/) | [BibTex](citations/keetha2023anyloc.txt) |
| [A holistic visual place recognition approach using lightweight cnns for signiffcant viewpoint and appearance changes](https://ieeexplore.ieee.org/abstract/document/8944012) | Ahmad Khaliq | TRO 2019 |  | [BibTex](citations/khaliq2019holistic.txt) |
| [Level-5 autonomous driving—Are we there yet? A review of research literature](https://dl.acm.org/doi/abs/10.1145/3485767) | Manzoor Ahmed Khan | ACM Computing Surveys |  | [BibTex](citations/khan2022level.txt) |
| [Narrowing your fov with solid: Spatially organized and lightweight global descriptor for fov-constrained lidar place recognition](https://ieeexplore.ieee.org/abstract/document/10629042) | Hogyun Kim | RAL 2024 | [Github](https://github.com/kimsoohwan/SOLiD-A-LOAM) | [BibTex](citations/kim2024narrowing.txt) |
| [Text2pos: Text-to-point-cloud cross-modal localization](https://openaccess.thecvf.com/content/CVPR2022/html/Kolmet_Text2Pos_Text-to-Point-Cloud_Cross-Modal_Localization_CVPR_2022_paper.html) | Manuel Kolmet | CVPR 2022 | [Github](https://github.com/mako443/Text2Pos-CVPR2022) | [BibTex](citations/kolmet2022text2pos.txt) |
| [Minkloc3d: Point cloud based large-scale place recognition](https://openaccess.thecvf.com/content/WACV2021/html/Komorowski_MinkLoc3D_Point_Cloud_Based_Large-Scale_Place_Recognition_WACV_2021_paper.html) | Jacek Komorowski | WACV 2021 | [Github](https://github.com/jac99/MinkLoc3D) | [BibTex](citations/komorowski2021minkloc3d.txt) |
| [Improving point cloud based place recognition with ranking-based loss and large batch training](https://ieeexplore.ieee.org/abstract/document/9956458) | Jacek Komorowski | ICPR 2022 | [Github](https://github.com/jac99/MinkLoc3Dv2) | [BibTex](citations/komorowski2022improving.txt) |
| [Generalized contrastive optimization of siamese networks for place recognition](https://arxiv.org/abs/2103.06638) | María Leyva-Vallina | arXiv | [Github](https://github.com/marialeyvallina/generalized_contrastive_loss) | [BibTex](citations/leyva2021generalized.txt) |
| [Toward Robust Visual Place Recognition for Mobile Robots With an End-to-End Dark-Enhanced Net](https://ieeexplore.ieee.org/abstract/document/10726589/) | Zhenyu Li | TII 2025 | [Github](https://github.com/CV4RA/Dark-enhanced-VPR-Net) | [BibTex](citations/li2024toward.txt) |
| [CSPFormer: A cross-spatial pyramid transformer for visual place recognition](https://www.sciencedirect.com/science/article/abs/pii/S0925231224002431) | Zhenyu Li | Neurocomputing 2024 |  | [BibTex](citations/li2024cspformer.txt) |
| [Feature-Level Knowledge Distillation for Place Recognition Based on Soft-Hard Labels Teaching Paradigm](https://ieeexplore.ieee.org/abstract/document/10759546/) | Zhenyu Li | TIIS 2025 | [Github](https://github.com/CV4RA/ASHT-KD) | [BibTex](citations/li2024feature.txt) |
| [CWPFormer: Towards High-performance Visual Place Recognition for Robot with Cross-weight Attention Learning](https://ieeexplore.ieee.org/abstract/document/10872972) | Zhenyu Li | TAI 2025 | [Github](https://github.com/CV4RA/CWPFormer) | [BibTex](citations/li2025cwpformer.txt) |
| [Translo: A window-based masked point transformer framework for large-scale lidar odometry](https://ojs.aaai.org/index.php/AAAI/article/view/25256) | Jiuming Liu | AAAI 2023 | [Github](https://github.com/IRMVLab/TransLO) | [BibTex](citations/liu2023translo.txt) |
| [Stochastic attraction-repulsion embedding for large scale image localization](https://openaccess.thecvf.com/content_ICCV_2019/html/Liu_Stochastic_Attraction-Repulsion_Embedding_for_Large_Scale_Image_Localization_ICCV_2019_paper.html) | Liu Liu | ICCV 2019 | [Github](https://github.com/Liumouliu/deepIBL) | [BibTex](citations/liu2019stochastic.txt) |
| [Stochastic attraction-repulsion embedding for large scale image localization](https://openaccess.thecvf.com/content_ICCV_2019/html/Liu_Stochastic_Attraction-Repulsion_Embedding_for_Large_Scale_Image_Localization_ICCV_2019_paper.html) | Liu Liu | ICCV 2019 | [Github](https://github.com/Liumouliu/deepIBL) | [BibTex](citations/liu2019stochastic.txt) |
| [Visual place recognition: A survey](https://ieeexplore.ieee.org/abstract/document/7339473/) | Stephanie Lowry | TRO 2015 |  | [BibTex](citations/lowry2015visual.txt) |
| [Unsupervised online learning of condition-invariant images for place recognition](https://www.araa.asn.au/acra/acra2014/papers/pap113.pdf) | Stephanie Lowry | ACRA 2014 |  | [BibTex](citations/lowry2014unsupervised.txt) |
| [Deep homography estimation for visual place recognition](https://ojs.aaai.org/index.php/AAAI/article/view/28901) | Feng Lu | AAAI 2024 | [Github](https://github.com/Lu-Feng/DHE-VPR) | [BibTex](citations/lu2024deep.txt) 
| [SelaVPR++: Towards Seamless Adaptation of Foundation Models for Efffcient Place Recognition](https://arxiv.org/abs/2502.16601) | Feng Lu | arXiv | [Github](https://github.com/Lu-Feng/SelaVPR) | [BibTex](citations/lu2025selavpr++.txt) 
| [Cricavpr: Cross-image correlation-aware representation learning for visual place recognition](https://openaccess.thecvf.com/content/CVPR2024/html/Lu_CricaVPR_Cross-image_Correlation-aware_Representation_Learning_for_Visual_Place_Recognition_CVPR_2024_paper.html) | Feng Lu | CVPR 2024 | [Github](https://github.com/Lu-Feng/CricaVPR) | [BibTex](citations/lu2024cricavpr.txt) 
| [Towards seamless adaptation of pre-trained models for visual place recognition](https://arxiv.org/abs/2402.14505) | Feng Lu | arXiv | [Github](https://github.com/Lu-Feng/SelaVPR) | [BibTex](citations/lu2024towards.txt) 
| [3D point cloud-based place recognition: a survey](https://link.springer.com/article/10.1007/s10462-024-10713-6) | Kan Luo | Artiffcial Intelligence Review |  | [BibTex](citations/luo20243d.txt) 
| [BEVPlace: Learning LiDAR-based place recognition using bird’s eye view images](https://openaccess.thecvf.com/content/ICCV2023/html/Luo_BEVPlace_Learning_LiDAR-based_Place_Recognition_using_Birds_Eye_View_Images_ICCV_2023_paper.html) | Lun Luo |  ICCV 2023 | [Github](https://github.com/zjuluolun/BEVPlace) | [BibTex](citations/luo2023bevplace.txt) 
| [Seqot: A spatial–temporal transformer network for place recognition using sequential lidar data](https://ieeexplore.ieee.org/abstract/document/9994714/) | Junyi Ma |  TIE 2022 | [Github](https://github.com/BIT-MJY/SeqOT) | [BibTex](citations/ma2022seqot.txt) 
| [OverlapTransformer: An efffcient and yaw-angle-invariant transformer network for LiDAR-based place recognition](https://ieeexplore.ieee.org/abstract/document/9785497/) | Junyi Ma | RAL 2022 | [Github](https://github.com/haomo-ai/OverlapTransformer) | [BibTex](citations/ma2022overlaptransformer.txt) 
| [1 year, 1000 km: The oxford robotcar dataset](https://journals.sagepub.com/doi/abs/10.1177/0278364916679498) | Will Maddern | IJRR 2017 | [Dataset](http://robotcar-dataset.robots.ox.ac.uk) | [BibTex](citations/maddern20171.txt) 
| [SeqSLAM: Visual route-based navigation for sunny summer days and stormy winter nights](https://ieeexplore.ieee.org/abstract/document/6224623/) | Michael J Milford | ICRA 2012 | [Github](https://github.com/tmadl/pySeqSLAM) | [BibTex](citations/milford2012seqslam.txt) 
| [Environment selection and hierarchical place recognition](https://ieeexplore.ieee.org/abstract/document/7139966/) | Mahesh Mohan | ICRA 2015 |  | [BibTex](citations/mohan2015environment.txt) 
| [FastSLAM: A factored solution to the simultaneous localization and mapping problem](https://cdn.aaai.org/AAAI/2002/AAAI02-089.pdf) | Michael Montemerlo | AAAI  2002 | [Github](https://github.com/bushuhui/fastslam) | [BibTex](citations/montemerlo2002fastslam.txt) 
| [ORB-SLAM: A versatile and accurate monocular SLAM system](https://ieeexplore.ieee.org/abstract/document/7219438/) | Raul Mur-Artal | TRO 2002 |  | [BibTex](citations/mur2015orb.txt) 
| [A comprehensive review on autonomous navigation](https://dl.acm.org/doi/abs/10.1145/3727642) | Saeid Nahavandi | Computing Surveys |  | [BibTex](citations/nahavandi2022comprehensive.txt) 
| [The mapillary vistas dataset for semantic understanding of street scenes](https://openaccess.thecvf.com/content_iccv_2017/html/Neuhold_The_Mapillary_Vistas_ICCV_2017_paper.html) | Gerhard Neuhold | ICCV 2017 | [Dataset](www.mapillary.com) | [BibTex](citations/neuhold2017mapillary.txt) 
| [Single-view place recognition under seasonal changes](https://arxiv.org/pdf/1808.06516) | Daniel Olid | Arxiv | [Github](http://webdiis.unizar.es/~jmfacil/pr-nordland/) | [BibTex](citations/olid2018single.txt) 
| [Dinov2: Learning robust visual features without supervision](https://arxiv.org/pdf/2304.07193) | Maxime Oquab | Arxiv | [Github](https://github.com/facebookresearch/dinov2) | [BibTex](citations/oquab2023dinov2.txt) 
| [Visual place recognition using landmark distribution descriptors](https://openaccess.thecvf.com/content_cvpr_2017/html/Qi_PointNet_Deep_Learning_CVPR_2017_paper.html) | Pilailuck Panphattarasap | ACCV 2016 | | [BibTex](citations/panphattarasap2017visual.txt) 
| [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://openaccess.thecvf.com/content_cvpr_2017/html/Qi_PointNet_Deep_Learning_CVPR_2017_paper.html) | Charles R Qi | CVPR 2017 | [Github](https://github.com/charlesq34/pointnet) | [BibTex](citations/qi2017pointnet.txt)
| [Pointnet++: Deep hierarchical feature learning on point sets in a metric space](https://proceedings.neurips.cc/paper/2017/hash/d8bf84be3800d12f74d8b05e9b89836f-Abstract.html) | Charles Ruizhongtai Qi | neurips 2017 | [Github](https://github.com/erikwijmans/Pointnet2_PyTorch) | [BibTex](citations/qi2017pointnet++.txt)
| [Fine-tuning CNN image retrieval with no human annotation](https://ieeexplore.ieee.org/abstract/document/8382272/) | Filip Radenović | TPAMI 2018 | [Github](http://cmp.felk.cvut.cz/cnnimageretrieval) | [BibTex](citations/radenovic2018fine.txt)
| [Learning transferable visual models from natural language supervision](http://proceedings.mlr.press/v139/radford21a) | Alec Radford | ICML 2021 | [Github](https://github.com/openai/CLIP) | [BibTex](citations/radford2021learning.txt)
| [Vlocnet++: Deep multitask learning for semantic visual localization and odometry](https://ieeexplore.ieee.org/abstract/document/8458420/) | Noha Radwan | RAL 2018 |  | [BibTex](citations/radwan2018vlocnet++.txt)
| [Learning with average precision: Training image retrieval with a listwise loss](http://openaccess.thecvf.com/content_ICCV_2019/html/Revaud_Learning_With_Average_Precision_Training_Image_Retrieval_With_a_Listwise_ICCV_2019_paper.html) | Jerome Revaud | ICCV 2019 | [Github](https://europe.naverlabs.com/Deep-Image-Retrieval/) | [BibTex](citations/revaud2019learning.txt)
| [Superglue: Learning feature matching with graph neural networks](https://openaccess.thecvf.com/content_CVPR_2020/html/Sarlin_SuperGlue_Learning_Feature_Matching_With_Graph_Neural_Networks_CVPR_2020_paper.html) | Paul-Edouard Sarlin | CVPR 2020 | [Github](github.com/magicleap/SuperGluePretrainedNetwork) | [BibTex](citations/sarlin2020superglue.txt)
| [MambaPlace: Text-to-Point-Cloud Cross-Modal Place Recognition with Attention Mamba Mechanisms](https://arxiv.org/abs/2408.15740) | Tianyi Shang | arXiv | [Github](https://github.com/nuozimiaowu/MambaPlace) | [BibTex](citations/shang2024mambaplace.txt)
| [Text-Driven 3D Lidar Place Recognition for Autonomous Driving](https://arxiv.org/abs/2503.18035) | Tianyi Shang | arXiv | [Github](https://github.com/nuozimiaowu/Des4Pos) | [BibTex](citations/shang2025text.txt)
| [Bridging Text and Vision: A Multi-View Text-Vision Registration Approach for Cross-Modal Place Recognition](https://arxiv.org/abs/2502.14195) | Tianyi Shang | arXiv | [Github](https://github.com/nuozimiaowu/Text4VPR) | [BibTex](citations/shang2025bridging.txt)
| [Voxel-based representation learning for place recognition based on 3d point clouds](https://ieeexplore.ieee.org/abstract/document/9340992) | Sriram Siva | IROS 2020 |  | [BibTex](citations/siva2020voxel.txt)
| [A dataset for benchmarking image-based localization](https://openaccess.thecvf.com/content_cvpr_2017/papers/Sun_A_Dataset_for_CVPR_2017_paper.pdf) | Xun Sun | CVPR 2017 |  | [BibTex](citations/sun2017dataset.txt)
| [On the performance of convnet features for place recognition](https://ieeexplore.ieee.org/abstract/document/7353986/) | Niko Sünderhauf | IROS 2015 |  | [BibTex](citations/sunderhauf2015performance.txt)
| [OpenSeqSLAM2. 0: An open source toolbox for visual place recognition under changing conditions](https://ieeexplore.ieee.org/abstract/document/8593761) | Ben Talbot | IROS 2018 | [Github](https://github.com/kadn/OpenSeqSLAM2.0) | [BibTex](citations/talbot2018openseqslam2.txt)
| [OpenSeqSLAM2. 0: An open source toolbox for visual place recognition under changing conditions](https://ieeexplore.ieee.org/abstract/document/8593761) | Ben Talbot | IROS 2018 | [Github](https://github.com/kadn/OpenSeqSLAM2.0) | [BibTex](citations/talbot2018openseqslam2.txt)
| [The graph SLAM algorithm with applications to large-scale mapping of urban structures](https://journals.sagepub.com/doi/abs/10.1177/0278364906065387) | Sebastian Thrun | IJRR 2006 |  | [BibTex](citations/thrun2006graph.txt)
| [24/7 place recognition by view synthesis](https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Torii_247_Place_Recognition_2015_CVPR_paper.html) | Akihiko Torii | CVPR 2015 |  | [BibTex](citations/torii201524.txt)
| [Visual place recognition with repetitive structures](https://www.cv-foundation.org/openaccess/content_cvpr_2013/html/Torii_Visual_Place_Recognition_2013_CVPR_paper.html) | Akihiko Torii | CVPR 2013 |  | [BibTex](citations/torii2013visual.txt)
| [Effovpr: Effective foundation model utilization for visual place recognition](https://arxiv.org/abs/2405.18065) | Issar Tzachor | ICLR 2025 |  | [BibTex](citations/tzachor2024effovpr.txt)
| [Pointnetvlad: Deep point cloud based retrieval for large-scale place recognition](https://openaccess.thecvf.com/content_cvpr_2018/html/Uy_PointNetVLAD_Deep_Point_CVPR_2018_paper.html) | Mikaela Angelina Uy | CVPR 2018 | [Github](https://github.com/mikacuy/pointnetvlad) | [BibTex](citations/uy2018pointnetvlad.txt)
| [LoGG3D-Net: Locally guided global descriptor learning for 3D place recognition](https://ieeexplore.ieee.org/abstract/document/9811753/) | Kavisha Vidanapathirana | ICRA 2022 | [Github](https://github.com/csiro-robotics/LoGG3D-Net) | [BibTex](citations/vidanapathirana2022logg3d.txt)
| [Text to point cloud localization with relation-enhanced transformer](https://ojs.aaai.org/index.php/AAAI/article/view/25347) | Guangzhi Wang | AAAI 2023 |  | [BibTex](citations/wang2023text.txt)
| [Transvpr: Transformer-based place recognition with multi-level attention aggregation](https://openaccess.thecvf.com/content/CVPR2022/html/Wang_TransVPR_Transformer-Based_Place_Recognition_With_Multi-Level_Attention_Aggregation_CVPR_2022_paper.html) | Ruotong Wang | CVPR 2022 | [Github](https://github.com/RuotongWANG/TransVPR-model-implementation) | [BibTex](citations/wang2022transvpr.txt)
| [Deepvo: Towards end-to-end visual odometry with deep recurrent convolutional neural networks](https://ieeexplore.ieee.org/abstract/document/7989236) | Sen Wang | ICRA 2017 | [Github](https://github.com/ChiWeiHsiao/DeepVO-pytorch) | [BibTex](citations/wang2017deepvo.txt)
| [Ranking-aware Continual Learning for LiDAR Place Recognition](https://arxiv.org/abs/2505.07198) | Xufei Wang | arXiv |  | [BibTex](citations/wang2025ranking.txt)
| [Text2loc: 3d point cloud localization from natural language](https://openaccess.thecvf.com/content/CVPR2024/papers/Xia_Text2Loc_3D_Point_Cloud_Localization_from_Natural_Language_CVPR_2024_paper.pdf) | Yan Xia | CVPR 2024 | [Github](https://yan-xia.github.io/projects/text2loc/) | [BibTex](citations/xia2024text2loc.txt)
| [TransLoc3D: Point cloud based large-scale place recognition using adaptive receptive ffelds](https://arxiv.org/abs/2105.11605) | Tian-Xing Xu | arXiv | [Github](https://github.com/slothfulxtx/TransLoc3D) | [BibTex](citations/xu2021transloc3d.txt)
| [TransVLAD: Multi-scale attention-based global descriptors for visual geo-localization](https://openaccess.thecvf.com/content/WACV2023/html/Xu_TransVLAD_Multi-Scale_Attention-Based_Global_Descriptors_for_Visual_Geo-Localization_WACV_2023_paper.html) | Yifan Xu | ECCV 2023 | [Github](https://github.com/Li-hq1/TransVLAD) | [BibTex](citations/xu2023transvlad.txt)
| [Hierarchical attention fusion for geo-localization](https://ieeexplore.ieee.org/abstract/document/9414517) | Liqi Yan | ICASSP 2021 | [Github](https://github.com/ylqi/HAF) | [BibTex](citations/yan2021hierarchical.txt)
| [Autonomous visual navigation for mobile robots: A systematic literature review](https://dl.acm.org/doi/abs/10.1145/3368961) | Yuri DV Yasuda | Computing Surveys |  | [BibTex](citations/yasuda2020autonomous.txt)
| [Mrs-vpr: a multi-resolution sampling based global visual place recognition method](https://ieeexplore.ieee.org/abstract/document/8793853/) | Peng Yin | ICRA 2019 |  | [BibTex](citations/yin2019mrs.txt)
| [Spatial pyramid-enhanced NetVLAD with weighted triplet loss for place recognition](https://ieeexplore.ieee.org/abstract/document/8700608) | Jun Yu | TNNLS 2019 |  | [BibTex](citations/yu2019spatial.txt)
| [3dmatch: Learning local geometric descriptors from rgb-d reconstructions](https://openaccess.thecvf.com/content_cvpr_2017/html/Zeng_3DMatch_Learning_Local_CVPR_2017_paper.html) | Andy Zeng | CVPR 2017 | [Github](http://3dmatch.cs.princeton.edu) | [BibTex](citations/zeng20173dmatch.txt)
| [PCAN: 3D attention map learning using contextual information for point cloud based retrieval](https://openaccess.thecvf.com/content_CVPR_2019/html/Zhang_PCAN_3D_Attention_Map_Learning_Using_Contextual_Information_for_Point_CVPR_2019_paper.html) | Wenxiao Zhang | CVPR 2019 | [Github](https://github.com/XLechter/PCAN) | [BibTex](citations/zhang2019pcan.txt)
| [Lidar-based place recognition for autonomous driving: A survey](https://dl.acm.org/doi/abs/10.1145/3707446) | Yongjun Zhang | Computing Surveys  |  | [BibTex](citations/zhang2024lidar.txt)
| [Learning deep features for scene recognition using places database](https://proceedings.neurips.cc/paper/2014/hash/3fe94a002317b5f9259f82690aeea4cd-Abstract.html) | Bolei Zhou | NeurIPS 2014  |  | [BibTex](citations/zhou2014learning.txt)
| [Loop closure detection using local 3D deep descriptors](https://ieeexplore.ieee.org/abstract/document/9729598/) | Youjie Zhou | RAL 2022  | [Github](github.com/yiming107/l3d_loop_closure) | [BibTex](citations/zhou2022loop.txt)
| [Ndt-transformer: Large-scale 3d point cloud localisation using the normal distribution transform representation](https://ieeexplore.ieee.org/abstract/document/9560932) | Zhicheng Zhou | ICRA 2021  | [Github](https://github.com/dachengxiaocheng/NDT-Transformer) | [BibTex](citations/zhou2021ndt.txt)
| [R2former: Uniffed retrieval and reranking transformer for place recognition](openaccess.thecvf.com/content/CVPR2023/html/Zhu_R2Former_Unified_Retrieval_and_Reranking_Transformer_for_Place_Recognition_CVPR_2023_paper.html) | Sijie Zhu | CVPR 2023  | [Github](https://github.com/Jeff-Zilence/R2Former) | [BibTex](citations/zhu2023r2former.txt)
| [PRGS: Patch-to-Region Graph Search for Visual Place Recognition](https://www.sciencedirect.com/science/article/pii/S0031320325003334) | Weiliang Zuo | Pattern Recognition 2025  | [Github](https://github.com/LKELN/PRGS) | [BibTex](citations/zuo2025prgs.txt)



@article{li2025place,
  title={Place Recognition: A Comprehensive Review, Current Challenges and Future Directions},
  author={Li, Zhenyu and Shang, Tianyi and Xu, Pengjie and Deng, Zhaojun},
  journal={arXiv preprint arXiv:2505.14068},
  year={2025},
  doi={10.48550/arXiv.2505.14068}
}
