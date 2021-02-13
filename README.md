# django-app
Django-Marcus

Run the following commands respectively in the project's directory.

### Get project's requirements
1. ```pip freeze > requirements.txt```

### Install the requirements
2. ``` pip install -r requirements.txt```


# Changes

#### Create ```media``` dir in ```django/djangoSite/static/``` an paste video files

Navigate to:

```django/djangoSite/contentApp/templates/contentApp/videos.html```

Replace the instances below with video file name e.g.(myvideo.mp4)


```PATH_TO_MP4_VIDEO_FILE```


### Create SQLite databse, run migrations

1. ```python manage.py migrate```

2. ``` python manage.py runserver```



Best
