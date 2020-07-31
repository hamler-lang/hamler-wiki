# Receive Expression

## Abstract

Implement `receive ... after` expression in Hamler.

## Design

### receive

```
receive
  p1 -> expr1
  p2 -> expr2
  ...
```

### receive ... after

```
receive
  p1 -> expr1
  p2 -> expr2
  ...
after
  timeout -> exprN
```

