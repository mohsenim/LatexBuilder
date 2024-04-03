![GitHub Actions Status](https://github.com/mohsenim/LatexBuilder/actions/workflows/main.yml/badge.svg)
![MIT - License](https://img.shields.io/pypi/l/mfdfa-toolkit)


# Latex Builder

This repository simplifies the process of compiling your LaTeX project using GitHub Actions. You only need to upload your files to the `files` directory and rename the main TeX file to `main.tex`. Additionally, ensure that write permissions for GitHub Actions workflows are enabled in the repository settings.

After each push, the compiled PDF file will be accessible in the release section of the repository under the name `main.pdf`.

For more specific requirements, please refer to the [latex-action](https://github.com/xu-cheng/latex-action) repository.