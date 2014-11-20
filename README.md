open-git-in-web
===============
A small bash script that opens a repo corresponding webpage hosted at either Github or Bitbucket. 

This is useful if you quick want to change some repository settings, add collaborators, or anything else that you need the web interface for. 

## Instructions ##

To use this script add to a folder in your path. I have a folder called '''.scripts''' in my home directory. 
It is important to then add this to your path (.bash_profile or .bash_rc)

First you need to create a scripts (hidden) directory and add this directory to your path such that terminal will be able to make use of the script automatically. 

```
cd ~
mkdir .scripts
vim bash_profile
```

then add 
```
PATH="PATH=$PATH:$HOME/.scripts" 
export PATH
```
You then need to refresh your profile
You can do this by typing
```
source .bash_profile
```

Next you need to clone or download the script:

clone repo:    `https://github.com/oscarmorrison/openInBitBucket/blob/master/openGit`
or download zip: `[ download ](https://github.com/oscarmorrison/open-git-in-web/archive/master.zip) `
to your new scripts directory
now you need to make executable
```
chmod 775 openGit
```

Now all you need to do is go to a bitbucket hosted repo and type
```
openGit
```
and it will open your browser to the repo online.

Enjoy!
