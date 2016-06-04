# Trakt.TV ratings trends
Trakt.tv ratings trends is a python script to create interactive visualisation of episode ratings of a TV show using Trakt.tv ratings data.

## Dependencies

- seaborn
- scipy
- pandas
- requests
- tqdm (optional)

## Usage

- Download or clone this repository
- Get a trakt API key by registering a new APP on Trakt TV (https://trakt.tv/oauth/applications/new)
- paste the API key in keys.py to replace the placeholder API
- Run trakt-ratings-trends.py

when prompted, type in the name of the TV show of interest.

The script will generate 3 files in the folder the script is running from: 
 - A csv file with all the fetched data from Trakt.tv
 - A png file with a static version of the episode ratings plot
 - A html file with an interactive version of the episode ratings plot

## Contributions

Any ideas or contributions for further development are very welcome. Just drop me an e-mail or submit a pull request

## Maintainer

* Dinesh Vatvani ([@d_vatvani](https://twitter.com/d_vatvani))