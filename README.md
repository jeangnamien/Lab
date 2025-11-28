# Business Card Project

This repository contains my personal business card written in LaTeX, as part of the Git & GitHub practice assignment.  
The project demonstrates the full Git workflow (branches, commits, merge, ignore files) as well as an automated LaTeX build and release system using GitHub Actions.

---

## 📇 Project Description

The project is based on a LaTeX template for generating a business card.  
I customized the template by adding my personal information and updating the logo.

Git was used to:

- Initialize a local repository  
- Track and commit source files  
- Create and merge branches  
- Ignore generated (compiled) files  
- Configure GitHub Actions for automatic PDF release  

---

## 🔧 Requirements

To manually compile the card on your machine, you need:

- **XeLaTeX** (preferred)  
- Or **pdflatex** (if using machines without XeLaTeX)  
- A working TeX distribution (TeX Live, MiKTeX, etc.)

If XeLaTeX fails, comment out the custom font lines in `card.tex`.

---

## 🧪 Manual Compilation

To compile the business card locally:

```bash
xelatex card.tex
