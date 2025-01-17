<p align="center">
  <a href="https://consumet.org/">
    <img alt="Consumet" src="https://consumet.org/images/consumetlogo.png" width="150">
  </a>
</p>

<h1 align="center">
  Consumet API
</h1>
<p align="center">
  Consumet provides an APIs for accessing information and links for various entertainments like movies, books, anime, etc.
</p>
<p align="center">
    <a href="https://github.com/consumet/consumet-api/actions/workflows/docker-build.yml">
      <img src="https://github.com/consumet/consumet-api/actions/workflows/docker-build.yml/badge.svg" alt="Discord">
    </a>
    <a href="https://github.com/consumet/consumet-api/actions/workflows/codeql-analysis.yml">
      <img src="https://github.com/consumet/consumet-api/actions/workflows/codeql-analysis.yml/badge.svg" alt="Discord">
    </a>
    <a href="https://discord.gg/qTPfvMxzNH">
      <img src="https://img.shields.io/discord/987492554486452315?color=7289da&label=discord&logo=discord&logoColor=7289da" alt="Discord">
    </a>
    <a href="https://github.com/consumet/api/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/consumet/api" alt="GitHub">
  </a>
</p>

Consumet scrapes data from various websites and provides APIs for accessing the data to satisfy your needs.

<h2> Table of Contents </h2>

- [Installation](#installation)
  - [Locally](#locally)
  - [Docker](#docker)
  - [Heroku](#heroku)
- [Documentation](#documentation)
- [Development](#development)
- [Provider Request](#provider-request)
- [Support](#support)
- [Related repositories](#related-repositories)

## Installation
### Locally
installation is simple.

Run the following command to clone the repository, and install the dependencies.

```sh
git clone https://github.com/consumet/consumet-api.git
cd consumet-api
npm install #or yarn install
```

start the server!

```sh
npm start #or yarn start
```

### Docker
Docker image is available at [Docker Hub](https://hub.docker.com/r/riimuru/consumet-api).

run the following command to pull and run the docker image.

```sh
docker pull riimuru/consumet-api
docker run -p 3000:3000 riimuru/consumet-api
```
This will start the server on port 3000. You can access the server at http://localhost:3000/, And can change the port by changing the -p option to `-p <port>:3000`.

You can add `-d` flag to run the server in detached mode.

### Heroku
Host your own instance of Consumet API on Heroku using the button below.

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/consumet/consumet-api/tree/main)

## Documentation
Please refer to the [documentation](https://docs.consumet.org). Join our [Discord server](https://discord.gg/qTPfvMxzNH) if you need any additional help or have any questions, comments, or suggestions.

## Development
Pull requests and stars are always welcome, for bugs and features create a new [issue](https://github.com/consumet/consumet-api/issues). If you're brave to make make a commit to the project see [CONTRIBUTING.md](https://github.com/consumet/extensions/blob/master/docs/guides/contributing.md).

## Provider Request
Make a new [issue](https://github.com/consumet/consumet.ts/issues/new?assignees=&labels=provider+request&template=provider-request.yml) with the name of the provider on the title, as well as a link to the provider in the body paragraph.

## Support
You can contact the maintainers of consumet.ts via [email](mailto:consumet.org@gmail.com), or [join the discord server](https://discord.gg/qTPfvMxzNH) (Recommended).

<a href="https://discord.gg/qTPfvMxzNH">
   <img src="https://discordapp.com/api/guilds/987492554486452315/widget.png?style=banner2">
</p>

## Related repositories
 - [Consumet.ts](https://github.com/consumet/extensions)
 - [Website](https://github.com/consumet/consumet.org)
 - [Providers Status](https://github.com/consumet/providers-status)
