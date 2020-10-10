# Django Rest Base

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Contributing](#contributing)
* [License](#license)

<!-- ABOUT THE PROJECT -->
## About The Project
![Swagger view](/documentation/images/swagger_screenshot.png)
I always start every django project by configuring some swagger documentation and adding a user view and serializer. This repository serves as a base project that can be cloned and installed with all of these things already set up.

### Built With
* [Django](https://docs.djangoproject.com/en/3.1/intro/overview/)
* [Django Rest Framework](https://www.django-rest-framework.org/tutorial/quickstart/)
* [Yet Aother Swagger Generator](https://github.com/axnsan12/drf-yasg)

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
`python3`,  `pip`, and `virtualenv` are needed to get started. All three of these should come with the latest installation of python.

### Installation

1. Clone the repo
```sh
git clone https://github.com/pplum09/django-rest-base.git
cd django-rest-base
```

2. Create python virtual environment
```sh
python3 -m venv venv
source venv/bin/activate
```
Run `source venv/bin/activate` from the project directory any time you want to start developing. Use command `deactivate` to exit out of the python virtual environment.

3. Install dependencies
```sh
pip3 install -r requirements.txt
cd api
```

4. Migrate the database
```sh
python manage.py migrate
```

5. Create superuser
```sh
python manage.py createsuperuser
```

6. Run server
```sh
python manage.py runserver
```
Your base app should now being running at [http://localhost:8000](http://localhost:8000)
Swagger docs are at [http://localhost:8000/swagger/](http://localhost:8000/swagger/)

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->
## License
Distributed under the MIT License.
