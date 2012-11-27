spacerls
========

Linda implementation in Erlang

## MoSCoW
### Must
#### Have make-file with install command
#### Implement "Linda" interface functions
##### out
out(t) adds tuple t to tuple space.
##### in
in(t) attempts to match some tuple t in tuple space to the template m 
and, if a match is found, removes t from tuple space.
##### rd
rd(t) Similar to in except that the matched tuple remains in tuple space. 
The executing process suspends if it fails to match a tuple.
##### eval
eval(expression) Similar to out except that the tuple argument to eval 
is evaluated after t is added to tuple space.
### Should
### Could
### Would (be nice)
