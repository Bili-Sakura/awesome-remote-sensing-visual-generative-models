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
- [Datasets](#datasets)
- [Evaluation Metrics](#evaluation-metrics)
- [Contributing](#contributing)
- [License](#license)

## Survey Papers

> **Note**: The following are related survey papers in remote sensing. However, **visual generative models remain under-explored** in all existing remote sensing surveys. This repository aims to fill this gap by providing a comprehensive collection of visual generative models specifically for **satellite images**. We focus exclusively on satellite imagery and exclude aerial images, street-view images, and their applications.

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
| HSIGene: A Foundation Model for Hyperspectral Image Generation | 2026 | IEEE TPAMI | [DOI](https://doi.org/10.1109/TPAMI.2025.3610927) | [GitHub](https://github.com/LiPang/HSIGene) |
| Extrapolate Azimuth Angles: Text and Edge Guided ISAR Image Generation Based on Foundation Model | 2026 | ISPRS JPRS | [DOI](https://doi.org/10.1016/j.isprsjprs.2025.12.002) | N/A |
| Text2Earth: Unlocking Text-Driven Remote Sensing Image Generation with a Global-Scale Dataset and a Foundation Model | 2025 | IEEE MGRS | [DOI](https://doi.org/10.1109/MGRS.2025.3560455) | [GitHub](https://github.com/chen-yang-liu/Text2Earth) |
| ZoomLDM: Latent Diffusion Model for Multi-scale Image Generation | 2025 | CVPR | [arXiv](https://arxiv.org/abs/2411.16969) | [GitHub](https://github.com/cvlab-stonybrook/ZoomLDM) |
| MetaEarth: A Generative Foundation Model for Global-Scale Remote Sensing Image Generation | 2025 | IEEE TPAMI | [DOI](https://doi.org/10.1109/TPAMI.2024.3507010) | [GitHub](https://github.com/jiupinjia/MetaEarth) |
| RSVQ-Diffusion Model for Text-to-Remote-Sensing Image Generation | 2025 | Applied Sciences | [DOI](https://doi.org/10.3390/app15031121) | N/A |
| DiffusionSat: A Generative Foundation Model for Satellite Imagery | 2024 | ICLR | [arXiv](https://arxiv.org/abs/2312.03606) | [GitHub](https://github.com/samar-khanna/DiffusionSat) |
| RSDiff: Remote Sensing Image Generation from Text Using Diffusion Model | 2024 | Neural Computing and Applications | [DOI](https://doi.org/10.1007/s00521-024-10363-3) | N/A |


## Controllable & Structural Synthesis

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| Transferable Image Synthesis for Remote Sensing Semantic Segmentation via Joint Reference-Semantic Fusion | 2026 | Information Fusion | [DOI](https://doi.org/10.1016/j.inffus.2025.103839) | N/A |
| EarthSynth: Generating Informative Earth Observation with Diffusion Models | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2505.12108) | N/A |
| Task-Oriented Data Synthesis and Control-Rectify Sampling for Remote Sensing Semantic Segmentation | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2512.16740) | N/A |
| TerraGen: A Unified Multi-Task Layout Generation Framework for Remote Sensing Data Augmentation | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2510.21391) | N/A |
| Cascaded Autoregressive Diffusion Models for Remote Sensing Scene Generation | 2025 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2025.3622225) | N/A |
| GeoSynth: Contextually-Aware High-Resolution Satellite Image Synthesis | 2024 | CVPR | [arXiv](https://arxiv.org/abs/2403.18959) | [GitHub](https://github.com/mvrl/GeoSynth) |
| SatSynth: Augmenting Image-Mask Pairs through Diffusion Models for Aerial Semantic Segmentation | 2024 | CVPR | [arXiv](https://arxiv.org/abs/2403.16605) | N/A |
| CRS-Diff: Controllable Remote Sensing Image Generation With Diffusion Model | 2024 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2024.3453414) | [GitHub](https://github.com/Sonettoo/CRS-Diff) |


## Image-to-Image Translation & Restoration

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|

## Inpainting & Content Editing

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| ChangeBridge: Spatiotemporal Image Generation with Multimodal Controls for Remote Sensing | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2507.04678) / [DOI](https://doi.org/10.48550/arXiv.2507.04678) | N/A |
| Exploring Text-Guided Single Image Editing for Remote Sensing Images | 2025 | JSTAR | [DOI](https://doi.org/10.1109/JSTARS.2025.3584418) | N/A |
| Text2Earth: Unlocking Text-Driven Remote Sensing Image Generation with a Global-Scale Dataset and a Foundation Model | 2025 | IEEE MGRS | [DOI](https://doi.org/10.1109/MGRS.2025.3560455) | [GitHub](https://github.com/chen-yang-liu/Text2Earth) |
| DiffusionSat: A Generative Foundation Model for Satellite Imagery | 2024 | ICLR | [arXiv](https://arxiv.org/abs/2312.03606) | [GitHub](https://github.com/samar-khanna/DiffusionSat) |

## Multi-temporal & Sequence Generation

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| Generating Any Changes in the Noise Domain | 2025 | IEEE TPAMI | [DOI](https://doi.org/10.1109/TPAMI.2025.3643733) | N/A |
| ChangeDiff: A Multi-Temporal Change Detection Data Generator with Flexible Text Prompts via Diffusion Model | 2025 | AAAI | [DOI](https://doi.org/10.1609/aaai.v39i9.33058) | [GitHub](https://github.com/DZhaoXd/ChangeDiff) |
| UniTS: Unified Time Series Generative Model for Remote Sensing | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2512.04461) | [GitHub](https://github.com/YuxiangZhang-BIT/UniTS) |
| Changen2: Multi-Temporal Remote Sensing Generative Change Foundation Model | 2024 | IEEE TPAMI | [DOI](https://doi.org/10.1109/TPAMI.2024.3475824) | [GitHub](https://github.com/Z-Zheng/pytorch-change-models) |
| Scalable Multi-Temporal Remote Sensing Change Data Generation via Simulating Stochastic Change Process | 2023 | ICCV | [DOI](https://doi.org/10.1109/ICCV51070.2023.01994) | [GitHub](https://github.com/Z-Zheng/pytorch-change-models) |

## Datasets

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|
| TerraMesh: A Planetary Mosaic of Multimodal Earth Observation Data | 2025 | CVPR Workshop | [arXiv](https://arxiv.org/abs/2504.11172) | [HF](https://huggingface.co/datasets/ibm-esa-geospatial/TerraMesh) |
<!-- | TerraFM: A Scalable Foundation Model for Unified Multisensor Earth Observation | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2506.06281) | [GitHub](https://github.com/mbzuai-oryx/TerraFM) | -->
| SAR-TEXT: A Large-Scale SAR Image-Text Dataset Built with SAR-Narrator and Progressive Transfer Learning | 2025 | arXiv | [arXiv](https://arxiv.org/abs/2507.18743) | [GitHub](https://github.com/YiguoHe/SAR-TEXT) |
| MMEarth: Exploring Multi-modal Pretext Tasks for Geospatial Representation Learning | 2024 | ECCV | [DOI](https://doi.org/10.1007/978-3-031-73039-9_10) | [GitHub](https://github.com/vishalned/MMEarth-train) |
| Prithvi-EO-2.0: A Versatile Multitemporal Foundation Model for Earth Observation Applications | 2026 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2025.3642610) | [GitHub](https://github.com/NASA-IMPACT/Prithvi-EO-2.0) |
| Galileo: Learning Global & Local Features of Many Remote Sensing Modalities | 2025 | ICML | [arXiv](https://arxiv.org/abs/2502.09356) | [GitHub](https://github.com/nasaharvest/galileo) |
| EarthView: A Large Scale Remote Sensing Dataset for Self-Supervision | 2025 | WACV Workshop | [arXiv](https://arxiv.org/abs/2501.08111) | [GitHub](https://github.com/satellogic/satellogic-earthview) |
| Towards a Unified Copernicus Foundation Model for Earth Vision | 2025 | ICCV | [arXiv](https://arxiv.org/abs/2503.11849) | [GitHub](https://github.com/zhu-xlab/Copernicus-FM) |
| SARLANG-1M: A Benchmark for Vision-Language Modeling in SAR Image Understanding | 2026 | IEEE TGRS | [DOI](https://doi.org/10.1109/TGRS.2026.3652099) | [GitHub](https://github.com/jimmyxichen/SARLANG-1M) |
| OpenEarthMap: A Benchmark Dataset for Global High-Resolution Land Cover Mapping | 2023 | WACV | [DOI](https://doi.org/10.1109/WACV56688.2023.00619) | [GitHub](https://github.com/bao18/open_earth_map) |
| OpenEarthMap-SAR: A Benchmark Synthetic Aperture Radar Dataset for Global High-Resolution Land Cover Mapping | 2025 | IEEE MGRS | [DOI](https://doi.org/10.1109/MGRS.2025.3599512) | [GitHub](https://github.com/cliffbb/OpenEarthMap-SAR) |
| BRIGHT: A Globally Distributed Multimodal Building Damage Assessment Dataset with Very-High-Resolution for All-Weather Disaster Response | 2025 | Earth System Science Data | [DOI](https://doi.org/10.5194/essd-17-6217-2025) | [GitHub](https://github.com/ChenHongruixuan/BRIGHT) |


## Evaluation Metrics

| Title | Year | Venue | Paper Link | Code Link |
|-------|------|-------|------------|-----------|

## Contributing

Contributions are welcome! You can either give a pull request or create an issue.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related or neighboring rights to this work. See the [LICENSE](LICENSE) file for the full legal text.
