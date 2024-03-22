
create folder
git init
git checkout -b djangotut
git commit -m "Initialising project"
git clone "https://github.com/mycloud1503/djangotut.git"

git init                                                           // start tracking current directory
git add -A                                                         // add all files in current directory to staging area, making them available for commit
git commit -m "commit message"                                     // commit your changes
git remote add origin https://github.com/username/repo-name.git    // add remote repository URL which contains the required details
git pull origin master                                             // always pull from remote before pushing
git push -u origin master                                          // publish changes to your remote repository


########## START PYTHON STEPS ###########
# download and install python 
# install django by using command
    pip install django
    Note: we are not using django rest framework for now, we are trying to create apis without rest framework.

###########################

########## RUN SERVER #############
python manage.py migrate
python manage.py runserver

