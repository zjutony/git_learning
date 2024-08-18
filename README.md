# Git_Learning
Learning Journey Record
## Normal working stream  
```bash  
git init  
git add . or <file name >  
git commit -m 'commit label'  
git remote add origin <repository github url>  
git push -u origin main or <branch name>  
```  
If you want to reset your **commit**,you can run  
```bash  
git reset --hard HEAD^  # reset to last commit and reset add  
git reset --soft HEAD^  # reset to last commit but remain add  
```
Sometimes I will face the problem like :   
    Failed to connect to github.com port 443 after 21090 ms: Couldn‘t connect to server  
it could be solved by using the **VPN** or build the connection for you shell (**if you have already used the VPN but still suffer from that bug*),you can run:  
```bash  
git config --global http.proxy 127.0.0.1:7890 # 127.0.0.1:7890 is your VPN address  
git config --global https.proxy 127.0.0.1:7890  
```
