[![CircleCI](https://circleci.com/gh/CIRCLECI-GWP/adonis-api-testing.svg?style=svg)](https://circleci.com/gh/CIRCLECI-GWP/adonis-api-testing)

<p align="center"><img src="https://avatars3.githubusercontent.com/u/59034516"></p>

## Details

This repo is built following a tutorial published on CircleCI blog under the CircleCI Guest Writer Program.

- Blog post: [Continuous integration for Adonis APIs][blog]
- Author's GitHub profile: [Fikayo Adepoju][author]

### About CircleCI Guest Writer Program

Join a team of freelance writers and write about your favorite technology topics for the CircleCI blog. Read more about the program [here][gwp-program].

Reviewers: [Ron Powell][ron], [Stanley Ndagi][stan]


[blog]: https://circleci.com/blog/continuous-integration-for-adonis-apis
[author]: https://github.com/coderonfleek

[gwp-program]: https://circle.ci/3ahQxfu
[ron]: https://github.com/ronpowelljr
[stan]: https://github.com/NdagiStanley

---

# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```
