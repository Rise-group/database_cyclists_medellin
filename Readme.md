<img src="figs/rise_logo.png" alt="Estructura Carpeta" align="center">
<img src="figs/unal_logo.png" alt="Estructura Carpeta" align="center">

## A database to analyze cycling routes in Medellin, Colombia


Juan P. Ospina-Zapata<sup>1,3</sup>, Victor I. Lopez-Rios<sup>1</sup>, Veronica Botero-Fernandez<sup>1</sup>, Juan C. Duque<sup>2,3</sup> \
\
<sup>1</sup> Universidad Nacional de Colombia, Medellin\
\
<sup>2</sup> Department of Mathematical Sciences, Universidad EAFIT, Medellin, Colombia\
\
<sup>3</sup> RiSE-group, Universidad EAFIT, Medellin, Colombia\
\
\
__maintainer__ = "RiSE Group"  (http://www.rise-group.org/). Universidad EAFIT\
\
__Corresponding author__ = jpospinaz@unal.edu.co (JPO)

### Abstract 

A bicycle route questionnaire was designed to collect information about the characteristics of cyclists and the routes they take. Medellin is used as a case study in this paper due to its strong sociodemographic inequality, land use, urban form diversity and topographical variability. The survey execution targeted bicycle commuters in the city by distributing the questionnaires online, personally by telephone and personally on the street. These data will be useful to support strategies aiming to promote bicycling as a mode of transportation. Several type of analysis may be derived from the data, including an explanation of the factors determining the route choice and route comparisons according to the sociodemographics and locations of users. For instance, these data have already been used by Ospina et al. (2020) [1] where they sought to understand cycling travel distance in Medellin city.

[1] J. P. Ospina, V. Botero-Fernández, J. C. Duque, M. Brussel, and A. Grigolon, “Understanding cycling travel distance: The case of Medellin city (Colombia),” Transp. Res. Part D Transp. Environ., vol. 86, no. 102423, pp. 1–15, 2020.


```tex
@article{XX,
    author = {Ospina-Zapata,Juan P. AND López-Ríos, Víctor I. AND Botero-Fernández, 
                Verónica AND Duque, Juan C.},
    journal = {Data in brief},
    publisher = {Elsevier},
    title = {A database to analyze cycling routes in Medellin, Colombia},
    year = {2019},
    month = {mm},
    volume = {vv},
    url = {xx},
    pages = {1-18},
    abstract = {A bicycle route questionnaire was designed to collect information about the characteristics of cyclists and the routes they take. Medellin is used   as a case study in this paper due to its strong sociodemographic inequality, land use, urban form diversity and topographical variability. The survey execution targeted bicycle commuters in the city by distributing the questionnaires online, personally by telephone and personally on the street. These data will be useful to support strategies aiming to promote bicycling as a mode of transportation. Several type of analysis may be derived from the data, including an explanation of the factors determining the route choice and route comparisons according to the sociodemographics and locations of users. For instance, these data have already been used by Ospina et al. (2020) [1] where they sought to understand cycling travel distance in Medellin city.

[1] J. P. Ospina, V. Botero-Fernández, J. C. Duque, M. Brussel, and A. Grigolon, “Understanding cycling travel distance: The case of Medellin city (Colombia),” Transp. Res. Part D Transp. Environ., vol. 86, no. 102423, pp. 1–15, 2020.},
    number = {nn},
    doi = {xx}
}
```

## Folders

### Folder: <span style="color:red">[Code](Code)</span>

**File_Name** | **Description**
  ---------------------------- | -----------------------------------------------
  Code_Networkx_OSMNx_MEDELLIN OPEN STREET DATA.ipynb | Jupyter Notebook file code to download Medellin’s Street Network from OSMNx.
  105_O_start_intersections_INDEX analysis.ipynb; 106_D_end_intersections_INDEX analysis.ipynb | Jupyter Notebook file code for the Origin and Destination variables related to the intersections. 
  107_O_start_street density_analysis.ipynb; 108_D_end_street density_analysis.ipynb | Jupyter Notebook file code for the Origin and Destination variables related to the street density.
  109_O_start_arcs infrastructure_analysis.ipynb; 110_D_end_arcs_infrastructure analysis.ipynb | Jupyter Notebook file code for the Origin and Destination variables related to the infrastructure of the street segments. 
  113_O_start_LU polygons_analysis.ipynb; 114_D_end_LU polygons_analysis.ipynb | Jupyter Notebook file code for the Origin and Destination variables related to the Land Use. 
  123_OD_encicla_bsindex.ipynb | Jupyter Notebook file code for the Origin and Destination variables related to the stations of the bike sharing system. 
  202_Route Intersection INDEX Analysis.ipynb | Jupyter Notebook file code for the route variables related to the intersections 
  212_Route_LU polygons analysis.ipynb | Jupyter Notebook file code for the route variables related to the land use. 
  221_Route_Infrastructure analysis.ipynb | Jupyter Notebook file code for the route variables related to the infrastructure of the segments.
  
### Folder: <span style="color:red">[Tables](Tables)</span>

**File_Name** | **Description**
  ---------------------------- | -----------------------------------------------
 Ospina_cyclists_BD_DIB.xlsx | Database including all the variables associated with the routes of each of the 810 cyclists in Medellin. 
 
### Folder: <span style="color:red">[Text](Text)</span>

**File_Name** | **Description**
  ---------------------------- | -----------------------------------------------
 Ospina_cyclists_questionnaire.docx | Final version of the survey questionnaire.  
 Ospina_route_list.txt | List of the 810 ID routes included in the database. 
 
## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

  
