# README
This folder lists the supplemental material of the submission titled *In Defence of Visual Analytics Systems: Replies to Critics*.

## Critics.csv
It lists the critics and has the following fields:
- IssueID, Issue: The criticisms
- section: corresponding sections (e.g., Introduction)
- Count: its count in the study 1
- specificity_mean, specificity_std: the mean and average scores for its specificity to VA systems (obtained from the study 2)

## Replies.csv
It stores the interview data and has the following fields:
- IssueID, Issue: The criticisms
- Participant ID
- If get critized, If critized others: interviewees' answers to "did you encounter this criticism when serving as VA system contributors or reviewers", respectively?
- Comments: interviewees' answers to "how can VA researchers respond to those criticisms?"
- Specificity: interviewee' answers to "on a 7-Likert scale, is the criticism not at all (1) or extremely specific (7) to VA systems (R)?"

## VIS21_VASys.csv  
It lists the 30 surveyed paper about VA systems in IEEE VIS 2021:
- DOI
- Authors
- Title

## VIS21_VASys_Sections.csv
It stores our labels about the section titles in surveyed papers.
- secIdx: section index
- secText: section text
- DOI
- ours: our label

## VIS21_VASys_Contributions.csv
It stores our labels about the contributions claimed in surveyed papers.
- Contribution: claimed contribution
- DOI
- Our Labels: our label

## VIS21_VASys_Eva.csv
It stores our labels about the evaluation methods in surveyed papers.
- method: evaluation methods
- num_participants: (if appliable)
- DOI
- measurement