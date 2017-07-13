httpBin
=======

![Screenshot](http://grabs.lucasmouilleron.com/Screen%20Shot%202017-07-13%20at%2010.07.46.png)

HTTP Client Testing Service.

Fork of http://httpbin.org.

Install
-------
- `pip install -r requirements.txt`

Run
---
- `cd .`
- `gunicorn -b localhost:8080 httpbin:app`