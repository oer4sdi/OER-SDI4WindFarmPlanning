# Leveraging Spatial Data Infrastructures for Wind Farm Expansion 

![alt text](https://www.bundesregierung.de/resource/image/2060958/16x9/990/557/802c8758c9ed57e5a4558d93089f82c2/vT/2022-06-15-grafik-wind-an-land-neu-en.png)

Photo: Graphic Federal Government Foto: Getty Images/Westend61

## *1. OER Overview*
The Federal Government in Germany has set itself a target of doubling the amount of electricity generated from renewable sources by 2030. Wind power will play a major role in this. Expanding an existing wind farm is a cost-effective way to increase the energy production. This OER module is focused on harnessing the power of Spatial Data Infrasturture to support wind farm planning.



Understanding the fundamentals of SDIs, performing basic spatial data analysis, and having practical experience using SDIs to expand wind farms are the learning objectives for this course.
Upon completion of this OER module, participants should acquire the necessary skills to:
- find and access geographic data from Spatial Data Infrastructure.
- Review metadata to evaluate the accuracy and currency of data.
- Use GIS Desktop software (QGIS) to manage geographic data and perform spatial analysis.  
- Create maps to visualize potential areas for wind energy farm extension, and interpret the results to make informed decisions.




## *2. Introduction*
The importance of wind energy as a renewable energy source is on the rise. Increasing the share of renewable and clean energy in the global energy mix is essential for achieving United Nations Sustainable Development Goals such as SDG 7 (Affordable and Clean Energy).
To support the development of wind farm projects it is crucial to work with realiable and updated geographic data.Spatial Information Infrastructure (SII) refers to a framework of geospatial data, technologies, policies, and standards that enable the collection, management, analysis, and dissemination of spatial information. SII is a comprehensive system that facilitates the integration and sharing of geospatial data and related information across different organizations, sectors, and levels of government.

## *3. Scope*

While Germany is one of the leaders in the development of wind energy with goal to allocate 2% of Germany's land area to wind power energy by 2032, the nation faces a number of obstacles and difficulties when constructing or expanding exisiting wind farms, including restrictions on building near protected areas, as well as concerns over noise pollution from wind turbines that can impact the health and well-being of nearby residents and animals.


## *4. Workflows*
A local authority in Lower Saxony has hired you to cooperate with a private investor to identify several potential sites in the state for enlarging and repowering existing wind farms with high-efficiency wind turbines. The selected site must meet several characteristics:

-	Located in the state of Lower Saxony
-	Within 4 km of existing wind farms containing turbines 
-	Within at least 800 m of neighboring houses
-   Does not intersect with any protected site
  
in order to meet these criteria, you need to explore and find the data for administrative boundaries, existing wind farms, buildings, and protected sites. Next, you'll start querying these layers to narrow down locations with the characteristics you want. Finally, you'll combine these into a single layer on which you can conduct a multicriteria analysis to locate a few viable sites.



## *5. Data Search and Download*

Identifying the precise type of data needed for the task is crucial before looking for and downloading geographic data. Finding geographic data is made easier by using Spatial Data Infrastructure. They enable quick and easy access to a variety of data from many sources, saving time and effort while looking for information. Additionally encouraging transparency, interoperability , innovation, and cost-effectiveness.

In this OER module, our focus will be on Lorup, a municipality in the Emsland district, in Lower Saxony. The module's primary objective is to identify SDIs that can supply precise geographical data related to wind energy.

To begin with, we need to download the required data from the [Marktstammdatenregister](www.marktstammdatenregister.de), MaStR is a register of the electricity and gas market in Germany, providing detailed information on renewable energy installations. It can be accessed by authorities and market players in the energy sector, and the information is publicly available for analysis of the renewable energy market. MaStR data is helpful in identifying opportunities for expanding the wind energy market in Germany.
1. Open your web browser and go to www.marktstammdatenregister.de, navigate to the "units" tab
- ![alt text]()

2. In this we page, you can download data for all renewable energy plants in Germany, including wind energy plants. To download data for wind energy plants only, click on the "Filter" button and Choose Energy Eource is equivalent to "Wind" and Community is equivalent to "Lorup", before clicking apply filter choose Extended Unit Overview on the top right corner of the table then click "Apply Filter".

- ![alt text]()

3. After applying the filter, the website will display a table containing all the registered wind energy plants in Lorup.click on the "Export" button at the top of the table.

4. In the export options, select the desired file format and then click "Exportieren" to start the download.

![alt text]()

5. Once the data is downloaded from MaStR as a CSV file, the next step is to import the table into QGIS in Data Prepration Section








In addition to the MaStR website, [The State Office for Geoinformation and State Surveying Lower Saxony](https://opengeodata.lgln.niedersachsen.de/) offer Open Geo Data for Lower Saxony, which we can access for our wind energy expansion analysis. The data available on the website, such as administrative boundary and building data, can be downloaded to help us designate our area of interest and correspond to constraints related to the distance between living houses and wind turbines. 



1. Go to the [The State Office for Geoinformation and State Surveying Lower Saxony](https://opengeodata.lgln.niedersachsen.de/), and click on the "Product Overview" button located in the top right corner of the page.
![alt text]()
 
2. Select the "ADMINISTRATIVE BOUNDARIES ATKIS" category from the list of available datasets, check the dataset details to know more information about coordinate reference system, Detailed product description, Format, license terms and conditions, and metadata [metadata](https://geoportal.geodaten.niedersachsen.de/harvest/srv/api/records/5c115053-be97-4072-9957-818673219aa5/formatters/xml)
   
![alt text]()
 
3. After checking meta data, got download tab and click on the "Download" button, Save the downloaded file to your computer or the desired location as we will need it later.
![alt text]()



## *6. Data Prepration*


## *7. suitability Analysis*



##  Self Assesment
In this OER module We will focus on wind farm expansion in Lower Saxony.Participants will learn how to leverage spatial data infrastructure. Upon completion of the tutorial, participants will be encouraged to apply the same steps they have learned to expand wind farms in North Rhine Westphalia(NRW).

