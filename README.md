# Heroku Demo
This repository contains a very simple PHP file demonstrating how to use Heroku to deploy a PHP application. The purpose of this repository is to help beginners understand the basic steps involved in deploying a PHP file to Heroku.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Deploying to Heroku](#deploying-to-heroku)
- [Demo Video](#demo-video)

<a name="introduction"></a>
## Introduction
Heroku is a cloud platform as a service (PaaS) that allows you to deploy, manage, and scale applications. This repository contains a minimal PHP file to guide you through the process of deploying a PHP application on Heroku.

<a name="prerequisites"></a>
## Prerequisites
Before you begin, ensure you have the following installed on your local machine:
- [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli)
- [Git](https://git-scm.com/)

<a name="getting-started"></a>
## Getting Started
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/batouldiab/heroku-demo.git
   ```

2. Navigate to the project directory:
   ```bash
   cd heroku-demo
   ```
   
3. Open index.php file and modify it according to your requirements.

<a name="deploying-to-heroku"></a>
## Deploying to Heroku
Follow these steps to deploy the PHP file to Heroku:

- Create a Heroku Account:
If you haven't already, sign up for a free account on [Heroku](https://www.heroku.com/).

- Login to Heroku:
Open your terminal and login to your Heroku account using the following command:
```bash
heroku login
```

- Create a Heroku App:
Create a new Heroku app using the Heroku CLI:
```bash
heroku create
```

- Deploy Your App:
Deploy your PHP file to Heroku:
```bash
git push heroku master
```

- Open Your App:
Once the deployment is successful, you can open your app in the browser:
```bash
heroku open
```

<a name="demo-video"></a>
## Demo Video
For a detailed demonstration of how to deploy a PHP file on Heroku, check out our demo video in Persian language: [Heroku Demo (بتول ذیاب - منیر خسروی)](https://www.youtube.com/watch?v=FltkQDNx5g8&t=1432s).
