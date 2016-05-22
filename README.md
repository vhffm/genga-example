# Genga Examples

This repository contains example initial conditions and parameter files for [Genga](https://bitbucket.org/sigrimm/genga/).

## Examples

| Directory | Description |
| --------- | ----------- |
| solar | Solar system planets (19-03-2015). |
| solar_ex | Solar system planets (19-03-2015) with some Earth crossers as massless tracer particles. |
| formation | Disk with 2000 massive planetesimal, eccentric Jupiter and Saturn (EJS), and a decaying gas disk. |

Each directory contains a Makefile to remove all simulation outputs. Simply run "make clean".

## Post-Processing

A demonstration of how to load Genga outputs into Python/Pandas is available in this [Jupyter notebook] (https://cheleb.net/ipython/astro/04-GengaPandas.html). Note that the functionality has also been wrapped into [this Python script](https://github.com/vhffm/G3/blob/master/Helpers/io_helpers.py) with various routines and scripts also available [here](https://github.com/vhffm/G3).

## Contact

Questions, comments, rants should be sent to [volker@cheleb.net](mailto:volker@cheleb.net).

