# IROS-2022-SLAM-paper-list 
 
This repository is a collection of papers related to SLAM for personal research purposes.  
Based on [PaoPaoRobot/IROS2022-paper-list](https://github.com/PaoPaoRobot/IROS2022-paper-list), categories were sorted by myself.  
If there are any missing papers or incorrect information, please feel free to contact me or leave an issue.  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

## Table of contents  
- [Dataset](#dataset)  
- [Visual odometry / Visual SLAM / Structure-From-Motion](#visual-odometry--visual-slam--structure-from-motion)  
- [Visual-inertial odometry / Visual-inertial SLAM](#visual-inertial-odometry--visual-inertial-slam)  
- [Visual localization / Visual place recognition](#visual-localization--visual-place-recognition)
- [LiDAR odometry / LiDAR SLAM](#lidar-odometry--lidar-slam)  
- [LiDAR-inertial odometry / LiDAR-inertial SLAM](#lidar-inertial-odometry--lidar-inertial-slam)  
- [LiDAR localization / LiDAR place recognition](#lidar-localization--lidar-place-recognition)
- [Point cloud registration](#point-cloud-registration)  
- [3D reconstruction](#3d-reconstruction)
- [Sensor fusion](#sensor-fusion)  
- [Inertial odometry / INS](#inertial-odometry--ins)  
- [Multi Robot SLAM / Localization](#multi-robot-slam--localization)  
- [Etc](#etc)

## Dataset  
- Are We Ready for Robust and Resilient SLAM? a Framework for Quantitative Characterization of SLAM Datasets  
- Multi-Modal Lidar Dataset for Benchmarking General-Purpose Localization and Mapping Algorithms  
- FusionPortable: A Multi-Sensor Campus-Scene Dataset for Evaluation of Localization and Mapping Accuracy on Diverse Platforms  
- STheReO: Stereo Thermal Dataset for Research in Odometry and Mapping  
- Challenges of SLAM in Extremely Unstructured Environments: The DLR Planetary Stereo, Solid-State LiDAR, Inertial Dataset  
- OdomBeyondVision: An Indoor Multi-Modal Multi-Platform Odometry Dataset Beyond the Visible Spectrum  
- The Hilti SLAM Challenge Dataset  
- WiSARD: A Labeled Visual and Thermal Image Dataset for Wilderness Search and Rescue  
- Danish Airs and Grounds: A Dataset for Aerial-To-Street-Level Place Recognition and Localization

[[top](#iros-2022-slam-paper-list)]

## Visual odometry / Visual SLAM / Structure-From-Motion  
- Real-Time Hybrid Mapping of Populated Indoor Scenes using a Low-Cost Monocular UAV  
- 360ST-Mapping: An Online Semantics-Guided Topological Mapping Module for Omnidirectional Visual SLAM  
- An Algorithm for the SE(3)-Transformation on Neural Implicit Maps for Remapping Functions  
- DRG-SLAM: A Semantic RGB-D SLAM Using Geometric Features for Indoor Dynamic Scene  
- RGB-D SLAM in Indoor Planar Environments with Multiple Large Dynamic Objects  
- Scale-Aware Direct Monocular Odometry  
- Scale Estimation with Dual Quadrics for Monocular Object SLAM  
- GeoROS: Georeferenced Real-time Orthophoto Stitching with Unmanned Aerial Vehicle  
- Learning to Complete Object Shapes for Object-level Mapping in Dynamic Scenes  
- LODM: Large-scale Online Dense Mapping for UAV  
- AFT-VO: Asynchronous Fusion Transformers for Multi-View Visual Odometry Estimation  
- Keyframe Selection with Information Occupancy Grid Model for Long-term Data Association  
- SLAM-Supported Self-Training for 6D Object Pose Estimation  
- On the Coupling of Depth and Egomotion Networks for Self-Supervised Structure from Motion  
- Exploring Event Camera-Based Odometry for Planetary Robots  
- OdomBeyondVision: An Indoor Multi-Modal Multi-Platform Odometry Dataset Beyond the Visible Spectrum  
- CFP-SLAM: A Real-Time Visual SLAM Based on Coarse-To-Fine Probability in Dynamic Environments  
- Probabilistic Data Association for Semantic SLAM at Scale  
- Visual Mapping and Localization System Based on Compact Instance-Level Road Markings with Spatial Uncertainty  
- Floorplan-Aware Camera Poses Refinement  
- MOTSLAM: MOT-Assisted Monocular Dynamic SLAM Using Single-View Depth Estimation  
- Tracking Monocular Camera Pose and Deformation for SLAM Inside the Human Body  
- These Maps Are Made For Walking: Real-Time Terrain Property Estimation for Mobile Robots  
- Struct-MDC: Mesh-Refined Unsupervised Depth Completion Leveraging Structural Regularities from Visual SLAM  
- Visual Odometry in HDR Environments by Using Spatially Varying Exposure Camera  
- S3LAM: Structured Scene SLAM  
- TwistSLAM: Constrained SLAM in Dynamic Environment  
- A New Dense Hybrid Stereo Visual Odometry Approach  
- Keeping Less Is More: Point Sparsification for Visual SLAM  
- Event-Based Line SLAM in Real-Time  
- LNC Assisted Localization and Mapping in Pipe Environment  
- Simultaneous Localization and Mapping: Through the Lens of Nonlinear Optimization  
- DSOL: A Fast Direct Sparse Odometry Scheme  
- Towards Specialized Hardware for Learning-Based Visual Odometry on the Edge  
- Robust Visual Teach and Repeat for UGVs Using 3D Semantic Maps  
- Hybrid Belief Pruning with Guarantees for Viewpoint-Dependent Semantic SLAM  
- Active Mapping via Gradient Ascent Optimization of Shannon Mutual Information over Continuous SE(3) Trajectories  
- From Timing Variations to Performance Degradation: Understanding and Mitigating the Impact of Software Execution Timing in SLAM


[[top](#iros-2022-slam-paper-list)]

## Visual-inertial odometry / Visual-inertial SLAM  
- FEJ-VIRO: A Consistent First-Estimate Jacobian Visual-Inertial-Ranging Odometry  
- Scalable and Modular Ultra-Wideband Aided Inertial Navigation  
- Monocular Event Visual Inertial Odometry Based on Event-Corner Using Sliding Windows Graph-Based Optimization  
- Thermal Inertial SLAM for the Environments with Challenging Illumination  
- P3-VINS: Tightly Coupled PPP/INS/Visual SLAM Based on Optimization Approach  
- Closed-Form Error Propagation on SEn(3) Group for Invariant EKF with Applications to VINS  
- Observability Analysis and Keyframe-Based Filtering for Visual Inertial Odometry with Full Self-Calibration (I)  
- LF-VIO: A Visual-Inertial-Odometry Framework for Large Field-Of-View Cameras with Negative Plane  
- Tightly-Coupled Visual-Inertial-Pressure Fusion Using Forward and Backward IMU Preintegration  
- Continuous-Time Stereo-Inertial Odometry  
- Square-Root Robocentric Visual-Inertial Odometry with Online Spatiotemporal Calibration  
- Visual-Inertial-Aided Online MAV System Identification  
- BOEM-SLAM: A Block Online EM Algorithm for the Visual-Inertial SLAM Backend  
- Visual-Inertial SLAM with Tightly-Coupled Dropout-Tolerant GPS Fusion  
- RGB-D Inertial Odometry for a Resource-Restricted Robot in Dynamic Environments  
- Towards Robust Visual-Inertial Odometry with Multiple Non-Overlapped Monocular Cameras  
- A Tightly-Coupled Event-Inertial Odometry Using Exponential Decay and Linear Preintegrated Measurements  
- Photometric Visual-Inertial Navigation with Uncertainty-Aware Ensembles (I)  
- Real-Time Visual Inertial Odometry with a Resource-Efficient Harris Corner Detection Accelerator on FPGA Platform  
- Visual-Inertial Multi-Instance Dynamic SLAM with Object-Level Relocalisation  




[[top](#iros-2022-slam-paper-list)]

## Visual localization / Visual place recognition  
- Monocular UAV Localisation with Deep Learning and Uncertainty Propagation  
- LiDAR-Aided Visual-Inertial Localization with Semantic Maps  
- Improving Worst Case Visual Localization Coverage Via Place-Specific Sub-Selection in Multi-Camera Systems  
- Making Parameterization and Constrains of Object Landmark Globally Consistent via SPD(3) Manifold and Improved Cost Functions  
- PI-ARS: Accelerating Evolution-Learned Visual-Locomotion with Predictive Information Representations  
- Enforcing Vision-Based Localization Using Perception Constrained N-MPC for Multi-Rotor Aerial Vehicles  
- Visual Loop Closure Detection for a Future Mars Science Helicopter  
- DH-LC: Hierarchical Matching and Hybrid Bundle Adjustment Towards Accurate and Robust Loop Closure  
- Pose Refinement with Joint Optimization of Visual Points and Lines  
- Spatio-Temporal Graph Localization Networks for Image-Based Navigation  
- Stubborn: A Strong Baseline for Indoor Object Navigation  
- Closing the Loop: Graph Networks to Unify Semantic Objects and Visual Features for Multi-Object Scenes  
- Object-Plane Co-Represented and Graph Propagation-Based Semantic Descriptor for Relocalization  
- A 2D Georeferenced Map Aided Visual-Inertial System for Precise UAV Localization  
- Scalable Fiducial Tag Localization on a 3D Prior Map via Graph-Theoretic Global Tag-Map Registration  
- Fast Structural Representation and Structure-Aware Loop Closing for Visual SLAM  
- LSDNet: A Lightweight Self-Attentional Distillation Network for Visual Place Recognition  
- STUN: Self-Teaching Uncertainty Estimation for Place Recognition  
- VMVG-Loc: Visual Localization for Autonomous Driving Using Vector Map and Voxel Grid Map  
- CGiS-Net: Aggregating Colour, Geometry and Implicit Semantic Features for Indoor Place Recognition  
- Towards holistic autonomous obstacle detection in railways by complementing of on-board vision with UAV-based object localization  
- Predicting to Improve: Integrity Measures for Assessing Visual Localization Performance  
- City-wide Street-to-Satellite Image Geolocalization of a Mobile Ground Agent  





[[top](#iros-2022-slam-paper-list)]

## LiDAR odometry / LiDAR SLAM
- Efficient and Probabilistic Adaptive Voxel Mapping for Accurate Online LiDAR Odometry  
- Efficient 2D LIDAR Based Map Updating for Long Term Operations in Dynamic Environments  
- Online Distance Field Priors for Gaussian Process Implicit Surfaces  
- Map-Free Lidar Odometry (MFLO) Using a Range Flow Constraint and Point Patch Covariances  
- Elevation Mapping for Locomotion and Navigation using GPU  
- PLC-LiSLAM: LiDAR SLAM with Planes, Lines and Cylinders  
- When Geometry Is Not Enough: Using Reflector Markers in Lidar SLAM  
- LOCUS 2.0: Robust and Computationally Efficient LiDAR Odometry for Real-Time 3D Mapping  
- Robust Structure Identification and Room Segmentation of Cluttered Indoor Environments from Occupancy Grid Maps  
- Efficient 2D Graph SLAM for Sparse Sensing  
- RO-LOAM: 3D Reference Object-Based Trajectory and Map Optimization in LiDAR Odometry and Mapping  
- Fast Sparse LiDAR Odometry Using Self-Supervised Feature Selection on Intensity Images  
- MD-SLAM: Multi-Cue Direct SLAM  
- Detecting Invalid Map Merges in Lifelong SLAM  
- PFilter: Building Persistent Maps through Feature Filtering for Fast and Accurate LiDAR-Based SLAM  
- Situational Graphs for Robot Navigation in Structured Indoor Environments  

[[top](#iros-2022-slam-paper-list)]

## LiDAR-inertial odometry / LiDAR-inertial SLAM  
- A LiDAR-Inertial Odometry with Principled Uncertainty Modeling  

[[top](#iros-2022-slam-paper-list)]

## LiDAR localization / LiDAR place recognition  
- Learning-Based Localizability Estimation for Robust LiDAR Localization  
- Fast Scan Context Matching for Omnidirectional 3D Scan  
- Probabilistic Object Maps for Long-Term Robot Localization  
- Hybrid Interval-Probabilistic Localization in Building Maps  
- NDD: A 3D Point Cloud Descriptor Based on Normal Distribution for Loop Closure Detection  
- ULSM: Underground Localization and Semantic Mapping with Salient Region Loop Closure under Perceptually-Degraded Environment  
- One RING to Rule Them All: Radon Sinogram for Place Recognition, Orientation and Translation Estimation  
- ROLL: Long-Term Robust LiDAR-Based Localization with Temporary Mapping in Changing Environments  
- Semantic Topological Descriptor for Loop Closure Detection within 3D Point Clouds in Outdoor Environment  
- Gaussian Variational Inference with Covariance Constraints Applied to Range-Only Localization  
- OverlapTransformer: An Efficient and Yaw-Angle-Invariant Transformer Network for LiDAR-Based Place Recognition  
- Global Data Association for SLAM with 3D Grassmannian Manifold Objects  
- Confidence-rich Localization and Mapping based on Particle Filter for Robotic Exploration  
- Are We Ready for Radar to Replace Lidar in All-Weather Mapping and Localization?  
- FSM: Correspondenceless Scan-Matching of Panoramic 2D Range Scans  
- BoxGraph: Semantic Place Recognition and Pose Estimation from 3D LiDAR  
- InCloud: Incremental Learning for Point Cloud Place Recognition  
- D-LC-Nets: Robust Denoising and Loop Closing Networks for LiDAR SLAM in Complicated Circumstances with Noisy Point Clouds  


[[top](#iros-2022-slam-paper-list)]

## Point cloud registration  
- DCPCR: Deep Compressed Point Cloud Registration in Large-Scale Outdoor Environments  
- Indirect Point Cloud Registration: Aligning Distance Fields Using a Pseudo Third Point Set  
- Point Cloud Registration Leveraging Structural Regularity in Manhattan World  
- Gravity-Constrained Point Cloud Registration  
- LCDNet: Deep Loop Closure Detection and Point Cloud Registration for LiDAR SLAM (I)  
- Linewise Non-Rigid Point Cloud Registration  

[[top](#iros-2022-slam-paper-list)]

## 3D reconstruction
- Neural Scene Representation for Locomotion on Structured Terrain  
- Make It Dense: Self-Supervised Geometric Scan Completion of Sparse 3D LiDAR Scans in Large Outdoor Environments  
- Roadside HD Map Object Reconstruction Using Monocular Camera  
- Robust Change Detection Based on Neural Descriptor Fields  
- S-MKI: Incremental Dense Semantic Occupancy Reconstruction Through Multi-Entropy Kernel Inference  
- Photometric Single-View Dense 3D Reconstruction in Endoscopy  
- Voxfield: Non-Projective Signed Distance Fields for Online Planning and 3D Reconstruction  
- 3D Lidar Reconstruction with Probabilistic Depth Completion for Robotic Navigation  
- Contrastive 3D Shape Completion and Reconstruction for Agricultural Robots Using RGB-D Frames  
- Real-Time Semantic 3D Reconstruction for High-Touch Surface Recognition for Robotic Disinfection  
- ACEFusion : Accelerated and Energy-Efficient Semantic 3D Reconstruction of Dynamic Scenes



[[top](#iros-2022-slam-paper-list)]


## Sensor fusion  
- Multi-Camera-LiDAR Auto-Calibration by Joint Structure-From-Motion  
- Multical: Spatiotemporal Calibration for Multiple IMUs, Cameras and LiDARs  
- Robust Real-Time LiDAR-Inertial Initialization  
- Exploring mmWave Radar and Camera Fusion for High-Resolution and Long-Range Depth Imaging  
- Lidar with Velocity: Correcting Moving Objects Point Cloud Distortion from Oscillating Scanning Lidars by Fusion with Camera  
- DXQ-Net: Differentiable LiDAR-Camera Extrinsic Calibration Using Quality-Aware Flow  
- TEScalib: Targetless Extrinsic Self-Calibration of LiDAR and Stereo Camera for Automated Driving Vehicles with Uncertainty Analysis  
- Extrinsic Calibration of a 2D Laser Rangefinder and a Depth-Camera Using an Orthogonal Trihedron  
- Continuous Calibration and Narrow Compensation Algorithm to Estimate a Joint Axis under the Various Conditions with Unit Sensor  
- Efficient Extrinsic Calibration of Multi-Sensor 3D LiDAR Systems for Autonomous Vehicles Using Static Objects Information  
- Continuous Self-Localization on Aerial Images Using Visual and Lidar Sensors  
- H-VLO: Hybrid LiDAR-Camera Fusion for Self-Supervised Odometry  
- FAST-LIVO: Fast and Tightly-Coupled Sparse-Direct LiDAR-Inertial-Visual Odometry  
- Online Extrinsic Correction of Multi-Camera Systems by Low-Dimensional Parameterization of Physical Deformation  
- Rail Vehicle Localization and Mapping with LiDAR-Vision-Inertial-GNSS Fusion  
- CROON: Automatic Multi-LiDAR Calibration and Refinement Method in Road Scene  
- Extrinsic Camera Calibration from a Moving Person  
- High Precision and Robust Camera Calibration under Learning-Based Distortion Correction and Feature Detection  
- Online Kinematic Calibration for Legged Robots  
- Vision-Assisted Localization and Terrain Reconstruction with Quadruped Robots  


[[top](#iros-2022-slam-paper-list)]  

## Inertial odometry / INS  
- Kinematics-Inertial Fusion for Localization of a 4-Cable Underactuated Suspended Robot Considering Cable Sag  
- Robust Slip-Aware Fusion for Mobile Robots State Estimation  
- Maintaining Robot Localizability with Bayesian Cramer-Rao Lower Bounds  
- Learnable Spatio-Temporal Map Embeddings for Deep Inertial Localization  
- Learning-Enhanced Adaptive Robust GNSS Navigation in Challenging Environments  
- IMU Dead-Reckoning Localization with RNN-IEKF Algorithm

[[top](#iros-2022-slam-paper-list)]  

## Multi Robot SLAM / Localization
- Multi-Agent Relative Pose Estimation with UWB and Constrained Communications  
- Optimal Localizability Criterion for Positioning with Distance-Deteriorated Relative Measurements  
- Data-Efficient Collaborative Decentralized Thermal-Inertial Odometry  
- HD-CCSOM: Hierarchical and Dense Collaborative Continuous Semantic Occupancy Mapping through Label Diffusion  
- Optimal Multi-robot Formations for Relative Pose Estimation Using Range Measurements  
- Distributed Riemannian Optimization with Lazy Communication for Collaborative Geometric Estimation  
- Certifiably Optimal Mutual Localization with Anonymous Bearing Measurements  
- Tether-Based Localization for Cooperative Ground and Aerial Vehicles  
- Loop Closure Prioritization for Efficient and Scalable Multi-Robot SLAM  
- LAMP 2.0: A Robust Multi-Robot SLAM System for Operation in Challenging Large-Scale Underground Environments  
- MR-TopoMap: Multi-Robot Exploration Based on Topological Map in Communication Restricted Environment  
- Decentralized Learning with Limited Communications for Multi-Robot Coverage of Unknown Spatial Fields  
- Efficient Range-Constrained Manifold Optimization with Application to Cooperative Navigation  


[[top](#iros-2022-slam-paper-list)]  

## Etc
- GaSLAM: An Algorithm for Simultaneous Gas Source Localization and Gas Distribution Mapping in 3D  
- Online Target Localization using Adaptive Belief Propagation in the HMM Framework  
- IMU Preintegration for 2D SLAM Problems Using Lie Groups  
- Unmanned Aircraft System-Based Radiological Mapping of Buildings  
- Robot-aided Microbial Density Estimation and Mapping  
- Adaptive-Resolution Field Mapping Using Gaussian Process Fusion With Integral Kernels  
- Generalized Laplace Particle Filter on Lie Groups Applied to Ambiguous Doppler Navigation  
- LayoutSLAM: Object Layout based Simultaneous Localization and Mapping for Reducing Object Map Distortion  
- Hierarchical Road Topology Learning for Urban Map-less Driving  
- Estimating Odometry Scale and UWB Anchor Location Based on Semidefinite Programming Optimization  
- Group-K Consistent Measurement Set Maximization for Robust Outlier Detection  
- MapLite 2.0: Online HD Map Inference Using a Prior SD Map  
- Maintaining Robot Localizability with Bayesian Cramer-Rao Lower Bounds  
- InCOpt: Incremental Constrained Optimization Using the Bayes Tree  
- Spectral Measurement Sparsification for Pose-Graph SLAM  
- Mapping of Spatiotemporal Scalar Fields by Mobile Robots using Gaussian Process Regression  
- Active SLAM in 3D deformable environments  
- Anchor Selection for SLAM Based on Graph Topology and Submodular Optimization  
- Optimization Strategies for Bayesian Source Localization Algorithms  
- A Spanning Tree-Based Multi-Resolution Approach for Pose-Graph Optimization  
- Nested Sampling for Non-Gaussian Inference in SLAM Factor Graphs


[[top](#iros-2022-slam-paper-list)]  
