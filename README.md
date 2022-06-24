# ETL 


### :nut_and_bolt: **Deployment**
#### :key: Prerequisites
1. To have installed `conda`
2. To have installed `git`

#### :one: Installation instructions
The installation process is the next:
  1. Clone this repository
  2. Execute in the terminal
   
   `conda env create -n etl -f requirements.txt`


#### :file_folder: **Folder structure**
```
└── ETL_ih
    ├── .gitignore
    ├── requirements.txt
    ├── README.md
    ├── data
        ├── attacks.csv
        ├── 
        ├──      
    ├── nb
        ├── attacks.csv
        ├── 
        ├──     
    ├── sql
        ├── attacks.csv
        ├── 
        ├──     
```



### :computer: **Technology stack**
In this case, the technologies used are based on Python.

- :bar_chart: The libraries included are the ones needed for DataCleaning : Pandas, Numpy, Matplotlib.

- The system is standalone.

------
### :boom: **Analysis developed**
The analysis made include the several steps for data cleaning
1. Erase missing values (~ 18000 rows)
2. Incorrect data types
3. Duplicate rows
4. Handling missing values
5. Standardization
6. Normalization
7. Verification & enrichment of the data
   

----
### :pushpin: **Some insights**

![Image](final_data/insights2.png)

![Image](final_data/insights3.png)

![Image](final_data/insights4.png)



---

----
![Image](https://earimediaprodweb.azurewebsites.net/Api/v1/Multimedia/486fabcb-1fca-45a4-bf3e-373dfbefbdc7/Rendition/low-res/Content/Public)




####


### :shit: **ToDo**
1. Improve insights
2. Improve data cleaning 
   1. Data dict for replace & str.contains
