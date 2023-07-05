1. Most of the instructions can be done after reading [the powerpoint](https://github.com/Ben-Drucker/PNNL-Internship-2023/blob/main/Resources/DeepKS%20Slides%20Link.md). You can, of course, ask me for help, but see if you can locate the relevant command(s) there first/online/stack overflow. It is expected that this process may be a challenge. 
2. Create a new folder/directory somewhere on your computer
3. Initialize this folder as a new git repository.
4. Create a new GitHub repository. Add this repository as a remote to the folder/directory you created in step 1. (You can find the remote URL on the GitHub repo creation page)
5. Push some content to the remote
6. Create a new branch locally and induce a conflict in some content.
7. Fix the conflict using the merge workflow in the PowerPoint. **Make sure to** take a screenshot of the following items and, at the end of this tutorial, upload them to your repo:
    - [ ] The git graph before attempting to fix the conflict
    - [ ] The conflict message in the terminal
    - [ ] The git graph after completed merge/fixing the conflict
9. Repeat steps 6 through 8 (only last screenshot needed), this time making a pull request rather than following the whole merge workflow. Make sure to still delete the secondary branch you created in step 6 both locally and remotely. Additionally, **Make sure to** do the following:
    - [ ] Add me as a reviewer
    - [ ] Make an informative comment
10. At this point, you should just have the `main` branch remaining locally and remotely. For the next task, in the git graph settings panel <img src = "images/git-graph-buttons.png" height = "16pt"></img> (middle button), check <img src = "images/reflog-commits.png" height = "16pt"></img>
11. Make several commits on `main`, but pretend you need to reset back to a previous point in history to undo something. Hint: you can get individual commit hashes by right clicking an entry in the git graph. **Make sure to**:
    - [ ] Screenshot the top of the git graph that shows going back in history, and upload at the end.
12. Reset `main` back to the most recent commit.
13. Pretend you forgot to add a file to the last commit. Amend the commit with the forgotten file. Push to origin.
14. Add, commit, and push all necessary screenshots, ensuring each file has an informative filename.

**Nice work! You're a git expert now!**
