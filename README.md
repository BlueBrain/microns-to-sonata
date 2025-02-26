> [!WARNING]
> The Blue Brain Project concluded in December 2024, so development has ceased under the BlueBrain GitHub organization.
> Future development will take place at: https://github.com/openbraininstitute/microns-to-sonata

# microns-to-sonata

Building a SONATA circuit from the MICrONS mm^3 data.
Ultimate goal is to create a Sonata model of the data that we can simulate.

## Overview

### Morphologies
Morphologies are skeletonized by Marwan. See https://bbpteam.epfl.ch/project/issues/browse/VIZTM-1311

### Connectivity
Synapse anatomy has been extracted from MICrONS into a conntility-based file format by Michael.
See https://doi.org/10.5281/zenodo.8364070

### Physiology
For neuron and synapse physiology we have not yet formulated a strategy

## Status
Currently, we have a jupyter notebook that uses the skeletonized morphologies and the synapse anatomy to create a Sonata CellCollection and a Sonata EdgeCollection, and writes them to disk.


# Funding & Acknowledgment
This development is supported by funding to the Blue Brain Project, a research center of the École polytechnique fédérale de Lausanne (EPFL), from the Swiss government's ETH Board of the Swiss Federal Institutes of Technology.
Copyright © 2024 Blue Brain Project/EPFL
