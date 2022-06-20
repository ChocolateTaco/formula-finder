<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- [![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]](https://mit-license.org/)
[![LinkedIn][linkedin-shield]](https://www.linkedin.com/in/steventranx/) -->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Formula Finder 2022</h3>

  <p align="center">
    Find availability of baby formula online without any hassle!
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]]([https://example.com](https://conservativeresearchgroup.com/wp-content/uploads/2022/06/Baby-Formula-Shortage-copy-768x424.jpg))

Purpose of this project is to help new and existing parents find Baby formula during the 2022 Baby Formula Shortage in the United States. It scrapes a few major online retailers for their baby formula inventory, and sends the report to a list of email subscribers. This project has benefitted me personally and a few other moms in our circle in keeping track of which formulas go in and out. The focus is primarily on [Store Brand Formula](https://www.storebrandformula.com/) for cost savings. However other formula may also be prevalent in the web scraping.


### Built With

* [Selenium](https://www.selenium.dev/)
* [Python](https://www.python.org/)

<!-- GETTING STARTED -->
## Getting Started

<!-- This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps. -->

### Prerequisites
* [Chrome Browser](https://www.google.com/chrome/)
* [Chrome Driver](https://chromedriver.chromium.org/downloads/)
* [Python 3+](https//www.python.org/)
* [Selenium](https://www.selenium.dev/)


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ChocolateTaco/formula-finder.git
   ```
2. Install Selenium
   ```sh
   pip install -U selenium
   ```
3. [Sign up for an AOL Email Address](https://mail.aol.com)
4. In AOL Account Security settings, "Generate app password"
5. In /emailer directory, create "emailAlert.txt"
6. In "emailAlert.txt" add the AOL email address and the one time password (separated by a line space). Note NOT the email address' password, but the One Time Password
   ```js
   emailAddress@aol.com
   emailsOneTimePassword
   ```
7. 


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] Scrape StoreBrand Formula Online Retailers
    - [x] Costco.com
      - [ ] Optimize Costco speed
    - [x] Target.com
    - [x] Amazon.com
    - 🛑 Kroger.com (Anti-Robot Friendly)
    - 🛑 SamsClub.com (Anti-Robot Friendly)
    - 🛑 Walmart.com (Anti-Robot Friendly)
- [x] Generate Report
  - [x] Gather Product Name, Availability, Price, URL
  - [ ] Gather Last In Stock Date
  - [ ] Shorten URL
- [ ] Email Results to list of email subscribers
    - [x] BCC emails to an email list using AOL SMTP 
    - [ ] Unsubscribe Feature
- [ ] Create Virtual Environment


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [JimSC for teaching me Selenium!](https://github.com/jimdevops19)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png