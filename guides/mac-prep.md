# lfz-environment-setup

## Mac OS

## Prep Class for Full Immersion Program


The following is a step by step guide to setting up the LearningFuze coding environment, which you will be using for all LearningFuze-related exercises, challenges, and coding activities.

If you experience any issues during the setup process, please reach out in the proper `question queue` Slack channel for your course to receive instructor assistance. We are here to help!!!

1. Submit your Github name in the primary Slack channel for your class. **THIS STEP IS MANDATORY TO BE ABLE TO CONTINUE THE SETUP PROCESS**

1. Download and install the Google `Chrome` browser if you do not already have it installed.
    - The LearningFuze programs use the `Chrome` browser exclusively.
    - Install link: https://www.google.com/chrome/?brand=CHBD&gclid=EAIaIQobChMIkfDJ9pei6AIVpBitBh0F5gqFEAAYASAAEgIAkvD_BwE&gclsrc=aw.ds
1. Download and install the `Zoom` Desktop client.
    - Zoom will be used for all remote classes and all remote student help.
    - Install link: https://zoom.us/download
1. Using the instructions located in the `lfz-code` repository, install `VS code` and `git` / `git bash`.
    - Installation instructions for `Mac` users: https://github.com/Learning-Fuze/lfz-code#macos-instructions
    - Installation instructions for `Windows` users: https://github.com/Learning-Fuze/lfz-code#windows-instructions
    - **NOTE:** The LearningFuze programs use a specially configured version of `VS code`. If you already have `VS Code` installed on your system, and you did not get it from us, you will **need** to delete it during the setup process.
        - Note: Instructions for both `Mac` and `Windows` have both automatic installation and manual installation instructions.
        - If you are unable to complete automatic installation, please install using the manual instructions.
        - **NOTE:** If you see the example screen below when following one of the above links, there are two possible reasons:
            - You are not logged in to `Github`
                - Logging in will fix this
            - You have not been added to the `Github` team.
                - Give your `Github` name to an instructor so you can be added to the team.
        - Example output:
        ![github 404](./images/404-example.png)
1. When the above installation, either manual or automatic is complete, you must confirm that git (on `Mac`) / git bash (on `Windows`) was installed correctly.
    - On `Mac`, open the `Terminal` application, and type `git` into the command line and press `enter`.
    - On `Windows` open the `Git Bash` application, and type `git` into the command line and press `enter`
    - If `Git` has been properly installed you should see the following output in the command line window:
        - Example output:
        ![terminal example](./images/terminal-example.png)

    - What you are seeing is a list of `Git` commands, this means installation is complete.
    - If you do not see the above output, contact an instructor for assistance!!
1. When the above installation is confirmed, it is time to confirm that `VS Code` is installed correctly.
    - Open `VS Code` and confirm that the bar on the bottom of your window is black:
        - Example `VS Code` screen:
        ![example vs code](./images/vs-example.png)
        - Example of black bar:
        ![example black bar](./images/vs-bar-focus.png)
    - If the bar is not black, contact an instructor so that they can assist you with getting the proper build of `VS Code`.
1. When the above installation is confirmed, it is time to install the `Slack` app.
    - The desktop/laptop application is required for all `LearningFuze` programs as it is much easier to miss notifications when using the web application.
    - Installation downloads link: https://slack.com/downloads/
    - After installation is complete, make sure to open the application and log in to confirm you are in the proper `LearningFuze` workspace.
1. When the above installation is complete and you are properly logged into `Slack`, it is time to `fork` the `Github` repository which contains all of the exercises and resources for the class. Please choose the link below which matches your class, either the LFZ Prep Course or Module 1 of the Part Time Program. **Please note that you will only be following one of the below links, corresponding to the class you are currently completing this guide for.**
    - Link for LFZ Prep lessons repo: https://github.com/Learning-Fuze/lfz-prep-lessons
    - Link for Module 1 lessons repo: https://github.com/Learning-Fuze/lfz-mod-1-lessons
    - Watch the video below on forking a repository:
        - Forking Video: https://youtu.be/pRhr2Ia6i70
1. When the above forking is complete, it is time to configure `Git` with your name and email so that it can correctly track and manage the code you will be working on in this and other LearningFuze programs.
    - Watch the video below on configuring `Git`:
        - Git config video: https://youtu.be/kdwH4680WuA
1. When `Git` has been properly configured, it is time to create the `lfz` directory which will hold the repository for this class.
    - Watch the video on creating the `lfz` directory: https://youtu.be/39qZ0oGc1a4
1. When you have successfully created the `lfz` folder, it is time to clone down the GitHub repository that you forked in step 8 and create your first git branch.
    - Watch the video on cloning down the forked repo and creating git branches: https://youtu.be/rmh9DpuUeCY
1. When the repository has been properly cloned, it is time to use `VS Code` to open the files of the repository and to create a new folder and a new `index.html` file which will hold some example `HTML` code.
    - Watch the video on using `VS Code` to open repositories and create new files and folders: https://youtu.be/UjFYiByVtiM
1. When you have been able to create your `index.html` file and open it correctly in the browser, it is time to use `Git` to save your file changes to the example branch and push that branch to Github so you can make a pull request to have your code checked by an instructor.
    - Watch the video on using `Git` to push your code to Github: https://youtu.be/n6MmLhWMSuw
1. When you have been able to successfully add, commit, and push your changes to the `example` branch on `Github` it is time to go back to the `master` branch and add the `upstream` url which will be used to update your forked version of the repository.
    - Watch the video on adding the correct `upstream` url: https://youtu.be/VNGj9jJpexo
1. When you have completed setting the upstream url, it is time to create a pull request on Github.
    - Watch the video on creating a pull request on Github: https://youtu.be/BmEU47GRcYo
1. When the pull request has been made and you have posted it in the correct `pull-requests` channel, congratulations!!! your setup process is completed. Please let your instructor know that you have completed the process, and get ready to become the coder you have been dreaming of!!!
