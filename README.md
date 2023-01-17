# Pipeline Incident Data Analysis


This study analyzes the mileage and incident data gathered by Pipeline Hazardous Material Safety Administration (PHMSA) on the US onshore Gas Transmission (GT) and Hazardous Liquids (HL) pipeline systems, between 2010 and 2020. 

The analysis was conducted using Python as the main programming language. For data manipulation and analysis open-source software, namely Pandas and NumPy, was used. Matplotlib was utilized for data visualization and creating plots. 

The main findings of the study are listed below:

* On average, the GT system and HL system consist of 478,240 km and 321,590 km, respectively, majority of which are cathodically protected steel pipes transporting natural gas, crude oil, HVL, and refined petroleum products. 
* The top three main failure causes for both GT system and HL system are identified as excavation damage, corrosion, and material failures, resulting in 82% and 86% of all incidents for each system, respectively.
<img width="350" alt="GT Incidents by Failure Cause" src="https://user-images.githubusercontent.com/77254817/213030702-ff2df1fa-1884-4f0b-9942-7e3afed24a4b.png">
<img width="350" alt="HL Incidents by Failure Cause" src="https://user-images.githubusercontent.com/77254817/213030739-53e32e98-77e1-4fcd-9394-b89c46c4466d.png">

* The most common failure type for both pipeline systems are leaks. However, failures resulting in ruptures make up the majority of ignited incidents.  
<img width="471" alt="GT Ignition by Release Type" src="https://user-images.githubusercontent.com/77254817/213031457-3e6d9774-6307-4ca4-a881-2a222363d361.png">

* The overall rupture rates for the GT system and HL system, between 2010 to 2020, are calculated at 2.53 x 10-5 /km.yr and 1.81 x 10-5 /km.yr, respectively, indicating a higher rate for the GT pipelines. This higher rate is driven by the higher corrosion rates in GT system.
<img width="483" alt="Rupture Rates by Commodity" src="https://user-images.githubusercontent.com/77254817/213027925-f4c8af68-9d50-4e94-833c-533ecfaf3207.png">

* For the GT pipelines, the rupture rates due to excavation activities are significantly higher for Class 3 locations which have a higher population density. 
<img width="482" alt="Gas Transmission Rupture Rates by Class" src="https://user-images.githubusercontent.com/77254817/213029799-fbc3e822-128d-469f-8f29-bcdacaa77098.png">

* The study showed higher rupture rates for pipelines constructed prior to 1960s for both systems, suggesting a higher rate of manufacturing or construction defects in pipes produced prior to this time. 
<img width="493" alt="GT Rupture Rates by Installation Decade" src="https://user-images.githubusercontent.com/77254817/213030139-e95af5a2-c51d-478e-b0dc-83c3538a1688.png">
<img width="493" alt="HL Rupture Rates by Installation Decade" src="https://user-images.githubusercontent.com/77254817/213030248-8fe08423-2a0c-4cfc-b47b-4b0b6ae4b20f.png">

* A revision to PHMSA’s annual mileage data format is recommended to allow breakdown of pipeline mileages based on multiple attributes.
