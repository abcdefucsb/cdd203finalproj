# Project Name
To Block or Not To Block:
Predicting hERG Channel Blockade with Machine Learning: A Data-Driven Approach


## Data
Data can be imported with python script
```bash
from tdc.single_pred import Tox
data = Tox(name = 'hERG_Karim')
split = data.get_split()
```
Data can also be accessed in data/herg_karim.tab

## Download Repo
Download as a ZIP file (No Git required)
<br>
Go to the repository page on GitHub.
<br>
Click the green Code button located above the file list.
<br>
Select Download ZIP from the dropdown.
<br>
The repository will be downloaded as a ZIP file. You can then unzip it to access the contents.
<br>

## Set Up Virtual Environment & Install Packages
(1)Recommened: Run the python script, using Google Colab
<br>
or
<br>
(2a) Set up virtual environment: 
<br>
    (2a1)Install Python (if not already installed)
    <br>
    First, make sure Python is installed on your system. You can check if Python is installed by running the following command in your terminal or command prompt:
    <br>
    ```bash
    python --version
    or
    python3 --version
    ```
    <br>
    I used python 3.13.0
    <br>
    (2a2)Create a Virtual Environment
    <br>
    In your project directory (or wherever you want the virtual environment), run the following command:
    <br>
    ```bash
    python -m venv myenv
    ```
    <br>
    myenv is the name of the virtual environment. You can replace it with any name you prefer.
    <br>
    This will create a folder named myenv in your project directory containing the virtual environment.
    <br>
    (2a3)Activate the Virtual Environment
    <br>
    ```bash
    .\myenv\Scripts\activate
    ```
    
   
When the virtual environment is activated, your terminal prompt should change to show the virtual environment name, like this:

   
```bash
(myenv) $
```
    



    
and
<br>
(2b)Install packages: use the command
<br>
```bash
!pip install pytdc xgboost rdkit scikit-learn pandas numpy
```
<br>
In this way, pytdc-1.1.1, xgboost-2.1.3, rdkit-2024.3.6, scikit-learn-1.5.2, pandas-2.2.2, and numpy-1.26.4 are installed.<br>

