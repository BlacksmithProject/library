# BlacksmithProject Library

## TODO:

- [ ] You should modify `composer.json` and update `name`, `description`, `authors` and namespaces in `autoload`/`autoload-dev`.
- [ ] You should modify this `README.md`.

## TOOLING

Contains:

- `phpcs`
- `phpstan`
- `phpunit`
- `infection`
- `travisCI`
- `scrutinizer`

Use:

- `make phpcs` to use `phpcs`
- `make phpcs-fix` to fix
- `make stan` to use `phpstan`
- `make test` to use `phpunit`
- `make infection` to use `infection`
- `make CI` for the CI
- modify `CHANGELOG.md` and `make release VERSION=<version_number>` to make a new release
