# 1. Questions

**1.1 What bodies, processes and artifacts can you identify at the policy, organization, and implementation levels of the GDI NI? Try to give at least one example for each cell in the following table.**

   Answers:
   
   - **Policy level**
      - Bodies: state cabinet
      - Processes: legal acts, tasking the steering committee 
      - Artifacts: laws, decisions
   - **Organizational**
      - Bodies: steering committee, coordination office (organized at LGLN), working groups, and all contributing organizations
      - Processes: concept development, project work, communication & coordination
      - Artifacts: reports, concepts, application profiles of standards, guidance documents, ..
   - **Implementation**
      - Bodies: information broker such as the LGLN, content and service providers such asl 
      - Processes: producing and providing datasets and services, publishing datasets and services via metadata, managing the metadata catalog, providing the GDI-NI geoportal (web site)
      - Artifacts: data, metadata, storage, computing and communication infrastructure, service instances, .. 


**1.2 What is the difference between the geoportal and the metadata catalog of a Spatial Data Infrastructure?** 

Answers:

  The GDI-NI geoportal is the web site that provides comprehensive information on the GDI-NI. The GDI-NI metadata catalog is a back-end component that supports storage and retrieval of metadata. The catalog can be accessed a) by humans via the geoportal’s user interface and b) by machines via its API (e.g. OGC CSW or OGC API records).  

**1.3 What makes a metadata catalog a federated metadata catalog?**

A federated system of metadata catalogs is characterized by the fact that they update each other according to certain rules and thus share metadata with each other. A catalog becomes a member of such a federation, and thus a federated catalog, when it actively or passively participates in such a federation. 
- Active: push metadata to subscribing catalogs
- Passive: respond to pull-requests from requesting catalogs.

For example, GDI-DE actively harvests metadata from all metadata catalogs of the German states. INSPIRE harvests metadata from the national geoportals of the member states. All participating metadata catalogs are federated catalogs.

**1.4 What are the advantages of a web feature service over a simple file download?**
