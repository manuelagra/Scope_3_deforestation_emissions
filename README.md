# Scope_3_deforestation_emissions


Python script for the calculation of deforestation derived emissions of GHGs for the Gran Chaco


Global deforestation remains a primary driver of the climate crisis, contributing approximately 8.1±2.5 GtCO2 e yr−1 in emissions and serving as a leading cause of catastrophic biodiversity loss. In this context, commodity production for international trade—specifically cattle and crop production— is responsible for an estimated 86% of global deforestation occurring between 2001 and 2022*. South America is a global deforestation hotspot where agricultural expansion is the dominant engine of land-use change. The region's most critical biomes have experienced staggering reductions in natural cover: the Amazonia has lost approximately 14% of its original forest, the Cerrado has seen a 27% reduction, and the Gran Chaco has lost around 20% of its natural vegetation*. These processes represent a massive transfer of carbon from stable terrestrial pools to the atmosphere.  

 
Production-related impacts are classified as "Scope 3" emissions for food and agricultural companies, this means indirect emissions occurring in the value chain that frequently represent 80% to 90% of a company’s total carbon footprint*. While companies have historically focused on Scope 1 and 2 emissions, including land-use change (LUC) in corporate inventories is now a regulatory and scientific necessity under the GHG Protocol’s Land Sector and Removals Guidance (LSRG). This framework requires companies to provide site-specific evidence of direct land-use change (dLUC) to achieve completeness and transparency*. 

 

The concept of the deforestation footprint has emerged as a metric for quantifying these upstream impacts. This means the total volume of GHG emissions (expressed in MgCO2eq) associated with the conversion of natural vegetation to agricultural or pastureland per unit of area (ha)*.  Accurately calculating this footprint is essential because it is critical for calculating upstream emissions in complex supply chains and also because downstream companies often source from thousands of individual producers, making traditional on-the-ground data collection for tracking dLUC impractical and with high costs*.  

 

Standardized geospatial footprinting allows companies to identify hotspots of supply chain risk enabling targeted interventions and more credible reporting of their overall carbon and environmental footprints*. These calculations have significant relevance for reducing emissions from deforestation and forest degradation such as REDD+ projects*. Improved "upstream" forest monitoring and footprinting allow producing nations to better attribute emissions to specific drivers or industries, which is a rational scientific and financial investment for securing higher compensation through carbon payments*. By reducing uncertainties in carbon accounting prior to crediting, footprinting strengthens the environmental integrity of global mitigation efforts and prevents the offsetting of uncertain land-sector reductions*. 

 

Despite the importance of this metric, establishing a rigorous methodology remains complex*. Our research is framed by three critical questions currently facing landscape ecologists and corporate auditors: How can companies practically track the deforestation footprint when sourcing from thousands of producers? The immense scale of agricultural supply chains requires a shift toward scalable geospatial tools *. Considering the current scenarios of deforestation and high commodities demand, and their related indirect emissions of GHG, we ask the following questions: I) How do we bridge the gap between landscape-scale ecological data and corporate GHG inventory requirements? II) How do we standardize the footprint methodology to avoid double counting in biomes where multiple commodities (e.g., soy and beef) interact? it is vital to distribute emissions accurately across different levels of the supply chain. The establishment of a systematic methodology to define this footprint is therefore essential for promoting greater transparency and devising effective mitigation strategies. 
 
	The aim of this study is to present a novel systematic methodology for quantifying the deforestation footprint (MgCO2eq/ha) of past and current crop and pasture lands at pixel level as the minumum unit of analysis, using a new calculation methodology to estimate emissions of GHG (in MgCO2eq/ha/year). We present this methodological framework by analyzing GHG emissions at biome level for the Amazonia, Cerrado, and Gran Chaco. Conversion of forest in the three biomes was assessed from 2006 to 2023. This study seeks to align landscape-scale remote sensing data with the LSRG to provide a scalable tool for corporate upstream Scope 3 reporting. 

 

 

Specific Objectives: 

Conversion Year x: Map Spatio-Temporal Land-Use Dynamics: 

 

We used MapBiomas time-series 1985-2023 to identify "emitting pixels" of natural vegetation conversion associated with soy crops and pasture expansion within a rolling 20-year window in the three biomes. We considered these pixels as the smallest unit of analysis which we could first discriminate as a pixel that has been deforested less than 20 years ago and then apply the linear discounting approach to calculate the emissions. These analyses were performed for soy crops or pastures that were identified as the LUC of every year from 2006 to 2023. The beginning of the analysis is related to the possibility of contemplating a full 20-year time span of the process of residual emissions related to the first event of deforestation.  

 

Soy crops or pastures in Year x:  

 

We obtained rasterized information on areas of soy crops and pastures. For the Amazon and the Cerrado the information was obtained from MapBiomas and for the Gran Chaco pasture covers as well. Spatial information on soy crops for the Gran Chaco was obtained from Song et al. 2021. 

 

Commodities mapping. Soy or pasture covers in year x from 2006 to 2023. 

 

Using MapBiomas time series we identified areas of pastures and for soy crops we used the soy crops time series developed by Song et al. 2021. 

 

Elegibility of pixels converted < or = to 20 years since first conversion event: Develop dLUC Emission Factors: Identification of pixels of soy crops or pastures converted < 20 years ago. 

 

We determined the elegibility of those areas of soy crops and pastures by dividing dLUC between pixels converted > 20 years ago and pixels converted =< 20 years. For each year from 2006 to 2023 we established the elegibility of emitting pixels.   

 

Integration of Above Ground Biomass (ABG) and Carbon stores in ABG: 

 

We integrated Above-Ground Biomass (AGB) ... . For Amazonia and Cerrado, we obtained AGB spatial information from (...). For the Gran Chaco we used the ESA Biomass Climate Change Initiative products to calculate precise AGB in Mg/ha. The AGB data was integrated to a map of natural forest cover of 1985 to establish that year as the preteritous AGB and Carbon in biomass stock, before the beginning of the analysis. For these we resampled the ABG information to adjust pixel sizes to those from MapBiomas Chaco collection 5* . We then obtained the average value of ABG for the different types of natural woody covers that collection 5 presents to finally obtain an ABG map with forest cover in 1985. 

 

Application of Linear Discount Method:  

 

Once the Evaluate Methodological Reliability: Assess the impact of mapping accuracy and biomass scale mismatches on footprint calculations to ensure data integrity for scientific and regulatory use. Align calculations with the LSRG formula to provide fit-for-purpose factors for corporate inventories and REDD+ monitoring. 

 

 

Calculation of emissions from conversion for soy crops in each year from 2006 to 2023.  

 

Identify Agricultural Frontiers: Classify productive areas in the three biomes to distinguish between "frontier" and "legacy" expansion zones to better inform corporate sourcing decisions... for decision making.
