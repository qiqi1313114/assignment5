# Assignment 5
### Principal Component Analysis

In the attached files you will find instructions for assignment 5. Please **fork** this repository to your own Github account and then clone it in RStudio.

For assignment 5 we will be using data from the Assistments Intelligent Tutoring system. This system gives students hints based on how they perform on math problems. We want to see if we can build a decision tree to help teachers decide which students to follow up with, based on students' performance in Assistments. We will create three groups ("teacher should intervene", "teacher should monitor student progress" and "no action") based on students' previous use of the system and how many hints they use. To do this we will be building a decision tree using the "party" package. The party package builds decision trees based on a set of statistical stopping rules.

The instructions to Assignment 5 are in the Assignment 5.rmd file. Assignments are structured in three parts, in the first part you can just follow along with the code, in the second part you will need to apply the code and in the third part is completely freestyle, apply your new knowledge in a new way. 

**Please complete as much as you can by 5:00pm, 11/25/20**

Once you have finished, commit, push and pull your assignment back to the main branch.

Good luck!


# Codebook
id - student id
prior_prob_count - The number of problems a student has done in the system prior to the surrent session  
score - The score the student achieved in the current session  
hints - The number of hints the student requested in the current session  
hint.y - Whether or not the student asked for hints in the current session  
complete - Whether or not the student completed the cirrent session  
action - The action suggested by the system to a teacher about a given student based on their performance
