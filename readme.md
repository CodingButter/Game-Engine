# Beginner Javascript Game Engine - Setup

## Project Chapters

<br/>

> 00:00:00 [Introduction And Project Overview](#introduction-and-project-overview)

> 00:01:48 [Intro Clip]()

> 00:02:00 [Installing VS Code](#installing-vs-code)

> 00:04:00 [Installing NodeJS And NPM](#installing-nodejs-and-npm)

> 00:06:00 [Installing Parcel Bundler](#installing-parcel-bundler)

> 00:09:00 [Initializing Our Project](#initializing-our-project)

> 00:19:00 [Video And Project Summary](#video-and-project-summary)

> 00:19:48 [Outro Clip]()

> 00:20:00 [Video End]()

</br>

> ## Introduction And Project Overview

</br>

    Hey Everybody, CodingButter Here Just Spreading Some Knowledge

</br>

- Learning Vanilla Javascript to me is very important. There are so many great resources/modules/libraries to use. But It's nice to learn to walk before you run.

- In this series we will begin by installing and using Parcel to build out our project for development and production but that is all its for. Our environment. But the code we will be writing atleast from the beginning in Vanilla Javascript and we wont depend on anyone elses Code..... Or will we (Forshadowing?)

> ## Installing VS Code

</br>

    Why VS Code

</br>

<a style="color:white" href="https://code.visualstudio.com/download"><img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" alt="VS-Code-Download" width="25"> Visual Studio Code</a>

- It's been widely adopted over the last few years.
  - better support
  - better docs
  - large community
  - large repository of useful plugins

</br>

> ## Installing NodeJS And NPM

</br>

<a style="color:white" href="https://nodejs.org/en/download/"><img src="https://cdn.worldvectorlogo.com/logos/nodejs.svg" alt="VS-Code-Download" width="100"></a>

Node comes with npm installed so we can include npm packages in our projects.

- Easy to create and fun projects
- Server side and client side
- Eventually the ability to install Packages from other

</br>

> ## Installing Parcel Bundler

</br>

<a href="https://parceljs.org/getting_started.html"><img src="https://user-images.githubusercontent.com/19409/31321658-f6aed0f2-ac3d-11e7-8100-1587e676e0ec.png" alt="alt text" width="150"></a>

- Packages up our project into a neat single minified html,css,js distrobution.
- Creates a simple development environtment
- Allows for live refreshing after code changes.

</br>

> ## Initializing Our Project

</br>

We need to set up our directory structure and basic html style and javascript files. The simple directory structur and files that we will start with go as follows

<details>
<summary><b>Project Directory</b></summary>

<details><summary>index.html</summary>
      
```html
<html>
    <body>
        <script src="./src/app.js"></script>
    </body>
</html>
```
</details>

<details><summary><b>src</b></summary>

<details><summary>app.js</summary>

```js
import "style.css"

const app = document.createElement("div")
app.id = "app"
document.body.appendChild(app)
```

</details>
<details><summary>style.css</summary>

```css
html,
body {
  margin: 0;
  padding: 0;
}
body {
  display: flex;
  align-items: center;
  justify-content: center;
  background: #666666;
}
#app {
  background: "white";
}
```

</details>
</details>
</details>

<br>

> ## Video And Project Summary

</br>

    We typed code that does things CONGRATS!

- Why VS CODE
- Why Node/NPM
- Why Parcel
- Importance of keeping a clean project structure
