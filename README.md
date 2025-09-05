# Master Thesis: Sound-Based AI and Augmented Reality for Interactive Systems

**Author**: Nathan VIDAL  
**Date**: 21 November 2024
**Supervisors**: Xiao Xiao 

This repository contains the LaTeX source code and assets for my master thesis exploring the integration of sound-based artificial intelligence and augmented reality to develop interactive systems for environmental monitoring, emotional expression, and immersive learning. The thesis presents three distinct projects that demonstrate the potential of AI and AR to transform Human-Computer Interaction in conservation, education, and performance arts.

## Project Structure

- `main.tex`: The main LaTeX file that compiles the entire thesis document.
- `chapters/`: This folder contains separate `.tex` files for each chapter and section of the thesis.
  - `01_introduction.tex`: Introduction and background motivation.
  - `02_SOTA.tex`: State of the art in sound-based AI, TTS systems, and AR technologies.
  - `03_BirdClassification.tex`: Machine learning for bird species classification through vocalizations.
  - `04_EmotionTTS.tex`: Development of an emotionally adaptive text-to-speech system.
  - `05_TheatreApplication.tex`: AR-based theater training platform with virtual character interaction.
  - `06_Conclusion.tex`: Final conclusions and future work.
  - `abstract.tex`: Thesis abstract.
  - `acknowledgements.tex`: Acknowledgements section.
- `images/`: Contains all figures, diagrams, and illustrations used in the thesis.
- `main.bib`: The BibTeX file containing all references cited throughout the thesis.
- `chapters/appendix/`: Any supplementary material, including additional graphs, detailed technical designs, or extended evaluation results.
- `styles/`: LaTeX configuration files (e.g., for formatting, styles, and packages).
- `kaobook.cls`: Custom LaTeX document class used for thesis formatting.
- `docs/`: Additional documentation and project files.
- `temp.ipynb`: Jupyter notebook for data analysis and experimentation.

## Requirements

To compile the thesis, you'll need a working LaTeX distribution. The recommended toolchain includes:

- **TeX Live** (for a full LaTeX environment)
- **Biber** (for bibliography management)

### Recommended LaTeX Editors:

- **VSCode** with LaTeX Workshop plugin
- **Overleaf** (for online collaboration)

## Compilation Instructions

### Locally

You can compile the entire thesis into a PDF by running:

```bash
./compileall.sh
```

This will:

1. Compile `main.tex` with references and citations.
2. Run `Biber` to process the bibliography.
3. Generate the final PDF output in the root directory.

### Overleaf

1. Upload the entire repository to Overleaf.
2. Set `main.tex` as the root document.

## Contribution

This repository is meant for academic and personal use.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Thesis Overview

This thesis presents three interconnected projects:

1. **Bird Species Classification**: A machine learning system for classifying bird species through their vocalizations, contributing to accessible bioacoustic monitoring for environmental conservation.

2. **Emotionally Adaptive TTS System**: Development of a text-to-speech system that can express emotions, enhancing Human-Computer Interaction with more lifelike and engaging vocal interfaces.

3. **AR Theater Training Platform**: An augmented reality application that combines TTS and AR technologies to create an immersive theater training environment where students can interact with virtual characters and receive real-time feedback.

For any questions, feel free to contact the author through the university.