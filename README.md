```sh
$ sudo dnf install pandoc
$ pandoc --version
pandoc 2.19.2
Compiled with pandoc-types 1.22.2.1, texmath 0.12.5.5, skylighting 0.13.2,
citeproc 0.8.1, ipynb 0.2, hslua 2.2.1
Scripting engine: Lua 5.4
```

```sh
$ pandoc test1.rst --from markdown --to html -s -o test1.html
$ pandoc test1.rst --from markdown --to odt -s -o test1.odt
```
