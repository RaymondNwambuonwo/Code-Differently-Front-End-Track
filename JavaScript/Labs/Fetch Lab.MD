![code differently](https://user-images.githubusercontent.com/54545904/91590200-f82ec600-e928-11ea-9433-eea450388abf.png)

# Javascript Fetch

# Table of Content
- [Javascript Fetch](#javascript-fetch)
- [Table of Content](#table-of-content)
  - [JavaScript Fetch Lab](#javascript-fetch-lab)
    - [Prerequisites](#prerequisites)
    - [About](#about)
    - [The Set Up](#the-set-up)
    - [The Task](#the-task)
  - [Additional Resources](#additional-resources)
  - [Submission](#submission)

## JavaScript Fetch Lab

### Prerequisites
* JavaScript Fundamentals

### About
Since the start of the program you have learned how to build your own websites, utilizing HTML and CSS. But you have yet to generate content on these sites outside of what you created from scratch. In this lab you will be utilizing Fetch to request information from third-party databases or APIs, generating content on your webpage from third party servers. 

### The Set Up
- You will need to fork and clone this repository.
- Change into the new directory.
- Once files are created you will need to run `npm install -g http-server` to install a package called `http-server globally`.
- Run http-server in the folder.
- Open your browser to localhost. 

### The Task
You are to make a basic webpage and will generate information from a third party database/API. Your webpage must include a search and submit form with an ordered/unordered list to show results.

For this particular lab we will be using the [Pokemon API](https://pokeapi.co/). Head over to the link above and browse around to get a feel for interacting with a third-party API site. Also be sure to look over the **DOCS**, docs or documentation is given to provide instructions on how to utilize the site's API.

**Example of using fetch and AJAX**
```js
const url = "https://pokeapi.co/api/v2/pokemon/";

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


## Submission
You will need to submit a pull request for submission.