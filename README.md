# Scripts

##b734k
Using Console :
```
$ php -f index.php
b374k shell packer 0.4

options :
        -o filename                             save as filename
        -p password                             protect with password
        -t theme                                theme to use
        -m modules                              modules to pack separated by comma
        -s                                      strip comments and whitespaces
        -b                                      encode with base64
        -z [no|gzdeflate|gzencode|gzcompress]   compression (use only with -b)
        -c [0-9]                                level of compression
        -l                                      list available modules
        -k                                      list available themes
```
example :
```
$ php -f index.php -- -o myShell.php -p myPassword -s -b -z gzcompress -c 9
