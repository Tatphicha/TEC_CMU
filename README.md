# TEC_CMU
Here is the process to read TEC data from matlab
1. main program is "main_teccal_30.m" to get file.mat💡


👉 change outname (ex "CM013160"), stations, and p_path as your directory the you will get matfile in **Results** folder.

:boom::boom:  Don’t forget to change **p_path** this to your directory path. :boom::boom:
  
👉 To test the program, please download the RINEX file from https://drive.google.com/drive/folders/13-18mmAL4U4alot1mx9xbqvDfGlgyGbc?usp=sharing to folder RINEX


2. "Run **mat2dataframe.p**y in the Python folder to get file.csv. [-- MATLAB (**convertmat2csv.m**) also works!)]"
3. plot data from csv (an example plot for CM013160 from P'Jumbo) :point_down::point_down:
## 
<img src="python/Example_plot_from_JB_CM013160.jpg" width="600">


