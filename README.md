# weatherApiExcel
### First Install the required libraries.
~~~python
pip install requirments.txt
~~~
#### You will need to get your AOI key for live wether data from openweathermap.org go to below link to get your api

https://openweathermap.org/price

#### Use free services that all we need here. That will give you your API key that page it in place of {Your API Key Here} in app.py file line 67.

#### Run the app.py and it will create a excel file with 2 sheets sheet one will contain the City Name and The temperature recoded in that city , and Sheets2 contains List of cities (to make file size short i only included Indian cities) the data about cities is in city.json file this sheet contain City Id , City Name, Country Code(which is IN for India) after running code will also create a data.txt file wich will be updated every 3 seconds and you can impot text dat in excel file for aut refres whenever the file is changed.


### Thanks
