# List Syntax

## Abstract

## Design

### Construct List

```erlang
[1|[3|[5|[7|[9|[]]]]]]
[1,3,5,7,9|[]]
[1,3,5,7,9]
[1|[3,5,7,9]]
[1,3,5|[7,9]]
```
### List Cons

```erlang
[h|t]
```
### List Pattern Match

### List Comprehensions

## Reference

### Erlang

```erlang
[H|T] = [1 | [2 | [3 | [4]]]].
```

### Elixir

[Elixir List] (https://hexdocs.pm/elixir/List.html)

### Haskell

### Clean

[Clean Programming language](https://en.wikipedia.org/wiki/Clean_(programming_language))

```clean
[x:xs] -- cons operator
```

