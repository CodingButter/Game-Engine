# Beginner Javascript Game Engine - Setup

## Project Chapters

<br/>

> 00:00:00 [Introduction And Project Overview](#introduction-and-project-overview)

> 00:01:48 [Intro Clip]()

> 00:02:00 [Installing VS Code](#installing-vs-code)

> 00:04:00 [Installing NodeJS And NPM](#installing-nodejs-and-npm)

> 00:06:00 [Installing HTTP Server](#installing-http-server)

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

</br>

> ## Installing VS Code

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

- Easy to create, test, and deploy projects
- Server side and client side
- With npm we will have the ability to install Packages from others which we may or may not do in later videos.

</br>

> ## Installing HTTP Server

</br>

<a style="color:white" href="https://www.npmjs.com/package/http-server"><img src="https://www.flaticon.com/svg/vstatic/svg/3208/3208726.svg?token=exp=1611828251~hmac=f4d4837fdc9a8fa501025d5ca11c0f29" alt="alt text" width="25"> HTTP-Server</a>

- Allows us to open files from the computer such as our json files once we get to that point.

</br>

> ## Initializing Our Project

</br>

We need to set up our directory structure and basic html style and javascript files. The simple directory structur and files that we will start with go as follows

<details>
<summary><b>Project Directory</b></summary>

<details><summary>index.html</summary>
      
```html
<html>
    <head>
        <title>Javascript Game Engine</title>
        <link rel="stylesheet" href="src/style.css"/>
    </head>
    <body>
        <script type="module" src="src/app.js"></script>
    </body>
</html>
```
</details>

<details><summary><b>src</b></summary>

<details><summary>app.js</summary>

```js
const app = document.createElement("div")
app.id = "app"
document.body.appendChild(app)
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
  background: #666;
}
#app {
  background: white;
  width: 50%;
  height: 50%;
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
