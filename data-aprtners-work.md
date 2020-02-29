# Data Partners Program

The **Data Partners** program was setup to **identify** and attempt to **fill** gaps in primarily IATI data where more comprehensive information on aid activities is needed to train artificial intelligent applications how to use IATI data to answer complex queries posed by humanitarian actors.

Humanitarian AI community volunteers will **analyze** usage of IATI information fields and subfields, **map** data gaps and **recruit** humanitarian organizations to join the Data Partners program to get involved in helping fill relevant gaps. Volunteers will work with participating organizations to **collect** information on targeted aid activities, **convert** the information into machine readable XML and then help organizations **report** the information to IATI or where applicable help organizations update information previously reported to IATI.

## Program Scope

The program doesn't aim to comprehensively collect information on all humanitarian activities capable of conceivably being reported. It aims rather to collect enough information on targeted activities to make it easier for intelligent algorithms and machine learning models to traverse a cloned version of IATI’s entire dataset to learn how to process IATI data, answer queries and return information of high operational relevance to humanitarian actors.

Initially, the program will concentrate on targetting and filling gaps relevant to current and emerging humanitarian crises guided by research suggesting ways artificial intelligent applications can play roles in supporting activities responding to these crises. Later the program will broaden its scope and look more generally at humanitarian and development activities and activity clusters and subcategories for example as classified by [OECD-DAC]() purpose codes and connected activity codes developed by [AidData]().

### Example

IATI includes fields for four types of information describing aid activities: type 1 = General, type 2 = Objectives, type 3 = Target groups and Type 4 = Other information. Most organizations provide descriptions but fail to use any of the other types.

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





The program will however familiarize more organizations to IATI, help first-time publishers report activities and sensatize organizations to what information is needed by humanitarian actors and artificial intelligent appliations alike to help support crisis response and help to chanel more high quality informatio into IATI, making the dataset more relevant, useful to applications developers and incentivize reporting...

## IATI

**IATI** is both a **reporting standard**, with hundreds of information fields and subfields humanitarian organizations can use to report aid activities, operational time frames, stakeholder relationships, transactions, results and etc in granular detail and a **publishing framework** or conduit organizations can use to make the information openly accessible to machine applications. IATI is used today by over 1000 humanitarian organizations. It is mandated by many government development agencies and the United Nations is encouraging it’s wide spread use to help make humanitarian operations more transparent and data driven. To the tech community, IATI is a highly structured data soure…



## The Data Partners program was setup to identify and attempt to fill gaps in primarily IATI data where more detailed information is needed to train artificial intelligent applications and enable them to use IATI data to answer complex queries posed by humanitarian actors.

After mapping reporting gaps in existing data, categorized by priority based on (potential uses of data in the field) current humanitarian informational needs in the field and potential data uses, Humanitarian AI community members will systematically reach out to and attempt to work with targeted humanitarian organizations to see aid activity information filling these gaps published to IATI or else provided to members to add to an AI training dataset.



The Data Partners program was setup to identify and attempt to fill gaps in primarily IATI data where more comprehensive information on aid activities is needed to train artificial intelligent applications how to use IATI data to answer complex queries posed by humanitarian actors.

IATI is both a reporting standard, with hundreds of information fields and subfields humanitarian organizations can use to report aid activities, operational time frames, stakeholder relationships, transactions, results and etc in granular detail and a publishing framework  organizations can use to make the information openly accessible to machine applications. IATI is used today by over 1000 humanitarian organizations. It is mandated by many government development agencies and the United Nations is encouraging it’s wide spread use to help make humanitarian operations more transparent and data driven. To the tech community, IATI is a highly structured data soure…
Humanitarian AI community volunteers will analyze usage of IATI information fields and subfields, map data gaps and invite humanitarian organizations to join the Data Partners program to work with volunteers who will help them generate new IATI files or update existing files where needed to fill information gaps and make it easier for AI applications to traverse a cloned version of IATI’s entire dataset.
Initially the program will concentrate on addressing data gaps relevant to information needs prioritized by crisis needs today.




report new or additional information where needed to 

help fill-out an AI training dataset 

publish new IATI files or update existing files where needed to make it easier for AI applications to traverse IATI’s entire dataset

IATI is both a reporting standard, with over 500 elements and codes humanitarian organizations can use to report aid activities, operational time frames, stakeholder relationships, transactions, results and etc and a publishing conduit which organizations can use to make the information openly accessible to machine applications.


Humanitarian AI community volunteers  will map reporting gaps in IATI data then based on


The project will.
Organizations will be contacted and asked to join the study
Volunteers will… 


Initially, the program will concentrate on collecting live information on activities responding to current humanitarian crises. Then the program will shift towards filling data gaps associated with completed humanitarian activities, development activities and related other activities. 
