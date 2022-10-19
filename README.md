# Bioinformatics

(CMPSC 300) Activity 06

This repository contains information about Bioinformatics Activity 06: schooling your colleagues about skills obtained from watching tutorials.

## Dates

Handed out: 19 Oct 2022

Due: 21 Oct 2022

## Important links
  + Playlist
    + https://www.youtube.com/playlist?list=PL7dF9e2qSW0azL2xOKAtxDW7QI8UU4XZ6

  + NCBI Minute: Enhancements to BLAST and Primer-BLAST
    + https://www.youtube.com/watch?v=LnkNhyTz4lo


  + NCBI Minute: Updated BLAST rRNA Databases for Identification
    + https://www.youtube.com/watch?v=I45-mmXM84U


  + NCBI Minute: QuickBLASTP - Rapidly Find High-scoring Protein Matches
    + https://www.youtube.com/watch?v=pO_a4e7QGRk


  + NCBI Minute: Using organism (taxonomic) information with standalone BLAST
    + https://www.youtube.com/watch?v=c-pFrvX5Aiw


## Instructions

You and your group are to study one of the above videos to give a presentation over one or two _main_ skills gained from the tutorial. The videos are to be assigned in class to have one video per group. Be sure to discuss the tutorial with your group for the group presentation discussed below.

### Presentation

At the next class meeting, you are to give a professional-looking presentation where you teach your colleagues some of the skills that you gained from watching the video. In addition, you are to give a live demonstration where you show how to complete one or two operations which were discussed in the tutorial.

Your demonstration will be about ten minutes where you discuss the one or two main skills taken from the tutorial. You are to have about five slides in addition to your live demonstration for your presentation.

## Working in Your Repository

As you are working on your assignment, you are to commit and push regularly. The commands are the following.

```
git add -A
git commit -m ``Your notes about the commit here''
git push
```

After you have pushed your work to your repository, please visit the repository at the GitHub website (you may have to log-in using your browser) to verify that your files were correctly sent.

## Instructions

Please see your notes and the slides from today's course for notes on how to complete code for each of the tasks below.

+ Create a database to contain the following information.
  - ID
  - Organism
  - DNASeq
  - Protseq
+ Add at least four rows of data (this data can be real or made-up)
+ Offer two queries to two different types of information from the data.

### Deliverable

Please complete the sections of the File: `writing/reflection.md`

## GatorGrade

You can check the baseline writing and commit requirements for this assignment by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python3 installed (type `python --version` to check). If you do not have Python installed, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, if you have not done so already, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Assessment

This grade is a check mark.
