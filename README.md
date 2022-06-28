# ETL 
### :page_facing_up: **Objective**
Develop an ETL (Extract, Load, Transform) of data related with national spanish elections from 2019. These data is enriched with unemployment rates by province and rent per capita.

### :nut_and_bolt: **Deployment**
#### :key: Prerequisites
1. To have installed `conda`
2. To have installed `git`

#### :one: Installation instructions
The installation process is the next:
  1. Clone this repository
   
    git clone <url-repo>

  2. Execute in the terminal
   
    conda env create -n etl -f environment.yml

----
#### :file_folder: **Folder structure**
```
└── ETL_ih
    ├── .gitignore
    ├── data
        ├── 
        ├── 
        ├──      
    ├── nb
        ├── data_extraction.ipynb
        ├── 
        ├──     
    ├── img
        ├── 
        ├── 
        ├──    
    ├── sql
        ├──
        ├── 
        ├──  
    ├── environment.yml
    ├── README.md   
```



### :computer: **Technology stack**

------
### :boom: **Analysis developed**
*1*. *Data extraction*
- WebScraping
    - Agencia Tributaria - Rent per capita by province
    - Unemployment rate in 2019 ([datos.gob.es](https://sede.sepe.gob.es/es/portaltrabaja/resources/sede/datos_abiertos/datos/Paro_por_municipios_2019_csv.csv))
- CSV download
    - Election result data ([infoelectoral](https://infoelectoral.interior.gob.es/opencms/es/elecciones-celebradas/area-de-descargas/))

----
### :pushpin: **Some insights**




---








### :shit: **ToDo**
