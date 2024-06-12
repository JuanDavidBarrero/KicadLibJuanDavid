# Component Library for KiCad 8.0

## Description

This repository contains symbols, footprints, and 3D models for use in KiCad 8.0. It is designed to help PCB designers save time by providing a comprehensive and easy-to-use library.

## Content

- **Symbols**: Schematic representations of electronic components.
- **Footprints**: Physical representations of components for PCB design.
- **3D Models**: Three-dimensional representations of components for visualization and fit-check in PCB design.

## Repository Structure

- `symbols/`: Contains the symbol files.
- `footprints/`: Contains the footprint files.
- `3d_models/`: Contains the 3D model files.

## Requirements

- **KiCad 8.0**: Make sure to have KiCad version 8.0 installed to ensure compatibility.

## Usage Instructions

1. **Clone the repository**:
    ```sh
   git clone https://github.com/your_username/your_repository.git](https://github.com/JuanDavidBarrero/KicadLibJuanDavid.git
    ```

2. **Set up the Libraries in KiCad**:

    - Open KiCad and go to `Preferences` > `Manage Libraries`.
    - Add the paths to the `symbols`, `footprints`, and `3d_models` folders in their respective sections.

3. **Use the Components**:

    - In the schematic editor, select the symbol library you added and choose the component you need.
    - In the PCB editor, select the corresponding footprint.
    - The 3D models will load automatically if properly configured in the footprints.

## Contributions

Contributions are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b new-branch`).
3. Make your changes and commit them (`git commit -m 'Description of change'`).
4. Push to the branch (`git push origin new-branch`).
5. Create a Pull Request.
