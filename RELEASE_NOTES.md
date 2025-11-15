# AI Product Studio v1.0 - Release Notes

**Release Date**: November 15, 2025  
**Platform**: Windows 10/11 (64-bit)

---

## 🎉 First Official Release!

AI Product Studio v1.0 is a complete, professional-grade product photography enhancement tool with cutting-edge AI capabilities.

---

## ✨ Key Features

### 🤖 AI Background Removal
- **14 AI Models**: U²-Net, BiRefNet, SAM, ISNET, SILUETA, and more
- **GPU Acceleration**: Automatic CUDA/DirectML detection
- **Batch Processing**: Process multiple images in parallel
- **Edge Refinement**: Alpha matting, edge softness, uncertainty detection

### 🌑 Professional Shadow System
- **Drop Shadow**: Amazon-style e-commerce shadows with gap control
- **Natural Shadow**: Realistic directional lighting (360° control)
- **Reflection Shadow**: Mirror effects with fade control
- **Real-time Preview**: 300ms debouncing for smooth adjustments
- **Profile System**: 5 presets per shadow type

### 🖼️ Background Management
- **Transparent**: Maintain alpha channel
- **Solid Colors**: Custom colors + 5 presets
- **Image Backgrounds**: Upload custom images with 4 fit modes

### 🎯 Transform & Positioning
- **Scale**: 1% - 2000% (20x zoom)
- **Position**: Precise X/Y control (-5000 to +5000)
- **Rotation**: -180° to +180°
- **Profile System**: 5 transform presets

### 🎨 Image Adjustments
- Brightness, Contrast, Saturation, Sharpness, Blur
- Real-time preview for all adjustments

### 💾 Export & Batch
- **Formats**: PNG, JPG, WEBP, BMP, TIFF
- **Quality Control**: Adjustable compression
- **Batch Export**: Process entire folders with progress tracking
- **Auto-save**: Automatic batch export

---

## 📦 Distribution

### Standalone Executable
- **Size**: 364 MB (compressed), ~800 MB (extracted)
- **No Installation Required**: Extract and run
- **All Dependencies Included**: PyQt6, ONNX Runtime, OpenCV, NumPy, etc.
- **Models**: Auto-downloaded on first use (~200-500MB)

### System Requirements

**Minimum**:
- Windows 10/11 (64-bit)
- 8GB RAM
- 2GB free storage
- Intel Core i5 or equivalent

**Recommended**:
- 16GB+ RAM
- NVIDIA GPU with CUDA
- SSD with 5GB+ free space

---

## 🚀 What's New in v1.0

### Core Features
✅ Complete AI background removal system
✅ 14 state-of-the-art AI models
✅ Professional 3-type shadow system
✅ Background image/color management
✅ Transform with profile presets
✅ Batch processing with GPU acceleration

### Performance
✅ Vectorized numpy operations (100x faster shadows)
✅ Debouncing system (no UI lag)
✅ GPU acceleration auto-detection
✅ Memory management (max 8192px auto-resize)
✅ Multi-core parallel processing

### UI/UX
✅ Dark theme interface
✅ Drag & drop support
✅ Real-time preview
✅ Processing indicators
✅ Undo/Redo (20 levels)
✅ Keyboard shortcuts

### Data Persistence
✅ SQLite profile database
✅ Shadow presets per type
✅ Transform presets
✅ Settings persist across sessions

---

## 🐛 Known Issues

- Very large images (>8192px) are automatically resized
- First run requires model downloads (internet needed)
- Some complex transparent objects (glass, hair) may need manual refinement
- Windows Defender may flag first run (safe to allow)

---

## 📝 Technical Details

### Built With
- **Python**: 3.11
- **GUI**: PyQt6 6.10.0
- **AI**: ONNX Runtime 1.17.1
- **Image Processing**: Pillow, OpenCV, NumPy, SciPy
- **Packager**: PyInstaller 6.16.0

### Architecture
- PyQt6 modern responsive UI
- ONNX Runtime with GPU acceleration
- SQLite for profile persistence
- ThreadPoolExecutor for parallel processing

---

## 📄 License

**MIT License** - Free for personal and commercial use

Copyright (c) 2025 Dinu-Sri

---

## 🙏 Credits

- **rembg**: Background removal library
- **ONNX Runtime**: GPU-accelerated AI inference
- **PyQt6**: GUI framework
- **U²-Net, BiRefNet, SAM**: State-of-the-art AI models

---

## 📧 Support & Contact

- **GitHub**: https://github.com/Dinu-Sri/ai-product-studio
- **Issues**: https://github.com/Dinu-Sri/ai-product-studio/issues
- **Author**: [@Dinu-Sri](https://github.com/Dinu-Sri)

---

## 🔄 Update Notes

This is the first official release. Future updates will be posted on GitHub.

To check for updates:
1. Visit: https://github.com/Dinu-Sri/ai-product-studio/releases
2. Download the latest version
3. Extract and replace old files

---

## ⭐ Show Support

If you find this tool useful:
- ⭐ Star the GitHub repository
- 🐛 Report bugs and issues
- 💡 Suggest new features
- 🔗 Share with others

---

**Built with ❤️ by Dinu-Sri**

*Making professional product photography accessible to everyone.*
