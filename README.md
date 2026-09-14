# ECON452-PROJECT

## **Introduction**

In the wake of the 2020 protests, several cities - including Minneapolis, Austin, and Los Angeles redirected portions of their police budgets toward social services. Abolitionist sentiment has been growing across the United States in favor of "defunding" the police. There are strong arguments for redirecting these funds toward upstream interventions. Understanding whether policing is effective is essential for determining the best allocation of our resources as taxpayers. Examination of previous research suggests a minor negative effect on crime. It is difficult to seperate police and crime due to reverse casuality. Police will be deployed to places naturally where more crime occurs. 

The Boston Marathon was always a premier event in the Northest, with tens of thousands of participants and spectators peppered across the route. But in 2013, everything changed with the Boston Bombings. The Terrorism shook the city to it's core. Ever since then, there has been extra emphasis on protecting the public. We proposed a quasi - experimental research design using the effects of the Boston Marathon bombings. The debate ultimately raises an important question: Does additional police presence actually reduce crime?

---

## **Research Question**

 We settled on a difference-in-differences framework aimed at assessing the impact of police presence on crime. The Boston Marathon's police deployment is primarily driven by event security needs rather than local crime conditions. The decision was to focus on violent crime, because the defintions are more strict and has a larger societal impact. 

 Ultimately, our research question was: What is the effect of the sustained post-2013 increase in police presence along the Boston Marathon on violent crime rates in the route-adjacent Boston police district from 2014 to 2019? 


---

## **Data** 

The analysis will be using publicly avaiable data sourced from [Analyze Boston](https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system) and [Legacy Data](https://data.boston.gov/dataset/crime-incident-reports-july-2012-august-2015-source-legacy-system)It's important to mention that from August of 2015 onward, the Boston Police Department switched from a legacy reporting system to a new one. The new reporting system has a "reduced amount of fields". 

---

## **Dependencies**

Any version of R later than version 4.0.0

R Studio or any other IDE that supports R 

**Libraries**
Tidyverse (Contains readr and ggplot2)

fixest package

---

## **Methods**

Other econometric methods are not sufficient to show causality. 
- OLS: Biased because police presence is endogenous. Areas with more crime will have more police officers to begin with. 
- IV regression (2SLS): We were unable to find an instrument that satisfies the exclusion restriction.
- Regression Discontinuity: We failed to find a clear cutoff where the treatment changes (e.g.distance to the route) or police presence (varies by different towns on the route, having bigger or smaller crowds, proximity to the finish line). 

---

## Key Findings


--- 

## Future Improvements


--- 

## License
This project is under the Mozilla Public License Version 2.0
