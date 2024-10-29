After Downlading the CSV file in the GitHub_task folder, terminal was opened and following commands were used to push the file:-

cd ~/GitHub_task
git init
git add Employee.txt
git config --global user.email "debug0197@gmail.com"
git config --global user.name "chirag"
git commit -m "Commiting CSV file"
git pull --rebase origin master
git remote -v //repo already added 
git push -u origin master

FILE SUCCESSFULY PUSHED
