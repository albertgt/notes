# notes

basic concepts in using git:
1. create a repo yourself 
2. clone this repo using 
    ````
    git clone http://url.to.your.repo
    ````
3. create your own file in your local repo folder 
4. add this new file to git using 
    ````
    git add .
    at the main folder level (this will also add recursively any new files in subfolders)
    ````
5. commit this new file using 
    ````
    git commit -m "i am a comment" 
    ````
6. push this new file to the remote repo using 
    ````
    git push
    ````
7. validate your new file has appeared at the remote repo using your web browser

8. get latest remote repo files using 
    ````
    git pull
    in the main folder
    ````
9. if you have messed up your local repo 
     and just want to pull latest from remote repo use
        ````
        git reset --hard
        then 
        git pull
        (this will lose any changes!)

        if you want to save ur changes first you can use 
        git stash 
        then the hard reset

        later if you want to apply your changes use 
        git stash apply
        ````

