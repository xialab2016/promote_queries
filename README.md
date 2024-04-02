# PROMOTE data queries

In this repository, you can find the following data queries:

1. Demographics
2. Sample collection
3. Patient-reported outcome questionnaires
4. DMT / relapse queries
5. NIH style enrollment report for PROMOTE cohort

# Demographics

<Enter description + version here>

Descriptive statistics of the PROMOTE cohort including age, sex, race, ethnicity, disease duration, disease modifying therapy class, disease modifying therapy type.

# Sample collection

1. Serum
2. Plasma
3. PBMC
4. DNA
5. Stool
6. CSF

# Patient-reported outcome questionnaires

1. Patient-determined disease steps (PDDS)

   Version 1: 2024-03-21

   Finds PDDS values and median scores per year for all PROMOTE participants and EDSS values stored in the PROMOTEDatabase.

   Input: PROMOTEDatabase, PROMOTE Longitudinal, Legacy, Missing IDs, Legacy SNQ, sensor, covid, vaccine, pre/pro.

   Output: Histogram of all PDDS scores, earliest PDDS scores, and most recent PDDS scores. CSV files of all PDDS scores, earliest PDDS scores, most recent PDDS scores, median PDDS score, and all EDSS scores.

2. Bladder Control Scale (BLCS) & Bowel Control Scale (BWCS)

   Version 1: 2024-04-02

   Finds all BLCS & BWCS measure scores for the PROMOTE Study

   Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers, Pre/Pro

   Output: Histogram of all total BLCS scores, histogram of all total BWCS scores. CSV files of all BLCS scores, CSV file of all BWCS scores.

3. Center for Epidemiological Studies-Depression (CESD)

   Version 1: 2024-04-02

   Finds all CESD measure scores for the PROMOTE study

   Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers

   Output: Histogram of all total CESD scores, histogram of all earliest total CESD scores, CSV file of all CESD scores.

# DMT / relapse queries


# NIH style enrollment report

<Enter description + version here>
