---
title: What is FAIR?
teaching: 40
exercise: 20
questions:
- What is FAIR? What is the origin of the FAIR movement?
- Why is FAIR important?
- What is the difference between FAIRness and FAIRification of data?
objectives:
- Define metadata and its various types
- Recall the community standards and how to apply them to data and metadata
keypoints:
- FAIR stands for Findable, Accessible, Interoperable and Reusable
  -sss 
- What is meant by FAIRness and FAIRification of data?
- FAIR principles were gradually formed by different sources
- Most data can be FAIRified 
- Metadata is key component in the process of FAIRification
---
 
### What is metadata?
Metadata refers to the information that describes your data.
In other words, imagine you have an Excel spreadsheet containing data values for an assay. You would use column headings to assign meaning and context. These column headings are your metadata, explaining the data values in each cell. In addition, any documentation or explanation of the accompanying excel file is also considered metadata.
Let's look at Figure 1, showcasing a spreadsheet containing data for a clinical assay. In this example, the data are the patient ID, disease type, and heart rate values. The metadata, the column headings, describe that those values correspond to the patient ID, disease type, and heart rate, as well as the name of the cohort and the contact e-mail.
![Figure 1: A fabricated example of a clinical assay that includes patient ID, disease type and heart rate. The image showcases which part of this assay represents the metadata](https://i.imgur.com/ldWrS5L.png)

**What information could we add to better understand the data contained in the dataset?**
We could add additional metadata to indicate data provenance, i.e. data origin, what happens to it or where it moves over time.
In this case, we should add more information about the cohort name. "Human Welsh Cohort" does not tell us much about the data if compared to other Welsh cohorts. Instead, we could include the following:
- A unique ID or detailed title for the cohort
- A project URL describing its origin and composition

At first glance, the column headings seem descriptive. However, taking a closer look, we can see that the "disease type" column captures both the disease type and stage, which can cause ambiguity:
- In row 3, it is unclear whether the disease is diabetes mellitus or insipidus
- In row 4, it is unclear whether the type of diabetes mellitus is 1 or 2
- There is an empty space in the final row. It is unclear whether this is due to a lack of information or that the patient does not have diabetes
Instead, we can create two separate columns: one for disease type and one for the stage (see Figure 2).
![Figure 2: An reviewed version of the fabricated example in Figure 1. Metadata has been updated to reduce ambiguity and offer further details.](https://i.imgur.com/d94Xckq.png)

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
 
> ## Exercise 1. Where to find your community standards
> RDMkit is an open-source, community-driven site that guides life scientists to manage their research data better. This resource can be your perfect starting point for finding other tools, training materials and any recommended resources related to RDM in the life sciences.
>
> Can you find the bioimage community standards in the RDMkit?
> [Start here>>](https://rdmkit.elixir-europe.org/)
>
> > ## Solution
> >
> > RDMkit covers various research data management topics and life sciences fields. You can find the community standards under the "Your domain" tab.
> >
> > Inside the domain tab, you can navigate the multiple available domains with the side navigation pane. At the top, you will find "Bioimage data" tab. This page includes the following information on the bioimage community standards:
> > 1. What is bioimage data and metadata?
> > 2. Standards of bioimage research data management
> > 3. Bioimage data collection
> > 4. Data publication and archiving
> > ![A demonstration of how to navigate the RDMkit to find Bioimage metadata information](https://i.imgur.com/kXl80Rm.gif)
> {: .solution}
>
{: .challenge}
### Recommended reading
If you want to learn more about how to describe your data with metadata visit the [RDMkit page on how to manage metadata](https://rdmkit.elixir-europe.org/metadata_management.html).

## FAIR principles covered in this episode
- **I1**  (meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation 
- **I3**  (meta)data include qualified references to other (meta)data 
- **A2** Metadata are accessible, even when the data are no longer available


