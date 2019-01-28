# CXA Python CLI Template

Python 3.7 based template for a Flask web server

## Usage

1. Install Pipenv https://pipenv.readthedocs.io/en/latest/install/#installing-pipenv
2. Run `pipenv run python cxa.py install` to install the project dependencies
3. Run `pipenv run python cxa.py run` to run the example app

### Code Formatting and Linting

#### Formatting

Run `pipenv run python cxa.py format` to run the Black formatter.

#### Linting

Run `pipenv run python cxa.py lint` to run Black and Flake8.

## Template Variables

-   project_name: string with no whitespace
-   project_human_name: string
-   description: string
-   author: string
-   author_email: _optional_ string
-   website: _optional_ string
-   repository: _optional_ string
-   license: _optional_ string
-   max_line_length: integer
