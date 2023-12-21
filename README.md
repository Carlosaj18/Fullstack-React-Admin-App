<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a>
    <img src="https://user-images.githubusercontent.com/62365628/214876004-be858914-bb6b-4b6e-8c40-b49112ff0d30.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">MERN Stack Admin Dashboard </h3>

  <p align="center">
    Build and Deploy a MERN Stack Admin Dashboard. For frontend, we will be using Material UI, Material UI Data Grid, Nivo Charts, Redux Toolkit and Redux Toolkit Query. For backend, we will be using Node JS, Express Js, Mongoose, and MongoDB. We will also go through how to Data Model using Entity Relationship Diagrams as well as making aggregate calls in MongoDB.
    <br />
    <a href="https://github.com/Carlosaj18/fullstack-admin"><strong>Explore the site »</strong></a>
    <br />
    <br />
    <a href="https://user-images.githubusercontent.com/62365628/225510216-5e05f97f-1994-4334-a486-4aad6b01d367.mp4">View Demo</a>
    ·
    <a href="https://github.com/Carlosaj18/fullstack-admin/issues">Report Bug</a>
    ·
    <a href="https://github.com/Carlosaj18/fullstack-admin/issues">Request Feature</a>
  </p>
</div>

<br />

<!-- ABOUT THE PROJECT -->
## :star2: About the Project

<div align="justify">Explore a versatile Admin Dashboard App designed to seamlessly manage and interact with your backend system. Empowered with MongoDB integration, this platform enables efficient communication and interaction with your database, ensuring streamlined data management and robust backend operations. Dive into a comprehensive dashboard experience tailored to enhance your administrative tasks and MongoDB functionalities. 
 <br><br>
</div>

## Project Technological Stack:

* Backend: MongoDB for efficient and scalable data management.
* Frontend: React for dynamic and interactive user interfaces.
* State Management: Redux for predictable state handling.
* Design: Figma for seamless UI/UX design creation.

<p align="center">
   <br><br>
  <a target="_blank" rel="noopener noreferrer"> <img src="https://github.com/devicons/devicon/blob/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/mongodb/mongodb-original-wordmark.svg" alt="Mongo" height="40" style="vertical-align:top; margin:4px"></a>
  <a target="_blank" rel="noopener noreferrer"> <img src="https://github.com/devicons/devicon/blob/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/express/express-original-wordmark.svg" alt="Express" height="40" style="vertical-align:top; margin:4px"></a>
  <a target="_blank" rel="noopener noreferrer"> <img src="https://github.com/devicons/devicon/blob/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/nodejs/nodejs-original-wordmark.svg" alt="Node" height="40" style="vertical-align:top; margin:4px"></a>
  <a target="_blank" rel="noopener noreferrer"> <img src="https://github.com/devicons/devicon/blob/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/javascript/javascript-original.svg" alt="Firebase" height="40" style="vertical-align:top; margin:10px"></a>
  <a target="_blank" rel="noopener noreferrer"> <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" alt="React" height="40" style="vertical-align:top; margin:10px"</a>
   <a> <img src="https://github.com/devicons/devicon/blob/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/materialui/materialui-original.svg" alt="MaterialUi" height="40" style="vertical-align:top; margin:10px"></a>
  <a> <img src="https://github.com/devicons/devicon/blob/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/redux/redux-original.svg" alt="Redux" height="40" style="vertical-align:top; margin:10px"></a>
   <a> <img src="https://github.com/devicons/devicon/blob/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/git/git-original-wordmark.svg" alt="MaterialUi" height="40" style="vertical-align:top; margin:10px"></a>
</p>
  
## Features:

*      Interactive Data Display: Material UI Data Grid for user-friendly tables.
*      Visual Data Representation: Nivo Charts for effective data visualization.
*      State Management: Redux Toolkit for predictable state handling.
*      Backend Setup: Node.js and Express.js for server-side operations.
*      Database Handling: Mongoose for MongoDB interaction.
*      Data Aggregation: MongoDB aggregate calls for efficient querying.
*      Design and UI: Material UI for consistent frontend design.
*      ERD Implementation: Entity Relationship Diagrams for data modeling.

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

`**Note**`: This app requires API key from <a href="https://www.mongodb.com/" >MongoDB Account</a>

### 1. Download Node.js and `npm` (follow instructions [here](https://nodejs.org/en/))

### 2. Git clone and cd into the repo folder:

```bash
https://github.com/Carlosaj18/Fullstack-React-Admin-App.git && cd admin-clone
```

### 3. Install all dependencies

```bash
npm install
```

### 4. In root directory of the server, create a `.env` file

```bash
.env
```

### 5. In root directory of the client, create a `.env.local` file

```bash
.env.local
```

### 6. In the `.env` file, create following environment variables:

```
MONGO_URL = YOUR_MONGO_API_KEY
PORT = 5001
```

### 7. In the `.env.local` file, create following environment variables:

```
REACT_APP_BASE_URL = http://localhost:5001
```

### 8. Run the server

```bash
npm start
#for deployed version

npm run dev
#for deployed version
```

### 9. Run the client

```bash
npm start
#for deployed version

```

### 10. Access the project in your browser at [`localhost:3000/`](localhost:3000)
   
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Demo & Showcasing:

 ### :camera: Screenshots

 https://user-images.githubusercontent.com/62365628/225510216-5e05f97f-1994-4334-a486-4aad6b01d367.mp4
 
### Data Model

https://lucid.app/lucidchart/81ff5432-cc50-4c41-a7b8-7258fec1e630/view?page=0_0#

![image](https://user-images.githubusercontent.com/62365628/225504686-ae57abec-ad89-466d-a167-71707c4f4dad.png)


## Live Site 

<p id="live-site"><p>

<a href="https://chat-ai-frontend.onrender.com">![Live Site](https://res.cloudinary.com/dn1e07eul/image/upload/v1659389947/Readme%20Headers/inter-live-site_ngkqcf.png)</a>

• **[Admin Dashboard](https://admin-frontend-1wzy.onrender.com/)** is a responsive web app can be viewed on any device.

<br>

<!-- CONTACT -->
## Contact

<a href=#lets-connect>![Let's Connect!](https://res.cloudinary.com/dn1e07eul/image/upload/v1659314257/Readme%20Headers/inter-lets-connect_bv3kcd.png)</a>

<p><a href="https://twitter.com/"><img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" height=30 width=90 alt="Twitter badge"></a> <a href="https://www.linkedin.com/in/carlos-jaramillo-full-stack-developer/"><img src="https://img.shields.io/badge/linkedin-%230064e7.svg?&style=for-the-badge&logo=linkedin&logoColor=white" height=30 width=90 alt="Linkedin badge"></a> <a href="mailto:cjaramilloportilla@gmail.com"><img src="https://img.shields.io/badge/gmail-%23fd1745.svg?&style=for-the-badge&logo=gmail&logoColor=white" height=30 width=90 alt="Gmail badge"></a> <a href="https://github.com/Carlosaj18"><img src="https://img.shields.io/badge/github-%23ff8e44.svg?&style=for-the-badge&logo=github&logoColor=white" height=30 width=90 alt="Github badge"></a></p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/Carlosaj18/fullstack-admin/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/Carlosaj18/fullstack-admin/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Carlosaj18/fullstack-admin/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/carlos-jaramillo-full-stack-developer/
[product-screenshot]: https://user-images.githubusercontent.com/62365628/216798918-82c7b3c2-8936-4e80-bf5d-9b83d2a1f3bc.mp4
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
