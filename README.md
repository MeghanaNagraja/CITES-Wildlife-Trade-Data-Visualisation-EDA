# CITES Wildlife Trade Data Visualisation

The Convention on International Trade in Endangered Species of Wild Fauna and Flora, or CITES for short, is an international treaty organization tasked with monitoring, reporting, and providing recommendations on the international species trade.
The dataset contains records on every international legal import or export conducted with species from the CITES. 
It contains columns identifying the species, the import and export countries, and the amount and characteristics of the goods being traded (which range from live animals to skins and cadavers).

Acknowledgment: https://trade.cites.org/ (or)
https://www.kaggle.com/datasets/cites/cites-wildlife-trade-database

## Approach

    - Data is downloaded directly from the website mentioned above
    - Merged files have over 25 million records and therefore only animal (fauna) records were considered
    - Data checks were done (Dropping unnecessary columns and missing values filled)
    - All the codes of countries, purpose, source were converted to common language
    - Inconsistent units were fixed
    - Data was aggregated to reduce millions of records to lakhs
    - Data uploaded to MySQL database
    - Data queried to arrive at insights
    - Visualisation of different insigts
    
