# [Flask Argon Dashboard](https://appseed.us/product/argon-dashboard/flask/)

Open-source **Flask Dashboard** generated by `AppSeed` op top of a modern design. Designed for those who like bold elements and beautiful websites, **[Argon Dashboard](https://appseed.us/product/argon-dashboard/flask/)** is ready to help you create stunning websites and webapps. **Argon Dashboard** is built with over 70 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining.

- 👉 [Flask Argon Dashboard](https://appseed.us/product/argon-dashboard/flask/) - product page
- 👉 [Flask Argon Dashboard](https://flask-argon-dashboard.appseed-srv1.com/) - LIVE deployment
- 👉 [Complete documentation](https://docs.appseed.us/products/flask-dashboards/argon-dashboard) - `Learn how to use and update the product`
  
<br />

> 🚀 Built with [App Generator](https://appseed.us/generator/), timestamp `2022-06-23 18:20`

- ✅ `Up-to-date dependencies`
- ✅ `Database`: `SQLite`, MySql
  - Silent fallback to `SQLite`
- ✅ `DB Tools`: SQLAlchemy ORM, `Flask-Migrate`
- ✅ `Authentication`, Session Based, `OAuth` via **Github**
- ✅ Docker, `Flask-Minify` (page compression)
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

<br />

![Argon Dashboard - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/183684596-4b29a886-f13d-4da5-98d3-12b5b90df47f.png)

<br />

## ✨ Start the app in Docker

> 👉 **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ git clone https://github.com/app-generator/flask-argon-dashboard.git
$ cd flask-argon-dashboard
```

<br />

> 👉 **Step 2** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:5085` in your browser. The app should be up & running.

<br />

## ✨ Manual Build

> Download the code 

```bash
$ git clone https://github.com/app-generator/flask-argon-dashboard.git
$ cd flask-argon-dashboard
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Create Users

By default, the app redirects guest users to authenticate. In order to access the private pages, follow this set up: 

- Start the app via `flask run`
- Access the `registration` page and create a new user:
  - `http://127.0.0.1:5000/register`
- Access the `sign in` page and authenticate
  - `http://127.0.0.1:5000/login`

<br />

## ✨ Code-base structure

The project is coded using blueprints, app factory pattern, dual configuration profile (development and production) and an intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/
   |    |
   |    |-- home/                           # A simple app that serve HTML files
   |    |    |-- routes.py                  # Define app routes
   |    |
   |    |-- authentication/                 # Handles auth routes (login and register)
   |    |    |-- routes.py                  # Define authentication routes  
   |    |    |-- models.py                  # Defines models  
   |    |    |-- forms.py                   # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>          # CSS files, Javascripts files
   |    |
   |    |-- templates/                      # Templates used to render pages
   |    |    |-- includes/                  # HTML chunks and components
   |    |    |    |-- navigation.html       # Top menu component
   |    |    |    |-- sidebar.html          # Sidebar component
   |    |    |    |-- footer.html           # App Footer
   |    |    |    |-- scripts.html          # Scripts common to all pages
   |    |    |
   |    |    |-- layouts/                   # Master pages
   |    |    |    |-- base-fullscreen.html  # Used by Authentication pages
   |    |    |    |-- base.html             # Used by common pages
   |    |    |
   |    |    |-- accounts/                  # Authentication pages
   |    |    |    |-- login.html            # Login page
   |    |    |    |-- register.html         # Register page
   |    |    |
   |    |    |-- home/                      # UI Kit Pages
   |    |         |-- index.html            # Index page
   |    |         |-- 404-page.html         # 404 page
   |    |         |-- *.html                # All other pages
   |    |    
   |  config.py                             # Set up the app
   |    __init__.py                         # Initialize the app
   |
   |-- requirements.txt                     # App Dependencies
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- run.py                               # Start the app - WSGI gateway
   |
   |-- ************************************************************************
```

<br />

## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Argon Dashboard is a premium Bootstrap Design now available for download in Flask. Made of hundred of elements, designed blocks, and fully coded pages, Argon Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [Argon Dashboard PRO Flask](https://appseed.us/product/argon-dashboard-pro/flask/) - Product Page
- 👉 [Argon Dashboard PRO Flask](https://flask-argon-dashboard-pro.appseed-srv1.com/) - LIVE Demo

<br >

![Argon Dashboard PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172859139-621325fd-a235-4019-a75d-64a9a978da29.png)

<br />

---
[Flask Argon Dashboard](https://appseed.us/product/argon-dashboard/flask/) - Open-source starter generated by **[App Generator](https://appseed.us/generator/)**.
