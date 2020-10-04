<p align="center">
   <img src=".github/logo.png" width="150"/>
</p>

# One Step Taskin Fitness

[![Author](https://img.shields.io/badge/author%20-turzo--ahsan--sami-blue)](https://github.com/turzo-ahsan-sami)
<!-- [![Languages](https://img.shields.io/github/languages/count/LauraBeatris/_one_step_taskin_fitness?color=%23EE4D64&style=flat-square)](#)
[![Stars](https://img.shields.io/github/stars/LauraBeatris/_one_step_taskin_fitness?color=EE4D64&style=flat-square)](https://github.com/turzo-ahsan-sami/_one_step_taskin_fitness/stargazers)
[![Forks](https://img.shields.io/github/forks/LauraBeatris/_one_step_taskin_fitness?color=%23EE4D64&style=flat-square)](https://github.com/turzo-ahsan-sami/_one_step_taskin_fitness/network/members)
[![Contributors](https://img.shields.io/github/contributors/LauraBeatris/_one_step_taskin_fitness?color=EE4D64&style=flat-square)](https://github.com/turzo-ahsan-sami/_one_step_taskin_fitness/graphs/contributors) -->

> Full stack solution to manage a fitness center :rocket:

<!-- <p align="center">
  <img align="center" src="https://i.ibb.co/tM9Bynr/Web-Signin.png" alt="Web-Signin" border="0">
</p>
<br>
<p align="center">
  <img align="center" src="https://i.ibb.co/gP77Lt5/Web-Plans.png" alt="Web-Plans" border="0">
</p> -->
<br>

# :pushpin: Table of Contents

* [Features](#rocket-features)
* [Installation](#construction_worker-installation)
* [Getting Started](#runner-getting-started)
* [FAQ](#postbox-faq)
* [Found a bug? Missing a specific feature?](#bug-issues)
* [Contributing](#tada-contributing)
* [License](#closed_book-license)

# :rocket: Features

* Member
* HRMS
* Plans
* Enrollments and payments
* Procurement

# :construction_worker: Installation

**You need to install [Node.js](https://nodejs.org/en/download/) and [Yarn](https://yarnpkg.com/) first, then in order to clone the project via HTTPS, run this command:**

```git clone https://github.com/turzo-ahsan-sami/gympoiny-api.git```

SSH URLs provide access to a Git repository via SSH, a secure protocol. If you have a SSH key registered in your Github account, clone the project using this command:

```git clone git@github.com:LauraBeatris/_one_step_taskin_fitness.git```


# :runner: Getting Started

Run the transactions in order to configure the database schema

```npx sequelize-cli db:migrate```

Run the following command in order to start the application in a development environment:

```
 // Start the server
  yarn dev

// Run the queue responsable for the mail job
  yarn queue-dev
```

## Status Codes

Gympoint returns the following status codes in its API:

| Status Code | Description |
| :--- | :--- |
| 200 | `OK` |
| 422 | `UNPROCESSABLE ENTITY` |
| 400 | `BAD REQUEST` |
| 404 | `NOT FOUND` |
| 500 | `INTERNAL SERVER ERROR` |

# :postbox: Faq

**Question:** What are the tecnologies used in this project?

**Answer:** The tecnologies used in this project are [NodeJS](https://nodejs.org/en/) + [Express Framework](http://expressjs.com/en/) to handle the server and [Sequelize](https://sequelize.org/)

# :bug: Issues

Feel free to **file a new issue** with a respective title and description on the the [Gympoint API](https://github.com/turzo-ahsan-sami/_one_step_taskin_fitness/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! Have a look at our [contribution guidelines](https://github.com/turzo-ahsan-sami/_one_step_taskin_fitness/blob/master/CONTRIBUTING.md) to find out about the coding standards.

# :tada: Contributing

Check out the [contributing](https://github.com/turzo-ahsan-sami/_one_step_taskin_fitness/blob/master/CONTRIBUTING.md) page to see the best places to file issues, start discussions and begin contributing.

# :closed_book: License

Released in 2020/21.
This project is under the [MIT license](https://github.com/turzo-ahsan-sami/_one_step_taskin_fitness/master/LICENSE).

Developed by [Turzo Ahsan Sami](https://github.com/turzo-ahsan-sami) 🚀