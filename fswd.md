# unit 1

Sure, I'll cover each of these topics in detail:

### 1. Canvas and SVG in Detail

#### Canvas
The `<canvas>` element is used to draw graphics on a web page using JavaScript. It provides a means for drawing graphics via scripting (usually JavaScript). It can be used for rendering graphs, game graphics, or other visual images on the fly.

##### Example Program using Canvas
```html
<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;">
Your browser does not support the HTML5 canvas tag.
</canvas>

<script>
var canvas = document.getElementById("myCanvas");
var ctx = canvas.getContext("2d");
ctx.fillStyle = "#FF0000";
ctx.fillRect(0, 0, 150, 75);
</script>

</body>
</html>
```

#### SVG
SVG (Scalable Vector Graphics) is an XML-based markup language for describing two-dimensional vector graphics. SVG is used to define graphics for the Web, providing high-quality images that are scalable and easy to animate.

##### Example Program using SVG
```html
<!DOCTYPE html>
<html>
<body>

<svg width="100" height="100">
  <rect width="100" height="100" style="fill:rgb(0,0,255);stroke-width:1;stroke:rgb(0,0,0)" />
</svg>

</body>
</html>
```

### 2. Web Storage in Detail

Web Storage provides a way to store data on the client side. It comes in two flavors:
- **Local Storage**: Stores data with no expiration date. Data will persist even after the browser is closed.
- **Session Storage**: Stores data for the duration of the page session. Data is lost when the page is closed.

#### Example Usage of Web Storage
```html
<!DOCTYPE html>
<html>
<body>

<h1>Web Storage Example</h1>

<button onclick="storeData()">Store Data</button>
<button onclick="retrieveData()">Retrieve Data</button>
<p id="result"></p>

<script>
function storeData() {
    localStorage.setItem("name", "John Doe");
    sessionStorage.setItem("age", "30");
}

function retrieveData() {
    var name = localStorage.getItem("name");
    var age = sessionStorage.getItem("age");
    document.getElementById("result").innerHTML = "Name: " + name + ", Age: " + age;
}
</script>

</body>
</html>
```

### 3. Differences Between HTML and HTML5

![image](https://github.com/ace2884/3-2-shorts/assets/119153850/47be880e-ebcb-4dfb-9cb9-c0d06e25d8dd)


### 4. HTML5 Elements  Video and Audio

#### Video Element
```html
<!DOCTYPE html>
<html>
<body>

<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

</body>
</html>
```

#### Audio Element
```html
<!DOCTYPE html>
<html>
<body>

<audio controls>
  <source src="audio.mp3" type="audio/mp3">
  Your browser does not support the audio element.
</audio>

</body>
</html>
```

### 5. HTML Code for Drag and Drop

```html
<!DOCTYPE html>
<html>
<head>
<style>
#div1 {
  width: 350px;
  height: 70px;
  padding: 10px;
  border: 1px solid #aaaaaa;
}
</style>
</head>
<body>

<h2>Drag and Drop Example</h2>
<p>Drag the image into the rectangle:</p>

<img id="drag1" src="img_logo.gif" draggable="true" ondragstart="drag(event)" width="336" height="69">

<div id="div1" ondrop="drop(event)" ondragover="allowDrop(event)"></div>

<script>
function allowDrop(ev) {
  ev.preventDefault();
}

function drag(ev) {
  ev.dataTransfer.setData("text", ev.target.id);
}

function drop(ev) {
  ev.preventDefault();
  var data = ev.dataTransfer.getData("text");
  ev.target.appendChild(document.getElementById(data));
}
</script>

</body>
</html>
```

### 6. Geolocation

The Geolocation API allows the user to provide their location to web applications if they so desire. It can be used to find a user's location and display it on a map.

#### Example Usage of Geolocation
```html
<!DOCTYPE html>
<html>
<body>

<p>Click the button to get your coordinates:</p>

<button onclick="getLocation()">Try It</button>

<p id="demo"></p>

<script>
var x = document.getElementById("demo");

function getLocation() {
  if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(showPosition);
  } else { 
    x.innerHTML = "Geolocation is not supported by this browser.";
  }
}

function showPosition(position) {
  x.innerHTML = "Latitude: " + position.coords.latitude + 
  "<br>Longitude: " + position.coords.longitude;
}
</script>

</body>
</html>
```

### 7. Five Bootstrap CSS Classes

1. **.container**: Used to create a responsive fixed-width container.
2. **.row**: Used to create a horizontal group of columns.
3. **.col**: Used for grid columns to define their width and layout.
4. **.btn**: Used to style buttons.
5. **.alert**: Used to create alert messages.

### 8. HTML Bootstrap Code for Forms

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

<div class="container">
  <h2>Bootstrap Form Example</h2>
  <form>
    <div class="form-group">
      <label for="email">Email address:</label>
      <input type="email" class="form-control" id="email" placeholder="Enter email" name="email">
    </div>
    <div class="form-group">
      <label for="pwd">Password:</label>
      <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pwd">
    </div>
    <div class="form-group form-check">
      <label class="form-check-label">
        <input class="form-check-input" type="checkbox" name="remember"> Remember me
      </label>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
</div>

</body>
</html>
```

### 9. HTML Bootstrap Code for Responsive Tables

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

<div class="container">
  <h2>Responsive Table</h2>
  <p>The .table-responsive class makes the table responsive:</p>            
  <div class="table-responsive">          
    <table class="table">
      <thead>
        <tr>
          <th>#</th>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Username</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>John</td>
          <td>Doe</td>
          <td>john@example.com</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Mary</td>
          <td>Moe</td>
          <td>mary@example.com</td>
        </tr>
        <tr>
          <td>3</td>
          <td>July</td>
          <td>Dooley</td>
          <td>july@example.com</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

</body>
</html>
```

### 10. Design Nav Bar for a College Website

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>College Website</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<body>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">CollegeName</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">About Us</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Departments</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Admissions</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Faculty</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Contact Us</a>
      </li>
    </ul>
  </div>
</nav>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
```


# unit 2

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



