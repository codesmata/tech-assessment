.PHONY: test composer db

SHELL:=/bin/bash

setup: composer db

composer:
	composer install

test:
	./vendor/bin/phpunit tests/

db:
	php Database/schema.php