---
title: FAIR guiding principles
teaching: 20
exercises: 20
questions:
- What is FAIR? 
- Why is FAIR important?
- Pillars of FAIR
objectives:
- Identify the importance of FAIR principles for the open science
- Explain The difference between FAIR and open data
- Contextualise the main principles of FAIR in the light of the main pillars (Identifiers, access, metadata, and registration)
keypoints:
- FAIR stands for Findable, Accessible, Interoperable and Reusable
- What is meant by FAIRness and FAIRification of data?
- Metadata, identifiers, registration and access are key components in the process of FAIRification
- The FAIR Principles differ from Open data because they permit the owner of the data to control access, although as part of this they are required to define methods and instances where data could be accessed
--- 
##### What is FAIR?
FAIR is an acronym encompassing four foundational principles: Findability, Accessibility, Interoperability, and Reusability. The FAIR Principles aim to help researchers to share, reuse and manage their data. (Figure 1). FAIR is not limited to the Life Sciences and spans all research disciplines. The FAIR principles are not limited to data and can be applied to services, software, training and data workflows. 

![Figure 1. Summary of FAIR principles](../fig/fairifying2.png)

Each foundational principle is can be further divided into subcomponents, thereby specifying much more defined targets that can be actioned, towards improving compliance towards the 'F', 'A', 'I' or 'R' principles.  

In this course, we will contexualize these guiding principles by going through the data life cycle, helping participants to understand **WHY and HOW to FAIR?** rather than going through each principles. You can find information about guiding principles covered in each episode, below **Key Points** section.

More comprehensive information for each guiding principle is available elsewhere, for example through [GO FAIR](https://www.go-fair.org/fair-principles/)


##### The history of FAIR and its use today
A report from the European Commission Expert Group on FAIR data describes the origins of FAIR and its development in 2014-2015, by a FORCE11 Working Group.  
FAIR is an acronym applicable to **any digital object**, and refers to its properties through the axes of Findability, Accessibility, Interoperability and Reusability. For FAIR data, the **digital object** we refer to is the data.  For a script or analysis workflow, the **digital object** would be “software”.
FAIR itself was then formalised and published in 2016 in 'FAIR Guiding Principles for scientific data management and stewardship'.

> ## Exercise1: Importance of FAIR
> Read page 11 of [the European Commission report](https://zenodo.org/record/1285272#.Yuk8O_HMIqt), under the 
> heading “Origins and definitions of FAIR”. What benefit did the FORCE11 Working Group see to coining the word FAIR? 
>> ## Solution
>> The report states: “a FORCE11 Working Group coined the FAIR data definition, latching onto an arresting and
>> rhetorically useful acronym. The wordplay with fairness, in the sense of equity and justice, has also been 
>> eloquent in communicating the idea that FAIR data serves the best interests of the research community and 
>> the advancement of science as a public enterprise that benefits society.”
> {: .solution}
{: .challenge}

> ## Exercise2: Digital objects 
> FAIR is not limited to data. From [the same report](https://zenodo.org/record/1285272#.Yuk8O_HMIqt), what
> other examples of “digital objects” can be made FAIR? 
>> ## Solution:
>> On page 15, the report states: “FAIR should be applied broadly to all objects (including metadata,
>> identifiers, software and data management plans (DMPs)) that are essential to the practice of research, and >> should inform metrics relating directly to these objects.” 
>> Also, on page 34 "FAIR data, code, workflows, models, and other digital research objects"”
>> The benefits of FAIR data in research are evidenced in two publications given below as further reading. 
>> See also RDMBites on [benefits of FAIR](https://docs.google.com/presentation/d/1xywEzC84RMor46moZVC-H-o3rJqEYYk1/edit#slide=id.p1)
> {: .solution}
{: .challenge}

**What is meant by FAIRification and FAIRness of data?**
**FAIRification** is the process of making your data more FAIR.  For example, adding specific metadata to your data and facilitating its sharing would improve its 'FAIRness'. We will take you through data FAIRification, in detail, later in this course.
The term **FAIRness** refers to the extent to which your data follows FAIR principles, and implies some implicit means of measuring this compliance.
A common misconception is to think that for data to be FAIR it needs to be open. FAIR data and Open data are different

##### Open science and FAIR

![Figure 2. FAIR data is not open data](../fig/Openfair.PNG)

The Open Data handbook defines Open data as **“data that can be freely used, reused and redistributed by anyone.”**
Hence, “Open data” refers to accessing the data without restriction.  Meanwhile, the phrase **“as open as possible, and as closed as necessary”** is used commonly when describing FAIR data. However, it is important to note that, while much FAIR data is open without restriction, FAIR compliance doesn’t require it to be open, but only specific if and what restrictions may exist on access. Hence, as long as the conditions of access are given, the data may be FAIR **and** not open.  The key is that there should be enough metadata to find the explicit conditions of access, either by human user or by machine.

> ## Exercise2: Open vs Fair
> Why would open data not be appropriate universally, across all communities and domains?
>> ## Solution:
>> Researches may produce and or work with sensitive 
>> data, or data itself may be subject to intellectual property.  Protecting sensitive data overrules mandating all research 
>> data should be open access.
>> Note though that in most cases, people following FAIR principles will likely be looking to share their data 
>> openly. It is also possible to handle some sensitive data release through anonymisation, or by putting in place controlled access measures for example through authentication.  
> {: .solution}
{: .challenge}

##### Pillars of FAIR
The description of the FAIR Principles refer to terms such as: machine readability, metadata, persistent identifiers, access, and data deposition. Before we start looking at real data examples that use the FAIR principles, we will start by explaining these first.

**Machine readability**
Machine readability refers to how data can be structured or formatted so that they can be processed or read computationally. Typically, this is accomplished through the use of strictly defined formats where the embedded data follows a known 'pattern', allowing the identification and processing of individual data items or values, in accordance with their context within the file format. For example, headings and rows in a spreadsheet define the context of the individual values within.  

> ## Exercise3: Machne readable digital objects
> Based on this definition, does it mean that any digital object is a machine readable?
>> ## Solution:
>> No, for any digital object to be machine readable, two key features should be fulfilled: structure and 
>> format. For instance, if you have a PDF with tabular data, this is not machine readable. Although the 
>> structure is tabular which can be read by computer, the PDF format is not read by machines, it is only 
>> human readable. Examples of machine readable formats are CSV and JSON.
> {: .solution}
{: .challenge}

Machine readability is considered one of the main goals of FAIR. Having your data machine readable, may facilitate its reuse and interoperability. 

Now, we will focus on some other key terms that play into the FAIR principles, and which will help you understand **WHY AND HOW TO FAIR**

In the next lessons, we explain the terms:
- Metadata
- Registration
- Access
- Persistent identifiers

