--use to test install and version git cli> git --version
--to initialise git use cli> git init
--to know current status of tracking file use cli > git status
--to keep track and add it git use cli> git add .
--now check git status, now file will track color change to green>git status
--now save changes use cli>git commit -m 'Commets about changes'
--to get log use cli> git log

/* 
    git init
    git status  => file changes zalet ka nahi te dakhvt
    git add .   => git cya controll made jate file
    git commit -m "MESSAGE" => breakpoint banto

    git log     => history of commit dakhvto

<<<<<<< HEAD
    git checkout [commitID]  => tya breakpotint(one commint is breakpoint) vr switch karto
    git checkout master     => move to master 
    git branch     => show all branches 
    git branch [BRANCH NAME]     => create branches 
    
=======
    git checkout [commitID]  => tya breakpotint vr switch karto
    git checkout master     => move to master 
    git branch     => show all branches 
    git branch [BRANCH NAME]     => create branches 
    git merge [BRANCH NAME] => merge branch into another branch, first go inside branch and cli and select branch which you want to merge. e.g) there are two branch master and child, you want to merge child into master then checkout to master and fire cli git merge child, by this child merge into master
>>>>>>> master
*/

git branch -D [BRANCH NAME] =>delete branch
git reset --soft [HEAD~1 ]=> rollback commit, change no of head count to how much previous commit want to rollback

/*create git hub site*/
-login to github and create repository
- go inside repository->setting->pages from left menu->select source branch from dropdown and save it will give you site url