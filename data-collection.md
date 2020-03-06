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


### Data Collection

The program is specifically interested in information reported in compliance with **IATI**, an **open data sharing framework** and **reporting standard** used by over 1000 humanitarian organizations, donors and other stakeholders. Not only is IATI usage growing almost exponentially due in part to government development agency mandates and United Nations efforts encouraging greater open data sharing, . (defacto... power apps).

IATI requires organizations to convert information on aid activities into machine readable XML code, in house or via popular third party applications like AidStream and Microsoft's new Dynamics. The program is specifically interested in usage of IATI elements and attributes (fields and subfields)

(humanitarian community working concertedly to improve open data sharing. IATI is defacto standard for aid activity reporting, mandated by aid organizations. On and engineering level, it is a consistant sorce, the most widely used and growing exponentially. )

For example, IATI includes fields for four types of information describing aid activities: type 1 = General, type 2 = Objectives, type 3 = Target groups and Type 4 = Other information. Most organizations provide descriptions but fail to use any of the other types.

```xml
<description type="1">
  <narrative>General activity description</narrative>
</description>
```

The program will collect missing information, making the files more complete, giving an AI the ability to traverse information linking locations and different beneficiaries.

```xml
<description type="1">
  <narrative>Title</narrative>
</description>
<description type="3">
  <narrative>Target group benefitting from the activity</narrative>
</description>
```

The point of the project is to ensure that enough data is present to give AI applications data to traverse. Relative to the above example, enough data to cover different types of beneficiarires listed by shphere for example. Relative to the crisis in Syria the program will undertake to collect information on activities targetting these different groups in locations where these individuals are present, mainly: Syria, Jordan, Lebanon, Iraq and Turkey, thus the program will try to collect at least information on five separate activities targeting each segment in each of these countries.

### Query Testing


Here is an example question:

```txt
"Who is providing aid to women in Afghanistan?"
```

Using IATI data, an intelligent appliations will use field matching to answer the question. Although the AI might be able to deduce who the beneficiary is using general descriptive information, adding further information clearifying the beneficiary will improve reliability and enable developers to test and compare ability to make deductions from descriptive text.

```xml
<participating-org type="implementing">Oxfam</participating-org>
<description type="3"><narrative>Women</narrative><description>
<location>Afganistan</location>
```

Based on data processing traiing will enable AI to return a desired answer.

```txt
"Oxfam is providing aid to women in Afghanistan?"
```

Properly tagged information is critical to algorithms and outputs algorithms generate. 

## Get Involved

Although the program will contact organizations based on needs, organizations are welcome to contact the program and get involved. 
