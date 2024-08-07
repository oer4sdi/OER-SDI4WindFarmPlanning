# 1. Questions

**1.1 What bodies, processes and artifacts can you identify at the policy, organization, and implementation levels of the GDI NI?**

|  | Bodies/Institutions | Processes | Artifacts |
|----------|----------|----------|----------|
| Policy | A1 | B1 | C1 |
| Organizational | A2 | B2 | C2 |
| Implementation | A3 | B3 | C3 |

**Try to assign the following institutions, processes and artifacts to the correct positions in the table:**

- (A1)  State Parliament of Lower Saxony 
- (B2)  Technical coordination of GDI-NI 
- (C3)  WFS NI ALKIS (simplified) /n
- (A2)  GDI-NI coordination office at the State Office for Geoinformation and
       Surveying of Lower Saxony (LGLN)
- (B3)  Searching and accessing spatial datasets and services
- (C2)  Guidance document on creating high-quality metadata
- (C1)  Lower Saxony Spatial Data Infrastructure Act
- (A3)  The Revento GmbH, consuming high-quality spatial data 
       in the context of wind farm planning
- (B1)  Transposing INSPIRE into state law in Lower Saxony


**1.2 What is the difference between the geoportal and the metadata catalog of a Spatial Data Infrastructure?** 

  The SDI's geoportal is the web site that provides comprehensive information on the SDI. The SDI metadata catalog is a back-end component that supports storage and retrieval of metadata. The catalog can be accessed a) by humans via the geoportal’s user interface and b) by machines via its API (e.g. OGC CSW or OGC API records).  

**1.3 What makes a metadata catalog a federated metadata catalog?**

   A federated system of metadata catalogs is characterized by the fact that they update each other according to certain rules and thus share metadata with each other. A catalog becomes a member of such a federation, and thus a federated catalog, when it actively or passively participates in such a federation. 
- Active: push metadata to subscribing catalogs
- Passive: respond to pull-requests from requesting catalogs.

For example, GDI-DE actively harvests metadata from all metadata catalogs of the German states. INSPIRE harvests metadata from the national geoportals of the member states. All participating metadata catalogs are federated catalogs.

**1.4 What are the advantages of a web feature service over a simple file download?**

   With file download, a preconfigured amount of data is offered for download as a single file or file archive. In this case, you usually download a lot of data that you don't need at all. A feature service allows direct selective access to data objects in a database. You can specify not only which data should be delivered, but also in which spatial reference system and in which format the data should be delivered. Feature services can be used to provide many views at one and the same dataset. With transactional feature services, data can also be written to the dataset.

# 2. Tasks

**2.1 Identifying potential areas for wind farms in the municipality of Saerbeck, North-Rhine Westphalia, Germany**

The municipality "Saerbeck" in the district of Steinfurt, North Rhine-Westphalia would like to determine which areas are available for the extended use of wind power in their municipal area. In a first step, existing nature reserves (NSG) and residential buildings are to be considered.
Use the Geodata Infrastructure North Rhine-Westphalia (GDI-NRW) to acquire suitable data on municipal boundaries, existing wind turbines, nature reserves and building footprints for your data analysis. Calculate the exclusion areas of the nature reserves (100m buffer) and the distance areas to residential buildings (500m buffer) as for Lorup and subtract them from the municipality area.

Sample solution: 

The screenprint shows how the result could look like:
   ![QGIS_Saerbeck_WFP](https://github.com/oer4sdi/OER-WindFarmExtension/assets/4353298/5713cea0-d124-4920-b0f8-0901e6140f58)

Tips:

- All data can be found in the Geoportal NRW
- Most of the data can be accessed via WFS. Make sure that you use the option "only request features overlapping the view extent" to avoid downloading the complete dataset again and again when working with the data. Extract the features from the WFS to a local dataset to avoid unnnecessary interactions with the WFS server over the Web.
- Be aware that the INSPIRE WFS on Protected Sites provides you with all kinds of protected Sites, not only Nature Reserves. In this case it is better to use the dataset on Nature Reserves that is provided by LANUF as a shape file. This dataset and the download link is provided in the geoportal as well. 
