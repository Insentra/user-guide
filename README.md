# Quick Start Guide for GitHub
This is a resource for information about using GitHub within Insentra, useful links for learning about GitHub and recommended tools. This guide is not intended to be a complete user guide but will contain useful information on getting up and running quickly for anyone new to Git and GitHub.

## About GitHub
Most of our usage within Insentra is likely to be PowerShell related usage as most of us IT Pros; however, additional usage will include repositories hosting Visual Studio code and SQL queries.

Be sure to read the [Insentra usage policy](https://github.com/Insentra/usage-policy) for GitHub.

### Creating a New Repository
When creating a new repository, the following selections are recommended:
* **Repository name** - choose a descriptive yet simplified name
* **Description** - add a short description of the repository
* **Public / Private** - the repository will be private by default
* **Initialise this repository with a README** - this will make it simple to provide some details as to what the repository is for
* **Add .gitignore** - choose an ignore template that matches the project, or close to it. The contents can be changed later
* **Add a license** - choose the MIT license by default

![](https://raw.githubusercontent.com/Insentra/user-guide/master/CreatingNewRepository.png?token=AH2Kf-Y5g_rHdVQK1laoRs0CdIAVY_P4ks5X18xkwA%3D%3D)

### README.md
Initialise each repository with a README.md that includes some information about the code stored in the repository. If the repository is for a specific project, including the project number in the readme will assist with tracking.

### License
It is recommended that an MIT license is added to every repository. Although we won’t be sharing all code publicly, this at least ensures consistency across all repositories.

### .gitignore files
To ensure that certain file types are not automatically synchronised with a repository, [create a .gitignore file](https://help.github.com/articles/ignoring-files/) within each repository.

A basic .gitignore file that should suit most repositories, can be found here: https://gist.githubusercontent.com/octocat/9257657/raw/3f9569e65df83a7b328b39a091f0ce9c6efc6429/.gitignore

For additional customisation, see [the gitignore.io site](https://www.gitignore.io/) that contains templates for a large number of languages.

## GitHub Tools
You can use git from the command line; however, to get up an running quickly GitHub provides graphical tools for local repository management and synchronisation.

The GitHub Desktop application provides a GUI interface to GitHub. You can [clone](https://help.github.com/articles/cloning-a-repository/) repositories right from github.com which will automatically open the repository in the GitHub Desktop app.

### Windows
* [GitHub Desktop](https://desktop.github.com/).
* [Microsoft Visual Studio Code](https://code.visualstudio.com/Docs/?dv=win) is a great alternative to the PowerShell ISE and [includes git integration](https://code.visualstudio.com/docs/editor/versioncontrol). After installing Visual Studio Code, add [the PowerShell extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell). Use the Quick Open command and run:
```
ext install PowerShell
```
* [git command line tools](https://git-scm.com/download/win) for Windows.
* [posh-git](https://github.com/dahlbyk/posh-git) enabled git command line functionality from PowerShell. On Windows 10, open a PowerShell window and run:
```
Install-PackageProvider -Name NuGet -Force
Install-Module posh-git
```
* The [GitHub Extension for Visual Studio](https://visualstudio.github.com/) is available as well.

### macOS
* [GitHub Desktop](https://desktop.github.com/).
* [git command line tools](https://git-scm.com/download/mac) for macOS.
* [Microsoft Visual Studio Code](https://code.visualstudio.com/Docs/?dv=osx) is also available for macOS. After installing Visual Studio Code, add [the PowerShell extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell). Use the Quick Open command and run:
```
ext install PowerShell
```
* PowerShell is now [available for macOS](https://github.com/PowerShell/PowerShell)

### Linux
* [git command line tools](https://git-scm.com/download/linux) for Linux.
* [Microsoft Visual Studio Code](https://code.visualstudio.com/) is available for Linux.
* PowerShell is now [available for Linux](https://github.com/PowerShell/PowerShell)

