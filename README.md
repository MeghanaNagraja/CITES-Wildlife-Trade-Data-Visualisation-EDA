# CITES Wildlife Trade Data Visualisation

The Convention on International Trade in Endangered Species of Wild Fauna and Flora, or CITES for short, is an international treaty organization tasked with monitoring, reporting, and providing recommendations on the international species trade.
The dataset contains records on every international legal import or export conducted with species from the CITES. 
It contains columns identifying the species, the import and export countries, and the amount and characteristics of the goods being traded (which range from live animals to skins and cadavers).

Acknowledgment: https://trade.cites.org/ (or)
https://www.kaggle.com/datasets/cites/cites-wildlife-trade-database

![img1](https://github.com/MeghanaNagraja/CITES-Wildlife-Trade-Data-Visualisation-EDA/assets/122547199/11153236-7cbf-4b84-92b5-bdc45d83cff2)
![img2](https://github.com/MeghanaNagraja/CITES-Wildlife-Trade-Data-Visualisation-EDA/assets/122547199/825bf5aa-5bbd-4bd8-b93f-72b695f99d6c)

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

![img8](https://github.com/MeghanaNagraja/CITES-Wildlife-Trade-Data-Visualisation-EDA/assets/122547199/292ca351-8279-46ee-9702-e5f73ddcea97)
![img4](https://github.com/MeghanaNagraja/CITES-Wildlife-Trade-Data-Visualisation-EDA/assets/122547199/5cc8837c-9be3-445a-9f5f-f50b00a16f0d)
![img5](https://github.com/MeghanaNagraja/CITES-Wildlife-Trade-Data-Visualisation-EDA/assets/122547199/84f24379-9402-4937-8094-0118febafed8)

    
