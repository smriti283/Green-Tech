# Network Size and Green Technology Innovation

## Overview - Theory of Change & Research Question

As the world continues to see and feel the impacts of climate change, including urban smog, more frequent forest fires, rising ocean temperatures, and more frequent and stronger hurricanes, ensuring green technology innovation is as successful and as efficient as possible constitutes an increasingly high priority. Our group was interested in how the geographic dispersal of researchers affected this efficiency. Empirical evidence from previous studies has borne out that the number of patents produced in a given place is directly correlated with population at increasing returns to scale. Researchers have theorized that these increasing returns are partially the result of the informal connections and interactions that larger metropolitan areas facilitate, as well as the thicker employment markets found there. Collaboration between academia and industry is likely also more easily facilitated in these areas in which industry actors are typically located.

**Articulated simply, our research question asks:** 

Does professional network size matter in innovation? 

## Dataset
- [StarMetrics Federal Reporter](https://federalreporter.nih.gov)
  Federal Grants data for the period 2010-2018
- [USPTO Patents View](https://patentsview.org)
  Federal Patents data for the period 2010-2020
- [US Census Bureau Cartographic Boundary Files](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.2014.html)
  Cartographic shapefile (2014) for map visualizations

## Methodology: Quantifying Innovation through Patents

Our outcome of interest is the number of patents produced within a given city as a function of the number of PIs (and associated researchers) and the dollar amount of grants received.

![alt text]

#### Some Definitions
- **Network:** The principle investigators & associated researchers located within a given city.
- **Grant Funding:** The amount of money awarded in grant funding to researchers for a given city,  measured in dollars.
- **Innovation:** The number of patents produced.

### Step 1: Identify Green Technology Grants

We defined green technology with by applying the NLP model Latent Dirichlet Allocation (LDA), also known as topic modeling. We made all the abstracts go through the steps of stemming, lemmatization and vectorization and segregated them in 10 topics, that gave us following green-tech keywords from the entire corpus of words.

![alt text]

Using the grant abstracts and the above keywords, we filtered our dataset for green grants.

This yielded 30,274 or 3.8% of all available grants. The grants are approximately uniformly distributed across 2010-2018.

### Step 2: Record Linkage of Grants and Patents




