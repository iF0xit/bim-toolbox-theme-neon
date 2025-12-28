# BIM Toolbox Neon Theme

[![License: GPL-3.0-or-later](https://img.shields.io/github/license/iF0xit/bim-toolbox-theme-neon?v=2)](https://www.gnu.org/licenses/gpl-3.0)
[![Release](https://img.shields.io/github/v/release/iF0xit/bim-toolbox-theme-neon?v=2)](https://github.com/iF0xit/bim-toolbox-theme-neon/releases/latest)
[![Blender](https://img.shields.io/badge/Blender-4.2%2B-orange?logo=blender&logoColor=white)](https://www.blender.org)
[![Theme: Neon](https://img.shields.io/badge/Theme-Neon-%2306b6d4)](.)

**Version:** 2026.04.08
**Blender:** 4.2+
**License:** GPL-3.0-or-later
**Maintainer:** iF0xit

> Futuristic Neon theme for the BIM Toolbox with glowing cyan accents - available in Dark and Light variants.

## Table of Contents

- [Description](#description)
- [Theme Variants](#theme-variants)
  - [Neon Dark](#neon-dark)
  - [Neon Light](#neon-light)
- [Installation](#installation)
  - [Method 1: XML Installation (Recommended)](#method-1-xml-installation-recommended)
  - [Method 2: Extension (ZIP Installation)](#method-2-extension-zip-installation)
- [Features](#features)
- [Technical Specifications](#technical-specifications)
- [File Structure](#file-structure)
- [Troubleshooting](#troubleshooting)
- [FAQ](#frequently-asked-questions-faq)
- [License](#license)
- [Support & Contact](#support--contact)
- [Version History](#version-history)

## Description

The **Neon** theme is a futuristic theme for the BIM Toolbox with glowing cyan/turquoise accents. It offers a modern, tech-inspired color scheme for creative workflows.

Available in two variants:
- **Neon (Dark)** - Dark theme for immersive work in dimly lit environments
- **Neon Light** - Light theme with vibrant cyan/magenta accents for daylight-optimized workspaces

## Theme Variants

### Neon Dark

The dark theme with glowing cyan accents for futuristic, immersive work in dimly lit environments.

**Main Colors:**

| Element | Description | Hex |
|---------|-------------|-----|
| Primary Accent | Cyan (Active Elements) | `#06b6d4` |
| Secondary Accent | Turquoise (Hover States) | `#22d3ee` |
| Tertiary Accent | Purple (Highlights) | `#a855f7` |
| Background (Editor) | Deep Dark | `#0a0e1a` |
| Panel Header | Dark Blue | `#0f1419` |
| Panel Background | Deep Dark (Transparent) | `#0a0e1aff` |
| Primary Text | Light Cyan | `#e0f2fe` |
| Text Cursor | Light Turquoise | `#22d3ee` |

**Status Colors:**

| Element | Color | Hex |
|---------|-------|-----|
| Success | Emerald | `#10b981` |
| Warning | Amber | `#f59e0b` |
| Error | Red | `#ef4444` |
| Info | Pink | `#ec4899` |

**Axis Colors (3D Viewport):**

| Axis | Color | Hex |
|------|-------|-----|
| X-Axis | Red | `#ef4444` |
| Y-Axis | Green | `#22c55e` |
| Z-Axis | Cyan | `#06b6d4` |
| W-Axis | Amber | `#f59e0b` |

### Neon Light

The light variant with vibrant cyan/magenta accents for daylight-optimized workspaces with a clean, professional appearance.

**Main Colors:**

| Element | Description | Hex |
|---------|-------------|-----|
| Primary Accent | Cyan (Active Elements) | `#06b6d4` |
| Secondary Accent | Turquoise (Hover States) | `#22d3ee` |
| Tertiary Accent | Purple (Highlights) | `#a855f7` |
| Background (Editor) | Pure White | `#ffffff` |
| Panel Header | Light Gray | `#f8fafc` |
| Panel Background | Pure White (Transparent) | `#ffffffff` |
| Primary Text | Deep Blue | `#0f172a` |
| Text Cursor | Light Turquoise | `#22d3ee` |

**Status Colors:**

| Element | Color | Hex |
|---------|-------|-----|
| Success | Emerald | `#10b981` |
| Warning | Amber | `#f59e0b` |
| Error | Red | `#ef4444` |
| Info | Pink | `#ec4899` |

**Axis Colors (3D Viewport):**

| Axis | Color | Hex |
|------|-------|-----|
| X-Axis | Red | `#ef4444` |
| Y-Axis | Green | `#22c55e` |
| Z-Axis | Cyan | `#06b6d4` |
| W-Axis | Amber | `#f59e0b` |

## Installation

### Method 1: XML Installation (Recommended)

Direct XML installation is the simplest and most reliable method.

1. Download the ZIP file from the [Releases](https://github.com/iF0xit/bim-toolbox-theme-neon/releases)
2. Extract the ZIP file
3. Open Blender
4. Navigate to: `Edit` → `Preferences` → `Themes`
5. Click `Install...`
6. Select the XML file from the extracted folder
7. The theme will appear in the theme list - select it

> **Note:** Both variants (Dark/Light) can be installed side by side.

### Method 2: Extension (ZIP Installation)

The extension method allows management through Blender's extension system.

#### Installation:

1. Download the ZIP file from the [Releases](https://github.com/iF0xit/bim-toolbox-theme-neon/releases)
2. Open Blender
3. **Drag & Drop** the ZIP file onto the Blender window

   **Or alternatively:**
   - Navigate to: `Edit` → `Preferences` → `Get Extensions`
   - Click the arrow in the top right → `Install from Disk`
   - Select the ZIP file

4. The theme will be automatically installed and activated

#### Uninstallation:

The theme must be manually removed from the extensions folder. Delete the corresponding theme folder:

**Linux:**
```
~/.config/blender/<VERSION>/extensions/user_default/<THEME_ID>
```

**Windows:**
```
%APPDATA%\Blender Foundation\Blender\<VERSION>\extensions\user_default\<THEME_ID>
```

**macOS:**
```
~/Library/Application Support/Blender/<VERSION>/extensions/user_default/<THEME_ID>
```

> **Note:** Replace `<VERSION>` with your Blender version (e.g., `5.0`) and `<THEME_ID>` with the extension ID (e.g., `if0xit_bim_toolbox_theme_neon_dark_b5`).

After deleting, restart Blender for the changes to take effect.

### Switch Theme

After installation, you can switch between themes at any time:

1. `Edit` → `Preferences` → `Themes`
2. Select the desired theme from the dropdown list
3. Changes are applied immediately

## Features

### Shared Features (both variants)

- **Futuristic Color Scheme**: Aligned with the BIM Toolbox web platform (Neon mode)
- **Neon Accent Colors**: Cyan/turquoise accents for important UI elements
- **Standardized Axis Colors**: Consistent X/Y/Z axis representation (Z-axis in cyan)
- **Optimized Icon Display**: Icon alpha at 0.95, saturation at 0.7
- **Rounded Panels**: Panel roundness at 0.4 for a modern look
- **Enhanced Gizmo Visibility**: Turquoise/purple color scheme for manipulators
- **Transparency Checker**: Optimized display of transparent areas
- **Status Colors**: Emerald for success, amber for warnings, red for errors, pink for info

### Neon Dark - Specific Features

- **Futuristic Atmosphere**: Deep dark backgrounds for immersive work
- **Glowing Accents**: Luminous cyan/turquoise colors for a tech feel
- **High Contrast**: Optimal readability for text and UI elements
- **Dark Editor Border**: `#0a0e1a` for clear separation
- **Reduced Eye Strain**: Ideal for night work and long sessions
- **Futuristic Design**: Modern, technical appearance
- **Optimized for Low Light**: Perfect for dimly lit studios and home offices

### Neon Light - Specific Features

- **Vibrant Accents**: Cyan/magenta highlights on a light background
- **Daylight Optimization**: Ideal for well-lit workspaces
- **Clear Element Separation**: Distinct visual hierarchy between UI components
- **Light Panels**: White and light gray panels for maximum clarity
- **Professional Appearance**: Perfect for client presentations
- **Screenshot-Friendly**: High-quality visuals for documentation
- **Light Editor Border**: `#ffffff` for smooth transitions

## Technical Specifications

### Theme Parameters

| Parameter | Dark | Light | Description |
|-----------|------|-------|-------------|
| `menu_shadow_fac` | 0.4 | 0.4 | Shadow intensity for menus |
| `menu_shadow_width` | 6 | 6 | Shadow width in pixels |
| `icon_alpha` | 0.95 | 0.95 | Icon transparency |
| `icon_saturation` | 0.7 | 0.7 | Icon color saturation |
| `panel_roundness` | 0.4 | 0.4 | Panel corner roundness |
| `transparent_checker_size` | 8 | 8 | Transparency checker size |

### Widget Color Definitions

#### Neon Dark

| Widget Type | Outline | Outline (Selected) | Inner | Inner (Selected) |
|-------------|---------|-------------------|-------|------------------|
| Regular | `#1e293b` (80%) | `#22d3ee` | `#0f1419` | `#06b6d4` |
| Tool | `#1e293b` (80%) | `#22d3ee` | `#0a0e1a` | `#0891b2` |
| State | `#334155` (80%) | `#10b981` | `#0f1419` | `#059669` |

#### Neon Light

| Widget Type | Outline | Outline (Selected) | Inner | Inner (Selected) |
|-------------|---------|-------------------|-------|------------------|
| Regular | `#cbd5e1` (80%) | `#22d3ee` | `#f8fafc` | `#06b6d4` |
| Tool | `#cbd5e1` (80%) | `#22d3ee` | `#ffffff` | `#0891b2` |
| State | `#94a3b8` (80%) | `#10b981` | `#f8fafc` | `#059669` |

### File Sizes

- **Neon Dark XML**: ~50 KB
- **Neon Light XML**: ~50 KB
- **Dark Manifest (TOML)**: ~270 Bytes
- **Light Manifest (TOML)**: ~280 Bytes

### Compatibility

- **Minimum Blender Version**: 4.2.0
- **Tested with**: Blender 4.2.0, 4.2.1, 4.3.0
- **Extension Schema**: 1.0.0
- **Operating Systems**: Windows, macOS, Linux
- **Theme Format**: Blender XML Theme Format

## File Structure

```
bim-toolbox-theme-neon/
├── README.md
├── LICENSE
├── neon_BlenderV4/
│   ├── blender_manifest.toml
│   └── bim_toolbox_neon_B4.xml
├── neon_BlenderV5/
│   ├── blender_manifest.toml
│   └── bim_toolbox_neon_B5.xml
├── neon-light_BlenderV4/
│   ├── blender_manifest.toml
│   └── bim_toolbox_neon_light_B4.xml
└── neon-light_BlenderV5/
    ├── blender_manifest.toml
    └── bim_toolbox_neon_light_B5.xml
```

## Troubleshooting

### Theme is not showing up

**Problem**: After installation, the theme does not appear in the theme list.

**Solutions**:
1. **Check Blender version**:
   - Open `Help` → `About Blender`
   - Make sure version 4.2.0 or higher is installed
   - For older versions: Update Blender

2. **Check extension activation** (Method 1 only):
   - Navigate to `Edit` → `Preferences` → `Extensions`
   - Search for "BIM Toolbox Neon"
   - Enable the checkbox if it is disabled

3. **Manual installation as fallback**:
   - If the extension method fails, use Method 2
   - The XML file can be imported directly via `Preferences` → `Themes`

### Colors look different than documented

**Problem**: The displayed colors differ from the documented hex values.

**Solutions**:
1. **Verify the correct theme variant**:
   - `Edit` → `Preferences` → `Themes`
   - Check whether "BIM Toolbox Neon" (Dark) or "BIM Toolbox Neon Light" is selected
   - The names are clearly distinct

2. **Color management settings**:
   - Open `Render Properties`
   - Check under `Color Management`:
     - Display Device: sRGB (Default)
     - View Transform: Standard (not Filmic)
   - Only change these settings if you understand the implications

3. **Conflict with other extensions**:
   - Temporarily disable other theme or UI extensions
   - Test whether the issue persists
   - Re-enable extensions one by one to identify the conflict

4. **Monitor calibration**:
   - Check your monitor settings (brightness, contrast, color temperature)
   - Compare colors across different devices
   - OLED/HDR displays may render cyan tones more intensely

### Extension fails to install

**Problem**: Error message when trying to install the extension.

**Solutions**:
1. **Check ZIP structure**:
   - Extract the ZIP file for testing
   - The file `blender_manifest.toml` MUST be in the root directory
   - Wrong: `neon.zip/neon-v2025.12.07/blender_manifest.toml`
   - Right: `neon.zip/blender_manifest.toml`
   - **Tip**: Compress the contents of the folder, not the folder itself

2. **Permission issues**:
   - Make sure you have write access to the Blender configuration directory
   - Windows: `C:\Users\[User]\AppData\Roaming\Blender Foundation\Blender\[Version]\`
   - macOS: `~/Library/Application Support/Blender/[Version]/`
   - Linux: `~/.config/blender/[Version]/`

3. **Validate manifest file**:
   - Open `blender_manifest.toml` in a text editor
   - Check that all required fields are present:
     - `schema_version = "1.0.0"`
     - `id` (unique ID)
     - `version`
     - `name`
     - `type = "theme"`

4. **Alternative: Manual installation**:
   - Use Method 2 (see Installation)
   - The XML file works independently of the extension system

### Theme switching does not work

**Problem**: After selecting a theme, the appearance does not change.

**Solutions**:
1. **Restart Blender**:
   - Save your work
   - Close Blender completely
   - Reopen Blender
   - The theme should now be active

2. **Startup file overrides theme**:
   - `File` → `Defaults` → `Load Factory Settings`
   - Select the theme again
   - `File` → `Defaults` → `Save Startup File`

3. **Save preferences**:
   - After switching themes: `Edit` → `Preferences`
   - Bottom left: Click the hamburger menu icon
   - Select `Save Preferences`

### Panels or buttons are hard to read

**Problem**: Text or UI elements have insufficient contrast.

**Solutions**:
1. **Switch theme variant**:
   - If Dark is too dark: Switch to Light
   - If Light is too bright: Switch to Dark
   - Your ambient lighting significantly affects readability

2. **Adjust monitor brightness**:
   - Increase monitor brightness in dark rooms
   - Reduce monitor brightness in daylight

3. **Customize theme** (Advanced):
   - Navigate to `Edit` → `Preferences` → `Themes`
   - Expand individual categories (e.g., "User Interface")
   - Adjust specific colors manually
   - Note: Changes will be lost when the theme is updated

## Frequently Asked Questions (FAQ)

### Installation & Usage

**Q: Can I install both variants (Dark and Light) at the same time?**

A: Yes, absolutely! Both variants can be installed side by side and you can switch between them at any time. Simply go to `Edit` → `Preferences` → `Themes` and select the desired variant from the dropdown list.

**Q: Does the theme work with older Blender versions?**

A: The extension method strictly requires Blender 4.2.0 or higher. Manual XML installation could theoretically work with older versions (3.0+), but this is not officially tested or supported. We recommend using Blender 4.2+ for best compatibility.

**Q: Do I need to reselect the theme every time I start Blender?**

A: No. After selecting the theme, save your preferences via `Edit` → `Preferences` → Hamburger menu → `Save Preferences`. The theme will then remain active permanently.

**Q: Can I switch between Dark and Light without reinstalling?**

A: Yes, if both variants are installed, you can switch between them at any time in the theme settings. The switch takes effect immediately without a restart.

### Customization & Modification

**Q: Can I customize the colors to my liking?**

A: Yes, in two ways:

1. **Directly in Blender**: `Edit` → `Preferences` → `Themes` → Expand the categories and change individual colors. Note: Changes will be lost when the theme is updated.

2. **Edit the XML file**: Open the `.xml` file in a text editor and modify the hex color codes. Save as a new XML file and install it as a custom theme.

**Q: Can I save my customizations as a separate theme?**

A: Yes! In Blender: `Edit` → `Preferences` → `Themes` → Click the `+` icon next to the theme name → Enter a new name → Your customizations will be saved as a new theme.

**Q: How can I share my theme settings with others?**

A: Go to `Edit` → `Preferences` → `Themes` → Click the gear icon → `Export Theme` → Save the XML file → Share this file with others.

### Updates & Maintenance

**Q: Are the themes updated regularly?**

A: Yes, the themes are updated alongside design changes to the BIM Toolbox web platform. Updates are distributed through the same channels as the initial installation.

**Q: How do I find out about theme updates?**

A: Updates are announced on the BIM Toolbox website (https://github.com/iF0xit/bim-toolbox-theme-neon). With extension installation, updates may become available through Blender's Extension Manager in the future (depending on the Blender roadmap).

**Q: Do I need to reinstall when updating?**

A: Yes, download the new version and install it using the same method as the first time. Your theme selection will be preserved, but custom modifications will be lost.

### Technical Questions

**Q: Does the theme affect render performance?**

A: No, themes only affect Blender's user interface, not the render engine or performance.

**Q: Does the theme work with all Blender workspaces?**

A: Yes, the theme applies globally to all workspaces (Modeling, Shading, Animation, etc.) and all editor types.

**Q: Is the theme compatible with other extensions?**

A: Generally yes. Conflicts can only occur with other theme extensions or UI-modifying extensions. In that case: Disable the conflicting extensions or load the theme after the other extension.

**Q: Why do the cyan tones look different on my monitor?**

A: Cyan is a very monitor-dependent color. OLED displays show more intense cyan than LCD displays. HDR settings can increase brightness. This is normal behavior and not a theme bug. Calibrate your monitor for consistent colors.

### License & Usage

**Q: Can I use the theme commercially?**

A: Yes, the theme is licensed under GPL-3.0-or-later and can be used freely, including in commercial projects.

**Q: Can I modify and redistribute the theme?**

A: Yes, under the terms of the GPL-3.0 license. Modified versions must also be licensed under GPL-3.0 and distributed with the source code (XML file).

**Q: Do I need to credit iF0xit when using the theme?**

A: Not required, but greatly appreciated! A mention in credits or documentation supports the project.

## License

**GPL-3.0-or-later** (GNU General Public License Version 3 or later)

This theme is **free software** and may be freely used, modified, and redistributed under the terms of the GNU General Public License Version 3 or later.

### What does this mean?

- **Free Use**: You may use the theme for private and commercial purposes
- **Modification**: You may customize the theme to your needs
- **Redistribution**: You may redistribute the theme and modifications
- **Source Code**: When redistributing, you must include the XML files (source code)
- **Same License**: Modified versions must be licensed under GPL-3.0+
- **No Warranty**: The theme is provided "as is" without any warranty

### Full License Text

The full license text can be found at: https://www.gnu.org/licenses/gpl-3.0.html

## Support & Contact

- **Maintainer**: iF0xit
- **Issues & Bugs**: https://github.com/iF0xit/bim-toolbox-theme-neon/issues

## Version History

### v2026.04.08

- Initial public release
- Neon Dark and Neon Light variants
- Blender 4.2+ and 5.0+ extension support
- Manual XML installation as an alternative


## Disclaimer & Notes

### Use at Your Own Risk

This software is provided "AS IS" without any express or implied warranty. Use is at your own risk. The author assumes no liability for any damages arising from the use of this software.

See the LICENSE file (GPL-3.0) for the full legal disclaimer.

### AI-Assisted Development

Parts of this project were developed with the assistance of AI tools. Final review and approval is performed by the maintainer. AI-generated content has been reviewed for correctness, but no guarantee of being error-free is provided.

---

**Last Update**: 2026-04-08
