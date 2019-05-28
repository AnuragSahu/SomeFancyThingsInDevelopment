# How to Make a Portfolio Website for yourself in Github. 

### Make a github Profile
1. Go to your browser
2. goto github.com
3. sign in with your credentials

### Make a new repo with the name as <username>.github.io
1. On the top right you will see a new icon with "New" Written on it.
2. Click on the icon 
3. In the repository name  write it as <yourusername>.github.io
4. Select a template you want to apply.
#### Or you can clone this repo for a template it is hosted in https://anuragsahu.github.io/SomeFancyThingsInDevelopment/
5. download the template
6. check if the template have any .git file
7. if there is .git file delete it
8. now open terminal and navigate to your current working directory
9. type in the following commands
```sh
sudo apt-get update
sudo apt-get install git
```
verify that git has been installed
```sh
git --version
```
if it give output like "git version 2.9.2"

10. Configure *your* Git username and email using the following commands, replacing Emma's name with your own. These details will be associated with any commits that you create:

```sh
git config --global user.name "Anurag Sahu"
git config --global user.email "anuragsahu926@gmail.com"
```

11.now in terminal type the following commands
```sh
git init .
git add .
git commit -m "First Commit"
git remote add add origin https://github.com/<username>/<username>.github.io.git
git push -u origin master
```
12. Goto settings of your repo and scrol down for Github pages sections and under that select your source to master breanch instead of none.
### Check your portfolio

1. Now that you have put in so much effort onto the website its time you should see the website.
2. Open a new tab on the browser and open
3. <username>.github.io
4. And Tada it is done.

** Also check for any _config.yml change the base url in config.yml file to <username>.github.io
