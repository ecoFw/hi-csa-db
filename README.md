# Hawai‘i Climate Smart Agriculture and Ecosystem Service Database

# Context

The City and County of Honolulu's Office of Climate Resilience has
contracted OACA to produce a Climate Smart Agriculture database
intended to inform food system professionals and policy makers on the
potential ecosystem service impacts of CSA activities. The consultant
(MK Lau) has been sub-contracted by OACA to complete the deliverables
listed below in partial fulfillment of the larger contracted
deliverable to HC&C.


# Database Construction

- The goal is to construct a database of resources to support climate
  smart agricultural practices, using the USDA NRCS climate smart mitigation
  strategies as a framework. 
- Via the data pipeline described in this document, data are ingested
  into the database starting with hand-extracted data gathered by
  Lucas McKinnon and Jackson Hart and then using a webcrawling to
  gather resources from existing websites, including the NRCS, NIFA,
  AMS, and ATTRA.
- A structured relational database in produced and saved to the main
  directory. 

# Project 


- `hi-csa-db.rds` is the database, which is contained in the `data`
  directory.
- `hi-csa-db.Rmd` is an R Notebook that generates the database via a
  data pipeline from extant databases and webcrawlers that gather data
  from several agricultural websites (e.g., NRCS, NIFA, ATTRA, AMS). 
- `data` also contains the webcrawler output.

# Information

- Please submit feature requests and bugs to [issues](issues/ "issues")
- For more information, contact Dr. Matthew Kekoa Lau [mklau3@hawaii.edu](mklau3@hawaii.edu "mklau3@hawaii.edu").
