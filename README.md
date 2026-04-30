# Awesome-AI-ISP
A list of awesome AI-ISP works. 
## 📜 Content
- [ISP render](#isp-render)
- [Image denoise](#image-denoise)
- [Video denoise](#video-denoise)
- [HDR](#hdr)
- [TMO](#tmo)
- [AWB](#awb)
- [Demosaicing](#demosaicing)
- [Image retouching](#image-retouching)
- [Low-Light enhancement](#low-light-enhancement)
- [Resources](#resources)

## ISP render
- Learning to See in the Dark. [[CVPR 2018]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Learning_to_See_CVPR_2018_paper.pdf) [[code]](https://github.com/cchen156/Learning-to-See-in-the-Dark)
- Dnf: Decouple and feedback network for seeing in the dark. [[CVPR 2023]](https://openaccess.thecvf.com/content/CVPR2023/papers/Jin_DNF_Decouple_and_Feedback_Network_for_Seeing_in_the_Dark_CVPR_2023_paper.pdf) [[code]](https://github.com/Srameo/DNF)
- Learning to See in the Extremely Dark. [[ICCV 2025]](https://arxiv.org/pdf/2506.21132) [[code]](https://github.com/JianghaiSCU/SIED)
- Modular Neural Image Signal Processing. [[paper]](https://arxiv.org/pdf/2512.08564)
- Learned Lightweight Smartphone ISP with Unpaired Data. [[CVPRW 2025]](https://arxiv.org/pdf/2505.10420) [[code]](https://github.com/AndreiiArhire/Learned-Lightweight-Smartphone-ISP-with-Unpaired-Data)
## Image denoise
- Architecture
  - (**PMRID**) Practical Deep Raw Image Denoising on Mobile Devices. [[ECCV 2020]](https://link.springer.com/chapter/10.1007/978-3-030-58539-6_1) [[code]](https://github.com/MegEngine/PMRID)
  - (**NBNet**) NBNet: Noise Basis Learning for Image Denoising with Subspace Projection. [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Cheng_NBNet_Noise_Basis_Learning_for_Image_Denoising_With_Subspace_Projection_CVPR_2021_paper.pdf) [[code]](https://github.com/MegEngine/NBNet)
  - (**NAFNet**) Simple Baselines for Image Restoration. [[ECCV 2022]](https://arxiv.org/pdf/2204.04676.pdf) [[code]](https://github.com/megvii-research/NAFNet)
  - (**CGNet**) CascadedGaze: Efficiency in Global Context Extraction for Image Restoration. [[TMLR 2024]](https://arxiv.org/abs/2401.15235) [[code]](https://github.com/Ascend-Research/CascadedGaze)
  - (**SplitterNet**) Real-World Mobile Image Denoising Dataset with Efficient Baselines. [[CVPR 2024]](https://openaccess.thecvf.com/content/CVPR2024/papers/Flepp_Real-World_Mobile_Image_Denoising_Dataset_with_Efficient_Baselines_CVPR_2024_paper.pdf) [[code]](https://github.com/rflepp/SplitterNet-Efficient-Mobile-Denoising-Models-CVPR2024)
  - **TinyLUT**: Tiny Look-Up Table for Efficient Image Restoration at the Edge. [[NeurIPS 2024]](http://proceedings.neurips.cc/paper_files/paper/2024/file/9b01c4a7d3fc49875dad3c13848bcd9e-Paper-Conference.pdf) [[code]](https://github.com/Jonas-KD/TinyLUT)
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
  - Noise Modeling in One Hour: Minimizing Preparation Efforts for Self-supervised Low-Light RAW Image Denoising. [[CVPR 2025]](https://arxiv.org/pdf/2505.00045) [[code]](https://github.com/SonyResearch/raw_image_denoising)
- Dateset-related
  - Unprocessing Images for Learned Raw Denoising. [[CVPR 2019]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Brooks_Unprocessing_Images_for_Learned_Raw_Denoising_CVPR_2019_paper.pdf) [[code]](https://github.com/timothybrooks/unprocessing)
  - Learning Raw Image Denoising with Bayer Pattern Unification and Bayer Preserving Augmentation. [[CVPR 2019]](https://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Liu_Learning_Raw_Image_Denoising_With_Bayer_Pattern_Unification_and_Bayer_CVPRW_2019_paper.pdf) [[code]](https://github.com/Jiaming-Liu/BayerUnifyAug)
  - CycleISP: Real Image Restoration via Improved Data Synthesis. [[CVPR2020 Oral]](https://arxiv.org/abs/2003.07761) [[code]](https://github.com/swz30/CycleISP)
  - Improving Image Restoration by Revisiting Global Information Aggregation. [[ECCV 2022]](https://link.springer.com/chapter/10.1007/978-3-031-20071-7_4) [[code]](https://github.com/megvii-research/TLC)
  - Day-to-Night Image Synthesis for Training Nighttime Neural ISPs. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Punnappurath_Day-to-Night_Image_Synthesis_for_Training_Nighttime_Neural_ISPs_CVPR_2022_paper.pdf) [[code]](https://github.com/SamsungLabs/day-to-night)
  - Learning to See in the Extremely Dark. [[ICCV 2025]](https://arxiv.org/pdf/2506.21132) [[code]](https://github.com/JianghaiSCU/SIED)
  
## Video denoise
- **EDVR**: Video Restoration with Enhanced Deformable Convolutional Networks. [[CVPR 2019]](https://openaccess.thecvf.com/content_CVPRW_2019/papers/NTIRE/Wang_EDVR_Video_Restoration_With_Enhanced_Deformable_Convolutional_Networks_CVPRW_2019_paper.pdf) [[code]](https://github.com/xinntao/EDVR)
- **FastDVDnet**: Towards Real-Time Deep Video Denoising Without Flow Estimation. [[CVPR 2020]](https://openaccess.thecvf.com/content_CVPR_2020/html/Tassano_FastDVDnet_Towards_Real-Time_Deep_Video_Denoising_Without_Flow_Estimation_CVPR_2020_paper.html) [[code]](https://github.com/m-tassano/fastdvdnet)
- (**RViDeNet**) Supervised Raw Video Denoising with a **Benchmark Dataset** on Dynamic Scenes. [[CVPR 2020]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yue_Supervised_Raw_Video_Denoising_With_a_Benchmark_Dataset_on_Dynamic_CVPR_2020_paper.pdf) [[code]](https://github.com/cao-cong/RViDeNet)
- (**EMVD**) Efficient multi-stage video denoising with recurrent spatio-temporal fusion. [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Maggioni_Efficient_Multi-Stage_Video_Denoising_With_Recurrent_Spatio-Temporal_Fusion_CVPR_2021_paper.pdf) [[code]](https://github.com/Baymax-chen/EMVD)
- (**Improved EMVD**) Improved EMVD for RAW video denoising. [[paper]](https://gretsi.fr/data/colloque/pdf/2022_zheng966.pdf)
- Dancing under the stars: video denoising in starlight. [[CVPR 2022]](https://openaccess.thecvf.com/content/CVPR2022/papers/Monakhova_Dancing_Under_the_Stars_Video_Denoising_in_Starlight_CVPR_2022_paper.pdf) [[code]](https://github.com/monakhova/starlight_denoising/tree/main)
- Towards Real-World Video Denosing: A Practical Video Denosing Dataset and Network. [[paper]](https://arxiv.org/pdf/2207.01356) [[code]](https://github.com/Marinyyt/PVDD)
- (**ShiftNet**) A Simple Baseline for Video Restoration with Grouped Spatial-temporal Shift. [[CVPR 2023]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_A_Simple_Baseline_for_Video_Restoration_With_Grouped_Spatial-Temporal_Shift_CVPR_2023_paper.pdf) [[code]](https://github.com/dasongli1/Shift-Net)
- (**BRVE**) Binarized Low-light Raw Video Enhancement. [[CVPR 2024]](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_Binarized_Low-light_Raw_Video_Enhancement_CVPR_2024_paper.pdf) [[code]](https://github.com/zhanggengchen/BRVE)
- **Rvideformer**: Efficient raw video denoising transformer with a larger benchmark dataset. [[TCSVT 2025]](https://arxiv.org/abs/2305.00767) [[code]](https://github.com/cao-cong/RViDeformer)

## HDR
- Deep high dynamic range imaging of dynamic scenes. [[SIGGRAPH 2017]](https://people.engr.tamu.edu/nimak/Data/SIGGRAPH17_HDR_LoRes.pdf) [[code]](https://github.com/TH3CHARLie/deep-high-dynamic-range)
- Attention-guided network for ghost-free high dynamic range imaging. [[CVPR 2019]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yan_Attention-Guided_Network_for_Ghost-Free_High_Dynamic_Range_Imaging_CVPR_2019_paper.pdf) [[code]](https://github.com/qingsenyangit/AHDRNet)
- ADNet: Attention-guided Deformable Convolutional Network for High Dynamic Range Imaging. [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/papers/Liu_ADNet_Attention-Guided_Deformable_Convolutional_Network_for_High_Dynamic_Range_Imaging_CVPRW_2021_paper.pdf) [[code]](https://github.com/liuzhen03/ADNet)
- Ghost-free High Dynamic Range Imaging with Context-aware Transformer. [[ECCV 2022]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136790336.pdf) [[code]](https://github.com/megvii-research/HDR-Transformer)
- HDRFlow: Real-Time HDR Video Reconstruction with Large Motions. [[CVPR 2024]](https://openaccess.thecvf.com/content/CVPR2024/papers/Xu_HDRFlow_Real-Time_HDR_Video_Reconstruction_with_Large_Motions_CVPR_2024_paper.pdf) [[code]](https://github.com/OpenImagingLab/HDRFlow)

## TMO
- Deep tone mapping operator for high dynamic range images. [[TIP 2019]](https://arxiv.org/pdf/1908.04197) [[code]](https://github.com/Aakanksha-Rana/DeepTMO)

## Image retouching
- (**CSRNet**) Conditional sequential modulation for efficient global image retouching.[[ECCV 2020]](https://arxiv.org/pdf/2009.10390) [[code]](https://github.com/hejingwenhejingwen/CSRNet)
- (**3D-LUT**) Learning Image-adaptive 3D Lookup Tables for High Performance Photo Enhancement in Real-time.[[TPAMI 2020]](https://arxiv.org/pdf/2009.14468) [[code]](https://github.com/HuiZeng/Image-Adaptive-3DLUT)
- **AdaInt**: Learning Adaptive Intervals for 3D Lookup Tables on Real-time Image Enhancement. [[CVPR 2022]](https://arxiv.org/pdf/2204.13983) [[code]](https://github.com/ImCharlesY/AdaInt)
- Learning Tone Curves for Local Image Enhancement. [[IEEE ACCESS 2022]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9784427) [[code]](https://github.com/SamsungLabs/ltmnet)
- **RSFNet**: A White-Box Image Retouching Approach using Region-Specific Color Filters. [[ICCV 2023]](https://arxiv.org/pdf/2303.08682) [[code]](https://github.com/vicky0522/rsfnet)
- (**LLF-LUT**) High-resolution photo enhancement in real-time: a laplacian pyramid network.[[TPAMI 2025]](https://arxiv.org/pdf/2510.11613) [[code]](https://github.com/fengzhang427/LLF-LUT)
- (**BPAM**) Learning Pixel-adaptive Multi-layer Perceptrons for Real-time Image Enhancement.[[ICCV 2025]](https://openaccess.thecvf.com/content/ICCV2025/papers/Lou_Learning_Pixel-adaptive_Multi-layer_Perceptrons_for_Real-time_Image_Enhancement_ICCV_2025_paper.pdf)[[code]](https://github.com/CVL-UESTC/BPAM)

## Low-Light enhancement
- Dataset
  - Towards Realistic Low-Light Image Enhancement via ISP–Driven Data Modeling. [[paper]](https://arxiv.org/pdf/2504.12204) [[code]](https://github.com/wzhsysu/LLIE)
  - Seeing in the Dark: Synthesizing Underexposure for More Robust Underwater Image Augmentation. [[WACV 2026]](https://openaccess.thecvf.com/content/WACV2026W/WVAQ/papers/Awad_Seeing_in_the_Dark_Synthesizing_Underexposure_for_More_Robust_Underwater_WACVW_2026_paper.pdf)
- Architecture
  - (**Zero-DCE**) Learning to Enhance Low-Light Image via Zero-Reference Deep Curve Estimation. [[TPAMI 2021]](https://arxiv.org/pdf/2103.00860.pdf) [[code]](https://github.com/Li-Chongyi/Zero-DCE)
  - (**RUAS**) Retinex-inspired unrolling with cooperative prior architecture search for low-light image enhancement. [[CVPR 2021]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Retinex-Inspired_Unrolling_With_Cooperative_Prior_Architecture_Search_for_Low-Light_Image_CVPR_2021_paper.pdf) [[code]](https://github.com/KarelZhang/RUAS)
  - (**SCI**) Toward Fast, Flexible, and Robust Low-Light Image Enhancement. [[CVPR 2022(Oral)]](https://openaccess.thecvf.com/content/CVPR2022/html/Ma_Toward_Fast_Flexible_and_Robust_Low-Light_Image_Enhancement_CVPR_2022_paper.html) [[code]](https://github.com/vis-opt-group/SCI)
  - **Retinexformer**: One-stage Retinex-based Transformer for Low-light Image Enhancement. [[ICCV 2023]](https://openaccess.thecvf.com/content/ICCV2023/papers/Cai_Retinexformer_One-stage_Retinex-based_Transformer_for_Low-light_Image_Enhancement_ICCV_2023_paper.pdf) [[code]](https://github.com/caiyuanhao1998/Retinexformer)
  - **HVI**: A New Color Space for Low-light Image Enhancement. [[CVPR 2025]](https://arxiv.org/abs/2502.20272) [[code]](https://github.com/Fediory/HVI-CIDNet)

## AWB
- Convolutional Color Constancy. [[paper]](https://arxiv.org/pdf/1507.00410)
- (**C5**) Cross-Camera Convolutional Color Constancy. [[ICCV 2021]](https://arxiv.org/pdf/2011.11890) [[code]](https://github.com/mahmoudnafifi/C5)
- Time-Aware Auto White Balance in Mobile Photography. [[ICCV 2025]](https://openaccess.thecvf.com/content/ICCV2025/papers/Afifi_Time-Aware_Auto_White_Balance_in_Mobile_Photography_ICCV_2025_paper.pdf) [[code]](https://github.com/SamsungLabs/time-aware-awb)
- Learning Camera-Agnostic White-Balance Preferences. [[ICCV 2025]](https://openaccess.thecvf.com/content/ICCV2025W/MIPI/papers/Zhao_Learning_Camera-Agnostic_White-Balance_Preferences_ICCVW_2025_paper.pdf) [[code]](https://github.com/SamsungLabs/aesthetics-pref-awb)
- Integral Fast Fourier Color Constancy. [[CVPR 2025]](https://openaccess.thecvf.com/content/CVPR2025/papers/Wei_Integral_Fast_Fourier_Color_Constancy_CVPR_2025_paper.pdf)

## Demosaicing
- Joint Demosaicing and Denoising with Self Guidance. [[CVPR 2020]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Liu_Joint_Demosaicing_and_Denoising_With_Self_Guidance_CVPR_2020_paper.pdf) [[code]](https://github.com/laulampaul/sgnet)
- Joint Denoising and Demosaicking with Green Channel Prior for Real-world Burst Images. [[TIP 2021]](https://arxiv.org/pdf/2101.09870) [[code]](https://github.com/GuoShi28/GCP-Net)

## Resources
- NTIRE (New Trends in Image Restoration and Enhancement)
- MIPI (Mobile Intelligent Photography and Imaging)
- MAI (Mobile AI Workshop)
- AIM (Advances in Image Manipulation)
- [Infinite-ISP](https://github.com/10x-Engineers/Infinite-ISP?tab=readme-ov-file)
- [fast-openISP](https://github.com/QiuJueqin/fast-openISP)
- [Awesome-Low-Level-Vision-Research-Groups](https://github.com/Kobaayyy/Awesome-Low-Level-Vision-Research-Groups)
