# Assignment 2 - FCB 2020
### Deadline: 06/10/2020 - 23:59

## Submission procedure

This assignment has to be submitted using GitHub Classroom. This
means that you should have cloned the GitHub repo of this assignment from
the organization account for FCB in the academic year 2020-21 at
[https://github.com/funcompbio2020](https://github.com/funcompbio2020)
using the submission link provided at the FCB Moodle site.

Once you have cloned the GitHub repo which has `assignment-2` and your
GitHub username as repo name, then you can work on it in your local disk
and _push_ your changes whenever you like, but make sure that you have pushed
the last version of your assignment before the deadline. There is no
_submit_ button or any other specific submission procedure or action than
just pushing your changes to you GitHub assignment repo. When correcting the
assignment, the version available at the deadline will be retrieved. If the
first version available is posterior to the deadline, then the mark of the
assignment will have a penalty.

## Description

The goal of this assignment is to provide a ranking of Catalan counties
by their risk of outbreak, largest on top, lowest at the bottom, on the
**most recent date** available in the data you have downloaded. To achieve
this goal you should follow these 3 steps:

  1. Go to the Catalan Health Departament COVID data portal at
   [https://dadescovid.cat](https://dadescovid.cat) and follow the
   downloads link. Click and download the CSV file corresponding to
   the "7 DAY AGGREGATION" for "COUNTIES". **Add the CSV file to
   your local GitHub repo of the assignment**.

  2. Create a shell script called `EPGranking.sh` with a text editor
   and type there the Unix shell commands necessary to produce the
   ranking of Catalan counties by their risk of outbreak.

  3. Once you have created the shell script in step 2, run it as
   follows to create a text file called `EPGranking.csv` containing
   the ranking of Catalan counties by their risk of outbreak, largest
   on top, lowest at the bottom:
   ```
   $ sh EPGranking.sh > EPGranking.csv
   ```
