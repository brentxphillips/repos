# Data Partners Program

The **Data Partners Program** aims to collect aid activity information from a targetted number of humanitarian organizations that's critically needed to train artificial intelligent applications how to answer queries made by humanitarian actors.

The program will concentrate on shepherding participating organizations through the process of reporting specific aid activities in compliance with the **IATI Standard** to fill gaps in an informational matrix that machine applications can traverse covering a wide range of operational scenarios.

## Problem

Humanitarian organizations are coalescing around using centralized repositories like the **Humanitarian Data Exchange** and reporting frameworks like **IATI** to openly share detailed information, creating machine accessible information sources artificial intelligent applications can plug into and use to answer complex queries posed by humanitarian actors.

The **IATI Standard** contains over 500 elements and attributes which humanitarian organizations can use to comprehensively detail aid activities, operational time frames, stakeholder relationships, transactions, results and etc. These fields are vitally important to artificial intelligent applications. They create digital **nodes** and **relationships** artificial intelligent applications can traverse, giving them the ability to break down and process raw information and queries.

Although IATI usage is growing exponentially, in part due to reporting mandates issued by many government development agencies and United Nations led efforts to improve open data sharing, organizations are collectively failing to comprehensively use IATI’s full compliment of fields or to add HXL (Humanitarian Exchange Language) hashtags to information stored in the Humanitarian Data Exchange to the degree needed to unlock machine data processing capabilities able to bring data usage to the next-generation.

On an engineering level, lack of adequate reporting and tagging makes it difficult to use files to train, test and improve artificial intelligent applications and in turn incentive's greater reporting, stifling critical engineering work on algorithms and machine learning models.

## Program

The program particulaly aims to identify gaps in IATI data where more information is needed to train artificial intelligent applications. Based on gap mapping, Humanitarian AI members will contact targetted organizations potenitally able to fill these gaps and work with them to identify aid activities to report via IATI, wither or not the files are actually published.

As needed members will interview staff from organizations, ollect information and generate IATI compliant XML for organizations.

### Data Gaps

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
### Query Testing

text
```txt
"Who is providing aid to women in Afghanistan?"
```

text

## Priorities

Initially the program will concentrate on live crises then expand to less urgent crises by scale and to development activities and combined activities. It will use clusters, IATI fields and OECD-DAC code categories primarily to generate a matrix.

## Get Involved

Currently, the program is reachng out to organizations involved in aid activities responding to the crises in and around Syria and Yemen. Particularly we're initially interested in status tracking, benefiieries, and descriptions of activities. Lear more [here]() if your organizations would like to get involved.

## Work text

This project aims to reach out to targeted humanitarian organizations and systematically collect information on key activities, inreasing information acessible to train and test artificial intelligent appliations.

Participating organizations will be shepherded through the process of reporting some number of their activities properly and using a wide variety of IATI information fields
