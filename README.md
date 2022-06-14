# Fake News Detector

[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/varisha-025/fake-news-app/pulls)

[Demo Link](https://newsdetectionapp.herokuapp.com/)

This website is an ML model created using Sklearn and NLP, integrated with Django, hosted on Heroku. It predicts whether the given news headline or news URL is fake or not. The dataset we used is the one available in kaggle with some Asian news web scraped from the internet using the trafilatura library.

[Final dataset link](https://drive.google.com/file/d/1ifXihj-jnWlZkVx-ZnLF8L2ETLaqSjyZ/view?usp=sharing)


## Reasons for building this website

- It was a group project build under an event , Dev Drive, organised by The Programming Club(TPC), at IIITDM Jabalpur.
- Learning Sklearn, NLP, web scraping and its integration with frontend.

## Key Features

- It can predict whether a news is fake or not using either of the two things:
  - News headline
  - News URL
- It enlists news headlines with a short description fetched from the NEWS API.

## Tech Stack

- Django
- Sklearn
- News API
- Heroku

## Contribution Guidelines

- Write clear meaningful git commit messages.
- Always create another branch and it should have a relevant name.
- When you make minor changes to a PR of yours (like for example fixing a text in button, minor changes requested by reviewers) make sure you squash your commits afterward so that you don't have too many commits for a very small fix.
- When you're submitting a PR for a UI-related issue, it would be really great if you add a screenshot of your change or a link to a deployment where it can be tested out along with your PR. It makes it very easy for the reviewers and you'll also get reviews quicker.
