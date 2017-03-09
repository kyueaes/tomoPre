# tomoPre
#
Preprocessing python function before tomo reconstruction

For this script, there are two ways to define prefers parameters. 

The first way is to define the parameters in Stitching_InitConv_TIFFtoHDF4_single.py and Stitching_InitConv_TIFFtoHDF4.py file.

The function are:

prefInitSinglePy()
prefInitPy()

The second way is to use the matlab file under matlab folder to generate a test.mat file, and use python to readin all the parameters.

The function is:

prefInitMatlab()

The function used for reading the data from the image file:

dataPrepare(prefs)


rec_1ID_example.py is example script for using the preprocessing function with tomopy.
