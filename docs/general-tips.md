---
title: General Tips for All Methods
parent: Working in Teams Using MAXQDA 
created_date: 2023-01-27
staff: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
nav_order: 3
layout: default
---

## General Tips for All Methods

* **Versions:** Normally team members would each be working on their own computers with their own MAXQDA licenses, and all team members need to be using the same version of MAXQDA.
* **User name:** When you first start up MAXQDA, you are prompted to set your user name. Anything you create or change in MAXQDA will be tagged with this user name. This is helpful in team projects to see who did what.
* **Codes:** For inductive coding, the team lead could set up a parent code for each team member, where they could put their suggested codes. At a team meeting, the suggested codes can be discussed and then merged to finalize the code system. If team members create new codes, they should also use a code memo to make notes about the code and provide some examples to remember what it means and when it is used. Some teams also create a "problems/questions" code to flag things they want to discuss in a team meeting. You can also use colours to signal items for discussion. Once a code system is finalized, you could still have an Other parent code for unexpected codes that come up.
* **Communication:** Team members should meet often to discuss the coding, how the project is going, themes emerging, etc. You can also use memos in MAXQDA to record and share thoughts about the project and to store meeting minutes.
* **Test Merge/Pilot:** First try doing a small amount of coding on one or two files, export the changes, and then do an import back into the master project file. This gives you an opportunity to try out the full import/export process and look at the options for comparing multiple coders’ work before getting too deep into the project. 
For some projects, if you are working as part of a team because you want to speed up the coding process by dividing the work, you may want to first test how team members are applying the codebook (or you may be developing your codebook) before launching into the full coding. You could get two people to do a full code of one or two documents using the agreed upon codebook (or proposing codes) and compare the coding (see next section), and then discuss as a team the results and challenges. You may need to do this multiple times with different combinations of teammates to check everyone's coding. In the end, you want everyone on the same page in terms of interpreting the codebook before you divide and conquer the work. This might result in adding more information to the codebook to clarify the meaning and application of the codes, or adding or subtracting codes.
* **Comparing Coding to Determine Intercoder Agreement:** 
After importing project files, you may want to compare different teammates' coding to each other, but remember you need to first set up your project file in a particular way, with duplicate files for each coder, in order to run the [Intercoder Agreement](https://www.maxqda.com/help/coding/problem-intercoder-agreement-qualitative-research) functions. See [the manual way](https://mdlutoronto.github.io/working-teams-maxqda/the-manual-way/) workflow steps for a refresher on the setup.
After importing project files, go to Analysis->Intercoder reliability. You will need to make comparisons between two coders at a time. Select the two document groups containing the duplicate files you want to compare. You then have three options to consider: 
  * Code occurrence in the document: Per document, it is checked whether both persons have assigned the same codes.
    * This option can give you an overall sense of how much agreement there is in the coding. Two tables pop up. One shows you the disagreement by codes and one shows you it by documents. From the document table, you can select "Count unassigned codes as matches" to display the Kappa (RK). You can double click on a cell in that table to bring up the cell matrix browser view to see more details about the frequency of each code used in the document, broken down by each coder. 
  * Code frequency in the document: Per document, it is checked whether both persons have assigned the same codes the same number of times.
    * This option also gives you an overall sense of how much agreement there is in the coding, from a different angle. It is similar to option 1, but it doesn't matter if one code is a lot more frequent or just a bit more frequent, it will show disagreement, and no Kappa is available. 
  * Min. code overlapping rate of X% at the segment level: Per coded segment, it is checked whether the other person has assigned the same code to the segment.
    * **This is the option most commonly used for qualitative coding,** as it not only shows you the differences at the segment level, but allows you to go through each disagreement and decide which one to keep and apply to the final file. Again, it'll open up two windows, one table shows you the overall disagreement by codes and the second table shows you **each segment** by document. For this segment table, you can double click on each row to bring up the document showing the segment (so you should have two tabs one for each coders coding of the document at that contested segment) so you can compare them in detail. You can flip back and forth between the tabs or you can pop out a window (right click on the tab and select View as separate window) so you can view them side-by-side, but you will have to do this each time you are making a comparison. If you decide which coder you agree with for that segment, you can right click on the row you agree with and select Adopt the Solution of Coder X. It will copy that coding into the other file, so that the files match for that coded segment. After you have gone through this process for each segment, you just keep one file (if you've adopted the coding) that has all the coding you want and then delete the duplicate file.

You may then need to do this more times for other comparisons. Once you've completed this process, you would consider this the end of a cycle. You could clean up the master project file, deleting the duplicate files. 
    
Often times, teams will do this process at the beginning on a small sample of documents to finalize a codebook and get all coders on the same page. Then you might start a new cycle of coding, sharing this new master project file with teammates. This time the team might take a divide and conquer approach where each coder works on a set of files that are different than another coder (or a subset of codes). You could always do periodic intercoder reliability checks throughout the project, or again at the end, to double check that you are still on track. 

**Technique:** [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools:** [MAXQDA](https://mdlutoronto.github.io/tutorials-search/?tool=MAXQDA)