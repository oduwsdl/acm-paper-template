# ACM Paper Template

A starter LaTeX template for ACM conferences such as JCDL.

```
$ git clone https://github.com/oduwsdl/acm-paper-template YOUR_PAPER_NAME
$ cd YOUR_PAPER_NAME
$ rm -rf .git
$ make
```

Use additional `techreport` class parameter to hide unnecessary conference metadata:

```
\documentclass[sigconf,techreport]{acmart}
```
