# Master Thesis: How Can Sensing Techniques Redefine Our Interaction with Plants?

**Author**: Matthieu SEGUI  
**Date**: Not finished yet  
**Supervisors**: Clément Duhart, Marc Teyssier  

This repository contains the LaTeX source code and assets for my master thesis titled _"How Can Sensing Techniques Redefine Our Interaction with Plants?"_. The thesis explores the integration of bio-sensing techniques, the Internet of Plants (IoP), and sonification to enhance human-plant interaction. The work presents technical prototypes, theoretical backgrounds, user studies, and a final discussion on the applications and future directions of this research.

## Project Structure

- `main.tex`: The main LaTeX file that compiles the entire thesis document.
- `chapters/`: This folder contains separate `.tex` files for each chapter and section of the thesis.
  - `01_introduction.tex`: Introduction and background motivation.
  - `02_SOTA.tex`: State of the art, including plant sensors, sonification, and IoP technologies.
  - `03_contribution_1.tex`: Technical implementation of plant-based sensors.
  - `04_contribution_2.tex`: Concept and architecture of the Internet of Plants.
  - `05_conclusion.tex`: Final conclusions and future work.
- `images/`: Contains all figures, diagrams, and illustrations used in the thesis.
- `main.bib`: The BibTeX file containing all references cited throughout the thesis.
- `appendices/`: Any supplementary material, including additional graphs, detailed technical designs, or extended evaluation results.
- `style/`: LaTeX configuration files (e.g., for formatting, styles, and packages).

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

For any questions, feel free to contact me on Linkedin: [Link to profile](www.linkedin.com/in/matthieu-segui).