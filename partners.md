# Data Partners Program

The Data Partners program was setup to **identify** and **fill** gaps in primarily IATI data where more information on aid activities is needed to **train** artificial intelligent applications how to use data sourced from IATI to **answer** complex queries posed by humanitarian actors.

Humanitarian AI members will **analyze** usage of IATI information fields, **map** data gaps and **recruit** humanitarian organizations to help fill gaps applicable to the program. Members will specifically work with organizations to **collect** information on targeted aid activities, **convert** the information into machine readable XML code and then help organizations **publish** the information to IATI.

In connection with the program, members will also source queries from participants to use for training and testing and make data collected and queries availible to members and others for study... and ask to examine database fields in house, establish IATI point of contact for participant visability.

## Program Focus

The program is specifically interested in data streaming through IATI, an open data sharing framework setup by the humanitarian community through the **International Aid Transparency Initiative**. The framework is used today by over 1000 organizations, supported by the United Nations and mandated by many government development agencies.

Through concerted efforts standardizing and improving open data sharing across the humanitarian community, IATI and the **Humanitarian Data Exchange** (HDX) have emerged to become the humanitarian community’s two principle sources of detailed information on humanitarian aid activities openly accessible to machine applications

IATI’s hundreds of standardized information fields are particularly important to the development and future of humanitarian AI applications, they create a matrix of cross-connecting nodes and relationships artificial intelligent applications and popular digital assistants like Alexa, Cortana, Google and Siri can traverse to collect information to answer complex queries and return information of high operational relevance to humanitarian actors.

Unlike HDX, data uniformely coded, structured and tagged, making ...

### Data Detail

Reporting to IATI involves converting information on aid activities into machine readable XML code and sharing file metadata with the IATI registry, making the information locatable and aggregatable.

In many cases however organizations fail to comprehensively use IATI's information fields..., leaving little data (variation and abundance) in some fields on a matrix level making it difficulet to adiquaty train and test applications. The program aims to help organization publish information on aid activities in greater detail.

For example, IATI's activity "Description" field is widely used, (alough some organizations add little narrative to the field and others expansive project descriptions (sometimes elaborating in place of filling other fields)), however fiew organizations use IATI descruption sub-categories to clearly state who the activities aim to benefit or what they aim to acomplish in terms of objectives. [Learn more]().

Likewise, sector (OECD-DAC purpose codes) and status codes (planned, implemented, completed) are often neglected for example. Learn more, learn more

Reporting using category 1 alone

```xml
<description type="1">
  <narrative>Title</narrative>
</description>
```
The project aims to see these otehr fields used, sufficently to train and test applications

```xml
<description type="1">
  <narrative>Title</narrative>
</description>
<description type="3">
  <narrative>Target group benefitting from the activity</narrative>
</description>
```

propper tagging clearifies, creates pathways and aids inferences predictions of other fields...

In addition to collecting data the program will experiment with collecting non-standard data for use to test additional processing capabiliites

* Needs Assessments
* Activity Financing
* Medical supply data
* Results (water quality for example)
* Geo-spatial data (for example a shape file of a facility damanged or under repair

### Data Variability

In addition to seeing more fields used and properly, the program aims to collect from organizations enough similar and contrasting data to ensure multiple data in each field and variation in queries.

For example who is targetting children, insure simularities and variations in activities, and enough to use half of data for training and the other for testing for example.

Location, target, status

```xml
<description type="1">
  <narrative>Title</narrative>
</description>
<description type="3">
  <narrative>Target group benefitting from the activity</narrative>
</description>
```

Location, target, status

```xml
<description type="1">
  <narrative>Title</narrative>
</description>
<description type="3">
  <narrative>Target group benefitting from the activity</narrative>
</description>
```

Location, target, status

```xml
<description type="1">
  <narrative>Title</narrative>
</description>
<description type="3">
  <narrative>Target group benefitting from the activity</narrative>
</description>
```

### Queries

The program aims to generate data for training and testing using simple to complex queries and generate queries from Data Program participants for use.

The point of collecting data is to be able to generate data developers can use to test questions and have sufficient data to be able to have answers to train and potential answers to test. While generating queries will give the program queries to execute against the data.

Training question

```txt
Q: Where are projects targetting children? 
```

Testing Question

```txt
Q: List planned projects targetting children?
```

Query processing using XML fields

```XML
list <status>projects targetting <target-group>
```

The point of algorithms and machine learning models is to process questions, identify intents, use elements to generate queries and retunr info

### Data Collection Priorities

Next thr program aims to begin my looking at live crises and then move to other thematics. As such in the short term the project will look at crisis areas like Syria and Yemen, current and planned activities and activities in cluster areas.

It will also use the opportunity to consider data privacy and security and ways AI applications can traverse fields while the data is hidden, a new technological capability.

XML wise

* Decription fields
* Local level Partners
* Status codes
* Sector codes
* Glide numbers
* Sub-activities with narratives
* Geo location data
* Contact
