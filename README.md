#Steps to push local file to remote

*First on local go to your project directory
*Clone your local directory to local

$ git clone https://github.com/username/sample

*copy/update your local updated file to the cloned folder structure
*commit the file changes

$git commit -a -m "comments"

*run $git status
*run $git push origin master

#### Other way are stated here:
* used the pull command ($ git pull origin master) which again throws the next error message saying git would refuse to merge unrelated histories.
This can be overcome by using the parameter --allow-unrelated-histories

Now, after this, if you use the git push -u origin master, you can upload the file on to Github.

* I used command
>>>'git push -u origin —all"
to push my changes for the first time. I performed a pull once I sync the repo with local before I made any changes.
