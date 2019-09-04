# Awesome Scene Understanding

A resource repository for scene understanding, inspired by [3D-Machine-Learning](https://github.com/timzhang642/3D-Machine-Learning).

## Contributing

Please feel free to [pull requests](https://github.com/bertjiazheng/awesome-scene-understanding/pulls) to add papers.

## Table of Contents

- [Survey](#survey)
- [Dataset](#dataset)
  - [Realistic Datasets](#realistic_dataset)
  - [Synthetic Datasets](#synthetic_dataset)
- [Holistic Scene Understanding](#holistic_scene_understanding)
  - [Perspective Image](#perspective_scene)
  - [Panoramic Image](#panoramic_scene)
- [Room Layout Estimation](#room_layout_estimation)
  - [Perspective Image](#perspective_layout)
  - [Panoramic Image](#panoramic_layout)
- [Floorplan](#floorplan)
- [Primitive Detection](#primitive_detection)
  - [Junction](#junction)
  - [Line Segment](#line_segment)
  - [Wireframe](#wireframe)
  - [Plane](#plane)
  - [Rectangle](#rectangle)
  - [Cuboid](#cuboid)
- [Object Reconstruction](#object)
  - [Patch](#patch)
  - [Mesh](#mesh)
  - [Primitive](#primitive)
  - [Hierarchy](#hierarchy)
  - [Implicit](#implicit)

<a name="survey" />

## Survey

* RGBD Datasets: Past, Present and Future (CVPRW'16) [[Project]](http://www.michaelfirman.co.uk/RGBDdatasets/) [[Paper]](https://arxiv.org/pdf/1604.00999.pdf)

* Indoor Scene Understanding in 2.5/3D for Autonomous Agents: A Survey (IEEE Access'19) [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8573760&tag=1)

<a name="dataset" />

## Dataset

<a name="realistic_dataset" />

### Realistic Dataset

* [NYUv2] Indoor Segmentation and Support Inference from RGBD Images (ECCV'12) [[Project]](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2) [[Paper]](http://cs.nyu.edu/~silberman/papers/indoor_seg_support.pdf)

* SUN3D: A Database of Big Spaces Reconstructed using SfM and Object Labels (ICCV'13) [[Project]](http://sun3d.cs.princeton.edu/) [[Paper]](http://openaccess.thecvf.com/content_iccv_2013/papers/Xiao_SUN3D_A_Database_2013_ICCV_paper.pdf)

* SUN RGB-D: A RGB-D Scene Understanding Benchmark Suite (CVPR'15) [[Project]](http://rgbd.cs.princeton.edu/) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2015/papers/Song_SUN_RGB-D_A_2015_CVPR_paper.pdf)

* SceneNN: a Scene Meshes Dataset with aNNotations (3DV'16) [[Project]](http://www.scenenn.net) [[Paper]](http://www.scenenn.net/pdf/dataset_3dv16.pdf)

* ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes (CVPR'17) [[Project]](http://www.scan-net.org/) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Dai_ScanNet_Richly-Annotated_3D_CVPR_2017_paper.pdf)

* [2D-3D-S] Joint 2D-3D-Semantic Data for Indoor Scene Understanding (CoRR'17) [[Project]](http://buildingparser.stanford.edu/dataset.html) [[Paper]](https://arxiv.org/pdf/1702.01105.pdf)

* Matterport3D: Learning from RGB-D Data in Indoor Environments (3DV'17) [[Project]](https://niessner.github.io/Matterport/) [[Paper]](https://arxiv.org/pdf/1709.06158.pdf) [[Code]](https://github.com/niessner/Matterport) 

* The Replica Dataset: A Digital Replica of Indoor Spaces (CoRR'19) [[Paper]](https://arxiv.org/pdf/1906.05797.pdf) [[Code]](https://github.com/facebookresearch/Replica-Dataset)

<a name="synthetic_dataset" />

### Synthetic Dataset

* The SYNTHIA Dataset: A Large Collection of Synthetic Images for Semantic Segmentation of Urban Scenes (CVPR'16) [[Project]](http://synthia-dataset.net/) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2016/papers/Ros_The_SYNTHIA_Dataset_CVPR_2016_paper.pdf)

* SceneNet: Understanding Real World Indoor Scenes With Synthetic Data (CVPR'16) [[Project]](https://robotvault.bitbucket.io/) [[Paper]](http://arxiv.org/pdf/1511.07041.pdf)

* [SUNCG] Semantic Scene Completion from a Single Depth Image (CVPR'17) [[Paper]](https://arxiv.org/pdf/1611.08974v1.pdf)

* SceneNet RGB-D: Can 5M Synthetic Images Beat Generic ImageNet Pre-training on Indoor Segmentation? (ICCV'17) [[Project]](https://robotvault.bitbucket.io/scenenet-rgbd.html) [[Paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/McCormac_SceneNet_RGB-D_Can_ICCV_2017_paper.pdf)

* InteriorNet: Mega-scale Multi-sensor Photo-realistic Indoor Scenes Dataset (BMVC'18) [[Project]](https://interiornet.org/) [[Paper]](https://arxiv.org/pdf/1809.00716.pdf)

* Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling (CoRR'19) [[Project]](https://structured3d-dataset.org) [[Paper]](https://arxiv.org/pdf/1908.00222.pdf) [[Code]](https://github.com/bertjiazheng/Structured3D)

<a name="holistic_scene_understanding" />

## Holistic Scene Understanding

<a name="perspective_scene" />

### Perspective Image

* Thinking Inside the Box: Using Appearance Models and Context Based on Room Geometry (ECCV'10) [[Paper]](http://vision.cs.uiuc.edu/~vhedau2/Publications/eccv2010_think_inside.pdf)

* Estimating Spatial Layout of Rooms using Volumetric Reasoning about Objects and Surfaces (NeurIPS'10) [[Paper]](https://papers.nips.cc/paper/4120-estimating-spatial-layout-of-rooms-using-volumetric-reasoning-about-objects-and-surfaces.pdf)

* Efficient Structured Prediction for 3D Indoor Scene Understanding (CVPR'12) [[Paper]](https://ttic.uchicago.edu/~rurtasun/publications/schwing_et_al_cvpr12.pdf)

* Efficient Exact Inference for 3D Indoor Scene Understanding (ECCV'12) [[Paper]](http://schwingag.de/papers/SchwingEtAl_ECCV2012.pdf)

* Recovering Free Space of Indoor Scenes from a Single Image (CVPR'12) [[Paper]](http://vision.cs.uiuc.edu/~vhedau2/Publications/cvpr2012_freespace.pdf)

* Understanding Indoor Scenes using 3D Geometric Phrases (CVPR'13) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2013/papers/Choi_Understanding_Indoor_Scenes_2013_CVPR_paper.pdf)

* Scene Parsing by Integrating Function, Geometry and Appearance Models (CVPR'13) [[Project]](http://www.stat.ucla.edu/~ybzhao/research/functionality/) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2013/papers/Zhao_Scene_Parsing_by_2013_CVPR_paper.pdf)

* Emptying, Refurnishing, and Relighting Indoor Spaces (SIGGRAPH Asia'16) [[Project]](https://grail.cs.washington.edu/projects/emptying/) [[Paper]](https://grail.cs.washington.edu/projects/emptying/emptying.pdf)

* DeepContext: Context-Encoding Neural Pathways for 3D Holistic Scene Understanding (ICCV'17) [[Project]](http://deepcontext.cs.princeton.edu) [[Paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhang_DeepContext_Context-Encoding_Neural_ICCV_2017_paper.pdf)

* Im2CAD (CVPR'18) [[Project]](https://homes.cs.washington.edu/~izadinia/im2cad.html) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Izadinia_IM2CAD_CVPR_2017_paper.pdf)

* Factoring Shape, Pose, and Layout from the 2D Image of a 3D Scene (CVPR'18) [[Project]](https://shubhtuls.github.io/factored3d/) [[Paper]](https://arxiv.org/pdf/1712.01812.pdf) [[Code]](https://github.com/shubhtuls/factored3d)

* Holistic 3D Scene Parsing and Reconstruction from a Single RGB Image (ECCV'18) [[Project]](http://siyuanhuang.com/holistic_parsing/main.html) [[Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Siyuan_Huang_Monocular_Scene_Parsing_ECCV_2018_paper.pdf) [[Code]](https://github.com/thusiyuan/holistic_scene_parsing)

* Cooperative Holistic Scene Understanding: Unifying 3D Object, Layout, and Camera Pose Estimation (NeurIPS'18) [[Project]](http://siyuanhuang.com/cooperative_parsing/main.html) [[Paper]](https://papers.nips.cc/paper/7305-cooperative-holistic-scene-understanding-unifying-3d-object-layout-and-camera-pose-estimation.pdf) [[Code]](https://github.com/thusiyuan/cooperative_scene_parsing)

* Complete 3D Scene Parsing from an RGBD Image (IJCV'18) [[Paper]](https://arxiv.org/pdf/1710.09490.pdf)

<a name="panoramic_scene" />

### Panoramic Image

* PanoContext: A Whole-room 3D Context Model for Panoramic Scene Understanding (ECCV'14) [[Project]](http://panocontext.cs.princeton.edu/) [[Paper]](http://panocontext.cs.princeton.edu/paper.pdf)

* Pano2CAD: Room Layout From A Single Panorama Image (WACV'17) [[Paper]](http://bjornstenger.github.io/papers/xu_wacv2017.pdf)

* Automatic 3D Indoor Scene Modeling from Single Panorama (CVPR'18) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_Automatic_3D_Indoor_CVPR_2018_paper.pdf)

<a name="room_layout_estimation" />

## Room Layout Estimation

<a name="perspective_layout" />

### Perspective Image

* Recovering the Spatial Layout of Cluttered Rooms (ICCV'09) [[Paper]](http://dhoiem.cs.illinois.edu/publications/iccv2009_hedau_indoor.pdf)

* Estimating the 3D Layout of Indoor Scenes and its Clutter from Depth Sensors (ICCV'13) [[Project]](https://cs.stanford.edu/people/zjian/project/ICCV13DepthLayout/ICCV13DepthLayout.html) [[Paper]](http://openaccess.thecvf.com/content_iccv_2013/papers/Zhang_Estimating_the_3D_2013_ICCV_paper.pdf)

* Box In the Box: Joint 3D Layout and Object Reasoning from Single Images (CVPR'13) [[Paper]](http://openaccess.thecvf.com/content_iccv_2013/papers/Schwing_Box_in_the_2013_ICCV_paper.pdf)

* Rent3D: Floor-Plan Priors for Monocular Layout Estimation (CVPR'15) [[Project]](http://www.cs.toronto.edu/~fidler/projects/rent3D.html) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2015/papers/Liu_Rent3D_Floor-Plan_Priors_2015_CVPR_paper.pdf)

* Learning Informative Edge Maps for Indoor Scene Layout Prediction (ICCV'15) [[Homepage]](http://arunmallya.github.io/) [[Paper]](http://openaccess.thecvf.com/content_iccv_2015/papers/Mallya_Learning_Informative_Edge_ICCV_2015_paper.pdf)

* DeLay: Robust Spatial Layout Estimation for Cluttered Indoor Scenes (CVPR'16) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2016/papers/Dasgupta_DeLay_Robust_Spatial_CVPR_2016_paper.pdf)

* A Coarse-to-Fine Indoor Layout Estimation (CFILE) Method (ACCV'16) [[Paper]](https://arxiv.org/pdf/1607.00598.pdf)

* Physics Inspired Optimization on Semantic Transfer Features: An Alternative Method for Room Layout Estimation (CVPR'17) [[Project]](https://sites.google.com/view/st-pio/) [[Paper]](https://arxiv.org/pdf/1707.00383.pdf)

* RoomNet: End-to-End Room Layout Estimation (ICCV'17) [[Paper]](https://arxiv.org/pdf/1703.06241.pdf)

* Thinking Outside the Box: Generation of Unconstrained 3D Room Layouts (ACCV'18) [[Paper]](https://arxiv.org/pdf/1905.03105.pdf)

* Flat2Layout: Flat Representation for Estimating Layout of General Room Types (CoRR'19) [[Paper]](https://arxiv.org/pdf/1903.08094.pdf)

<a name="panoramic_layout" />

### Panoramic Image

* Efficient 3D Room Shape Recovery From a Single Panorama (CVPR'16) [[Project]](http://cgcad.thss.tsinghua.edu.cn/yanghao/3droom/) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2016/papers/Yang_Efficient_3D_Room_CVPR_2016_paper.pdf) [[Code]](https://github.com/YANG-H/Panoramix)

* LayoutNet: Reconstructing the 3D Room Layout from a Single RGB Image (CVPR'18) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zou_LayoutNet_Reconstructing_the_CVPR_2018_paper.pdf) [[Code]](https://github.com/zouchuhang/LayoutNet)

* Layouts from Panoramic Images with Geometry and Deep Learning (IROS'18) [[Paper]](https://arxiv.org/pdf/1806.08294.pdf) [[Code]](https://github.com/cfernandezlab/Lines-and-Vanishing-Points-directly-on-Panoramas)

* HorizonNet: Learning Room Layout with 1D Representation and Pano Stretch Data Augmentation (CVPR'19) [[Paper]](https://arxiv.org/pdf/1901.03861) [[Code]](https://github.com/sunset1995/HorizonNet)

* DuLa-Net: A Dual-Projection Network for Estimating Room Layouts from a Single RGB Panorama (CVPR'19) [[Project]](https://cgv.cs.nthu.edu.tw/projects/dulanet) [[Paper]](https://arxiv.org/pdf/1811.11977.pdf)

* Corners for Layout: End-to-End Layout Recovery from 360 Images (CoRR'19) [[Project]](https://cfernandezlab.github.io/CFL/)  [[Paper]](https://arxiv.org/pdf/1903.08094.pdf) [[Code]](https://github.com/cfernandezlab/CFL-End-to-End-Layout-Recovery-from-360-Images)

<a name="floorplan" />

## Floorplan

### Reconstruction

* Raster-to-Vector: Revisiting Floorplan Transformation (ICCV'17) [[Project]](http://art-programmer.github.io/floorplan-transformation.html) [[Paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_Raster-To-Vector_Revisiting_Floorplan_ICCV_2017_paper.pdf) [[Code]](https://github.com/art-programmer/FloorplanTransformation)

* FloorNet: A unified framework for floorplan reconstruction from 3D scans (ECCV'18) [[Project]](http://art-programmer.github.io/floornet.html) [[Paper]](https://arxiv.org/pdf/1804.00090.pdf) [[Code]](https://github.com/art-programmer/FloorNet)

* Floorplan Priors for Joint Camera Pose and Room Layout Estimation (CoRR'18) [[Paper]](https://arxiv.org/pdf/1812.06677.pdf)

* HouseExpo: A Large-scale 2D Indoor Layout Dataset for Learning-based Algorithms on Mobile Robots (CoRR'19) [[Paper]](https://arxiv.org/pdf/1903.09845.pdf) [[Code]](https://github.com/TeaganLi/HouseExpo)

* CubiCasa5K: A Dataset and an Improved Multi-Task Model for Floorplan Image Analysis (CoRR'19) [[Paper]](https://arxiv.org/abs/1904.01920) [[Code]](https://github.com/CubiCasa/CubiCasa5k)

* DeepPerimeter: Indoor Boundary Estimation from Posed Monocular Sequences (CoRR'19) [[Paper]](https://arxiv.org/pdf/1904.11595.pdf)

* Floor-SP: Inverse CAD for Floorplans by Sequential Room-wise Shortest Path (ICCV'19) [[Project]](https://jcchen.me/floor-sp/) [[Paper]](https://arxiv.org/pdf/1908.06702.pdf) [[Code]](https://github.com/woodfrog/floor-sp)

* Deep Floor Plan Recognition using a Multi-task Network with Room-boundary-Guided Attention (ICCV'19) [[Project]](https://github.com/zlzeng/DeepFloorplan) [[Paper]](https://arxiv.org/pdf/1908.11025.pdf)

<a name="primitive_detection" />

## Primitive Detection

<a name="junction" />

### Junction

* Manhattan Junction Catalogue for Spatial Reasoning of Indoor Scenes (CVPR'13) [[Paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Ramalingam_Manhattan_Junction_Catalogue_2013_CVPR_paper.pdf)

<a name="line_segment" />

### Line Segment

* LSD: A Fast Line Segment Detector with a False Detection Control (TPAMI'10) [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4731268)

* Lifting 3D Manhattan Lines from a Single Image (ICCV'15) [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6751171)

* MCMLSD: A Dynamic Programming Approach to Line Segment Detection (CVPR'17) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Almazan_MCMLSD_A_Dynamic_CVPR_2017_paper.pdf)

* A Novel Linelet-Based Representation for Line Segment Detection (TPAMI'18) [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7926451)

* Novel Single View Constraints for Manhattan 3D Line Reconstruction (3DV'18) [[Paper]](https://arxiv.org/pdf/1810.03737.pdf)

* Learning Attraction Field Representation for Robust Line Segment Detection (CVPR'19) [[Paper]](https://arxiv.org/pdf/1812.02122.pdf) [[Code]](https://github.com/cherubicXN/afm_cvpr2019)

<a name="wireframe" />

### Wireframe

* Learning to Parse Wireframes in Images of Man-Made Environments (CVPR'18) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_Learning_to_Parse_CVPR_2018_paper.pdf) [[Code]](https://github.com/huangkuns/wireframe)

* PPGNet: Learning Point-Pair Graph for Line Segment Detection (CVPR'19) [[Paper]](https://arxiv.org/pdf/1905.03415.pdf) [[Code]](https://github.com/svip-lab/PPGNet)

* End-to-End Wireframe Parsing (ICCV'19) [[Paper]](https://arxiv.org/pdf/1905.03246.pdf) [[Code]](https://github.com/zhou13/lcnn)

* Learning to Reconstruct 3D Manhattan Wireframes from a Single Image (ICCV'19) [[Paper]](https://arxiv.org/pdf/1905.07482.pdf)

<a name="plane" />

### Plane

* PlaneNet: Piece-wise Planar Reconstruction from a Single RGB Image (CVPR'18) [[Project]](https://www.cse.wustl.edu/~chenliu/planenet.html) [[Paper]](https://arxiv.org/abs/1804.06278) [[Code]](https://github.com/art-programmer/PlaneNet)

* LS3D: Single-View Gestalt 3D Surface Reconstruction from Manhattan Line Segment (ACCV'18) [[Paper]](http://www.elderlab.yorku.ca/wp-content/uploads/2018/12/LS3DACCV18.pdf)

* Recovering 3D Planes from a Single Image via Convolutional Neural Networks (ECCV'18) [[Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Fengting_Yang_Recovering_3D_Planes_ECCV_2018_paper.pdf) [[Code]](https://github.com/fuy34/planerecover)

* PlaneRCNN: 3D Plane Detection and Reconstruction from a Single Image (CVPR'19) [[Project]](https://research.nvidia.com/publication/2019-06_PlaneRCNN) [[Paper]](https://arxiv.org/pdf/1812.04072.pdf) [[Code]](https://github.com/NVlabs/planercnn)

* Single-Image Piece-wise Planar 3D Reconstruction via Associative Embedding (CVPR'19) [[Paper]](https://arxiv.org/pdf/1902.09777.pdf) [[Code]](https://github.com/svip-lab/PlanarReconstruction)

<a name="rectangle" />

### Rectangle

* Bottom-Up/Top-Down Image Parsing with Attribute Grammar (TPAMI'09) [[Paper]](http://www.stat.ucla.edu/~sczhu/papers/PAMI_Grammar_rectangle.pdf)

<a name="cuboid" />

### Cuboid

* A Linear Approach to Matching Cuboids in RGBD Images (CVPR'13) [[Project]](https://vision.princeton.edu/projects/2013/RGBDcuboid/index.html) [[Paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Jiang_A_Linear_Approach_2013_CVPR_paper.pdf)

* Deep Cuboid Detection: Beyond 2D Bounding Boxes (CoRR'16) [[Paper]](https://arxiv.org/pdf/1611.10010.pdf)

<a name="object" />

## Object Reconstruction

<a name="patch" />

### Patch-based

* A Papier-Mâché Approach to Learning 3D Surface Generation (CVPR'18) [[Project]](http://imagine.enpc.fr/~groueixt/atlasnet/) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Groueix_A_Papier-Mache_Approach_CVPR_2018_paper.pdf) [[Code]](https://github.com/ThibaultGROUEIX/AtlasNet)

* Adaptive O-CNN: A Patch-based Deep Representation of 3D Shapes (SIGGRAPH Asia'18) [[Project]](https://wang-ps.github.io/AO-CNN) [[Paper]](https://arxiv.org/pdf/1809.07917.pdf) [[Code]](https://github.com/Microsoft/O-CNN)

<a name="mesh" />

### Mesh-based

* Neural 3D Mesh Renderer (CVPR'18) [[Project]](http://hiroharu-kato.com/projects_en/neural_renderer.html) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kato_Neural_3D_Mesh_CVPR_2018_paper.pdf) [[Code]](https://github.com/hiroharu-kato/neural_renderer)

* Pixel2Mesh: Generating 3D Mesh Models from Single RGB Images (ECCV'18) [[Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Nanyang_Wang_Pixel2Mesh_Generating_3D_ECCV_2018_paper.pdf) [[Code]](https://github.com/nywang16/Pixel2Mesh)

* GEOMetrics: Exploiting Geometric Structure for Graph-Encoded Objects (ICML'19) [[Paper]](https://arxiv.org/pdf/1901.11461.pdf) [[Code]](https://github.com/EdwardSmith1884/GEOMetrics)

* A Skeleton-bridged Deep Learning Approach for Generating Meshes of Complex Topologies from Single RGB Images (CVPR'19) [[Paper]](https://arxiv.org/pdf/1903.04704.pdf)

* Mesh R-CNN (ICCV'19) [[Paper]](https://arxiv.org/pdf/1906.02739.pdf)

<a name="primitive" />

### Primitive-based

* Learning Shape Abstractions by Assembling Volumetric Primitives (CVPR'17) [[Project]](https://shubhtuls.github.io/volumetricPrimitives/) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Tulsiani_Learning_Shape_Abstractions_CVPR_2017_paper.pdf) [[Code]](https://github.com/shubhtuls/volumetricPrimitives)

* 3D-PRNN: Generating Shape Primitives with Recurrent Neural Networks (ICCV'17) [[Paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zou_3D-PRNN_Generating_Shape_ICCV_2017_paper.pdf) [[Code]](https://github.com/zouchuhang/3D-PRNN)

* Im2Struct: Recovering 3D Shape Structure from a Single RGB Image（CVPR'18) [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Niu_Im2Struct_Recovering_3D_CVPR_2018_paper.pdf) [[Code]](https://github.com/chengjieniu/Im2Struct)

* Superquadrics Revisited: Learning 3D Shape Parsing beyond Cuboids (CVPR'19) [[Paper]](https://arxiv.org/pdf/1904.09970.pdf) [[Code]](https://github.com/paschalidoud/superquadric_parsing)

<a name="hierarchy" />

### Hierarchy

* GRASS: Generative Recursive Autoencoders for Shape Structures (SIGGRAPH'17) [[Project]](https://kevinkaixu.net/projects/grass.html) [[Paper]](https://arxiv.org/pdf/1705.02090.pdf) [[Code]](https://github.com/junli-lj/Grass)

* StructureNet : Hierarchical Graph Networks for 3D Shape Generation (SIGGRAPH Asia'19) [[Project]](https://cs.stanford.edu/~kaichun/structurenet/) [[Paper]](https://arxiv.org/pdf/1908.00575.pdf) [[Code]](https://github.com/daerduoCarey/structurenet)

<a name="Implicit" />

### Implicit

* Learning Implicit Fields for Generative Shape Modeling (CVPR'19) [[Project]](https://www.sfu.ca/~zhiqinc/imgan/Readme.html) [[Paper]](https://arxiv.org/pdf/1812.02822.pdf) [[Code]](https://github.com/czq142857/implicit-decoder)

* Occupancy Networks: Learning 3D Reconstruction in Function Space (CVPR'19) [[Project]](https://avg.is.tuebingen.mpg.de/publications/occupancy-networks) [[Paper]](https://arxiv.org/pdf/1812.03828.pdf) [[Code]](https://github.com/autonomousvision/occupancy_networks)

* DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation (CVPR'19) [[Paper]](https://arxiv.org/pdf/1901.05103.pdf) [[Code]](https://github.com/facebookresearch/DeepSDF)

* Deep Level Sets: Implicit Surface Representations for 3D Shape Inference (CoRR'19) [[Paper]](https://arxiv.org/pdf/1901.06802.pdf)

* Learning Shape Templates with Structured Implicit Functions (CoRR'19) [[Paper]](https://arxiv.org/pdf/1904.06447.pdf)

* DISN: Deep Implicit Surface Network for High-quality Single-view 3D Reconstruction (NeurIPS'19) [[Paper]](https://arxiv.org/pdf/1905.10711.pdf) [[Code]](https://github.com/laughtervv/DISN)
