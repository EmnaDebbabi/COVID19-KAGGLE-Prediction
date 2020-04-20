# COVID19-KAGGLE-Prediction
## Project overview
Predict the end of the pandemic.and the whether conditions impact on the pandemic transmission rate and extracting its key factors.
### Dataset
Novel Corona Virus 2019 Dataset
2019 Novel Coronavirus (2019-nCoV) is a virus (more specifically, a coronavirus) identified as the cause of an outbreak of respiratory illness first detected in Wuhan, China. Early on, many of the patients in the outbreak in Wuhan, China reportedly had some link to a large seafood and animal market, suggesting animal-to-person spread. However, a growing number of patients reportedly have not had exposure to animal markets, indicating person-to-person spread is occurring. At this time, it’s unclear how easily or sustainably this virus is spreading between people - CDC

This dataset has daily level information on the number of affected cases, deaths and recovery from 2019 novel coronavirus. Please note that this is a time series data and so the number of cases on any given day is the cumulative number.

The data is available from 22 Jan, 2020.
#### Column Description

Main file in this dataset is covid_19_data.csv and the detailed descriptions are below.

covid_19_data.csv
<ul type="circle">
<li> Sno - Serial number </li>
<li> ObservationDate - Date of the observation in MM/DD/YYYY </li>
<li> Province/State - Province or state of the observation (Could be empty when missing) </li>
<li> Country/Region - Country of observation </li>
<li> Last Update - Time in UTC at which the row is updated for the given province or country. (Not standardised and so please clean before using it) </li>
<li> Confirmed - Cumulative number of confirmed cases till that date </li>
<li> Deaths - Cumulative number of of deaths till that date </li>
<li> Recovered - Cumulative number of recovered cases till that date </li>
 </ul>
2019_ncov_data.csv

This is older file and is not being updated now. Please use the covid_19_data.csv file

Added two new files with individual level information

COVID_open_line_list_data.csv
This file is obtained from this <a href="https://docs.google.com/spreadsheets/d/1itaohdPiAeniCXNlntNztZ_oRvjh0HsGuJXUJWET008/edit#gid=0">link</a>

COVID19_line_list_data.csv
This files is obtained from this <a href="https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vQU0SIALScXx8VXDX7yKNKWWPKE1YjFlWc6VTEVSN45CklWWf-uWmprQIyLtoPDA18tX9cFDr-aQ9S6/pubhtml"> link </a>

Country level datasets
If you are interested in knowing country level data, please refer to the following Kaggle datasets:
<ul type="circle">
<li> India - https://www.kaggle.com/sudalairajkumar/covid19-in-india </li>
<li> South Korea - https://www.kaggle.com/kimjihoo/coronavirusdataset </li>
<li> Italy - https://www.kaggle.com/sudalairajkumar/covid19-in-italy </li>
<li> Brazil - https://www.kaggle.com/unanimad/corona-virus-brazil </li>
<li> USA - https://www.kaggle.com/sudalairajkumar/covid19-in-usa </li>
<li> Switzerland - https://www.kaggle.com/daenuprobst/covid19-cases-switzerland </li>
<li> Indonesia - https://www.kaggle.com/ardisragen/indonesia-coronavirus-cases </li>
</ul>
