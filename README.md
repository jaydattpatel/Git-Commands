# Git Commands And Github
<div id="badges">
  <img src="https://api.visitorbadge.io/api/visitors?path=jaydattpatel%2FGit-Commands&label=Visitors&labelColor=%23720026&countColor=%23ffae00" alt="Visitor badge" width="120" height="28"/>
</div>

| Command | Description |
| ------- | ----------- |
| `git --version    ` | check git version |
| `ls -a    ` | list all files with hidden files or folder |
| `git config --global user.name {"username"}` |     set user name in local git |
| `git config --global user.email {"email"}` |   set user email in local git |
| `git config --list` |     show all Git config properties throughout all the variously scoped Git files |

| Command | Description |
| ------- | ----------- |
| `git init ` |  create empty git repository folder |
| `git status` |   check status of files |
#### status-untracked : created new files that git does not track
#### status-modified : files modified which are commited track files
#### status-staged : files ready to commit from stage
#### status-unmodified : not modified any file

| Command | Description |
| ------- | ----------- |
| `git clone {Github_Repo_URL}` |    copy GitHub file to local pc |
| `git clone ssh://git@github.com/[username]/[repository-name].git` |   create a local copy of a remote repository |

| Command | Description |
| ------- | ----------- |
| `git add {file_name}` |    add file in stage from working directory. |
| `git add .` |      add all files in stage from working directory. |
| `git add -A` |    add all new and changed files to the staging area |

| Command | Description |
| ------- | ----------- |
| `git commit -m “{Message for Changes}”` |      commit files from the stage into local directory. |
| `git rm -r {file-name}` |     remove a file (or folder) |

| Command | Description |
| ------- | ----------- |
| `git remote add origin {Github_Repo_URL}` |    set GitHub repository as origin to push |
| `git remote -v` |     check remote origin |

| Command | Description |
| ------- | ----------- |
| `git push origin {branch_name}` |      push committed files to origin branch of remote Github. |
| `git push -u origin {branch_name}` |   push committed files to origin branch of remote Github. ‘-u ’ to remember branch so  next time we can omit ' origin branchname ' . we just use git push.|
| `git push` |   push committed file to remembered origin branch |

| Command | Description |
| ------- | ----------- |
| `git pull` |  update local repository to newest commit |
| `git pull origin {branch_name}` |     update local repository from modified remote github repository. |

#### `master` branch is default branch in local git 
#### `main` branch is default branch in remote GitHub repository
| Command | Description |
| ------- | ----------- |
| `git branch` |     check branches (asterisk denotes the current branch) |
| `git branch -a` |      check all branches local and remote. |
| `git branch {branch_name}` |   create new branch |
| `git checkout -b {branch_name}` |      create new branch and switch to it |
| `git branch -d {branch_name}` |    delete branch |
| `git push origin –delete {branch_name}` |      delete remote branch |
| `git branch -m {old_branch_name} {new_branch_name}` |      rename local branch |
| `git branch -m  {new_branch_name}` |   rename current branch |
| `git checkout {branch_name}` |     switch to branch |
| `git checkout -` |     switch to last checked out branch |

| Command | Description |
| ------- | ----------- |
| `git diff` |   compare working file with stage file |
| `git diff --staged` |      compare staged file with last commited file |
| `git diff {source_branch} {target_branch}` |  preview changes before merge |

| Command | Description |
| ------- | ----------- |
| `git log` |    check all commited logs. |
| `git log --summary` |     check all logs in details. |
| `git log --outline` |     check all logs in briefly. |

| Command | Description |
| ------- | ----------- |
| `git checkout {commit_ID}` |   get committed file using commit id. |
| `git checkout {file_name}` |   get last committed file. |

| Command | Description |
| ------- | ----------- |
| `git checkout -f` |    recover all commited files. |

| Command | Description |
| ------- | ----------- |
| `git merge {branch_name}` |    merge branch to current branch |
| `git merge {source_branch} {target_branch}` |     merge source branch into target branch |

| Command | Description |
| ------- | ----------- |
| `git reset {file_name}` |     reset staged file to commited file. |
| `git reset` |      reset multiple staged files to commited files. |
| `git reset HEAD~1` |  set head to second last commited. |
| `git reset {commit_ID}` |     set head to specific commited ID. |
| `git reset --hard {commit_ID}` |  set head to specific commited ID and reflects in file. |

# Fork repository and make a pull request on GitHub :<br />
## Steps:<br />
####     • Fork the repository
####     • Clone your fork
####     • Create a new branch
####     • Make changes
####     • Commit changes
####     • Push to GitHub
####     • Create a pull request

## 1. Fork the Repository<br />
    If you don't have write access to the repository, you'll need to fork it.
    1.  Go to the repository page on GitHub.
    2.  Click the "Fork" button at the top right of the page. This will create a copy of the repository under your GitHub account.
## 2. Clone the Repository<br />
    Clone the forked repository to your local machine.
        git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
        cd REPOSITORY-NAME
## 3. Create a New Branch<br />
    Create a new branch for your changes.
        git checkout -b my-feature-branch
## 4. Make Your Changes<br />
    Edit, add, or remove files in your local repository as needed.
## 5. Commit Your Changes<br />
    Commit your changes with a meaningful commit message.
        git add .
        git commit -m "Description of changes"
## 6. Push Your Changes<br />
    Push your changes to your forked repository on GitHub.
        git push origin my-feature-branch
## 7. Create a Pull Request<br />
    1.  Go to the original repository on GitHub.
    2.  Click the "Pull requests" tab.
    3.  Click the "New pull request" button.
    4.  Select the branch you pushed your changes to (e.g., my-feature-branch) from your forked repository.
    5.  Compare it with the base branch of the original repository (usually main or master).
    6.  Review the changes to ensure everything is correct.
    7.  Add a title and description for your pull request.
    8.  Click the "Create pull request" button.
## 8. Address Feedback<br />
    The repository maintainers may request changes or ask questions about your pull request. Be prepared to make additional commits to your branch to address this feedback.


