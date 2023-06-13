Group 23 - Pansharpening Of Multispectral Images

On inputting a panchromatic and multispectral image, you get a pan-sharpening high-resolution image as an output. We used IHS, Mean and Brovey pan-sharpening techniques.

• A Pdf/Slides of the project has been uploaded to give an overview of our research.

• Input images are in the folders MS (multispectral) and Pan (Panchromatic), and output images in the Output folder.

• Our code is in the final_python_file.py file.

Due to the complexity of our code and the constraint of inputting two images, we faced several errors while making a .exe file.
We still uploaded it, but the file fails to load sometimes and shows an error on one of the module 'rasterio' we used.

We derived excellent results using our code and to verify:
1. Save and run the code
2. To Check for a different image -- At line 19,20 just change
 'MS/MS_1.tif'  ---> 'MS/MS_2.tif'
 'PAN/PAN_1.tif' ----> 'PAN/PAN_2.tif'
Basically changing the index to test different images 

After you run the code, an image will appear which isn't the only output image. You'll be able to view all the images but they will appear one by one. As first image appears, close it, then the next one appears and so on. With that we show all the results one by one and the final image making the net comparison using all the techniques