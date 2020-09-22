# GitBash Repo

This is a locally created repository using Git Bash & pushed to GitHub.

Even this README.md file was pushed from Git Bash on 22-09-2020.

Here below are the steps used for pushing this README.md file into the repo.

#### Creating README.md file

1.  Create a new text file.

   ![Right Click Menu](Assets/Right%20click%20menu.png)

   ![Creating New text file](Assets/RIght%20click-New%20file.png)

2. Rename the file to this -

   ![Creating README.md](Assets/Creating%20README%20file.png)

3. Follow the following guide to get yourself acquainted to .md files. And put some content in this file.  You can use your regular Notepad editor also to edit these markdown (.md) files.

   [Markdown Guide]: https://www.markdownguide.org/	"Markdown Guide by  Matt Cone"


#### Pushing README.md file to GitBash repo

1. Track your README.md file 

   ![Tracking README.md file](Assets/Tracking%20README.md.png)

   Use the following commands -

   ```bash
   git status
   git add README.md
   ```

2. Commit the changes 

   ```bash
   git commit README.md -m "Added README.md file"
   ```

3. Push your changes !

   ```bash
   git push
   ```

   Make sure you have set remote repository before pushing. Use help command if you get lost

   ```bash
   git help
   ```

   Or

   ```bash
   git help <command>
   ```

   