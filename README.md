# signal_processing_for_wxmaxima
A collection of function modules for doing discrete-time signal processing with [wxMaxima](https://wxmaxima-developers.github.io/wxmaxima/).

## Introduction
This package is mostly about doing numerical calculations and plotting for discrete-time signal processing analysis, modeling and simulation. I started to write it in January 2025 as an experiment to see how far I could take things from my experience with other tools, most notable Python and Julia. I was pleasantly surprised! Maxima is not as fast as Python and Julia, but you get the power of a full *computer algebra system* (CAS). There are some interesting possibilities that I will explore in the examples document.

## The modules
There are currently three modules that constitute this package:

* `DSPTools.mac` 
* `CommTools.mac`
* `FilterTools.mac`

The documentation was build using [Typst](https://typst.app/home/) and write code in a wxMaxima document. A [documentation and examples pdf](docs/sp_tools_wxmaxima.pdf) is contained in the `docs` folder.

I welcome feedback and have plans for enhancing the code base.