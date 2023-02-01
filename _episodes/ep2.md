---
title: Metadata
teaching: 40
exercises: 10
questions:
- What is metadata?
- What information could we add to better understand the data contained in the dataset?
- Where to find information about metadata community standards?
objectives:
- Define metadata and its various types
- Recall the community/domain standards and how to apply them to data and metadata
keypoints:
- FAIR principle adressed (I1) - (Meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation
- FAIR principle adressed (I3) - (Meta)data include qualified references to other (meta)data
- FAIR principle adressed (F2) - Data are described with rich metadata
- FAIR principle adressed (A2) - Metadata are accessible, even when the data are no longer available
- FAIR principle adressed (R1.3) -  (Meta)data meet domain-relevant community standards
--- 
### What is metadata?
Metadata refers to the information that describes your data.
In other words, imagine you have an Excel spreadsheet containing data values for an assay. You would use column headings to assign meaning and context. These column headings are your metadata, explaining the data values in each cell. In addition, any documentation or explanation of the accompanying excel file is also considered metadata.
Let's look at Figure 1, showcasing a spreadsheet containing data for a clinical assay. In this example, the data are the patient ID, disease type, and heart rate values. The metadata, the column headings, describe that those values correspond to the patient ID, disease type, and heart rate, as well as the name of the cohort and the contact e-mail.
![Figure 1: A fabricated example of a clinical assay that includes patient ID, disease type and heart rate. The image showcases which part of this assay represents the metadata](https://i.imgur.com/ArqBsRG.png)
### What information could we add to better understand the data contained in the dataset?
We could add additional metadata to indicate data provenance, i.e. data origin, what happens to it or where it moves over time.
In this case, we should add more information about the cohort name. "Human Welsh Cohort" does not tell us much about the data if compared to other Welsh cohorts. Instead, we could include the following:
- A unique ID or detailed title for the cohort
- A project URL describing its origin and composition
At first glance, the column headings seem descriptive. However, taking a closer look, we can see that the "disease type" column captures both the disease type and stage, which can cause ambiguity:
- In row 3, it is unclear whether the disease is diabetes mellitus or insipidus
- In row 4, it is unclear whether the type of diabetes mellitus is 1 or 2
- There is an empty space in the final row. It is unclear whether this is due to a lack of information or that the patient does not have diabetes
Instead, we can create two separate columns: one for disease type and one for the stage (see Figure 2).
![Figure 2: An reviewed version of the fabricated example in Figure 1. Metadata has been updated to reduce ambiguity and offer further details.](https://i.imgur.com/hujGaWw.png)
### The importance of metadata
Metadata is small and can be easily maintained not only in the database but in personal computers. The maintenance of datasets in a public database comes at a cost. It can be minimised when maintaining the metadata instead.
In addition, metadata is also highly efficient for sharing sensitive data. The details available are those provided in the metadata, such contact details of the researchers, how to get the data and how it was generated.
### Types of metadata
We've seen that metadata can describe various aspects of your dataset. It can be classified into three types:
- **Descriptive Metadata**: defines the characteristics of the dataset
- **Structural Metadata**: explains how the dataset is generated and structured internally, known as **data provenance**.
- **Administrative metadata**: describes data owner(s), data contributors and funding sources.
Let's look at an example using microarray data from the ArrayExpress database (Figure 3) to locate the different types of metadata that we have defined.
[![Figure 3: A snapshot of a real microarray dataset on the ArrayExpress database](https://i.imgur.com/igdEmOu.png)](https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-7933)
We can observe:
- **Administrative metadata**: authors and organisations underneath the dataset title, and the information in "Publication"
- **Descriptive metadata**: "Description" section that sumarises the information contained in the dataset
- **Structural Metadata**: "Protocols", "Samples" and "Assay and Data" sections describing the structure of the dataset and how it was generated
### Following community standards
Each data type has its own community that develops guidelines to describe data appropriately and consistently. Make sure to follow the community standards when describing your data.
Following standards will also make your data more reliable for other researchers, allowing it to be reused across multiple platforms. If you decide to use other guidelines outside your community, document them. 
 
> ## Exercise 1: Finidng community standards for your data
> [RDMkit](https://rdmkit.elixir-europe.org/) is an open-source, community-driven site that guides life scientists to manage their research data better. >RDMKit provides comprehensive information about [RDM life cycle](https://rdmkit.elixir-europe.org/data_life_cycle), [resources relevant to RDM specific roles](https://rdmkit.elixir-europe.org/your_role), [guidlines and solutions for common data managment tasks](https://rdmkit.elixir-europe.org/your_tasks), [RDM tools ecosystem](https://rdmkit.elixir-europe.org/tool_assembly), [national](https://rdmkit.elixir-europe.org/national_resources) and [RDM training resoures](https://rdmkit.elixir-europe.org/all_training_resources). 
> 
>  In addition information about research domain or community can be found inside the domain tab where you can navigate though multiple available sudomains with the side navigation panel. For example you can extract the following information for [Bioimaging data](https://rdmkit.elixir-europe.org/bioimaging_data) community standards.
>  
>  1. What is bioimage data and metadata?
>  2. Standards of bioimage research data management
>  3. Bioimage data collection
>  4. Data publication and archiving
> ![A demonstration of how to navigate the RDMkit to find Bioimage metadata information](https://i.imgur.com/kXl80Rm.gif)
>   
>  Please use RDMkit to find information and discuss, what should be considered and what solutions are avaliable for storing and sharing sturctural predictions? Think about one other example of RDM domain/community standards, try to find information about it in **RDMkit**?
>> ## Solution
>> Extract this information from RDMkit >> Your domain >> [Structural Bioinformatics](https://rdmkit.elixir-europe.org/structural_bioinformatics)
>>
>   {: .solution}
>
{: .challenge}


