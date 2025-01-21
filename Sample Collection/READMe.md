# Sample Collection

1. Serum

   Version 2: 2025-01-21

   We updated the queries to reflect the new diagnosis status classification on REDCap.

   Version 1: 2024-04-16

   Finds list of participants with serum sample and their demographics

   Input: PROMOTEDatabase

   Output: Table of demographic summary for all PROMOTE participants with a serum sample, CSV file containing all participants with serum sample and their demographics
   
3. Plasma

   Version 2: 2025-01-21

   We updated the queries to reflect the new diagnosis status classification on REDCap.

   Version 1: 2024-04-15

   Finds list of participants with plasma sample and their demographics

   Input: PROMOTEDatabase

   Output: Table of demographic summary for all PROMOTE participants with a plasma sample, CSV file containing all participants with DNA sample and their demographics

5. PBMC

   Version 2: 2025-01-21

   We updated the queries to reflect the new diagnosis status classification on REDCap.
   
   Version 1: 2024-04-15

   Finds list of participants with PBMC sample and their demographics

   Input: PROMOTEDatabase

   Output: Table of demographic summary for all PROMOTE participants with a PBMC sample, CSV file containing all participants with DNA sample and their demographics
   
7. DNA

   Version 2: 2025-01-21

   We updated the queries to reflect the new diagnosis status classification on REDCap.

   Version 1: 2024-04-02

   Finds list of participants with DNA sample and their demographics
 Iden
   Input: PROMOTEDatabase, Genomic data attained participant list

   Output: Table of demographic summary for all PROMOTE participants with a DNA sample, CSV file containing all participants with DNA sample and their demographics
   
8. Stool

   Version 1: 2024-04-16

   Finds number of stool samples/list of all stool samples, combined with demographic/subtype information, statistics regarding stool sample collection for the PROMOTE project

   Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers

   Output: Table with statistics regarding stool sample collection, CSV file with demographic information for participants with stool samples, CSV file with subtypes for all PROMOTE participants with stool sample, CSV file with all stool samples for which a subtype was not provided (NP), CSV file with number of stool samples per participants and the amount of time elapses between longitudinal samples (for same participant), CSV file for all stool samples donated by cohabs
   
9. Cerebrospinal fluid (CSF)

   Version 2: 2025-01-21

   We updated the queries to reflect the new diagnosis status classification on REDCap.
   
   Version 1: 2024-04-02

   Finds demographic information and dates of all CSF samples collected in the PROMOTE cohort

   Input: PROMOTEDatabase

   Output: Table of demographic summary of participants who have donated CSF samples, CSV file containing all CSF sample dates with the demographics of the donating participant.

11. Discontinuation Query

   Version 1: 2024-06-05

   Finds PROMOTE participants that we have a serum sample for both before and after permanant discontinuation of DMT, using estimate exported from EHR Data in 4/2024

   Input: PROMOTEDatabase, discont_raw.csv (in the relevant .csv files folder of shared OneDrive -> Data Analysis -> Data Queries)

   Output: CSV file with all PROMOTE participants that we have serum sample for both before and after permanent discontinuation of DMT (estimated based on incomplete EHR data), mean (sd) time length between the two samples (most recent before and most recent after)

9. OCT Cleaning Query

   Version 1: 2024-06-05

   Pulls all OCT reports for PROMOTE participants

   Input: PROMOTEDatabase

   Output: CSV file with all OCT reports in the PROMOTE Database
