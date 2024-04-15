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

6. Functional Assessment of Multiple Sclerosis (FAMS)

   Version 1: 2024-04-09

   Finds all FAMS scores and subscores for the PROMOTE study

   Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers

   Output: CSV file with FAMS total scores and subscores for all PROMOTE participants, histograms of all total scores/subscores, plot with number of FAMS survey responses over time, histogram of earliest FAMS scores

7. Impact of Visual-Impairment (IVIS)

   Version 1: 2024-04-09

   Finds all IVIS scores for the PROMOTE study

   Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers

   Output: CSV file with IVIS scores and subscores for all PROMOTE participants, histogram of IVIS total scores

8. Leisure

   Version 1: 2024-04-09

   Finds all leisure scores for the PROMOTE study
   
   Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2

   Output: CSV file with all Leisure scores (and ages), histogram of all leisure subscores and total scores in young 20's, histogram of all leisure subscores and total scores for most current response, histogram of all leisure subscores and total scores

9. Loneliness
   
   Version 1: 2024-04-09

   Finds all UCLA Loneliness Scale scores for the PROMOTE study

   Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2

   Output: CSV file with all Loneliness scores for PROMOTE participants, histogram of all loneliness scores

11. LongSetUp

    Version 1: 2024-04-09

    Combines the two PROMOTE Longitudinal Projects for use in weekly report and other queries

    Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2

    Output: CSV file with combined Longitudinal projects

13. Modified Fatigue Impact Scale (MFIS)

    Version 1: 2024-04-09

    Finds all MFIS-21 and MFIS-5 scores for the PROMOTE study

    Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers, Sensor, PrePro

    Output: CSV file of all MFIS-21 scores for PROMOTE participants, histogram of all MFIS-21 physical/cognitive/psychosocial/total scores, CSV file of all MFIS-5 scores for PROMOTE participants, histogram of all MFIS-5 total scores

15. Legacy Missing ID Link Code

    Version 1: 2024-04-15

    Code to link missing promote IDs to the legacy PQ/SRO project

    Input: Legacy PQ/SRO, Missing Identifiers

    Output: None (is just a chunk of code that can be copied into new queries using Legacy PQ/SRO)

17. Multiple Sclerosis Severity Score (MSSS)

    Version 1: 2024-04-15

    Scores and transforms all MSSS scores (per MSQIL guide) for the PROMOTE project

    Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers, Covid Longitudinal

    Output: CSV file of all MSSS scores for PROMOTE participants, histogram of all total MSSS scores, histogram of all transformed MSSS scores

19. NEO Five Factor Inventory (NEOFFI)

    Version 1: 2024-04-15

    Scores all NEOFFI questionnaires for the PROMOTE project

    Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, PROMOTE Database

    Output: CSV file of all NEOFFI scores for PROMOTE participants, histogram of each factor (and histogram of the t-score for each factor)

21. NIH Enrollment Report

    Version 1: 2024-04-15

    Generates tables with demographic information required for NIH Enrollment reports for the PROMOTE project

    Input: PROMOTEDatabase

    Output: A table with demographic information for all PROMOTE participants, and a table with demographic information for all PROMOTE MS participants

23. Pain Query (Pain Effects Scale, PES)

    Version 1: 2024-04-15

    This code finds preliminary PES info- # completed, # unique prts. Also finds info for associated measures: social support, anxiety, depression, fatigue

   Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers, Covid Longitudinal, Covid Vaccine, Sensor, PrePro

   Output: CSV file with all PES scores for PROMOTE participants, completion table to generate list of unique participants with at least one PES score

24. Perceived Deficits Questionnaire (PDQ)

    Version 1: 2024-04-15

    Scores all PDQ responses for the PROMOTE project

    Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers

    Output: CSV file with all PDQ responses and total scores, histogram of PDQ total scores, histogram of earliest PDQ response
