openInBitBucket
===============

A little bash script that I wrote that lets you open a git repo in the browser at bitbucket

*** Instructions ***

To use this script add to a folder in your path. I have a folder called '''.scripts''' in my home directory,
that I have added to my path.

To do this 

'''
cd ~
mkdir .scripts
vim bash_profile
'''
then add 
'''
PATH="PATH=$PATH:$HOME/.scripts" 
export PATH
'''
You then need to refresh your profile
You can do this by typing
'''
source .bash_profile
'''
now just clone repo, or copy https://github.com/oscarmorrison/openInBitBucket/blob/master/openGit
to your new scripts directory
now you need to make executable
'''
chmod 775 openGit
'''

Now all you need to do is go to a bitbucket hosted repo and type
'''
openGit
'''
and it will open your browser to the repo online.

Enjoy!