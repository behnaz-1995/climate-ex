# Create a virtual environment and install the requirements
```
python -m venv .venv
.\.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```
# Info 
1. change the name of the data to (data.nc)
2. Computing the following indices for temperature and precipitation :
   
Temperature
*  Monthly Maximum Value of Daily Maximum Temperature (TXx)
*  Monthly Minimum Value of Daily Minimum Temperature (TNn)
  
Precipitation
*  Monthly 1-day Precipitation  (Rx1day)
*  Consecutive Dry Days (CDD)
