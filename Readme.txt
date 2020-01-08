The SWMM model for the Astlingen benchmark network is provided here with the name of Astlingen_SWMM.inp
Two different control rules are considered, which are the Base Case control (BC) of locally controlled throttle settings and the Equal Filling Degree real-time control (EFD). 
Internal control rules are provided for both of them respectively in the control editor of SWMM. The Rule BC is developed for the BC control, while the rest are for the EFD control. When one control is to be applied, the other control rules should be deleted from the control editor first.
Besides, before running this SWMM model, you also need to reload the four rain files and the backdrop picture cause they are using relative paths. You can refer to the 1-year rainfall times series for the four different rain guages with the names of:
1Astlingen_Erft1.txt
2Astlingen_Erft2.txt
3Astlingen_Erft3.txt
4Astlingen_Erft4.txt
astingen.jpg is the backdrop picture.
