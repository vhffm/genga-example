# Genga Examples

This repository contains example initial conditions and parameter files for [Genga](https://bitbucket.org/sigrimm/genga/).

## Examples

| Directory | Description |
| --------- | ----------- |
| solar | Solar system planets. |
| solar_ex | Solar system planets with some Earth crossers as massless tracer particles. |
| formation | Disk with 2000 massive planetesimal, eccentric Jupiter and Saturn (EJS), and a decaying gas disk. |

Solar system planets are loaded from the [NASA/JPL Horizons](http://ssd.jpl.nasa.gov/horizons.cgi) system. Earth crossing asteroids are extracted from the [Astorb](http://asteroid.lowell.edu/external/astorb) database. State vectors are from 19 March 2015, JDTDB (Epoch Julian Date, Barycentric Dynamical Time).

Each directory contains a Makefile to remove all simulation outputs. Simply run "make clean".

## Post-Processing

A demonstration of how to load Genga outputs into Python/Pandas is available in this [Jupyter notebook] (https://cheleb.net/ipython/astro/04-GengaPandas.html). Note that the functionality has also been wrapped into [this Python script](https://github.com/vhffm/G3/blob/master/Helpers/io_helpers.py) with various routines and scripts also available [here](https://github.com/vhffm/G3).

## Contact

Questions, comments, rants should be sent to [volker@cheleb.net](mailto:volker@cheleb.net).

