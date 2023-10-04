# A02

**Branch**
This is used to create a separate version of the original repository. This can be done by inputting “git branch [Name Here]” which will then create a new branch with the chosen name.
**Clone**
This is used to create a copy of what repository you are in at that time. This can be done by inputting “git clone [file name]” which will then clone that specific file.
**Commit**
This is used to create a save in order to confirm the changes done so far. Think of this as a save point in a video game. This can be done by inputting “git commit -m “notes/message” which will then commit the changes done at this point and allow you to leave some sort of message or information relevant to the file/changes.
**Fetch**
This is used to retrieve/gather a file and its changes without changing anything locally. This can be done by inputting “git fetch [rule/parameter] [file name]” which will then gather than information as requested.
**GIT**
Git is commonly known as a version control system. What this means is that it is used to allow multiple people to work on the same project while tracking all changes and code. This is used to help work efficiently and also prevents any loss of data or setbacks because of the tracked changes.
**Github**
Github works along side Git by essentially taking what can be done in Git and putting it onto a website so that the repositories can be accessed of the website and from almost anywhere. 
**Merge**
This is used to connect the changes of multiple branches into one. This can be done by “git merge [branch name]” which will then merge the branch you named in the merge with the current branch.
**Merge Conflict**
A Git merge conflict is when a merge is unable to complete a merge. This tends to happen when the same file is being merged but the file itself has different/conflicting edits. 
**Push**
This is used to upload changes from a local repository to a remote repository. This can be done by inputting “git push [remote repo name] [branch]” which will then upload the changes from the local repository to the remote repository.
**Pull**
This is used to get changes from a remote repository and bring it to the branch on the local repository. This can be done by inputting “git pull [branch]” which will then get the changes and update your local repository.
**Remote**
Remote refers to the type of repository. This is a repository that isn’t on the local machine and is hosted/stored on a different server/machine. 
**Repository**
A repository is a place that stores files and tracks the changes/edits that we made to those files. This holds all the changes and edits so that the user can go back if need be and also helps prevent data loss.

**How to use Git & Github**
	Git is a version control software that allows the user to track changes made on a file so that they are able to not only keep track of those changes but also allows them to go back if need be. 
Step one: Git can be downloaded at https://gitforwindows.org/ which will then prompt you to complete the download manager and finally download Git. I personally use Gitbash to run Git from the command line. 
Step two: Now that git is downloaded we then must go to https://github.com/ and create an account. 
Step three: On GitHub, you will create an account using an email and password of your choosing.
Step four: Once an account is created we must then create and setup a SSH key so that it can link our local machine to Github. Open Gitbash and type “ssh-keygen -t ed25519 -C [your email]”. 
Step five: You must then choose where you want to save the SSH key, but for this just save at the default location. 
Step six: Next, you are going to be prompted to enter a password that you can choose. 
Step sever: Once that is done take the SSH key you got and go to GitHub. Once you are on GitHub then go to your account and then settings. Once in settings choose “SSH and GPG Keys”. 
Step eight: After this go ahead and paste the SSH key into the corresponding area and hit add SSH key. Once this is done you are ready to use Git from your local machine and have it sent over to GitHub.


**How to use WebStorm**
 Webstorm is an IDE that can be used to write, open, and edit code files. 
Step one: Download Webstrom from https://www.jetbrains.com/webstorm/. 
Step two: Once it is being downloaded you can follow the steps provided in the downloader. 
Step three: Once you have followed all the steps provided by the downloader you can then open up WebStorm and go to system preferences. This can be done by pressing Ctrl + Alt + S. 
Step four: Once that is done you are prompted with the system preferences. At this point, you will click “Git” on the left under “Version Control”. Make sure that the path you make end in “git.exe”.
Step five: From here you are able to add a password by clicking “Passwords” under “System settings”. 
Step six: Here you will add the file location for the password file and then click “OK” once you are done. (Using KeePass will be best here). In the end, it should look like “C:\[YourFileAddress]\c.kdbx”. 
	Some basics utilizing Webstorm include clicking the file in the top left corner and then clicking new. Under this, you will find the different file types/coding languages. Choose whichever one you like and then you are able to begin coding. Additionally, you are able to open, rename, and save files all from the “File” tab in the top left corner.

**References**
https://git-scm.com/doc
https://www.jetbrains.com/help/rider/Using_Git_Integration.html 
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh 
https://www.jetbrains.com/help/webstorm/using-git-integration.html#set-passwords-for-git-remotes 
Professor Chiusano’s Slides
  IntroToGitHub Slides
