# Repo Stats
![GitHub Repo stars](https://img.shields.io/github/stars/LukeGus/Containix?style=flat&label=Stars)
![GitHub forks](https://img.shields.io/github/forks/LukeGus/Containix?style=flat&label=Forks)
<a href="https://discord.gg/jVQGdvHDrf"><img alt="Discord" src="https://img.shields.io/discord/1347374268253470720"></a>

If you would like, you can support the project here!\
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/LukeGustafson803)

# Overview
Containix is a list of popular self-hosted Docker compose files. This repo stands as a storage place for said compose files, and is used in the "Compose Store" feature of my project [Dashix]("https://dashix.dev").

# How to contribute?

Containix is almost entirely run by the community. To add your self-hosted service to the list, create a GitHub [Issue]("https://github.com/LukeGus/Containix/issues") with the following template:
```
### Service Name
[Insert the name of the service you’re submitting, e.g. nginx, redis]

### Example docker-compose.yml
[Paste a working example of the docker-compose.yml config for this service]

### Documentation or references
[Add links to the official docs, Docker Hub page, or GitHub repo]

### Notes
[Any other context or setup instructions]
```
Before submitting a compose file, ensure the following are true:
- All comments in the file have been removed
- Unnecessary ports, environment variables, etc., have been removed
- The Docker image is publicly available to pull
- All environment variables should be included within the text, not within a .env file
- If possible, use the `latest` tag for the image

# License
Distributed under the MIT license. See LICENSE for more information.
