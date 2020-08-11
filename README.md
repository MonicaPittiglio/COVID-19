# COVID-19 Research Project
### BIOL 390: Reproducable Research, Summer 2020
**Copyright © (2020) Monica Pittiglio** 

## Abstract
There is much debate worldwide over which healthcare type is superior - universal or non-universal. With previous data backing the claim that broader health coverage increase access to necessary care, this report set out to determine whether countries with universal healthcare had lower COVID mortality rates than those with non-universal healthcare.

World COVID death data and recent population data were both examined for total deaths and deaths as a proportion of population. The results disproved the hypothesis. While countries with universal healthcare averaged fewer deaths per country, they had more total deaths than countries with non-universal healthcare, despite having almost half as many total citizens. They averaged four times more deaths per capita than countries with non-universal healthcare, and totaled ten times more. This could be due to a decrease in the quality of care provided by practitioners employed under universal healthcare regulations, but the real cause will require further analysis.

## Introduction
Universal government-funded health systems are such a complex beast that only 31 of the world's 32 developed nations have been able to make them work. In countries with non-universal healthcare, up to 90% of the population may be uninsured. There is data that exists already linking broader health coverage to better access to necessary care and improved overall health. Thus, it is expect that healthcare type is also indicative of how well-equiped a country is to handle a global pandemic. 

Healthcare type is expected to impact how likely citizens are to seek treatment once they develop COVID symptoms, the prevelance of untreated underlying health conditions, and how healthy the general population is. All of these items will directly impact death numbers. This report examines the COVID-related deaths in countries with universal healthcare, and compares them to the COVID-related deaths in countries with non-universal healthcare.

## Hypothesis
I hypothesize that countries with non-universal health insurance systems experience greater COVID-19 mortality rates than countries with universal government-funded health systems.

In countries that have non-universal health insurance systems, some citizens may have private insurance, some may be eligible for subsidized public healthcare, and some may be completely without insurance. Countries that fall under this category are Bangladesh, Burundi, the Democratic Republic of Congo, Ethiopia, Jordan, Kenya, Nigeria, Paraguay, Tanzania, Uganda, the United Arab Emirates, and of course, the United States. Egypt, India, and Indonesia also fall into this category but will be left out of this report, as their healthcare systems are in transition.

In countries with universal government-funded health systems, healthcare is available to all citizens, no matter what. Countries that fall under this category are Australia, Bahrain, Bhutan, Botswana, Brazil, Brunei, Canada, Cuba, Denmark, Finland, Georgia, Greece, Iceland, Ireland, Italy, Kuwait, Malta, New Zealand, Norway, Oman, Portugal, San Marino, Saudi Arabia, South Africa, Spain, Sri Lanka, Sweden, Trinidad and Tobago, and the United Kingdom. Taiwan and North Korea also fall into this category but will be left out of this report, as they have not released their coronavirus data.

Other types of healthcare do exist. Some governments provide universal public insurance, universal public-private insurance, or universal private insurance. Those healthcare systems, however, are not examined in this report.

## Datasets used
My main dataset is the World Health Organization's international dataset, which includes number of COVID cases and deaths reported both daily and cumulatively, by country. This dataset is updated daily and can be found at https://covid19.who.int/. Data collection began in mid-January and this report includes data through August 2nd, 2020.

The population dataset I used is from worldbank.org. Key sorces for this dataset are listed as the United Nations, various census reports, and Eurostat, among other reputable sources. It can be found at https://data.worldbank.org/indicator/SP.POP.TOTL. It is updated yearly, with the most recent data being from 2019.

## Description of analyses
First, I examined deaths over time grouped by healthcare type. The total number of deaths as of August 2nd in countries with non-universal healthcare was 157,786. The United States of America led the pack, followed by Bangladesh and then Nigeria. These top three countries accounted for 99% of the deaths in countries that have non-universal healthcare. The United States of America alone comprised 97% of the total. When it comes to countries with universal healthcare, the total number of deaths was 234,315. Brazil led the pack, followed by the United Kingdom and then Italy. These top three countries accounted for 74% of the deaths in countries that have universal healthcare.

The countries with non-universal healthcare had more average deaths per country but an enormous standard deviation, no doubt due to the pull of the United States' death toll, which is 48 times that of the next country in the dataset. Countries with universal healthcare had a larger median, and a standard deviation 45% smaller than that of the non-universal healthcare countries. This dataset also had more total deaths. Overall, the data indicates that individual countries with universal healthcare tend towards more overall coronavirus deaths than those with non-universal healthcare.

Next, the populations of each of the examined countries were plotted and compared. Even though there are less countries with non-universal healthcare, they have a larger summed population than countries that have universal healthcare. In fact, the four most highly-populated countries that have non-universal healthcare account for 51% of the total population between all 41 countries in this graph. The average population of the non-universal healthcare countries is also 4 times larger than the average population of the universal healthcare countries. That said, their standard deviation is also much larger, no doubt due to the United States' massive population.

When we divide deaths by population, we get deaths per capita. While countries with universal healthcare have smaller populations, they tend to have far more deaths per capita than countries with non-universal healthcare - a total of 10 times more, actually, and an average of 4 times more per country.

New daily deaths per capita were also examined and seperated by healthcare type. Some countries, like Burundi, the United Republic of Tanzania, Bhutan, Italy, the United Kingdom, Spain, Ireland, and Canada are doing a great job of decreasing or even eliminating daily deaths. That said, other countries like Brazil, South Africa, The United States of America, Bangladesh, and Ethiopia are not doing as well, with deaths that increase every day. Overall though, the countries with universal healthcare have a sum of squares 3000 times larger than those with universal healthcare, indicating more variability in the number of new cases every day. Some countries with universal healthcare may be handling the virus well, but their efforts are offset globally by those who are not.

## Conclusions
The data does not support the hypothesis. While countries with non-universal healthcare average more deaths overall than countries with non-universal healthcare, that is due almost entirely to the data from one country - the United States. Countries with universal healthcare saw more deaths, both in total and per capita. More research will be needed to figure out why this is the case.

## Viewing this project
The completed project files can be accessed online at https://MonicaPittiglio.github.io/COVID-19/. The repo for this reproducible project is also publicly available at https://github.com/MonicaPittiglio/COVID-19.