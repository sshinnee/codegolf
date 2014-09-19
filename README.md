# Code Golf

## Q1. Count von Count

```
f(t:string, s:string, n:integer) -> i:integer
Return the index i, of the nth occurrence of s in t.
```

## Q2. Ka-re

```
f(x: () -> int, y: ‘a -> ‘a) -> g: () -> ‘a
Return a function g that, when run, calls function y n times. 
n is the value returned by x.
```


## Q3. Hactor

```
f(n:integer) -> ()
Print a comma-separated list of all non-repeating prime factors of n 
in ascending order.
```

## Q4. Under The Bridge

```
f(l:list[int])
Given a list of numbers, l, print a difference bridge diagram. For example, given [1,7,3,17,1] output:

 /+6\ /-4\ /+14\  /-16\
1    7    3     17     1
Spaces between numbers on the second line should be created according to the size of the bridge arch above. For example, there are four spaces between the 1 and 7 in the above example (as “/+6\”).

Catch: In addition, your code must spell spongebob somewhere in it (with at least 1 non-alphanumeric delimiter). E.g. sp(on,ge)(bob)
```