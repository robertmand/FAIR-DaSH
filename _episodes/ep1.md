---
title: What is FAIR?
teaching: 40
exercise: 20
questions:
- What is FAIR?
- What is meant by FAIRness and FAIRification of data?
- Where does FAIR come from?
- What is FAIRification/Fairness of data?
objectives:
- Illustrate FAIR background and main concepts
keypoints:
- So what is FAIR?
- What is meant by FAIRness and FAIRification of data?
- FAIR principles were gradually formed by different sources
- Most data can be FAIRified 
- Metadata is key component in the process of FAIRification
---

The FAIR principles were created to help researchers share, reuse, and manage their data.  A common layperson's interpretation of FAIR data is a dataset that can be:
> - discovered and downloaded by others; and
> - interpreted correctly through the provision of detailed descriptions about the data.

Descriptions of data (metadata) enables appropriate reuse.  This is similar to other aspects of published research, such as figures in papers, where titles and notes are given as well as descriptions of axes where data are plotted.  The provision of metadata is key to FAIR.

Note that FAIR is not limited to the Life Sciences and spans across all research disciplines.  Additionally, applying FAIR principles is not limited to data, but can be applied to the sharing and reuse of software and data workflow. 

## So, what is FAIR?

FAIR is an acronym summarising the 4 priniciples of data being: 
> - **F**indable
> - **A**ccessible
> - **I**nteroperable
> - **R**esuable

and is described in the Nature 2016 publication:

Wilkinson, M., Dumontier, M., Aalbersberg, I. et al. The FAIR Guiding Principles for scientific data management and stewardship. Sci Data 3, 160018 (2016). https://doi.org/10.1038/sdata.2016.18

<mark>NEEDS NEW DIAGRAM BELOW</mark>

![FAIR principles https://www.scibite.com/solutions/enterprise-fair-data-mdm/](../fig/FAIR.png)
https://www.scibite.com/solutions/enterprise-fair-data-mdm/
{: .callout}

To apply FAIR to your data (and metadata), each principle has a subset of specific requirements that can be used as a checklist.  Note, we put these into context later in this course when we take real datasets through FAIRification.  This checklist and further level of granularity is given in the 2016 publication as:

<mark>INSERT BOX2 of the publicatoin here from top of page 4</mark>

> ## For further details on the FAIR Guiding Principles, please see our RDMbites series
> (https://docs.google.com/presentation/d/1RwEVZC390wtxPQM-zQsBDT7IbNVq0wpZ/edit#slide=id.p2)
> (https://docs.google.com/presentation/d/1RwEVZC390wtxPQM-zQsBDT7IbNVq0wpZ/edit#slide=id.p2](https://docs.google.com/presentation/d/1Ac0qF1IKIVH2kjGmXFbyH0WAqI2vXqUB/edit#slide=id.p1))
> > [RDMBites](https://docs.google.com/presentation/d/1uMyUGVH6mm48iDm6jNoBnAuqF3sGiTeO/edit?usp=sharing&ouid=115915105600833888129&rtpof=true&sd=true)
> 
{: .callout}


## What is meant by FAIRness and FAIRification of data?

FAIRfication is the process of making your data FAIR.  Since giving a unique identifier to your data is part of the first **Findability** principle, by doing so you are performing part of the FAIRification process.

FAIRness refers to the extent to which your data follows FAIR principles.  One way to achive this is by using a FAIR checklist, and measuring the extent of FAIRness through simply counting the number principles applied.


Data communities often have their own rules and interpretations of FAIRification of data.  As an example, here is a summary of the process provided by [GO-FAIR](https://www.go-fair.org/fair-principles/fairification-process/)
![[FAIRification of data](../fig/ep1fair.png)


> ## Further reading and resources
>
> - FAIR guiding principles, FAIRification workflow and examples: https://www.go-fair.org/fair-principles/
> - FAIRification recipes in FAIRcookbook: https://faircookbook.elixir-europe.org/content/home.html
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





