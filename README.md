# Loads

## Requirements
In order to run the notebook you will need to have the latest version of Python and JupyterLab or Jupyter Notebook installed on device. All included packages will be commented out in the first lines of the notebook.

### JupyterLab
Install JupyterLab with pip:

`pip install jupyterlab`

Once installed, launch JupyterLab with:

`jupyter-lab`

### Jupyter Notebook
Install the classic Jupyter Notebook with:

`pip install notebook`

To run the notebook:

`jupyter notebook`

## Goals
Later iterations will abstract the scripts out into self contained .py files to be ran in a cloud environment.

### Web Scraper Tool
- [x] Headless Selenium Client Opens Chrome
- [ ] List of All US Cities
- [x] Client Opens CLC Website
- [x] Client Uses Credentials to Login
- [x] Client Searches City
- [x] Client Filters Results to Only Truck Sites
- [ ] Client Builds Pandas Dataframe Containing All Site Data Iterating Over Every Page Per City Location 
  - [ ] Title
  - [ ] Address 
  - [ ] Phone Number
  - [ ] CLC Hotel ID
  - [ ] Amenity List
  - [ ] CheckINN Certification
  - [ ] Average Rate
  - [ ] Guest Review Rating
- [ ] Client Iterates Over All City Locations Exporting Dataframe to CSV
- [ ] Convert to .py file

### Data Cleaning Tool
- [ ] Import CSV into a Pandas Dataframe
- [ ] Remove Duplicate Locations
- [ ] Append Lat/Long Coordinates to Each Location
- [ ] Export Dataframe Containing All Locations to CSV
- [ ] Convert to .py file

### Database
- [ ] Setup Firebase
- [ ] Setup Lambdas to Run Chron Jobs of Web Scraper Tool and Data Cleaning Tool
- [ ] Import/Overwrite Data into Firebase

### Application
- [ ] Design Work
- [ ] Firebase Login
- [ ] Firebase Data Fetch
- [ ] Data Caching 
