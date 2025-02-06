Version Control Lab 2

#Remove dev branch<br>
Local:<br>
git branch -d dev<br>
Remote:<br>
git push origin :dev<br><br>

#Remove test branch<br>
Local:<br>
git branch -d test<br>
Remote:<br>
git push origin :test<br><br>

#checkout another branch without commit changes<br>
git stash<br><br>

#List tags<br>
git tag<br><br>

#Remove tag<br>
Local:<br>
git tag -d v1.7<br>
Remote:<br>
git push origin --delete v1.7<br><br>

<<<<<<< HEAD
![Alt text](img.png)
=======
>>>>>>> origin/main
