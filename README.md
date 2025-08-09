<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" style="height:64px;margin-right:32px"/>

# Show in a table.

Here is the comprehensive table of **Histopathology Foundation Models** available for feature extraction:


| Model Name | Hugging Face Link | Embedding Size | Parameters (M) | Architecture | Training Images | Training Algorithm | Organization | Key Task | Year |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| **Virchow** | https://huggingface.co/paige-ai/Virchow | 2560 | 632.0 | ViT-H/14 | 1.5M WSIs | DINOv2 | Paige.ai | H\&E histopathology foundation model | 2024 |
| **Virchow2** | https://huggingface.co/paige-ai/Virchow2 | 2560 | 632.0 | ViT-H/14 | 3.1M H\&E + 400K IHC WSIs | DINOv2 | Paige.ai | Multi-scale H\&E + IHC foundation model | 2024 |
| **Virchow2G** | https://huggingface.co/paige-ai/Virchow2G | 6144 | 1900.0 | ViT-G/14 | 3.1M H\&E + 400K IHC WSIs | DINOv2 | Paige.ai | Large-scale pathology AI | 2024 |
| **Virchow2G-Mini** | https://huggingface.co/paige-ai/Virchow2G-Mini | 768 | 21.6 | ViT-S/14 (distilled) | 3.1M H\&E + 400K IHC WSIs | DINOv2 + distillation | Paige.ai | Lightweight pathology model | 2024 |
| **UNI** | https://huggingface.co/MahmoodLab/UNI | 1024 | 303.0 | ViT-L/16 | 100M patches from 100K WSIs | DINOv2 | Mahmood Lab | General-purpose pathology foundation | 2024 |
| **UNI2-h** | https://huggingface.co/MahmoodLab/UNI2-h | 1536 | 681.0 | ViT-H/14 | 200M patches from 350K H\&E+IHC WSIs | DINOv2 | Mahmood Lab | Enhanced general-purpose pathology | 2025 |
| **CONCH** | https://huggingface.co/MahmoodLab/CONCH | 768 | 200.0 | ViT-B/16 + Text Encoder | 1.17M image-caption pairs | Contrastive learning | Mahmood Lab | Vision-language pathology model | 2024 |
| **Prov-GigaPath** | https://huggingface.co/prov-gigapath/prov-gigapath | 1536 | 1135.0 | ViT-G/14 + LongNet | 1.3B tiles from 171K WSIs | DINOv2 + LongNet | Microsoft + Providence | Whole-slide gigapixel analysis | 2024 |
| **Path Foundation** | https://huggingface.co/google/path-foundation | 384 | 90.0 | ViT-S/16 | Large H\&E dataset | Masked Siamese Networks | Google | H\&E patch feature extraction | 2023 |
| **CTransPath** | https://github.com/Xiyue-Wang/TransPath | 768 | 28.0 | Hybrid CNN-Transformer | 15M patches from 30K WSIs | SRCL (Semantically-Relevant Contrastive Learning) | Academic | CNN-Transformer hybrid for pathology | 2022 |
| **H-optimus-0** | https://huggingface.co/bioptimus/H-optimus-0 | 1536 | 1135.0 | ViT-G/14 | Several hundred million images from 500K slides | DINOv2 | Bioptimus | Large-scale pathology diagnostics | 2024 |
| **H-optimus-1** | https://huggingface.co/bioptimus/H-optimus-1 | 1536 | 1135.0 | ViT-G/14 | 1M+ WSIs from 800K+ patients | DINOv2 | Bioptimus | Advanced pathology foundation model | 2025 |
| **PRISM** | https://huggingface.co/paige-ai/Prism | 1280 | 558.0 | Perceiver + BioGPT | 587K WSIs + 195K reports | CoCa (Contrastive Captioning) | Paige.ai + Microsoft | Slide-level analysis + report generation | 2024 |
| **TITAN** | https://huggingface.co/MahmoodLab/TITAN | 1024 | 300.0 | Transformer + Vision-Language | 335K WSIs + 423K synthetic captions | SSL + Vision-Language alignment | Mahmood Lab | Multimodal whole-slide foundation model | 2024 |
| **RudolfV** | Not publicly available | 1024 | 304.0 | ViT-L/16 | 1.2M patches from 134K WSIs | DINOv2 + pathologist curation | Mayo Clinic + Charite + Aignostics | Pathologist-guided foundation model | 2024 |
| **Atlas** | Not publicly available | 1024 | 304.0 | RudolfV-based | 1.2M WSIs | RudolfV approach | Mayo Clinic + Charite + Aignostics | Enhanced RudolfV model | 2025 |
| **PathoDuet** | https://github.com/openmedlab/PathoDuet | 768 | 86.0 | ViT-B/16 | H\&E and IHC datasets | Cross-scale positioning + cross-stain transfer | OpenMEDLab | H\&E and IHC stain analysis | 2023 |
| **PLIP** | https://github.com/PathologyFoundation/plip | 768 | 149.0 | CLIP-based (ViT-B/32 + Text) | Twitter pathology image-text pairs | Contrastive learning (CLIP) | PathologyFoundation | Vision-language pathology model | 2023 |
| **BiomedCLIP** | https://huggingface.co/microsoft/BiomedCLIP-PubMedBERT_256-vit_base_patch16_224 | 768 | 200.0 | ViT-B/16 + PubMedBERT | 15M biomedical image-text pairs | Contrastive learning | Microsoft | General biomedical vision-language model | 2024 |
| **PixCell** | https://huggingface.co/papers/2506.05127 | Generative | 500.0 | Diffusion model | 69K WSIs (PanCan-30M) | Diffusion-based generation | Academic | Generative histopathology foundation model | 2025 |
| **EXAONE Path 2.0** | https://huggingface.co/LGAI-EXAONE/EXAONE-Path-2.0 | 1024 | 300.0 | Vision Transformer | 37K WSIs | Direct slide-level supervision | LG AI Research | Biomarker prediction with limited data | 2024 |

## Key Statistics:

- **Total Models**: 21 foundation models
- **Parameter Range**: 21.6M - 1.9B parameters
- **Embedding Size Range**: 384 - 6,144 dimensions
- **Organizations**: 12 different organizations represented
- **Years**: Models released from 2022-2025
- **Most Common Architecture**: Vision Transformer (ViT) variants
- **Dominant Training Algorithm**: DINOv2 (used by 7 models)

The table shows the rapid evolution and scaling of histopathology foundation models, with the largest models like **Virchow2G** (1.9B parameters) and **Prov-GigaPath** (1.135B parameters) representing state-of-the-art capabilities for feature extraction from histopathological images.

