# Awesome Remote Sensing Visual Generative Models

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![GitHub stars](https://img.shields.io/github/stars/Bili-Sakura/awesome-remote-sensing-visual-generative-models.svg?style=social&label=Star)](https://github.com/Bili-Sakura/awesome-remote-sensing-visual-generative-models) [![GitHub forks](https://img.shields.io/github/forks/Bili-Sakura/awesome-remote-sensing-visual-generative-models.svg?style=social&label=Fork)](https://github.com/Bili-Sakura/awesome-remote-sensing-visual-generative-models/fork) [![GitHub watchers](https://img.shields.io/github/watchers/Bili-Sakura/awesome-remote-sensing-visual-generative-models.svg?style=social&label=Watch)](https://github.com/Bili-Sakura/awesome-remote-sensing-visual-generative-models) [![GitHub issues](https://img.shields.io/github/issues/Bili-Sakura/awesome-remote-sensing-visual-generative-models)](https://github.com/Bili-Sakura/awesome-remote-sensing-visual-generative-models/issues) [![GitHub contributors](https://img.shields.io/github/contributors/Bili-Sakura/awesome-remote-sensing-visual-generative-models)](https://github.com/Bili-Sakura/awesome-remote-sensing-visual-generative-models/graphs/contributors)

A curated list of awesome remote sensing visual generative models, papers, datasets, and resources. This repository focuses exclusively on **satellite images** and excludes aerial images, street-view images, and their applications.

## Contents

- [Survey Papers](#survey-papers)
- [Scene Synthesis (Unconditional/Text-to-Image Generation)](#scene-synthesis-unconditionaltext-to-image-generation)
- [Controllable & Structural Synthesis](#controllable--structural-synthesis)
- [Image-to-Image Translation & Restoration](#image-to-image-translation--restoration)
- [Inpainting & Content Editing](#inpainting--content-editing)
- [Multi-temporal & Sequence Generation](#multi-temporal--sequence-generation)
- [Generative Modeling for Discriminative Tasks](#generative-modeling-for-discriminative-tasks)
- [Datasets](#datasets)
- [Evaluation Metrics](#evaluation-metrics)
- [Contributing](#contributing)
- [License](#license)

## Survey Papers

> [!IMPORTANT] 
> The following are related survey papers in remote sensing. However, **visual generative models remain under-explored** in all existing remote sensing surveys. This repository aims to fill this gap by providing a comprehensive collection of visual generative models specifically for **satellite images**. We focus exclusively on satellite imagery and exclude aerial images, street-view images, and their applications.

| Title | Year | Venue | Tags | Link |
|-------|------|-------|------|------|
| From Orbit to Ground: A Comprehensive Review of Multimodal Self-Supervised Learning for Remote Sensing | 2025 | IEEE MGRS | Multimodal, SSL | [DOI](https://doi.org/10.1109/MGRS.2025.3588505) |
| Remote Sensing Spatiotemporal Vision--Language Models: A Comprehensive Survey | 2025 | IEEE MGRS | VLMs, (Spatio-)Temporal-VLMs | [DOI](https://doi.org/10.1109/MGRS.2025.3598283) |
| Vision-Language Models in Remote Sensing: Current Progress and Future Trends | 2024 | IEEE MGRS | VLMs | [DOI](https://doi.org/10.1109/MGRS.2024.3383473) |
| Vision Foundation Models in Remote Sensing: A Survey | 2025 | IEEE MGRS | Vision Foundation Models, SSL  | [DOI](https://doi.org/10.1109/MGRS.2025.3541952) |
| Artificial Intelligence to Advance Earth Observation: A Review of Models, Recent Trends, and Pathways Forward | 2025 | IEEE MGRS | Representation Learning | [DOI](https://doi.org/10.1109/MGRS.2024.3425961) |
| Vision-Language Modeling Meets Remote Sensing: Models, Datasets, and Perspectives | 2025 | IEEE MGRS | VLMs | [DOI](https://doi.org/10.1109/MGRS.2025.3572702) |
| Foundation Models for Remote Sensing and Earth Observation: A Survey | 2025 | IEEE MGRS | Vision Foundation Models, VLMs | [DOI](https://doi.org/10.1109/MGRS.2025.3576766) |
| Regression in Earth Observation: Are Vision--Language Models up to the Challenge? | 2025 | IEEE MGRS | VLMs | [DOI](https://doi.org/10.1109/MGRS.2025.3596243) |

## Scene Synthesis (Unconditional/Text-to-Image Generation)

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| Uni-RS: A Spatially Faithful Unified Understanding and Generation Model for Remote Sensing | 2026 | arXiv | [arXiv](https://arxiv.org/abs/2601.17673) | N/A |
| HSIGene: A Foundation Model for Hyperspectral Image Generation | 2026 | IEEE TPAMI | [DOI](https://doi.org/10.1109/TPAMI.2025.3610927) | [GitHub](https://github.com/LiPang/HSIGene) |
| Extrapolate Azimuth Angles: Text and Edge Guided ISAR Image Generation Based on Foundation Model | 2026 | ISPRS JPRS | [DOI](https://doi.org/10.1016/j.isprsjprs.2025.12.002) | N/A |
| Text2Earth: Unlocking Text-Driven Remote Sensing Image Generation with a Global-Scale Dataset and a Foundation Model | 2025 | IEEE MGRS | [DOI](https://doi.org/10.1109/MGRS.2025.3560455) | [GitHub](https://github.com/chen-yang-liu/Text2Earth) |
| ZoomLDM: Latent Diffusion Model for Multi-scale Image Generation | 2025 | CVPR | [CVPR](https://openaccess.thecvf.com/content/CVPR2025/html/Yellapragada_ZoomLDM_Latent_Diffusion_Model_for_Multi-scale_Image_Generation_CVPR_2025_paper.html) | [GitHub](https://github.com/cvlab-stonybrook/ZoomLDM) |
| MetaEarth: A Generative Foundation Model for Global-Scale Remote Sensing Image Generation | 2025 | IEEE TPAMI | [DOI](https://doi.org/10.1109/TPAMI.2024.3507010) | [GitHub](https://github.com/jiupinjia/MetaEarth) |
| RSVQ-Diffusion Model for Text-to-Remote-Sensing Image Generation | 2025 | Applied Sciences | [DOI](https://doi.org/10.3390/app15031121) | N/A |
| DiffusionSat: A Generative Foundation Model for Satellite Imagery | 2024 | ICLR | [ICLR](https://openreview.net/forum?id=I5webNFDgQ) | [GitHub](https://github.com/samar-khanna/DiffusionSat) |
| RSDiff: Remote Sensing Image Generation from Text Using Diffusion Model | 2024 | Neural Computing and Applications | [DOI](https://doi.org/10.1007/s00521-024-10363-3) | N/A |


## Controllable & Structural Synthesis

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| Object Fidelity Diffusion for Remote Sensing Image Generation | 2026 | ICLR | [ICLR](https://openreview.net/forum?id=ngfIm9aPsH) | [GitHub](https://github.com/VisionXLab/OF-Diff) |
| Transferable Image Synthesis for Remote Sensing Semantic Segmentation via Joint Reference-Semantic Fusion | 2026 | Information Fusion | [DOI](https://doi.org/10.1016/j.inffus.2025.103839) | N/A |
| EarthSynth: Generating Informative Earth Observation with Diffusion Models | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2505.12108) | N/A |
| Task-Oriented Data Synthesis and Control-Rectify Sampling for Remote Sensing Semantic Segmentation | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2512.16740) | N/A |
| TerraGen: A Unified Multi-Task Layout Generation Framework for Remote Sensing Data Augmentation | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2510.21391) | N/A |
| Cascaded Autoregressive Diffusion Models for Remote Sensing Scene Generation | 2025 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2025.3622225) | N/A |
| GeoSynth: Contextually-Aware High-Resolution Satellite Image Synthesis | 2024 | CVPR | [CVPR](https://openaccess.thecvf.com/content/CVPR2024W/EarthVision/html/Sastry_GeoSynth_Contextually-Aware_High-Resolution_Satellite_Image_Synthesis_CVPRW_2024_paper.html) | [GitHub](https://github.com/mvrl/GeoSynth) |
| SatSynth: Augmenting Image-Mask Pairs through Diffusion Models for Aerial Semantic Segmentation | 2024 | CVPR | [CVPR](http://openaccess.thecvf.com//content/CVPR2024/papers/Toker_SatSynth_Augmenting_Image-Mask_Pairs_through_Diffusion_Models_for_Aerial_Semantic_CVPR_2024_paper.pdf) | N/A |
| CRS-Diff: Controllable Remote Sensing Image Generation With Diffusion Model | 2024 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2024.3453414) | [GitHub](https://github.com/Sonettoo/CRS-Diff) |


## Image-to-Image Translation & Restoration

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| Adaptive Domain Shift in Diffusion Models for Cross-Modality Image Translation | 2026 | arXiv | [arXiv](https://arxiv.org/abs/2601.18623) | N/A |
| Efficient End-to-End Diffusion Model for One-Step SAR-to-Optical Translation | 2025 | IEEE GRSL | [DOI](https://doi.org/10.1109/LGRS.2024.3506566) | N/A |
| 3rd Multi-modal Aerial View Image Challenge: Sensor Domain Translation - PBVS 2025 | 2025 | CVPRW (PBVS) | [CVPRW](https://openaccess.thecvf.com/content/CVPR2025W/PBVS/html/Bowald_3rd_Multi-modal_Aerial_View_Image_Challenge_Sensor_Domain_Translation_-_CVPRW_2025_paper.html) | N/A |
| Conditional Diffusion Model With Spatial-Frequency Refinement for SAR-to-Optical Image Translation | 2024 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2024.3491826) | N/A |
| SAR-to-Optical Image Translation With Hierarchical Latent Features | 2022 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2022.3200996) | N/A |
| Gan-based SAR to Optical Image Translation in Fire-Disturbed Regions | 2022 | IGARSS | [DOI](https://doi.org/10.1109/IGARSS46834.2022.9884234) | N/A |

## Inpainting & Content Editing

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| DreamCD: A Change-Label-Free Framework for Change Detection via a Weakly Conditional Semantic Diffusion Model in Optical VHR Imagery | 2026 | JAG | [DOI](https://doi.org/10.1016/j.jag.2026.105125) | [GitHub](https://github.com/tangkai-RS/DreamCD) |
| ChangeBridge: Spatiotemporal Image Generation with Multimodal Controls for Remote Sensing | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2507.04678)  | N/A |
| Exploring Text-Guided Single Image Editing for Remote Sensing Images | 2025 | JSTAR | [DOI](https://doi.org/10.1109/JSTARS.2025.3584418) | N/A |
| Text2Earth: Unlocking Text-Driven Remote Sensing Image Generation with a Global-Scale Dataset and a Foundation Model | 2025 | IEEE MGRS | [DOI](https://doi.org/10.1109/MGRS.2025.3560455) | [GitHub](https://github.com/chen-yang-liu/Text2Earth) |
| DiffusionSat: A Generative Foundation Model for Satellite Imagery | 2024 | ICLR | [ICLR](https://openreview.net/forum?id=I5webNFDgQ) | [GitHub](https://github.com/samar-khanna/DiffusionSat) |

## Multi-temporal & Sequence Generation

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| Generating Any Changes in the Noise Domain | 2025 | IEEE TPAMI | [DOI](https://doi.org/10.1109/TPAMI.2025.3643733) | N/A |
| ChangeDiff: A Multi-Temporal Change Detection Data Generator with Flexible Text Prompts via Diffusion Model | 2025 | AAAI | [AAAI](https://doi.org/10.1609/aaai.v39i9.33058) | [GitHub](https://github.com/DZhaoXd/ChangeDiff) |
| UniTS: Unified Time Series Generative Model for Remote Sensing | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2512.04461) | [GitHub](https://github.com/YuxiangZhang-BIT/UniTS) |
| Changen2: Multi-Temporal Remote Sensing Generative Change Foundation Model | 2024 | IEEE TPAMI | [DOI](https://doi.org/10.1109/TPAMI.2024.3475824) | [GitHub](https://github.com/Z-Zheng/pytorch-change-models) |
| Scalable Multi-Temporal Remote Sensing Change Data Generation via Simulating Stochastic Change Process | 2023 | ICCV | [ICCV](https://doi.org/10.1109/ICCV51070.2023.01994) | [GitHub](https://github.com/Z-Zheng/pytorch-change-models) |

## Generative Modeling for Discriminative Tasks

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| Can Generative Geospatial Diffusion Models Excel as Discriminative Geospatial Foundation Models? | 2025 | ICCV | [ICCV](https://openaccess.thecvf.com/content/ICCV2025/html/Jia_Can_Generative_Geospatial_Diffusion_Models_Excel_as_Discriminative_Geospatial_Foundation_ICCV_2025_paper.html) | [GitHub](https://github.com/yurujaja/SatDiFuser) |
| RemoteVAR: Autoregressive Visual Modeling for Remote Sensing Change Detection | 2026 | arXiv | [arXiv](https://arxiv.org/abs/2601.11898) | [GitHub](https://github.com/yilmazkorkmaz1/RemoteVAR) |

## Datasets

> [!IMPORTANT]
> This section mainly lists dataset papers from 2025 onward, with a few earlier references for context.

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| TerraMesh: A Planetary Mosaic of Multimodal Earth Observation Data (SSL, Temporal, Multi-Sensor) | 2025 | CVPR Workshop | [CVPRW](https://openaccess.thecvf.com/content/CVPR2025W/EarthVision/html/Blumenstiel_TerraMesh_A_Planetary_Mosaic_of_Multimodal_Earth_Observation_Data_CVPRW_2025_paper.html) | [HF](https://huggingface.co/datasets/ibm-esa-geospatial/TerraMesh) |
| TerraMind: Large-Scale Generative Multimodality for Earth Observation | 2025 | ICCV | [ICCV](https://openaccess.thecvf.com/content/ICCV2025/html/Jakubik_TerraMind_Large-Scale_Generative_Multimodality_for_Earth_Observation_ICCV_2025_paper.html) | [GitHub](https://github.com/IBM/terramind) &#124; [HF](https://huggingface.co/ibm-esa-geospatial) |
| SAR-TEXT: A Large-Scale SAR Image-Text Dataset Built with SAR-Narrator and Progressive Transfer Learning (SAR Vision-Language) | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2507.18743) | [GitHub](https://github.com/YiguoHe/SAR-TEXT) |
| MMEarth: Exploring Multi-modal Pretext Tasks for Geospatial Representation Learning | 2024 | ECCV | [ECCV](https://doi.org/10.1007/978-3-031-73039-9_10) | [GitHub](https://github.com/vishalned/MMEarth-train) |
| Prithvi-EO-2.0: A Versatile Multitemporal Foundation Model for Earth Observation Applications | 2026 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2025.3642610) | [GitHub](https://github.com/NASA-IMPACT/Prithvi-EO-2.0) |
| Galileo: Learning Global & Local Features of Many Remote Sensing Modalities | 2025 | ICML | [ICML](https://openreview.net/forum?id=gqZO3eSZRy) | [GitHub](https://github.com/nasaharvest/galileo) |
| EarthView: A Large Scale Remote Sensing Dataset for Self-Supervision (SSL, Temporal, Multi-Sensor) | 2025 | WACV Workshop | [WACVW](https://openaccess.thecvf.com/content/WACV2025W/CV4EO/html/Velazquez_EarthView_A_Large_Scale_Remote_Sensing_Dataset_for_Self-Supervision_WACVW_2025_paper.html) | [GitHub](https://github.com/satellogic/satellogic-earthview) |
| Towards a Unified Copernicus Foundation Model for Earth Vision | 2025 | ICCV | [ICCV](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_Towards_a_Unified_Copernicus_Foundation_Model_for_Earth_Vision_ICCV_2025_paper.html) | [GitHub](https://github.com/zhu-xlab/Copernicus-FM) |
| SARLANG-1M: A Benchmark for Vision-Language Modeling in SAR Image Understanding (SAR Vision-Language) | 2026 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2026.3652099) | [GitHub](https://github.com/jimmyxichen/SARLANG-1M) |
| SOMA-1M: A Large-Scale SAR-Optical Multi-resolution Alignment Dataset for Multi-Task Remote Sensing | 2026 | arXiv | [arXiv](https://arxiv.org/abs/2602.05480) | [GitHub](https://github.com/PeihaoWu/SOMA-1M) |
| MaRS: A Multi-Modality Very-High-Resolution Remote Sensing Foundation Model with Cross-Granularity Meta-Modality Learning | 2026 | AAAI | N/A | [GitHub](https://github.com/WanderRainy/MaRS) |
| OpenEarthMap: A Benchmark Dataset for Global High-Resolution Land Cover Mapping | 2023 | WACV | [WACV](https://doi.org/10.1109/WACV56688.2023.00619) | [GitHub](https://github.com/bao18/open_earth_map) |
| OpenEarthMap-SAR: A Benchmark Synthetic Aperture Radar Dataset for Global High-Resolution Land Cover Mapping (SAR Segmentation Maps) | 2025 | IEEE MGRS | [DOI](https://doi.org/10.1109/MGRS.2025.3599512) | [GitHub](https://github.com/cliffbb/OpenEarthMap-SAR) |
| BRIGHT: A Globally Distributed Multimodal Building Damage Assessment Dataset with Very-High-Resolution for All-Weather Disaster Response (Optical-SAR Pairs) | 2025 | Earth System Science Data | [DOI](https://doi.org/10.5194/essd-17-6217-2025) | [GitHub](https://github.com/ChenHongruixuan/BRIGHT) |
| ChatEarthBench: Benchmarking Multimodal Large Language Models for Earth Observation | 2026 | IEEE MGRS | [DOI](https://doi.org/10.1109/MGRS.2026.3650840) | N/A |
| EarthVL: A Progressive Earth Vision-Language Understanding and Generation Framework | 2026 | arXiv | [arXiv](https://arxiv.org/abs/2601.02783) | N/A |
| GAIA: A Global, Multimodal, Multiscale Vision-Language Dataset for Remote Sensing Image Analysis | 2026 | IEEE MGRS | [DOI](https://doi.org/10.1109/MGRS.2025.3650613) | N/A |
| A Large-Scale Image–Text Dataset Benchmark for Farmland Segmentation | 2025 | Earth System Science Data | [DOI](https://doi.org/10.5194/essd-17-4835-2025) | N/A |
| CHOICE: Benchmarking the Remote Sensing Capabilities of Large Vision-Language Models | 2025 | NeurIPS D&B | [OpenReview](https://openreview.net/forum?id=GZ5LI6Fetp) | N/A |
| Constructing an Extensible Building Damage (EBD) Dataset via Semi-Supervised Fine-Tuning Across 12 Natural Disasters | 2025 | Journal of Remote Sensing | [DOI](https://doi.org/10.34133/remotesensing.0733) | N/A |
| DisasterM3: A Remote Sensing Vision-Language Dataset for Disaster Damage Assessment and Response | 2025 | NeurIPS D&B | [OpenReview](https://openreview.net/forum?id=sQO1ZEQGqX) | N/A |
| JL1-CD: A New Benchmark for Remote Sensing Change Detection and a Robust Multi-Teacher Knowledge Distillation Framework | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2502.13407v4) | N/A |
| RSAR: Restricted State Angle Resolver and Rotated SAR Benchmark | 2025 | CVPR | [DOI](https://doi.org/10.1109/CVPR52734.2025.00695) | N/A |
| RSCC: A Large-Scale Remote Sensing Change Caption Dataset for Disaster Events | 2025 | NeurIPS D&B | [OpenReview](https://openreview.net/forum?id=yn2fJYBKEB) | N/A |
| RSGPT: A Remote Sensing Vision Language Model and Benchmark | 2025 | ISPRS JPRS | [DOI](https://doi.org/10.1016/j.isprsjprs.2025.03.028) | N/A |
| RSVLM-QA: A Benchmark Dataset for Remote Sensing Vision Language Model-Based Question Answering | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2508.07918) | N/A |
| S-EO: A Large-Scale Dataset for Geometry-Aware Shadow Detection in Remote Sensing Applications | 2025 | CVPR Workshop | [CVPRW](https://openaccess.thecvf.com/content/CVPR2025W/EarthVision/html/Masquil_S-EO_A_Large-Scale_Dataset_for_Geometry-Aware_Shadow_Detection_in_Remote_CVPRW_2025_paper.html) | N/A |
| Git-10M (Text2Earth): Text-Driven Remote Sensing Image Generation Dataset | 2025 | IEEE MGRS | [DOI](https://doi.org/10.1109/MGRS.2025.3560455) | N/A |
| reBen: Refined BigEarthNet Dataset for Remote Sensing Image Analysis | 2025 | IGARSS | [DOI](https://doi.org/10.1109/IGARSS55030.2025.11242834) | N/A |


## Evaluation Metrics

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| Rethinking FID: Towards a Better Evaluation Metric for Image Generation (KID, FID, sFID, CMMD, SSIM, LPIPS) | 2024 | arXiv | [arXiv](https://arxiv.org/abs/2401.09603) | [GitHub](https://github.com/google-research/google-research/tree/master/cmmd) |

## Contributing

Contributions are welcome! You can either give a pull request or create an issue.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related or neighboring rights to this work. See the [LICENSE](LICENSE) file for the full legal text.
