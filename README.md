# Surface Scratch Inspection Device

A reproducible handheld inspection system with controllable illumination for surface scratch visualization on polished metal surfaces.

---

## Project Status

This project is currently under preparation for academic publication in HardwareX.

The repository will be updated gradually with documentation, design files, software, and validation examples.

---

## Overview

Polishing inspection is often affected by operator experience, surface condition, lighting condition, and scratch orientation.

This project develops a handheld inspection device that integrates adjustable illumination, camera imaging, and real-time image processing to enhance the visibility of residual scratches on polished surfaces.

The system is designed as a reproducible academic version of the device, focusing on general inspection methodology rather than application-specific industrial parameters.

---

## Key Features

- Handheld inspection device for polished surface observation
- Adjustable illumination angle for enhancing scratch visibility
- Real-time camera preview
- Real-time scratch visualization using image processing
- Screenshot and video recording functions
- Calibration workflow for selecting suitable illumination conditions
- Designed for reproducible open-hardware documentation

---

## Repository Structure

```text
docs/
    Build instructions, operation manual, and calibration method

hardware/
    Public 3D-printable files, wiring information, and bill of materials

paper/
    HardwareX manuscript preparation files

src/
    Source code for camera control, GPIO control, GUI, and image processing
