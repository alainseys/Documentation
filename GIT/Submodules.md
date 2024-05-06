# Submodules

If you want to add a new submodule to your existing git project just follow these stems 

1. Clone your master repo
2. cd in your master repo
3. git clone your sub repo
4. add the sub repo to your main repo (git add . , git commit -m "add new submodule", git push)

Now you have added your submodule to your master repo if want to keep track of your commits in your subrepo you need to checkin your changes from the sub repo in te main repo you can use the script in this folder called `UpdateSubmodule.sh` (update the path and the repo) and you can add this script as an alias for ease of use.
When you run the script the changes will be checked it.
