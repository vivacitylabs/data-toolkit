# Vivacity data toolkit
This repository stores notebooks and similar data tools to help you retrieve and/or analyse VivaCity data. 

<br>

## Notebooks

Collection of notebooks to allow data downloads for a number of data features via the API for multiple sensors and over multiple days. It is aimed as an **interim solution** while we're working on new dashboard developments. You can contact your customer success manager for more information.

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

Copy the links into Postman. 

- VivaCity Postman environment: https://raw.githubusercontent.com/vivacitylabs/data-toolkit/master/postman-collections/VivaCity%20Environment.postman_environment.json
- VivaCity Postman collection: https://raw.githubusercontent.com/vivacitylabs/data-toolkit/master/postman-collections/Vivacity%20API.postman_collection.json

Note: To download the files, you will need to right click inside the file and select `save as` to save locally. 

### What you need

- VivaCity API login credentials
- Postman (free download [here](https://www.postman.com/)) 
