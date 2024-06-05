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

25. PROMIS Fatigue

    Version 1: 2024-04-15

    Scores all PROMIS responses for the PROMOTE project

    Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers, Legacy SNQ, Covid Longitudinal, Covid Vaccine, Sensor, PrePro, PASC

    Output: CSV file with all PROMIS-Physical scores, histogram of all PROMIS-Physical scores, histogram of all PROMIS-Physical scores per year, CSV file with all mediam PROMIS-Physical scores per year, CSV file with all PROMIS-Cognitive scores, histogram of all PROMIS-Cognitive scores, histogram of all PROMIS-Cognitive scores per year, CSV file with all mediam PROMIS-Cognitive scores per year, CSV file with all PROMIS-Depression scores, histogram of all PROMIS-Depression scores, histogram of all PROMIS-Depression scores per year, CSV file with all mediam PROMIS-Depression scores per year

26. Pittsburgh Sleep Quality Index (PSQI)

    Version 1: 2024-04-15

    Scores all PSQI responses for the PROMOTE project

    Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers

    Output: CSV file with all PSQI scores for PROMOTE project, histogram of all PSQI scores

27. Perceived Stress Scale (PSS)

    Version 1: 2024-04-15

    Scores all PSS responses from the Sensor project

    Input: Sensor

    Output: CSV file with all PSS scores from the Sensor project, histogram of all PSS scores

28. Relapses

    Version 1: 2024-04-16

    Creates one long data frame with relapses captured from all sources for the PROMOTE project

    Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Covid longitudinal, PrePro

    Output: CSV file with all relapse dates and types for all PROMOTE participants (who have at least one recorded relapse)

29. Sexual Satisfaction Scale (SSS)

    Version 1: 2024-04-16

    Scores all SSS available for PROMOTE participants

    Input: PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO, Missing Identifiers

    Output: CSV file with all SSS scores for PROMOTE participants, histogram of all SSS scores

30. Alcohol Query

    Version 1: 2024-06-05

    Generates list of all PROMOTE participants with alcohol data (any), then prts with alcohol data and at least one PDDS score, then separates by subject group.

    Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Legacy PQ/SRO

    Output: XLSX file with list of all PROMOTE participants with at least one question answered regarding alcohol consumption, CSV file with list of all MS participants with alcohol data and at least one PDDS score, CSV file with list of all NMO participants with alcohol data and at least one PDDS score, CSV file with list of all MOG participants with alcohol data and at least one PDDS score, CSV file with list of all healthy control participants with alcohol data and at least one PDDS score

31. Covid Longitudinal Outcomes

    Version 1: 2024-06-05

    Finds mean (sd) number of scores/reports per participants for the following outcomes (within the Covid cohort): PDDS, MSRSR, PROMIS cognitive, PROMIS physical, PROMIS depression, SDMT, 9HP, T25W, EDSS, and OCT

    Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, Covid Registry, pdds_all.csv, msrsr_all.csv, promis_physical_all.csv. promis_cognitive_all.csv, promis_depression_all.csv, sdmt_all.csv, hpt_all.csv, footwalk_all.csv, oct_all.csv

    Output: CSV file of Covid Registry PROMOTE participant list, then mean (SD) number of scores for each of the above listed outcomes

32. FFQ Descriptive Stats

    Version 1: 2024-06-05

    Finds total number of FFQs completed, mean (sd) number of FFQs completed by all PROMOTE/PrePro participants, as well as IQR and Median of time elapsed between longitudinal scores for participants that have completed more than 1

    Input: PROMOTEDatabase, PROMOTE Longitudinal 1, PROMOTE Longitudinal 2, PrePro

    Output: Generates number of unique participants that have completed at least one FFQ, how many FFQ those participants have completed, mean (sd) number of scores per participants, and mean, sd, median, and IQR of time elapsed between consecutive FFQs for participants that have completed at least 2

33. FFQ Descriptive Stats

    Version 1: 2024-06-05

    Finds sustained disability progression outcomes for all PROMOTE participants

    Input: PROMOTEDatabase, pdds_all, clinical_demographics

    Output: Generates one of four outcomes for each PROMOTE participants based on PDDS availability:
      0 = had sufficient data to assess, neither sustained increase or decrease
      1 = had sufficient data to assess, sustained PDDS increase (disability worsening)
      2 = had sufficient data to assess, sustained PDDS decrease (disability improvement)
      NA = did not have sufficient PDDS data to assess

33. Relapse Outcome

    Version 1: 2024-06-05

    Finds relapse outcomes (N relapses, annualized relapse rate, time to first relapse) for whatever participant list you enter

    Input: CombinedData (this is the file name you'll see in the code, you can change it to whatever participant list you need. It needs to include id_participant, relapse date, relapse type, and clinical demographic data (dob, date MS dx))

    Output: Generates N relapses, annualized relapse rate, and time to first relapse for all entered participants, exports a CSV file containing all three relapse outcomes
      

