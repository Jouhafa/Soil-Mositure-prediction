# Datasets Readme :
This file will provide you information about the datasets;
## The Field measurrements : (SMC_dataset)
An important part of the dataset is the exact value of the soil moisture in the desired area, and this information is vital to train our model and also to validate it and test afterwards;
So to grab some credible datasets about this information, I referred to  the "International Soil Moisture Network", find the link below, that provides a world map of the soil moisture network, and  it's a huge network full of nodes that represents different points in the map;

P.S: the colors represent the duration of the period where the data is available about that area, and make sure that you adjusting the time range for your research  
P.S 2: Shit+drag to select the area that you want + the selection of the time range, that will help you avoid downloading a dataset of the whole network; 

Finally, follow my code to extract your dataset as a .csv file, or maybe if you want to dig deeper, you can check the documentation about it *https://ismn.readthedocs.io/en/latest/*

**Link to the network map :** *https://www.geo.tuwien.ac.at/insitu/data_viewer/?user_id=8964&session=cd5gv1usj4xc66v010gxnarajc0616om#*

## Images dataset :
Second thing in the dataset is our inputs, Satellite images. For this Matter I chose to work with the Sentinal collections provided by *Earth Engine*, and more precisely, the Sentinel-2 MSI with images of the Surface reflectance;
The Earth enigne catalog provides a dataset from 2017-03-28 to  2021-08-03 which may help you build a reasonable dataset;

Finally, The choice of the satellite bands that you will work with, for me I downloaded from B1 to B12. However, you may want to read a bit about it before;

P.S: Your images have definitely to capture the area from the soil moisture network, and for this you may use the help of Google Maps to get some exact coordinates;
P.S 2: the Earth Engine requires having a ee account, so make sure to register first and wait for your application to be accepted;

**Link to Sentinel-2:** *https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2_SR*

## The Dataset :
After downloading the your images and their corresponding values of soil moisture, you may want to synchronize all of this in one dataset with mabye just 2 or 3 columns (Date_time, Soil_mositure, Image_name or Image_path);

You can find all of this in the **data collection** part; 
