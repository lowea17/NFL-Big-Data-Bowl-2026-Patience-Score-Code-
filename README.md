Patience Score
A Tracking-Based Metric for Defensive Discipline in Downfield Pass Coverage

Big Data Bowl 2026 — University Track

-------------------------------------------------------------------------------------------------------------------------------
Code

This repository contains the implementation of the Patience Score, a motion-based metric designed to 
quantify how long a defender delays their directional reaction toward the ball after quarterback release.

The analysis notebook is located in the notebooks folder.

Supporting images and documents used can be found in the other directories included in this repository.

To reproduce the results, open and run in Kaggle:
notebooks/patience-score-submission.ipynb

Before running, you need to download the Dataset we used and upload it into a created dataset in your Kaggle Workbook 
by clicking "add input" and naming it full-dataset, then uploading the file into it.

The file is available as a GitHub release in this repository or through the link below
[Download FINISHED_MasterSheet.1.xlsx](https://github.com/lowea17/NFL-Big-Data-Bowl-2026-Patience-Score-Code-/releases/latest)

-------------------------------------------------------------------------------------------------------------------------------
Abstract

Patience is a core defensive trait on downfield pass plays. When the ball is released, defenders face a 
moment of decision: whether to hold leverage or commit early toward the catch point. Traditional coverage 
metrics evaluate outcomes—such as completions, yards allowed, or interceptions—but they do not measure 
this process of reaction timing.

Using NFL Next Gen Stats tracking data, we introduce Patience Score, a continuous metric that captures how 
long a defender waits before initiating directional movement toward the ball’s landing point. By comparing 
the defender’s orientation and movement profile from the moment of ball release forward, the metric
identifies a precise “reaction moment” and converts it into a normalized measure of patience across man 
and zone coverage schemes.

Our findings show that patience is both measurable and meaningful. Defenders known for disciplined coverage 
such as Marshon Lattimore, Xavier McKinney, and Jack Campbell—exhibit strongly negative (more patient) 
scores, while more aggressive players trigger earlier and show higher variability. Further, patient 
defenders recorded significantly more interceptions in our sample, suggesting that delayed commitment may 
improve leverage and contestability. Comparison with external sources, including PFF’s highest-graded 
cornerbacks of 2023, reinforces that Patience Score reflects real, film-supported defensive behavior.

We view Patience Score as a step toward evaluating coverage technique directly from tracking data, offering 
coaches, analysts, and researchers a new lens into defensive movement quality during the ball-in-air phase.

-------------------------------------------------------------------------------------------------------------------------------
Citation
If you use or reference this work, please cite:

Patience Score: A Motion-Based Metric for Defensive Discipline in Downfield Pass Plays.
Andrew Lowe, AJ Kurke, Big Data Bowl 2026 — University Track.

-------------------------------------------------------------------------------------------------------------------------------
Contact
For questions or collaboration:

Andrew Lowe
GitHub: https://github.com/lowea17
LinkedIn: https://www.linkedin.com/in/andrew-lowe-9abb79324/

AJ Kurke
LinkedIn: https://www.linkedin.com/in/ajkurke/



