# TEC_CMU
Here is the process to read TEC data from matlab
1. main program is "main_teccal_30.m" 💡


👉 change outname (ex "CM013160"), stations, and p_path as your directory the you will get matfile in **Results** folder.
  
👉 To test the program, please download the RINEX file from https://drive.google.com/drive/folders/13-18mmAL4U4alot1mx9xbqvDfGlgyGbc?usp=sharing to folder RINEX


2. "Run **mat2dataframe.p**y in the Python folder to get file.csv. [-- MATLAB (**convertmat2csv.m**) also works!)]"
3. plot data from csv
python/Example plot from_JB_CM013160.jpg

![My Plot](python/Example_plot_from_JB_CM013160.jpg.png)
