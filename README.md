# Songjam Lite Paper

This is the Songjam Lite Paper - A Cryptographic Voice Verification System

## Prerequisites

To compile this LaTeX document, you need:
- A LaTeX distribution (e.g., TeX Live, MiKTeX, or MacTeX)
- A PDF viewer

## Project Structure

- `main.tex`: The main LaTeX document
- `references.bib`: Bibliography file
- `Makefile`: For easy compilation

## How to Compile

1. Using Make (recommended):
   ```bash
   make        # Compile the document
   make clean  # Clean temporary files
   ```

2. Manual compilation:
   ```bash
   pdflatex main
   bibtex main
   pdflatex main
   pdflatex main
   ```