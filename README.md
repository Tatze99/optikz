README for optikz.sty

# optikz – Draw Optical Setups in TikZ

**Author**: Martin Beyer  
**Released**: July 29, 2025  
**License**: LaTeX Project Public License (LPPL Version 1.3c 2008-05-04)
**Contact**: martinbeyer99@googlemail.com

See http://www.ctan.org/tex-archive/help/Catalogue/licenses.lppl.html for the details of the license.

## Overview

`optikz` is a LaTeX package that provides a library of customizable optical components for drawing laser setups and optical systems using TikZ.

It includes a variety of elements such as:
- **Lenses** (convex, concave, etc.)
- **Mirrors** (flat, curved)
- **Detectors** (cameras, spectrometers, photodiodes)
- **Devices** (Faraday rotator, Pockels cell, microscope objective, laser head)
- **Other components** waveplates, splitters, parabolas, gratings
- **Rays and beams** rainbow beam for stretchers and compressors, single color beams

Each component can be easily customized with intuitive optional arguments to control angle, size, color, thickness, labels, and more.

## Features

- Built entirely on TikZ – no external dependencies (other than xparse and xcolor)
- Consistent usage of arguments and minimal syntax
- Showcase of sophisticated setups and examples in the documentation
- Compatibility with TikZ coordinates
- Customizable styling (color, rotation, labels)
- Easily extendable and changeable

## Usage

Include the package in your LaTeX document:

```latex
\usepackage{optikz}