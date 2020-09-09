---
layout: page
title: Schedule
menu: true
order: 2
---


All course delivery for Fall 2020 will be online via this public facing website.  New class content will be posted on a weekly basis throughout the quarter.  Clicking on the topics below will take you to corresponding video lectures, hands-on "lab sessions" supporting walk-through screencasts, required reading material and homework assignments.

<br>

| \# | Week         | Topics for Fall 2020                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| :-: | :-----------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 0  | 10/02/20 | [**Getting Oriented**](#0) <br> Course introduction, Learning goals & expectations, Meet the instructional team. Setup your computer with required software.                                                                                                                                               |
| 1  | 10/05/20 | [**Welcome to Bioinformatics**](#1) <br> Biology is an information science, History of Bioinformatics, Types of data, Application areas and introduction to upcoming course segments, Hands on with major Bioinformatics databases and key online NCBI and EBI resources                                                                                                                                               |
| 2  | 10/12/20 | [**Sequence alignment fundamentals, algorithms and applications**](#2) <br> Homology, Sequence similarity, Local and global alignment, classic Needleman-Wunsch, Smith-Waterman and BLAST heuristic approaches, Hands on with dot plots, Needleman-Wunsch and BLAST algorithms highlighting their utility and limitations                                                                                                                                                 |
| *  | 10/19/20  | **Project:** [**Find a gene project assignment**](#11) <br> (Part 1) Principles of database searching, due in 3 weeks. (Part 2) Sequence analysis, structure analysis and general data analysis with R due at the end of the quarter.                                                                                                                                                                                                 |
| 3  | 10/19/20  | [**Bioinformatics data analysis with R**](#3) <br> Why do we use R for bioinformatics? R language basics and the RStudio IDE, Major R data structures and functions, Using R interactively from the RStudio console                                                                                                                                                                                                                                          |
| 4  | 10/26/20  | [**Data exploration and visualization in R**](#4) <br> The exploratory data analysis mindset, Data visualization best practices, Simple base graphics (including scatterplots, histograms, bar graphs, dot chats, boxplots and heatmaps), Building more complex charts with ggplot.                                                                                                                                                                                                                                                       |
| 5  | 11/02/20 | [**Writing your own R functions and using packages from CRAN,  BioConductor and GitHub**](#5) <br> The basics of writing your own functions that promote code robustness, reduce duplication and facilitate code re-use. Extending functionality and utility with R packages from CRAN and BioConductor, Working with Bio3D for molecular data. <br> **Project: Pt 1. Q1-Q4 due\!**                                                                                                                                                                                                                                                                                      |
| 6  | 11/09/20  | [**Machine learning for Bioinformatics**](#6) <br> Unsupervised learning, K-means clustering, Hierarchical clustering, Heatmap representations. Dimensionality reduction, Principal Component Analysis (PCA)                                                                                                                                                                                                                                                            |
| 7  | 11/16/20  | [**Genome informatics and high throughput sequencing**](#7) <br> Searching genes and gene functions, Genome databases, Variation in the Genome, High-throughput sequencing technologies, biological applications, bioinformatics analysis methods; The Galaxy platform along with resources from the EBI & UCSC                                                                                                                                                                                                                                                            |
| 8  | 11/23/20  | [**Happy Thanksgiving!**](#8) <br> **N.B.** No formal lab class live-cast this week but we do present video lectures on [**Essential UNIX for bioinformatics**](#8) and also please note that the find a gene assignment is due soon!                                                                                                                                                                                                                                            |
| 9  | 11/30/20  | [**Transcriptomics, RNA-Seq analysis, and the interpretation of gene lists**](#9) <br> RNA-Seq aligners, Differential expression tests, RNA-Seq statistics, Counts and FPKMs and avoiding P-value misuse, Hands-on analysis of RNA-Seq data with R. Gene function annotation, Functional databases KEGG, InterPro, GO ontologies and functional enrichment analysis.                                                                                                                                                                                                                                            |
| 10  | 12/07/20  | [**Course summary**](#10) <br> Summary of learning goals, Student course evaluation time; <br> **Project: Find a gene assignment due\!**                                                                                                                                                                                                              |



# Class material

---



<a name="0"></a>
## Week 0: Getting oriented

**Topics:**  
Course introduction, Learning goals & expectations, Meet the instructional team. Seting up your computer with required software.   

**Goals:**
- Understand course scope, expectations, logistics and ethics code.  
- Complete the pre-course questionnaire.  
- Setup your computer for this course.  


**Videos:**
- 0.1 - [Welcome to BGGN 213 (course introduction and overview)](hhttps://youtu.be/MpF0sVb7zpQ){:target="_blank"}  
- 0.2 - [Website overview (finding course content and installing software)](https://youtu.be/vSxhjyRs-lg){:target="_blank"}  
- 0.3 - [Meet the team (Barry & Yu)](){:target="_blank"}  
- 0.4 - [Signing up for Piazza](https://youtu.be/aswdH8vXiB0){:target="_blank"}  
 

**Supporting material:**  
- Handout: [Class Syllabus]({{ site.baseurl }}/class-material/BGGN213_F20_syllabus.pdf){:.no-push-state}{:target="_blank"},  
- Pre-course [Questionnaire](https://forms.gle/EL9JjxvPRnFqGMWy5){:target="_blank"},   
- Computer [Setup Instructions]({{ site.baseurl }}/setup/).  
- Sign up for our [Piazza class Q&A site](https://piazza.com/ucsd/summer2020/bggn213){:target="_blank"},   
- View the class [**GradeBook**](https://docs.google.com/spreadsheets/d/1drbyXl6BSYUThXWMbVafKKZoRxORRI5rJqI1Y5mHZgg/){:target="_blank"}.  


---

<a name="1"></a>
## Week 1: Welcome to Bioinformatics

**Topics:**
Biology is an information science, History of Bioinformatics, Types of data, Application areas and introduction to upcoming course segments, Introduction to NCBI & EBI resources for the molecular domain of bioinformatics, Hands-on session using NCBI-BLAST, Entrez, GENE, UniProt, Muscle and PDB bioinformatics tools and databases.

**Goals:**
- Understand the increasing necessity for computation in modern life sciences research.  
- Get introduced to how bioinformatics is practiced. 
- Be able to query, search, compare and contrast the data contained in major bioinformatics databases (GenBank, GENE, UniProt, PFAM, OMIM, PDB) and describe how these databases intersect. 
- The goals of the hands-on session is to introduce a range of core bioinformatics databases and associated online services whilst actively investigating the molecular basis of several common human disease.  


**Videos:**
- 1.1 - [Introduction to bioinformatics (what, where and why of bioinformatics)](https://youtu.be/FNXMFXZR6HU){:.no-push-state}{:target="_blank"},  
- 1.2 - [Major bioinformatics resource providers (NCBI and EBI)](https://youtu.be/zUK7c9J1KGU){:.no-push-state}{:target="_blank"},  
- 1.3 - [A quick tour of major NCBI and EBI resources (GENE, UniProt, GO, OMIM, PDB, PFAM)](https://youtu.be/k77QilYmrfk){:.no-push-state}{:target="_blank"}.    


**Supporting Material**:  
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture-1-bggn213_large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture-1-bggn213_small.pdf){:.no-push-state}{:target="_blank"},     
- Handout: [Major Bioinformatics Databases]({{ site.baseurl }}/class-material/Major_Databases.pdf){:.no-push-state}{:target="_blank"},  
- Lab: [Hands-on section worksheet]({{ site.baseurl }}/class-material/lab-2-BIMM143_online-form.pdf){:target="_blank"}{:.no-push-state},  
- Lab: [Video walk-through](https://youtu.be/tv3Yt-wcXxY){:target="_blank"}{:.no-push-state} live on Thur @ 10am SD time,   
- Office Hours: [Zoom on Thur @ 12:30pm SD time](https://ucsd.zoom.us/s/167105503){:.no-push-state}{:target="_blank"},   
- Feedback: [Muddy Point Assessment](https://forms.gle/fHMc1C5gd7hh5eog7){:.no-push-state}{:target="_blank"},    


**Homework**:  
- [Questions](https://forms.gle/oSEoqGy9JCcc6VJy6){:.no-push-state}{:target="_blank"},  
- Readings: 
  - PDF1: [What is bioinformatics? An introduction and overview]({{ site.baseurl }}/class-material/bioinformatics_review.pdf){:.no-push-state},  
  - PDF2: [Advancements and Challenges in Computational Biology]({{ site.baseurl }}/class-material/bioinformatics_challenges_2015.pdf){:.no-push-state}.  
  

---

<a name="2"></a>
## Week 2: Sequence alignment fundamentals, algorithms and applications

**Topics:**
Sequence Alignment and Database Searching: Homology, Sequence similarity, Local and global alignment, Heuristic approaches, Database searching with BLAST, E-values and evaluating alignment scores and statistics.

**Goals:**
- Be able to describe how dynamic programming works for pairwise sequence alignment.  
- Appreciate the differences between global and local alignment along with their major application areas.  
- Understand how aligning novel sequences with previously characterized genes or proteins provides important insights into their common attributes and evolutionary origins.  
- The goals of the hands-on session are to explore the principles underlying the computational tools that can be used to compute and evaluate sequence alignments.  


**Videos:**  
- 2.1 - [Alignment fundamentals](https://www.youtube.com/watch?v=SU22pycFrDk){:.no-push-state}{:target="_blank"},    
- 2.2 - [Dot plots](http://youtu.be/nnPNwlzX2qg){:.no-push-state}{:target="_blank"},    
- 2.3 - [Dynamic programing, global alignment](https://youtu.be/LkwgI2mHbik){:.no-push-state}{:target="_blank"},    
- 2.4 - [Dynamic programing, local alignment and BLAST basics](https://youtu.be/uhD77hnxM2g){:.no-push-state}{:target="_blank"},    
  

**Supporting Material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture-2-bggn213_large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture-2-bggn213_small.pdf){:.no-push-state}{:target="_blank"},  
- Dot Plot App Mirrors: [app-1](https://barryus.shinyapps.io/dotplot/){:.no-push-state}{:target="_blank"},  [app-2](https://bioboot.shinyapps.io/dotplot/){:.no-push-state}{:target="_blank"},     
- Lab: [Hands-on section worksheet]({{ site.baseurl }}/class-material/lab-3-BIMM143_online-form.pdf){:.no-push-state}{:target="_blank"}  
- Lab: [Video walk-through](https://youtu.be/mttQRu4Fnmg){:target="_blank"}{:.no-push-state} live on Thur @ 10am SD time,   
- Office Hours: [Zoom on Thur @ 12:30pm SD time](https://ucsd.zoom.us/s/167105503){:.no-push-state}{:target="_blank"},   
- Feedback: [Muddy Point Assessment](https://forms.gle/FEbKxnq4X7nUMhcn8){:.no-push-state}{:target="_blank"}.   
     


**Homework**:   
- [Questions](https://forms.gle/z95D5XMvyYKWRrFq5){:.no-push-state}{:target="_blank"},  
- For next week please [install R and RStudio](https://www.datacamp.com/community/tutorials/installing-R-windows-mac-ubuntu){:.no-push-state}{:target="_blank"},  
- Complete the following [Alignment Problem]({{ site.baseurl }}/class-material/lecture2-BIMM134_homework.pdf){:.no-push-state}{:target="_blank"},  
- DataCamp: Sign-up to our **BIMM143_S20 group/organization** via the link in your UCSD email (we will use this next week),   



**Readings**:    
- Readings: PDF1: [What is dynamic programming?]({{ site.baseurl }}/class-material/Dynamic_programming_primer.pdf){:.no-push-state},  
- Readings: PDF2 [Fundamentals of database searching]({{ site.baseurl }}/class-material/Fundamentals.pdf){:.no-push-state}.   


 
---
<a name="11"></a>
<br>



## (**Project:**) Find a Gene Assignment Part 1        
The [**find-a-gene project**]({{ site.baseurl }}/class-material/Find_A_Gene_Project.pdf){:.no-push-state} is a required assignment for BIMM-143. The objective with this assignment is for you to demonstrate your grasp of database searching, sequence analysis, structure analysis and the R environment that we have covered to date in class.
 
You may wish to consult the scoring rubric at the end of the above linked project description and the [**example report**]({{ site.baseurl }}/class-material/Find_A_Gene_Project_Example.pdf){:.no-push-state} for format and content guidance.  
 
Your responses to questions Q1-Q4 are due **Tuesday Nov 3rd** (11/03/20) at 12pm San Diego time.   
 
The complete assignment, including responses to all questions, is due **Friday Dec 11th** (12/11/20) at 12pm San Diego time.  
 
In both instances your PDF format report should be submitted to GradeScope. Late responses will not be accepted under any circumstances.    


---
<a name="3"></a>
## Week 3: Bioinformatics data analysis with R


**Topics:**
Why do we use R for bioinformatics? R language basics and the RStudio IDE, Major R data structures and functions, Using R interactively from the RStudio console.

**Goal:**
- Understand why we use R for bioinformatics
- Familiarity with R’s basic syntax,
- Familiarity with major R data structures (vectors, data.frames and lists),
- Understand the basics of using functions (arguments, vectorizion and re-cycling).


**Videos:**
- 3.1 [Why R and RStudio](https://youtu.be/Asm2PHOZAcE){:.no-push-state}{:target="_blank"},    
- 3.2 [Major R data structures, data types, and using functions](http://youtu.be/3LOTxeQEHSM){:.no-push-state}{:target="_blank"},  
- 3.3 [Working with DataCamp](https://www.youtube.com/watch?v=q_GUl2YRoVk){:.no-push-state}{:target="_blank"}  **N.B.** Use your UCSD email invite to sign up and visit our class group/organization.    

**Supporting Material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture4-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture4-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},  
- Cheat Sheet: [Base R overview]({{ site.baseurl }}/class-material/base-r.pdf){:target="_blank"}{:.no-push-state},
- Lab: [Hands-on section]({{ site.baseurl }}/class-material/04_rintro/){:.no-push-state},  
- Lab: [Video walk-through](https://youtu.be/BngLbEIgQlo){:target="_blank"}{:.no-push-state} focusing on introducing [Project]({{ site.baseurl }}/class-material/Find_A_Gene_Project.pdf){:target="_blank"}{:.no-push-state} assignment, live on Thur @ 10am SD time,   
- Office Hours: [Zoom on Thur @ 12:30pm SD time](https://ucsd.zoom.us/s/167105503){:.no-push-state}{:target="_blank"},   
- Feedback: [Muddy point assessment](https://forms.gle/pGzaaSRGnQ1r9mrL9){:.no-push-state}{:target="_blank"},  
  


**Homework**:   
- [Questions](https://forms.gle/9uBet6MmqbH2Ro4c7){:.no-push-state}{:target="_blank"},  
- **DataCamp**: Sign-up to our **BIMM143_F20 group/organization** via the link in your UCSD email and **complete** [**Introduction to R!**](https://learn.datacamp.com/courses/free-introduction-to-r){:.no-push-state}{:target="_blank"} (4hrs).  
    



---
<a name="4"></a>
## Week 4: Data exploration and visualization in R

**Topics:** 
The exploratory data analysis mindset, Data visualization best practices, Simple base graphics (including scatterplots, histograms, bar graphs, dot chats, boxplots and heatmaps), Building more complex charts with ggplot.


**Goal:**
- Appreciate the major elements of exploratory data analysis and why it is important to visualize data.  
- Be conversant with data visualization best practices and understand how good visualizations optimize for the human visual system.  
- Be able to generate informative graphical displays including scatterplots, histograms, bar graphs, boxplots, dendrograms and heatmaps and thereby gain exposure to the extensive graphical capabilities of R.  
- Appreciate that you can build even more complex charts with ggplot and additional R packages.  
- Be able to write and (re)use basic R scripts to aid with reproducibility.  



**Videos:**
- 4.1 - [Why visualize data?](https://youtu.be/R_b7g5sGzwY){:.no-push-state}{:target="_blank"},   
- 4.2 - [Data visualization best practices](https://youtu.be/0WPeOxrboug){:.no-push-state}{:target="_blank"},   
- 4.3 - [Introduction to ggplot](https://youtu.be/qtfJa8muH9E){:.no-push-state}{:target="_blank"},   
- 4.4 - Optional: [The **g**rammar of **g**raphics - the **gg** in ggplot](https://vimeo.com/332290655){:.no-push-state}{:target="_blank"},   


**Supporting Material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture5-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture5-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},  
- Lab: [Hands-on worksheet]({{ site.baseurl }}/class-material/ggplot_play.html){:.no-push-state}{:target="_blank"},
- Lab: Live screencast [video walk-through](https://youtu.be/embeBPxY2HQ){:target="_blank"}{:.no-push-state} @ 10am Thur SD time.
- Office Hours: [Zoom on Thur @ 10am SD time](https://ucsd.zoom.us/s/167105503){:.no-push-state}{:target="_blank"},   
- Feedback: [Muddy point assessment](https://forms.gle/FJHD9Bnrmgj32Tk69){:.no-push-state}{:target="_blank"},  
 
 
**Homework**:   
- DataCamp: [Introduction to Data Visualization with ggplot2](https://learn.datacamp.com/courses/introduction-to-data-visualization-with-ggplot2){:.no-push-state}{:target="_blank"} (~4hrs).    
- SideNote: [Convincing with graphics](https://xkcd.com/833/){:.no-push-state}.  
- Check-out the new website: [Data-to-Viz](https://www.data-to-viz.com/){:.no-push-state}{:target="_blank"} and [ggplot cheat sheat](https://rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf){:.no-push-state}{:target="_blank"}.  

 

---
<a name="5"></a>
## Week 5: R functions and R packages from CRAN and BioConductor

**Topics:** 
The why, when and how of writing your own R functions with worked examples. Further extending functionality and utility with R packages, Obtaining R packages from CRAN and Bioconductor, Working with Bio3D for molecular data, Managing genome-scale data with bioconductor.

**Goals:**
- Understand the structure and syntax of R functions and how to view the code of any R function,  
- Be able to follow a step by step process of going from a working code snippet to a more robust function that reduces duplication and facilitate code re-use,    
- Be able to find and install R packages from CRAN and bioconductor,  
- Understand how to find and use package vignettes, demos, documentation, tutorials and source code repository where available.    

**Videos:**  
- 5.1 - [Writing your own functions (why, when and how)](https://www.youtube.com/watch?v=Z30gU8bowPU){:.no-push-state}{:target="_blank"},
- 5.2 - [Introduction to CRAN & BioConductor](http://youtu.be/OyOzRiu3458){:.no-push-state}{:target="_blank"},
- 5.3 - [Quick introduction to RMarkdown](https://www.youtube.com/watch?v=O7GMs9V3HQk){:.no-push-state}{:target="_blank"},  
- 5.4 - Optional longer video: [Getting started with RMarkdown](https://rstudio.com/resources/webinars/getting-started-with-r-markdown/){:.no-push-state}{:target="_blank"}.  


**Supporting material:**  
- Lecture Slides: [Pt1. Large PDF]({{ site.baseurl }}/class-material/lecture6-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Pt2. Large PDF]({{ site.baseurl }}/class-material/lecture07-BIMM143-large.pdf){:.no-push-state}{:target="_blank"},  
- Lab: [Hands-on section worksheet]({{ site.baseurl }}/class-material/lab_week6.pdf){:.no-push-state}{:target="_blank"},  
- Lab supplement: [Hands-on section supplemental information]({{ site.baseurl }}/class-material/lecture6-BIMM143_W19.pdf){:.no-push-state}{:target="_blank"},   
- Lab live session [zoom video](https://youtu.be/k3FKc2FXH2c){:.no-push-state}{:target="_blank"},   
- Extra: [Introductory tutorial on R packages](https://www.datacamp.com/community/tutorials/r-packages-guide){:.no-push-state}{:target="_blank"},  
- Office Hours: [Zoom on Thur @ 10am SD time](https://ucsd.zoom.us/s/167105503){:.no-push-state}{:target="_blank"},   
- Feedback: [Muddy point assessment](https://forms.gle/Y8un1ziwe99GYq1r6){:.no-push-state}.  

 
**Homework**:   
 - See **Q6** of the [hands-on lab supplement above]({{ site.baseurl }}/class-material/lecture6-BIMM143_W19.pdf){:.no-push-state}{:target="_blank"}. This entails turning a supplied code snippet into a more robust and re-usable function that will take any of the three listed input proteins and plot the effect of drug binding. Note assessment rubric and submission instructions within document. (Submission deadline: 12:00pm next **Tuesday, 11/10/20**).    
- DataCamp: [Intermediate R](https://learn.datacamp.com/courses/intermediate-r){:.no-push-state}{:target="_blank"} compltete chapters 1-3 only (~4hrs).   


**Other**:  
- Flat files for practicing importing with read.table: [test1.txt]({{ site.baseurl }}/class-material/test1.txt){:.no-push-state}, [test2.txt]({{ site.baseurl }}/class-material/test2.txt){:.no-push-state}, [test3.txt]({{ site.baseurl }}/class-material/test3.txt){:.no-push-state}.  



---
<a name="6"></a>
## Week 6: Introduction to machine learning for Bioinformatics

**Topics:** 
Unsupervised learning, supervised learning and reinforcement learning; Focus on unsupervised learning, K-means clustering, Hierarchical clustering, Dimensionality reduction, visualization and analysis, Principal Component Analysis (PCA) Practical considerations and best practices for the analysis of high dimensional datasets.


**Goal:**  
- Understand the major differences between unsupervised and supervised learning.  
- Be able to create k-means and hierarchical cluster models in R  
- Be able to describe how the k-means and bottom-up hierarchical cluster algorithms work.  
- Know how to visualize and integrate clustering results and select good cluster models.  
- Be able to describe in general terms how PCA works and its major objectives.  
- Be able to apply PCA to high dimensional datasets and visualize and integrate PCA results (e.g identify outliers, find structure in features and aid in complex dataset visualization).



**Videos:**
- 6.1 - [Introduction to unsupervised learning and K-means clustering](http://youtu.be/k2QPXRtTons){:.no-push-state}{:target="_blank"},  
- 6.2 - [Hierarchical clustering](http://youtu.be/L72a2QPzlRE){:.no-push-state}{:target="_blank"},  
- 6.3 - [Principal component analysis (PCA) Pt.1](http://youtu.be/2Ja1BGlfKQo){:.no-push-state}{:target="_blank"}.   
  

**Supporting material:**  
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture08-BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture08-BIMM143-small.pdf){:.no-push-state}{:target="_blank"},  
- WebApp: [Introduction to PCA]({{ site.baseurl }}/class-material/pca/){:.no-push-state}{:target="_blank"},  
- Lab: [Hands-on section worksheet for PCA]({{ site.baseurl }}/class-material/lab-wk7-bimm143.html){:.no-push-state}{:target="_blank"},  
- Data files: [UK_foods.csv]({{ site.baseurl }}/class-material/UK_foods.csv){:.no-push-state}, [WisconsinCancer.csv]({{ site.baseurl }}/class-material/WisconsinCancer.csv){:.no-push-state}, [new_samples.csv]({{ site.baseurl }}/class-material/new_samples.csv){:.no-push-state}.  
- Lab: Live screencast [video walk-through](https://youtu.be/5AiK2fSoE24){:target="_blank"}{:.no-push-state} @ 10am Thur SD time.
- Office Hours: [Zoom on Thur @ 12:30pm SD time](https://ucsd.zoom.us/s/167105503){:.no-push-state}{:target="_blank"},   

- Feedback: [Muddy point assessment](https://docs.google.com/forms/d/e/1FAIpQLSdiQn7n6XvvRGq5AfQWaRa7G22-twFCN4bYNANCWSK09DBYZg/viewform){:.no-push-state}.  

 

**Homework**:   
- DataCamp: [Introduction to the Tidyverse](https://learn.datacamp.com/courses/introduction-to-the-tidyverse){:.no-push-state}{:target="_blank"} (~4hrs).   
- Mini-Project: [Unsupervised learning analysis of breast cancer cells]({{ site.baseurl }}/class-material/wk7_miniproject.html){:.no-push-state}{:target="_blank"},  
- Data file: [WisconsinCancer.csv]({{ site.baseurl }}/class-material/WisconsinCancer.csv){:.no-push-state}, [new_samples.csv]({{ site.baseurl }}/class-material/new_samples.csv){:.no-push-state}.     
 


**Other Material**:  
- Bonus: [StackExchange discussion on PCA](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa){:.no-push-state}{:target="_blank"}.   




---
<a name="7"></a>
## Week 7: Genome informatics

**Topics:** 
Genome sequencing technologies past, present and future (Sanger, Shotgun, PacBio, Illumina, toward the $500 human genome), Biological applications of sequencing, Variation in the genome, RNA-Sequencing for gene expression analysis; Major genomic databases, tools and visualization resources from the EBI & UCSC, The Galaxy platform for quality control and analysis; Sample Galaxy RNA-Seq workflow with FastQC and Bowtie2

**Goals:**
- Appreciate and describe in general terms the rapid advances in sequencing technologies and the new areas of investigation that these advances have made accessible.  
- Understand the process by which genomes are currently sequenced and the bioinformatics processing and analysis required for their interpretation.  
- For a genomic region of interest (e.g. the neighborhood of a particular SNP), use a genome browser to view nearby genes, transcription factor binding regions, epigenetic information, etc.  
- Be able to use the Galaxy platform for basic RNA-Seq analysis from raw reads to expression value determination.  
- Understand the FASTQ file format and the information it holds.  
- Understand the SAM/BAM file format and the information it holds.  

**Videos:**  
- 7.1 - [Introduction to genomics](http://youtu.be/WpbE1dANSDU){:.no-push-state}{:target="_blank"},   
- 7.2 - [Sequencing methods](https://www.ibiology.org/techniques/dna-sequencing/){:.no-push-state}{:target="_blank"} from Jonathan Weissman (UCSF),    
- 7.3 - [The basics of RNASeq work-flows](http://youtu.be/_JPAV9PBgnA){:.no-push-state}{:target="_blank"},   
- 7.4 - Optional: [Lessons from the Human Genome Project](https://www.youtube.com/watch?v=qOW5e4BgEa4){:.no-push-state}{:target="_blank"}.   

**Supporting material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture13_BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture13_BIMM143-small.pdf){:.no-push-state}{:target="_blank"},
- Lab: [Hands-on section worksheet]({{ site.baseurl }}/class-material/wk8_genomics_lab.pdf){:.no-push-state}{:target="_blank"} (as PDF form),
- Lab: Live screencast [video walk-through](https://youtu.be/jfAlMYAJNw8){:target="_blank"}{:.no-push-state} @ 10am Thur SD time.  
- RNA-Seq data files: [HG00109_1.fastq]({{ site.baseurl }}/class-material/HG00109_1.fastq){:.no-push-state}, [HG00109_2.fastq]({{ site.baseurl }}/class-material/HG00109_2.fastq){:.no-push-state}, [genes.chr17.gtf]({{ site.baseurl }}/class-material/genes.chr17.gtf){:.no-push-state}, [Expression genotype results]({{ site.baseurl }}/class-material/rs8067378_ENSG00000172057.6.txt){:.no-push-state}, [Example R script]({{ site.baseurl }}/class-material/lecture13_plot.r){:.no-push-state}, [Example Rmd](https://github.com/bioboot/test_github/blob/master/lecture13_plot.md){:.no-push-state}.
- [SAM/BAM file format description]({{ site.baseurl }}//class-material/sam_format/){:.no-push-state}{:target="_blank"}.  
- Office Hours: [Zoom on Thur @ 12:30pm SD time](https://ucsd.zoom.us/s/167105503){:.no-push-state}{:target="_blank"},   

- Feedback: [Muddy point assessment](https://forms.gle/Qx4UTSc4zkpafRvq9){:.no-push-state}{:target="_blank"}.  

## IPs     
- nt1  IP: http://3.212.78.120/galaxy  
- nt2  IP: http://3.231.195.172/galaxy  


---
<a name="8"></a>
## Week 8: Essential UNIX for bioinformatics

**Topics:** 
Bioinformatics on the command line, Why do we use UNIX for bioinformatics? UNIX philosophy, 21 Key commands, Understanding processes, File system structure, Connecting to remote servers, Redirection, streams and pipes, Workflows for batch processing, Organizing computational projects.  


**Goals:**  
- Understand why we use UNIX for bioinformatics  
- Use UNIX command-line tools for file system navigation and text file manipulation.  
- Have a familiarity with 21 key UNIX commands that we will use ~90% of the time.  
- Be able to connect to remote servers from the command line.  
- Use existing programs at the UNIX command line to analyze bioinformatics data.  
- Understand IO Redirection, Streams and pipes.  
- Understand best practices for organizing computational projects.  

**Videos:**
- 8.1 - [Essential UNIX for bioinformatics](){:.no-push-state}{:target="_blank"},  
- 8.2 - [Using remote UNIX machines](){:.no-push-state}{:target="_blank"},  
- 8.3 - [Organizing your computational biology projects ](){:.no-push-state}{:target="_blank"}.  .    
- Lab screencast - *No Live video walk-through this Thanksgiving week*.      


**Supporting material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture17_bggn213-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture17_bggn213-large-small.pdf){:.no-push-state}{:target="_blank"}.
- Hands-on section worksheet
  * [Using remote UNIX machines (Part I, **REQUIRED**)]({{ site.baseurl }}/class-material/17_blast-01/){:.no-push-state}{:target="_blank"},
  * [Using remote UNIX machines (Part II, Optional)]({{ site.baseurl }}/class-material/16_blast-02/){:.no-push-state},
  * [Using remote UNIX machines (Part III, Optional)]({{ site.baseurl }}/class-material/16_blast-03/){:.no-push-state}.  
- Example data set [bggn213_01_unix.zip]({{ site.baseurl }}/class-material/bggn213_01_unix.zip){:.no-push-state},  
- [Muddy point assessment](https://goo.gl/forms/W2G06LVrn2pADB2q1){:.no-push-state}.  



---
<a name="9"></a>
## Week 9: Transcriptomics and the analysis of RNA-Seq data

**Topics:** 
Analysis of RNA-Seq data with R, Differential expression tests, RNA-Seq statistics, Counts and FPKMs, Normalizing for sequencing depth, DESeq2 analysis. Gene finding and functional annotation from high throughput sequencing data, Functional databases KEGG, InterPro, GO ontologies and functional enrichment.  


**Goals:**  
- Given an RNA-Seq dataset, find the set of significantly differentially expressed genes and their annotations.  
- Gain competency with data import, processing and analysis with DESeq2 and other bioconductor packages.  
- Understand the structure of count data and metadata required for running analysis.  
- Be able to extract, explore, visualize and export results.  
- Perform a GO analysis to identify the pathways relevant to a set of genes (e.g. identified by transcriptomic study or a proteomic experiment). Use both Bioconductor packages and online tools to interpret gene lists and annotate potential gene functions.

**Videos:**
- 9.1 - [Differential expression analysis of RNA-Seq data](https://youtu.be/AGAmd51oIEg){:.no-push-state}{:target="_blank"},  
- 9.2 - [Differential expression tests and pathway analysis](https://youtu.be/bxvZmGe3IGk){:.no-push-state}{:target="_blank"}.    
- Lab screencast - [Live video walk-through](https://youtu.be/_hFjQvK2UdI){:target="_blank"}{:.no-push-state} @ 10am Thur SD time.      


**Supporting material:**
- Lecture Slides: [Large PDF]({{ site.baseurl }}/class-material/lecture14_BIMM143-large.pdf){:.no-push-state}{:target="_blank"}, [Small PDF]({{ site.baseurl }}/class-material/lecture14_BIMM143-small.pdf){:.no-push-state}{:target="_blank"}.
- Detailed [Bioconductor setup]({{ site.baseurl }}//class-material/bioconductor_setup/){:.no-push-state}{:target="_blank"} instructions.
- Lab: [Hands-on section worksheet]({{ site.baseurl }}/class-material/week09_lab_bimm143){:.no-push-state}{:target="_blank"},  
- Lab: Live screencast [video walk-through](https://youtu.be/_hFjQvK2UdI){:target="_blank"}{:.no-push-state} @ 10am Thur SD time.  
- Data files: [airway_scaledcounts.csv]({{ site.baseurl }}/class-material/airway_scaledcounts.csv){:.no-push-state}, [airway_metadata.csv]({{ site.baseurl }}/class-material/airway_metadata.csv){:.no-push-state}.  
- Office Hours: [Zoom on Thur @ 12:30pm SD time](https://ucsd.zoom.us/s/167105503){:.no-push-state}{:target="_blank"},   
- [Muddy point assessment](https://goo.gl/forms/CjzYyzBT0VsuOvBt2){:.no-push-state}.  


**Readings**:
 - Excellent review article: [Conesa et al. A survey of best practices for RNA-seq data analysis. _Genome Biology_ 17:13 (2016)](http://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0881-8){:.no-push-state}.
 - An oldey but a goodie: [Soneson et al. "Differential analyses for RNA-seq: transcript-level estimates improve gene-level inferences." _F1000Research_ 4 (2015)](https://f1000research.com/articles/4-1521/v2).
 - Good review article: Trapnell C, Hendrickson DG, Sauvageau M, Goff L et al. "*Differential analysis of gene regulation at transcript resolution with RNA-seq*". Nat Biotechnol 2013 Jan;31(1):46-53. [PMID: 23222703](https://www.ncbi.nlm.nih.gov/pubmed/23222703){:.no-push-state}.   
 - Abstract and introduction sections of: [Himes et al. "RNA-Seq transcriptome profiling identifies CRISPLD2 as a glucocorticoid responsive gene that modulates cytokine function in airway smooth muscle cells." _PLoS ONE_ 9.6 (2014): e99625](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0099625){:.no-push-state}.  


**Optional extension exercises:**
- Optional extension lab: [Hands-on worksheet]({{ site.baseurl }}/class-material/lab-15-bimm143.html){:.no-push-state}{:target="_blank"},  
- Data files: [GSE37704_featurecounts.csv]({{ site.baseurl }}/class-material/GSE37704_featurecounts.csv){:.no-push-state}, [GSE37704_metadata.csv]({{ site.baseurl }}/class-material/GSE37704_metadata.csv){:.no-push-state}.   

 
**R Knowledge Check**:
[**Quiz Assessment**](https://forms.gle/FppQDHdzRnQpJudP7){:.no-push-state}{:target="_blank"}. 




---
<a name="10"></a>
## Week 10: Course wrap up, project completion

**Topics:** 
Summary of learning goals, Student course evaluation time; Find a gene assignment due. Open study. Student selected topic:


**Bioinformatics and genomics in industry and beyond**  

- Video [**live stream interview**](https://youtu.be/UFYeovcGcwY){:.no-push-state}{:target="_blank"} with leading bioinformatics and genomics scientists from industry including **Dr Ali Crawford** (Associate Director, Scientific Research, *Illumina Inc.*), **Dr. Bjoern Peters** (Full Professor and Principal Investigator, *La Jolla Institute*) and **Dr. Ana Grant** (Director of Research Informatics, *Synthetic Genomics Inc.*).

- Submit [your questions here](https://piazza.com/class/k80g6xd4ijjjo?cid=68){:.no-push-state}{:target="_blank"}.


**Side-note:**
Student topic of choice was selected from those below:

- Biological network analysis
- Cancer genomics
- Unix for Bioinformatics
- Structural Bioinformatics and computational drug design
- Introduction to the tidyverse  
- Bioinformatics and genomics in industry and beyond   

