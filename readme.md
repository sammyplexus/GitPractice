## Overview of tasks

Welcome to your practice session with Git. This practice session tests the following:

1. Cloning a Git repository
2. Adding/committing git files
3. Resolving conflicts
4. Creating new branches
5. Raising pull requests

### Problem statement
A University currently has a manual system of assigning students and professors to courses (they use paper and pen). They intend to transition to a more automated approach in the form of a web application that allows students to choose their courses. Create the underlying database tables for this web application. Here are the constraints below:
In a university, a Student enrolls in Courses. A student must be assigned to at least one or more Courses. Each course is taught by a single Professor. To maintain instruction quality, a Professor can deliver only one course.

### Exercise

1. Clone this repository onto your local machine
2. Create a new branch off the 'main' branch (so first of all ensure you're on the main branch) and call it any name you want
3. Create three new folders: a) erd_diagrams b)db_snippets c)requirements_analysis
4. In your requirements analysis perform a MoSCoW analysis of the problem statement (see problem statement). Here is a link that explains MoSCoW - https://www.productplan.com/glossary/moscow-prioritization/
5. In your erd_diagrams folder, include a erd_diagram represent your database modelling of a problem statement (see problem statement)
6. In your db_snippets, include the corresponding SQL queries as files
7. Push all your changes to your remote branch
8. Raise a pull request to the main branch

### Useful commands

git status
git add <filename>
git commit -m <message>
git log: view history of commits
git branch: see list of branches
git checkout -b <branch name>: create a new branch and then check it out
git checkout <branch name>: check out an already existing branch
git push: push your current local committed changes into your remote repo
