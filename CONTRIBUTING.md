# Contributing:
We are glad that you are interested in contributing to our project! Contributions here are made through forking the repository and submitting pull requests. This document will guide you through the process.

There are two sections:
1. Use this section when working with the command line
2. Working with the command line (recommended for the future)

pls note that while creating new branches is optional it is recommended when many people are working on the same thing. You don't have to necessarily create branches though <br>
also please don't make a pull request after each commit. make commits first!

# 1. working directly with the Github interface
## Getting Started
- **Fork the Repository**  
- In the top-right corner of the page, click **Fork**.

### Create a New Branch in Your Fork (optional)
- In your fork, click the **Branch** dropdown menu.
- Enter a name for your new branch.
- Click **Create branch**.

## Making Changes

### Edit Files
- Navigate to the file you wish to change.
- Click the pencil icon in the top right corner of the file view.
- Make your changes in the editor.

### Upload Files
- Navigate (or make and navigate) to the folder where you want to add files in your fork.
- Click **Add file** and then choose **Upload files**.
- Drag and drop the files or click to select the files to upload.
- Once the files are uploaded, you can commit them.

### Commit Changes
- After making changes, scroll down to the **Commit changes** section.
- Enter a commit message that clearly describes your changes.
- Select **Commit directly to the `[your-branch-name]` branch**.
- Click **Commit changes**.

## Creating a Pull Request

### Open a Pull Request
- after commiting, there should be an option to compare and pull request.
- if theres no option of compare and pull request, then there might be an option of "contribute"
- you may have to select which branch to compare with
- if none of the above options are there then pls do follow the steps below:<br>
1. On GitHub, navigate to the main page of the repository.
2. In the "Branch" menu, choose the branch that contains your commits.
3. To the right of the "Branch" menu, click New pull request.
4. Use the base branch dropdown menu to select the branch you'd like to merge your changes into, then use the compare branch drop-down menu to choose your branch.
5. write the message and click Create pull request.

- make your pull request with appropiate title and description. If there are any problems while making a PR pls let us know or please check out [github pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)


# 2. working with command line
forking the repo remains same. <br>

## Clone Your Fork 
- On GitHub, navigate to your fork of the repository.
- Above the list of files, click **Code**.
- To clone the repository using HTTPS, under "Clone with HTTPS", click the clipboard icon.
- Open your command line or Terminal application and enter `git clone [URL of the fork]`.

## Create a New Branch (optional)
- Navigate to the cloned directory. (`cd [Repository-Name]`)
- Use `git checkout -b [branch-name]` to create and switch to a new branch.

## Making Changes
- Make your changes.
- Stage your changes for commit with `git add .` or `git add [file]`.
- Commit your changes with `git commit -m <your commit message>`.

## Push Your Changes
- Push the changes to your fork with `git push origin [branch-name]`.

## Creating a Pull Request
- after commiting, there should be an option to compare and pull request.
- if theres no option of compare and pull request, then there might be an option of "contribute"
- you may have to select which branch to compare with
- if none of the above options are there then pls do follow the steps below:<br>
1. On GitHub, navigate to the main page of the repository.
2. In the "Branch" menu, choose the branch that contains your commits.
3. To the right of the "Branch" menu, click New pull request.
4. Use the base branch dropdown menu to select the branch you'd like to merge your changes into, then use the compare branch drop-down menu to choose your branch.
5. write the message and click Create pull request.

- make your pull request with appropiate title and description. If there are any problems while making a PR pls let us know or please check out [github pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)



## After Your Pull Request is Opened
- Wait for the project maintainers to review your pull request. They may ask for additional changes or clarification.
- If changes are requested, make them on your branch and push them. Your pull request will automatically update.

## Need Help?
If you get stuck or have questions, don’t hesitate to ask for help. You can also open up an issue.

Thank you for your contributions!
