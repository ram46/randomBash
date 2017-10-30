
#### Change extension in filenames 

###### Task

A directory contains a list of files with .js extension. Goal is to change the extension only from .js tp .py.

###### Solution

```for jsName in `ls`; do pyName=`echo $jsName | sed s/js/py/`; mv $jsName $pyName; done```
