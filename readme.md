git log give all the information of commit changes
git log --oneline give changes information in one line 
we can also use git show "id "  in this id we place taht id present in git log --oneline the id is the first 8 chaarcter of change address commit likha hota haid

firstly we do cd folder name
then git init

we can modify it and then we do git add file name or for all file we do git add .

we can commit using 
<!-- git commit --m "mesaage kuch bhi likh skate ho" -->

<!-- Rever the change  -->
git reset --hard<hash>
git revert <hashcode>
revrt ke baad git add .
phir commit kar do

<!-- How to create branch  -->
git checkout -b <branch-name>

we use git merge name to merge the branch

we use git merge branch name to merge but first of fall we need to back to master branch so we sue
<!-- git checkout master -->

we can also check how many branch are present and which branch am i currently at

<!-- Delete a branch -->
git branch -d branch-name
git branch -D branch-name(unmerged also)

<!-- esq:wq helpful(escape the writing code ,save and quiet) -->

<!-- How to change branch name -->
git branch -m <branch_name>

<!-- Git stash -->
allow you to temporary save your uncomiited change (both staged and unstaged) in a stash and revert working 
directoryback to the last commit

<!-- agar ham chate hai ek cycle na bankar linear change ban jaye to ham branch ka base change kar denge uske liye hame branxh par aana
hoga aur likhna hoga
git rebase master jisse ho jayega
uske baad ham add . karenge par commit nhi katrenge
hame karna hai

git rebase --continue -->


<!-- github me kya karna hai -->

<!-- git remote add origin https://github.com/Prashant1b/Git-Learning.git
 git branch -M main
 git push -u origin main-->

 agar hame main update akrn ahai to
 <!-- git pull origin main -->
<!-- git pull --rebase origin main -->

<!-- git branch -r -->

<!-- git push origin --delete feature -->

