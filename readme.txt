 ## Upload a Project from Visual Studio Code to GitHub##
 
 To upload your project in GitHub using Visual Studio Code, follow the following steps.

Open the Visual Studio Code. if you don't have the VSCode download.
In VSCode go to File-->Open Folder..
Go to Terminal-->New Terminal
Execute the following commands one by one after one another in order
git init

git add .

git commit -m "First Commit"

git remote add origin https://github.com/yourusername/your-repo-name.git

git push origin master

Note: in the above command git remote add origin https://github.com/yourusername/your-repo-name.git please change the bold sections with your GitHub account name and your repository name.

