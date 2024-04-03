# PROMOTE data queries

In this repository, you can find the following data queries:

1. Demographics
2. Sample collection
3. Patient-reported outcome questionnaires
4. DMT / relapse queries
5. NIH style enrollment report for PROMOTE cohort

# Demographics

Version 1: 2024-04-02

Descriptive statistics of the PROMOTE cohort including age, sex, race, ethnicity, disease duration, disease modifying therapy class, disease modifying therapy type, address, and Charleson Comorbidity Index (CCI).

Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Missing Identifiers, Legacy PQ/SRO, Covid Longitudinal, Covid Registry, PASC, DMTs enroll (attained using DMT Query also found in this repository)

Output: Table 1 demographics of entire PROMOTE cohort, CSV file with demographics of PROMOTE cohort (at time of enrollment), density plot of age/sex by subject group, stacked/grouped bar plots of sex by subject group, density plot of disease duration by subject group, stacked/grouped bar plots of DMT efficacy of subject group, density plot of age at onset by subject group, stacked/grouped bar plots of age at onset by subject group, stacked/grouped bar plots of race/ethincity by subject group, CSV file of address of all PROMOTE participant, CSV file with earliest CCI for each PROMOTE participant, histogram of all total CCI scores.

# Sample collection

1. Serum
2. Plasma
3. PBMC
4. DNA

   Version 1: 2024-04-02

   Finds list of participants with DNA sample and their demographics

   Input: PROMOTEDatabase, Genomic data attained participant list

   Output: Table of demographic summary for all PROMOTE participants with a DNA sample, CSV file containing all participants with DNA sample and their demographics
   
6. Stool
7. Cerebrospinal fluid (CSF)

   Version 1: 2024-04-02

   Finds demographic information and dates of all CSF samples collected in the PROMOTE cohort

   Input: PROMOTEDatabase

   Output: Table of demographic summary of participants who have donated CSF samples, CSV file containing all CSF sample dates with the demographics of the donating participant.

# Patient-reported outcome questionnaires

1. Patient-determined disease steps (PDDS)

   Version 1: 2024-03-21

   Finds PDDS values and median scores per year for all PROMOTE participants and EDSS values stored in the PROMOTEDatabase.

   Input: PROMOTEDatabase, PROMOTE Longitudinal, Legacy, Missing IDs, Legacy SNQ, sensor, covid, vaccine, pre/pro.

   Output: Histogram of all PDDS scores, earliest PDDS scores, and most recent PDDS scores. CSV files of all PDDS scores, earliest PDDS scores, most recent PDDS scores, median PDDS score, and all EDSS scores.

2. Multiple sclerosis rating scale, revised (MSRS-R)

   Version 1: 2024-04-03

   Finds MSRS-R values and mediam scores per year for all PROMOTE participants.

   Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing IDs, Legacy SNQ, Sensor, Covid Longitudinal, Vaccine Longitudinal, Pre/pro, PASC

   Output: CSV file with all MSRSR scores (and subscores), histogram of all MSRSR scores, histogram of most recent MSRSR scores, CSV file with most recent MSRSR scores, histogram of earliest MSRSR scores, CSV file with earliest MSRSR scores, histogram of difference in days between two consecutive scores for participants with at least 2 MSRSR scores, CSV file with median score from all years. 

4. Bladder Control Scale (BLCS) & Bowel Control Scale (BWCS)

   Version 1: 2024-04-02

   Finds all BLCS & BWCS measure scores for the PROMOTE Study

   Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers, Pre/Pro

   Output: Histogram of all total BLCS scores, histogram of all total BWCS scores. CSV files of all BLCS scores, CSV file of all BWCS scores.

5. Center for Epidemiological Studies-Depression (CESD)

   Version 1: 2024-04-02

   Finds all CESD measure scores for the PROMOTE study

   Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers

   Output: Histogram of all total CESD scores, histogram of all earliest total CESD scores, CSV file of all CESD scores.


# DMT / relapse queries


# NIH style enrollment report

<Enter description + version here>
