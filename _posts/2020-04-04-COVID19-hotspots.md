---
layout: post
title: Beyond the COVID-19 hotspots
author: Jason Khadka
date: '2020-04-04'
category: covid-19
summary: What lies behind
thumbnail: virus.jpg
---

Coronavirus Sars-CoV-2 has brought the world to standing still. The impact of the novel virus is felt everyday in homes around the world and the hospitals have been the new battle ground. WHO announced [the virus as pandemic on March 11](http://www.euro.who.int/en/health-topics/health-emergencies/coronavirus-covid-19/news/news/2020/3/who-announces-covid-19-outbreak-a-pandemic), while there were 20,000 cases across the globe and almost 1000 deaths. By the morning of April 3, only little more than three weeks later, there are now more than 1 million cases with 54,000 deaths.

It is suspected to have emerged from the city of Wuhan in China, possibly jumped from bats to human with other intermediary. Since its first human infection, it has spread in all continents and almost all the countries. The virus has not been obstructed by borders, and has not discriminated on the lines of nationality, race or religion.  However, curiously, its spread across the countries has seen one commonality.

The focus on this corona virus started soon after the new year with its epidemy centered in Wuhan or China as a whole. [The exponential increase in case numbers in China](https://www.aljazeera.com/news/2020/01/timeline-china-coronavirus-spread-200126061554884.html) gave early indications of what was to come in the coming weeks and months. By late January, [parts of china were in lockdown in hopes of stopping the spread](https://edition.cnn.com/2020/01/26/asia/wuhan-coronavirus-update-intl-hnk/index.html). The virus then soon found its way to [South Korean, then to Iran, Italy, rest of Europe, and in recent weeks, we have seen the infection rates in USA increase dramatically](https://www.aljazeera.com/news/2020/01/timeline-china-coronavirus-spread-200126061554884.html). The spread of virus through these early months is visualised in the plot below. 

<p align='center'>
<img class='img-post' alt="Daily cases of Corona virus" src="/assets/img/posts/dailyCasesMap.gif" width="90%">
</p>
<p align='center'>
Fig 1. Map of Daily Sars-CoV-2 cases seen by countries
</p>

We observe a clear shift of hotspots, looking at the daily increase in cases, from East Asia (China and S. Korea) to the middle east, Europe and finally to USA. The pandemic has been localised for now in the northern hemisphere and is suspected to be aided by [the cold temperatures of the winter months](https://www.scmp.com/news/china/science/article/3074970/coronavirus-becomes-pandemic-scientists-ask-if-lines-map-hold). However, another key factor defining the perceived localisation of virus could just be the prevalence of the testing. We saw early on in [South Korea how mass testing](https://www.scmp.com/news/china/science/article/3074970/coronavirus-becomes-pandemic-scientists-ask-if-lines-map-hold) was able to reveal the true scale of epidemic. Currently, governments around the world [face the pressure](https://www.theguardian.com/australia-news/2020/mar/13/global-shortage-of-covid-19-test-kits-hits-australia-as-other-nations-limit-exports) to accelerate their testing, but are seriously limited by the resource. Nations are [limiting their exports](https://www.politico.eu/article/coronavirus-eu-limit-exports-medical-equipment/) of critical equipments for testing and treatment, and are fighting to procure whatever they can in this fight. In this global crisis, the countries with means are clearly well placed to secure the testing and therapeutic equipment. [Germany has stated](https://www.theguardian.com/world/2020/apr/02/germany-told-it-needs-to-massively-increase-coronavirus-testing) that its current capacity of testing 500,000 a week is not enough to control the pandemic and [UK hopes to have capacity of testing at least 100,000 a day](https://www.theguardian.com/politics/2020/apr/02/boris-johnson-restates-pledge-to-boost-uk-coronavirus-testing-capacity). On the other end of spectrum, the countries with lesser economic prowess
have barely tested a fraction of that number in total (e.g. India ([47,951](https://www.theguardian.com/world/2020/apr/01/india-coronavirus-cases-rise-amid-fears-true-figure-much-higher)) and Nepal ([~1000 tests](https://www.scmp.com/video/coronavirus/3078066/nepal-full-lockdown-few-cases-doing-few-covid-19-tests-amid-coronavirus))).

To check if the economic means have indeed had an impact on the location of COVID-19 hotspots, I looked at the data provided by [John Hopkins University of detected total Sars-CoV-2 cases](https://github.com/CSSEGISandData/COVID-19) and the [world bank data for GDP](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD). The following animation shows the total detected cases over the time against the GDP of a nation. We see that the countries along the right of x-axis see the rise in corona cases (even if you ignore China) as compared to the bunched up countries in the left most part of x-axis (lower GDP). 
<p align='center'>
<img class='img-post-small'  alt='Total corona cases against GDP' src='/assets/img/posts/coronaTotalVsGDP.gif'>
</p>
<p align='center'>
Fig 2. Rise in total COVID-19 cases with the GDP of a country. Some countries are highlighted with red mark and the country code is mentioned for emphasis.
</p>
This correlation of total cases to GDP of a country is further highlighted if I normalise the case count and GDP by population of a country. Below, the figure shows the COVID-19 cases per 1000 against the GDP per capita for the countries. The gaining momentum in case counts among the higher GDP countries is clear compared to countries with less means in the left bottom corner of the plots.

<p align='center'>
<img class='img-post-small' alt="Total corona cases per 1000 agains GDP per capita" src="/assets/img/posts/coronaVsGDP_perCapita.gif">
</p>
<p align='center'>
Fig 3. Total COVID-19 cases per 1000 with the GDP per capita of a country. Some countries are highlighted with red mark and the country code is mentioned for emphasis.
</p>
The limited test-kits are concentrated at the moment in the countries that produce them or [that can gather them](https://www.bbc.com/news/world-us-canada-52161032) through the economic or political means. The rising cases in these countries and the creation of supposed hotspots in the past months can be attirbuted to basically the fact that those with means know who are sick, those without know nothing. The plot below is bracketing the GDP to see the distribution of total cases per 1000 in counties. Over the time, again, it is evident that the case counts sky-rocket in countries to the right of x-axis, while to the very left we see minimal cases. 
<p align='center'>
<img class='img-post-small'  alt="Distribution of corona cases per 1000 by GDP brackets" src="/assets/img/posts/CoronaCaseDistribution.gif">
</p>
<p align='center'>
Fig 4. Case distribution per 1000 against GDP of countries. (Please be patient with this plot, the bars become significant only in March.)
</p>
The relation of ability to gather and administer test and be the possible hotspot is clear with these plots. With rising case numbers in limited countries, the narrative of hotspots are driven in the news cycles and social media. However, one has to be careful to take these narratives at face value. Has the virus clearly chosen to be particularly harmful to the richer countries? Is the spread to these countries and creation of these hotspots correlated to the globalisation? Where these well-off countries harbour stronger connection to the globe than the once on the lower end of GDP table. The stronger ties are one of the reasons often mentioned while explaining the rising cases in these countries. However, the flight network has woven the globe tight in the past decades, with little to no part of the world being left isolated. Fig. 6 visualises the flight network per nation. With such prevalent connection among all the countries, the localisation of the virus in richer East Asian, or the European or North American countries is hard to digest. 


<p align='center'>
<img class='img-post-small' alt="Top 5 and bottom 5 countries comparison" src='/assets/img/posts/topbot5_countries.png'>
</p>
<p align='center'>
Fig 5. Corona cases for five rich countries with GDP per capita of near 100,000 compared to countries with bottom five countries in terms of GDP.
</p>

<p align='center'>
<img class='img-post' src="/assets/img/posts/world_flight_network.gif" alt="World flight network" width="90%"/>
</p>
<p align='center'>
Fig 6. Network of flight connection to different countries visualised for each country.
</p>
Over the following months, we will have a better grasp of the situation around the world, especially among the developing countries. If there are indeed undetected spread in the developing countries and these cases are not isolated and treated due to the lack of testing and protective equipment, we might see the surge in the death rates to the numbers that are unimaginable for us right now. The countries at the higher end of GDP spectrum are struggling in their fight against the virus, struggling to provide PPEs, tests and ventilators. One can only imagine how the situation might turn in the countries on the lower parts of the economic table. 
The only way to fight and limit the power of this virus has to be the simple measure of social distancing, that does not cost anything upfront, and has been proven to be effective. It might do better for every nation, regardless of the case numbers **detected**, to employ this measure and not rely on the narrative of limited hotspots on faraway islands. 

