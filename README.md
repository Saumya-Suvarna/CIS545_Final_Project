# CIS545 Final Project | Group 30 | Fall 2021
---
## Group Members: Saumya Suvarna and Vijay Yevatkar


---
### Notebook Structure:
---
We have 3 Notebooks that are being submitted. Please run them in Google Colaboratory in the following order:

1. [Wrangling_And_EDA.ipynb](https://colab.research.google.com/drive/1lZhdWA0IxwM9bQPokf7yynX8iRltJ0Ry?authuser=2#scrollTo=YlGOaLuGDDyF)
2. [Modeling_And_Bias.ipynb](https://colab.research.google.com/drive/1bLTKZP2xyjnMfn2lZh5-_EJnzdsnks6m?authuser=2#scrollTo=rNxzJixUWJBC)
3. [Interpretability.ipynb](https://colab.research.google.com/drive/1A1qq1yEfcZ3cIVE8eiBX80Jxu3YXExo6?authuser=2#scrollTo=74jzleyizj4J)


---
### Data Flow
---
1. Wrangling_And_EDA.ipynb
    - In this notebook, the main dataset csv is being downloaded from the public link of [Murder Accountability Project](http://www.murderdata.org/p/data-docs.html) | [CSV File link](http://www.murderdata.org/p/data-docs.html)
    - For GeoMapping, we require the USA map shape file which we are storing in this [Public Drive link](https://drive.google.com/drive/u/2/folders/1BIgjyP0x5dotmoojJHzkBEl-M753Rc6c) accessible only via SEAS emails. You will be required to Mount your GDrive and add a shortcut of this folder (namely `CIS545_Final_Project_Files`) folder into your `My Drive` location. All further data will be stored and collected from here.
    - The above drive link also stores the `income_state.csv` file which is downladed from the [US Census website](https://www.census.gov/data/tables/time-series/demo/income-poverty/historical-income-households.html)
    - Finally, the EDA data is stored in your local drive folder copy with the name `decoded_data_with_avg.csv` - This file is essential for the 2nd part
2. Modeling_And_Bias.ipynb
    - Again, the your GDrive has to be mounted and this notebook expects the file `decoded_data_with_avg.csv` to be present. This will be created after successful execution of the above notebook.
    - 2 pickle files namely - `all_encoded_data_offsex.pickle` and `feature_data_offsex.pickle` will be stored in your local drive folder copy.
3. Interpretability.ipynb
    - GDrive is again mounted and both the files `all_encoded_data_offsex.pickle` and `feature_data_offsex.pickle` are expected to be present. Both these files will be created after successful execution of the above notebook.
 
    