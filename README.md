# SIADS593
SIADS593 Repository for Code

## Jupyter Notebooks Setup
### Within GitHub
1. Within GitHub, click on your profile image in the top right and click settings
2. On the left side of the screen, scroll all the way down to the bottom and click "<> Developer Settings"
3. On the left side of the screen, click "Personal access tokens" and then click the classic one
4. Click "Generate new token" and copy it somewhere where you can refer back to it

### Within Jupyter Notebooks
5. Open your terminal and type in: git clone https://github.com/milleau98/SIADS593.git
7. Type in your user name
8. Paste your access token NOT your password
9. Once the repository is downloaded, navigate to the left side of the screen and click on the git icon
10. Click new branch and create it based on origin/development and name it whatever you want but please include your user name so that we know whose repos are whose
11. You now have a branch created locally in Jupyter Notebooks that you can do your work in

### Once you want to send the work back to GitHub
1. Navigate back to the git icon in Jupyter Notebooks
2. In the "Untracked" section, hover over the file you wish to track and then click on the "+"
3. Type in your summary
4. Click commit
5. Click on the cloud icon in the top with the up-arrow to push to GitHub

### Pulling the data into the development branch
6. Once the data is pushed to GitHub, go to GitHub
7. Click Pull requests in the top banner
8. Click "New pull request"
9. **IMPORTANT:** For some reason GitHub has the requests go from right to left. Think of it as you are sending the data from a source to a target. So, the source would be your branch (right side) and the target is the development branch (left side)
10. Click Create pull request
11. Click Create pull request again
12. Assuming there are no conflicts, click Merge pull request. If there are conflicts, then those must be resolved before the Merge pull request button allows you to click on it
13. After that, everything is merged. You can optionally delete your branch
