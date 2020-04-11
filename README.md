# COVID-DI-Prototype: COVIDMinder Development

* For those new to github: https://education.github.com/git-cheat-sheet-education.pdf (github cheatsheet)

## Shinyapps.io Deployment (Created 30 Mar 2020; updated frequently!)
http://bit.ly/COVIDMinder
https://olyerickson.shinyapps.io/covid-di-prototype/

## Data Sources: Updated daily! (See also `data` subdirectories)

* JHU CSSE github: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data
* CTP Data API: https://covidtracking.com/api
* NY Times github: https://github.com/nytimes/covid-19-data

## Screen Shot (06 Apr 2020)
![COVIDMinder Screenshot](https://raw.githubusercontent.com/TheRensselaerIDEA/COVID-DI-Prototype/master/COVIDMinder_screenshot.png)

## Project structure

* **app.R**: The main application file which includes the Shiny application code for both UI and server.
* **README.md**: The file includes the documentation for this project.
* **/modules**: The application is divided into several modules based on their functions which are all located inside this directory.
* **/data**: This directory includes all the data files used in the project, including both json as well as CSV files.
* **/LDI**: This directory includes all the LDI related Rmd and HTML files.
