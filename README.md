# django-app
Django-Marcus

Run the following commands respectively in the project's directory.

### Get project's requirements
1. ```pip freeze > requirements.txt```

### Install the requirements
2. ``` pip install -r requirements.txt```


# Changes
Navigate to:

```django/djangoSite/contentApp/templates/contentApp/videos.html```

#### Change the following to link to videos after pasting the videos in ```django/djangoSite/static/media/```

Replace the instances below with video file name e.g.(myvideo.mp4)


```PATH_TO_MP4_VIDEO_FILE```


### Create SQLite databse, run migrations

1. ```python manage.py migrate```

2. ``` python manage.py runserver```



