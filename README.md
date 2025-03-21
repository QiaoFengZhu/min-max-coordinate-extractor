# min-max-coordinate-extractor

## Overview

This Jupyter Notebook (`min_max_extractor.ipynb`) is designed to scan a directory named `Data` and its subdirectories for CSV files. It extracts specific data from each CSV file and compiles the results into a summary CSV file. The summary includes the file name, file path and the minimum and maximum values of the `Coord_X` and `Coord_Y` columns for each CSV file.

## Instructions 

### 1. Clone the repository or download the notebook 
- Clone the repository or download the min_max_coordinate_extractor.ipynb notebook to your local machine.

### 2. Prepare the Data Directory
- Make sure the notebook is located in the same directory as the "Data" folder:
```
├── Data/
|  ├── subfolder1/
|  │   ├── file1.csv
|  │   └── subsubfolder1/
|  │       └── file2.csv
|  ├── subfolder2/
|  │   └── file3.csv
|  └── file4.csv
├── min_max_coordinate_extractor.ipynb <---
```
### 3. Run the notebook
- Make sure that the Data folder containing the csv files is named 'Data'. If not, change the string assigned to 'data_folder_path' at the top of cell 2 to the coresponding folder name.
- Execute the cells in the notebook.
- The results will be outputed in a summary csv file named 'Locations.csv' in the same directory as the notebook. 
