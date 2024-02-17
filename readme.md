# Student's ID: 22FTT1497

- **Student's Email:** [22FTT1497@student.pb.edu.bn]

---

## Table of Contents
- [Week 1](#week-1)
    - [Day 1: January 23, 2024](#day-1-january-23-2024)

- [Week 4](#week-4)
    - [Day 2: February 17, 2024](#day-2-february-17-2024)

## Week 1

### Day 1: January 23, 2024 [9:00am]
- **Objective:** Git installed and using Git Bash (for the following commands) [9:30am]
- *Comments:* It has already been downloaded and installed in the laptop.


- **Objective:** Git version 2.43.0 or higher installed [9:30am]
- *Comments:* How to check if the version installed is 2.43.0 or higher? It is by the command of, "git --version". As this is my logbook, and with evidence, I can confirmed I've got version 2.43.0 installed.

## Week 4

### Day 2: February 17, 2024 [7:32am]
- **Objectives:** Git global username set to student’s name [7:32am]
- *Comments:* By setting the command to, "git config --global user.name "Azie Amiza"".

---

- **Objectives:** Git global email set to student’s PB email [7:33am]
- *Comments:* By setting the command to, "git config --global user.email "22FTT1497@student.pb.edu.bn"".

---

- **Objectives:** Create new folder called “WADT AS1 PT1” using CLI [7:35am]
- *Comments:* First, make sure to place it within the place you wanted it to be. For example, desktop.
- *Comments:* Then, we initialized the empty repository.
- *Comments:* After that, we make a new folder with the command, "mkdir WADT-AS1-PT1"
- *Comments:* To see if there's folder been created, write up the command, "ls". If there's the folder, then it has been successfully created.

---

- **Objectives:** Git initialize the new created folder [7:39am]
- *Comments:* This time, we initialized again the newly created folder by, "git init", command.

---

- **Objectives:** Use nano to create a markdown file called readme.md [7:40am]
- *Comments:* If you want to create the markdown file, all we have to do is to command it by, "nano readme.md".
- *Comments:* Again, it has to be inside the folder.

---

- **Objectives:** In the file readme.md contains properly formatted using markdown [7:43am]
- *Comments:* With the command, "Ctrl + O" + "Enter", to save the file and confirm the name.
- *Comments:* To close the readme.md file, all we have to do is to press "Ctrl + X".
- *Comments:* As you can see from the top of the logbook, I added markdown syntax of ID (heading), Student's Email (bolded), and Horizontal line (---).

---

- **Objectives:** Use git to stage the newly created readme.md file [7:46am]
- *Comments:* To see if it has been commit or not, we can check it from the command, "git status". If it doesn't stated there, it means that the readme.md file hasn't been added/commit.
- *Comments:* If you want to add/commit, then the command for it would be, "git add readme.md".
- *Comments:* Again confirmation if it has been added or not? We check it with the command "git status", command.

---

- **Objectives:** Use git to commit the newly created readme.md with message “readme added” [7:46am]
- *Comments:* Next, we commit readme.md file with message that is with the command, "git commit -m "readme added"".
- *Comments:* How to check if it is in clean working state after committing? It is by, "git status".

---

- **Objectives:** Show git logging history [7:47am]
- *Comments:* To show the loging history, all we have to do is with, "git log" command.

---

- **Objectives:** Create a new branch called “as1” [7:49am]
- *Comments:* As I prefer to do things all at once, I did create a new branch by, "git checkout -b as1", command.
- *Comments:* But there's away to do it one by one. At first, we can create the branch first by, "git branch as1", command.

---

- **Objectives:** Git checkout branch “as1” [7:49am]
- *Comments:* And then, switches it out by, "git checkout as1".
- *Comments:* For those who used command, "git checkout -b as1". There's no need for switching it out again, as it was automatically switching it out.

---

- **Objectives:** Modify readme.md (using nano) and git commit changes [7:53am]
- *Comments:* As usual, modifying will be having markdown syntax. As we goes on, this is what markdown syntax is.
- *Comments:* How to modify it? with the command, "nano readme.md".
- *Comments:* Saving would be "Ctrl + O", and "Enter" for the confirmation.
- *Comments:* As for exiting the panel, it would be "Ctrl + X", command.
- *Comments:* Make sure to add the changes to not lose the files by, "git add readme.md", command.
- *Comments:* After that, we commit the changes with message, "git commit -m "Added Message"", command.

---

- **Objectives:** Git checkout to main/master branch [12:28pm]
- *Comments:* To see whether it is main/master branch, all we have to do is to write up command, "git branch".
- *Comments:* Depending on what type it is, it can be typed in as "git checkout master" / "git checkout main".
- *Comments:* As this is my logbook, mine is master, so I worte the command as "git checkout master".

---

- **Objectives:** Git set a new remote called “upstream” that points to [http://pb.edu.bn/gitserver] [12:31pm]
- *Comments:* To set the new remote, we can do it with the command, "git remote add http://pb.edu.bn/gitserver".
- *Comments:* To verify, if it has been created, we command it with "git remote -v".