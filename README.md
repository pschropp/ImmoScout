# MVP ImmoScoutScraper
Scraper for Immoscout as proof of concept before API activation. Deprecated. Code quality, structure and features far from current standards. Stopped when requester did not get API clearance.

## Steps for execution
Go to immobilienscout24.de, search (specifying all search criteria), copy url and paste into input cell below.
Specify SaveFolder for result .csv.

Expose-ID will be read and Immobilien-Scout Expose-API will be called

## Instruction to open result file (.csv)

1. open .csv file (Excel (or similar)
2. mark first column ("A") 
3. go to "Data" -> "Text to columns" 
4. choose "delimited", then "comma" as separator. you can choose formats for certain columns but not necessary 
5. save copy as Excel-File. Do (better) not save changes to the original file, if you still want to process them

## Instructions for Jupyter
Start Jupyter notebook on Mac or Linux: Terminal --> jupyter notebook

cd to folder containing notebook, browser tab will open in that folder directly
