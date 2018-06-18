# Central Hypothesis

Precipitation clustering and timing has an effect on soil carbon stocks and distribution.

To examine precipitation clustering we will assume a one pool model at quasi-steady state and then examine the effects of climate (air temperature and precipitation) on the inferred bulk decay rate.

# Harmonized data product including 

  1) soil organic carbon [mass-percent and g cm-3]
  2) soil characteristics [lat-lon, depth, pH, clay, ...]
  3) net primary production (modern multi-decadal mean)
  4) 1 m air temperature (daily)
  5) precipitation (daily)
  6) [tentative] water table data

**Soil data** will be taken from ISCN3 (possibly ISCN4), a compilation of various national soil surveys, and will only include data points with organic carbon (as both a mass-percent and g cm-3), soil layer depth, latitude, longitude, time of observation. Other soil characteristics may include pH, clay, and C:N ratios.

**Net primary production** will be taken from MODIS and used to approximate soil inputs.

**Climate** variables (1-m air temperature and precipitation) will be taken from CRU at a daily resolution (if possible). Calculate a temperature corrected bulk density using Q10. Open question on how to analyze quantity vs frequency but one possible approach might be FFT.

**Hydrological** variables like water table depth are on a wish list but we aren't sure where they would come from right now.

## Summer 2018 Timeline

Week | Theme | Notes     | Outcome
-----|-------|-----------|---------
June 11 | organization and scope | @vlbailey and @bpbond meet to draft project scope | initial draft of scope document
June 18 | identify data products | Monday meeting refined scope and identified targeted data products | 1. set up Git Hub repository 2. script download + ingest of ID-ed data products
June 25| visulize data products | |
July 2 | match locations across data types | |
July 9 | | @ktoddbrown is out |
July 16| | @ktoddbrown is out |
July 23| QA/QC data | |
July 30| calculate bulk decay | |
August 6| correct bulk decay for temperature | |
August 13| visulize decay across precipitation | |
August 20| documentation | | 
August 27| hand off project | | 

Current plan is weekly calls/meetings with @vlbailey @bpbond and @ktoddbrown

@ktoddbrown is funded at 25% from June-August of 2018 for a total of ~160 hours.

## From the proposal

>Data harmonization
>
>We will leverage a number of open-source datasets relevant to soil carbon, soil gas fluxes, baseline climate, and extreme event (e.g., drought) frequency and contribute to community efforts to harmonize data from previous studies (e.g., ISCN*). These include, for example, data on rewetting-associated gas fluxes of CH4 and CO2 under both field and laboratory conditions39; the Global Soil Respiration Database of seasonal to annual soil surface CO2 flux observations105; and the SoilGrids 1 km dataset.106 Such data can be matched to synthesis, wall-to-wall satellite, and statistical upscaling products (e.g., climate, global gross primary production, and FLUXNET2015) to draw powerful inferences about larger-scale carbon cycle dynamics that then pose local-scale hypotheses,107–109 and compare how controls on GHG production and soil dynamics change at various spatial and temporal scales.13,35

### Alternative possible analysis for future

1) Map local climate to incubation data, check out Carlos Sierra's temperature incubation data product.
2) Map local climate to incubation data to Ameriflux sites
3) Pull soil rewetting incubations from the literature



