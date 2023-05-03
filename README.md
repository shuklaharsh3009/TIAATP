# Auction Website
# Motivation

A lot of farmers suffer in the hands of middlemen who exploit them when they are trying to find market for their livestock.
Moreover, buyers are also exploited by the same middlemen/brokers. The aim of building this application is to cut out these brokers and middlemen to prevent 
the exploitations that takes place. This platform provides farmers and buyers a direct link. 

# Technologies Used

* Django Back-end Framework 
* Bootstrap4 Front-End Framework 

## Features

- User Authentification System
- Bidding System
- Admin Dashboard
- Comment System

## Installation

Clone this repository

```
git clone https://github.com/WMKharles/Auction-Site.git
```

Open the folder

```
cd Auction-Site
```

## Create a virtual environment

```
python -m venv venv
```

Activate environment - varies depending on your OS

```
venv\scripts\activate
```

Install all the requirements

```
python -m pip install -r requirements.txt
```

## Make migrations

```
python manage.py makemigrations
```
```
python manage.py migrate
```
## Create Superuser
```
python manage.py createsuperuser
```

## Running Application

```
python manage.py runserver
```

## Contributions

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

## Bug / Feature Request

In case you find a bug, kindly open an issue [here](https://https://github.com/WMKCharles/Auction-Site/issues/new). Include your query and your expected results.

