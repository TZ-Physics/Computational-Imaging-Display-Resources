# Computational Imaging & Display Resources

## Computational Imaging

### Lens Design

**Deep learning-enabled framework for automatic lens design starting point generation.**<br>
*G Côté, JF Lalonde, S Thibault.*<br>
Optics express, 2021.
[[Paper](https://opg.optica.org/oe/viewmedia.cfm?uri=oe-29-3-3841&html=true)]

**Comparison of methods for end-to-end co-optimization of optical systems and image processing with commercial lens design software.**<br>
*A Fontbonne, H Sauer, F Goudail.*<br>
Optics Express, 2022.
[[Paper](https://opg.optica.org/viewmedia.cfm?uri=oe-30-8-13556&seq=0&html=true)]

**Inferring the solution space of microscope objective lenses using deep learning.**<br>
*G Côté, Y Zhang, C Menke, JF Lalonde, S Thibault.*<br>
Optics Express, 2022.
[[Paper](https://opg.optica.org/viewmedia.cfm?uri=oe-30-5-6531&seq=0&html=true)]

### DiffOptics

**Differentiable compound optics and processing pipeline optimization for end-to-end camera design.**<br>
*E Tseng, A Mosleh, F Mannan, K St-Arnaud, A Sharma, Y Peng, A Braun, D Nowrouzezahrai, et al.*<br>
ACM Transactions on Graphics (TOG), 2021.
[[Paper](https://dl.acm.org/doi/abs/10.1145/3446791)]

**do: A differentiable engine for deep lens design of computational imaging systems.**<br>
*C Wang, N Chen, W Heidrich.*<br>
IEEE Transactions on Computational Imaging, 2022.
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9919421)]
[[Github](https://github.com/vccimaging/diffOptics)]

**Pixelrnn: in-pixel recurrent neural networks for end-to-end-optimized perception with neural sensors.**<br>
*HM So, L Bose, P Dudek, G Wetzstein.*<br>
CVPR, 2024.
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/So_PixelRNN_In-pixel_Recurrent_Neural_Networks_for_End-to-end-optimized_Perception_with_Neural_CVPR_2024_paper.pdf)]

### TrustedRobustImaging

|Date|Task|Sensor|Title|Paper|Github|DataSets|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2024| Low-light |Camera| Unsupervised Illumination Adaptation for Low-Light Vision.|[[TPAMI]](https://ieeexplore.ieee.org/abstract/document/10480646) |-|-|
|2024| Adverse Weather |Camera| AllWeather-Net: Unified Image Enhancement for Autonomous Driving Under Adverse Weather and Low-Light Conditions.|[[ArXiv]](https://arxiv.org/pdf/2409.02045) |-|-|
|2022| Rain |Camera| Rain rendering for evaluating and improving robustness to bad weather.|[[IJCV]](https://link.springer.com/article/10.1007/s11263-020-01366-3) |-|-|
|2022| Snow |LiDAR| Lidar snowfall simulation for robust 3d object detection.|[[CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Hahner_LiDAR_Snowfall_Simulation_for_Robust_3D_Object_Detection_CVPR_2022_paper.pdf) |[[Github]](https://github.com/SysCV/LiDAR_snow_sim)|-|
|2020| Fog |Mulmimodal| Seeing through fog without seeing fog: Deep multimodal sensor fusion in unseen adverse weather.|[[CVPR]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Bijelic_Seeing_Through_Fog_Without_Seeing_Fog_Deep_Multimodal_Sensor_Fusion_CVPR_2020_paper.pdf) |-|-|
|2021| Fog |LiDAR| Fog simulation on real LiDAR point clouds for 3D object detection in adverse weather.|[[ICCV]](https://openaccess.thecvf.com/content/ICCV2021/papers/Hahner_Fog_Simulation_on_Real_LiDAR_Point_Clouds_for_3D_Object_ICCV_2021_paper.pdf) |-|-|
|2024| Fog |Camera| SynFog: A Photo-realistic Synthetic Fog Dataset based on End-to-end Imaging Simulation for Advancing Real-World Defogging in Autonomous Driving.|[[CVPR]](https://openaccess.thecvf.com/content/CVPR2024/papers/Xie_SynFog_A_Photo-realistic_Synthetic_Fog_Dataset_based_on_End-to-end_Imaging_CVPR_2024_paper.pdf) |-|-|
|2024| HDR |Camera| Neural Exposure Fusion for High-Dynamic Range Object Detection.|[[CVPR]](https://openaccess.thecvf.com/content/CVPR2024/papers/Onzon_Neural_Exposure_Fusion_for_High-Dynamic_Range_Object_Detection_CVPR_2024_paper.pdf) |-|-|

### UltrafastHDImaging

|Date|Task|Title|Paper|HomePage|Github|DataSets|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2022| TOF | All-photon polarimetric time-of-flight imaging.|[[CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Baek_All-Photon_Polarimetric_Time-of-Flight_Imaging_CVPR_2022_paper.pdf) |-|-|-|
|2022| TOF | Fisher information guidance for learned time-of-flight imaging.|[[CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Fisher_Information_Guidance_for_Learned_Time-of-Flight_Imaging_CVPR_2022_paper.pdf) |-|-|-|
|2023| TOF | Centimeter-wave free-space neural time-of-flight imaging.|[[TOG]](https://dl.acm.org/doi/pdf/10.1145/3522671) |-|-|-|
|2022| LiDAR | Pushing Point Cloud Compression to the Edge.|[[MICRO]](https://par.nsf.gov/servlets/purl/10440765) |-|-|-|
|2023| LiDAR | Torchsparse++: Efficient training and inference framework for sparse convolution on gpus.|[[MICRO]](https://dl.acm.org/doi/pdf/10.1145/3613424.3614303) |-|[[Github]](https://github.com/mit-han-lab/torchsparse)|-|
|2024| LiDAR | Towards an ultrafast 3D imaging scanning LiDAR system: a review.|[[PRJ]](https://opg.optica.org/viewmedia.cfm?uri=prj-12-8-1709&seq=0&html=true) |-|-|-|
|2018| Stereo | Activestereonet: End-to-end self-supervised learning for active stereo systems.|[[ECCV]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yinda_Zhang_Active_Stereo_Net_ECCV_2018_paper.pdf) |-|-|-|
|2021| Stereo | Polka lines: Learning structured illumination and reconstruction for active stereo.|[[CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Baek_Polka_Lines_Learning_Structured_Illumination_and_Reconstruction_for_Active_Stereo_CVPR_2021_paper.pdf) |-|-|-|
|2024| Stereo | Cross-spectral Gated-RGB Stereo Depth Estimation..|[[CVPR]](https://openaccess.thecvf.com/content/CVPR2024/papers/Brucker_Cross-spectral_Gated-RGB_Stereo_Depth_Estimation_CVPR_2024_paper.pdf) |-|[[Github]](https://light.princeton.edu/publication/gatedrccbstereo/)|-|

### MiniAccurateImaging

|Date|Task|Title|Paper|HomePage|Github|DataSets|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2021| Metalens | Neural nano-optics for high-quality thin lens imaging.|[[NC]](https://www.nature.com/articles/s41467-021-26443-0) |-|[[Code]](https://doi.org/10.5281/zenodo.5637678)|-|
|2023| Metalens | Miniature color camera via flat hybrid meta-optics.|[[SA]](https://www.science.org/doi/full/10.1126/sciadv.adg7297) |-|-|-|
|2024| Metalens | End-to-end optimization of metasurfaces for imaging with compressed sensing.|[[ACSP]](https://arxiv.org/pdf/2201.12348) |-|-|-|

## Biomedical Optics

|Date|Task|Title|Paper|HomePage|Github|DataSets|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2021| Endoscope | Ultra-thin 3D lensless fiber endoscopy using diffractive optical elements and deep neural networks.|[[LAM]](https://www.light-am.com/article/doi/10.37188/lam.2021.030f) |-|-|-|
|2022| Endoscope | Quantitative phase imaging through an ultra-thin lensless fiber endoscope.|[[LSA]](https://www.nature.com/articles/s41377-022-00898-2.pdf) |-|-|-|
|2023| Endoscope | Autonomous intelligent navigation for flexible endoscopy using monocular depth guidance and 3-D shape planning.|[[ICRA]](https://arxiv.org/pdf/2302.13219) |-|-|-|
|2020| Tomography | Three-dimensional imaging through scattering media based on confocal diffuse tomography.|[[NC]](https://www.nature.com/articles/s41467-020-18346-3.pdf) |-|-|-|
|2021| Tomography | X-ray computed tomography.|[[NR]](https://www.nature.com/articles/s43586-021-00015-4) |-|-|-|
|2021| Tomography | High resolution, deep imaging using confocal time-of-flight diffuse optical tomography.|[[TPAMI]](https://ieeexplore.ieee.org/abstract/document/9415130/) |-|-|-|
|2018| Microscopy | Content-aware image restoration: pushing the limits of fluorescence microscopy.|[[Nature]](https://www.biorxiv.org/content/biorxiv/early/2018/07/03/236463.full.pdf) |-|-|-|
|2018| Microscopy | Deep-STORM: super-resolution single-molecule microscopy by deep learning.|[[Optica]](https://opg.optica.org/optica/fulltext.cfm?uri=optica-5-4-458&id=385495) |-|-|-|
|2021| Microscopy | An adaptive optics module for deep tissue multiphoton imaging in vivo.|[[NM]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9090585/) |-|-|-|

## Computational Display

### Autostereoscopy

|Date|Task|Title|Paper|HomePage|Github|DataSets|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2020| Holography | Neural holography with camera-in-the-loop training.|[[TOG]](https://drive.google.com/file/u/0/d/1Y_gUeAAolN35I3cG7T-QRXTvXAlw5Let/view?pli=1) |-|-|-|
|2022| Holography | Joint neural phase retrieval and compression for energy-and computation-efficient holography on the edge.|[[TOG]](https://par.nsf.gov/servlets/purl/10465404) |-|[[Github]](https://github.com/HoloCompress/DPRC)|-|
|2022| Holography | Holographic glasses for virtual reality.|[[SIGGRAPH]](https://dl.acm.org/doi/pdf/10.1145/3528233.3530739) |-|-|-|

### XR

|Date|Task|Title|Paper|HomePage|Github|DataSets|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2021| AR | Design and manufacture AR head-mounted displays: A review and outlook.|[[LAM]](Design+and+manufacture+AR+head-mounted+displays_+A+review+and+outlook.pdf) |-|-|-|
|2023| AR | High-efficiency and compact two-dimensional exit pupil expansion design for diffractive waveguide based on polarization volume grating.|[[OE]](https://opg.optica.org/oe/fulltext.cfm?uri=oe-31-4-6601) |-|-|-|
|2023| AR | Extended depth-of-field projector using learned diffractive optics.|[[VR]](https://repository.kaust.edu.sa/server/api/core/bitstreams/9964dbae-4261-43ae-9905-2c3182714e38/content) |-|-|-|
|2022| VR | Multimodality in VR: A survey.|[[CSUR]](https://arxiv.org/pdf/2101.07906) |-|-|-|
|2022| VR | Optical design and pupil swim analysis of a compact, large EPD and immersive VR head mounted display.|[[OE]](https://opg.optica.org/oe/fulltext.cfm?uri=oe-30-5-6584) |-|-|-|
|2024| VR | Context-Aware Head-and-Eye Motion Generation with Diffusion Model.|[[VR]](https://ieeexplore.ieee.org/abstract/document/10494124) |-|-|-|
|2024| Benchmark | Xrbench: An extended reality (xr) machine learning benchmark suite for the metaverse.|[[PMLS]](https://proceedings.mlsys.org/paper_files/paper/2023/file/07b7c2f8a6978e376f9656d69619bfbb-Paper-mlsys2023.pdf) |-|-|-|
