# NFL-Injuries
Scraper to get NFL injuries from prosporttransactions.com


## What is this project

Much like the scraper written for NBA injuries, this project gets NFL injurieds from the popular prosportstransactions.com website.

The data is then injested by the popular hashtagfootball.com website tyo use in Fantasy Football tools.


## Usage

The job is scheduled to run at 0715UTC nightly. The github action runs the file `R/incremental_scrape.R` to scrape new data posted to the site. It then appends these records to `data/nfl_injuries.json`.
