pythonlib
=========

pythonlib is a pure and fast OCaml library for parsing and pretty
printing Python code.

Install
-------
* cd to `ocaml-pythonlib` dir
* install omake
```
  opam install omake
```
* omake src
```
  omake
```
* add pythonlib to ocamlfind
```
  cd src; ocamlfind install pythonlib META pythonlib.*
```
* compile examples
```
  cd ../examples; make
```
* run examples
```
  ./pydump  # results should be the same as "python pydump.py"
  ./pypp    # pretty print
```

Licence
-------

This software is licensed under the term of GNU LGPL with OCaml
linking exception.

----

Copyright (C) 2011-2015  Tomohiro Matsuyama <<m2ym.pub@gmail.com>>
