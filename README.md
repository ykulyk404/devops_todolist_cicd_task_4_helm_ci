# Django ToDo list 

This is a todo list web application with basic features of most web apps, i.e., accounts/login, API, and interactive UI. To do this task, you will need:

- CSS | [Skeleton](http://getskeleton.com/)
- JS  | [jQuery](https://jquery.com/)

## Explore

Try it out by installing the requirements (the following commands work only with Python 3.8 and higher, due to Django 4):

```
pip install -r requirements.txt
```

Create a database schema:

```
python manage.py migrate
```

And then start the server (default is <http://localhost:8000>):

```
python manage.py runserver
```

Now you can browse the [API](http://localhost:8000/api/) or start on the [landing page](http://localhost:8000/).

## Task

Extend a GitHub Actions workflow for this project with a Docker build and push to the DockerHub Registry.
Docker CI Job Requirements:

1. Add `docker-ci` job to the workflow.
2. Job should include the following steps:
    1. Login to the DockerHub Registry.
    1. Build and Push Docker image to your existing the DockerHub Registry with a tag of current's commit hash.
    1. Use the provided Dockerfile to build the image.
3. Create a Pull Request with the changes.
4. Pull Requests description should also contain a reference to a workflow run with successfull Docker CI job.
