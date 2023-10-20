---
title: 8.1. Mapping POI with ODK + KoboToolbox Server
bookShowToC: True
---

_The following workflow showcases the tools and processes used in a simple field mapping project during which HOT trained local NGOs to integrate mapping into existing programs using OpenDataKit and KoboToolBox Server._

<br></br>
***
<br></br>

## Learning Activities

<br></br>

### Project Overview

**Bridging Gaps in Development and Emergency for the Refugee Crisis in East Africa**

East Africa (and Uganda specifically) continues to be the center of one of the world’s largest and fastest growing refugee crises. Uganda’s progressive open-door policy alone has led to an influx of approximately 1.4 million refugees into the country. High mobility of refugees means distribution and size of refugee settlements changes constantly and the need for standardized accessible information to make timely informed decisions about where services need to be planned and built becomes more crucial than ever. Through the use of open-source technical tools combined with a community-based methodology, HOT has been able to address the critical data gap in these contexts by increasing real-time comprehensive data production on infrastructure and services where refugees and host communities reside. To ensure that government and organizations involved in the refugee response know that, first, this data exists and, second, how to effectively use it, HOT has worked extensively to support and train actors on how to systematically incorporate citizen-generated data into their programs to address and fill existing gaps.

**Project page:** [BRIDGING DATA GAPS: MAPPING REFUGEE CONTEXTS IN EAST AFRICA](https://www.hotosm.org/projects/bridging-data-gaps-mapping-refugee-contexts-in-east-africa/)

**Dates:** June 2018 - May 2019

**Status**: Complete

**Tools used:**
* **Field and Remote Data collection**: OpenDataKit (ODK) Collect, Kobo server, HOT Tasking Manager (ID Editor, JOSM)
* **Data Field Monitoring:** OSMand and Maps.me
* **Data Cleaning:** OpenRefine, Excel, JOSM, Python scripts
* **Data Extraction and Visualization:** HOT Export tool, OSM Analytics, QGIS, Overpass Turbo, Umap, HDX

### Field Mapping Workflow

#### 1. Identifying Partners’ Need and Area of Interest/Operation
Through regular interactions and planned meetings with various stakeholders & partners - including UNHCR, OPM, LWF, etc. - the Project Manager and/or Country Manager would work to understand the technical gaps and needs that institutions were facing in strengthening their contributions to the national refugee response. From this point, we would identify data gaps and the institutional skills needed to fill these areas and co-devise an implementation plan to train the group/organization over multiple days to achieve the intended results and outcomes.

Steps used in this phase:
* [Defining Needs and Requirements](https://docs.google.com/document/d/1nsTC2cbT6N1TCsIYmcu6VGQT6m-mLz6nmf-ZwyExeHo/edit?usp=drive_link)


#### 2. Trainings and Capacity-building Exercises
After the extensive consultation process, trainings would be planned and conducted in house or at a partners’ premise. The main objective of these trainings would be to introduce - and attempt to instil - GIS tools and support capacity building with refugee response partners through custom lessons over a short number of days. These training materials were all specifically designed for each partner organization to ensure the resources matched their level of skill/understanding and enable them to adequately improve their practical knowledge. Trainings generally lasted between 2-5 days and covered topics including data collection, storage, extraction, analysis and visualization.

Steps used in this phase:
* [Trainings and Workshops](https://docs.google.com/document/d/1l5JmlkTGMUvsbI9CyShysICeAGw55GkTsw_6P4558zI/edit?usp=drive_link)

Trainings provided to partners included:
* [Introduction to OSM](https://docs.google.com/presentation/d/1QneNbichunhVjyN4RPRyPuYV3Q7QMJctp50_90FpMpc/edit#slide=id.g526e73601c_0_1163)
* [Mapping with JOSM](https://docs.google.com/presentation/d/1nLs1JA-nlmqWA2vIr9ZsoDcg8wjsoc5nv1QMK9GT8KI/edit?usp=sharing)
* [Mapping with ID editor](https://docs.google.com/presentation/d/1sbTZp5B7sQlEM-RzDU-33JlJnUUUGDkeOchhC6srK20/edit#slide=id.g51d3d58777_0_0)
* [Mobile Data Collection Tools](https://docs.google.com/document/d/1sTU36IIhwzDAdB62pmt4WGE2ZRdB3Ruv2XC5MEYHBZI/edit)
* [Introduction to QGIS](https://docs.google.com/presentation/d/1EA63n-jEjgEYVGzfdW8dispZpqvkbGDYx7ZtuayxZnQ/edit?usp=sharing)
* [Downloading data from OSM (Hot Export Tool and Quick OSM)](https://docs.google.com/presentation/d/1RyHYVPZU5d4xJ1cpWga4QRdfohpEs-t9ylJ_HTJ7wm8/edit?usp=sharing)

#### 3. Data collection
Data collection activities were consultative and participatory in nature, where data collectors were chosen from the local communities that we were interested in generating data to support the refugee response. Data collectors used their personal smartphones and those who didn’t have proper functioning smartphones were equipped with one by HOT. OpenDatakit was the main data collection tool/application used and 6 unique forms - incl. Health, Education, Water, Sanitation - would be implemented by surveyors and used for mapping in every village visited both in and around the refugee settlements.

Steps used in this phase:
* [Choosing a Data Collection Application: OpenDataKit (ODK)](https://docs.google.com/document/d/1sTU36IIhwzDAdB62pmt4WGE2ZRdB3Ruv2XC5MEYHBZI/edit)
* [Overview ODK Collect](https://docs.google.com/document/d/1BcQUE1__qNK6DD0Uq8lcvwDLR3T9HXvljOE1l-LeMlk/edit)
* [Using ODK Collect](https://docs.google.com/document/d/1lVMcZ6wvcht1IYvEY7j6iYOgi7idLzX0ODZjp403qJ8/edit)

#### 4. Data Storage and Monitoring
The data from the field was stored on the online UNHCR kobo server space. This allowed for different UNHCR and OPM implementing partners to access the data easily and effectively. The data was uploaded by the field data collector at the end of each working day. Uploading ODK requires as low as a 2G connection to send the files to the server. The surveyors were always provided with at least 50 MB of data to accomplish such tasks. The Kobo server was also used as a monitoring tool to determine the number of data points collected and quickly assess any data quality gaps in the field.

Steps used in this phase:
* [Data Collection Servers](https://hotosm.github.io/toolbox/pages/data-collection-and-field-mapping/3.4-data-collection-servers/)

#### 5. Data Cleaning and Analysis
After storing the data on Kobo, the data would be downloaded then cleaned and uploaded using JOSM.
Steps used in this phase:
* [Data Cleaning with JOSM](https://docs.google.com/document/d/1W5a8I3B-YCd2HrZKd23yFHxMgqQ7tnpjoZWG8E0Y1-w/edit)

#### 6. Data Visualization
For this project, HOT used a number of methods to visualize data; from using QGIS to create static maps and atlases to using tools such as Overpass turbo, Umap and Mapbox Studio to create dynamic & informative map products. The types of visualizations were mainly developed included distance matrices, resource gap identifiers, location and navigation maps and proximity indicator maps.

Steps used in this phase:
* [Downloading data with HOT Export Tool](https://docs.google.com/document/d/1wn31VVQ2eNZQuOst2tyxlDvAy4bbSc2A_MOtxgE-scw/edit)
* [Creating Maps and Atlases in QGIS](https://docs.google.com/document/d/1rZ41GBEFQabyJi44SoGz_S7r6YYcrYvPUGqccvtvT1U/edit)
* [Web & Interactive Maps](https://docs.google.com/document/d/1i03eAxiemHSou89TBApcTDekTILrJKnHv3WyozDP834/edit)