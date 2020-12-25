# flask_tutorial
flask官方教程用例

Run

```
$ export FLASK_APP=flaskr
$ export FLASK_ENV=development
$ flask init-db
$ flask run
```

Or on Windows cmd:

```
> set FLASK_APP=flaskr
> set FLASK_ENV=development
> flask init-db
> flask run
```

Open http://127.0.0.1:5000 in a browser.

将项目打包并安装到本地

```
pip install -e .
```

可以通过 pip list 来查看项目的安装情况。

```
$ pip list

Package        Version   Location
-------------- --------- ----------------------------------
click          6.7
Flask          1.0
flaskr         1.0.0     /home/user/Projects/flask-tutorial
itsdangerous   0.24
Jinja2         2.10
MarkupSafe     1.0
pip            9.0.3
setuptools     39.0.1
Werkzeug       0.14.1
wheel          0.30.0
```
