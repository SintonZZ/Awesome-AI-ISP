# Awesome-AI-ISP
A list of awesome AI-ISP works. 
## 📜 Content
- [Image denoise](#image-denoise)
- [Video denoise](#video-denoise)
- [HDR](#hdr)
- [Image enhancement](#image-enhancement)
- [Resources](#Resources)
  
## Image denoise
- Architecture
  - (**SID**) Learning to See in the Dark. [[CVPR 2018]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Learning_to_See_CVPR_2018_paper.pdf) [[code]](https://github.com/cchen156/Learning-to-See-in-the-Dark)
  - (**PMRID**) Practical Deep Raw Image Denoising on Mobile Devices. [[ECCV 2020]](https://link.springer.com/chapter/10.1007/978-3-030-58539-6_1) [[code]](https://github.com/MegEngine/PMRID)
  - (**NBNet**) NBNet: Noise Basis Learning for Image Denoising with Subspace Projection. [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Cheng_NBNet_Noise_Basis_Learning_for_Image_Denoising_With_Subspace_Projection_CVPR_2021_paper.pdf) [[code]](https://github.com/MegEngine/NBNet)
  - (**NAFNet**) Simple Baselines for Image Restoration. [[ECCV 2022]](https://arxiv.org/pdf/2204.04676.pdf) [[code]](https://github.com/megvii-research/NAFNet)
  - (**CGNet**) CascadedGaze: Efficiency in Global Context Extraction for Image Restoration. [[TMLR 2024]](https://arxiv.org/abs/2401.15235) [[code]](https://github.com/Ascend-Research/CascadedGaze)
- Noise Modeling
  - (**ELD**) Physics-based Noise Modeling for Extreme Low-light Photography. [[TPAMI 2021]](https://arxiv.org/pdf/2108.02158.pdf) [[code]](https://github.com/Vandermode/ELD)
  - (**SFRN**) Rethinking Noise Synthesis and Modeling in Raw Denoising. [[ICCV 2021]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_Rethinking_Noise_Synthesis_and_Modeling_in_Raw_Denoising_ICCV_2021_paper.pdf)  [[code]](https://github.com/zhangyi-3/Noise-Synthesis)
  - (**PNGAN**) Learning to Generate Realistic Noisy Images via Pixel-level Noise-aware Adversarial Training. [[NeurIPS 2021]](https://arxiv.org/abs/2204.02844)  [[code]](https://github.com/caiyuanhao1998/PNGAN)
  - (**PMN**) Learnability Enhancement for Low-Light Raw Image Denoising: A Data Perspective. [[TPAMI 2023]](https://ieeexplore.ieee.org/document/10207751) [[code]](https://github.com/megvii-research/PMN/tree/TPAMI) [[ZhiHu]](https://zhuanlan.zhihu.com/p/651674070) 
  - (**LLD**) Physics-Guided ISO-Dependent Sensor Noise Modeling for Extreme Low-Light Photography. [[CVPR 2023]](https://openaccess.thecvf.com/content/CVPR2023/papers/Cao_Physics-Guided_ISO-Dependent_Sensor_Noise_Modeling_for_Extreme_Low-Light_Photography_CVPR_2023_paper.pdf)
  - (**LED**) Lighting Every Darkness in Two Pairs: A Calibration-Free Pipeline for RAW Denoising. [[ICCV 2023]](https://arxiv.org/abs/2308.03448) [[ZhiHu]](https://zhuanlan.zhihu.com/p/648242095) [[code]](https://github.com/Srameo/LED)
  - (**PNNP**) Physics-guided Noise Neural Proxy for Low-light Raw Image Denoising. [[arXiv]](https://arxiv.org/abs/2308.03448)[[code]](https://github.com/fenghansen/PNNP)
  - (**LRD**) Towards General Low-Light Raw Noise Synthesis and Modeling. [[ICCV 2023]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_Towards_General_Low-Light_Raw_Noise_Synthesis_and_Modeling_ICCV_2023_paper.pdf) [[code]](https://github.com/fengzhang427/LRD)
  - (**S2R**) From Synthetic to Real: A Calibration-free Pipeline for Few-shot Raw Image. [[CVPR 2024]](https://openaccess.thecvf.com/content/CVPR2024W/MIPI/papers/Li_From_Synthetic_to_Real_A_Calibration-free_Pipeline_for_Few-shot_Raw_CVPRW_2024_paper.pdf)
- Dateset-related
  - Unprocessing Images for Learned Raw Denoising. [[CVPR 2019]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Brooks_Unprocessing_Images_for_Learned_Raw_Denoising_CVPR_2019_paper.pdf) [[code]](https://github.com/timothybrooks/unprocessing)
  - Learning Raw Image Denoising with Bayer Pattern Unification and Bayer Preserving Augmentation. [[CVPR 2019]](https://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Liu_Learning_Raw_Image_Denoising_With_Bayer_Pattern_Unification_and_Bayer_CVPRW_2019_paper.pdf) [[code]](https://github.com/Jiaming-Liu/BayerUnifyAug)
  - CycleISP: Real Image Restoration via Improved Data Synthesis. [[CVPR2020 Oral]](https://arxiv.org/abs/2003.07761) [[code]](https://github.com/swz30/CycleISP)
  - Improving Image Restoration by Revisiting Global Information Aggregation. [[ECCV 2022]](https://link.springer.com/chapter/10.1007/978-3-031-20071-7_4) [[code]](https://github.com/megvii-research/TLC)
  - Day-to-Night Image Synthesis for Training Nighttime Neural ISPs. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Punnappurath_Day-to-Night_Image_Synthesis_for_Training_Nighttime_Neural_ISPs_CVPR_2022_paper.pdf) [[code]](https://github.com/SamsungLabs/day-to-night)
  
## Video denoise
- **EDVR**: Video Restoration with Enhanced Deformable Convolutional Networks. [[CVPR 2019]](https://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Wang_EDVR_Video_Restoration_With_Enhanced_Deformable_Convolutional_Networks_CVPRW_2019_paper.pdf) [[code]](https://github.com/xinntao/EDVR)
- **FastDVDnet**: Towards Real-Time Deep Video Denoising Without Flow Estimation. [[CVPR 2020]](https://openaccess.thecvf.com/content_CVPR_2020/html/Tassano_FastDVDnet_Towards_Real-Time_Deep_Video_Denoising_Without_Flow_Estimation_CVPR_2020_paper.html) [[code]](https://github.com/m-tassano/fastdvdnet)
- (**RViDeNet**) Supervised Raw Video Denoising with a **Benchmark Dataset** on Dynamic Scenes. [[CVPR 2020]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yue_Supervised_Raw_Video_Denoising_With_a_Benchmark_Dataset_on_Dynamic_CVPR_2020_paper.pdf) [[code]](https://github.com/cao-cong/RViDeNet)
- (**EMVD**) Efficient multi-stage video denoising with recurrent spatio-temporal fusion. [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Maggioni_Efficient_Multi-Stage_Video_Denoising_With_Recurrent_Spatio-Temporal_Fusion_CVPR_2021_paper.pdf) [[code]](https://github.com/Baymax-chen/EMVD)
- (**Improved EMVD**) Improved EMVD for RAW video denoising. [[paper]](https://gretsi.fr/data/colloque/pdf/2022_zheng966.pdf)
- Dancing under the stars: video denoising in starlight. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Monakhova_Dancing_Under_the_Stars_Video_Denoising_in_Starlight_CVPR_2022_paper.pdf) [[code]](https://github.com/monakhova/starlight_denoising/tree/main)
- (**ShiftNet**)A Simple Baseline for Video Restoration with Grouped Spatial-temporal Shift. [[CVPR 2023]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_A_Simple_Baseline_for_Video_Restoration_With_Grouped_Spatial-Temporal_Shift_CVPR_2023_paper.pdf) [[code]](https://github.com/dasongli1/Shift-Net)
- (**BRVE**)Binarized Low-light Raw Video Enhancement. [[CVPR 2024]](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Binarized_Low-light_Raw_Video_Enhancement_CVPR_2024_paper.pdf) [[code]](https://github.com/zhanggengchen/BRVE)
- 
## HDR
- Deep high dynamic range imaging of dynamic scenes. [[SIGGRAPH 2017]](https://people.engr.tamu.edu/nimak/Data/SIGGRAPH17_HDR_LoRes.pdf) [[code]](https://github.com/TH3CHARLie/deep-high-dynamic-range)
- Attention-guided network for ghost-free high dynamic range imaging. [[CVPR 2019]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yan_Attention-Guided_Network_for_Ghost-Free_High_Dynamic_Range_Imaging_CVPR_2019_paper.pdf) [[code]](https://github.com/qingsenyangit/AHDRNet)
- ADNet: Attention-guided Deformable Convolutional Network for High Dynamic Range Imaging. [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Liu_ADNet_Attention-Guided_Deformable_Convolutional_Network_for_High_Dynamic_Range_Imaging_CVPRW_2021_paper.pdf) [[code]](https://github.com/liuzhen03/ADNet)

## Tone Mapping
- [Pyramid Reconstruction Network for Tone Mapping: Pyramid Reconstruction Network for Tone Mapping][[TPAMI 2025]](High-resolution Photo Enhancement in Real-time: A Laplacian Pyramid Network)[[code]](https://github.com/fengzhang427/LLF-LUT)

## Image Enhancement
- Low-Light image enhancement
  - Learning to Enhance Low-Light Image via Zero-Reference Deep Curve Estimation. [[TPAMI 2021]](https://arxiv.org/pdf/2103.00860.pdf) [[code]](https://github.com/Li-Chongyi/Zero-DCE)
  - Toward Fast, Flexible, and Robust Low-Light Image Enhancement. [[CVPR 2022(Oral)]](https://openaccess.thecvf.com/content/CVPR2022/html/Ma_Toward_Fast_Flexible_and_Robust_Low-Light_Image_Enhancement_CVPR_2022_paper.html) [[code]](https://github.com/vis-opt-group/SCI)
  - Retinexformer: One-stage Retinex-based Transformer for Low-light Image Enhancement. [[ICCV 2023]](https://openaccess.thecvf.com/content/ICCV2023/papers/Cai_Retinexformer_One-stage_Retinex-based_Transformer_for_Low-light_Image_Enhancement_ICCV_2023_paper.pdf) [[code]](https://github.com/caiyuanhao1998/Retinexformer)
  - HVI: A New Color Space for Low-light Image Enhancement. [[CVPR 2025]](https://arxiv.org/abs/2502.20272) [[code]](https://github.com/Fediory/HVI-CIDNet)
- Contrast enhancement
  - Learning Tone Curves for Local Image Enhancement. [[IEEE ACCESS 2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9784427) [[code]](https://github.com/SamsungLabs/ltmnet)

## Resources
- NTIRE (New Trends in Image Restoration and Enhancement)
- MIPI (Mobile Intelligent Photography and Imaging)
- MAI (Mobile AI)
- AIM (Advances in Image Manipulation)
- [Infinite-ISP](https://github.com/10x-Engineers/Infinite-ISP?tab=readme-ov-file)
- [openISP](https://github.com/cruxopen/openISP)
- [fast-openISP](https://github.com/QiuJueqin/fast-openISP)
- [Awesome-Low-Level-Vision-Research-Groups](https://github.com/Kobaayyy/Awesome-Low-Level-Vision-Research-Groups)

## Researchers
- [Ying Fu](https://ying-fu.github.io/) 
- [Shuaicheng LIU](http://www.liushuaicheng.org/)
- [Chao Dong](https://xpixel.group/index.html)
- [Hansen Feng](https://fenghansen.github.io/)
