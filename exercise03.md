# Exercise 3 - Configuring your first repository

1. Enable color

        git config --global color.ui auto

2. Set your name

        git config --global user.name "John Doe"

3. Set your email address

        git config --global user.email "john.doe@somewebsite.com"

4. Why did we use the `--global` flag?  (What does that do?)

_______________________________________________________________________________________

The --global flag allows the user to modify the variable outside of the current scope.


5. Check your git config to show the changes you have made

        git config -l

_______________________________________________________________________________________

diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
color.ui=auto
user.name=John Doe
user.email=john.doe@somewebsite.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/keepitgross/msac-lab6.git     
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main
PS C:\Users\miago\OneDrive\Documents\Breanna\Code Files\msac-lab6> 

