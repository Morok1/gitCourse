#Getting start
git --version

which git  -/usr/bin/git
git add <file/directory name #1> <file/directory name #2> < ... >
git add .

git commit -m

#Adding remote
git remote add origin https://github.com/Morok1/gitCourse.git
git clone https://github.com/username/projectname.git

#config
git config --global user.name "Your Name"
git config --global user.email mail@example.com

#remove global
git config --global --remove-section user.name
git config --global --remove-section user.email

#learning about a command
git diff --help
git help diff
git checkout -h

##Browsing of history 
git log

##
git config --global alias.lol "log --decorate --oneline --graph"






