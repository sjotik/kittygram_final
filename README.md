<br/>
<p align="center">
  <a href="https://github.com/sjotik/kittygram_final">
    <img src="frontend/src/images/logo.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">KITTYGRAM</h3>

  <p align="center">
    Instagram for cats
    <br/>
    <br/>
  </p>
</p>

![workflow](https://github.com/sjotik/kittygram_final/actions/workflows/main.yml/badge.svg)

## Table Of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Technologies](#used-technologies)
* [License](#license)
* [Authors](#authors)

## About The Project

Social network for cats like instagram.
You can share images and achievements your pet cats.

## Getting Started

If you don't have Docker on your server, use manual from [Official page](https://docs.docker.com/engine/install/)

### Installation

1. [Clone](git@github.com:sjotik/kittygram_final.git) this project repo.

2. For starting this project locally use next command from project directory:

`docker compose up -d`

Open http://127.0.0.1:9000 in browser. **ENJOY**

### ENV variable

Project use PostgresQL database and for deploy you need create **.env** file in root directory with variables:
+ POSTGRES_DB=***set_name_for_DB***
+ POSTGRES_USER=***set_db_user***
+ POSTGRES_PASSWORD=***set_password***
+ DB_HOST=**db**
+ DB_PORT=**5432**

Also there is taken out django variables **SECREC_KEY** and **DEBUG**. You need to set them.

## Used Technologies

* Python
* REST_Framework
* React
* PostgresQL
* Docker Compose

## License

Distributed under the MIT License. See [LICENSE](https://github.com/sjotik/kittygram_final/blob/main/LICENSE.md) for more information.

## Authors

* [**Sjotik**](https://github.com/sjotik/)
