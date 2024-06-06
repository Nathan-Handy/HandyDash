

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h1 align="center">HandyDash</h1>
  <h2 align="center">Operational Monitoring Made Easy.</h2>

  <p align="center">
    HandyDash is a HTTP, TCP, and IP monitoring tool, intended for desktop use. It is agent free, requires no installation, and saves all configuration to a single portable file. Simply unzip the package and run the executable to view and edit nodes within the browser based UI. 
  </p>  
  
  <a href="https://github.com/Nathan-Handy/HandyDash">
    <img src="images/logo.png" alt="Logo" width="323" height="194">
  </a>
  
  <p>
    <a href="https://github.com/Nathan-Handy/HandyDash/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/Nathan-Handy/HandyDash/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
  
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About </a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Welcome to HandyDash. I set about developing this software with the following features in mind:

* I wanted a monitoring tool that could be run with a single click, and doesn't require the installation of agents on target systems.
* I wanted a monitoring tool that is simple to configure, without requiring programming or scripting knowledge.  
* I wanted a monitoring tool that can visually represent the platforms that my team is monitoring.
* I wanted a monitoring tool that distinguishes the criticality of different events.
* I wanted a monitoring tool that distinguishes between application failures and lower level connectivity failures.
* I wanted a monitoring tool that articulates failures in a way that is actionable for my operations team.
* I wanted a monitoring tool that links the systems underpinning composite platforms, and propagates failures to upstream nodes.

Please see [my blog](https://www.nathanhandy.blog/articles/) for further discussion of application and systems monitoring.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get started using HandyDash, simply:

1. Download and unzip <a href="https://github.com/Nathan-Handy/HandyDash/releases/tag/v1.0">HandyDash-v1.0-win-x64.zip</a>.
2. Run HandyDash.exe to load the UI.
3. Add and edit monitor configurations using the Plus and Cog icons shown.

That's it!


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

HandyDash v1.0 is set to poll configured monitors at 1 minute intervals. The UI also refreshes every 1 minute, and while this may be manually refreshed via the web browser, it will not trigger the monitor polling functionality. 

Various UI features exist, including alert bubble up after repeated failures, the ability to disable bubbled up alerts for 24 hours, and click to zoom for individual monitor nodes.

Please check again soon for further details regarding HandyDash features and usage.

<img src="images/screenshot-overview.png" alt="Screenshot">

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

As visible within the create and edit node screens, only a subset of configuration features are currently implemented. For example, while there are TCP and IP checks conducted when a HTTP check fails, you cannot currently specify a TCP, UDP, or IP only monitor.

I plan on extending these features as time permits. A star in GitHub or an email will certainly help with motivation, so please feel free to contact me using the details further below.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

HandyDash v1.0 is free, however it is not open-source. Please see <a href="https://github.com/Nathan-Handy/HandyDash/blob/main/license/License-HandyDash-v1.0.txt">`LICENSE.txt`</a> for full license details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

**Nathan Handy** - All feedback and questions are welcome. If you encounter any bugs please [raise an issue](https://github.com/Nathan-Handy/HandyDash/issues).

* Email: nathanhandyblog@gmail.com
* Personal Blog: [www.nathanhandy.blog](https://www.nathanhandy.blog/)
* Twitter / X: [_H4NDY](https://x.com/_H4NDY)
* LinkedIn: [www.linkedin.com/in/nahandy](https://www.linkedin.com/in/nahandy/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

HandyDash makes use of the following open source frameworks and templates.

* [Treant.js](https://fperucic.github.io/treant-js/)
* [Raphaël](https://github.com/DmitryBaranovskiy/raphael)
* [Zoomooz.js](https://jaukia.github.io/zoomooz/)
* [Loading-Bar.js](https://loading.io/progress/) 
* [jQuery](https://jquery.com)
* [othneildrew](https://github.com/othneildrew/Best-README-Template)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[stars-shield]: https://img.shields.io/github/stars/Nathan-Handy/HandyDash.svg?style=for-the-badge
[stars-url]: https://github.com/Nathan-Handy/HandyDash/stargazers
[issues-shield]: https://img.shields.io/github/issues/Nathan-Handy/HandyDash.svg?style=for-the-badge
[issues-url]: https://github.com/Nathan-Handy/HandyDash/issues
[license-shield]: https://img.shields.io/github/license/Nathan-Handy/HandyDash.svg?style=for-the-badge
[license-url]: https://github.com/Nathan-Handy/HandyDash/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/nahandy/
[product-screenshot]: images/screenshot.png
