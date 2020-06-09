<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
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


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/vzdrizhni/re-former">
    <img src="app/assets/images/microverse.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Bare Metal Forms and Helpers</h3>

  <p align="center">
    This project is part of the Microverse curriculum in Ruby on Rails module!
    <br />
    <a href="https://github.com/vzdrizhni/re-former"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/vzdrizhni/re-former/issues">Report Bug</a>
    ·
    <a href="https://github.com/vzdrizhni/re-former/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
  * [Usage](#usage)
* [Contributors](#contributors)
* [Acknowledgements](#acknowledgements)
* [License](#license)

<!-- ABOUT THE PROJECT -->
## About The Project

This project is about learning the multiple ways to build a form in rails that can send parameters to a controller so that it can build an instance of a model with those parameters.

### Built With
This project was built using these technologies.
* Ruby & Ruby on Rails
* SQLite
* Rubocop
* Stickler
* Atom :atom:

<!-- INSTALLATION -->
## Usage

To have this app on your pc, you need to:
* have Ruby & Ruby on Rails installed in your computer
* [download](https://github.com/vzdrizhni/re-former/archive/develop.zip) or clone this repo:
  - Clone with SSH:
  ```
    git@github.com:vzdrizhni/re-former.git
  ```
  - Clone with HTTPS
  ```
    https://github.com/vzdrizhni/re-former.git
  ```
* and open the terminal inside the repo and run the bundler
  - ```$ bundler install```
* then, run rails db:migrate. This creates the database with the corresponding tables, columns and associations
  - ```$ rails db:migrate```
* and finally, you can test it in the console by running
  - ```$ rails server``` and using the ```localhost:3000/users/new``` to create a new user
* and try out the [new](http://localhost:3000/users/new) 

![screenshot](app/assets/images/re-former_new.png)

* and [edit](http://localhost:3000/users/1/edit) (you have to create an user first to see this page)

![screenshot](app/assets/images/re-former_edit.png)


<!-- AUTOMATED TEST -->
### Automated Test

> There are no Automated Test for this project yet

<!-- CONTACT -->
## Contributors

👤 **Roman Nikolaev** 
    
- LinkedIn: [Roman Nikolaev](https://www.linkedin.com/in/roman-nikolaev-65b639197/) - 
- GitHub: [@vzdrizhni](https://github.com/vzdrizhni)
- E-mail: vzdrizhni@gmail.com

👤 **Alexandru Bangau**

- LinkedIn: [Alexandru Bangau](https://www.linkedin.com/in/alexandru-bangau/)
- GitHub: [@rammazzoti2000](https://github.com/rammazzoti2000)
- E-mail: bangau.alexandru@gmail.com

## :handshake: Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/vzdrizhni/re-former/issues).

## Show your support

Give a :star: if you like this project!


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Microverse](https://www.microverse.org/)
* [The Odin Project](https://www.theodinproject.com/)
* [Ruby Documentation](https://www.ruby-lang.org/en/documentation/)
* [Ruby on Rails](https://rubyonrails.org/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/vzdrizhni/re-former.svg?style=flat-square
[contributors-url]: https://github.com/vzdrizhni/re-former/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/vzdrizhni/re-former.svg?style=flat-square
[forks-url]: https://github.com/vzdrizhni/re-former/network/members
[stars-shield]: https://img.shields.io/github/stars/vzdrizhni/re-former.svg?style=flat-square
[stars-url]: https://github.com/vzdrizhni/re-former/stargazers
[issues-shield]: https://img.shields.io/github/issues/vzdrizhni/re-former.svg?style=flat-square
[issues-url]: https://github.com/vzdrizhni/re-former/issues
[product-screenshot]: app/assets/images/micro_reddit.png

## 📝 License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.
