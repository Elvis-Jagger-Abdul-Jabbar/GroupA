<a name="readme-top"></a>

<!-- PROJECT SHIELDS
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Roehampton][Roehampton-shield]][Roehampton-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA/blob/main/ReadME.md">
    <img src="/images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Data Engeneering Project</h3>

  <p align="center">
    A repository for a group work
    <br />
    <a href="https://github.com/users/Elvis-Jagger-Abdul-Jabbar/GroupA/ReadME.md"><strong>Read Me</strong></a>
    <br />
    <br />
    <a href="https://github.com/users/Elvis-Jagger-Abdul-Jabbar/projects/1">Kanban Board</a>
    ·
    <a href="https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA/issues">Log an Issue</a>
    ·
    <a href="https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA/wiki/Quick-Guide">Quick Guide</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!--[![Product Name Screen Shot][product-screenshot]]https://airflow.apache.org/._-->

This is a Data Engeneering group project made using Apache Airflow.
It aims as creating a system (data pipeline) for a business’s smooth and efficient data delivery.
The business model is a music streaming service.

The datasets we are using come from
http://millionsongdataset.com/
We will be coordinating data from several sets that will contain information
about songs from listener data to lyric content.

DataSet located in: https://github.com/Elvis-Jagger-Abdul-Jabbar/dataSet

A Quick Guide is available in Wiki section for general installation and command lines etc.


<!-- Back to top -->
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

List tools and technologies used to deliver this project.

* [![Airflow][Airflow-shield]][Airflow-url]
* [![Python][Python.js]][Python-url]
* [![Mysql][Mysql.js]][Mysql-url]

Badges made with:
* [![ShieldsIO][Shields.io]][Shields-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Getting started section

### Prerequisites

- Docker Desktop
- Code Editor

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupAe.git
   ```
2. Install Docker
   ```sh
   choco install docker-desktop --pre
   ```
3. Install Airflow
   ```js
   pip install "apache-airflow[celery]==2.1.4" --constraint "https://raw.githubusercontent.com/apache/airflow/constraints-2.1.4/constraints-3.6.txt"
   ```
4. Mount Airflow Image
   ```sh
   docker-compose up airflow-init
   ```
5. Launch Docker
   ```sh
   docker-compose up
   ```
6. Navigate to localhost://8080

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

_Please refer to Apache Airflow [Documentation](https://airflow.apache.org/)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Identifying the requirements (functional and non-functional)
- [x] Prioritising the requirements (if applicable)
- [x] Task allocation
- [x] Identifying the scope of your project
- [ ] Identifying the stakeholders
- [ ] Risk management



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Sprints

- Sprint 1

  - GitHub project for coursework setup.
  - Product backlog created.
  - Initial tasks are defined as user stories.
  - Kanban/project board being used.
  - Sprint boards are being used.
  - Necessary starting docker files for the project set up and working.
  - Correct branches for GitFlow workflow created – includes master, develop, and release branches.
  - The first release was created on GitHub.
  - Code of Conduct defined.



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

This project is licensed under the terms of the MIT license. Check `LICENSE.cmd`for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA](https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

State resources or references

* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Elvis-Jagger-Abdul-Jabbar/GroupA
[contributors-url]: https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Elvis-Jagger-Abdul-Jabbar/GroupA?style=social
[forks-url]: https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA/network/members
[stars-shield]: https://img.shields.io/github/stars/Elvis-Jagger-Abdul-Jabbar/GroupA?style=social
[stars-url]: https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA/stargazers
[issues-shield]: https://img.shields.io/github/issues/Elvis-Jagger-Abdul-Jabbar/GroupA
[issues-url]: https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA/issues
[license-shield]: https://img.shields.io/github/license/Elvis-Jagger-Abdul-Jabbar/GroupA
[license-url]: https://github.com/Elvis-Jagger-Abdul-Jabbar/GroupA/master/LICENSE.txt
[Roehampton-shield]: https://img.shields.io/badge/Roehampton%20University-green.svg?logo=data:image/jpeg;base64,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
[Roehampton-url]: https://www.roehampton.ac.uk
[product-screenshot]: images/screenshot.png
[Python.js]: https://img.shields.io/badge/Python-blue?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Airflow-shield]: https://img.shields.io/badge/Airflow-0769AD?style=for-the-badge&logo=apacheairflow&logoColor=white
[Airflow-url]: https://airflow.apache.org
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Shields.io]: https://img.shields.io/badge/Shields-IO-blue
[Shields-url]: https://shields.io
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[Mysql.js]: https://img.shields.io/badge/Mysql-orange?style=for-the-badge&logo=mysql&logoColor=black
[Mysql-url]: https://www.mysql.com/
[Badis-shield]: https://img.shields.io/badge/Badis-Aoun-blue.svg
[Badis-url]: https://github.com/Elvis-Jagger-Abdul-Jabbar
