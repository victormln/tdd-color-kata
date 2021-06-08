# tdd-color-kata

This repository has a simple PHP container with composer and phpunit in order to show in a kata the benefits of TDD.

# Installation

Build docker image:
`docker compose build php8`

Start the containers:
`docker compose up`

Enter inside the container of php:
`docker exec -it php8 bash`

Install all composer dependencies:
`composer install`

Execute phpunit:
`vendor/bin/phpunit`