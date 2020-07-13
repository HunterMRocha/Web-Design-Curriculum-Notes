# How to use Github :) 

## STEP 1: make sure you create a folder for all your code

<img src="assets/createfolder.png" alt="drawing" width="500" height="300"/>

## STEP 2: Now that I've created the folder "needMyCode" with all my code inside of it, I'm going to go ahead and create a github repository.

<img src="assets/githubrepo.png" alt="drawing" width="1000" height="600"/>

### your screen should look something like this. You don't need to click 'initialize this repo. with a README" because we will do that in the next step.

## STEP 3: open your terminal and navigate to the proper directory. Below is a table with some basic commands
### Since my code is inside another folder called "testing" inside of "needMyCode" I'm going to navigate into that directory

<img src="assets/terminal.png" alt="drawing" width="1000" height="600"/>

| Descriptions | Windows | Mac |
| :---: | :---: | :---: |
| Change Directories: | cd | cd |
| List Directories: | dir | ls |
| Move out of a Directory: | cd . | cd . |
| Clear Terminal: | cls | clear |

## Step 4: Copy and Past this command into your terminal/command prompt (Note: you must be inside the folder you want to link with your repository)

<img src="assets/githubcommand.png" alt="drawing" width="1000" height="600"/>

```
echo "# add description of your project here" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/HunterMRocha/Web-Design-Curriculum.git
git push -u origin master

make sure you change the fifth line to match your link. The fifth line is going to be the link to your github repo so make sure you use yours, not mine. or else it won't work
```

## Step 5: Once you paste the above command inside your terminal just press enter and you should be good to go :) 

| Github Command Description | Github Commands | 
| :---: | :---: | 
| Add a single file: | git add index.html | 
| Add all files: | git add . | 
| Commit a message | git commit -m "insert description of changes" | 
| pushing your files and message: | git push | 

