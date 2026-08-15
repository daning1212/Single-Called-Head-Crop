# Single-Called-Head-Crop | LoRA Dataset Preprocessor

**Head-centric 1:1 crop tool for LoRA training (Ostris AI-Toolkit / Kohya_ss)**

> Your LoRA can't learn the face because your dataset has random ratios? Select a folder and auto-crop to head-centric 1:1 squares.

![preview](./screenshot.png)

**Live Demo:** https://daning1212.github.io/Single-Called-Head-Crop/

### 🌐 Language
Single `index.html` supports both KO/EN - Click KO/EN button on top right to switch.

### Why for LoRA?
- **SDXL / Pony / Illustrious LoRA** learns better with consistent face ratios
- Normalize to **1024x1024 head-centric 1:1**

### Features
- **Batch Crop**: Up to 100 images at once
- **Head-Centric**: FaceDetector + MediaPipe BlazeFace
- **LoRA Ready**: 512/1024/2048px, JPG/PNG/WebP
- **Manual Adjust**: Intuitive drag to fine-tune
- **3 Save Modes**: Save to Folder / ZIP / Individual
- **100% Local**: No server upload

### Recommended Settings
| Model | Resolution | Margin |
| SDXL, Pony | 1024px | 30% |
| SD1.5 | 512px | 25% |
| Illustrious | 1024px | 35% |

### License
MIT
