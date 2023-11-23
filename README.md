# Underwater-Image-Enhancement
Summary of Publicly Available Underwater Image Enhancement Method

**Raise Issue or PR to add more**

## Dataset

[Github Summary](https://github.com/xinzhichao/underwater_datasets)

[Github Summary](https://github.com/lizhh268/awesome_underwater_image_enhancement-UIE-)

Sea-thru can be downloaded from [Kaggle](https://www.kaggle.com/datasets/colorlabeilat/seathru-dataset)

## Method

### Traditional

| Title                                                        | Year | Publication      | Code                                                         |
| ------------------------------------------------------------ | ---- | ---------------- | ------------------------------------------------------------ |
| Enhancing the low quality images using Unsupervised Colour Correction Method | 2010 | SMC              | [Python](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration) |
| Underwater Image Enhancement by Wavelength Compensation and Dehazing | 2011 | TIP              | [MATLAB](https://github.com/mohitkumarahuja/Underwater-Image-Enhancement-by-Wavelength-Compensation-and-Dehazing) |
| Enhancing underwater images and videos by fusion             | 2012 | CVPR             | [MATLAB](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration) |
| Transmission Estimation in Underwater Single Images          | 2013 | ICCV Workshop    | [Python](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration) |
| Single underwater image enhancement using depth estimation based on blurriness | 2015 | ICIP             | [MATLAB](https://github.com/ytpeng-aimlab/Single-Underwater-Image-Enhancement-Using-Depth-Estimation-based-on-Blurriness) |
| Underwater image enhancement by dehazing with minimum information loss and histogram distribution prior | 2016 | TIP              | [MATLAB](https://github.com/Li-Chongyi/TIP2016-code)         |
| Single underwater image restoration by blue-green channels dehazing and red channel correction | 2016 | ICASSP           | [Python](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration) |
| Underwater Image Restoration Based on Image Blurriness and Light Absorption | 2017 | TIP              | [Python](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration) |
| Diving into Haze-Lines: Color Restoration of Underwater Images | 2017 | BMVC             | [MATLAB](https://github.com/danaberman/underwater-hl)        |
| Shallow-Water Image Enhancement Using Relative Global Histogram Stretching Based on Adaptive Parameter Acquisition | 2018 | MMM              | [Python](https://github.com/wangyanckxx/Single-Underwater-Image-Enhancement-and-Color-Restoration) |
| Color Balance and Fusion for Underwater Image Enhancement    | 2018 | TIP              | [MATLAB](https://github.com/fergaletto/Color-Balance-and-fusion-for-underwater-image-enhancement.-.) |
| Enhancement of Underwater Images With Statistical Model of Background Light and Optimization of Transmission Map | 2019 | IEEE T BROADCAST | [Python](https://github.com/wangyanckxx/Enhancement-of-Underwater-Images-with-Statistical-Model-of-BL-and-Optimization-of-TM) |
| Real-time Model-based Image Color Correction for Underwater Robots | 2019 | IROS             | [C++](https://github.com/dartmouthrobotics/underwater_color_enhance) |
| Sea-Thru: A Method for Removing Water From Underwater Images | 2019 | CVPR             | [Python](https://github.com/hainh/sea-thru)                  |
| Restoration of Non-rigidly Distorted Underwater Images using a Combination of Compressive Sensing and Local Polynomial Image Representations | 2019 | ICCV             | [MATLAB](https://github.com/jeringeo/CompressiveFlows)       |
| Local Color Mapping combined with Color Transfer for Underwater Image Enhancement | 2019 | WACV             | [MATLAB](https://github.com/rprotasiuk/underwater_enhancement) |
| Adaptive Enhancement of Underwater Images using Multiobjective PSO | 2019 | MTA              | [MATLAB](https://github.com/Rajni27/CIEUI)                   |
| L^2UWE: A Framework for the Efficient Enhancement of Low-Light Underwater Images Using Local Contrast and Multi-Scale Fusion | 2020 | CVPR Workshop    | [MATLAB](https://github.com/tunai/l2uwe)                     |
| Bayesian retinex underwater image enhancement                | 2021 | EAAI             | [MATLAB](https://github.com/zhuangpeixian/Bayesian-Retinex-Underwater-Enhancement) |
| Underwater Image Enhancement via Minimal Color Loss and Locally Adaptive Contrast Enhancement | 2022 | TIP              | [MATLAB](https://github.com/Li-Chongyi/MMLE_code)            |
| Underwater Image Enhancement With Hyper-Laplacian Reflectance Priors | 2022 | TIP              | [MATLAB](https://github.com/zhuangpeixian/HLRP)              |
| Non-uniform Illumination Underwater Image Restoration via Illumination Channel Sparsity Prior | 2023 | TCSVT            | [MATLAB](https://github.com/Hou-Guojia/ICSP)                 |
| Underwater Image Enhancement via Weighted Wavelet Visual Perception Fusion | 2023 | TCSVT            | [MATLAB](https://github.com/Li-Chongyi/WWPF_code)            |

### Learning

| Name                 | Year | Publication    | Code                                                         |
| -------------------- | ---- | -------------- | ------------------------------------------------------------ |
| WaterGAN             | 2017 | RA-L           | [Tensorflow](https://github.com/kskin/WaterGAN)              |
| UGAN                 | 2018 | ICRA           | [Tensorflow](https://github.com/cameronfabbri/Underwater-Color-Correction)\|[Pytorch](https://github.com/xahidbuffon/FUnIE-GAN) |
| WAug Encoder-Decoder | 2019 | CVPR Workshop  | [Pytorch](https://github.com/AdarshMJ/Underwater-Image-Enhancement-via-Style-Transfer) |
| UIE-DAL              | 2019 | CVPR Workshops | [Pytorch](https://github.com/VITA-Group/All-In-One-Underwater-Image-Enhancement-using-Domain-Adversarial-Learning) |
| WaterNet             | 2019 | TIP            | [Tensorflow](https://github.com/Li-Chongyi/Water-Net_Code)\|[Pytorch](https://github.com/BIGWangYuDong/UWEnhancement) |
| FUnIE-GAN            | 2020 | RA-L           | [Tensorflow & Pytorch](https://github.com/xahidbuffon/FUnIE-GAN) |
| SESR                 | 2020 | RSS            | [Tensorflow](https://github.com/xahidbuffon/Deep_SESR)       |
| UWCNN                | 2020 | PR             | [Tensorflow](https://github.com/saeed-anwar/UWCNN)\|[Pytorch](https://github.com/BIGWangYuDong/UWEnhancement) |
| HybridDetectionGAN   | 2020 | TCSVT          | [Tensorflow](https://github.com/cjh666-sym/HybridDetectionGAN) |
| cGAN                 | 2020 | SPIC           | [Tensorflow](https://github.com/JOU-UIP/Underwater-image-enhancement-based-on-conditional-generative-adversarial-network) |
| PRWNet               | 2021 | ICCV Workshop  | [Pytorch](https://github.com/huofushuo/PRWNet)               |
| CWR                  | 2021 | IGARSS         | [Pytorch](https://github.com/JunlinHan/CWR)                  |
| Shallow-UWNet        | 2021 | AAAI           | [Pytorch](https://github.com/mkartik/Shallow-UWnet)          |
| UColor               | 2021 | TIP            | [Tensorflow](https://github.com/Li-Chongyi/Ucolor)\|[Pytorch](https://github.com/CV-Reimplementation/Ucolor-Reimplementation) |
| UIEC^2-Net           | 2021 | SPIC           | [Pytorch](https://github.com/BIGWangYuDong/UWEnhancement)    |
| STSC                 | 2022 | ICRA           | [Pytorch](https://github.com/wdhudiekou/STSC)                |
| URSCT-SESR           | 2022 | TGRS           | [Pytorch](https://github.com/TingdiRen/URSCT-SESR)           |
| TACL                 | 2022 | TIP            | [Pytorch](https://github.com/Jzy2017/TACL)                   |
| TOPAL                | 2022 | TCSVT          | [Pytorch](https://github.com/Jzy2017/TOPAL)                  |
| SGUIE-Net            | 2022 | TIP            | [Pytorch](https://github.com/trentqq/SGUIE-Net_Simple)       |
| PUIE-Net             | 2022 | ECCV           | [Pytorch](https://github.com/zhenqifu/puie-net)              |
| UIE-WD               | 2022 | ICASSP         | [Pytorch](https://github.com/ZZiyin/UIE-WD_Code)             |
| UHD-SFNet            | 2022 | ACCV           | [Pytorch](https://github.com/zzr-idam/UHD-Underwater-Image-Enhancement) |
| ADMNNet              | 2022 | KBS            | [Pytorch](https://github.com/xhyan006/ADMNNet)               |
| LANet                | 2022 | RA-L           | [Pytorch](https://github.com/LiuShiBen/LANet)                |
| U-Shape Transformer  | 2023 | TIP            | [Pytorch](https://github.com/LintaoPeng/U-shape_Transformer_for_Underwater_Image_Enhancement) |
| PUGAN                | 2023 | TIP            | [Pytorch](https://github.com/rmcong/PUGAN_TIP2023)           |
| Semi-UIR             | 2023 | CVPR           | [Pytorch](https://github.com/Huang-ShiRui/Semi-UIR)          |
| SyreaNet             | 2023 | ICRA           | [Pytorch](https://github.com/RockWenJJ/SyreaNet)             |
| Five A+ Network      | 2023 | BMVC           | [Pytorch](https://github.com/Owen718/FiveAPlus-Network)      |
| UIALN                | 2023 | TCSVT          | [Pytorch](https://github.com/kevendai/UIALN-Reproduction-Experiment) |
| Deep WaveNet         | 2023 | TOMM           | [Pytorch](https://github.com/pksvision/Deep-WaveNet-Underwater-Image-Restoration) |
| DM                   | 2023 | MM             | [Pytorch](https://github.com/piggy2009/DM_underwater)        |
| P2CNet               | 2023 | TCSVT          | [Pytorch](https://github.com/Ray2OUC/P2CNet)                 |

## Metric

### Full-Reference

[torchmetrics](https://github.com/Lightning-AI/torchmetrics) for cuda calculation

**PSNR**

**SSIM**

**MAE**

**MSE**

**RMSE**

### Non-Reference

**UIQM**

**UCIQE**

**NIQE**

**PS**

**MUSIQ**

