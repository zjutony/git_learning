# git_learning
Learning Journey Record
## Normal working stream  
'''bash  
{  
git init  
git add . or <file name >  
git commit -m 'commit label'  
git remote add origin <repository github url>  
git push -u origin main or <branch name>  
}  
'''  
if you want to reset your commit,you can run  
'''bash  
{  
git reset --hard HEAD^  # reset to last commit and reset add  
git reset --soft HEAD^  # reset to last commit but remain add  
}  
'''  
