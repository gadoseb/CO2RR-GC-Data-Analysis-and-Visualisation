# CO2RR-GC-Data-Analysis
GC Data Analysis
Data analysis and elaboration from the Agilent GC instrument in place. Here is a list of the different versions uploaded here:
1. Folder "Files_Example_1": the Notebook gives a comprehensive table of the product mixture. To use it, the GC_Data_collection.ipynb has to be stored in the same folder of the files to be analysed and the final computed table will be saved as GC_outputs.xlsx
2. Folder "Files_Example_2": the Notebook performs all the data analysis from the GC_output.xlsx data. The code calculates the partial current densities and the Faraday efficiencies from the product mixture. The Notebook has to be copied and pasted in the same folder of the data. The output is an output.xlsx file which contains three worksheets:

      a. Data Analysis, table with the following information: product mix areas, Current Density (mAcm-2), CO2 flow rate (mL/min), Ji (mAcm-2), FEi (%).
      
      b. Plot FE (%) vs Current Density (mAcm-2) with trend line for the different total Farday efficiencies.
      
      c. FE (%) mean values and standard error calculation results.

3. GC_Data_collection_V3.ipynb is the same Notebook of V2, but when it runs it asks the user to select the folder which contains the data to avoid the CTRL+C/CTRL+V in every folder.
