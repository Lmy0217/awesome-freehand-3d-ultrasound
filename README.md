# Awesome - Freehand 3D Ultrasound

> A curated list of related papers and resources for freehand 3d ultrasound.
>
>**Note that:**
>- **This list is not exhaustive. Your contributions are welcome!**
>- **Lists are organized by year and alphabetically for fairness.**

Freehand three-dimensional (3D) ultrasound is a technique for acquiring 3D ultrasound data by measuring the trajectory of a conventional 2D ultrasound probe as a clinician moves it across an object of interest.

## Overview
- [Challenge](#Challenge)
- [Review](#Review)
- [Reconstruction](#Reconstruction)
- [Protocol](#Protocol)
- [System](#System)
- [Guidance](#Guidance)
- [Interpolation](#Interpolation)
- [Large-FOV](#Large-FOV)

## Challenge
- **Trackerless 3D Freehand Ultrasound Reconstruction (TUS-REC) Challenge** \
    [MICCAI, 2024] [[Website](https://github-pages.ucl.ac.uk/tus-rec-challenge/TUS-REC2024/)] [[Dataset](https://github-pages.ucl.ac.uk/tus-rec-challenge/TUS-REC2024/data.html)] [[Paper](https://doi.org/10.48550/arXiv.2506.21765)] \
    [MICCAI, 2025] [[Website](https://github-pages.ucl.ac.uk/tus-rec-challenge)] [[Dataset](https://github-pages.ucl.ac.uk/tus-rec-challenge/data.html)]
    

## Review
- **A review of calibration techniques for freehand 3-D ultrasound systems** \
    [Ultrasound in Medicine & Biology, 2005] [[Paper](https://doi.org/10.1016/j.ultrasmedbio.2004.11.015)]
- **Freehand 3D Ultrasound Reconstruction Algorithms—A Review** \
    [Ultrasound in Medicine & Biology, 2007] [[Paper](https://doi.org/10.1016/j.ultrasmedbio.2007.02.015)]
- **Freehand 3D Ultrasound Calibration: A Review** \
    [Advanced Imaging in Biology and Medicine, 2009] [[Paper](https://doi.org/10.1007/978-3-540-68993-5_3)]
- **Freehand 3-D Ultrasound Imaging: A Systematic Review** \
    [Ultrasound in Medicine & Biology, 2017] [[Paper](https://doi.org/10.1016/j.ultrasmedbio.2017.06.009)]
- **A Survey on 3D Ultrasound Reconstruction Techniques** \
    [Artificial Intelligence - Applications in Medicine and Biology, 2019] [[Paper](https://doi.org/10.5772/intechopen.81628)]
- **The big bang of deep learning in ultrasound-guided surgery: a review** \
    [IEEE TUFFC, 2023] [[Paper](https://doi.org/10.1109/TUFFC.2023.3255843)]
- **Trackerless 3D Freehand Ultrasound Reconstruction: A Review** \
    [Applied Sciences, 2024] [[Paper](https://doi.org/10.3390/app14177991)]

## Reconstruction
- **Sensorless freehand 3-D ultrasound using regression of the echo intensity** \
    [Ultrasound in Medicine & Biology, 2003] [[Paper](https://doi.org/10.1016/S0301-5629(02)00703-2)]
- **Sensorless freehand 3D ultrasound in real tissue: Speckle decorrelation without fully developed speckle** \
    [MedIA, 2006] [[Paper](https://doi.org/10.1016/j.media.2005.08.001)]
- **Rotational motion in sensorless freehand three-dimensional ultrasound** \
    [Ultrasonics, 2008] [[Paper](https://doi.org/10.1016/j.ultras.2008.01.008)]
- **Learning for Graph-Based Sensorless Freehand 3D Ultrasound** \
    [MLMI, 2016] [[Paper](https://doi.org/10.1007/978-3-319-47157-0_25)]
- **Deep Learning for Sensorless 3D Freehand Ultrasound Imaging** \
    [MICCAI, 2017] [[Paper](https://doi.org/10.1007/978-3-319-66185-8_71)]
- **3D freehand ultrasound without external tracking using deep learning** \
    [MedIA, 2018] [[Paper](https://doi.org/10.1016/j.media.2018.06.003)]
- **Total Variation Regularization of Pose Signals With an Application to 3D Freehand Ultrasound** \
    [IEEE TMI, 2019] [[Paper](https://doi.org/10.1109/TMI.2019.2898480)] [[Code](https://github.com/IFL-CAMP/pose_regularization)]
- **Sensorless Freehand 3D Ultrasound Reconstruction via Deep Contextual Learning** \
    [MICCAI, 2020] [[Paper](https://doi.org/10.1007/978-3-030-59716-0_44)] [[Code](https://github.com/DIAL-RPI/FreehandUSRecon)]
- **Three-Dimensional Thyroid Assessment from Untracked 2D Ultrasound Clips** \
    [MICCAI, 2020] [[Paper](https://doi.org/10.1007/978-3-030-59716-0_49)]
- **Localizing 2D Ultrasound Probe from Ultrasound Image Sequences Using Deep Learning for Volume Reconstruction** \
    [Medical Ultrasound, and Preterm, Perinatal and Paediatric Image Analysis, 2020] [[Paper](https://doi.org/10.1007/978-3-030-60334-2_10)]
- **ImplicitVol: Sensorless 3D ultrasound reconstruction with deep implicit representation** \
    [arXiv, 2021] [[Paper](https://doi.org/10.48550/arXiv.2109.12108)] [[Code](https://github.com/pakheiyeung/ImplicitVol)]
- **Self Context and Shape Prior for Sensorless Freehand 3D Ultrasound Reconstruction** \
    [MICCAI, 2021] [[Paper](https://doi.org/10.1007/978-3-030-87231-1_20)]
- **Transducer Adaptive Ultrasound Volume Reconstruction** \
    [IEEE ISBI, 2021] [[Paper](https://doi.org/10.1109/ISBI48211.2021.9433756)]
- **Deep Motion Network for Freehand 3D Ultrasound Reconstruction** \
    [MICCAI, 2022] [[Paper](https://doi.org/10.1007/978-3-031-16440-8_28)] [[Code](https://github.com/Lmy0217/MoNet)]
- **Ultrasound Volume Reconstruction From Freehand Scans Without Tracking** \
    [IEEE TBME, 2022] [[Paper](https://doi.org/10.1109/TBME.2022.3206596)]
- **Spatial Position Estimation Method for 3D Ultrasound Reconstruction Based on Hybrid Transfomers** \
    [IEEE ISBI, 2022] [[Paper](https://doi.org/10.1109/ISBI52829.2022.9761499)]
- **Stretched reconstruction based on 2D freehand ultrasound for peripheral artery imaging** \
    [IJCARS, 2022] [[Paper](https://doi.org/10.1007/s11548-022-02636-w)]
- **RecON: Online learning for sensorless freehand 3D ultrasound reconstruction** \
    [MedIA, 2023] [[Paper](https://doi.org/10.1016/j.media.2023.102810)] [[Code](https://github.com/Lmy0217/RecON)]
- **Multi-IMU with Online Self-consistency for Freehand 3D Ultrasound Reconstruction** \
    [MICCAI, 2023] [[Paper](https://doi.org/10.1007/978-3-031-43907-0_33)] [[Code](https://github.com/Lmy0217/OSCNet)]
- **Trackerless Volume Reconstruction from Intraoperative Ultrasound Images** \
    [MICCAI, 2023] [[Paper](https://doi.org/10.1007/978-3-031-43999-5_29)] [[Code](https://github.com/Sidaty1/IVUS_Trakerless_Volume_Reconstruction)]
- **Trackerless Freehand Ultrasound with Sequence Modelling and Auxiliary Transformation Over Past and Future Frames** \
    [IEEE ISBI, 2023] [[Paper](https://doi.org/10.1109/ISBI53787.2023.10230773)]
- **Sensorless End-to-End Freehand Ultrasound with Physics Inspired Network** \
    [IEEE IUS, 2023] [[Paper](https://doi.org/10.1109/IUS51837.2023.10307112)]
- **A Freehand 3D Ultrasound Reconstruction Method Based on Deep Learning** \
    [Electronics, 2023] [[Paper](https://doi.org/10.3390/electronics12071527)]
- **Sensorless volumetric reconstruction of fetal brain freehand ultrasound scans with deep implicit representation** \
    [MedIA, 2024] [[Paper](https://doi.org/10.1016/j.media.2024.103147)]
- **Neural implicit surface reconstruction of freehand 3D ultrasound volume with geometric constraints** \
    [MedIA, 2024] [[Paper](https://doi.org/10.1016/j.media.2024.103305)] [[Code](https://github.com/chenhbo/FUNSR)]
- **Fine-grained Context and Multi-modal Alignment for Freehand 3D Ultrasound Reconstruction** \
    [MICCAI, 2024] [[Paper](https://doi.org/10.1007/978-3-031-72104-5_33)] [[Code](https://github.com/Lmy0217/FiMA)]
- **Nonrigid Reconstruction of Freehand Ultrasound without a Tracker** \
    [MICCAI, 2024] [[Paper](https://doi.org/10.1007/978-3-031-72083-3_64)] [[Code](https://github.com/QiLi111/NR-Rec-FUS)]
- **Advancing Sensorless Freehand 3D Ultrasound Reconstruction with a Novel Coupling Pad** \
    [MICCAI, 2024] [[Paper](https://doi.org/10.1007/978-3-031-72083-3_52)]
- **RoCoSDF: Row-Column Scanned Neural Signed Distance Fields for Freehand 3D Ultrasound Imaging Shape Reconstruction** \
    [MICCAI, 2024] [[Paper](https://doi.org/10.1007/978-3-031-72083-3_67)] [[Code](https://github.com/chenhbo/RoCoSDF)]
- **Long-term Dependency for 3D Reconstruction of Freehand Ultrasound Without External Tracker** \
    [IEEE TBME, 2024] [[Paper](https://doi.org/10.1109/tbme.2023.3325551)] [[Code](https://github.com/ucl-candi/freehand)]
- **Sensorless End-to-End Freehand 3-D Ultrasound Reconstruction With Physics-Guided Deep Learning** \
    [IEEE TUFFC, 2024] [[Paper](https://doi.org/10.1109/TUFFC.2024.3465214)] [[Code](https://github.com/Alphafrey946/PLPPI)]
- **Pitfalls with Neural Radiance Fields for 3D Freehand Ultrasound Reconstruction** \
    [IEEE EMBC, 2024] [[Paper](https://doi.org/10.1109/EMBC53108.2024.10781966)]
- **Continuous Bernoulli Distribution for More Realistic Ultrasound Reconstruction with NeRF** \
    [IEEE UFFC-JS, 2024] [[Paper](https://doi.org/10.1109/UFFC-JS60046.2024.10793769)]
- **Enhancing Free-hand 3D Photoacoustic and Ultrasound Reconstruction using Deep Learning** \
    [IEEE TMI, 2025] [[Paper](https://doi.org/10.1109/TMI.2025.3579454)] [[Code](https://github.com/guhong3648/MoGLo)]
- **MoNetV2: Enhanced Motion Network for Freehand 3-D Ultrasound Reconstruction** \
    [IEEE TNNLS, 2025] [[Paper](https://doi.org/10.1109/TNNLS.2025.3573210)] [[Code](https://github.com/Lmy0217/MoNetV2)]
- **IMU-Assisted Manual 3D-Ultrasound Imaging Using Motion-Constrained Swept-Fan Scans** \
    [Ultrasonic Imaging, 2025] [[Paper](https://doi.org/10.1177/01617346241242718)]
- **3d freehand ultrasound reconstruction by reference-based point cloud registration** \
    [IJCARS, 2025] [[Paper](https://doi.org/10.1007/s11548-024-03280-2)]
- **DualTrack: Sensorless 3D Ultrasound Needs Local and Global Context** \
    [MICCAI ASMUS, 2025] [[Paper](https://arxiv.org/abs/2509.09530)] [[Code](https://github.com/ImFusionGmbH/DualTrack)]

## Protocol
- **Privileged Anatomical and Protocol Discrimination in Trackerless 3D Ultrasound Reconstruction** \
    [Simplifying Medical Ultrasound, 2023] [[Paper](https://doi.org/10.1007/978-3-031-44521-7_14)]

## System
- **A Probe-Camera System for 3D Ultrasound Image Reconstruction** \
    [Imaging for Patient-Customized Simulations and Systems for Point-of-Care Ultrasound, 2017] [[Paper](https://doi.org/10.1007/978-3-319-67552-7_16)]

## Guidance
- **Automatic Probe Movement Guidance for Freehand Obstetric Ultrasound** \
    [MICCAI, 2020] [[Paper](https://doi.org/10.1007/978-3-030-59716-0_56)]
- **Population-based 3D respiratory motion modelling from convolutional autoencoders for 2D ultrasound-guided radiotherapy** \
    [MedIA, 2021] [[Paper](https://doi.org/10.1016/j.media.2021.102260)]
- **Visual-Assisted Probe Movement Guidance for Obstetric Ultrasound Scanning Using Landmark Retrieval** \
    [MICCAI, 2021] [[Paper](https://doi.org/10.1007/978-3-030-87237-3_64)]
- **Multimodal-GuideNet: Gaze-Probe Bidirectional Guidance in Obstetric Ultrasound Scanning** \
    [MICCAI, 2022] [[Paper](https://doi.org/10.1007/978-3-031-16449-1_10)]
- **Automatic Image Guidance for Assessment of Placenta Location in Ultrasound Video Sweeps** \
    [Ultrasound in Medicine & Biology, 2023] [[Paper](https://doi.org/10.1016/j.ultrasmedbio.2022.08.006)]
- **Gaze-probe joint guidance with multi-task learning in obstetric ultrasound scanning** \
    [MedIA, 2023] [[Paper](https://doi.org/10.1016/j.media.2023.102981)]
- **Pose-GuideNet: Automatic Scanning Guidance for Fetal Head Ultrasound from Pose Estimation** \
    [MICCAI, 2024] [[Paper](https://doi.org/10.1007/978-3-031-72083-3_65)]

## Interpolation
- **Hole-filling based on content loss indexed 3D partial convolution network for freehand ultrasound reconstruction** \
    [Computer Methods and Programs in Biomedicine, 2021] [[Paper](https://doi.org/10.1016/j.cmpb.2021.106421)]

## Large-FOV
- **PURE: Panoramic Ultrasound Reconstruction by Seamless Stitching of Volumes** \
    [SASHIMI, 2016] [[Paper](https://doi.org/10.1007/978-3-319-46630-9_8)]
