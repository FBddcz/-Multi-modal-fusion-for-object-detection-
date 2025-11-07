# Multi-modal  fusion for  object detection

Provide a summary of Multi-modal  fusion for  object detection <br> 
(**Paper, Code, Dataset，Evaluation criteria and  more**). 

--------------------------------------------------------------------------------------
## Content:

1. <a href="# Multi-modal  fusion for  object detection Dataset"> Multi-modal  fusion for  object detection Dataset </a>
2. <a href="#Multi-modal  fusion for  object detection（RGB-T)"> Multi-modal  fusion for  object detection（RGB-T) </a>
3. <a href="#Multi-modal  fusion for  object detection(RGB-D)"> Multi-modal  fusion for  object detection（RGB-D)</a>
4. <a href="#Multi-modal  fusion for  object detection(RGB-Lidar)"> Multi-modal  fusion for  object detection（RGB-Lidar)</a>
5. <a href="#Multi-modal  fusion for  object detection(others)"> Multi-modal  fusion for  object detection（others)</a>
5. <a href="#Multi-modal  fusion for  object detection( survey)"> Multi-modal  fusion for  object detection（survey)</a>
--------------------------------------------------------------------------------------
# Multi-modal  fusion for  object detectiont Dataset <a id="Dataset" class="anchor" href="Dataset" aria-hidden="true"><span class="octicon octicon-link"></span></a> 
--------------------------------------------------------------------------------------
## RGB-T:
**RGBTDronePerson**  <br>
The first dataset is newly collected by drone-based RGBT cameras from various scenarios, named ''RGBTDronePerson'', which contains 6,125 pairs of RGBT images and 70,880 instances. <br>
You can find in [Paper](https://nnnnerd.github.io/RGBTDronePerson/)   <br>
**Teledyne FLIR ADAS**  <br>
This dataset3 contains 26,442 fully annotated frames with 520,000 bounding box annotations for 15 categories of objects including persons, different types of vehicles, traffic lights, etc. as shown in Table 2. Of these images, 9711 thermal and 9233 RGB frames are provided for training/validation purposes. <br>
You can find in [Paper](https://www.flir.com/oem/adas/adas-dataset-form/)   <br>
**DroneVehicle（2020）**  <br>
DroneVehicle dataset consists of a total of 56878 image sets, half of which are RGB images and the rest are Thermal images.  <br>
You can find in [Paper](https://arxiv.xilesou.top/pdf/2003.02437.pdf)   <br>
**UAV RGB-T 2400**  <br>
UAV-based dataset (UVA RGB-T 2400) with unregistered visible light and thermal infrared image pairs.  <br>
You can find in [Paper](https://ieeexplore.ieee.org/document/10315195)   <br>

**VT821（2018）**  <br>
VT821 includes 821 RGB-T image pairs and their ground truth annotations for the saliency detection purpose.  <br>
You can find in [Paper](https://github.com/mmic-lcl/Datasets-and-benchmark-code)  <br>
**VT1000（2019）**  <br>
VT1000 contains 1000 pairs of RGB-T images including more than 400 kinds of common objects collected in 10 types of scenes under different illumination conditions. <br>
You can find in [Paper](https://github.com/mmic-lcl/Datasets-and-benchmark-code)   <br>
**VT5000（2020）**  <br>
ncludes 5000 spatially aligned RGBT image pairs with ground truth annotations. VT5000 has 11 challenges collected in different scenes and environments for exploring the robustness of algorithms.<br>
You can find in [Paper](https://paperswithcode.com/dataset/vt5000)   <br>
**RoadScene（2020)**  <br>
it contains a total of 221 sets of aligned RGB-T image pairs. The main scenarios in the dataset are roads, including vehicles, pedestrians, traffic signs, and other objects. <br>
You can find in [Paper](https://github.com/hanna-xu/RoadScene)   <br>
**KAIST（2015）**  <br>
It includes a total of 95,328 images, each of which contains both RGB color images and infrared images. A total of 103128 dense annotations are included. The dataset captures a variety of regular traffic scenarios, including campuses, streets, and the countryside, during the day and at night. <br>
You can find in [Paper](http://openaccess.thecvf.com/content_cvpr_2015/html/Hwang_Multispectral_Pedestrian_Detection_2015_CVPR_paper.html)   <br>
**VI-RGBT3500**  <br>
The VI-RGBT3500 dataset contains 630 pairs of variable illumination images from the VT821, VT1000, and VT5000, 1190 pairs of images from the VDT2048, and all images from the VI-RGBT1500 dataset. <br>
You can find in [Paper](https://github.com/VDT-2048/SIA)   <br>


## RGB-D:
**NJUD（2014）**  <br>
NJUD is a large RGB-D dataset containing 1,985 image pairs. The stereo images were collected from the Internet and 3D movies, while photographs were taken by a Fuji W3 camera. 
<br>You can find in [Paper](https://paperswithcode.com/dataset/nju2k)   <br>
**NLPR**  <br>
 NLPR contains 1000 pairs of RGB and depth images, covering rich indoor and outdoor scenes.<br>
You can find in [Paper](https://pan.baidu.com/s/1pocKI_KEvqWgsB16pzO6Yw)  <br>
**SIP（2020)**  <br>
The Salient Person dataset (SIP) contains 929 salient person samples with different poses and illumination conditions.<br>
**SSD**  <br>
It includes 80 samples covering indoor and outdoor scenes.<br>
You can find in [Paper](https://pan.baidu.com/s/1zNL9-KSQwGILdAAfStMXWQ).<br>
**ReDWeb-S**  <br>
 ReDWeb-S is a large-scale challenging dataset for Salient Object Detection. It has totally 3179 images with various real-world scenes and high-quality depth maps. The dataset is split into a training set with 2179 RGB-D image pairs and a testing set with the remaining 1000 image pairs. <br>
You can find in [Paper](https://paperswithcode.com/dataset/redweb-s)   <br>
**COME15K**  <br>
COME15K is an RGB-D saliency detection dataset which contains 15,625 image pairs with high quality polygon-/scribble-/object-/instance-/rank-level annotations.<br>
You can find in [Paper](https://paperswithcode.com/dataset/come15k)   <br>
**RGBD135**  <br>
It Contains 135 images captured by Microsoft Kinect.<br>
You can find in [Paper](https://aistudio.baidu.com/datasetdetail/155597)   <br>
**LFSD**  <br>
The Light Field Saliency Database (LFSD) contains 100 light fields with 360×360 spatial resolution. A rough focal stack and an all-focus image are provided for each light field. The images in this dataset usually have one salient foreground object and a background with good color contrast.<br>
You can find in [Paper](https://paperswithcode.com/dataset/lfsd)   <br>
**SUN-RGBD**
It contains 10335 real RGB-D images of room scenes. Each RGB image has a corresponding depth and segmentation map. As many as 700 object categories are labeled. The training and testing sets contain 5285 and 5050 images, respectively. <br>
You can find in [Paper](https://paperswithcode.com/dataset/sun-rgb-d)   <br>
**Scale Multi-view RGBD**  <br>
It consists of 47210 RGBD images from 37 object categories, annotated with 15 visual affordance types. <br>
You can find in [Paper](https://ieeexplore.ieee.org/document/10222906)   <br>
**RGBD NYU-rank**  <br>
The proposed RGBD NYU-rank dataset contains RGB images, depth images and truth images for salient object ranking. We randomly divide this dataset into a training set of 1160 images and a test set of 289 images.<br>
You can find in [Paper](https://www.sciencedirect.com/science/article/pii/S0031320322007300#sec0023)   <br>


## RGB-Lidar:
**KITTI**  <br>
The entire dataset of KITTI was collected in Karlsruhe, Germany, and can be divided into five categories according to the scene: "road", "city", "residential area", "campus" and "pedestrian". <br>
You can find in [Paper](http://www.cs.toronto.edu/~urtasun/publications/geiger_et_al_ijrr13.pdf)   <br>
**nuScenes**  <br>
It collected 1000 driving scenes in Boston and Singapore, two cities that are known for their dense traffic and highly challenging driving situations.<br>
You can find in [Paper](https://arxiv.org/pdf/1903.11027.pdf)   <br>
**nuScenes-lidarseg**  <br>
It is the most complete test dataset for LiDAR, including 850 training scenarios, 150 test scenarios, an astonishing 1.4 billion annotation points, 40,000 point cloud frames, and 32 levels of classification. <br>
You can find in [Paper](https://www.nuscenes.org/nuscenes#panoptic)   <br>
**JRDB**  <br>
The dataset includes 64 minutes of annotated multimodal sensor data including stereo cylindrical 360 degrees RGB video at 15 fps, 3D point clouds from two Velodyne 16 Lidars, line 3D point clouds from two Sick Lidars, audio signal, RGB-D video at 30 fps, 360 degrees spherical image from a fisheye camera and encoder values from the robot's wheels. <br>
You can find in [Paper](https://blog.csdn.net/moxibingdao/article/details/106667809)   <br>
## RGB-D-T:
**VDT2048**  <br>
This dataset contains 2048 image groups, and each group contains triple-modal images (i.e., visible image, depth image, and thermal image). All of the images have the same resolution of 640×480. This dataset collected 34 household items in the seven most common household scenes.<br>
You can find in [Paper](https://github.com/VDT-2048/VDT-Dataset)   <br>










--------------------------------------------------------------------------------------
# Multi-modal  fusion for  object detection（RGB-T)
## 2023
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
01 | **IEEE** | Cross-Modality Double Bidirectional Interaction and Fusion Network for RGB-T Salient Object Detection| [Paper](https://ieeexplore.ieee.org/document/10032588)/[Code]()
02 | **IEEE** | Feature Enhancement and Fusion for RGB-T Salient Object Detection| [Paper](https://ieeexplore.ieee.org/document/10222404/)/[Code]()
03 | **IEEE** | Modality-Induced Transfer-Fusion Network for RGB-D and RGB-T Salient Object Detection| [Paper](https://ieeexplore.ieee.org/document/9925217)/[Code]()
04 | **IEEE** | SF-YOLO: RGB-T Fusion Object Detection in UAV Scenes| [Paper](https://ieeexplore.ieee.org/document/10270358)/[Code]()
05 | **IEEE** | CAVER: Cross-Modal View-Mixed Transformer for Bi-Modal Salient Object Detection| [Paper](https://ieeexplore.ieee.org/document/10015667)/[Code]()
06| **IEEE** | Scribble-Supervised RGB-T Salient Object Detection | [Paper](https://ieeexplore.ieee.org/document/10219673)/[Code]()
07 | **IEEE** | (*)Modality Registration and Object Search Framework for UAV-Based Unregistered RGB-T Image Salient Object Detection| [Paper](https://ieeexplore.ieee.org/document/10315195)/[Code]()
08 | **IEEE** | A Potential Vision-Based Measurements Technology: Information Flow Fusion Detection Method Using RGB-Thermal Infrared Images| [Paper](https://ieeexplore.ieee.org/document/10015881#full-text-header)/[Code]()
09 | **IEEE** | Vehicle Detection Based on Adaptive Multimodal Feature Fusion and Cross-Modal Vehicle Index Using RGB-T Images| [Paper](https://ieeexplore.ieee.org/document/10179923/)/[Code]()
10| **IEEE** | Does Thermal Really Always Matter for RGB-T Salient Object Detection? | [Paper](https://ieeexplore.ieee.org/document/9926193#full-text-header)/[Code]()
11 | **IEEE** | HRTransNet: HRFormer-Driven Two-Modality Salient Object Detection | [Paper](https://ieeexplore.ieee.org/document/9869666)/[Code]()
12 | **IEEE** | WaveNet: Wavelet Network With Knowledge Distillation for RGB-T Salient Object Detection | [Paper](https://ieeexplore.ieee.org/document/10127616)/[Code]()
13 | **Elsevier** |Drone-based RGBT tiny person detection | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271623002319#preview-section-snippets)/[Code]()
14✔ | **Elsevier** | Illumination-aware window transformer for RGBT modality fusion| [Paper](https://www.sciencedirect.com/science/article/pii/S1047320322002450)/[Code]()
15✔ | **Elsevier** | Multimodal salient object detection via adversarial learning with collaborative generator | [Paper](https://www.sciencedirect.com/science/article/pii/S0952197622006972)/[Code]()
16 | **Elsevier** | Feature aggregation with transformer for RGB-T salient object detection| [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231223004526)/[Code]()
17✔| **Elsevier** |SIA: RGB-T salient object detection network with salient-illumination awareness| [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0143816623003718)/[Code]()
18 | **Elsevier** |Thermal images-aware guided early fusion network for cross-illumination RGB-T salient object detection | [Paper](https://www.sciencedirect.com/science/article/pii/S0952197622006303)/[Code]()
19 *| **Elsevier** | RGB-T image analysis technology and application: A survey| [Paper](https://www.sciencedirect.com/science/article/pii/S0952197623001033)/[Code]()
20 | **Elsevier** |CrossFuse: A novel cross attention mechanism based infrared and visible image fusion approach | [Paper](https://www.sciencedirect.com/science/article/pii/S1566253523004633#sec5)/[Code]()
21 | **Elsevier** |Feature dynamic alignment and refinement for infrared–visible image fusion: Translation robust fusion | [Paper](https://www.sciencedirect.com/science/article/pii/S1566253523000519)/[Code]()
# Multi-modal  fusion for  object detection（RGB-D)
## 2023
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
01 | **IEEE** | Modality-Induced Transfer-Fusion Network for RGB-D and RGB-T Salient Object Detection| [Paper](https://ieeexplore.ieee.org/document/9925217)/[Code]()
02 | **IEEE** | CAVER: Cross-Modal View-Mixed Transformer for Bi-Modal Salient Object Detection| [Paper](https://ieeexplore.ieee.org/document/10015667)/[Code]()
03| **IEEE** |(survey) RGB-D and Thermal Sensor Fusion: A Systematic Literature Review| [Paper](https://ieeexplore.ieee.org/document/10201865)/[Code]()
04 | **IEEE** | CMCLNet Cross-Modality Attention Fusion and Cross-Level Feature Interaction for RGBD salient object detection| [Paper](https://ieeexplore.ieee.org/document/10262928)/[Code]()
05 | **IEEE** | Depth Injection Framework for RGBD Salient Object Detection| [Paper](https://ieeexplore.ieee.org/document/10258039#full-text-header)/[Code]()
06| **IEEE** |Surface Defect Detection for No-Service Rails With Skeleton-Aware Accurate and Fast Network | [Paper](https://ieeexplore.ieee.org/document/10304418)/[Code]()
07✔| **IEEE** |A Large Scale Multi-View RGBD Visual Affordance Learning Dataset | [Paper](https://ieeexplore.ieee.org/document/10222906)/[Code]()
08✔| **Elsevier** | Multimodal salient object detection via adversarial learning with collaborative generator | [Paper](https://www.sciencedirect.com/science/article/pii/S0952197622006972)/[Code]()
09 | **Elsevier** | Depth guided feature selection for RGBD salient object detection| [Paper](https://www.sciencedirect.com/science/article/pii/S0925231222014102#ab005)/[Code]()
10 | **Elsevier** | Geometry-guided multilevel RGBD fusion for surface normal estimation| [Paper](https://www.sciencedirect.com/science/article/pii/S0140366423001330)/[Code]()
11 | **Elsevier** |Dual attention guided multi-scale fusion network for RGB-D salient object detection | [Paper](https://www.sciencedirect.com/science/article/pii/S0923596523000863)/[Code]()
12 | **Elsevier** |MRNet: Multi-modal and multi-scale refined network for RGB-D salient object detection| [Paper](https://www.sciencedirect.com/science/article/pii/S0031320322006197#sec0015)/[Code]()
13 | **Elsevier** | Transformers and CNNs fusion network for salient object detection| [Paper](https://www.sciencedirect.com/science/article/pii/S0925231222013704#s0070)/[Code]()
14 | **Elsevier** | Bidirectional Attentional Interaction Networks for RGB-D salient object detection| [Paper](https://www.sciencedirect.com/science/article/pii/S026288562300166X#s0065)/[Code]()
15 | **Elsevier** |Channel-overcomplete convolutional architectures for RGB-D salient object detection | [Paper](https://www.sciencedirect.com/science/article/pii/S1051200423001902#ab0010)/[Code]()
16 | **Elsevier** | Depth cue enhancement and guidance network for RGB-D salient object detection| [Paper](https://www.sciencedirect.com/science/article/pii/S104732032300130X)/[Code]()
17 | **Elsevier** |Dual Swin-transformer based mutual interactive network for RGB-D salient object detection | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231223009025#sec4)/[Code]()
18 | **Elsevier** | CVit-Net: A conformer driven RGB-D salient object detector with operation-wise attention learning| [Paper](https://www.sciencedirect.com/science/article/pii/S0957417423005778)/[Code]()
# Multi-modal  fusion for  object detection（RGB-Lidar)
## 2023
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
01 | **IEEE** | ImLiDAR: Cross-Sensor Dynamic Message Propagation Network for 3-D Object Detection| [Paper](https://ieeexplore.ieee.org/document/10268462)/[Code]()
02 | **IEEE** | EPNet++: Cascade Bi-Directional Fusion for Multi-Modal 3D Object Detection| [Paper](https://ieeexplore.ieee.org/document/9983516)/[Code]()
03 | **IEEE** | Camera and LiDAR Fusion for Robust 3D Person Detection in Indoor Environments | [Paper](https://ieeexplore.ieee.org/document/10129627)/[Code]()
04 | **Elsevier** | BCAF-3D: Bilateral Content Awareness Fusion for cross-modal 3D object detection| [Paper](https://www.sciencedirect.com/science/article/pii/S0950705123007025#sec6)/[Code]()
# Multi-modal  fusion for  object detection（others)
## 2023
**No.** | **Pub.** | **Title** | **Links** |**Remark**|
:-: | :-: | :-  | :-: | :-: |
01| **IEEE** |Artifacts Mapping: Multi-Modal Semantic Mapping for Object Detection and 3D Localization | [Paper](https://ieeexplore.ieee.org/document/10256373)/[Code]()|RGB-D-Lidar|
02 | **IEEE** | Ad Hoc-Obstacle Avoidance-Based Navigation System Using Deep Reinforcement Learning for Self-Driving Vehicles| [Paper](https://ieeexplore.ieee.org/document/10189852)/[Code]()|RGB-D RGB-Lidar|
03✔✔| **Elsevier** |A systematic literature review on object detection using near infrared and thermal images | [Paper](https://www.sciencedirect.com/science/article/pii/S092523122300927X#sec3)/[Code]()| RGB-Nir,liadr|
04 | **Elsevier** | Hierarchical Two-stage modal fusion for Triple-modality salient object detection| [Paper](https://www.sciencedirect.com/science/article/pii/S0263224123007443)/[Code]()| RGB-D-T SOD|
05 | **Elsevier** |Lightweight multi-level feature difference fusion network for RGB-D-T salient object detection | [Paper](https://www.sciencedirect.com/science/article/pii/S1319157823002562)/[Code]()| RGB-D-T SOD|

--------------------------------------------------------------------------------------
# Multi-modal  fusion for  object detection（survey)
## 2023
**No.** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-  | :-: 
01 | **Elsevier** | A systematic review of image-level camouflaged object detection with deep learning| [Paper](https://www.sciencedirect.com/science/article/pii/S0925231223011736)/[Code]()
02 | **Elsevier** | RGB-T image analysis technology and application: A survey| [Paper](https://www.sciencedirect.com/science/article/pii/S0952197623001033)/[Code]()
03 | **Elsevier** |A systematic literature review on object detection using near infrared and thermal images | [Paper](https://www.sciencedirect.com/science/article/pii/S092523122300927X#sec3)/[Code]()







--------------------------------------------------------------------------------------
# keep updating
