An interpreter for a toy calculator language, written in python 3. 

To run the repl type ```python repl.py``` into your terminal.



## Language syntax

All expressions should be wrapped in open ```|``` and close ```>```.

All variable names should start with "?".

To assign use ```<-```.

Operators are:
```!ADD```
```!SUB```
```!MUL```



## Examples

The following are grammatically correct sentences:

```| 5 !MUL 7 >```

```| | 2 !ADD | 3 !ADD 1 > > !SUB | 5 !ADD 7 > >```

```| ?x <- | 1 > >```

```| ?x <- | 5 !ADD 7 > > | 20 !ADD 10 >```

