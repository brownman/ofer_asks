packages
----

- shell stuff:

```bash
$ mkdir package1
$ touch package1/__init__.py
$ touch python_demo1.py
```


-  package1/\_\_init\_\_.py

```python

from module1 import Class1 , Class2 
```

- python_demo1.py

```python
#HERE GOES MAGIC:
import package1 

#generate an instance of our class:
instance1 = package1.Class1('my name','my family name')
instance1.show() #hopefuly prints our name and family name.
```
