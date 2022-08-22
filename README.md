# rsaccharis
An R package for beautifying the output of SACCHARIS.

This package will use metadata .json and .tree files output from SACCHARIS v2 to generate annotated phylogenetic tree PDF files. Highly customizable, as the formatting of the tree is done using ``ggtree`` and ``ggplot2``. Of course plotting functions can easily be manipulated as desired.

## Usage

Install package using R/R Studio, and run both functions:

``A_load_data()``

``B_plots_all()``

Follow prompts to provide .json and .tree files.

If it helps, our default plots used are domain_ECno_numeric, and we pretty them up further using Inkscape.

## Citation
Citation to come soon.

Please note ``rsaccharis`` uses a number of other R packages to function. Thanks to those authors.

Please cite as necessary:

1. G Yu. Using ggtree to visualize data on tree-like structures. Current Protocols in Bioinformatics, 2020, 69:e96. doi: 10.1002/cpbi.96.

2. H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2016. https://ggplot2.tidyverse.org

## Creators
Greta Reintjes (<greintje@mpi-bremen.de>)
Kristin E. Low (<kristin.low@agr.gc.ca>)
