# Blogpaper

## Description

A blog-style web application built with Django. Users can create, publish, edit and delete their articles, as well as comment on other users' posts.

## Try it 
Click [here](https://lth-newspaper-8ffa74dfa98b.herokuapp.com/) to try it. Enjoy 😊 

### Current features
**User Authentication**

- Users can create accounts and log in securely.
- Password reset functionality is available to help users regain access to their accounts if they forget their passwords.

**Article Management**

- Authenticated users can write and publish articles.
- Authors have the ability to edit and delete their own articles.
- Articles display the author's name, publication date, and a title.
- Visitors can not read articles without an account.

**Comment System**

- Authenticated users can leave comments on articles.
- Comments show the commenter's name and content.
- Only superuser can moderate and delete comments on articles.

### Next Feature
- User can upload image on their article
- Visitors can read articles without needing an account.

## Setup
To run this Django application locally, follow these steps:

1 . Clone the repository to your local machine:
```bash
git clone https://github.com/LudoTreb/news_paper.git
```
2 . Create a virtual environment and activate it & install dependencies:

```bash
python -m venv .venv 
source .venv/bin/activate
pip install -r requirements.txt 
```

## Run the code
Run the server from the root folder
```
python manage.py runserver
```  
and open in browser this adress: <http:/127.0.0.1:8000/>

## How to use it
You can create an account with the signup button or you can use this account ⬇️  
Username: fake_user0  
Password: fake_password0 
