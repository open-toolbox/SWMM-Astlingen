Here you can refer to the 1-year rainfall times series for the four different rain guages with the names of:
1Astlingen_Erft1.txt
2Astlingen_Erft2.txt
3Astlingen_Erft3.txt
4Astlingen_Erft4.txt
Two different SWMM .inp files are included, where Astlignen_BC.inp is the one for base case, Astlingen_EFD is for equal-filling degree.
The only difference between the two model is, in Astlingen_BC, all the orifice gates are configurated to generate throttle flows; while in Astlingen_EFD.inp, orifices gates are completely opened and being controlled through rules defined in the control editor.
Before running these models, you only need to reload the four rain files and the backdrop picture cause they are using relative paths. 