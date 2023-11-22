# Books API

A Django-based Book API project with a dedicated API app, traditional Django setup, and integration of Django Rest Framework (DRF).

## Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Django Templates](#django-templates)
- [Contributing](#contributing)
- [License](#license)

## About

The Book API project is designed to provide a flexible and extensible solution for managing and retrieving information about books. It uses Django for the backend, Django Rest Framework for the API, and includes a traditional Django setup with templates.


## Features

- Dedicated API app (`api`) for managing book-related functionality.
- Traditional Django setup with models, views, and templates.
- Integration of Django Rest Framework (DRF) for building the API.

## Getting Started

### Prerequisites

Make sure you have Python, Pipenv, and Django installed on your machine.

```bash
# Example installation commands
pip install pipenv
pipenv install
```

## Installation

1. **Clone the repository.**

    ```bash
    git clone https://github.com/bagoviggo/Books_api.git
    cd Books_api
    ```

2. **Install dependencies.**

    ```bash
    pipenv install
    ```

3. **Apply migrations.**

    ```bash
    pipenv run python manage.py migrate
    ```

4. **Run the development server.**

    ```bash
    pipenv run python manage.py runserver
    ```

## Usage

Access the Django admin interface at [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) to manage books. The API is available at [http://127.0.0.1:8000/api/](http://127.0.0.1:8000/api/).

## API Endpoints

- `/api/books/`: List and create books.
- `/api/books/<book_id>/`: Retrieve, update, or delete a specific book.

## License

This project is licensed under the [MIT LICENSE] - see the [LICENSE.md](LICENSE.md) file for details.


