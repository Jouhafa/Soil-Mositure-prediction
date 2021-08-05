## Data collection Read me :
Some important things to keep in mind before and also during the execution of the notebook above :
 
#### 1- Field measurement :
After going through downloading process that you will find in the **Datasets** Readme file, you maybe will have to upload that "Data_separate_files..." file to your drive in case you're working online, otherwise  just get its path from your local folders.
One important thing to keep in mind while following the code to get a .csv file by the end first section of the notebook, is if ever you want to restart again, maybe because you missed something, you have to go back to the folder "Data_separate_files..." and look for a folder named "python metadata" and delete it to  start over. 


#### 2- Satellite Imagery :
So now you decide your area and you have the field measurements of it, you still need just the images of that area;
First thing, you should already went through **Datasets** Readme file and now you have an account in earth engine that will allow you to download from it.

So concerning the things to pay attention to for an accurate downloadinf, are, first the crietera that you want to have on your  images, starting from the shape of the images, the coordinates of each corner to decide onthe filters( region, time_range, bands ...). Maybe you want to read about Imagecollection in eartg engine  before you decide on that;

After launching the downloading that will take a while depending on you time range and the size of your region, we want to tracker it  and see if everything is going okay, so for this matter you can go to *https://code.earthengine.google.com* and connect to your account, and in the **Tasks** tab you will find your images. Gray color means still downloading, blue-downloaded, red-not downloaded.

P.S: when  it gets red, hover on the image and click on ? icon to read what prevented it. Sometimes the filters aren't correct, sometimes is your storages capacity;

Finally, check the folder on your drive;


#### 3- Dataset :
*Synchronize the field measurement with images dates*

Here, the code should work just fine, but there's some decisions to make, like how many column you want in your  dataset ...
while going through the code, try to pay attention to the comment and make your decisions;

