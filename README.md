Python Study

-----

## Django---Windows Installation

* 1.install python

http://www.python.org/download/releases/2.7.6/

http://legacy.python.org/ftp//python/2.7.6/python-2.7.6.msi

将C:\Python27\Scripts加入环境变量path中

* 2.install setuptools

https://pypi.python.org/pypi/setuptools#downloads

https://pypi.python.org/packages/2.7/s/setuptools/setuptools-0.6c11.win32-py2.7.exe#md5=57e1e64f6b7c7f1d2eddfc9746bbaf20

* 3.install pip

https://pypi.python.org/pypi/pip#downloads

https://pypi.python.org/packages/source/p/pip/pip-1.5.4.tar.gz#md5=834b2904f92d46aaa333267fb1c922bb

D:\Downloads\pip-1.5.4>python setup.py install

* 4.pip install Django

C:\Users\Administrator>pip install Django

Downloading/unpacking Django

Installing collected packages: Django

Successfully installed Django

Cleaning up...


* 5.install apache,mod_python

 or nginx
 
 http://nginx.org/en/download.html
 
 http://nginx.org/download/nginx-1.5.11.zip
 
 http://nginx.org/cn/docs/windows.html
 
cd nginx

start nginx

http://www.cnblogs.com/wenanry/archive/2012/01/18/2325140.html



* 6.create proj

http://www.cnblogs.com/way_testlife/archive/2011/03/22/1991453.html

cd djangoWorkspaces

django-admin.py startproject mysite

python manage.py runserver

try: http://127.0.0.1:8000/

python manage.py runserver 0.0.0.0:8080


## web.py---Linux Installation

* install MySQL-python

yum install MySQL-python

* install web.py

wget http://webpy.org/static/web.py-0.37.tar.gz

tar zxvf web.py-0.37.tar.gz

cd web.py-0.37

python setup.py install
