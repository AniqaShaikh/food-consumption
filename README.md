# Description
The relative consumption of certain food items in European and Scandinavian countries. 

# Data
The numbers represent the percentage of the population consuming that food type.

# Preparation
Python version: 3.6
Preparation was carried out keeping in view the utilization and reuzibility of datapackage.json and code respectively. For this purpose couple of script files (`process.py` and `wrapper.py`) were included in scripts folder. `wrapper.py` has the abstract class with generic methods to download raw files and appending data to CSVs. `process.py` has the concrete class, implementing the `setData()` method.

# License
Please follow [this]("http://www.unicode.org/copyright.html#License") for License information
