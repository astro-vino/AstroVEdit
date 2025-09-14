# AstroVEdit

<div align="center">
<img width="389" height="387" alt="FullColor_Logo-Only_Round" src="https://github.com/user-attachments/assets/a0a39cab-f5c9-4d49-9e31-36c1dcf6d8bd" />

  
  **Amateur Astronomical Image Editing Software**
  
  [![.NET](https://img.shields.io/badge/.NET-9.0-blue.svg)](https://dotnet.microsoft.com/)
  [![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows)
  [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE.txt)
  [![Version](https://img.shields.io/badge/version-1.0.0-orange.svg)](https://github.com/observatory-software/astrovEdit/releases)
</div>

## Overview

AstroVEdit is a modern astronomical image editing application designed specifically for processing FITS (Flexible Image Transport System) files and other astronomical image formats. Built with WPF and .NET 9, it provides professional-grade tools for astrophotographers and astronomers to enhance and analyze their celestial captures.

## ✨ Key Features

### 🖼️ **Image Processing**
- **FITS File Support** - Native support for .fits, .fit, and .fts astronomical image formats
- **Non-Destructive Editing** - Layer-based adjustment system preserves original image data
- **Real-Time Preview** - Instant feedback for all adjustments and modifications
- **High Bit-Depth Processing** - Maintains astronomical image precision throughout editing

### 🎨 **Adjustment Tools**
- **Brightness & Contrast** - Fine-tune image luminosity and dynamic range
- **Color Balance** - Adjust color temperature and tint for natural-looking results
- **Levels Adjustment** - Precise control over shadows, midtones, and highlights
- **Curves Adjustment** - Advanced tone mapping with customizable curves
- **Hue & Saturation** - Selective color enhancement and desaturation
- **Selective Color** - Target specific color ranges for precise adjustments

### 🔧 **Features**
- **Layer Management** - Organize adjustments in a professional layer stack
- **Channel Control** - Individual RGB composite channel visibility and manipulation
- **Histogram Analysis** - Real-time histogram display for exposure analysis
- **Crop Tool** - Precise image cropping with visual guides
- **FITS Header Viewer** - Examine astronomical metadata and capture information
- **Preset Adjustments** - Quick-apply presets for common enhancement workflows

### 🎯 **User Experience**
- **Modern Dark Theme** - Eye-friendly interface optimized for long editing sessions
- **Material Design UI** - Clean, intuitive interface following modern design principles
- **Customizable Workspace** - Flexible panel layout for personalized workflow
- **Keyboard Shortcuts** - Efficient navigation and tool access
- **Professional Tooltips** - Contextual help throughout the application

## 🚀 Getting Started

### System Requirements

- **Operating System:** Windows 10/11 (64-bit)
- **Framework:** .NET 9.0 Runtime
- **Memory:** 4 GB RAM minimum, 8 GB recommended
- **Storage:** 500 MB available space
- **Graphics:** DirectX 11 compatible graphics card

### Installation

#### Windows Installer 
1. Download the latest `AstroVEdit-1.0.0-Setup.exe` from [Releases](https://github.com/observatory-software/astrovEdit/releases)
2. Run the installer as Administrator
3. Follow the installation wizard
4. Launch AstroVEdit from Start Menu or Desktop shortcut

### Quick Start Guide

1. **Open an Image**: File → Open or drag-and-drop a FITS file
2. **Add Adjustments**: Use the Adjustments panel to add enhancement layers
3. **Fine-tune Settings**: Click the gear icon next to any adjustment to modify parameters
4. **Monitor Changes**: Watch the real-time histogram and preview updates
5. **Save Your Work**: File → Save to preserve your edited image

## 🛠️ Development

### Technology Stack

- **Framework:** .NET 9.0 with WPF
- **UI Library:** Material Design in XAML Toolkit
- **Plotting:** ScottPlot.WPF for histogram visualization
- **FITS Support:** CSharpFITS library for astronomical image handling
- **Architecture:** MVVM pattern with layer-based image processing

### Project Structure

```
AstroVEdit/
├── MainWindow.xaml(.cs)          # Main application window and logic
├── Layer.cs                      # Base layer and ImageLayer classes
├── LayerManager.cs               # Layer stack management
├── AdjustmentLayer.cs            # Base class for all adjustments
├── Channel.cs                    # RGB channel representation
├── *AdjustmentDialog.xaml(.cs)   # Individual adjustment tool dialogs
├── AboutDialog.xaml(.cs)         # Application information dialog
├── BoolToEyeIconConverter.cs     # UI converters and utilities
├── CropTool.cs                   # Image cropping functionality
├── ConvertStretchedToRawData.cs  # Data conversion utilities
├── FitsHeaderCard.cs             # FITS metadata handling
├── FitsHeaderWindow.xaml(.cs)    # FITS header viewer
├── assets/                       # Application icons and resources
└── nsis installer/               # Windows installer configuration
```

### Dependencies

- **MaterialDesignThemes** - Modern UI components and theming
- **ScottPlot.WPF** - Real-time plotting and histogram display
- **CSharpFITS** - FITS file format support and metadata handling

## 📸 Screenshots

*Coming soon - Screenshots will be added to showcase the application interface and features.*

## 📋 Roadmap

### Upcoming Features
- [ ] **Plugin System** - Extensible architecture for custom tools
- [ ] **Noise Reduction** - Specialized astronomical noise reduction algorithms
- [ ] **Star Analysis** - Automated star detection and analysis tools

### Long-term Goals
- [ ] **AI Enhancement** - Machine learning-powered image enhancement

## 📚 Documentation

- [User Manual](docs/user-manual.md) *(Coming Soon)*

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature request? Please create an issue on our [GitHub Issues](https://github.com/observatory-software/astrovEdit/issues) page.

**When reporting bugs, please include:**
- Operating system and version
- .NET version
- Steps to reproduce the issue
- Expected vs actual behavior
- Sample FITS file (if applicable)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## 🙏 Acknowledgments

- **CSharpFITS Team** - For excellent FITS file format support
- **Material Design Team** - For beautiful, modern UI components
- **ScottPlot Contributors** - For powerful plotting capabilities
- **Astronomical Community** - For feedback and feature suggestions

## 📞 Contact

- **Project Homepage:** [https://github.com/observatory-software/astrovEdit](https://github.com/observatory-software/astrovEdit)
- **Issues & Support:** [GitHub Issues](https://github.com/observatory-software/astrovEdit/issues)
- **Discussions:** [GitHub Discussions](https://github.com/observatory-software/astrovEdit/discussions)

---

<div align="center">
  <strong>Made with ❤️ for the astronomical imaging community</strong>
</div>
