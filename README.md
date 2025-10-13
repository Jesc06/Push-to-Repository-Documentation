# Step-by-Step Guide: Push Your Code to GitHub (Using Git CLI)

### 1. Set up your Git identity (only needed once per machine)
```bash
git config --global user.name "Your Name"
git config --global user.email youremail@example.com

```

<br>


### 2. Change directory to your project
```bash

cd path/to/your/project

```

<br>

### 3. Go to main branch
```bash

git branch -M main

```


<br>

### 4. Initialize Git
```bash
git init
```

<br>

### 5. Link your local project to the GitHub repository (set the remote origin)
```bash
git remote add origin https://github.com/username/my-project.git
```


<br>


### 6. Add your changes 
```bash
git add .
```


<br>


### 7. Commit your changes 
```bash
git commit -m "Initial commit"
```


<br>


### 8. Push your code to Github Repo

<br>

If Empty new repo

```bash
git push -u origin main
```

<br>

If the new repository is not empty, it already has a README file.

```bash
git pull origin main --allow-unrelated-histories
```
Then press ESC on your keyboard and type :wq

and Enter

```bash
:wq
```


<br>
<br>

# *Method for adding a branch, switching to the created branch, and pushing it to GitHub.*

#### *1. create branch*

```git
git branch "your branch name"
```

#### 2. *Switch to created branch*
```git
git checkout "your created branch name earlier"
```


#### 2. *Push to github repo*
```git
git push -u origin "your created branch name earlier"
```
