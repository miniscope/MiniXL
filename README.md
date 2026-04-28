# MiniXL — Miniscope Extra Large FOV

The MiniXL is the second generation of the MiniLFOV, a large field-of-view miniature microscope for imaging neuronal activity in freely moving mice and larger animals. It supports deep brain imaging using implanted optical probes and cortical imaging through cranial windows.

## Features

- 3.5 mm field of view
- ~3 um resolution
- 1.9 mm working distance
- +/-200 um electronic focal adjustment
- Modular, achromatic optics
- 3.5 grams
- 30 mm tall
- Absolute head orientation sensor
- Single coaxial cable (down to 0.3 mm diameter) for power, communication, and data
- No soldering required

## Repository Structure

```
pcb/                PCB designs (KiCad)
  rigid-flex/       Main rigid-flex PCB assembly
    fabrication/    Gerber and drill files for manufacturing
optics/             Optical design (Zemax) source files
  plots/            Standardized output plots (MTF, spot diagrams, etc.)
housing/            3D printed microscope body
baseplate/          Head-mount baseplate
assets/             Images and resources for documentation
wiki.yml            Top-level metadata; per-component wiki.yml files in each subdir
                    are picked up by wiki-repo-bridge and synced on release tags.
```

## How to Cite

If you use the MiniXL in your research, please cite:

> Zhao, P., Guo, C., Xie, M., Chen, L., Golshani, P., & Aharoni, D. MiniXL: An open-source, large field-of-view epifluorescence miniscope enabling single-cell resolution and multi-region imaging in mice. *Science Advances*, 11(24), eads4995, 2025. DOI: [10.1126/sciadv.ads4995](https://doi.org/10.1126/sciadv.ads4995)

A BibTeX entry is available in [CITATION.bib](CITATION.bib).

## License

See [LICENSE](LICENSE) for details.
