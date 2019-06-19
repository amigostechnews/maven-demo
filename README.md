Command line instructions

Git global setup
git config --global user.name "Sridhar"
git config --global user.email "smaddineni@e-pragati.in"

Create a new repository
git clone git@172.19.137.94:E-Highway/Alfresco-Upload.git
cd Alfresco-Upload
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder
cd existing_folder
git init
git remote add origin git@172.19.137.94:E-Highway/Alfresco-Upload.git
git add .
git commit -m "Initial commit"
git push -u origin master

Existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin git@172.19.137.94:E-Highway/Alfresco-Upload.git
git push -u origin --all
git push -u origin --tags