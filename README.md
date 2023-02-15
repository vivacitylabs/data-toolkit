# Vivacity data toolkit
This repository stores notebooks and similar data tools to help you retrieve and/or analyse VivaCity data. 

<br>

## Notebooks

The repository contains a collection of notebooks to allow easier data downloads for a number of data features via the API. It is aimed as an **interim solution** while we're working on new dashboard developments. You can contact your customer success manager for more information.

### How it works

Select the notebook you need
- [Countline Speed bulk download](https://github.com/vivacitylabs/data-toolkit/blob/master/countline_speeds_bulk_download_generator.ipynb)
- [Classified Counts bulk download](https://github.com/vivacitylabs/data-toolkit/blob/master/classified_counts_bulk_download_generator.ipynb)
- [Journey Times bulk download](https://github.com/vivacitylabs/data-toolkit/blob/master/journey_times_bulk_download_generator.ipynb)
- [Zonal speeds bulk download](https://github.com/vivacitylabs/data-toolkit/blob/master/zonal_speeds_bulk_download_generator.ipynb)
- [Turning Counts bulk download](https://github.com/vivacitylabs/data-toolkit/blob/master/turning_counts_bulk_download_generator.ipynb)
- [Dwell Times bulk download](https://github.com/vivacitylabs/data-toolkit/blob/master/dwell_times_bulk_download_generator.ipynb)

Each notebook will run you through all the necessary steps and will save a final csv file locally or in your Google Drive.
You can also make changes to code (if you wish) or save the notebook to your own Google Drive. 

### What you need

- VivaCity API login credentials

<br>

## Postman Collections

This repository also contains the latest collections of APIs to be used with Postman for testing purposes. Read [this guide](https://vivacitylabs.customerly.help/vivacity-api/api-postman-guide) on how to use Postman to to request small amounts of data via the VivaCity API. You can use the same API user credentials as you do for the notebooks. 

Download both json files and import them into Postman. 

- [VivaCity Postman environment](https://github.com/vivacitylabs/data-toolkit/blob/master/VivaCity%20Environment.postman_environment.json) (json file)
- [VivaCity Postman collection](https://github.com/vivacitylabs/data-toolkit/blob/master/Vivacity%20API.postman_collection.json) (json file)

Note: To download the files, you will need to right click inside the file and select `save as` to save locally. To view large files, you migth need to click `download` first to view the whole file in a new tab.

### What you need

- VivaCity API login credentials
- Postman (free download [here](https://www.postman.com/)) 
