# Steps to setup a repository

### 1. Initialize a github repository in your local folder

```
git init
```

- This command initialize a github repository in your local folder

### 2. Connect the actual repository to the local folder using the repo_url

```
git remote add origin <url_link>
```

- Example: git remote add origin https://github.com/tahooranai20-coder/WebDev_Code.git

### 3. Add the changes in my code to move it to the repository

```
git add .
```
### 4. Commit the changes with a message to move it to the repository

```
git commit -m "what are the new changes" .
```

### 5. Push the changes  to the repository
- if it is for the 1st time: 
```
git push -u origin branch_name(at the bottom of vs code; ex: master)
```

- Otherwise: 
```
git push .
```



