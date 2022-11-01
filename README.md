# machine_learning_project

creating conda environment
'''

conda create -p venv python==3.7 -y
'''

'''
To Add files to git
'''

OR
'''
git add <file_name>
'''

>Note :to ignore file or folder from git we can write name of file/folder in .gitigmore file.

To check git status
'''
git status
'''
To check all version maintained by git
'''
git log
'''
To create version/commit all changes by git
'''
git commit -m "message"
'''
To send version/changes in github
'''
git push origin main
'''
To get remote url
'''
git remote -v
'''
To set up CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = pranalirjagtap1999@gmail.com
2. HEROKU_API_KEY = 2d2fcd5f-d481-42d2-b03b-88fa38ccda8d
3. HEROKU_APP = ml-project12



BUILD DOCKER IMAGE
'''
docker build -t <image_name>:<tagname> .
'''
> Note :- The image_name should be always written in small letters.

