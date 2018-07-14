Telegram GUI running in Docker
==============================

how to use
----------

first run:
```docker run -d --name telegram -e DISPLAY -v /tmp/.X11-unix/:/tmp/.X11-unix malvex/telegram```

next runs:
```docker start telegram```


