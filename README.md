
##  make Env

```
$   python -m venv myvenv

$   source myvenv/bin/activate

    or  $  . myvenv/bin/activate
  
  
--> // for myvenv   in (myvenv)

(myvenv) $   python3 -m pip install --upgrade pip
(myvenv) $   pip install  django

        or $   pip install  django~=2.0.0

// It will continue below  in (myvenv)


$   django-admin django_prj mysite .    //end with '.' (dot)

$   python manage.py runserver
or
$   python manage.py runserver 0:8000


```



###  my-com  :   http://192.168.56.101:8000/


###  python manage.py startapp [App's Name]

```

$   python manage.py migrate


$   python manage.py runserver 0:8000
```


