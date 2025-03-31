
<!-- README.md is generated from README.Rmd. Please edit that file -->

# nfittoosm

<!-- badges: start -->
<!-- badges: end -->

Package build to prepare NFI ground plot data into OSM input data using
`data.table`.

To explore what fields exists in NFI ground plot data go to their
[documentation page](https://nfi.nfis.org/en/ground_plot).  
To request NFI data you can go to their [form
webpage](https://nfi.nfis.org/en/datarequestform).  
Details about Open Stand Model (OSM) are found at [FORUS Research
webpage](https://forusresearch.com/downloads/osm/index.html).

# Uses

This package contains only one main function to produce the OSM input
that from NFI. Make sure to explore its documentation `?nfi_to_osm()` to
learn about about how you can modify some of the data translation
parameters.

``` nfi
osm_example <- nfi_to_osm()
```

The function creates the two required data tables Stand List Table and
Tree List Table. [OSM Input Data
Details](https://forusresearch.com/downloads/osm/help/OSM.HelpFiles/OSM.Input.htm).

``` table
osm_example
```

Contact the developer if any issues found.
