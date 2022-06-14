# Mice Protein Expression

The data set under analysis consists of the expression levels of 77 proteins/protein modifications that produced detectable signals in the nuclear fraction of cortex.

There are 38 control mice and 34 trisomic mice (Down syndrome), for a total of 72 mice. In the experiments, 15 measurements were registered of each protein per sample/mouse. Therefore, for control mice, there are 38x15, or 570 measurements, and for trisomic mice, there are 34x15, or 510 measurements. The dataset contains a total of 1080 measurements per protein. Each measurement can be considered as an independent sample/mouse.

The eight classes of mice are described based on features such as genotype, behavior and treatment. According to genotype, mice can be control or trisomic. According to behavior, some mice have been stimulated to learn (context-shock) and others have not (shock-context) and in order to assess the effect of the drug memantine in recovering the ability to learn in trisomic mice, some mice have been injected with the drug and others have not.

Classes: c-CS-s: control mice, stimulated to learn, injected with saline (9 mice) c-CS-m: control mice, stimulated to learn, injected with memantine (10 mice) c-SC-s: control mice, not stimulated to learn, injected with saline (9 mice) c-SC-m: control mice, not stimulated to learn, injected with memantine (10 mice)

t-CS-s: trisomy mice, stimulated to learn, injected with saline (7 mice) t-CS-m: trisomy mice, stimulated to learn, injected with memantine (9 mice) t-SC-s: trisomy mice, not stimulated to learn, injected with saline (9 mice) t-SC-m: trisomy mice, not stimulated to learn, injected with memantine (9 mice)

The aim of this machine learning project is to solve a clustering task to identify subsets of proteins that are discriminant between the classes. 

<p align="center">
  <img 
    src="https://storage.googleapis.com/plos-corpus-prod/10.1371/journal.pone.0129126/1/pone.0129126.g001.PNG_L?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=wombat-sa%40plos-prod.iam.gserviceaccount.com%2F20220614%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20220614T075041Z&X-Goog-Expires=86400&X-Goog-SignedHeaders=host&X-Goog-Signature=732216a8d1fbec74d03d0c7ea94b807414b414c743c937bcfa824fdb24a4dcfddcdc0f1617e575821c888b714e629c37029a7c1c7f19317930157f6c3ba41f64b7d8a55f8cd8d4e9bf20b1f657265b57d4ed9f3d73c938fdcc736bc941af42597a8c139a65ffa3de3b78f134e2df4becee592eaeaf7346f7e6a53811c7f4debec2a19d1ab23429c774df815997bc5e380af5160de0d4d35e69b3ba9c6109d70206d95552985f03bc8327f223dae3eed8c02437ddf50cdead882685b6223157553cb6ae2f7060aa58a7aa17d51f2d7e8484059c43167e801c6d800925e4e2450568919a0374f994c6b2ab018b0b742442c3a83a56b70ce2df35f62f9471ae1607#center">
</p>

The notebook can be viewed at https://nbviewer.org/github/emanuelecavalleri/MiceProteinExpression/blob/main/MiceProteinExpression.ipynb.
