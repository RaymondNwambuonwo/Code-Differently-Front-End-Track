![code differently](https://user-images.githubusercontent.com/54545904/91590200-f82ec600-e928-11ea-9433-eea450388abf.png)

# Javascript AJAX

# Table of Content
- [Javascript AJAX](#javascript-ajax)
- [Table of Content](#table-of-content)
  - [JavaScript AJAX Lab](#javascript-ajax-lab)
    - [Prerequisites](#prerequisites)
    - [About](#about)
    - [The Set Up](#the-set-up)
    - [The Task](#the-task)
  - [Additional Resources](#additional-resources)

## JavaScript AJAX Lab

### Prerequisites
* JavaScript Fundamentals

### About
Since the start of the program you have learned how to build your own websites, utilizing HTML and CSS. But you have yet to generate content on these sites outside of what you created from scratch. In this lab you will be utilizing AJAX/Fetch to request information from third-party databases or APIs, generating content on your webpage from third party servers. 

### The Set Up

- Create a repository and call it  <em>“JS AJAX Lab”</em> 

- Initialize the repository

- Clone locally and open repository in Visual Studio Code

- Create an JS file called `index.html`, a `styles.css`, and a `script.js` file, be sure to link them.

- Push up your changes to the remote repository

- Once files are created you will need to run `npm install -g http-server` to install a package called `http-server globally`.
- Run http-server in the folder.
- Open your browser to localhost. 

### The Task
You are to make a basic webpage that possesses minimal styling and will generate information from a third party database/API. For this particular lab we will be using the [Pokemon API](https://pokeapi.co/). Your webpage is to generate at least one or more pokemon and some of its characteristics.

**Example of using fetch and AJAX**
```
const url = "http://pokeapi.salestock.net/api/v2/pokemon/7";

// fetch takes a url, and an object with a few optional parameters.
// Ex: {method: 'POST', headers: {'Content-Type': 'application/json'}}
// The default method of fetch is a GET request
// For now all we have to pass fetch is the url
fetch(url)
  .then(res => {
    console.log("success!", res);
  })
  .catch(err => {
    console.log("something went wrong...", err);
  });
  ```

## Additional Resources
List of free APIs [here](https://github.com/public-apis/public-apis).