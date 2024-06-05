# Creating a pull request on GitHub involves several steps:<br />
## 1. Fork the Repository<br />
    If you don't have write access to the repository, you'll need to fork it.<br />
    1.	Go to the repository page on GitHub.<br />
    2.	Click the "Fork" button at the top right of the page. This will create a copy of the repository under your GitHub account.
## 2. Clone the Repository<br />
    Clone the forked repository to your local machine.<br />
    git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git<br />
        cd REPOSITORY-NAME<br />
## 3. Create a New Branch<br />
    Create a new branch for your changes.<br />
        git checkout -b my-feature-branch<br />
## 4. Make Your Changes<br />
    Edit, add, or remove files in your local repository as needed.<br />
## 5. Commit Your Changes<br />
    Commit your changes with a meaningful commit message.<br />
        git add .<br />
        git commit -m "Description of changes"<br />
## 6. Push Your Changes<br />
    Push your changes to your forked repository on GitHub.<br />
        git push origin my-feature-branch<br />
## 7. Create a Pull Request<br />
    1.	Go to the original repository on GitHub.<br />
    2.	Click the "Pull requests" tab.<br />
    3.	Click the "New pull request" button.<br />
    4.	Select the branch you pushed your changes to (e.g., my-feature-branch) from your forked repository.<br />
    5.	Compare it with the base branch of the original repository (usually main or master).<br />
    6.	Review the changes to ensure everything is correct.<br />
    7.	Add a title and description for your pull request.<br />
    8.	Click the "Create pull request" button.<br />
## 8. Address Feedback<br />
    The repository maintainers may request changes or ask questions about your pull request. Be prepared to make additional commits to your branch to address this feedback.<br />
## Summary<br />
### • Fork the repository<br />
### • Clone your fork<br />
### • Create a new branch<br />
### • Make changes<br />
### • Commit changes<br />
### • Push to GitHub<br />
### • Create a pull request<br />

