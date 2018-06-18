_Central Hypothesis:_
Precipitation clustering and timing has an effect on C stocks and distribution.

_From the proposal:_
>Data harmonization
>We will leverage a number of open-source datasets relevant to soil carbon, soil gas fluxes, baseline climate, and extreme event (e.g., drought) frequency and contribute to community efforts to harmonize data from previous studies (e.g., ISCN*). These include, for example, data on rewetting-associated gas fluxes of CH4 and CO2 under both field and laboratory conditions39; the Global Soil Respiration Database of seasonal to annual soil surface CO2 flux observations105; and the SoilGrids 1 km dataset.106 Such data can be matched to synthesis, wall-to-wall satellite, and statistical upscaling products (e.g., climate, global gross primary production, and FLUXNET2015) to draw powerful inferences about larger-scale carbon cycle dynamics that then pose local-scale hypotheses,107–109 and compare how controls on GHG production and soil dynamics change at various spatial and temporal scales.13,35

Most of these are standard and available products. The big exception and central dataset of this effort is the first: rewetting-associated gas flux data.

(Note on above: we will also want to pull 1) soil texture information and any depth resolutions; 2) total OC, if that’s parsed out from Total C; and 3) any information about precipitation vs water table depth, with seasonality, that can be gleaned.)

Three months seems like a good amount of time to define variables of interest (i.e. that are required); contact PIs for datasets and work out sharing/credit; assemble the data, and write scripts (akin to the ISCN scripts Kathe has already spent lots of time on) normalizing each into a common format. This will provide a solid foundation for moving forward with a synthesis analysis (with which KTB will of course be involved).

This could be structured as:
- First two weeks: Work with BBL and VLB to define specific analyses planned and variables required, and identify PIs to contact for data, as well as openly available datasets (e.g. continuous soil respiration datasets from dry ecosystems with occasional rainfall)
- Middle ten weeks: Contact PIs, assemble datasets, write normalization scripts, QA/QC data if time.
  + Target data for an analysis using (let’s assume for now) R’s metafor package
- Final two weeks: Prepare summary document on what’s been done, how to run scripts, plans for next steps.



