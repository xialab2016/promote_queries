# Demographics

Version 1: 2024-04-02

Descriptive statistics of the PROMOTE cohort including age, sex, race, ethnicity, disease duration, disease modifying therapy class, disease modifying therapy type, address, and Charleson Comorbidity Index (CCI).

Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Missing Identifiers, Legacy PQ/SRO, Covid Longitudinal, Covid Registry, PASC, DMTs enroll (attained using DMT Query also found in this repository)

Output: Table 1 demographics of entire PROMOTE cohort, CSV file with demographics of PROMOTE cohort (at time of enrollment), density plot of age/sex by subject group, stacked/grouped bar plots of sex by subject group, density plot of disease duration by subject group, stacked/grouped bar plots of DMT efficacy of subject group, density plot of age at onset by subject group, stacked/grouped bar plots of age at onset by subject group, stacked/grouped bar plots of race/ethincity by subject group, CSV file of address of all PROMOTE participant, CSV file with earliest CCI for each PROMOTE participant, histogram of all total CCI scores.

# First Degree Relative Query

Version 1: 2024-05-28

Queries all sources to identify PROMOTE participants that are first degree relatives of someone with MS.

Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2 Legacy PQ/SRO

Output: CSV file of all PROMOTE MS participants with a first degree relative that has MS, CSV file of all PROMOTE participants (regardless of subject group) with a first degree relative that has MS

# PROMOTESubjectGroups

Version 1: 2024-06-04

Generates a table with the totals of all subject groups in the PROMOTE Study.

Input: PROMOTEDatabase

Output: Table with number of unique participants in each of the following subject groups: CIS, RIS, RRMS, SPMS, PPMS, Uncategorized MS, MS Total, NMOSD, MOGAD, Myelitis, Other NID, Other Autoimmune, Other Misc, Other NID/OND/Autoimmune Total, Healthy Control, Unknown, Total Overall

# Pediatric Query

Version 1: 2024-06-05

Generates lists of participants that had pediatric MS at three different criteria for 'pediatric'

Input: PROMOTEDatabase

Output: List of participants with first neuro sx under age of 18 AND diagnosed with MS under 18, list of participants with first neuro sx at/under age of 18 AND diagnosed with MS at/under age 18, and list of participants with first neuro sx under 21 AND diagnosed with MS under age 21


