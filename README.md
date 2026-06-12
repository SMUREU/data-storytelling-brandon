# Data Storytelling Mini-Project: Brandon Kung

In this project, I aimed to use visualizations to gain insight into the relationship between economic development and bombings. 

I was inspired by [Erin Lin](https://www.erin-lin.com), a political scientist at Ohio State University who used satellite imagery to detect unexploded ordnance (UXO) density and estimate the how UXO affected the economic development of Cambodia. I soon found that the question of how war, specifically explosive munitions, affects economic development, is a hotly contested one. 

Digging deeper into the literature, I found [this paper](https://doi-org.ccl.idm.oclc.org/10.1016/j.jdeveco.2020.102611)(Yamada and Yamada 2021). They investigated the same exact question: did U.S. bombing during the Second Indochina War affect economic development in Laos? Their novel strategy involved using nighttime light emissions as a proxy for economic activity. They lacked images in their paper, so I decided to try to visualize the relationship explored in their paper to see what it could tell us. 

Data sources:

- National borders of Laos and Cambodia, used to crop the nighttime lights image , are from [Natural Earth](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-admin-0-countries/).
- Laos province boundaries are from [GADM](https://gadm.org/)
- Subnational HDI data is from the [Global Data Lab](https://globaldatalab.org/shdi/)
- Bombing data for Laos is from the Theater History of Operations (THOR) Data, hosted on [data.world](https://data.world/datamil/vietnam-war-thor-data)
- Bombing data for Cambodia is from [OpenDevelopmentCambodia](https://data.opendevelopmentcambodia.net//dataset/us-bombing-in-cambodia-1965-1975-)
- Nighttime lights data for both Laos and Cambodia is from the [Earth Observation Group](https://eogdata.mines.edu/products/vnl/) at the Colorado School of Mines 


My analysis confirmed the findings of Yamada and Yamada (2021) and others, such as [Miguel and Roland (2006)](https://www.nber.org/system/files/working_papers/w11954/w11954.pdf). There does not seem to be an association between long-run economic development and bombings during the Second Indochina War. However, I must emphasize that my findings are based on a highly qualitative look at visualizations based on two variables. I did not perform any statistical modeling or other causal identification techniques, nor did I control for covariates. There is still much work to be done on the topic, potentially with new causal identification strategies. 

Relevant files can be found in each folder. 