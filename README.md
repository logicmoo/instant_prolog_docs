# instant_prolog_docs
Magically document prolog source files based on predicate and variable naming conventions


```prolog

 :- pack_install('https://github.com/TeamSPoon/instant_prolog_docs.git').

```


```prolog

:- use_module(library(instant_prolog_docs)).

?- autodoc_file('some_file.pl').

```

I haven't ran this for a very very long time so carefull.

TODO:  
  Make the Anglification system read a : instant_prolog_docs.config  (instead of being in the module itself)
