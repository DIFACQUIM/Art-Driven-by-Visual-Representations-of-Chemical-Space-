# Art Driven by Visual Representations of Chemical Space

Science and art have been connected for centuries. With the development of new computational methods, new scientific disciplines have emerged, such as computational chemistry, and related fields, such as cheminformatics. Chemoinformatics is grounded on the chemical space concept: a multi-descriptor space in which chemical structures are described. In several practical applications, visual representations of the chemical space of compound datasets are low-dimensional plots helpful in identifying patterns. However, the authors propose that the plots can also be used as artistic expressions. This work introduces an approach to merging art with chemoinformatics through visual and artistic representations of chemical space. As case studies, we portray the chemical space of food chemicals and other compounds to generate visually appealing graphs with twofold benefits: sharing chemical knowledge and developing pieces of art driven by chemoinformatics. The art driven by chemical space visualization will help increase the application of chemistry and art and contribute to general education and dissemination of chemoinformatics and chemistry through artistic expressions.

We invite you to read our [article](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-023-00770-4) and visit our [online gallery](https://www.difacquim.com/chemical-art-gallery/).

![figure](https://github.com/DIFACQUIM/Art-Driven-by-Visual-Representations-of-Chemical-Space-/blob/fa32453a6436361edc9974978074088a9c9ad541/Graphical_Abstract_V1.jpg)


## PCA and t-SNE visualization 

These can be automatly genetared using Google Colab.

**Instructions**
1. Select any files (files 01-07).
2. Click in "open in colab".
3. Save a copy in drive for edit files from personal drive.

## Chemical space visualizations with datawarrior
 **Instructions**
 1. Click in folder: "Chemical_space_visualizations_with_Datawarrior".
 2. Click in any file.dwar.
 3. Dowloand files.

## TMAPs visualization 

Display TMAP visualizations by clicking at links from folder: "TMAP_visualizations" or can be automatly generated using 
Jupyter-notebook on local PC.

**Intructions**

1. Dowloand TMAPs (files 07-10).

2. Dowloand Anaconda navigator.
https://www.anaconda.com/download

4. Create a virtual ambient with conda and rdkit.
        
        conda create -c conda-forge -n my-rdkit-env rdkit
   
5. Install Jupyter notebook. Open anaconda navigator with:

        anaconda-navigator
   
   In Anaconda navigator change <base(root)> to <my-rdkit-env>. Then, install Jupyter notebook.
   Close Anaconda navigator and return to terminal.
        
6. Activate virtual ambient.

        conda activate my-rdkit-env
   
7. Install TMAP and Faerun libraries. Available for Linux and MacOS.

        conda install -c tmap tmap
   
        conda install -c conda-forge faerun
   
9. Install venn diagram.
   
        pip install venn
   
10. Open notebook with:
   
        jupyter-notebook

# Reference
Please, cite our manuscript:
Gaytán-Hernández, D., Chávez-Hernández, A.L., López-López, E. et al. Art driven by visual representations of chemical space. J Cheminform 15, 100 (2023). [https://doi.org/10.1186/s13321-023-00770-4](https://doi.org/10.1186/s13321-023-00770-4)
   


   
   
