---
title: The Manual Way
parent: Working in Teams Using MAXQDA 
created_date: 2023-01-27
staff: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
nav_order: 1
layout: default
---

## The Manual Way

### Overview

To work as a team in MAXQDA, one person needs to be designated the project lead to manage all the files. They would set up the MAXQDA master project file. Then they would share copies of the master project file with team members. Team members would work on their copy. After they have done their work, they would export their project changes and send that back to the project lead. The project lead would then import those changes back into the master project file.

### Basic Steps of the general workflow

[Detailed steps](https://www.maxqda.com/help/teamwork/transferring-coded-segments-memos-variables-etc-from-one-project-to-another) can be found in the [MAXQDA Manual](https://www.maxqda.com/help/welcome), but here is an overview of the process.

1. The project lead sets up a MAXQDA master project file, adding all the documents needed, setting up codes along with their code memos and hierarchies (if a codebook has been agreed upon ahead of time), and setting up other details, such as document variables

### Optional: For intercoder agreement checks, the set up is slightly different (skip if not checking for intercoder agreement)
{:style="counter-reset:step-counter 1"}
1. Pick a file or files you want multiple people to code to compare
1. Create a document group for each person (minus the team leader who can work on the master project file)
1. Put copies of the files you want people to code in those folders (You will need to import the files, you can’t just copy/paste.)

### Continue with the general workflow
{:style="counter-reset:step-counter 4"}
1. Save the master project file and give teammates a copy of the master project file with their initials in the file name
1. Teammates work on their project file, and team leader works on the master project file
1. When the work is done, the teammates should export their project changes to a MQEX file, picking the documents that they made changes to and all the codes, using the Home->Teamwork->Export option
1. The team leader should make a backup copy of the master project file before importing anything
1. The team leader should then import each MQEX file using the Home->Teamwork->Import feature 

### Optional: For intercoder Agreement checks (skip if not checking for intercoder agreement)
{:style="counter-reset:step-counter 9"}
1. Once the changes have been imported, the team leader can run the [Intercoder Agreement](https://www.maxqda.com/help/coding/problem-intercoder-agreement-qualitative-research) functions to see how teammates' coding compares to each other and then decide which coding to keep. Once all changes have been agreed upon and applied to the files, you can then delete the duplicate files (double check the files that you are keeping to make sure you have all the changes before deleting). More information and tips about Intercoder Agreement are found in the [General Tips](https://mdlutoronto.github.io/working-teams-maxqda/general-tips/) section
1. Once the team is happy with intercoder reliability and feels that everyone is on the same page, you can start a new cycle. The difference is that you don’t need repeated files now. You could use document groups to specify which person should work on which files, if you like. Then the steps can be repeated to code and exchange work. But now when it is imported, as different files were worked upon by different people, there’s no worries about overwriting changes or needing to merge two people’s changes through intercoder agreement functions

### Continue with the general workflow
{:style="counter-reset:step-counter 11"}
1. In a project, there may be many rounds of coding. The team lead can decide to start a new cycle, where you have a new updated copy of the master file (with some coding already done) that is then shared out again to teammates for more coding. Start at step 5 and repeat the work again, as many cycles as needed

### Clarifications and Tips

* **Merge vs Import/Export:** There are two ways to merge projects in MAXQDA: [Using the merge project option or the import/export options](https://www.maxqda.com/help/teamwork/can-maxqda-support-teamwork). The [merge project option](https://www.maxqda.com/help/teamwork/merging-two-maxqda-projects) is only used if you want to merge non-document specific items, such as a free memo, into a project or if someone is adding more documents/transcripts, etc. to a project after the initial setup. The [import/export option](https://www.maxqda.com/help/teamwork/transferring-coded-segments-memos-variables-etc-from-one-project-to-another) described above are traditionally more what a team wants to do on a project - merge teammates coding changes into one project file. If you are familiar with NVivo, you might be confused by this terminology. 
* **What imports and doesn't:** Generally the rule with importing changes is that the most recent change will overwrite an older change, if there's a conflict (which is why you need to have duplicate files if you want to use Intercoder Agreement to see the differences in coding and decide on which change to keep). Except when you import the MQEX file, even if the teammate exported code memos, code memo changes will not overwrite the code memos in the master project file. Same with a project memo - the master project file's project memo will remain untouched. New memos (where there's no conflict) with be imported, though.
* **Sharing Copies of the Master File:** How you share/transfer your master file and copies will depend on how large your project file is and if you have to keep it secure. Depending on the situation, you could use U of T’s services, such as [OneDrive](https://easi.its.utoronto.ca/shared-services/office365/onedrive/) or [Sharepoint](https://easi.its.utoronto.ca/shared-services/office365/sharepoint/).
* **Back up and File Names:** It is recommended that you always make a backup of the master project file before you do any importing, in case the project file is corrupted during the import (very rare), or you want to roll back to a previous version of the project. Follow a file naming convention, such as appending the date to the file name. There could **also** be a lot of copies of the team members' MQEX files, so make sure to again establish and follow a file naming convention, such as appending a team members’ initials and the date to the file names.
* **Local Files:** [MAXQDA](https://www.maxqda.com/) recommends that ideally you work off a copy of your project file stored locally on your computer instead of working off a file stored on a network drive, external drive, or cloud storage service. If the project file isn’t local, there is a potential that it could get corrupted. Another reason to have lots of backups! 

Consult MAXQDA's help pages for more information on [backing up project files](https://www.maxqda.com/help/the-workspace/backups).

**Technique:** [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools:** [MAXQDA](https://mdlutoronto.github.io/tutorials-search/?tool=MAXQDA)