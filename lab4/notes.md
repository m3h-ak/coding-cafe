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

