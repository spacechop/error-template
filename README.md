# SpaceChop Error Template

Welcome! If you are here then you were likely referred to this repo when reporting an error to [`spacechop/spacechop`][1]. The core team is invested in making the best tool for image processing as possible, so when you hit an error it is important to the team that the error is resolved as soon as possible.

Unfortunately, describing an error in GitHub is often not enough to truly understand the reported issue. By creating a small reproduction test case using this template repo the SpaceChop team will be able to identify and fix your error much faster then they could without.

This repo was created with [`docker-compose`][2] for a great developer experience. If you are not using docker-compose then a small reproduction case with your framework of choice would go a long way.

To make changes in the configuration make sure to look at the `./config.yml` file where we define the configuration using [yaml][3] which will be validated in the SpaceChop docker container.

[1]: https://github.com/spacechop/spacechop
[2]: https://github.com/docker/compose
[3]: http://yaml.org/

# Reproduction Creation Steps

1. Fork this repository to your GitHub account.
2. After cloning, install all dependencies with `npm install`.
3. Start the development server with `docker-compose up -d`.
4. Make the changes that will reproduce this error locally.
5. When ready, push your changes back to GitHub and let the `SpaceChop` team know where they can be found.
