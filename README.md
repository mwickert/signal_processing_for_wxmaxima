# signal_processing_for_wxmaxima
A collection of function modules for doing discrete-time signal processing with [wxMaxima](https://wxmaxima-developers.github.io/wxmaxima/).

## Introduction
This package is mostly about doing numerical calculations and plotting for discrete-time signal processing analysis, modeling and simulation. I started to write it in January 2025 as an experiment to see how far I could take things from my experience with other tools, most notable Python and Julia. I was pleasantly surprised! Maxima is not as fast as Python and Julia, but you get the power of a full *computer algebra system* (CAS). There are some interesting possibilities that I will explore in the examples document.

## The modules
There are currently three modules that constitute this package:

* `DSPTools.mac` 
* `CommTools.mac`
* `FilterTools.mac`

## Documentation and Examples

A [documentation and examples pdf](docs/sp_tools_wxmaxima.pdf) can be found in the `docs` folder. Teaching materials for related courses can be found on (https://faculty.uccs.edu/mwickert/). The examples here are mostly written using Python and Julia. As a challenge try to replicate some of them using the wxMaxima tools. 

### Tools used for Documentations

The documentation was build using [Typst](https://typst.app/home/). Here you can use the cloud-based tools by first writing code in a wxMaxima document and cutting and pasting directly into the Typst cloud editor. Graphics are taken from the wxMaxima window by right clicking over a graphic and from the floating menu choose *Popout interactively*. Next in the plot viewer export the graphic to `SVG`. Typst natively works with SVG.

## The future

I welcome feedback and already have plans for enhancing the code base.