Using R to Make a Workflow More Efficient: Work Environment Survey
========================================================
autosize: true

![BC Stats](Workflow_V01-figure/bc_stats_man.png)

Stephanie Yurchak   
October 11, 2018



Background
========================================================
type:prompt

Similar to the BC Public Service Work Environment Survey (WES), BC Stats runs several smaller surveys to external clients

Two main report types:

![BCPS WES report](Workflow_V01-figure/bcps_overall.png) ![BCPS WES work unit table](Workflow_V01-figure/bcps_workbook.png)


Initial state of these projects
========================================================
type:prompt

Process:

![initial software](Workflow_V01-figure/initial_software.png)

Issues:

1. Run by different employees at BC Stats
  + Minimal standardization
  + Lack of version control
2. Report generation done by an individual IT resource for all projects

Tackling Version Control/Standardization
========================================================
type:prompt

- Template project folders

![folder structure](Workflow_V01-figure/folder_structure.png)

- Template syntax in SPSS and Excel files with updatable formulas 

![excel formulas](Workflow_V01-figure/concat_formulas.png)

Results:
- Clearer direction on steps required for data processing and reporting
- Shortest time with least issues for report generation by in-house IT in 12 years!
 

Report generation: Work unit tables
========================================================
type:prompt

- Packages: haven, xlsx
- Inputs: SPSS dataset, Excel "Questions" file
- Customization: at the top of the program, or with Excel inputs
- Output: Formatted excel tables with multiple tabs, auto filters and freeze panes

![r code](Workflow_V01-figure/check_files_setup.png)

Report generation: Work unit tables
========================================================
type:prompt

![unform response](Workflow_V01-figure/wu_response_log.png)

![form response](Workflow_V01-figure/RR_tab.png)

Report generation: Work unit tables
========================================================
type:prompt

![unform driver](Workflow_V01-figure/wu_driver_log.png)

![form driver](Workflow_V01-figure/eng_tab.png)

Report generation: Work unit tables
========================================================
type:prompt

![unform scores](Workflow_V01-figure/wu_scores_log.png)

![form scores](Workflow_V01-figure/score_tab.png)

Report generation: PDF reports
========================================================
type:prompt

How to recreate our highly formatted report appearance?

With R and LaTeX!

![percentile](Workflow_V01-figure/percentile.png) ![engagement states](Workflow_V01-figure/eng_states.png)

Current state of these projects
========================================================
type:prompt

Initial Process:

![initial software](Workflow_V01-figure/initial_software.png)

Current Process:

![current software](Workflow_V01-figure/current_software.png)


Conclusion
========================================================
type:prompt

Workflow enhancements:
- Clear direction and consistency across projects run by different people
- No longer reliant on one person to produce all reports

Next steps:
- Using Rprojects and git for version control
- Extracting survey data from CallWeb directly into R for data processing
- Looking at web based reporting in R

![desired software](Workflow_V01-figure/desired_software.png)


Thanks!
========================================================
type:prompt

Any questions?

![questions](Workflow_V01-figure/questions.jpg)

Stephanie.Yurchak@gov.bc.ca
