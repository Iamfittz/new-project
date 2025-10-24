#Setup instructions

## Step 1: Create a new folder
```
mkdir new-project
cd new-project
```
## Step 2: Init a new repository
```
git init
```
## Step 3: Create a README file and make the first commit
```
echo "# new-project" > README.md
git add .
git commit -m "Init commit"
```
## Step 4: Create and switch to a new branch called "development"
```
git branch development
git switch development
```
## Step 5: Add step-by-step instructions to README.md
Open the file directly and add the instructions.
```
git add .
git commit -m "PROM-42164 #comment Added setup instructions"
```
## Step 6: Merge changes back to master
```
git switch master
git merge development
```
## Step 7: Push to GitHub
```
git remote add origin https://github.com/YOUR_USERNAME/new-project.git
git branch -m master
git push -u origin master
git push origin development
```
