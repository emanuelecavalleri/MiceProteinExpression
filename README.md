# Mice Protein Expression

The data set consists of the **expression levels of $77$ proteins/protein modifications that produced detectable signals in the nuclear fraction of cortex**. There are $38$ control mice and $34$ trisomic mice (Down syndrome), for a total of $72$ mice. In the experiments, $15$ measurements were registered of each protein per sample/mouse. Therefore, for control mice, there are $38x15$, or $570$ measurements, and for trisomic mice, there are $34x15$, or $510$ measurements. The dataset contains a total of $1080$ measurements per protein. Each measurement can be considered as an **independent** sample/mouse.

The eight classes of mice are described based on features such as **genotype**, **behavior** and **treatment**. According to genotype, mice can be **control** or **trisomic**. According to behavior, some mice have been stimulated to learn (**context-shock**) and others have not (**shock-context**) and in order to assess the effect of the drug **memantine** in recovering the ability to learn in trisomic mice, some mice have been injected with the drug and others have not.

<p align="center">
  <img 
    src="https://journals.plos.org/plosone/article/figure/image?size=large&id=10.1371/journal.pone.0129126.g001#center">
</p>

Higuera C, Gardiner KJ, Cios KJ (2015) <i>Self-Organizing Feature Maps Identify Proteins Critical to Learning in a Mouse Model of Down Syndrome.</i> PLoS ONE 10(6): e0129126. [<a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0129126">Web Link</a>] journal.pone.0129126 

The aim of this machine learning project is to solve a **clustering** task starting from this dataset identifying subsets of proteins that are discriminant between the classes, i .e. find structures in the data that allow samples from different classes to be easily identified, and to compare the performance of different clustering algorithms using appropriate clustering metrics. 

The notebook can be viewed at https://nbviewer.org/github/emanuelecavalleri/MiceProteinExpression/blob/main/MiceProteinExpression.ipynb.
