[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HFRGJMMY9KF7C) [![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/grandnode/Lobby) [![Build
status](https://ci.appveyor.com/api/projects/status/ox0qebg3wv3dp30e/branch/develop?svg=true)](https://ci.appveyor.com/project/KrzysztofPajak/grandnode/branch/develop) [![Build Status](https://travis-ci.org/grandnode/grandnode.svg?branch=develop)](https://travis-ci.org/grandnode/grandnode)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/acbd143050984c1983d7cb0bd10b3472)](https://www.codacy.com/app/grandnode/grandnode?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=grandnode/grandnode&amp;utm_campaign=Badge_Grade)
![Github All Releases](https://img.shields.io/github/downloads/grandnode/grandnode/total.svg) [![Demo](https://img.shields.io/badge/DEMO-HERE-green.svg)](https://demo.grandnode.com/)

<br />
<p align="center">
  <a href="https://grandnode.com/">
    <img src="https://grandnode.com/content/images/uploaded/arts/git_header.jpg" alt="Logo">
  </a>

  <h3 align="center">GrandNode</h3>

  <p align="center">
    Cloud friendly, All-in-One e-Commerce Platform
    <br />
    <a href="https://grandnode.com/?utm_source=github&utm_medium=link&utm_campaign=readme"><strong>Explore the project »</strong></a>
    <br />
    <br />
    <a href="https://demo.grandnode.com/?utm_source=github&utm_medium=link&utm_campaign=readme">View Demo</a>
    ·
    <a href="https://github.com/grandnode/grandnode/issues">Report Bug</a>
    ·
    <a href="https://github.com/grandnode/grandnode/issues">Request Feature</a>
    ·
    <a href="https://grandnode.com/boards/?utm_source=github&utm_medium=link&utm_campaign=readme">Visit forum</a>
    ·
    <a href="https://grandnode.com/grandnode-themes/?utm_source=github&utm_medium=link&utm_campaign=readme">Premium Themes</a>
    ·
    <a href="https://grandnode.com/extensions/?utm_source=github&utm_medium=link&utm_campaign=readme">Integrations & Plugins</a>
    ·
    <a href="https://grandnode.com/premium-support-packages/?utm_source=github&utm_medium=link&utm_campaign=readme">Premium support</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [Why GrandNode?](#about-the-project)
  * [Technology Stack](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Online demo](#online-demo)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## About The Project

![GithHub Header](https://grandnode.com/content/images/uploaded/Blog/gitbanner.jpg)

GrandNode is an e-commerce platform for developing online stores. It gives you possibility to create highly advanced, good-looking online stores which have unlimited power of customization. 


### Built With

* []()
* []()
* []()



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

GrandNode requires .NET Core 3.1, MongoDB 4.0+, and OS-specific dependency tools. 

### Installation

GrandNode can be installed in a few different ways. Note: The develop branch is the development version of GrandNode and it may be unstable. To use the
latest stable version, download it from the Releases page or switch to a release branch. 

1. Clone the repo
* Docker 
```
sh docker run -d -p 127.0.0.1:27017:27017 --name mongodb mongo 
docker run -d -p 80:80 --name grandnode --link mongodb:mongo grandnode/develop
``` 
If you want to download the latest stable version of GrandNode please use the following command, where x.xx is a number of GrandNode release: 
```
sh docker pull grandnode/grandnode:x.xx 
```
Feel free to visit our [detailed guide about GrandNode installation.](https://grandnode.com/how-to-install-grandnode-on-linux-ubuntu-1604)

Install GrandNode with one click on [DigitalOcean](https://marketplace.digitalocean.com/apps/grandnode) ![DigitalOcean_Logo](https://grandnode.com/content/images/uploaded/digitalocean1.png)

### Online demo 
#### Frontend #### 
[https://demo.grandnode.com/](https://demo.grandnode.com/)
[![ScreenShot](http://grandnode.com/content/images/uploaded/showcase/frontend.JPG)](https://demo.grandnode.com/) 

#### Backend #### 
[https://demo.grandnode.com/admin](https://demo.grandnode.com/admin) 
[![ScreenShot](https://grandnode.com/content/images/uploaded/showcase/backend.JPG)](https://demo.grandnode.com/admin)
Demo is restoring once per day to the original state. Access to the admin panel: 
Admin email: admin@yourstore.com 
Admin password: 123456


## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=flat-square
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=flat-square
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=flat-square
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=flat-square
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=flat-square
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
[product-screenshot]: images/screenshot.png
