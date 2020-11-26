# Email with AJAX

## Installation
Clone the repo to your local dev environment. This uses PHP on the back end, so you'll need something like WAMP or MAMP to run it (alternatively configure a Docker project and run it that way).

## Docker
- Run `docker-compose up` and then visit the site in http://localhost:3040
- Mailhog can be found in http://localhost:8025

## Usage
Pretty straightforward - navigate to the live instance and try submitting an email. The endpoint isn't connected to an API at this point - just a simple POST check and it returns back a success or error message, depending on the outcome.

CSS is generated with SASS using the command line tools. You'll need dart-sass (preferred) - [you can get it here](https://sass-lang.com/install)

## License
MIT
