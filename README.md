# Parrit

A historical recommendation engine for daily pair rotation management, with an interactive visual aide of each pairing team.

## Tech Stack

- Spring Boot
- ReactJS
- Webpack
- Gradle

## Core Contributors

Big shoutout to the following people for helping to guide the direction that Parrit took. Core contributors also please feel free to add others to the core contributor list for those who significantly shape the direction of Parrit.

- [Anthony Dreessen](mailto:anthonydreessen@gmail.com) - Product Owner, Product Management + Full-stack Development
- [Darcie Fitzpatrick](mailto:darciefitzpatrick@gmail.com) - Product Design, Product Management + User Research
- [Cat Zhang](mailto:cielzee@gmail.com) - Product Management + Product Design
- [Joseph Greubel](mailto:joegreubel1@gmail.com) - Front-end Development, Back-end Development
- [Michael Oleske](mailto:moleske@pivotal.io) - Back-end Development

As of 2025, `parrit.io` was taken over by someone, and the original Parrit team is no longer maintaining the site. I (@mahata) have forked the project to revive the service.

## Want to contribute?

* See [Contributing](./docs/Contributing.md)

## Running Server Locally

1. Create postgres user with name `parrit` password `parrit`
2. create new database called `local_parrit`
3. migrate the database with `gradle migrate`
4. Run application through `./gradlew bootRun`
