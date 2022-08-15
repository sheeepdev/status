## Are you updating? Use these commands

Download your site with all the directories. `git clone --recursive <your repo link goes here>`

Update the cState theme submodule. `git submodule foreach git pull origin master`

In the parent directory, type `hugo serve`. Check to see if everything is working.

Then do `git add -A; git commit -m "Update cState"; git push origin <branch, probably main or master>`. Your status page is now updated and uploaded.
