# github-cheat-sheet

1- we create a repo on github

2- we need to initalize git repo locally on some directory

    git init

3- we can add gitignore file using (optional)

    echo "xxx" gitignore


4- we define globally who we are by

    git config --global user.email "mohammed.alshareef2002@gmail.com"
    git config --global user.name "Mohammad Alshareef"

5- we add the changes by

    git add .

6- we create our first commit

    git commit -m "First Push"

7- then we need to add git remote origin, we git this link from the git repo after clicking clone button

    git remote add origin git@github.com/mohammad2002m/Quran-forum-graduation-project
    
to get current remote origin

    git config --get remote.origin.url 
    
to remove current remote origin

    git remote remove origin


8- now we should create ssh key using this command

    ssh-keygen -t ed25519 -C "your_email@example.com"

we can get the set email using
    git config user.email
    
#important note: don't name the file keep clicking enter. This will cause a problem and not create .ssh folder

9- then we copy the content of SSH-KEY-NAME.pub 

    clip < DIRECTORY_OF_PUB_FILE

10- add the ssh key to github account

    settings > access > add ssh and gpg keys > add ssh

then paste the content of the file. 

Congratulation 🎉🎉


    

    



