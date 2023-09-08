# Art Driven by Visual Representations of Chemical-Space

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

These can be dowloand from folder: "TMAP_visualizations" and open on local PC, or can be automatly generated using 
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
   


   
   
