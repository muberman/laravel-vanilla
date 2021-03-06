# Vanilla Laravel

### Setup

- git clone git@github.com:DeSmart/laravel-vanilla.git .
- . dev.sh
- dc up -d
- chmod -R 0777 bootstrap/ storage/ (on host machine)
- cp .env.example .env
- dc run api composer install --prefer-source
- dc run api php artisan key:generate
- dc run api php vendor/bin/codecept bootstrap

---

# Project Name

Some introduction text here.

---

### Setup
This project requires **Docker** to run. If you don't have Docker installed, please visit https://www.docker.com/ and follow the instructions regarding installation. Once you have Docker installed, proceed with the instructions below.

1. Clone the project from GitLab:
```
git clone git@git.desmart:foo/bar.git .
```

2. Run `composer install`.
3. Do all sorts of crazy stuff to get the project up and running.

---

### Deployment

##### Test
1. `ssh project-name`
2. `cd /var/www/project`
3. `phing build`
4. eat popcorn

##### Beta
1. `ssh project-name`
2. `cd /var/www/project`
3. `phing build`
4. eat popcorn

##### Production
1. `ssh project-name`
2. `cd /var/www/project`
3. `phing build`
4. eat popcorn

---

### Environment
- PHP: 7.0
- MySql: 5.6

---

### Developers
- **Back-end / API** - John Doe, john.doe@desmart.com, mobile +48 555 666 777
- **iOS / Android** - John Doe, john.doe@desmart.com, mobile +48 555 666 777
- **QA** - John Doe, john.doe@desmart.com, mobile +48 555 666 777

---

### Client
- **Product Owner** - John Doe, john.doe@desmart.com, mobile +48 555 666 777
- **Graphic Designer** - John Doe, john.doe@desmart.com, mobile +48 555 666 777

---

### Resources
- **Issue tracker** - https://pivotaltracker.com/n/projects/123
- **Prototype** - https://uxpin.com/foobar
- **Docs** - https://drive.google.com/foobar

---

### Tests
In order to run tests use the following commands:

##### PHPUnit
- run `vendor/bin/phpunit --verbose`

##### PHPSpec
- run `vendor/bin/phpspec run --verbose`

---

### Instances

##### Test
- **API**: http://foo.desmart.com
- **Front-end**: http://bar.desmart.com

##### Beta
- **API**: http://foo.desmart.com
- **Front-end**: http://bar.desmart.com

##### Production
- **API**: http://foo.desmart.com
- **Front-end**: http://bar.desmart.com

---

### Introducing new developer

List of actions needed to be taken when introducing a new developer to the project (e.g. one developer is leaving for holidays and wants to pass his know-how to a new person).

- install and configure the project
- give SSH access
- show pictures of cats
