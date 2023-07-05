
# Chat Room

A website made in **Django** which is a web framework in **Python**.
- You can host rooms with a title and a topic where people can join your room and discuss on it through chatbox.
- User can edit their profile by adding a profile picture to it.
- User can delete their messages from chatbox as well as from activity feed.
- You can search the room of the topics you want from search bar or from the topics area.
- A **Dockerfile** in the repo to build the docker image of the website


## Run Locally

Install requirements

```bash
  pip install --no-cache-dir -r requirements.txt
```

Initialise the database model

```bash
  python manage.py makemigrations
  python manage.py migrate
```

Run the server

```bash
  python manage.py runserver
```

### Run with Docker

Build docker image

```bash
  docker build -t chat-room .
```

Run the docker Image

```bash
  docker run -p 8000:8000 chat-room
```

## Screenshots

![ss1](https://github.com/AkramExp/chat-room/blob/main/screenshots/ss1.png)

![ss2](https://github.com/AkramExp/chat-room/blob/main/screenshots/ss2.png)

![ss3](https://github.com/AkramExp/chat-room/blob/main/screenshots/ss3.png)

