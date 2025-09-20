# AstroVEdit

<div align="center">
<img width="128" height="128" alt="FullColor_Logo-Only_Round" src="https://github.com/user-attachments/assets/a0a39cab-f5c9-4d49-9e31-36c1dcf6d8bd" />


  **Astronomical Image Editing Software**

  [![.NET](https://img.shields.io/badge/.NET-9.0-blue.svg)](https://dotnet.microsoft.com/)
  [![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows)
  [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE.txt)
  [![Version](https://img.shields.io/badge/version-1.1.0-orange.svg)](https://github.com/astro-vino/AstroVEdit/releases)
</div>

## Overview

AstroVEdit is an astronomical image editing application designed specifically for processing FITS (Flexible Image Transport System) files and other astronomical image formats. Built with WPF and .NET 9, it provides comprehensive tools for astrophotographers and astronomers to enhance and analyze their celestial captures with industry-standard workflows and performance optimizations.

Featuring a complete suite of adjustment layers, advanced plugin integrations, and specialized astrophotography tools, AstroVEdit delivers high-quality processing with an intuitive, modern interface designed for amateur astronomers and astrophotographers.

<img width="3047" height="2038" alt="image" src="https://github.com/user-attachments/assets/263f7e7d-6c69-4d7e-b222-c7d1da366d77" />


## 🆕 What's New in v1.1.0

### ⚡ **Performance Revolution**
- **Ultra-Fast Slider Response** - Eliminated lag with lookup table optimization and fast preview mode
- **Real-Time Preview System** - Reduced resolution rendering during adjustments with visual feedback indicator
- **Intelligent Performance Scaling** - Adaptive update intervals based on layer complexity
- **Visual Feedback** - Orange "FAST PREVIEW" indicator shows when optimized rendering is active

### 🎭 **Layer Masks**
- **Luminosity Mask Creation** - Automatically generate masks from current viewport using standard luminance formula
- **Advanced Mask Controls** - Levels adjustment (Input Black, Input White, Gamma) for precise mask contrast
- **Gaussian Blur Processing** - Smooth mask edges with 0-20 pixel radius blur for natural transitions
- **Real-Time Preview** - Ultra-fast mask preview with 1/4 resolution processing during adjustments
- **Mask Operations** - Copy, paste, and delete masks between layers with right-click context menus
- **Visual Feedback** - Optional red overlay to visualize mask areas on the main viewport
- **Performance Optimized** - Intelligent caching and fast preview mode for smooth editing experience

<img width="3043" height="2038" alt="image" src="https://github.com/user-attachments/assets/8ff517d2-28ac-4de3-adc1-04748a23e3fb" />


### 🌟 **Star Analysis Tools**
- **Star Detection** - Advanced algorithms with Gaussian smoothing and local maxima detection
- **FWHM Measurement** - Sub-pixel accuracy for focus quality assessment with radial profile analysis
- **Quality Scoring** - Comprehensive star quality metrics based on SNR, FWHM, and roundness
- **Statistical Analysis** - Real-time focus quality calculation and CSV export capabilities
- **Configurable Detection** - Adjustable SNR thresholds, FWHM limits, and detection sensitivity
- **Interactive Selection** - Click stars on image to select them in analysis dialog
- **Zoom/Pan Integration** - Non-modal dialog allows main window navigation during analysis

<img width="3046" height="2036" alt="image" src="https://github.com/user-attachments/assets/e2f1fa0a-d3f8-410a-aa62-6cfa1318dcb1" />


### 🔧 **Advanced Processing Tools**
- **Star Reduction** - Star size reduction with 4 methods (Transfer, Halo, Star, Lightness)
- **Add Stars** - Professional star blending with multiple blend modes, opacity control, and star enhancement options
- **Remove Magenta** - Comprehensive magenta cast removal with 5 algorithms
- **SCNR (Subtractive Chromatic Noise Reduction)** - Color noise reduction with 5 protection methods
- **StarNet Integration** - Complete StarNet plugin with layer-based workflow for star removal and mask generation
- **GraXpert Integration** - Background extraction and AI denoising with layer-based output

<img width="3045" height="2039" alt="image" src="https://github.com/user-attachments/assets/e367e84f-e2a6-4300-8b7a-7b4248173f05" />


### 🎨 **Enhanced User Interface**
- **Modern Material Design** - Consistent styling across all dialogs with dark theme
- **Orange Signature Highlighting** - Custom menu highlighting with the signature orange color
- **Improved About Dialog** - Comprehensive feature documentation with scrollable content
- **Enhanced Recent Files** - Right-expanding submenu with file type icons and "More..." option
- **Custom Dialog System** - Styled dialogs replacing standard Windows MessageBox
- **Responsive Layout** - All dialogs properly sized and scrollable for different screen resolutions

## ✨ Key Features

### 🖼️ **Image Processing**
- **FITS File Support** - Native support for .fits, .fit, and .fts astronomical image formats
- **Multi-Format Support** - JPEG, PNG, TIFF, and other standard image formats
- **Non-Destructive Editing** - Layer-based adjustment system preserves original image data
- **Real-Time Preview** - Instant feedback for all adjustments and modifications
- **High Bit-Depth Processing** - Maintains astronomical image precision throughout editing
- **Hardware Acceleration** - Optimized rendering with intelligent caching for smooth performance

### 🎨 **Advanced Adjustment Tools**
All adjustment tools now feature **ultra-responsive sliders** with real-time fast preview mode:

- **Levels Adjustment** - Optimized gamma correction with lookup tables for instant response
- **Curves Adjustment** - Advanced tone mapping with Bézier interpolation and fast preview during editing
- **Brightness & Contrast** - Fine-tune image luminosity with immediate visual feedback
- **Color Balance** - Adjust Cyan-Red, Magenta-Green, Yellow-Blue with presets
- **Hue & Saturation** - Selective color enhancement with real-time preview
- **Selective Color** - Target specific color ranges (CMYK) with fast slider response and astrophotography presets

#### **Add Stars Layer**
Professional star re-addition tool for astrophotography workflows:

- **Star Image Selection** - Browse for star images with intelligent folder detection (starts in original image folder)
- **Multiple Blend Modes** - Screen, Linear Dodge, Lighten, Color Dodge, Soft Light, Overlay, Normal for different star effects
- **Opacity Control** - Fine-tune star visibility with 0-100% opacity adjustment
- **Star Enhancement** - Brightness and contrast controls specifically for star appearance
- **Star Size Adjustment** - Resize stars from 50% to 200% for optimal visual balance
- **Color Preservation** - Optional star color preservation to maintain natural star colors
- **Star Masking** - Optional threshold-based masking to control which stars are added
- **Real-Time Preview** - Instant feedback with optimized rendering during adjustments
- **StarNet Integration** - Perfect companion to StarNet-generated star images and masks

<img width="3046" height="2036" alt="image" src="https://github.com/user-attachments/assets/2ba70ebb-6f2b-4baa-8ba9-856e8636373b" />


### 🌌 **Astrophotography Presets**
Narrowband and broadband color palettes used by the astrophotography community:

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

### 🔧 **Features**
- **Layer Management System** - Organize adjustments in a layer stack with show/hide controls
- **Layer Visibility Toggle** - Individual layer on/off controls for comparison and fine-tuning
- **Layer Masks** - Luminosity-based selective adjustments with levels, blur, and invert controls
- **Mask Operations** - Copy, paste, and delete masks between layers with intuitive right-click menus
- **Read-Only Layers** - Special layers (like GraXpert and StarNet processing) that preserve workflow integrity
- **Add Stars Layer** - Professional star blending with multiple blend modes and enhancement controls
- **Channel Control** - Individual RGB composite channel visibility and manipulation
- **Live Histogram Analysis** - Real-time RGB histogram with square root and logarithmic scaling
- **Star Analysis Tools** - FWHM measurement and focus quality assessment with interactive selection
- **Advanced Crop Tool** - Precise image cropping with visual guides and undo/redo
- **FITS Header Viewer** - Examine astronomical metadata and capture information
- **Image Information Dialog** - Comprehensive image statistics and technical details
- **Undo/Redo System** - Comprehensive 20-level undo history for all operations
- **Enhanced Recent Files** - Right-expanding menu with file type icons and quick access
- **Splash Screen** - Visual startup feedback with animated loading indicators

### 🖱️ **Navigation Controls**
- **Zoom Control** - Hold `Ctrl` + Mouse Wheel to zoom in/out smoothly
- **Pan Navigation** - Right Mouse Button + Drag to pan around large images
- **Fit to Window** - Automatic image scaling for optimal viewing
- **Viewport** - Smooth scrolling and responsive image manipulation

### 🔌 **Plugin System**

#### **GraXpert Integration**
Integration with GraXpert for advanced background extraction and denoising:

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

- **Workflow**
  - Auto-detection of GraXpert installation
  - Creates non-destructive "GraXpert" layers
  - Preserves original image data
  - Temporary file cleanup
  - Command-line interface for batch processing

- **Interface**
  - Dialog matching AstroVEdit's dark theme
  - Export/Import settings capability
  - Progress feedback during processing
  - Error handling with user prompts

<img width="3046" height="2041" alt="image" src="https://github.com/user-attachments/assets/18bed9a1-fb18-48fb-bffe-0ed71c23ea57" />


#### **StarNet Integration**
Complete StarNet plugin integration for star removal and mask generation:

- **Star Removal Processing**
  - Auto-detection of StarNet installation paths
  - Python and Conda environment support
  - GPU and CPU processing modes
  - 16-bit RGB TIFF compatibility

- **Layer-Based Workflow**
  - Creates "StarNet Starless" layer with star-removed image
  - Creates "StarNet Extracted Stars" layer for use with Add Stars adjustment
  - Optional saving of extracted stars as separate TIFF files
  - Non-destructive workflow preserving original data
  - Full layer system integration (visibility, deletion, selection)

- **Interface**
  - Installation path configuration with auto-detection
  - Test functionality to verify Python environment
  - Processing options and environment settings
  - Progress feedback with auto-scroll console
  - Temporary file management with cleanup options

- **Advanced Features**
  - Registry-based settings persistence
  - Error handling with custom dialog system
  - Layer system compatibility (eye icons, edit buttons)
  - Styling matching AstroVEdit theme

<img width="3048" height="2040" alt="image" src="https://github.com/user-attachments/assets/e7bd6d50-2908-46c6-af10-238ad55ae63d" />


### 🎯 **User Experience**
- **Modern Dark Theme** - Eye-friendly interface optimized for long editing sessions
- **Material Design UI** - Clean, intuitive interface with consistent styling across all dialogs
- **Orange Signature Theme** - Custom highlighting and accent colors
- **Fast Preview Feedback** - Visual indicators show when optimized rendering is active
- **Splash Screen** - Visual feedback during application startup with animated loading indicators
- **Responsive Dialog System** - Intelligent positioning and drag functionality for all dialogs
- **Enhanced About Dialog** - Comprehensive feature documentation with scrollable content
- **Keyboard Shortcuts** - Efficient navigation and tool access
- **Tooltips** - Contextual help throughout the application
- **Performance Optimized** - Intelligent rendering cache with hash-based change detection

<img width="3047" height="2038" alt="image" src="https://github.com/user-attachments/assets/06220e65-740d-4313-bee5-ca7f6b1dd03f" />


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
1. Download the latest `AstroVEdit-1.1.0-Setup.exe` from [Releases](https://github.com/astro-vino/AstroVEdit/releases)
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
1. **Open an Image**: File → Open Recent (right-expanding menu) or drag-and-drop a FITS file
2. **Navigate the Image**: Use `Ctrl + Mouse Wheel` to zoom, `Right Mouse + Drag` to pan
3. **Add Adjustments**: Use the Adjustments panel to add enhancement layers
4. **Experience Fast Preview**: Notice the orange "FAST PREVIEW" indicator during slider adjustments
5. **Apply Presets**: Try astrophotography presets for quick results
6. **Fine-tune Settings**: Click the gear icon next to any adjustment to modify parameters
7. **Layer Management**: Use show/hide toggles to compare before/after results
8. **Analyze Stars**: Use Analysis → Star Analysis for focus quality assessment
9. **Monitor Changes**: Watch the real-time histogram and preview updates
10. **Save Your Work**: File → Save to preserve your edited image

#### Advanced Astrophotography Workflow
1. **Load Your Image**: Open FITS, TIFF, or other astronomical image formats
2. **Assess Image Quality**: Use Star Analysis to measure FWHM and focus quality with interactive star selection
3. **Background Processing**: Apply GraXpert background extraction or denoising as separate layers
4. **Star Processing**: Use StarNet for star removal and extracted stars generation, or Star Reduction for size control
5. **Star Re-addition**: Use Add Stars layer with StarNet-extracted stars for selective star blending
6. **Apply Narrowband Preset**: Choose SHO, HOO, or other palettes for instant color grading
7. **Fine-tune with Optimized Layers**: Add Levels, Curves, or Color Balance with ultra-fast response
8. **Create Selective Masks**: Right-click layers to add luminosity masks for targeted adjustments
9. **Refine Mask Properties**: Use levels, blur, and invert controls for precise mask customization
10. **Color Correction**: Use Remove Magenta or SCNR tools for color cast and noise reduction
11. **Compare Results**: Toggle layer visibility and mask overlays to compare processing stages
12. **Export Analysis Data**: Export star analysis to CSV for record keeping
13. **Export Final Image**: Save in your preferred format with all adjustments applied


To best showcase AstroVEdit's capabilities, consider capturing these key scenarios:

### **Primary Interface Screenshots**
1. **Main Interface Overview** - Load a colorful nebula image with multiple adjustment layers visible in the layer panel, histogram showing, and fast preview indicator active
2. **Layer Management** - Show the layers panel with various layer types: Background, GraXpert, StarNet Starless, StarNet Mask, and multiple adjustment layers with masks
3. **Before/After Comparison** - Split view or toggle showing original vs processed image with SHO palette applied

### **Advanced Tools in Action**
4. **Star Analysis Dialog** - Non-modal dialog open with detected stars visible on main image, sortable data grid filled with star data, and quality metrics displayed
5. **Layer Mask Creation** - Layer mask dialog showing luminosity mask with levels controls, blur settings, and red overlay visualization on main image
6. **Star Reduction Dialog** - Show the four method options with Transfer method selected, stretch factor slider, and small star protection controls

### **Plugin Integration**
7. **GraXpert Dialog** - Interface showing background extraction settings, AI model selection, and progress feedback
8. **StarNet Dialog** - Installation detection, processing options, and the resulting starless/mask layers in the layer panel
9. **SCNR Dialog** - Color noise reduction interface with protection method dropdown and real-time preview

### **Performance Features**
10. **Fast Preview System** - Orange "FAST PREVIEW" indicator visible in top-right corner during slider adjustment
11. **Responsive UI** - Levels dialog with gamma slider being adjusted and lookup table optimization in action
12. **Custom Dialogs** - Styled dialogs (Information, Warning, Error) replacing standard Windows MessageBox

### **Astrophotography Workflow**
13. **Narrowband Processing** - SHO palette application showing dramatic color transformation from original to processed
14. **Quality Results** - Final processed image showcasing the quality achievable with AstroVEdit's tools
15. **Multi-Layer Workflow** - Complex processing chain showing GraXpert background removal, StarNet star processing, color grading, and selective masking



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
- **LayerManager** - Layer system with intelligent caching and performance optimization
- **AdjustmentLayers** - Non-destructive editing with ultra-fast preview and lookup table optimization
- **LayerMask** - Luminosity masking with levels, blur, and invert processing
- **LayerMaskDialog** - Advanced mask editing interface with real-time preview and performance optimization
- **AstroPaletteProcessor** - Authentic narrowband channel combination engine
- **StarDetector** - Advanced star detection with FWHM measurement and quality assessment
- **StarReductionAdjustmentLayer** - Star size reduction with 4 methods
- **AddStarsAdjustmentLayer** - Professional star blending with multiple blend modes and enhancement controls
- **RemoveMagentaAdjustmentLayer** - Comprehensive magenta cast removal with 5 algorithms
- **SCNRAdjustmentLayer** - Color noise reduction with 5 protection methods
- **GraXpertDialog** - Plugin integration interface with layer-based output
- **StarNetDialog** - Complete StarNet integration with auto-detection and layer workflow
- **RecentFilesManager** - Persistent recent files with automatic cleanup and file type detection
- **FastPreviewSystem** - Reduced resolution rendering for real-time slider feedback
- **InformationDialog** - Custom styled dialogs replacing standard Windows MessageBox

## 📋 Roadmap

### Recently Completed in v1.1.0 ✅
- [x] **Performance Revolution** - Ultra-fast slider response with lookup table optimization
- [x] **Layer Masks** - Luminosity-based selective adjustments with advanced controls
- [x] **Star Analysis Tools** - FWHM measurement and focus quality assessment with interactive selection
- [x] **Advanced Processing Tools** - Star Reduction, Remove Magenta, and SCNR algorithms
- [x] **StarNet Plugin Integration** - Complete star removal and mask generation with layer-based workflow
- [x] **Fast Preview System** - Real-time reduced resolution rendering during adjustments
- [x] **Enhanced User Interface** - Consistent Material Design with orange signature theme and custom dialogs
- [x] **Navigation Controls** - Ctrl+Mouse Wheel zoom and right-click pan functionality
- [x] **About Dialog Redesign** - Comprehensive feature documentation with scrollable content

### Previously Completed ✅
- [x] **GraXpert Plugin Integration** - Background extraction and denoising with layer-based output
- [x] **Astrophotography Presets** - Complete narrowband and broadband palette system with multi-layer approach
- [x] **Layer System Enhancement** - Show/hide controls, read-only layer support, and mask operations
- [x] **Performance Optimization** - Hardware acceleration and intelligent caching with hash-based change detection
- [x] **Recent Files System** - Quick access to recently opened images with right-expanding menu
- [x] **Comprehensive Undo/Redo** - 20-level operation history for all image operations
- [x] **Splash Screen** - Startup feedback with animated indicators and fade transitions

### Considered Features
- [ ] **Advanced Stacking** - Built-in image stacking capabilities
- [ ] **Batch Processing** - Automated processing of multiple images

### Long-term Goals
- [ ] **AI Enhancement** - Machine learning-powered image enhancement
- [ ] **Plate Solving Integration** - Automatic astrometric calibration
- [ ] **Photometry Tools** - Stellar magnitude measurement capabilities

## 📚 Documentation
- [User Manual](docs/user-manual.md) *(Coming Soon)*
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

## 🎮 Controls Reference

### Navigation
- **Zoom In/Out**: `Ctrl` + Mouse Wheel
- **Pan Image**: Right Mouse Button + Drag
- **Fit to Window**: Double-click on image
- **Reset Zoom**: `Ctrl` + `0`

### File Operations
- **Open File**: `Ctrl` + `O`
- **Save File**: `Ctrl` + `S`
- **Recent Files**: File → Open Recent (right-expanding submenu)

### Layer Management
- **Toggle Layer Visibility**: Click eye icon next to layer
- **Edit Layer**: Click gear icon next to layer (not available for read-only layers like GraXpert/StarNet)
- **Add Adjustment Layer**: Right-click "+" button in layers panel for context menu (includes Add Stars layer)
- **Add Layer Mask**: Click mask button or right-click layer name
- **Edit Layer Mask**: Click orange mask icon next to layer
- **Copy/Paste Masks**: Right-click mask icon for context menu
- **Toggle Mask Overlay**: Use "Show Mask Overlay" in mask dialog
- **Delete Layers**: Select layer and use delete button (works for all layer types)

### Analysis & Tools
- **Star Analysis**: Analysis → Star Analysis (non-modal dialog with interactive star selection)
- **FITS Header**: View → FITS Header
- **Image Information**: View → Image Information
- **GraXpert**: Plugins → GraXpert (background extraction and denoising)
- **StarNet**: Plugins → StarNet (star removal and mask generation)
- **SCNR**: Plugins → SCNR Tool (subtractive chromatic noise reduction)

## 📄 License
This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## 🙏 Acknowledgments
- **CSharpFITS Team** - For excellent FITS file format support
- **Material Design Team** - For beautiful, modern UI components
- **ScottPlot Contributors** - For powerful plotting capabilities
- **GraXpert Team** - For outstanding background extraction and denoising tools
- **StarNet Team** - For revolutionary star removal technology and open-source availability
- **Astronomical Community** - For feedback, feature suggestions, palette contributions, and inspiration in astronomical image processing workflows

## 📞 Contact
- **Project Homepage:** [https://github.com/astro-vino/AstroVEdit](https://github.com/astro-vino/AstroVEdit)
- **Issues & Support:** [GitHub Issues](https://github.com/astro-vino/AstroVEdit/issues)
- **Discussions:** [GitHub Discussions](https://github.com/astro-vino/AstroVEdit/discussions)

---

<div align="center">
  <strong>Made with ❤️ for the astronomical imaging community</strong><br>
  <em>Professional tools for amateur astronomers</em><br><br>
  <strong>Copyright © 2025 Astro_Vino</strong>
</div>
