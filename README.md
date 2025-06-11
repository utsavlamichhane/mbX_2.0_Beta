# mbX 2.0 Beta

mbX is a comprehensive R toolkit for rapid cleaning, statistical analysis, and high-resolution visualization of microbiome data generated with QIIME 2. 
The stable v1 release is available on CRAN and used by many at our university; this v2.0 Beta on GitHub adds major workflow enhancements and a new statistics module.

# What's New in 2.0 Beta

- Dedicated Output DirectoriesEach function now writes its outputs—tables and figures—into a user-specified folder, keeping your project organized.

- ezstat()A one-stop analysis pipeline performing:

    - Kruskal–Wallis tests across groups
    - Dunn’s post-hoc comparisons with BH adjustment
    - FDR correction
    - Compact Letter Display (CLD) annotation

- ezviz: A new parameter *flip* is added to the function. The parameter can have value "True" or "False". This parameter flips the orter of the taxa stacks in the barplot and the legends.
         If the user does not provide the *flip* parameter, the functions assumes "False" as default value.

# Contact & Citation

Author: Utsav Lamichhane and Dr. Jerefson Lourenco

Email: utsav.lamichhane@uga.edu

If you use mbX, please cite the CRAN version:

Lamichhane U., Lourenco J. (2025). *mbX: An R Package for Streamlined Microbiome Analysis.* Stats, 8(2), 44. https://doi.org/10.3390/stats8020044





