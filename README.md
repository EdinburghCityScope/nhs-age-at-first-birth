# nhs-age-at-first-birth
Number of first time mothers who are aged 19 and under, or 35 and over. The 3 year aggregate shown is for financial year ending 31 March and refers to the year of discharge from hospital.

More information is available on the [ISD website](http://www.isdscotland.org/Health-Topics/Maternity-and-Births/Births/Background.asp).

Statistics provided by NHS Information Services Division:  http://statistics.gov.scot/data/age-at-first-birth

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/nhs-age-at-first-birth.git
```

Install npm dependencies

```
cd nhs-age-at-first-birth
npm install
```

Run the API (from the nhs-age-at-first-birth directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
