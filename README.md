# andorra_explorer
Crowdsourcing environmental information in Andorra's natural ecosystems. 

# Using cleaning_coordinates.ipynb

This scrip processes a raw txt file from the logger. Follow these steps to process your files. 

1. Drop .txt file into the test_data folder. 
2. Open the notebook. 
3. Head to **Clean File** section. 
4. Change file name in call to `clean_gps_data('file_name')` function.
5. Run full script. 
6. Your new file should be in the processed_data folder. It will have the same name as the original file with `_dd.csv` appended to the end.
7. This file is ready to be used in [Kepler's GUI](https://kepler.gl/demo). You just need to drag and drop the file and it should automatically plot out the points. 
8. Explore data and different visualizations. Happy mapping! 