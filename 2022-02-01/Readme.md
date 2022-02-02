Feb 1, 2022 - Abby Tyrell's Ecosystem and Socioeconomic Profiles Report Workflow

12AM PT/3PM ET/10AM HI NMFS R User Group - Abigail Tyrell - NOAA Affiliate(NEFSC) will share code and workflow/process insights on her work contributing to Ecosystem and Socioeconomic Profiles produced by the NEFSC and AFSC! Add this meeting to your calendar!
Participate where there is a yellow highlight!

## Announcements

* AI data call - quick turnaround. Link to email instructions (feds only) Jordan Watson - NOAA Federalhas the deets!
* A free Bayesian modeling course coming up! Applications due Feb 15. https://www.nrel.colostate.edu/projects/bayesian
* rOpenSci Community Call for R and OpenScience in Government: https://github.com/ropensci-org/community-calls/issues/26#issuecomment-1004913495
* Government Advances in Statistical Programming conference is next week. Here is the schedule and link to register (free). https://nces.ed.gov/fcsm/pdf/Program_Virtual_Workshop.pdf
* Elizabeth Holmes - NOAA Federal NOAA NMFS Xaringan theme for some upcoming talks and drafted a theme by adapting @Christine Stawitz - NOAA Federal 's https://github.com/nmfs-fish-tools/presentations theme and adding in some css from https://rstudio-conf-2020.github.io/design-ds-classroom/.  Here's the repo: Feel free to copy, adapt, or add material to this repo via a pull request. https://nmfs-openscapes.github.io/xaringan-nmfs/
* Machine Learning/Artificial Intelligence to Advance Earth System Science workshop - National academies of science. February 7, 10 & 11
https://www.eventbrite.com/e/machine-learningartificial-intelligence-to-advance-earth-system-science-tickets-211782094947
* PSAW III: learn more here and sign up here! We’ve added calendar events for these workshops to the NMFS R users calendar. 
* HPC resources available through Schmidt Ocean Institute: We are pleased to announce our continued interest in providing our high-performance computer (HPC) (details provided here) to support pioneering ocean research and data science projects.  We seek project ideas interested in harnessing the potential of the system in support of their oceanographic research. Successful proposals will demonstrate a cogent plan to maximize the HPC, a team capable of meeting the technical goals, and a research question in line with the Strategic Framework of our Foundation. Limited logistical support for successful proponents to access and engage the infrastructure will be provided.  The investigative team must address its own technical and/or software developments and analysis.
To express interest in this opportunity:
Respond to proposals@schmidtocean.org with a maximum of two pages proposal of the work to be deployed on the HPC, written in English, with body text typed in single-spaced 12 point font
Complete this short submission form
 Schmidt Ocean Institute staff will review the received proposals and may schedule a call with you to discuss your plans in further detail. Proposals will be accepted beginning Friday, January 14, 2022 and then on an ongoing basis until the compute power of the HPC is fully utilized.


## Upcoming meeting

* Feb 15 10 HI/12 PT/3 ET: RStudio Connect test
Christine Stawitz - NOAA Federal (OST) -  We want to test the ability of the RStudio Connect instance to scale to multiple users. As such, we wanted to set up a time for us to try to use a bunch of the Shiny apps on there simultaneously. Join to learn more about the NMFS R Shiny Connect instance and see if we can break it!
* Upcoming meeting: March 8 10 HI/12 PT/3 ET: Confidential data and GitHub
Adyan Rios - NOAA Federal (SEFSC) will talk about the SouthEast Data, Assessment, and Review (SEDAR) is dealing with confidential data used in projects on GitHub. She'll talk about various tools and processes to prevent confidential data or secrets from being committed to repos.
* Upcoming meeting: March 29 10 HI/12 PT/3 ET: Data & Code QAQC with Erin Steiner
Erin Steiner - NOAA Federal(NWFSC) runs a data collection program where she collects cost and participation info from Commercial fishers, processors, and quota owners. She will present two types of markdown tools they have developed to QA their data and communicate with participants. Finally, she'll present some data flow challenges the team has encountered and hopefully facilitate a discussion of how others have resolved those issues. 

## Today’s meeting: Feb 1st 10 HI/12 PT/3 ET: NEFSC Ecosystem and Socioeconomic Profiles.

Abigail Tyrell - NOAA Affiliatewill share code and workflow/process insights on her work contributing to Ecosystem and Socioeconomic Profiles produced by the NEFSC and AFSC! https://github.com/atyrell3/AKesp  [Slides NOAA access](https://docs.google.com/presentation/d/14CnVSQOp2q171obKH1gHHb1bBBblGWLsuMEkPXbFCxU/edit#slide=id.p) [Video NOAA access](https://drive.google.com/file/d/1JDJolN2wPOQR55vE4eBiDCEAnJNTEZp9/view?usp=sharing)
 
### Questions

KS: it's a bit hacky, but I very recently discovered that it is easier (for me) to format nice tables and figures and use all the cross-references with the bookdown::pdf_document2 output, then using Acrobat to export as a Word Doc, vs. trying to make a good looking output straight to Word. It may not play nicely with flextable, but I'd be curious to try.

Table of contents: KS: as Tracy mentions, \listoftables and \listoffigures in the pdf output makes table and figure content lists really easy

TM: Do you do QA/QC before creating the plots? *Nope, not at this stage in the process*

TM: So you have to edit each report that is run? *Yes, but minimal copy/pasting.*

AO: Were you able to build-in 508 compliance with your RMarkdown output? *No, but yes where she can!*

TM: If the text doesn't change much from report to report, can you pull that data in like the images?

Em: I would say so! I often keep static text in the rmarkdown doc and text I will need each time but will be slightly different beyond what my code can estimate in google docs and pulling from there. 
 
EH: In practice, how to you update the text each year? Do team members edit the Rmd? *Port to Google docs for editing*
