# Movie-Library

<div id="top"></div>


<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
--


<!-- PROJECT LOGO -->
<br />









<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* List of softwares need to be installed before installation step.
1. npm 
2. nodejs
3. git

### Installation

1. Get a free API Key at (http://www.omdbapi.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/Poojitha1203/Movies-library
   ```
3. Change your current directory to cloned folder
   ```sh
   cd Movies-Library-Website
   ```
4. Install NPM packages of root directory 
   ```sh
   npm install
   ```
5. Change your current directory to frontend folder
   ```sh
   cd frontend
   ```
6. Install NPM packages of frontend directory 
   ```sh
   npm i
   ```
   
7. Enter your details in .env file in the root directory of project folder
    ```js
    NODE_ENV = development
    PORT = 5000
    REACT_APP_CLIENT_SECRET = {your api key)
    MONGO_URI = {enter your mongodb connection uri}
    JWT_SECRET = {enter any text}
    ```
8. In your terminal in the root directory of project folder
    ```sh
    npm run dev
    ```
   The frontend server will start on http://localhost:3000 and the backend server will start on http://localhost:5000

<p align="right">(<a href="#top">back to top</a>)</p>


## Endpoints

HTTP verbs, or methods, should be used in compliance with their definitions under the [HTTP/1.1](http://www.w3.org/Protocols/rfc2616/rfc2616-sec9.html) standard.
The action taken on the representation will be contextual to the media type being worked on and its current state. Here's an example of how HTTP verbs map to create, read, update, delete operations in a particular context:
| Function      | Request Type  | Route  |
| ------------- |:-------------:| -----:|
| Get data of logged in user| GET | /api/auth |
| Login a user      | POST      |   /api/auth |
| Register a user | POST     |    /api/users |
| Search for a movie | GET     |    /api/data/${searchValue} |
| Get all movies list of the user| GET | /api/mylist |
| Add movie to users list| POST | /api/mylist |
| Delete the movie from the list| DELETE | /api/mylist/:id |
| Get data of movies list(public) | GET     |    /api/share/:id |




<!-- USAGE EXAMPLES -->
<!-- ## Usage -->
<!-- 
Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>
 -->


<!-- ROADMAP -->
<!-- ## Roadmap -->
<!-- 
- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p> -->





<!-- CONTACT -->

