## Introduction

* Use LaTeX in **VSCode** with LaTeX Workshop extension

* Add `% !TeX root = [path to thesis.tex]` in the first line of every `.tex` file

* [wengan-li's demo PDF](https://github.com/wengan-li/ncku-thesis-template-latex-sample/raw/master/thesis%20(demo).pdf)

## Installation

1. Install [MiKTeX](https://miktex.org/download) with exe Installer

    > Install missing packages on-the-fly: **Yes**

2. In VSCode, press `Ctrl + p` : `ext install latex-workshop`

## Usage

#### Without *Reference*
`F1` or `Ctrl + Shift + p`: `LaTeX Workshop: Build LaTeX project`
> default (first) recipe: xe

> or recipe: xe->xe

#### With *Reference*
`F1` or `Ctrl + Shift + p`: `LaTeX Workshop: Build with recipe`: xe->bib->xe->xe

#### Cleanup files
`F1` or `Ctrl + Shift + p`: `LaTeX Workshop: Clean up auxiliary files`
> or `find . -type f -name 'thesis.*' ! -name 'thesis.tex' -delete`