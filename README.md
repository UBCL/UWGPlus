# UWGPlus
**Model nature-based cooling. From urban weather to community well-being.**

A simulation tool for urban design and nature-based solutions. It measures the environmental and health risks of proposed urban strategies for specific locations. It is built for public and decision makers to understand the impact of urban development strategies on people and the environment.

## What is UWGPlus?
UWGPlus is a research-based update of the Urban Weather Generator code. It combines enhanced modeling of nature-based cooling with a statistical framework for estimating heat-associated health outcomes.

By linking neighborhood design, local climate, and population-health evidence, UWGPlus helps planners and researchers investigate not only how much a place could cool, but also why that cooling matters for people.

## What's New!
UWGPlus builds on the Urban Weather Generator with enhanced representations of urban greenery and an integrated statistical health-assessment workflow.

## Read the Science
Plan cooler neighborhoods with health in mind.

UWGPlus connects neighborhood climate simulation with statistical health modeling to explore how urban greenery could reduce heat exposure and improve community-health outcomes.

The code evaluates how tree canopy, ground vegetation, green roofs, and vegetated façades influence neighborhood climate and building performance. The published health demonstration focuses on tree canopy and ground vegetation. It compares greening scenarios, assess changes in temperature and humidity, and estimate potential changes in health metrics.

It assesses temperature and humidity together. UWGPlus represents evaporative cooling while accounting for changes in atmospheric moisture and vegetation-related radiation exchange—providing a more complete picture of modeled heat conditions. The model translates simulated heatwaves into estimates of health metrics using statistical relationships developed for a defined population.

UWGPlus supports research and planning. Health outputs are population-level estimates dependent on the selected model, input data, and scenario assumptions. They are not individual medical predictions or guarantees of avoided illness or mortality.

### Core publications
**Modeling the cooling potential of urban greenery:**

This study establishes the enhanced microclimate modeling foundation behind UWGPlus. It extends UWG’s representation of vegetation, urban surfaces, shading, evapotranspiration, and radiation exchange, including applications to tree canopy, green roofs, and vegetated façades. The model was evaluated against local weather observations to investigate its ability to represent neighborhood temperature and humidity.

  + Dardir, M., & Berardi, U. (2021). Development of microclimate modeling for enhancing neighborhood thermal performance through urban greenery cover. Energy and Buildings, 252, 111428. DOI: 10.1016/j.enbuild.2021.111428.

**Connecting urban cooling with community health:**

This study develops the integrated climate-to-health framework informing UWGPlus. It links enhanced UWG simulations with statistical models of mortality and emergency department visits to assess potential health benefits of urban greening. The health models were developed using historical records and incorporate seasonal patterns and delayed responses to heat.

  + Dardir, M., Berardi, U., & Wilson, J. (2023). Health-informed predictive regression for statistical-simulation decision-making in urban heat mitigation. Sustainable Cities and Society, 98, 104853. DOI: 10.1016/j.scs.2023.104853.

#### Related research
**Understanding heat, air quality, and vulnerable populations:**

This complementary study examines associations between environmental conditions and mortality and emergency department visits, with particular attention to older adults and people with cardiorespiratory conditions. It provides additional context for the population-health perspective informing UWGPlus. However, the current software does not include an air-quality prediction module.

  + Dardir, M., Wilson, J., & Berardi, U. (2023). Heat and air quality related cause-based elderly mortalities and emergency visits. Environmental Research, 216, 114640. DOI: 10.1016/j.envres.2022.114640.

#### Foundational research
**The original Urban Weather Generator:**

UWGPlus builds on the Urban Weather Generator developed by Bueno and colleagues. Their foundational work introduced a method for estimating urban-canyon air temperatures from weather-station observations outside a city, supporting the consideration of urban heat island effects in building energy simulations.

  + Bueno, B., Norford, L., Hidalgo, J., & Pigeon, G. (2013). The urban weather generator. Journal of Building Performance Simulation, 6(4), 269–281. DOI: 10.1080/19401493.2012.718797.

## Acknowledgment
UWGPlus builds upon the Urban Weather Generator developed by Bueno and colleagues. We acknowledge the original developers and subsequent contributors whose work established the foundation for this research-based extension. The publications above document the microclimate enhancements and health-modeling framework informing UWGPlus.

## How to Cite
When using UWGPlus in research, teaching, or professional studies, please cite the publications relevant to your application. Cite Dardir and Berardi (2021) for the enhanced microclimate modeling approach, Dardir, Berardi, and Wilson (2023) for the integrated health-assessment framework, and Bueno et al. (2013) to acknowledge the original Urban Weather Generator.
