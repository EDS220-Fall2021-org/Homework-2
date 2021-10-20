# Homework 2
## Learning about Datasets

For this homework assignment, your goals are to get to know an environmental dataset of your choice. Work together in groups of 3; then collectively:

### 1. Write code to load in the dataset 

Using the example codes provided in this template repo, load in your dataset into Python. You should include a discussion of the data format used here (netCDF? CSV? HDF5? Other?) 

You may choose to work with a dataset which has been ported to Google Earth Engine. However, if you do so, you should include a discussion of the file formats used by the original dataset (it's good to know the primary sources of your information!)

Things to discuss regarding the input data files:
- How are they organized? Daily output? Monthly? Are all variables included in a single file, or multiple?
- What kind of metadata are provided?
- What format are the date and geospatial coordinate information provided in?

In your example code, provide commands that allow a user to view the various metadata fields available.


### 2. Investigate data quality

Consider the quality control measures implemented in your dataset. Not all of these factors will be equally important for all datasets, but assess:
- The presence of any data artifacts: gaps in data, outliers/unphysical spikes, etc.
- Data coverage and completeness, both spatially and temporally
- Any systematic biases or limitations associated with the instruments used to generate the data/algorithms involved in post-processing



### 3. Consider appropriate use cases

Given your previous results, now consider when this dataset might be more or less appropriate for use. Example considerations might include:
- Detection of long-term trends
- Identification of extreme events
- Usability for high spatial resolution applications

Give some examples of user groups who might benefit most from application of this information, and some examples of areas where the data might be most relevant.


### 4. Prepare dataset overview for class presentation
Prepare a brief (~3-4 minute) presentation for class Wednesday, November 3 summarizing the results of part 1-3 above!
