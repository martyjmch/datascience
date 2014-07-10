Notes about git

package : /usr/local/git/
binary  : /usr/bin/git


Here are some commands I've used so far:

> git config --global user.name "Martin McHugh"
> git config --global user.email "martyjmch@gmailcom"
> git config --list

> git init
> git remote add orgin https://github.com/martyjmch/datascience.git

> git add -A
> git commit -m "first change"   git add -A

> git status

There were some problems.  

Push didn't work at first.  I had to generate a public ssh key on my Mac.  
Here are the instructions:

  https://help.github.com/articles/generating-ssh-keys
  
This helped, but I still needed to to a pull first.  So

> git pull origin master
> git push origin master
