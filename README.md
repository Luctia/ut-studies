# UT-Studies
The purpose of this repo is to provide a list of studies given at the University of Twente. At the time of writing, the university does not provide an easily readable (by code) list itself, although it is clear that a lot of people could use it.

## Data
The data is represented in the following way:
```
{
    "abbreviation": the abbreviation of the study. If the abbreviation is unknown or does not exist, this value is "UNKNOWN".
    "name": the full name of the study.
    "type": the type of the study. This value is either "Bachelor" or "Master".
}
```
These values may be changed in the future. Values that we intend to include, include, but are not limited to: duration, abbreviation with type (B-TCS and M-TCS), language, CROHO code, fulltime/parttime.

## The project
This repo only contains the data itself, at least for the time being. We'd also like to develop at least two other applications to go along with this repo; a scraper to scrape the website of the University of Twente and make changes to the data if necessary, and an API that can be deployed on a server so users do not have to clone this repo. These repositories can be found here:
- [API](https://github.com/Luctia/ut-studies-api)
- [Scraper](https://github.com/Luctia/ut-studies-scraper)

We use [semantic versioning](https://semver.org/).
