# python_webserver


## Part one
https://ruslanspivak.com/lsbaws-part1/

python_webserver.py

Simple webserver serving simple hello world.

$ python python_webserver.py

$ curl localhost:8888

## Part two
https://ruslanspivak.com/lsbaws-part2/

python_webserver2.py

Simple webserver able to serve content from differnet frameworks.
* pyramid
* flask
* django
* custome wsgi

$ python python_webserver2.py pyramidapp:app

$ python python_webserver2.py flaskapp:app

$ python python_webserver2.py djangoapp:app

$ python python_webserver2.py wsgiapp:app

$ curl localhost:8888/hello