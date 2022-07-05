---
title: What is FAIR?
teaching: 40
exercise: 20
questions:
- Explaining the acronym (the F .. the A .. the I .. the R ..)
- Where does FAIR come from?
- What is FAIRification/Fairness of data?
objectives:
- Illustrate the main concept of FAIR
keypoints:
- What is FAIR?
- What is the difference between FAIRness and FAIRification of data?
- FAIR principles were gradually formed by different sources
- Most data can be FAIRified 
- Metadata is key component in the process of FAIRification
---

With the current expansion of biomedical research data, there was an urgent need to develop guidelines to ensure proper data management. That's why FAIR principles were published to help researchers properly share, reuse, and manage their data. 
Also bear in mind that FAIR principles are not only applied to data but also to software, and workflows. They are easily adapted to different data types and more resources are now available on how to apply FAIR principles to different types of data, algorithms, tools, workflows, and software. 
In this lesson, we will explain FAIR principles and how FAIR principles will help you properly manage your data.

## What is FAIR?

> ## These principles were published in 
> Wilkinson, M., Dumontier, M., Aalbersberg, I. et al. The FAIR Guiding Principles for scientific data management and stewardship. Sci Data 3, 160018 (2016). 
> The FAIR publication of 2016 makes reference to the FAIR principles which are:
> - F stands for Findable 
> - A stands for Accessible 
> - I stands for Interoperable 
> - R stands for Reusable 
>
![FAIR principles https://www.scibite.com/solutions/enterprise-fair-data-mdm/](../fig/FAIR.png)
https://www.scibite.com/solutions/enterprise-fair-data-mdm/
{: .callout}

To apply FAIR to your data, each principle has set of specific requirements that guide researchers through the process of FAIRification of their data to make their data Findable, Accessible, Interoperable, Reusable.
### F in FAIR 
F is the first letter of FAIR, it indiactes findability. To make your data findable, the data should fulfil 4 principles. In this RDMBites, we will explain what are these principles

> ## Watch this RDMBites to know what are these Fs 
> The powerpoint will be converted to video, please add your comments directly in the powerpint. Your name will be added as a reviewer
> (https://docs.google.com/presentation/d/1RwEVZC390wtxPQM-zQsBDT7IbNVq0wpZ/edit#slide=id.p2)
> 
{: .callout}

> ## To recap
> To make your data **Findable**
> - F1: Metadata and data are assigned globally unique and persistent identifiers**
> - F2: Data are described with rich metadata
> - F3: Metadata clearly and explicitly include the identifier of the data they describe 
> - F4: Metadata and data are registered or indexed in a searchable resource
{: .keypoints}

> ## Exercise
> After watching this videos, answer the following questions:
> - How many of these principles have you applied to your data?
> - What is metadata?
> - What are persistant identifiers?
> **Keep this in mind, we will need this for our next section on FAIRness of data**
> 
{: .discussion}

### A in FAIR
A stands for accessibility to the data, this principle allows machine and human readability of your data. However, your data is still secure. As mentioned in Landi et al. **The “A” of FAIR – As Open as Possible, as Closed as Necessary** 

**To make your data comply with A, you need to apply two main principles**

> ## Watch this RDMBites to know what are these principles
>  The powerpoint will be converted to video, please add your comments directly in the powerpint. Your name will be added as a reviewer 
>  [RDMBites](https://docs.google.com/presentation/d/1Ac0qF1IKIVH2kjGmXFbyH0WAqI2vXqUB/edit#slide=id.p1)
> 
{: .callout}

> ## To recap
> To make your data **Accessible**
>- A1: (Meta)data are retrievable by their identifier using a standardized communication protocol
>- A1.1: The protocol is open, free, and universally implementable
>- A1.2: The protocol allows for an authentication and authorization where necessary
>- A2: Metadata should be accessible even when the data is no longer available
>
{: .keypoints}

> ## Exercise
> After watching this videos, answer the following questions:
> - How many of these principles have you applied to your data?
> - What is protocol? Can you give an example?
> **Keep this in mind, we will need this for our next section on FAIRness of data**
> 
{: .discussion}

### I in FAIR
I is related to technical interoperability. To understand more what this means, watch our RDMBites on I in FAIR

> ## Watch this video to know what is I in FAIR through different examples
>  The powerpoint will be converted to video, please add your comments directly in the powerpint. Your name will be added as a reviewer
> [RDMBites](https://docs.google.com/presentation/d/15jRnCLWnjk-3klwRJBc5cQomfqu8BRdv/edit#slide=id.p2)
> 
{: .callout}

> ## To recap
> To make your data **Interoperable**
>-	I1: (Meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation
>-	I2: (Meta)data use vocabularies that follow the FAIR principles
>-	I3: (Meta)data include qualified references to other (meta)data
>
{: .keypoints}

> ## Exercise
> After watching this videos, answer the following questions:
> - How many of these principles have you applied to your data?
> - What are vocabularies? Can you give an example?
> **Keep this in mind, we will need this for our next section on FAIRness of data**
> 
{: .discussion}

### R in FAIR
R indicates reusability and it is the last principle of FAIR. 

It included one main category that describes the importance of the use of well-descriptive metadata
- R1: (Meta)data are richly described with a plurality of accurate and relevant attributes

> ## Watch this video to know what is R in FAIR through different examples
>  The powerpoint will be converted to video, please add your comments directly in the powerpint. Your name will be added as a reviewer
> [RDMBites](https://docs.google.com/presentation/d/1uMyUGVH6mm48iDm6jNoBnAuqF3sGiTeO/edit?usp=sharing&ouid=115915105600833888129&rtpof=true&sd=true)
> 
> {: .callout}

> ## To recap
> To make your data **Reusable**
>-	R1: (Meta)data are richly described with a plurality of accurate and relevant attributes
>
{: .keypoints}

> ## Exercise
> After watching these videos, how many of these principles have you applied to your data?
> what are attributes in your field?
>
{: .discussion}

## What is FAIRification of data?
It is a process of applying FAIR to your data. Your data will be Findable, Accessible, Interoperable, and Reusable.

Each community has its rules for FAIRification of data, here is a summary of the process provided by [GO-FAIR](https://www.go-fair.org/fair-principles/fairification-process/)
![[FAIRification of data](../fig/ep1fair.png)
## What is FAIRness of data
When you apply FAIR to your data, you can apply one or more of the principles. FAIRness describes how much your data fulfilled FAIR principles. Usually, you can use one of the assessment tools that will help you know and guide you on how to make your data more FAIR. This will be discussed later in detail.

> ## For further reading
>
> - https://www.go-fair.org/fair-principles/
> - https://faircookbook.elixir-europe.org/content/home.html
> - https://www.nature.com/articles/sdata201618
> 
{: .callout}
___
## Benefits of FAIRness
**Reusability of data assets**
FAIRification of your data allows short- and long-term use of these data. Furthermore, the availability of these data allowed the implementation and testing of different predictive models. 
**Cost savings**
FAIR data saves not only time but also money spent on finding relevant data. Bear in mind, that it also helps researchers avoid duplicating experiments which will lower the costs and accelerate the research process. 
**Time efficiency**
FAIRification of your data will allow machine and human readability of your data. A and I of FAIR create a single point of access that saves time for researchers using and accessing your data. Machine readability ensures that research engines can find your data which will increase the visibility of your data. 
*In addition to the aforementioned benefits, FAIR data allow reproducibility of research results because data are published with metadata and an analysis pipeline.*

## Costs of not FAIRifying your data
Based on a report by the EU, not complying with FAIR principles have a detrimental effect at many levels: Research activities, Collaboration, and innovation. At each step of the data life cycle, there is a cost for not FAIRifying your data. 

> ## To know more about costs of not FAIRifying your data, Watch our RDMBites on costs of not FAIRifying your data
> (Youtube link of the RDMbites)
> []
{: .callout}


> ## In this research paper, the authors assessed the cost/benefit relationship of the FAIRification process
> Ebtisam Alharbi, Rigina Skeva, Nick Juty, Caroline Jay, Carole Goble; Exploring the Current Practices, Costs and Benefits of FAIR Implementation in Pharmaceutical > Research and Development: A Qualitative Interview Study. Data Intelligence 2021; 3 (4): 507–527. doi: https://doi.org/10.1162/dint_a_00109
> 
{: .keypoints}


## What are misunderstandings of FAIR?

![FAIR data do not have to be open](../fig/Openfair.PNG)

> ## Open data
> - The Open Data Handbook defined open data as:
> <br>“Open data is data that can be freely used, reused and redistributed by anyone – subject only, at most, to the requirement to attribute and sharealike.”
> This video explains the concept of open data, open science and FAIR principles
> <iframe width="560" height="315" src="https://www.youtube.com/embed/mVCDkhxxUgg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; 
> clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
> 
{: .keypoints}

There is a misconception that aligning with FAIR principles means your data has to be open. There are many examples where data can be FAIR but not open like sensitive data and any data subject to intellectual property. These data can still be FAIR and have controlled access. That's why the research community uses the phrase **“open as possible, closed as necessary”**
However, the research community strives to make the data as open as possible to allow the reproducibility of research results. There are a lot of methods that can be used to make your data FAIR and open. Different anonymization and controlled access techniques can be used to ensure the FAIRness of your data and yet your data is secure. These will be discussed in more detail in another lesson

> ## References For further reading
>
> - https://www.go-fair.org/fair-principles/
> - https://faircookbook.elixir-europe.org/content/home.html
> - https://www.nature.com/articles/sdata201618
> 
{: .callout}
___
## Where does FAIR come from?
### The history of FAIR
- The first paper discussing related context dates only to 2007 (see link 10.5281/ZENODO.1285272). G20 Hangzhou summit in 2016 next approved applying of FAIR principles in research. 
- The following year the Netherlands, France and Germany established GO FAIR International Support and Coordination Office to support the scheme. The same year a study supporting FAIRIfication of data spread the awareness among the researchers but at the same time added to the confusion of applying the concept in differing fields that led to inconsistent interpretations. 
- In 2019 CARE Principles for Indigenous Data Governance was released by the Global Indigenous Data Alliance aiming to complement and expand the guidelines with historical and structural contexts. The CARE principles for Indigenous Data Governance derived from the International Data Week and Research Data Alliance Plenary event in November 2018 Gaborone, Botswana. The related principles included Collective benefit, Authority to control, Responsibility and Ethics. 
- This resulted in nine universities endorsing Sorbonne declaration on research data rights in January 2020 that advocated for FAIR data commitment and pressing the global governments for support in advising its use. In April this year Nature journal published an article asking for implementation of FAIR principles in material sciences.

### What data can be FAIRyfied?
Most data can be FAIRyfied. The ultimate goal of FAIR principles is that humans as well as machines can share and find other’s data by way of safe and quick access, interoperability and reuse. Any data from tools, workflows or algorithms that lead from input, output and objects can be FAIRyfied.
> # Example
> Metadata is essential in the process of FAIRification because it is the key in finding, managing and reusing the rest of the document or project. 
{: .callout}

Metadata will describe the lead researcher and confirm why, when and where the data was collected hence how the study should be referenced and cited. Because the guiding principles of FAIR are based on the use of machine-actionable metadata for finding, accessing, interoperating, combining and reusing data with little or no human effort, the metadata should have a detailed level of FAIRness to allow easy interpretation and association with other research data. Also, depending on specific areas of research, the researchers must keep in mind preparing the data in parallel with future FAIRification. This is because digital technologies and related supporting services for sharing and managing data to include collection software and data repositories are progressing fast. Hence attention must be paid to digital science techniques and methods in individual lines of research to assure key information is captured and ready before FAIRification.

> # Further reading
> For more info about origins of FAIR see this link: https://zenodo.org/record/1285272#.Yp9oQHbMKUk
> For further information about selecting your data, services and repositories for FAIRification see this link: [https://zenodo.org/record/6345114#.YqDAsXbMKUk]
{: .callout}
___





