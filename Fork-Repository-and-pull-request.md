# Creating a pull request on GitHub involves several steps:<br />
## 1. Fork the Repository<br />
    If you don't have write access to the repository, you'll need to fork it.
    1.	Go to the repository page on GitHub.
    2.	Click the "Fork" button at the top right of the page. This will create a copy of the repository under your GitHub account.
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
    1.	Go to the original repository on GitHub.
    2.	Click the "Pull requests" tab.
    3.	Click the "New pull request" button.
    4.	Select the branch you pushed your changes to (e.g., my-feature-branch) from your forked repository.
    5.	Compare it with the base branch of the original repository (usually main or master).
    6.	Review the changes to ensure everything is correct.
    7.	Add a title and description for your pull request.
    8.	Click the "Create pull request" button.
## 8. Address Feedback<br />
    The repository maintainers may request changes or ask questions about your pull request. Be prepared to make additional commits to your branch to address this feedback.
## Summary<br />
### • Fork the repository<br />
### • Clone your fork<br />
### • Create a new branch<br />
### • Make changes<br />
### • Commit changes<br />
### • Push to GitHub<br />
### • Create a pull request<br />

