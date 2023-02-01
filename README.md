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

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/raining-codes/molecube">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">molecube</h3>

  <p align="center">
    A command line application to make discord.js easier!
    <br />
    <a href="https://github.com/raining-codes/molecube"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/raining-codes/molecube">View Demo</a>
    ·
    <a href="https://github.com/raining-codes/molecube/issues">Report Bug</a>
    ·
    <a href="https://github.com/raining-codes/molecube/issues">Request Feature</a>
  </p>
</div>


<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

molecube is a simple Command Line Application written in NodeJS. It helps you generate discord.js bots. Again, this is a discord bot **generator**, not a bot itself. Its configuration is saved in molecube.json.

molecube offers you:

* Creating a project in discord.js
* A command handler
* A event handler
* Easly generate events with its documentation links
* Easly generate commands
* Conection to a database
* Simplicity

**Full Changelog**: https://github.com/raining-codes/molecube/commits/Release

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->

## Getting Started

Installing molecube is pretty easy and straightforward.

### Installation
##### To use with yarn do:
yarn global add molecube
##### To use with npm do:
npm install -g molecube

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

### Making a new bot
To make a new discord bot using molecube, open terminal in your preffered location and type `molecube new`. This will ask you a couple of questions, These questions are:
1. Bot name
2. Your preffered language
3. Your package manager
4. Your bots token
5. Your MongoDB Database URI (If you don't have a database just skip this)

After you've answered these questions, molecube will create a new folder and create a simple ping slash command.

### Generating events or commands
To add your own custom commands and events, you need to follow these instructions.
1. Open terminal in a molecube project directory.
2. Run `molecube gen`, this will ask you to generate a event or command.
3. Select your option and press enter.

If you selected event, theres gonna be list of all events and you can create multiple events at once. Your generated event files are gonna be located in src/events.

If you selected command, it will ask for command name and description. Command file will be located in src/commands


_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Your Name - **George Tskitishvili**

Project Link: [https://github.com/raining-codes/molecube](https://github.com/raining-codes/molecube)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/raining-codes/molecube.svg?style=for-the-badge
[contributors-url]: https://github.com/raining-codes/molecube/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/raining-codes/molecube.svg?style=for-the-badge
[forks-url]: https://github.com/raining-codes/molecube/network/members
[stars-shield]: https://img.shields.io/github/stars/raining-codes/molecube.svg?style=for-the-badge
[stars-url]: https://github.com/raining-codes/molecube/stargazers
[issues-shield]: https://img.shields.io/github/issues/raining-codes/molecube.svg?style=for-the-badge
[issues-url]: https://github.com/raining-codes/molecube/issues
[license-shield]: https://img.shields.io/github/license/raining-codes/molecube.svg?style=for-the-badge
[license-url]: https://github.com/raining-codes/molecube/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white/
[next-url]: https://microsoft.com/
[react.js]: https://starship.rs/icon.png
[react-url]: https://github.com/shibayan/Sharprompt
[vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[vue-url]: https://vuejs.org/
[angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[angular-url]: https://angular.io/
[svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[svelte-url]: https://svelte.dev/
[laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[laravel-url]: https://laravel.com
[bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-url]: https://getbootstrap.com
[jquery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[jquery-url]: https://jquery.com
