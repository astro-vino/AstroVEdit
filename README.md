# AstroVEdit

<div align="center">
<img width="128" height="128" alt="FullColor_Logo-Only_Round" src="https://github.com/user-attachments/assets/a0a39cab-f5c9-4d49-9e31-36c1dcf6d8bd" />


  **Professional Amateur Astronomical Image Editing Software**

  [![.NET](https://img.shields.io/badge/.NET-9.0-blue.svg)](https://dotnet.microsoft.com/)
  [![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows)
  [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE.txt)
  [![Version](https://img.shields.io/badge/version-1.0.0-orange.svg)](https://github.com/astro-vino/AstroVEdit/releases)
</div>

## Overview

AstroVEdit is a modern, professional-grade astronomical image editing application designed specifically for processing FITS (Flexible Image Transport System) files and other astronomical image formats. Built with WPF and .NET 9, it provides comprehensive tools for astrophotographers and astronomers to enhance and analyze their celestial captures with industry-standard workflows.

<img width="3383" height="2016" alt="image" src="https://github.com/user-attachments/assets/58cb0965-e9ae-4a0c-9ef7-ee1140d4f476" />

<img width="3386" height="2020" alt="image" src="https://github.com/user-attachments/assets/19969120-0505-440e-9544-4d8e37cf8921" />

## ✨ Key Features

### 🖼️ **Image Processing**
- **FITS File Support** - Native support for .fits, .fit, and .fts astronomical image formats
- **Multi-Format Support** - JPEG, PNG, TIFF, and other standard image formats
- **Non-Destructive Editing** - Professional layer-based adjustment system preserves original image data
- **Real-Time Preview** - Instant feedback for all adjustments and modifications
- **High Bit-Depth Processing** - Maintains astronomical image precision throughout editing
- **Hardware Acceleration** - Optimized rendering with intelligent caching for smooth performance

### 🎨 **Advanced Adjustment Tools**
- **Brightness & Contrast** - Fine-tune image luminosity and dynamic range
- **Color Balance** - Adjust color temperature and tint for natural-looking results
- **Levels Adjustment** - Precise control over shadows, midtones, and highlights with histogram feedback
- **Curves Adjustment** - Advanced tone mapping with customizable RGB curves
- **Hue & Saturation** - Selective color enhancement and desaturation controls
- **Selective Color** - Target specific color ranges (Reds, Yellows, Greens, Cyans, Blues, Magentas, Whites, Neutrals, Blacks) for precise CMYK adjustments

### 🌌 **Astrophotography Presets**
Professional narrowband and broadband color palettes used by the astrophotography community:

#### **Narrowband Palettes**
- **SHO (Hubble Palette)** - Classic red/orange nebula colors using Sulfur-II, Hydrogen-alpha, Oxygen-III mapping
- **HOO Natural** - Natural-looking narrowband with enhanced star colors and H-beta simulation
- **HSO Palette** - Alternative narrowband mapping for different aesthetic results
- **HOS Palette** - Hydrogen-Oxygen-Sulfur combination for unique color rendition
- **Dynamic SHO** - Enhanced SHO with improved star color handling

#### **Broadband & Artistic Palettes**
- **Realistic 1 & 2** - Natural color enhancement for broadband RGB images
- **Foraxx Palette** - Popular warm-toned palette with enhanced oranges and gold tones
- **Teal & Orange** - Cinematic color grading adapted for astrophotography

### 🔧 **Professional Features**
- **Layer Management System** - Organize adjustments in a professional layer stack with show/hide controls
- **Layer Visibility Toggle** - Individual layer on/off controls for comparison and fine-tuning
- **Read-Only Layers** - Special layers (like GraXpert processing) that preserve workflow integrity
- **Channel Control** - Individual RGB composite channel visibility and manipulation
- **Histogram Analysis** - Real-time RGB histogram display for exposure analysis
- **Crop Tool** - Precise image cropping with visual guides
- **FITS Header Viewer** - Examine astronomical metadata and capture information
- **Undo/Redo System** - Comprehensive 20-level undo history for all operations
- **Recent Files** - Quick access to the last 5 opened images with automatic cleanup

### 🔌 **Plugin System**

#### **GraXpert Integration**
Professional integration with GraXpert for advanced background extraction and denoising:

- **Background Extraction**
  - Subtraction and Division correction methods
  - Smoothing control (0-1 range)
  - AI model selection for optimal results
  - Background model saving capability

- **AI-Powered Denoising**
  - Strength control (0.01-1.00 range)
  - Batch size optimization (1-32)
  - Multiple AI model options
  - GPU acceleration support

- **Professional Workflow**
  - Auto-detection of GraXpert installation
  - Creates non-destructive "GraXpert" layers
  - Preserves original image data
  - Temporary file cleanup
  - Command-line interface for batch processing

- **PixInsight-Style Interface**
  - Professional dialog matching AstroVEdit's dark theme
  - Export/Import settings capability
  - Progress feedback during processing
  - Error handling with user prompts

### 🎯 **User Experience**
- **Modern Dark Theme** - Eye-friendly interface optimized for long editing sessions
- **Material Design UI** - Clean, intuitive interface following modern design principles
- **Professional Splash Screen** - Visual feedback during application startup with animated loading indicators
- **Customizable Workspace** - Flexible panel layout for personalized workflow
- **Keyboard Shortcuts** - Efficient navigation and tool access
- **Professional Tooltips** - Contextual help throughout the application
- **Performance Optimized** - Intelligent rendering cache with hash-based change detection

## 🚀 Getting Started

### System Requirements
- **Operating System:** Windows 10/11 (64-bit)
- **Framework:** .NET 9.0 Runtime
- **Memory:** 4 GB RAM minimum, 8 GB recommended for large FITS files
- **Storage:** 500 MB available space
- **Graphics:** DirectX 11 compatible graphics card (recommended for hardware acceleration)
- **Optional:** GraXpert installation for plugin functionality

### Installation
#### Windows Installer 
1. Download the latest `AstroVEdit-1.0.0-Setup.exe` from [Releases](https://github.com/astro-vino/AstroVEdit/releases)
2. Run the installer as Administrator
3. Follow the installation wizard
4. Launch AstroVEdit from Start Menu or Desktop shortcut

#### GraXpert Plugin Setup (Optional)
1. Download and install [GraXpert](https://github.com/Steffenhir/GraXpert) from the official repository
2. AstroVEdit will auto-detect GraXpert in common installation paths:
   - `%LocalAppData%\Programs\GraXpert`
   - `C:\Program Files\GraXpert`
   - `C:\Program Files (x86)\GraXpert`
3. If not found automatically, you'll be prompted to locate the GraXpert executable

### Quick Start Guide

#### Basic Workflow
1. **Open an Image**: File → Open or drag-and-drop a FITS file
2. **Add Adjustments**: Use the Adjustments panel to add enhancement layers
3. **Apply Presets**: Try astrophotography presets for quick professional results
4. **Fine-tune Settings**: Click the gear icon next to any adjustment to modify parameters
5. **Layer Management**: Use show/hide toggles to compare before/after results
6. **Monitor Changes**: Watch the real-time histogram and preview updates
7. **Save Your Work**: File → Save to preserve your edited image

#### Astrophotography Workflow
1. **Load Your Image**: Open FITS, TIFF, or other astronomical image formats
2. **Apply Narrowband Preset**: Choose SHO, HOO, or other palettes for instant color grading
3. **Fine-tune with Layers**: Add Levels, Curves, or Color Balance adjustments
4. **Use GraXpert Plugin**: Apply background extraction or denoising as separate layers
5. **Compare Results**: Toggle layer visibility to compare original vs processed versions
6. **Export Final Image**: Save in your preferred format with all adjustments applied

<img width="3383" height="2018" alt="image" src="https://github.com/user-attachments/assets/69c03d51-20df-4d7e-bea3-0c6e925acc36" />

<img width="3386" height="2019" alt="image" src="https://github.com/user-attachments/assets/2eba8975-9ab7-4a9b-b15c-2b07636827d3" />

<img width="3383" height="2018" alt="image" src="https://github.com/user-attachments/assets/728aa30f-199c-4484-9d06-3d8499abe989" />

## 🛠️ Development

### Technology Stack
- **Framework:** .NET 9.0 with WPF
- **UI Library:** Material Design in XAML Toolkit
- **Plotting:** ScottPlot.WPF for histogram visualization
- **FITS Support:** CSharpFITS library for astronomical image handling
- **Architecture:** MVVM pattern with layer-based image processing
- **Performance:** Hardware-accelerated rendering with intelligent caching

### Dependencies
- **MaterialDesignThemes** - Modern UI components and theming
- **ScottPlot.WPF** - Real-time plotting and histogram display
- **CSharpFITS** - FITS file format support and metadata handling
- **System.Text.Json** - Settings and recent files persistence

### Key Components
- **LayerManager** - Professional layer system with caching and performance optimization
- **AdjustmentLayers** - Non-destructive editing with real-time preview
- **AstroPaletteProcessor** - Authentic narrowband channel combination engine
- **GraXpertDialog** - Professional plugin integration interface
- **RecentFilesManager** - Persistent recent files with automatic cleanup

## 📋 Roadmap

### Recently Completed ✅
- [x] **GraXpert Plugin Integration** - Professional background extraction and denoising
- [x] **Astrophotography Presets** - Complete narrowband and broadband palette system
- [x] **Layer System Enhancement** - Show/hide controls and read-only layer support
- [x] **Performance Optimization** - Hardware acceleration and intelligent caching
- [x] **Recent Files System** - Quick access to recently opened images
- [x] **Comprehensive Undo/Redo** - 20-level operation history
- [x] **Professional Splash Screen** - Startup feedback with animated indicators

### Considered Features
- [ ] **Star Analysis Tools** - Automated star detection and FWHM measurement
- [ ] **Advanced Stacking** - Built-in image stacking capabilities

### Long-term Goals
- [ ] **AI Enhancement** - Machine learning-powered image enhancement
- [ ] **Plate Solving Integration** - Automatic astrometric calibration
- [ ] **Photometry Tools** - Stellar magnitude measurement capabilities

## 📚 Documentation
- [User Manual](docs/user-manual.md) *(Coming Soon)*
- [Plugin Development Guide](docs/plugin-development.md) *(Coming Soon)*
- [Astrophotography Workflow Guide](docs/astro-workflow.md) *(Coming Soon)*

## 🐛 Bug Reports & Feature Requests
Found a bug or have a feature request? Please create an issue on our [GitHub Issues](https://github.com/astro-vino/AstroVEdit/issues) page.

**When reporting bugs, please include:**
- Operating system and version
- .NET version
- Steps to reproduce the issue
- Expected vs actual behavior
- Sample FITS file (if applicable)
- GraXpert version (if using plugin features)

## 📄 License
This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## 🙏 Acknowledgments
- **CSharpFITS Team** - For excellent FITS file format support
- **Material Design Team** - For beautiful, modern UI components
- **ScottPlot Contributors** - For powerful plotting capabilities
- **GraXpert Team** - For outstanding background extraction and denoising tools
- **Astronomical Community** - For feedback, feature suggestions, and palette contributions
- **PixInsight Team** - For inspiration in professional astronomical image processing workflows

## 📞 Contact
- **Project Homepage:** [https://github.com/astro-vino/AstroVEdit](https://github.com/astro-vino/AstroVEdit)
- **Issues & Support:** [GitHub Issues](https://github.com/astro-vino/AstroVEdit/issues)
- **Discussions:** [GitHub Discussions](https://github.com/astro-vino/AstroVEdit/discussions)

---

<div align="center">
  <strong>Made with ❤️ for the astronomical imaging community</strong><br>
  <em>Professional tools for amateur astronomers</em>
</div>
