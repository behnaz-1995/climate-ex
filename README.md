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
*  Monthly max daily max temp (TXx)
*  Monthly min daily max temp (TXn)
Precipitation
*  Monthly 1-day precip (Rx1day)
*  Consecutive dry days (CDD)
