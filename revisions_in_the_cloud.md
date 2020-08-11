[[Home](README.md)] [[Growth Mindset](growthmindset.md)] [[What is Markdown?][[Home](README.md)] [[Growth Mindset](growthmindset.md)] [[What is Markdown?](learning_markdown.md)] [[Coder's Computer](coders_computer.md)] [[Revisions in the Cloud](revisions_in_the_cloud.md)] [[Getting Started With HTML](gettingstartedwithhtml.md) [[CSS Beginner Basics](css_basics.md)] [[Dynamic Web Pages With Javascript](dynamic_webpages_with_javascript.md)]
# Using Git to Clone a Repository
![picture of parallel shining lights](images/clone.jpg)
<span>Photo by <a href="https://unsplash.com/@franckinjapan?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Franck V.</a> on <a href="https://unsplash.com/s/photos/clone?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>
## What is Git?
Git allows software developers the ability to manage changes in code during project development. Git has many features such as the ability to track changes made locally on a user's computer and save those changes within project repositories in the cloud.  Teams can work on the same project through branching.  When a user wants to submit a change to a project repository, a command is typed or executed in the computer's terminal. The command saves the file(s) in the master branch in the user's Github account.

## What steps do you take to Clone a Repository and Sync Locally?
1. Open Github and click on the project repository.
2. Click on the green code button and "copy the Clone with HTTPS" URL.
3. Open the terminal and type "pwd" to locate where you are at in the terminal.  Navigate to home if necessary by typing "cd ~".  Navigate to the location where you will copy your cloned repository and type in the terminal (e.g., "cd documents").
3. Next, type "git clone [insert copied repo link]".  This makes a copy of the repository in your current location in the terminal.  If you want to clone within a directory/folder, type the name of the chosen folder immediately after the cloned URL (e.g., "git clone (insert github clone repo link) (insert directory name)")
4. Open Visual Code Studio by typing "code ." and make any changes.  
6. In the terminal, type "git add [insert filename]".  Note:  You may add all changes of all files by executing the "git add *" command.
7. If you want to check the status at any time (recommended after each change) type "git status".
8. To commit a file, type "git commit -m 'description of change'".
9. After that, you mush push this to the github remote repository by typing "git push origin master".
10. Finally, go to the github repository online and check to make sure the changes were made.  This may take several minutes due to server lag.

