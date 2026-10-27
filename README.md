# GITDemo
GIT commands
git config --list
    credential.helper=manager
    user.name=VikasPalotra
    user.email=vikas.patidar9288@gmail.com

E:\AfterWipro> git --version
        git version 2.53.0.windows.1
E:\AfterWipro> git -v
        git version 2.53.0.windows.1


E:\AfterWipro> git clone https://github.com/VikasPalotra/GITDemo.git
    Receiving objects: 100% (6/6), done.

E:\AfterWipro\GITDemo> git status
    On branch main
    Your branch is up to date with 'origin/main'.

git restore Test.java  //to discard changes in working directory

git add Test.java
git commit -m "Add Test.java file"
git push //not worked so used below
git push origin main

git pull

//show the origin
git remote show origin

Now github to local changes
