# FrogNetworks
Analysis of co-calling networks for frog community data from the North American Amphibian Monitoring Program (NAAMP).

Foreman, T.M., Grant, E.H.C., and Weir, L.A., 2017, North American Amphibian Monitoring Program (NAAMP) anuran detection data from the eastern and central United States (1994-2015): U.S. Geological Survey data release, https://doi.org/10.5066/F7G44NG0
 

## Data files: 
*CountsWithComplexes.csv*- original NAAMP data for counts
*CountsWithoutComplexes.csv*- original NAAMP data for counts (excluding species complex designations)
*frogedgelist.csv*- edgelist generated from *CountsWithComplexes.csv* using *GenerateEdgeLists.Rmd*
*frogedgelist_cwoc.csv* - edgelist generated from *CountsWithoutComplexes.csv* using *GenerateEdgeLists.Rmd*


## Code files:
*GenerateEdgeLists.Rmd*- generate edgelists from *CountsWithComplexes.csv* and *CountsWithoutComplexes.csv* datasets
*CountsWithComplexes.Rmd*- generate frigures for *Hyla cinerea* for counts with complexes data using *frogedgelist.csv*
*CountsWithoutComplexes.Rmd*- generate frigures for *Hyla cinerea* for counts with complexes data using *frogedgelist_cwoc.csv*
*CWC_chrysoscelis.Rmd* -generate frigures for *Hyla chrysoscelis* for counts with complexes data using *frogedgelist.csv*
*CWOC_chrysoscelis.Rmd*- generate frigures for *Hyla chrysoscelis* for counts with complexes data using *frogedgelist_cwoc.csv*

## Figure metadata:
Figures were generated for two focal species *Hyla chrysoscelis* and *Hyla cinerea*. All *Hyla chrysoscelis* figures begin with "Chrysoscelis"

**Nomenclature:**
* cwoc= Counts without Complexes
* cwc= Counts with Complexes
* global= global network for given focal species
* dd= degree distribution
* star= star network
* circle =circle network
