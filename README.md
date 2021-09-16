<!-- PROJECT LOGO -->
<br />
<p align="center">
  <img src="https://i.ibb.co/yFSDMWr/SEMPECANAL.png" alt="Logo" width="200" height="200">

  <h3 align="center">Live Micro Frontends with Full Cycle</h3>

  <p align="center">
    This project it's created on the live with Dev Full Cycle about micro frontend architecture. The live was shown on September 15, 2021. To demonstrate the architecture, 5 projects were created. First, I created the root project. This project is responsible for calling routes to other micro frontends and injecting dependencies. I created 3 other projects and transform on another project in micro frontend.
The projects are: 2 in react (navbar and app1) , 1 (project transformed on mfe) in vue (home) and created 1 to footer using Angular 12. In the live show I demonstrated how the micro frontend architecture works and how we can use many independent projects and frameworks in the same Dom.
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#frameworks">Frameworks</a></li>
      </ul>
    </li>
    <li><a href="#live">Live</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.


### Prerequisites

This is a prerequisites for this application: 

* Install node
  ```sh
  sudo apt install nodejs
  ```

* Install npm
  ```sh
  sudo apt install npm
  ```

* Update you packages
  ```sh
  sudo apt-get update
  ```

* Upgrade
  ```sh
  sudo apt-get upgrade
  ```


### Usage

Execute this on all folders (all micro frontends)

1. Install packages (all projects/folders)
   ```sh
   npm install
   ```

2. Build
   ```sh
   npm run build
   ```

3. Start
   ```
   yarn start
   or
   yarn serve
   or
   yarn run serve:single-spa:footer
   ```

4. The micro frontend is here
   ```sh
   http://localhost:9000
   ```


### Frameworks
<ul>
  
   <li><a href="https://www.typescriptlang.org/">Typescript</a></li>
  
   <li><a href="https://nodejs.org/en/">Node</a></li>
  
   <li><a href="https://pt-br.reactjs.org/">React</a></li>
  
   <li><a href="https://angular.io/">Angular</a></li>
  
   <li><a href="https://vuejs.org/">Vue</a></li>
  
   <li><a href="https://single-spa.js.org/">Single-Spa</a></li>
  
</ul>

## Live

This project is created on this live. For what the video, click on the image.

[![IMAGE ALT TEXT](https://img.youtube.com/vi/KZpSghOWOnE/mqdefault.jpg)](https://www.youtube.com/watch?v=KZpSghOWOnE "Micro Frontends na Prática")


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Contact

Author: Carlos Sempé <br />
Email: sempejunior@gmail.com <br />
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555)](https://www.linkedin.com/in/carlos-semp%C3%A9/)
[![Youtube Badge](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UC86JKVL2p0sPcdkUJ9093cQ)
[![Github Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sempejunior/live-full-cycle/stargazers)
