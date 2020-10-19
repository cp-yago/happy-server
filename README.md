<div align="center">
	<h1>Happy Server</h1>
</div>

<div align="center">
	<img src="/.github/happy-banner.png" alt="banner" width="80%" />
</div>

<div align="center">
	<h3>What is Happy? 🚪</h3>
</div>

Happy is a project that was developed during **Next Level Week 3**. An online event organized by [Rocketseat](https://rocketseat.com.br/) 
that aims to **up the career of developers** by challenging them to build a **complete application**. We built an API, a website and a mobile application.In this repositorie you can check the API.

<p align="center">
	<img alt="Repository size" src="https://img.shields.io/github/repo-size/cp-yago/happy-server">
	<a href="https://www.linkedin.com/in/yagocunha/">
	  <img alt="made by" src="https://img.shields.io/badge/made%20by-Yago%20Cunha-orange">
	</a>
	<a href="https://github.com/cp-yago/happy-server/commits/master">
	  <img alt="last commit" src="https://img.shields.io/github/last-commit/cp-yago/happy-server">
	</a>
	<a href="https://github.com/cp-yago/happy/issues">
		<img alt="issues" src="https://img.shields.io/github/issues/cp-yago/happy-server">
	</a>
	<a href="https://github.com/cp-yago/happy/network/members">	
		<img alt="forks" src="https://img.shields.io/github/forks/cp-yago/happy-server">	
	</a>
	<a href="https://github.com/cp-yago/happy/stargazers">
		<img alt="stars" src="https://img.shields.io/github/stars/cp-yago/happy-server">
	</a>
	<a href="https://github.com/cp-yago/happy-server/blob/master/LICENSE.md">
		<img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT">	
	</a>
	<!-- version, status da build, status dos testes -->
</p>

<div align="center">
	<h3>Whats the idea?</h3>
</div>

Inspired by October 12th (Children's day in Brazil) we create this application to help orphanages share their location and main informations to visit the children 
and make then more **happy**.


<div align="center">
	<h3>See too</h3>

[Happy Web](https://github.com/cp-yago/happy-web) ||
[Happy Mobile](https://github.com/cp-yago/happy-mobile)
</div>


<div align="center">
	<h3>Technologies</h3>
</div>

- [TypeScript](https://www.typescriptlang.org/docs/home.html) language
- [Node.js](https://nodejs.org/en/docs/) for the API
- [ReactJS](https://reactjs.org/docs/getting-started.html) for the website
- [React Native](https://reactnative.dev/docs/getting-started) and [Expo](https://docs.expo.io/) for the mobile application

<div align="center">
	<h3>Server 📡</h3>
</div>

<h4>Routes</h4>

- [Click here](.github/insomnia.json), copy the content, create .json with it, and import it on [Insomnia](https://insomnia.rest/)

<h4>Main libs</h4>

- [Express](https://expressjs.com/) as web application framework
- [Sqlite3](https://www.sqlite.org/docs.html) and [TypeORM](https://typeorm.io/) for database
- [Multer](https://www.npmjs.com/package/multer) to upload images
- [Yup](https://www.npmjs.com/package/yup) for validation

<h4>How to run it on your computer</h4>

- Install [Node.js](https://nodejs.org/en/download/), [Yarn](https://classic.yarnpkg.com/en/docs/install/#debian-stable) (or use npm), and [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git), then:

```
# clone this repo
$ git clone https://github.com/cp-yago/happy-server.git

# go to api folder
$ cd happy-server

# install dependencies
$ yarn

# run migrations
$ yarn typeorm migration:run

# Change to your computer's IP on .env file

# run the server
$ yarn dev
```
