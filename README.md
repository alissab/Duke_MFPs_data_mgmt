# Duke_MFPs_Brown_et_al
This repo contains R code used to analyze mapped forest plots in the Duke Forest for A. Brown's PhD dissertation.

### .R files:
- **data_mgmt** manipulating Duke Forest mapped forest plot (MFP) data in prep for analysis. 
- **mods_5m** model selection for growth/survival models at 5m spatial scale. 
- **mods_10m** model selection for growth/survival models at 10m spatial scale. 
- **mods_15m** model selection for growth/survival models at 15m spatial scale. 
- **mods_20m** model selection for growth/survival models at 20m spatial scale. 
- **best_mods** constructs final (best performing) models for all spatial scales; tests for spatial autocorrelation; constructs summary tables. 

### Background

**Brown, AJ, CJ Payne, PS White, and RK Peet. 2019. Shade tolerance and mycorrhizal type may influence sapling susceptibility to conspecific negative density dependence. *Journal of Ecology*  [https://doi.org/10.1111/1365-2745.13237](https://doi.org/10.1111/1365-2745.13237)**

The maintenance of tree diversity has been explained by multiple mechanisms. One of the most thoroughly studied is conspecific negative density dependence, in which specialist plant enemies reduce survivorship of seeds, seedlings or saplings located near adult conspecifics. Although there is much support that conspecific negative density dependence occurs in temperate forests, only a subset of the species investigated thus far exhibit this recruitment pattern. It remains unclear what drives differential susceptibility to conspecifics among tree species. Previous investigators have considered shade tolerance and mycorrhizal type (arbuscular mycorrhizal vs. ectomycorrhizal association) as two traits that might explain differential susceptibility to conspecific negative density dependence.

Here, we test whether these two plant traits predict susceptibility of tree saplings to conspecific negative density dependence in a temperate hardwood forest using three responses: spatial point patterns of saplings, sapling growth and sapling survival.

Spatial patterns of saplings indicate that shade tolerant species are less sensitive to conspecifics than shade intolerant species, but show no differences based on mycorrhizal type. Conversely, shade tolerant saplings exhibit reduced growth, but not survival, when located in areas with high conspecific density. We interpret this finding in light of the conservative functional strategies of shade tolerant species, which typically have low leaf nitrogen levels and slower growth to divert resources to tissue defence against enemies. We found an effect of mycorrhizal type interacting with adult conspecific density, where arbuscular mycorrhizal species show a greater reduction in growth than ectomycorrhizal species in areas dense with conspecifics.

Synthesis. We conclude that the shade tolerance level and the mycorrhizal type of temperate forest saplings may influence how their growth and survival respond to the adult conspecific trees in their neighbourhoods.
