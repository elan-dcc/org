# Q&A DCC ELAN

| nr | Question | Priority | Deadline | Q Owner |
| --- | --- | --- | --- | --- |
| 1 | Is reading SPSS files necessary? Might loading in the files in other extensions be faster? | Low |  | Marcel |
| 2 | How does CBS store the files? Is it completely necessary for them that they are in SPSS format? | Low |  | Marcel |
| 3 | Is it possible for CBS to save the files in a more accessible format? | Low |  | Marcel |
| 5 | Can the structure of the code be improved? "A_Preprocess_CBS_ELAN_area_gem_codes.Rmd". Currently there are 1200 lines, which is quite large. Is it possible to split the code up to different files, with each file running a separate part? | Medium |  | Marcel |
| 6 | Is it possible to restructure "A_Preprocess_CBS_ELAN_area_gem_codes.Rmd" to Jasper's suggestions? | Medium |  | Marcel, Jasper |
| 9 | What are the optimal steps to take if we are to switch to online repository systems like GitHub for code sharing? | **High** | Workshop dates | Marcel |
| 10 | How do we make sure people get accustomed to GitHub even if they do not have a computer science background? | **High** | Workshop dates | Marcel |
| 13 | While pre-processing height/weight data, there is a discrepancy between the number of results for R and SPSS (Willemijn). Is there possibly a problem with R? | Medium |  | Willemijn, Lisette, Jasper |
| 14 | There is a discrepancy between the results for BMI when it is calculated from height and weight and BMI when it is taken directly from the "BMI"-field for the same patients, what are (possible) explanations for this? | Medium |  | Willemijn, Janet, Lisette |
| 15 | For the ELAN patient (PAT) file, does every patient have one row? Multiple rows per patient seem to appear when patients switch GPs. 0.13% of the duplicate RINPERSOON rows have different birthdates, how is this possible? |  |  | **??** |
| 16 | If patients first attend a non-ELAN practice and then transfer to an ELAN practice, is the relevant medical history (correctly) transferred to ELAN? How much missing data is there in this aspect? |  |  | **??** |
| 17 | Is it possible to add general statistics on the unlinkable population per data upload, to aid in assessing differences within confounding variables and groups? |  |  | **??** |
| 18 | How much do the medication entries in ELAN GP differ from medication entries in Vektis? In theory they should be identical, but a lot of medication entries are missing in ELAN GP, for a large part this happens when the medication is prescribed by a specialist and this is not communicated to the GP His. I'm mainly interested in the medications commonly used for rheumatic diseases and prescribed by the specialists, to be precise the following level-4 ATC codes: A07EA, A07EC, H02AB, L01AA, L01BA, L01XC, L04AA, L04AB, L04AC, L04AD, L04AX, M01CB, M01CC, P01BA  |  |  | Georgy, **??** |
| 19 |  |  |  |  |





## Archive with answers 

| nr | Question | Answer | Date | Who gave the answer? | 
| --- | --- | --- | --- | --- |
| 11 | Can we have a central document or forum on standard questions and frequently asked data points like total amount of patients? An FAQ if you will. | That should be **this file** | 20240315 | Marcel | 
| 4 | Can the author's name and version code be added to code files? | On GitHub, that's all solved! | 20240315 | Marcel | 
| 7 | Is it better to keep "A_Preprocess_CBS_ELAN_area_gem_codes.Rmd" all in one file for clarity's sake for people with non-technical backgrounds? | Especially for non-technical people, separation of concerns adds to clarity, as long as the overall structure is clear and comments are adequate. This should be part of the review process. | 20240315 | Marcel | 
| 8 | Should we stick to R overall? Or should we venture out to SPSS, Python, Excel etc. as well? What are the challenges if we were to head this way? | We will not demand peple to use what we want them to use. To keep the barriers low, everybody uses their own environment of preference, BUT the review process should be in place, so you can'be the only one to understand what happens. Challenges will arise (e.g. strategy implemented in one, is not yet available in the other language), but that's the price we pay. | 20240315 | Marcel | 
| 12 | If we were to use GitHub, should we stick to one standardised file format on there? Like R, SPSS, Python etc. | See question 8 | 20240315 | Marcel | 
