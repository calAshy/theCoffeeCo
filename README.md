## Project README:
This folder is where the preprocessing, machine learning algorithms and evaluation is created. The primary objective of this project is to perform an in-depth exploratory analysis (EDA) on the capabilities of unsupervised learning models and their ability to segment customers using transaction data. 

## Project Structure:
The folder structure for this project is broken down in the following way: 

- 0_Data
    - processed_data
    - raw_data

- 1_Project_Notebooks
    - Notebook_1
    - Notebook_2
    - Notebook_3

- README.md
- requirements.txt

-----------------------------------------------------------------------------
## Folder Explanations:

*0_Data* houses the folders: 'processed_data' and 'raw_data'. The 'raw_data' folder is where the initial unprocessed datasets are imported. Then 'processed_data' represents where the preprocessed and merged datasets are created and saved. 

*1_Project_Notebooks* is where the main project lives. This folder holds the notebooks 1, 2 and 3. Notebook_1 is where preprocessing is started on the first two datasets and where these two datasets are merged together creating a master dataset -> 'merged_df'. Notebook_2 is where this master dataset is enriched with complimentary features from the third dataset. Once added the master dataset is then used to create the customer profiling dataset 'customer_features' (This is the dataset that will be fed into the machine learning pipeline). Notebook_3 is where the machine learning pipeline is implemented, paired with analysis of the results and an example of application. 

The file *README.md* (this file) is where the project introduction and set up information is housed. 
 
Finally, *requirements.txt* is a text file containing a list of all of the dependencies and imports needed to run the project correctly. 

-----------------------------------------------------------------------------
## Setting up the project enviroment:

To start open the project root folder in VS Code. This is done to ensure the folder structure is preserved and allows the implemented file paths to run correctly. 

This project has been designed to be run in Visual Studio Code. In order to run the notebooks correctly, ensure the following extensions are installed (found in the 'Extensions' panel in VS Code): 

### Extensions Needed:
- "Jupyter"
- "Python"

Before running any of the notebooks, the list of dependencies will also need to be installed into the project onto a the local machine. Running the following command will execute this step: 
 
*(Python 3.10+ needed):*
> pip install -r requirements.txt

-----------------------------------------------------------------------------
## Running the project: 
At this point the project will be ready to be run. In order to avoid errors on compiling, the notebooks must be run in a specific order. Firstly, open the folder titled: '1_Project_Notebooks' then in order running each notebook: 

### Notebook Execution Order: 
 > Notebook_1 ->  Notebook_2 ->  Notebook_3


