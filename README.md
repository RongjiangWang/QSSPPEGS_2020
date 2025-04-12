A variant of FORTRAN code QSSP for calculating prompt elasto-gravity signals (PEGS) of an earthquake in a spherically symmetric and elastic earth.

For Windows user, the executable file is provided under folder "WindowsEXE". Linux user may compile the source codes with "gfortran" via a single command like, e.g.,

~>cd .../SourceCode

~>gfortran -o qssppegs *.f -O3

to get the excutable code qssppegs.

After start the executable code, the program ask for an input file in the ASCII format. An example input file is provided under folder "InputFile". You may change the input data included in this file for your own applications.

References

Wang, R., S. Heimann, Y. Zhang, H. Wang, and T. Dahm (2017). Complete synthetic seismograms based on a spherical self-gravitating Earth model with an atmos-phere-ocean-mantle-core structure. Geophysical Journal International, doi: 10.1093/gji/ggx259.

Zhang, S., R. Wang, T. Dahm, S. Zhou, and S. Heimann (2020). Prompt elasto-gravity signals (PEGS) and their potential use in modern seismology. Earth and Planetary Science Letters, 36: 116150. doi:10.1016/j.epsl.2020.116150.
