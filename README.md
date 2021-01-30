<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<h3 align="center">PyInv</h3>
<p align="center">
  <a href="https://github.com/albusnoir/pyinv" align="center">
    <img src="https://github.com/AlbusNoir/AlbusNoir/blob/master/Icons/logo_2021.png" alt="Logo" width="100" height="100">
  </a>
  <br />
  Python Inventory Nonsense Venture
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#languages-and-frameworks">Languages and Frameworks</a></li>
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
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

PyInv is a GUI based spreadsheet manager using the Google Sheets API. It allows you to update cells realtime, add sheets, choose between sheets, etc. <br />
It basically allows you to do everything you could do if you just went to your sheet!

<img src="https://github.com/AlbusNoir/AlbusNoir/blob/master/Icons/logo_2021.png">

### Languages and Frameworks

* Python3



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* An incredible amount of laziness
* Alternatively, a love for over-engineered things
* A Google Account
* Some Google Sheets
* Edit access to these sheets
* The Authentication stuff done with the GoogleSheetsAPI (follow [QuickStart](https://developers.google.com/sheets/api/quickstart/python))

### Installation

There are a few packages you will need to install:<br />
* The GoogleSheetsAPI packages: `pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib`
* PySimpleGUI: `pip install pysimplegui`


<!-- USAGE EXAMPLES -->
## Usage

* Select your sheet from the dropdown (this data is pulled from sheets.json)
* Enter your cells in the proper notation (hover over the box to see this)
* Enter your stuff to put into the cells
* Hope you entered things correctly<br /><br /><br />
**More features coming eventually



<!-- ROADMAP -->
## Roadmap
_Current_
- [x] Completely, and unnecessarily, over-engineer using Google Sheets
- [x] Test, break, retest, succeed, break, rewrite, repeatx4
- [x] Figure out how the heck json works
- [x] Figure out how the heck keys and fields work
- [ ] Find a practical use for this

_Future Plans_
- [ ] TBD



<!-- CONTRIBUTING -->
## Contributing

If you want to make contributions:

1. Fork this Repository
2. Create your Branch(`git checkout -b <branch name>`)
3. Commit your Changes(`git commit -m 'I did some things'`)
4. Push to the Branch(`git push origin <project_name>/<location>`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the `GPLv3` License. See [`LICENSE INFO`](https://choosealicense.com/) for more information.



<!-- CONTACT -->
## Contact

Name | Social | Email |
------------ | ------------- | ------------- |
Kale | [![Twitter][twitter-shield]][twitter-url] | <a href="mailto:kalegithub@gmail.com"><img src="https://img.shields.io/badge/-email-Email?style=for-the-badge&logo=gmail&colorB=555"></a>


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements & Contributions

#### Thank you to the following:

User | Contribution |
------------ | ------------- |
[@albusnoir](https://github.com/albusnoir) | Did the thing |



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/albusnoir/pyinv.svg?style=for-the-badge
[contributors-url]: https://github.com/albusnoir/pyinv/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/albusnoir/pyinv.svg?style=for-the-badge
[forks-url]: https://github.com/albusnoir/pyinv/network/members
[stars-shield]: https://img.shields.io/github/stars/albusnoir/pyinv.svg?style=for-the-badge
[stars-url]: https://github.com/albusnoir/pyinv/stargazers
[license-shield]: https://img.shields.io/github/license/albusnoir/pyinv.svg?style=for-the-badge
[license-url]: https://github.com/albusnoir/pyinv/blob/main/LICENSE
[twitter-shield]: https://img.shields.io/badge/-twitter-Twitter?style=for-the-badge&logo=twitter&colorB=555
[twitter-url]: https://twitter.com/kaleleafygreen
