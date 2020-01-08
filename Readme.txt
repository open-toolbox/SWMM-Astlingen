Astlingen_SWMM.inp is the SWMM model for the Astlingen benchmark network, which originally includes the Base Case control (BC) of locally controlled throttle settings, and can be run directly without alternations.
Another type of real-time control rules, the EFD control, has also been defined in the EFD_Control.txt.
To run Astlingen_SWMM.inp using EFD control, the only thing you need to do is replacing control rules in the SWMM editor at Astlinge_SWMM.inp with the rules defined in EFD_Control.txt. Similar scheme can be used to apply some other simple real-time control rules.
Small tips to use Astlingen_SWMM.inp: you may need to reload the four rain files and the backdrop picture cause they are using relative paths. You can refer to the 1-year rainfall times series for the four different rain guages with the names of:
1Astlingen_Erft1.txt
2Astlingen_Erft2.txt
3Astlingen_Erft3.txt
4Astlingen_Erft4.txt
astingen.jpg is the backdrop picture.
