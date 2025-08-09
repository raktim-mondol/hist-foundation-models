
Here is the filtered table showing only **Histopathology Image Feature Extraction Models** (excluding vision-language and generative models):


| Model Name | Hugging Face Link | Embedding Size | Parameters (M) | Architecture | Training Images | Training Algorithm | Organization | Key Task | Year |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| **Atlas** | Not publicly available | 1024 | 304.0 | RudolfV-based | 1.2M WSIs | RudolfV approach | Mayo Clinic + Charite + Aignostics | Enhanced RudolfV model | **2025** |
| **H-optimus-1** | https://huggingface.co/bioptimus/H-optimus-1 | 1536 | 1135.0 | ViT-G/14 | 1M+ WSIs from 800K+ patients | DINOv2 | Bioptimus | Advanced pathology foundation model | **2025** |
| **UNI2-h** | https://huggingface.co/MahmoodLab/UNI2-h | 1536 | 681.0 | ViT-H/14 | 200M patches from 350K H\&E+IHC WSIs | DINOv2 | Mahmood Lab | Enhanced general-purpose pathology | **2025** |
| **EXAONE Path 2.0** | https://huggingface.co/LGAI-EXAONE/EXAONE-Path-2.0 | 1024 | 300.0 | Vision Transformer | 37K WSIs | Direct slide-level supervision | LG AI Research | Biomarker prediction with limited data | **2024** |
| **H-optimus-0** | https://huggingface.co/bioptimus/H-optimus-0 | 1536 | 1135.0 | ViT-G/14 | Several hundred million images from 500K slides | DINOv2 | Bioptimus | Large-scale pathology diagnostics | **2024** |
| **Prov-GigaPath** | https://huggingface.co/prov-gigapath/prov-gigapath | 1536 | 1135.0 | ViT-G/14 + LongNet | 1.3B tiles from 171K WSIs | DINOv2 + LongNet | Microsoft + Providence | Whole-slide gigapixel analysis | **2024** |
| **RudolfV** | Not publicly available | 1024 | 304.0 | ViT-L/16 | 1.2M patches from 134K WSIs | DINOv2 + pathologist curation | Mayo Clinic + Charite + Aignostics | Pathologist-guided foundation model | **2024** |
| **UNI** | https://huggingface.co/MahmoodLab/UNI | 1024 | 303.0 | ViT-L/16 | 100M patches from 100K WSIs | DINOv2 | Mahmood Lab | General-purpose pathology foundation | **2024** |
| **Virchow** | https://huggingface.co/paige-ai/Virchow | 2560 | 632.0 | ViT-H/14 | 1.5M WSIs | DINOv2 | Paige.ai | H\&E histopathology foundation model | **2024** |
| **Virchow2** | https://huggingface.co/paige-ai/Virchow2 | 2560 | 632.0 | ViT-H/14 | 3.1M H\&E + 400K IHC WSIs | DINOv2 | Paige.ai | Multi-scale H\&E + IHC foundation model | **2024** |
| **Path Foundation** | https://huggingface.co/google/path-foundation | 384 | 90.0 | ViT-S/16 | Large H\&E dataset | Masked Siamese Networks | Google | H\&E patch feature extraction | **2023** |
| **PathoDuet** | https://github.com/openmedlab/PathoDuet | 768 | 86.0 | ViT-B/16 | H\&E and IHC datasets | Cross-scale positioning + cross-stain transfer | OpenMEDLab | H\&E and IHC stain analysis | **2023** |
| **CTransPath** | https://github.com/Xiyue-Wang/TransPath | 768 | 28.0 | Hybrid CNN-Transformer | 15M patches from 30K WSIs | SRCL (Semantically-Relevant Contrastive Learning) | Academic | CNN-Transformer hybrid for pathology | **2022** |

## Summary for Image Feature Extraction Models:

**By Year:**

- **2025**: 3 models (latest generation)
- **2024**: 9 models (breakthrough year)
- **2023**: 2 models (early development)
- **2022**: 1 model (pioneering work)

**Key Statistics:**

- **Total Models**: 15 pure image feature extraction models
- **Parameter Range**: 21.6M - 1.9B parameters
- **Embedding Size Range**: 384 - 6,144 dimensions

**Architecture Distribution:**

- **ViT-G/14**: 3 models (largest scale)
- **ViT-H/14**: 3 models (high performance)
- **ViT-L/16**: 2 models (balanced performance)
- **Other architectures**: 7 models (specialized approaches)



