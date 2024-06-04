# unit 5

## Build the steps to create a new git local Repository and remote repository.


### Step-by-Step Guide to Create a New Git Local and Remote Repository

#### 1. Install Git
Ensure Git is installed on your system. You can verify by running:

```sh
git --version
```

If Git is not installed, download it from [git-scm.com](https://git-scm.com/) and follow the installation instructions.

#### 2. Configure Git
Set your username and email.

```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

#### 3. Create a New Local Repository

1. **Navigate to your project directory**:
    ```sh
    cd /path/to/your/project
    ```

2. **Initialize a Git repository**:
    ```sh
    git init
    ```

3. **Add your project files**:
    ```sh
    git add .
    ```

4. **Commit the files**:
    ```sh
    git commit -m "Initial commit"
    ```

#### 4. Create a New Remote Repository on GitHub

1. **Log in to GitHub**.
2. **Click on the "+" icon** in the upper right corner and select "New repository".
3. **Fill in the repository details**:
   - Repository name: `your-repo-name`
   - Description: (optional)
   - Public or Private: Choose based on your preference
4. **Click "Create repository"**.

#### 5. Link Local Repository to Remote Repository

1. **Copy the remote repository URL** from GitHub. It looks like `https://github.com/yourusername/your-repo-name.git`.
2. **Add the remote URL to your local repository**:
    ```sh
    git remote add origin https://github.com/yourusername/your-repo-name.git
    ```

#### 6. Push Local Repository to Remote Repository

1. **Push the initial commit**:
    ```sh
    git push -u origin master
    ```

This will upload your local repository's contents to the remote repository on GitHub.

### Summary of Commands

Here’s a summary of the commands used in the steps above:

1. **Initialize a Git repository**:
    ```sh
    git init
    ```

2. **Add files to the repository**:
    ```sh
    git add .
    ```

3. **Commit the files**:
    ```sh
    git commit -m "Initial commit"
    ```

4. **Add a remote repository**:
    ```sh
    git remote add origin https://github.com/yourusername/your-repo-name.git
    ```

5. **Push to the remote repository**:
    ```sh
    git push -u origin master
    ```

### Additional Tips

- **Check the status of your repository**:
    ```sh
    git status
    ```

- **View the commit history**:
    ```sh
    git log
    ```

- **Create and switch to a new branch**:
    ```sh
    git checkout -b new-branch
    ```

- **Merge a branch**:
    ```sh
    git checkout master
    git merge new-branch
    ```

- **Push changes to the remote repository**:
    ```sh
    git push origin master
    ```

## How to deploy your website on heroku using github or git?


### Option 1: Deploying from GitHub

#### Step 1: Prepare Your Code

1. **Push your code to a GitHub repository**.
    ```sh
    cd /path/to/your/project
    git init
    git add .
    git commit -m "Initial commit"
    git remote add origin https://github.com/yourusername/your-repo-name.git
    git push -u origin master
    ```

#### Step 2: Create a Heroku App

1. **Log in to your Heroku account**.
2. **Click on "New"** in the top right corner and select "Create new app".
3. **Fill in the app details**:
   - App name: Choose a unique name
   - Region: Select your region
4. **Click "Create app"**.

#### Step 3: Connect GitHub to Heroku

1. **Navigate to the "Deploy" tab** in your newly created Heroku app.
2. **Select "GitHub" as the deployment method**.
3. **Connect your GitHub account** if you haven't already.
4. **Search for your repository** and connect it.

#### Step 4: Deploy the App

1. **Manual Deployment**: Under "Manual deploy", select the branch you want to deploy (usually `master` or `main`) and click "Deploy Branch".
2. **Automatic Deployment**: Enable automatic deployment if you want Heroku to automatically deploy new commits pushed to the selected branch.

Heroku will now build and deploy your app. You can view the progress and any build errors in the activity log.

### Option 2: Deploying from Git (Heroku CLI)

#### Step 1: Prepare Your Code

1. **Ensure your project is a Git repository**.
    ```sh
    cd /path/to/your/project
    git init
    git add .
    git commit -m "Initial commit"
    ```

#### Step 2: Log in to Heroku

1. **Open your terminal and log in to Heroku**.
    ```sh
    heroku login
    ```

#### Step 3: Create a Heroku App

1. **Create a new Heroku app**.
    ```sh
    heroku create your-app-name
    ```

This command creates a new app and sets up a remote named `heroku` in your Git repository.

#### Step 4: Deploy the App

1. **Push your code to Heroku**.
    ```sh
    git push heroku master
    ```

This command pushes your code to Heroku, and Heroku will automatically build and deploy your app.

### Verification

Once deployed, you can open your app in the browser:
```sh
heroku open
```

You can also view logs to debug any issues:
```sh
heroku logs --tail
```

## Distinguish between Git and GitHub.

![image](https://github.com/ace2884/3-2-shorts/assets/119153850/54da5a70-73c4-4d94-90e7-ea3bd6a23721)


Identify the features and benefits of using Git? 

it is easy to contribute to open source projects via GitHub.

It helps to create an excellent document.

We can attract recruiter by showing off your work. If you have a profile on GitHub, you will have a higher chance of being recruited.

It allows your work to get out there in front of the public.

We can track changes in your code across versions.

### Features of GitHub

GitHub is a place where programmers and designers work together. They collaborate, contribute, and fix bugs together. It hosts plenty of open source projects and codes of various programming languages.

**Some of its significant features are as follows.**

Collaboration

Integrated issue and bug tracking

Graphical representation of branches

Git repositories hosting

Project management

Team management

Code hosting

Track and assign tasks

Conversations

Wikisc



