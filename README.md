# Elections 2019 :es:
### :page_facing_up: **Objective**
Explorar mediante los datos de las elecciones de 2019 y de renta media y paro la estructura social votante de españa.


### :nut_and_bolt: **Deployment**
#### :key: Prerequisites
1. To have installed `conda`
2. To have installed `git`

#### :one: Installation instructions
The installation process is the next:
  1. Clone this repository
   
    git clone <url-repo>

  2. Execute in the terminal
   
    conda env create -n elec -f environment.yml

----
#### :file_folder: **Folder structure**
```
└── Elections2019
    ├── .gitignore
    ├── data
        ├── ccaa_renta.csv
        ├── provincias_renta.csv
        ├── resultados_elecciones_2019.csv
        ├── Paro_por_municipios_2019_csv.csv
        ├── Partidospoliticos_ccaa.csv    
    ├── nb
        ├── data_extraction_income_tax.ipynb
        ├── data_extraction_unemployment.ipynb
        ├── data_prep_manually_downloaded.ipynb 
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
- Jupyter Notebook
- MySQL
- PowerBI


------
### :boom: **Analysis developed**
*1*. *Data extraction*
- WebScraping
    - Agencia Tributaria - Rent per capita by province 
    - Instituto Vasco de Estadística ([eustat]) (https://es.eustat.eus/)
    - Instituto de Estadística de Navarra ([navstat]) (https://nastat.navarra.es/)
    - Unemployment rate in 2019 ([datos.gob.es](https://sede.sepe.gob.es/es/portaltrabaja/resources/sede/datos_abiertos/datos/Paro_por_municipios_2019_csv.csv))
- CSV download
    - Election result data ([infoelectoral](https://infoelectoral.interior.gob.es/opencms/es/elecciones-celebradas/area-de-descargas/))
    - 

----
### :pushpin: **Some insights**




---








### :shit: **ToDo**
Explicar que tipos