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
    git clone https://github.com/JuanDavidBarrero/KicadLibJuanDavid.git
    ```

2. **Set up the Libraries in KiCad**:

    - Add the path to the lib and call it `JUANDA_LIB`
    - Open KiCad and go to `Preferences` > `Configure Paths`.
    - Click `Add`.
    - In the `Name` field, enter `JUANDA_LIB`.
    - In the `Path` field, enter the full path to the library folder (e.g., `C:/Users/JuanDavid/Libraries`).
    - Click `OK` to save the environment variable.
    - Open KiCad and go to `Preferences` > `Manage Libraries`.
    - In the `Symbol Libraries` tab, add the key `JuanDavid_Library` with path `${JUANDA_LIB}/symbols/JuanDavid_Library.kicad_sym`.
    - In the `Footprint Libraries` tab, add the key `JuanDavid_Library` the path `${JUANDA_LIB}/footprints/JuanDavid_Library.pretty`.
    - In the `3D Models` tab, add the path `${JUANDA_LIB}/3d_models`.


## Contributions

Contributions are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b new-branch`).
3. Make your changes and commit them (`git commit -m 'Description of change'`).
4. Push to the branch (`git push origin new-branch`).
5. Create a Pull Request.
