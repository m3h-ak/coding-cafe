Lab 4 Notes



Question 1

`--global` means that the name and email settings apply to Git for my user account, rather than just one repository. If I left it out, the settings would only apply to the repository where I ran the command.



Question 2

The `.git` directory appeared in `ls -a` but not normally in `ls`. It contains Git's internal information, including the repository's history and configuration.



Question 3

Git was offering two entries to track: `README.md` and the `week02/` folder. The `week02/` folder may contain files that I did not write myself.



Question 4

After creating `.gitignore`, the files inside the `.venv/` directory no longer appeared in `git status` because Git was now ignoring them. The other files, including `README.md`, `week02/`, and `.gitignore` itself, were still shown as untracked.



Question 5

`.gitignore` should be committed because it is part of the project and tells Git which files should be ignored. If it were ignored too, other people using the repository would not automatically have the same ignore rules.



Question 6

`README.md` moved from “Untracked files” to “Changes to be committed.” In the three-places model, this means the file moved from the working directory to the staging area, ready to be included in the next commit.



Question 7

Git created the first commit with the message “Lab work so far” and reported that 4 files changed, with 140 insertions. The four files were `.gitignore`, `README.md`, `week02/lab01-log.txt`, and `week02/notes.md`.



Question 8

The first seven characters of my commit hash are `2adaf82`. They are a short version of the commit's unique hash, which Git can use to identify and refer to that specific commit.

 Question 9

The four steps are edit, stage, commit, and check the history. I make or change a file, use `git add` to stage it, use `git commit` to save the change as a new version, and then use `git log` to view the history.



&#x20;Question 10

README.md has a special name because GitHub automatically displays it on the repository's front page. It gives visitors an immediate overview of the project, while a file such as notes.md does not have this special role.



&#x20;Question 11

`gh auth login` authenticated GitHub CLI with my GitHub account and stored an authentication token for Git operations. This means Git can authenticate with GitHub when I push without asking me for my GitHub password each time.



&#x20;Question 12

The README.md file is showing on the repository's front page, with the Markdown rendered as formatted text. It appears there because GitHub automatically displays a repository's README as its main introduction and overview.



&#x20;Question 13

No, pushing did not change my local history. The same commits are still present locally; `git push` copied those commits to the remote GitHub repository.



&#x20;Question 14

A private repository still exists on GitHub but can only be accessed by people who have been given permission. If the repository did not exist on GitHub at all, there would be no online repository for the TAs to access or review.

