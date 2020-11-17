[![Build
status](https://ci.appveyor.com/api/projects/status/ox0qebg3wv3dp30e/branch/develop?svg=true)](https://ci.appveyor.com/project/KrzysztofPajak/grandnode/branch/develop) [![Build Status](https://travis-ci.org/grandnode/grandnode.svg?branch=develop)](https://travis-ci.org/grandnode/grandnode)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/acbd143050984c1983d7cb0bd10b3472)](https://www.codacy.com/app/grandnode/grandnode?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=grandnode/grandnode&amp;utm_campaign=Badge_Grade)
![Github All Releases](https://img.shields.io/github/downloads/grandnode/grandnode/total.svg) [![Demo](https://img.shields.io/badge/DEMO-HERE-green.svg)](https://demo.grandnode.com/)

<br />
<p align="center">
  <a href="https://grandnode.com/">
    <img src="https://grandnode.com/content/images/uploaded/blogimages/githubfirst1.JPG" alt="Logo">
  </a>

  <h1 align="center">GrandNode</h1>

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

* Docker 
```
docker run -d -p 127.0.0.1:27017:27017 --name mongodb mongo 
docker run -d -p 80:80 --name grandnode --link mongodb:mongo grandnode/develop
``` 
If you want to download the latest stable version of GrandNode please use the following command, where x.xx is a number of GrandNode release: 
```
docker pull grandnode/grandnode:x.xx 
```
Feel free to visit our [detailed guide about GrandNode installation.](https://grandnode.com/how-to-install-grandnode-on-linux-ubuntu-1604)

Install GrandNode with one click on [DigitalOcean](https://marketplace.digitalocean.com/apps/grandnode)


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

:star: Star us on GitHub - it's the first step to become a GrandNode supporter! GrandNode is an open source online shopping solution, each developer is welcome and encouraged to contribute with their own improvements and enhancements.

GrandNode is mostly written in ASP.NET. Other languages used in the project are HTML, CSS, JavaScript, MongoDB. To start with us, you should do this few steps: 

1. Create your own GitHub account. 

2. Fork the GrandNode to your GitHub account

3. Clone the forked project to your local machine

4. After that, create a branch for your own changes

5. Change the files. 6. Push your changes from local machine to your fork in your GitHub account 

7. It's time to create a pull request for your changes on the GrandNode project. If you don't know how to do it, you can read more about pull request [here](https://help.github.com/articles/about-pull-requests/) 

8. Wait for the information. One of our developers will comment your changes and approve it or will suggest some
improvements in your code. 

And that's all, you are GrandNode official contributor! [Coding standards and guides](https://docs.grandnode.com/developer-guides)


## License

Distributed under the GNU General Public License v3.0. It's available [here](https://github.com/grandnode/grandnode/blob/develop/LICENSE)
