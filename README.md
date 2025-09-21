# AstroVEdit

<div align="center">
<img width="128" height="128" alt="FullColor_Logo-Only_Round" src="https://github.com/user-attachments/assets/a0a39cab-f5c9-4d49-9e31-36c1dcf6d8bd" />


  **Astronomical Image Editing Software**

  [![.NET](https://img.shields.io/badge/.NET-9.0-blue.svg)](https://dotnet.microsoft.com/)
  [![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows)
  [![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE.txt)
  [![Version](https://img.shields.io/badge/version-1.5.0-orange.svg)](https://github.com/astro-vino/AstroVEdit/releases)
</div>

## Overview

AstroVEdit is an astronomical image editing application designed specifically for processing FITS (Flexible Image Transport System) files and other astronomical image formats. Built with WPF and .NET 9, it provides comprehensive tools for astrophotographers and astronomers to enhance and analyze their celestial captures with industry-standard workflows and performance optimizations.

Featuring a complete suite of adjustment layers, advanced plugin integrations, specialized astrophotography tools, and seamless file association system, AstroVEdit delivers high-quality processing with an intuitive, modern interface designed for amateur astronomers and astrophotographers.

<img width="3066" height="1901" alt="image" src="https://github.com/user-attachments/assets/0cd90956-cdbd-4129-a723-1a766f1b570b" />



## 🆕 What's New in v1.5.0

### 🗂️ **Enhanced File Explorer**
- **Streamlined Interface** - Removed non-functional toggle view button for cleaner, more focused file browsing
- **Reliable Folder Memory** - Fixed folder memory system to properly remember and restore your last browsing location
- **Improved Initialization** - Enhanced startup timing ensures folder memory works consistently across application restarts
- **Debug Logging** - Added comprehensive logging for troubleshooting file explorer navigation issues

### 🎨 **User Interface Refinements**
- **Cleaner Navigation** - Simplified file explorer controls focusing on essential functionality
- **Better Responsiveness** - Improved file explorer loading with proper event handling
- **Enhanced Debugging** - Better diagnostic information for file system operations

### 🐛 **Bug Fixes & Stability**
- **File Explorer Memory** - Fixed issue where last folder wasn't properly restored on application startup
- **UI Cleanup** - Removed unused view toggle functionality that provided no actual functionality
- **Initialization Timing** - Improved component loading order to ensure proper folder memory restoration

## 🔄 What Was New in v1.4.0

### 🌌 **Professional Narrowband Processing System**
- **PixInsight-Style Interface** - Complete narrowband processing dialog matching PixInsight's NarrowbandNormalization tool
- **12 Authentic Palettes** - SHO (Hubble), HOO, HSO, HOS, OSH, OHS, OSS, OHH, HSS, Foraxx, Realistic 1 & 2
- **Advanced Channel Controls** - SCNR, OIII Boost, SII Boost with professional parameter ranges
- **Synthetic Green Blend** - 4 blend modes (Average, Geometric, Maximum, Minimum) with adjustable amount
- **Lightness Preservation** - Preserve, Ignore, or Enhance modes for luminance control
- **Tonal Adjustments** - Shadow Point, Highlight Reduction, and Brightness controls
- **18 Professional Blend Modes** - Complete blend mode system including Luminosity, Color, Saturation, Hue
- **Performance Optimized** - Intelligent caching, lookup tables, and fast preview mode

### 🔧 **Enhanced Noise Reduction**
- **Fixed Dialog Issues** - Resolved DialogResult exceptions and layer creation problems
- **Improved Performance** - Optimized processing algorithms with better caching
- **Professional Integration** - Seamless layer system integration with proper error handling
- **Real-time Preview** - Smooth slider response with intelligent throttling

### ⚡ **Performance Improvements**
- **Instant Dialog Loading** - Deferred control initialization for immediate dialog appearance
- **Optimized ComboBox Selection** - Direct index assignment instead of slow string comparison loops
- **Fast Preview Optimization** - Improved slider responsiveness with better caching and throttling
- **Smart Timer Management** - Intelligent update intervals for smooth real-time feedback

### 🐛 **Critical Fixes**
- **Dialog Startup Delay** - Eliminated delays when opening adjustment dialogs
- **Property Change Notifications** - Fixed cache invalidation and UI update issues
- **DialogResult Handling** - Robust dialog result management with fallback detection
- **Layer Creation Logic** - Reliable adjustment layer creation and integration

## 🔄 What Was New in v1.3.0

### 🗂️ **Advanced Project File System (.vino)**
- **Complete Layer Preservation** - Save and restore entire layer stacks with exact parameter values
- **Layer Mask Support** - Full luminosity mask serialization with all settings (levels, blur, invert)
- **Image Layer Support** - Preserves GraXpert, StarNet, and other processed image layers
- **Metadata Tracking** - Project creation/modification dates and AstroVEdit version compatibility
- **Compressed Storage** - ZIP-based format for efficient file size with organized internal structure
- **Professional Workflow** - Non-destructive project management comparable to Photoshop PSD files

### 📤 **Professional Export System**
- **Advanced Format Support** - Export to JPEG, PNG, TIFF, BMP, FITS, and XISF with format-specific options
- **Quality Control** - JPEG quality presets (Low 30%, Medium 60%, High 80%, Maximum 95%) plus custom slider (1-100%)
- **TIFF Options** - LZW/ZIP/None compression, 8-bit/16-bit color depth, metadata embedding
- **PNG Optimization** - Fast/Default/Best compression levels with interlaced option
- **Real-time Preview** - File size estimation updates as settings change
- **Professional UI** - Format-specific settings panels with dynamic control visibility

### 🔧 **Enhanced User Interface**
- **Streamlined Menu System** - "Save Project" replaces confusing dual save options
- **Logical Toolbar** - Save Project and Export As buttons with consistent steel blue styling
- **Format-Aware Dialogs** - Export dialog adapts to show relevant options for each format
- **Size Display** - Read-only image dimensions instead of confusing editable fields
- **Clean Organization** - Removed unnecessary area selection options

### 🐛 **Critical XISF Compatibility Fixes**
- **Layer Mask Support** - Fixed layer mask creation and preview for 16-bit XISF files
- **Pixel Format Handling** - Proper RGB48 format support in mask blending system
- **Viewport Corruption Fix** - Eliminated purple artifacts when using masked adjustment layers
- **16-bit Processing** - Correct handling of 16-bit per channel data throughout the pipeline

## 🔄 What Was New in v1.2.0

### 🗂️ **Complete File Association System**
- **Native .vino Project Files** - Double-click .vino files to open projects directly in AstroVEdit
- **Windows Integration** - Full file association with custom icons and "Open with AstroVEdit" context menus
- **Command-Line Support** - Launch AstroVEdit with file paths for automation and scripting
- **Drag & Drop Enhancement** - Drop both .vino project files and images directly onto the application
- **Smart File Handling** - Automatic detection of file types with appropriate loading methods

### 🔄 **Advanced Project Management**
- **Seamless Project Loading** - Projects load with automatic image fitting and enabled save functionality
- **Enhanced Save Dialogs** - Custom styled confirmation dialogs with appropriate language ("Update" vs "Delete")
- **Progress Bar Improvements** - Smooth animated progress indicators during save/load operations
- **Thread-Safe Operations** - Reliable project operations without threading exceptions
- **Auto-Fit on Load** - Projects automatically fit to viewport for optimal viewing

### 🎯 **Professional Noise Reduction System**
- **Five Advanced Algorithms** - Gaussian, Median, Bilateral, Edge Preserving, and Adaptive noise reduction
- **Astrophotography-Focused** - Star protection system with adjustable threshold (0.1-1.0)
- **Chrominance-Only Mode** - Preserve luminance details while reducing color noise
- **Real-Time Preview** - Dual-timer system for responsive slider feedback
- **Professional Controls** - Method selection, strength, radius, threshold with dynamic UI
- **Performance Optimized** - Intelligent caching and fast preview integration

### 🌟 **Enhanced Star Reduction Tools**
- **Multiple Reduction Methods** - Transfer, Halo, Star, and Lightness algorithms for different star types
- **Advanced Protection** - Configurable star protection to preserve natural star appearance
- **Real-Time Feedback** - Instant preview with optimized rendering during adjustments
- **Professional Integration** - Seamless layer system integration with undo/redo support

### 🎨 **Improved User Experience**
- **Streamlined Dialogs** - Removed unnecessary confirmation popups for cleaner workflow
- **Consistent Styling** - All dialogs match AstroVEdit's Material Design theme
- **Better Progress Feedback** - Visible progress bars with smooth animation throughout operations
- **Enhanced File Dialogs** - Custom overwrite confirmations with context-appropriate messaging

## 🔄 What Was New in v1.1.0

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

<img width="3058" height="1893" alt="image" src="https://github.com/user-attachments/assets/92deba02-7f41-4a66-968c-0d420c44e9ae" />



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

<img width="3837" height="2158" alt="image" src="https://github.com/user-attachments/assets/01b97261-617b-4d60-89f7-495667c91a28" />



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

<img width="2876" height="1779" alt="image" src="https://github.com/user-attachments/assets/9bf383b1-526a-4715-a091-f1b523d19073" />



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
- **Layer Reordering** - Move layers up/down with buttons or Ctrl+Up/Down keyboard shortcuts
- **Layer Flattening** - Multi-select layers and collapse them into a single "Flattened Layer"
- **Base Layer Protection** - Padlocked background layer stays at bottom of stack
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
1. Download the latest `AstroVEdit-1.5.0-Setup.exe` from [Releases](https://github.com/astro-vino/AstroVEdit/releases)
2. Run the installer as Administrator
3. Follow the installation wizard
4. **File Associations**: Installer automatically registers .vino project files and adds "Open with AstroVEdit" to image context menus
5. Launch AstroVEdit from Start Menu or Desktop shortcut

#### GraXpert Plugin Setup (Optional)
1. Download and install [GraXpert](https://github.com/Steffenhir/GraXpert) from the official repository
2. AstroVEdit will auto-detect GraXpert in common installation paths:
   - `%LocalAppData%\Programs\GraXpert`
   - `C:\Program Files\GraXpert`
   - `C:\Program Files (x86)\GraXpert`
3. If not found automatically, you'll be prompted to locate the GraXpert executable

### Quick Start Guide

#### Basic Workflow
1. **Open an Image**: Double-click .vino project files, File → Open Recent (right-expanding menu), or drag-and-drop FITS files or .vino projects
2. **Navigate the Image**: Use `Ctrl + Mouse Wheel` to zoom, `Right Mouse + Drag` to pan
3. **Add Adjustments**: Use the Adjustments panel to add enhancement layers including new Noise Reduction
4. **Experience Fast Preview**: Notice the orange "FAST PREVIEW" indicator during slider adjustments
5. **Apply Presets**: Try astrophotography presets for quick results
6. **Fine-tune Settings**: Click the gear icon next to any adjustment to modify parameters
7. **Layer Management**: Use show/hide toggles to compare before/after results
8. **Analyze Stars**: Use Analysis → Star Analysis for focus quality assessment
9. **Monitor Changes**: Watch the real-time histogram and preview updates
10. **Save Your Work**: File → Save Project to preserve your complete editing session as .vino file

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
11. **Optimize Layer Stack**: Multi-select multiple adjustment layers and flatten them into single processed layers for performance
12. **Compare Results**: Toggle layer visibility and mask overlays to compare processing stages
13. **Export Analysis Data**: Export star analysis to CSV for record keeping
14. **Export Final Image**: Save in your preferred format with all adjustments applied




### **🆕 v1.2.0 Feature Showcase**

#### **🗂️ File Association & Project Management**
1. **Windows Explorer Integration** - Capture Windows Explorer showing:
   - .vino project files with custom AstroVEdit icons
   - Right-click context menu with "Open with AstroVEdit" option
   - File association working when double-clicking .vino files

2. **Drag & Drop Excellence** - Show enhanced drag and drop functionality:
   - Drag overlay displaying "Drop file here" with "Supports .vino projects and images"
   - Format list showing "FITS, JPEG, PNG, BMP, TIFF, VINO"
   - Successful drop of both image files and .vino project files

3. **Project Loading Workflow** - Demonstrate seamless project loading:
   - Progress bar with smooth animation during project load
   - Auto-fit to viewport after loading (showing full image properly fitted)
   - Enabled save buttons and menu items after project loads
   - Console output showing successful project loading messages

4. **Enhanced Save Dialogs** - Capture improved save experience:
   - Custom styled "Update Project File" confirmation dialog
   - "Update" and "Cancel" buttons (not "Delete")
   - Progress bar animation during save operations
   - Professional styling matching AstroVEdit theme

#### **🎯 Noise Reduction System**
5. **Professional Noise Reduction Interface** - Show comprehensive noise reduction dialog:
   - Method dropdown with all 5 algorithms (Gaussian, Median, Bilateral, Edge Preserving, Adaptive)
   - Dynamic controls showing/hiding based on selected method
   - Star protection controls with threshold slider
   - Chrominance-only processing option
   - Real-time preview toggle and method descriptions

6. **Noise Reduction in Action** - Demonstrate noise reduction effectiveness:
   - Before/after comparison showing noise reduction results
   - Star protection preserving star details while reducing background noise
   - Different algorithms applied to same image showing varied results
   - Layer integration with noise reduction as adjustment layer

#### **🌟 Star Reduction Tools**
7. **Advanced Star Reduction** - Capture star reduction capabilities:
   - Star Reduction dialog with 4 methods (Transfer, Halo, Star, Lightness)
   - Protection controls preserving natural star appearance
   - Before/after showing controlled star size reduction
   - Real-time preview with fast feedback during adjustments

### **🎯 Primary Interface Showcase**
1. **Complete Workspace Overview** - Load a stunning nebula image (M42, Rosette, or Eagle Nebula) with:
   - Multiple adjustment layers visible in layers panel (Curves, Levels, Color Balance, SCNR)
   - Real-time histogram displaying RGB channels with logarithmic scaling
   - Orange "FAST PREVIEW" indicator active during slider adjustment
   - Channel panel showing RGB composite controls
   - Console output showing processing feedback

2. **Professional Layer Stack** - Demonstrate complex layer hierarchy:
   - Background layer (padlocked) at bottom
   - GraXpert background-extracted layer
   - StarNet Starless and StarNet Extracted Stars layers
   - Multiple adjustment layers with orange mask indicators
   - "Flattened Layer" showing eye icon (not padlock)
   - **Highlight all layer control buttons**: Add, Mask, Move Up/Down, Flatten, Delete

3. **Advanced Layer Operations** - Show professional workflow in action:
   - Multi-selected layers (Ctrl+Click) with Flatten button enabled
   - Layer reordering with Move Up/Down buttons and smart button states
   - Layer mask editing dialog with red overlay on main image
   - Confirmation dialogs with proper "Flatten" button text

### **🔬 Advanced Processing Tools**
4. **Star Analysis Excellence** - Capture the non-modal star analysis dialog with:
   - Interactive star selection on main image (click stars to highlight in grid)
   - Sortable data grid showing FWHM, SNR, and quality metrics
   - Real-time focus quality calculation and statistics
   - CSV export functionality for data analysis

5. **Professional Masking Workflow** - Demonstrate luminosity masking power:
   - Layer mask dialog with levels controls (Input Black/White, Gamma)
   - Gaussian blur slider (0-20 pixels) for mask softening
   - Red overlay visualization showing mask areas on main image
   - Before/after comparison with mask toggle

6. **Specialized Astrophotography Tools** - Show dedicated processing features:
   - Star Reduction with 4 methods and protection controls
   - Add Stars layer with blend modes and enhancement options
   - Remove Magenta with 5 algorithms and star protection
   - SCNR with protection methods and real-time preview

### **🔌 Plugin Integration Excellence**
7. **GraXpert Professional Integration** - Showcase seamless plugin workflow:
   - Auto-detection of installation paths
   - Background extraction with AI model selection
   - Denoising controls with GPU acceleration options
   - Layer-based output preserving non-destructive workflow

8. **StarNet Complete Workflow** - Demonstrate star removal mastery:
   - Installation detection and Python environment setup
   - Star removal processing with progress feedback
   - Automatic layer creation (Starless, Extracted Stars, Mask)
   - Integration with Add Stars layer for selective re-addition

### **⚡ Performance & UI Excellence**
9. **Ultra-Fast Preview System** - Capture performance optimizations:
   - Orange "FAST PREVIEW" indicator during slider adjustments
   - Lookup table optimization for instant gamma correction
   - Reduced resolution rendering for real-time feedback
   - Smooth slider response with visual feedback

10. **Professional Dialog System** - Show consistent Material Design:
    - Custom styled dialogs (Information, Warning, Error, Confirmation)
    - Dark theme consistency across all interfaces
    - Orange signature highlighting and accent colors
    - Proper button labeling ("Flatten" not "Delete" for layer operations)

### **🎨 Layer Management Mastery**
11. **Complete Layer Control Interface** - Detailed view of layer panel showing:
    - All layer control buttons with tooltips: Add (+), Mask (○), Move Up (↑), Move Down (↓), Flatten (⧉), Delete (🗑)
    - Smart button states (enabled/disabled based on selection and position)
    - Layer type indicators (padlock for base, eye for toggleable layers)
    - Orange mask indicators for layers with active masks

12. **Multi-Selection Flattening** - Step-by-step flattening demonstration:
    - Multiple layers selected with Ctrl+Click (highlight selection)
    - Flatten button enabled with proper tooltip
    - Confirmation dialog showing layers to be flattened with "Flatten" button
    - Resulting "Flattened Layer" with eye icon (not padlock)

13. **Layer Reordering Precision** - Show intelligent reordering system:
    - Move Up/Down buttons with keyboard shortcut tooltips
    - Smart button states preventing invalid moves
    - Base layer protection (Move Down disabled when appropriate)
    - Layer selection preservation after moving

14. **Base Layer Protection** - Demonstrate foundational layer security:
    - Padlocked Background layer at bottom of stack
    - Disabled buttons when base layer selected
    - Warning dialogs when attempting invalid operations
    - Clear visual distinction between base and processed layers

### **🌌 Astrophotography Workflow Excellence**
15. **Narrowband Palette Mastery** - Show dramatic color transformations:
    - SHO (Hubble) palette application with before/after split
    - HOO Natural palette for realistic narrowband results
    - Dynamic color grading with real-time preview
    - Channel combination techniques for optimal results

16. **Professional Processing Chain** - Complete workflow demonstration:
    - Original FITS file → GraXpert background extraction → StarNet processing
    - → Narrowband palette application → Selective masking → Layer optimization
    - → Final export with all processing stages visible in layer stack

17. **Quality Results Showcase** - Final processed images demonstrating:
    - Deep sky objects with enhanced detail and color
    - Proper star color preservation and enhancement
    - Noise reduction while maintaining fine detail
    - Professional-grade results comparable to commercial software

### **💡 Advanced Techniques for Users to Try**

#### **🎯 Layer Stack Optimization Techniques:**
- **Performance Boost**: Flatten multiple adjustment layers after fine-tuning to improve rendering speed
- **Selective Processing**: Use layer masks to apply different adjustments to stars vs nebulosity
- **Non-Destructive Workflow**: Keep original layers hidden but preserved for future adjustments
- **Layer Organization**: Group related adjustments and flatten them into logical processing stages

#### **🔧 Professional Masking Workflows:**
- **Luminosity Separation**: Create masks from current viewport to separate bright and dark regions
- **Star Protection**: Use inverted masks to protect stars during nebula enhancement
- **Gradient Masks**: Apply blur to masks for smooth transitions between processed areas
- **Mask Refinement**: Use levels controls to fine-tune mask contrast and coverage

#### **⚡ Performance Optimization Tips:**
- **Fast Preview Mode**: Watch for orange indicator during adjustments for optimal responsiveness
- **Layer Flattening**: Collapse complex adjustment stacks to reduce computational overhead
- **Selective Rendering**: Toggle layer visibility to isolate processing effects and improve performance
- **Cache Management**: Understand how layer changes invalidate cache for efficient workflow planning



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
- **StarReductionAdjustmentLayer** - Star size reduction with 4 methods and advanced protection
- **NoiseReductionAdjustmentLayer** - Professional noise reduction with 5 algorithms and star protection
- **AddStarsAdjustmentLayer** - Professional star blending with multiple blend modes and enhancement controls
- **RemoveMagentaAdjustmentLayer** - Comprehensive magenta cast removal with 5 algorithms
- **SCNRAdjustmentLayer** - Color noise reduction with 5 protection methods
- **GraXpertDialog** - Plugin integration interface with layer-based output
- **StarNetDialog** - Complete StarNet integration with auto-detection and layer workflow
- **ProjectManager** - .vino project file handling with seamless save/load operations
- **FileAssociationSystem** - Windows integration with custom icons and context menus
- **RecentFilesManager** - Persistent recent files with automatic cleanup and file type detection
- **FastPreviewSystem** - Reduced resolution rendering for real-time slider feedback
- **InformationDialog** - Custom styled dialogs replacing standard Windows MessageBox
- **ConfirmationDialog** - Professional confirmation dialogs with context-appropriate messaging

## 📋 Roadmap

### Recently Completed in v1.5.0 ✅
- [x] **Enhanced File Explorer** - Streamlined interface with reliable folder memory and improved initialization
- [x] **UI Refinements** - Cleaner navigation controls and better responsiveness
- [x] **Bug Fixes** - Fixed file explorer memory system and removed non-functional UI elements
- [x] **Improved Debugging** - Enhanced logging and diagnostic information for better troubleshooting

### Completed in v1.4.0 ✅
- [x] **Professional Narrowband Processing** - Complete PixInsight-style narrowband system with 12 palettes and advanced controls
- [x] **Performance Revolution** - Instant dialog loading, optimized ComboBox selection, and improved slider responsiveness
- [x] **Enhanced Noise Reduction** - Fixed dialog issues, improved performance, and seamless layer integration
- [x] **18 Professional Blend Modes** - Complete blend mode system including HSL-based modes for creative processing
- [x] **Smart Caching System** - Intelligent result caching with hash-based validation for optimal performance
- [x] **Dialog Optimization** - Eliminated startup delays with deferred initialization and direct index assignment

### Completed in v1.3.0 ✅
- [x] **Advanced Project File System** - Complete .vino project format with layer preservation and metadata tracking
- [x] **Professional Export System** - Advanced export dialog with format-specific options and quality control
- [x] **Enhanced User Interface** - Streamlined menu system and logical toolbar organization
- [x] **XISF Compatibility Fixes** - Fixed layer mask support and viewport corruption for 16-bit XISF files
- [x] **Format-Aware Processing** - Proper handling of RGB48, BGRA32, and BGR24 pixel formats throughout the pipeline

### Completed in v1.2.0 ✅
- [x] **Complete File Association System** - Native .vino project files with Windows integration and custom icons
- [x] **Advanced Project Management** - Seamless loading, enhanced save dialogs, and progress bar improvements
- [x] **Professional Noise Reduction** - Five advanced algorithms with star protection and chrominance-only mode
- [x] **Enhanced Star Reduction** - Multiple reduction methods with advanced protection controls
- [x] **Improved User Experience** - Streamlined dialogs, consistent styling, and better progress feedback
- [x] **Command-Line Support** - Launch AstroVEdit with file paths for automation and scripting
- [x] **Drag & Drop Enhancement** - Support for both .vino project files and images with updated overlay
- [x] **Thread-Safe Operations** - Reliable project operations without threading exceptions

### Completed in v1.1.0 ✅
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
- **Save Project**: File → Save Project (saves as .vino file)
- **Open Project**: File → Open Project or double-click .vino files
- **Recent Files**: File → Open Recent (right-expanding submenu)
- **Drag & Drop**: Drop .vino projects or images directly onto application

### Layer Management
- **Toggle Layer Visibility**: Click eye icon next to layer
- **Move Layers**: Use Move Up/Down buttons or `Ctrl` + `Up`/`Down` arrows to reorder layers
- **Flatten Layers**: Multi-select layers (Ctrl+Click) and use Flatten button to collapse into single layer
- **Base Layer Protection**: Background layer with padlock icon cannot be moved or have layers moved below it
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
- **Noise Reduction**: Right-click "+" → Noise Reduction (5 algorithms with star protection)
- **Star Reduction**: Right-click "+" → Star Reduction (4 methods with protection controls)
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
