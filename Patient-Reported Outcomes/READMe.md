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
