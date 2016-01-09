# Dataviz-with-python
#### Python script to generate json dataset, json based graphs and maps v1.1 - Jan 2016
---
This rep contain Python scripts to build json datasets from open data available through API (e.g. World Bank, UN, Quandl etc.).
These dataviz and dataset have been created to build AFD Country Dashboards and Coutry at a Glance (http://stats4dev.com/glance), a project of development economics dataviz portal to help informing economic and social context to development practitionners.

This rep contains:
+ Json datasets builder: Creating a Json Database HDRdata, IMF and WDI.ipynb 
+ Dataviz for dev builder.ipynb
+ A repository containing json datasets which structure is organized this way:

 ```javascript
{
  "FM.LBL.MQMY.GD.ZS": {
    "label": "Money and quasi money (M2) as % of GDP",
    "info": " ",
    "YearMin": 2013,
    "YearMax": 2014,
    "AGO2014": 39.5611669731,
    "AGO2013": 36.699709125,
    "SSF2014": 36.6572761603,
    "SSF2013": 37.6087125097,
    "UMC2014": 136.9621174532,
    "UMC2013": 129.5101900065,
    "WLD2014": 112.8607789282,
    "WLD2013": 110.6236750281,
      },
  "AGO": {
    "country": "Angola",
    "region": "Sub-Saharan Africa",
    "incomegroup": "Upper middle income"
  },
  "data_source": {
    "source": "World Bank, WDI",
    "provider": "World Bank, API",
    "Download_date": "2015-11-06"
        }
    }
    ```
+ exemple of such a json file used to feed the dataviz: http://www.stats4dev.com/glance/data/WB_WDI_BRA.json 
