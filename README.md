# Competitive Pokémon Graph Database

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

The idea behind the project is to create a database containing all information related to competitive Pokémon videogame, with particular reference to the Video Game Championship Series 12 rules, the official format in effect for official tournaments and events during the period February - August 2022 and valid for the Pokémon World Championship in London in August 2022. The goal is to obtain a useful tool as a support for competitive play, both for novice and experienced players. The different Pokémon are placed in relation to the teammates, moves, tools, skills the basic statistics with which they are most frequently matched within teams in competitive matches. For this reason, the choice on the type of database to be implemented fell on a graph database, implemented through Neo4J. The choice of the graph database allowed us to take advantage of its characteristic of being schema less, which allows us to create nodes, to model the different entities, and arcs, to model the various relationships, without following a predefined schema. The database was populated through data obtained through API and Web Scraping, appropriately integrated and processed.

![PokemonCopertina](https://user-images.githubusercontent.com/80491610/177854097-0d5a62c7-6b56-497f-b2d7-6a467a46ce80.png)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/giocoal/Competitive-Pokemon-Graph-Database.svg?style=for-the-badge
[contributors-url]: https://github.com/giocoal/Competitive-Pokemon-Graph-Database/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/giocoal/Competitive-Pokemon-Graph-Database.svg?style=for-the-badge
[forks-url]: https://github.com/giocoal/Competitive-Pokemon-Graph-Database/network/members
[stars-shield]: https://img.shields.io/github/stars/giocoal/Competitive-Pokemon-Graph-Database.svg?style=for-the-badge
[stars-url]: https://github.com/giocoal/Competitive-Pokemon-Graph-Database/stargazers
[issues-shield]: https://img.shields.io/github/issues/giocoal/Competitive-Pokemon-Graph-Database.svg?style=for-the-badge
[issues-url]: https://github.com/giocoal/Competitive-Pokemon-Graph-Database/issues
[license-shield]: https://img.shields.io/github/license/giocoal/Competitive-Pokemon-Graph-Database.svg?style=for-the-badge
[license-url]: https://github.com/giocoal/Competitive-Pokemon-Graph-Database/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/giorgio-carbone-63154219b/
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
