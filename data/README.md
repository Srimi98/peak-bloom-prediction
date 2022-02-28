# Cleaned data sets

The structure of the cleaned data files is as follows:

*bloom_doy (Bloom day of year): The predictor variable ( days since January 1st of the year until peak bloom (`integer`). January 1st is `1`).(integer)
*Years : Corresponding time series identifier.(integer)
*Date of bloom : The exact date of peak bloom.(string)
*Avg Humidity on BD : Average humidity on the Bloom Date (in %).(float)
*Jan temp : Average temperature of January of the corresponding year (in Celcius).(float)
*Feb temp : Average temperature of February of the corresponding year (in Celcius).(float)
*March temp :  Average temperature of March of the corresponding year (in Celcius).(float)
*April temp : Average temperature of April of the corresponding year (in Celcius).(float)
*Avg Temp on BD : Average temperature of the Peak Bloom Day (in Celcius).(float)
*Precp. Winter : Amount of Precipitation in Winter (in mm). (float)
*Precp. Spring: Amount of Precipitation in Spring (in mm). (float)
*Latitude : latitude of the observation (`double`)
*Longitude : longitude of the observation (`double`)
*Altitude : altitude of the observation (`double`)



## Data sources

### Washington, D.C. (USA)

The data in file *washingntondc.csv* has been obtained from https://www.epa.gov/climate-indicators/cherry-blossoms. Aother site, used for collecting data is https://www.wunderground.com/calendar/us/dc/washington/KDCA . Data for each of the variables are collected from 1921 to 2021.

The peak bloom date is defined as the day when **70%** of the Yoshino Cherry (Prunus x yedoensis) are in full bloom, as determined by the [National Park Service](https://www.nps.gov/subjects/cherryblossom/bloom-watch.htm).


### Liestal-Weideli (Switzerland)

The data in the file *liestal.csv* is obtained from
Data for each of the variables are collected from 1982 to 2021.
The peak bloom date is defined as the day when **25%** of the blossoms are in full bloom.
The date is determined by MeteoSwiss.


### Kyoto (Japan)

The data has been obtained from http://atmenv.envi.osakafu-u.ac.jp/aono/kyophenotemp4/.
Also from https://www.wunderground.com/weather/jp/nakagy%C5%8D-ku, https://www.data.jma.go.jp/obd/stats/etrn/view/monthly_s3_en.php?block_no=47759&view=1

Data is collected from 1922 to 2021 for all the variables mentioned above.
The peak bloom date of the Prunus jamasakura is determined by a local news paper in Arashiyama (Kyoto, JP).

### MeteoSwiss (other locations in Switzerland)

The data file *meteoswiss.csv* contains peak bloom dates for various sites across Switzerland, obtained from https://opendata.swiss/en/dataset/phanologische-beobachtungen.

###### Copyright notice

The data license is "Open use. Must provide the source."

- You may use this dataset for non-commercial purposes.
- You may use this dataset for commercial purposes.
- You must provide the source ("Source: MeteoSwiss")

### Japanese Meteorological Agency (other locations in Japan)

The data file *japan.csv* contains peak bloom dates for various sites across Japan.

The sample trees are located within a 5km radius of the location indicated in the data file.

###### Copyright notice

Source: Japan Meteorological Agency website (https://www.data.jma.go.jp/sakura/data/pdf/005.pdf).

### South Korea

The data file *south_korea.csv* contains **first flowering dates** for various sites across South Korea, curated by the Korean Meteorological Administration.

###### Copyright notice

Source: Korean Meteorological Administration.

### USA National Phenology Network

Additional data were provided by the USA National Phenology Network and the many participants who contribute to its *Nature’s Notebook* program.

###### Copyright notice

- *USA-NPN_individual_phenometrics_data.csv:*
USA National Phenology Network. 2022. Plant and Animal Phenology Data. Data type: Individual Phenometrics. 2009--2021. USA-NPN, Tucson, Arizona, USA. Data set accessed 2022-01-13 at http://doi.org/10.5066/F78S4N1V.
- *USA-NPN_status_intensity_data.csv:*
USA National Phenology Network. 2022. Plant and Animal Phenology Data. Data type: Status and Intensity. 2009--2021. USA-NPN, Tucson, Arizona, USA. Data set accessed 2022-01-13 at http://doi.org/10.5066/F78S4N1V.

