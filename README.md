# Awesome CV: Andrea Maioli

This project is a CV/Resume for Andrea Maioli, built using LaTeX.

## Prerequisites

To build this CV, you need a LaTeX distribution installed on your system, specifically one that includes `xelatex`.
This project uses the `awesome-cv` class.

## Building the CV

You can compile the CV using `xelatex`:

```bash
xelatex resume.tex
```

This will generate a `resume.pdf` file.

Alternatively, this repository includes a GitHub Actions workflow that automatically builds the PDF on every push to `main` or `master`. The built PDF is available as an artifact in the Actions tab.

## Project Structure

- `resume.tex`: The main LaTeX file for the CV.
- `awesome-cv.cls`: The Awesome CV class file.
- `fontawesome.sty`: Style file for FontAwesome icons.
- `fonts/`: Directory containing fonts used in the CV.
- `resume/`: Directory containing sections of the CV:
    - `experience.tex`
    - `education.tex`
    - `techskills.tex`
    - `projects.tex`
    - `languages.tex`
    - `hobby.tex`
    - `dreams.tex`
    - `honors.tex`

## Acknowledgements

This project is based on the **Awesome CV** LaTeX template.
Original Template: [Awesome CV on Overleaf](https://it.overleaf.com/latex/templates/awesome-cv/dfnvtnhzhhbm)
GitHub Repository: [posquit0/Awesome-CV](https://github.com/posquit0/Awesome-CV)

Author references from the template:
- Claud D. Park <posquit0.bj@gmail.com>
- http://www.posquit0.com
