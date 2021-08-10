# Dynamic-Mode-Decomposition-For-Foreground-Extraction
Using  a singular value decomposition (SVD) based dynamic mode decomposition (DMD) to extract the foreground in highway traffic footage.

As of now this is very much a work in progress: The DMD has been performed on the highway traffic footage and the background frequency components have been identified. All that remains is DMD signal reconstruction. The DMD.ipynb file contains the first attempt at actually extracting the background and it is not working as of now.

UPDATE: The DMD extraction is now working. I forgot to propagate the background dynamics to obtain the background for every time step. The notebook now contains the working version. 

The .pdf file contains some notes I put together while working on this. 
