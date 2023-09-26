# This is for Notes
<style>
    #command{
        color:rgb(153 205 161);
    }
</style>
**mkdir** can be used for creating a directory.
Eg:

>A-9817@LE2049 ~ % cd Desktop
A-9817@LE2049 Desktop % mkdir git_station
A-9817@LE2049 Desktop % cd git_station
A-9817@LE2049 git_station %

><span id="command">$ git staus</span> -
for checking the status of the Local Repo, for know the files changed.


><span id="command">$ git add `filepath`</span> - Used for adding the changes for staging means the changes are prepared as a snapshot prior to adding to the main remote history.

><span id="command">$ git commit -m</span> - Used for committing the added snapshot to the remote Repository. What ever comes after the -m is commit message -> for including a message about the commit. It should be inside " ".

><span id="command">$ git push origin main</span> - Used for pushing the changes in Local to the Remote Repo.
