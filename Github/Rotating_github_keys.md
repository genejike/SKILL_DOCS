## Step by Step guide 
- click on your user icon
- <img width="302" height="84" alt="image" src="https://github.com/user-attachments/assets/73dc760d-a182-443f-91db-8d5dc37c43b7" />
- click on settings 
- navigate and click  the developer settings
- click on the personal access token
- select either the tokens classics or the fine grained tokens and allocate to the right github account with permissions 
- if its the token classic
- on your server use the
  ```
  git remote set-url origin https://<username>:<token>@github.com/x/x.git
  ```
- To persist it use
  ```
  git config --global credential.helper store
  ```
- For fine grained tokens
- It will always prompt the username and password
- The username is github name eg  genejike and password is the fine grained token 
  
