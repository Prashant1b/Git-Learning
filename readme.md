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
git branch --d branch-name
git branch --D branch-name(unmerged also)