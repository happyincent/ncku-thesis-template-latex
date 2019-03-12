## Introduction

Use LaTeX in **VSCode** with LaTeX Workshop extension.

Add `% !TeX root = [path to thesis.tex]` in the first line of every `.tex` file

https://github.com/wengan-li/ncku-thesis-template-latex-sample/raw/master/thesis%20(demo).pdf

## Installation

1. Install [MiKTeX](https://miktex.org/download) with exe Installer

    > Install missing packages on-the-fly: **Yes**

2. In VSCode, press `Ctrl + p` : `ext install latex-workshop`

## Usage

#### First time
`F1` or `Ctrl + Shift + p`: `LaTeX Workshop: Build with recipe`: xe->xe
> in **thesis.tex**

#### Without *Reference*
`F1` or `Ctrl + Shift + p`: `LaTeX Workshop: Build LaTeX project`
> using default (first) recipe : xe

#### With *Reference*
`F1` or `Ctrl + Shift + p`: `LaTeX Workshop: Build with recipe`: xe->bib->xe->xe

#### Cleanup files
`F1` or `Ctrl + Shift + p`: `LaTeX Workshop: Clean up auxiliary files`
> or `find . -type f -name 'thesis.*' ! -name 'thesis.tex' -delete`