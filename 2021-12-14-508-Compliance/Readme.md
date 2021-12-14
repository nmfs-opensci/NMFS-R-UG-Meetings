# Notes from the session

[Full meeting notes with the chat - NOAA access only](https://docs.google.com/document/d/1mrgtrSXVtPCTxrpBa_0ZbxEsnK9vcQzs6RIV3f-OTPw/edit#bookmark=id.a4g6djxgdqcz)

[Link to slides on Google Drive - NOAA access only](https://docs.google.com/presentation/d/1PBJJs6o_9LMjJffCj5zjGwjUA0oGAXGicfukN6E_EKE/edit?usp=sharing)
or [See PDF of slides in this repo](https://github.com/nmfs-openscapes/NMFS-R-UG-Meetings/blob/main/2021-12-14-508-Compliance/A%20Brief%20Overview%20of%20Section%20508%20Compliance%20-%20final.pdf)

# 508 Compliance from the Editor’s Perspective

9AM PT/12 ET NMFS R User Group discussion and tutorial about how to manually make documents 508 compliant and best practices we may be able to adapt to report writing in R. 

Kelly Mayo (NMFS Office of Science and Technology) will be giving a 1 hour tutorial and discussion about manually (via Adobe Acrobat) editing reports to be 508 compliant and talk about how we can use screen readers to check our work. 
Through this tutorial, we hope that we can learn more about the 508-ing process and will be better able to adapt these lessons to our workflows in R and other languages. By understanding what makes a document 508 compliant and the process editors have to go through to make them 508 compliant, we can help folks across the agency make better products, better collaborate with their comms teams, and save everyone time. 

## What do we need to do better?

As you watch Kelly’s presentation, take notes here about what best practices you want to remember, what you didn’t realize, and ideas on solutions. Please “+1” anything you agree with or additional commentary! Perhaps we can use this to update our wiki on the GitHub organization?

## General

* 508 components
* Tagged content - allows screen reader to recognize content
* Reading order - should be logical
* Headings
* Tables
    * Accessibility checkers require that every table has column headers. 
    * Accessibility checkers can also read row headers. The reader would then read “column X row 2 A ####” 
    * Blank cell above untagged a column of what should be row headers will cause issues for screen readers. There shouldn’t be any blank cells in a table
    * Merging across a row is bad (horizontal merging). Merge across a column instead (vertical merging).
* Alt text
* Bookmarks - required for documents >20 pages
* Color contrast
* File properties


## PDF-specific resources for checking 508 compatibility

* Video from NOAA library about the Adobe Acrobat accessibility checker: https://www.youtube.com/watch?v=4JqWmpbAbMg
* There is an accessibility checker tool that (for me) is along the toolbar on the right of my screen when I open a document in adobe (this is the same one as the bullet above!).

## Word-specific resources for checking 508 compatibility

* In Word, go to the View tab → Properties → Inspect document → Check accessibility

## Screen readers

* NVDA: https://www.nvaccess.org/download/ NVD that seems to be the most popular one, followed by JAWS and VoiceOver

## 508 Resources

* NOAA library has a 508 checklist
* Check for 508 compliance with an accessibility checker, screen readers, and self-check
* NOAA Central Library Section 508 Compliance Quick Start Guide https://libguides.library.noaa.gov/Section508/QuickStart  
* Alternative text for complex images  https://www.w3.org/WAI/tutorials/images/complex/ 
* NOAA Central Library Accessibility Checklist: PDF Documents https://libguides.library.noaa.gov/ld.php?content_id=61618926 
* Section508.gov  https://www.section508.gov/ 

## Questions

* Does the NOAA library or NOAA somewhere else have a checklist of which 50 elements are covered by which automated checkers? It seems like we could save a lot of time if we know which things we can rely on automated tools to check and which ones we don’t.
* Example from the presentation: [Fisheries Economics of the US Report, 2017](https://www.fisheries.noaa.gov/resource/document/fisheries-economics-united-states-report-2017)



