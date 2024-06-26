<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][https://www.linkedin.com/in/justfederico/]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/justinfederico/Marlin">
    <img src="linus.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Ender-3 V2 Custom Firmware based on Marlin</h3>

  <p align="center">
    Quick and dirty custom solution for my issue of precompiled firmware not working on my BTT SKR Mini E3 V3 on my Ender-3 V2, which has been modified quite  a bit.
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs (when they exist lol)»</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo (there is none yet, lol2)</a>
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This is a custom build of Marlin utilizing the nightly bugfix release as a template. It is customized to work on my Ender-3 V2 3D Printer from Creality, which has numerous upgrades which necessitated my foray into building my own firmware. This is always a work in progress, and is a personal build only meant to work on my specific machine, however I will list the alterations I have made to my printer regardless, since I understand there is a slim chance it may be used as a reference fro customization (proper documentation coming soon).

* Ender-3 V2 Frame
* Microswiss All-Metal Direct Drive Extruder
* SKR mini E3 V3 motherboard
* Stock Ender-3 V2 LCD with custom ribbon cable for interfacing with SKR mini E3 V3 (doesn't work without custom cable AND updating firmware on display)
* Custom Satsana duct made with ASA, and Noctua 40x10mm 12V fan to reduce noise
* [Gulfcoast Robotics Thermistor upgrade](https://www.amazon.com/gp/product/B08R3J6GJ3/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1)
* [POLISI3D Heater Cartridge Element upgrade](https://www.amazon.com/gp/product/B08CNCHC29/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&th=1)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* Latest Marlin nightly bugfix release
* AutoBuildMarlin extension in VS Code
* PlatformIO in VS Code

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

To be clear, it is unlikely that this firmware will build and flash on any machine but my own without **SOME** modification. So, as such, do not build this firmware expecting it work perfectly unless your specifications are **EXACTLY** the same as my machine. Even then, it still may not work, as firmware, in my limited experience, is very touchy. However, feel free to ask questions, I will attempt to answer them to the best of my ability.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Justin Federico - [@justinfederic0](https://twitter.com/justinfederic0)

Project Link: [https://github.com/justinfederico/Marlin](https://github.com/justinfederico/Marlin)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [The geniuses at Marlin who saved me from writing all of this myself](https://github.com/MarlinFirmware/Marlin)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



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
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
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
