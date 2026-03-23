# ENGR 103: Programming Questionnaire

## Getting Started

This is your private Git repository for assignment 1, created from a template when you accepted the assignment. Both the TAs and I (the instructor) have access to this repository and can see your work as you push changes.

First, you need to create a local mirror of this repository on the ENGR servers. In studio 2, you learned how to clone repositories from GitHub to create a local mirror. You'll do the same here. Ensure you have already set up SSH keys to authenticate with your GitHub account from your ENGR servers user account. If you haven't done this, complete studio 2 before continuing.

Here's a reminder on how to clone this repository:

1. Click the green "<> code" button at the top right of the main page of this repository.
2. Select the SSH tab if it's not already selected.
3. Click the clipboard button to copy the SSH connection string to your clipboard.
4. Open a terminal and connect to the ENGR servers over SSH.
5. Navigate to the directory where you want to store your programming assignment work for this course using the `cd` command.
6. Run the following command: `git clone <SSH_connection_string>`, replacing "`<SSH_connection_string>`" with the connection string you copied in step 3.
7. Run the `ls` command. You should now see a directory called `getting-started-XXX`, where `XXX` is your GitHub username. Enter that directory using `cd`.

Your terminal's working directory should now be your local copy of this Git repository. If you run `ls` at this point, you should see this assignment description file (`README.md`) as well as `answers.txt`. Use `vim` to edit `answers.txt` as instructed in the next section.

## Assignment

This assignment is not a programming task; you won't be writing any code. Its main purposes are:

1. To help you familiarize yourself with the assignment work and submission process using a terminal, SSH, Vim, Git, and GitHub Classroom.
2. To help me (the instructor) better understand your programming background and goals.

To complete this assignment, use the tools listed above to modify `answers.txt` and provide answers to the following questions:

1. What is your first and last name? (This is important so that we can link your GitHub username to you.)
2. Do you have any programming experience? If so, how much, and what programming languages have you used?
3. Do you have experience writing code in C++?
4. How do you think learning to solve computational problems and write programs could benefit an engineer, regardless of their field?
5. Do you think learning to solve computational problems and write programs could benefit you in everyday life? If so, how?
6. We may have time for a special topics lecture at the end of the term, depending on how the term unfolds. Are there any special topics related to computer science that you're curious about? (e.g., an introduction to machine learning, computer graphics, object-oriented programming, functional programming, frontend development, backend development, databases, cloud development, mobile app development, etc.)

## Submission

Once you've edited `answers.txt` using `vim` to include your answers to these questions, use Git to stage (`git add`), commit (`git commit`), and push (`git push`) your changes to this assignment repository, as you learned in studio 2 and in lecture. After pushing your changes, return to this GitHub repository page (accessible via the assignment link in Canvas) and verify that the `answers.txt` file was updated accordingly. As mentioned, the TAs and I have access to this repository, so simply pushing your changes counts as a formal assignment submission.

> [!NOTE]  
> While you can modify `answers.txt` using GitHub's built-in text editor, we strongly encourage you to use a terminal, SSH, Vim, and Git. These tools will be indispensable for future programming assignments, so it's beneficial to learn how to use them now.
