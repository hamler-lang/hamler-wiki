# Erlang Style Maps

## Abstract

Hamler should implement erlang style maps.

## Design

### Construct Maps

```haskell
-- New map
m = #{:foo => "bar", :bar => "foo"}
```

### Map Pattern match

```haskell
-- Match Map
#{"foo" := x, "bar" := y} = m
```

## Basic Functions

```haskell
-- get
Map.get :foo m -- return "bar"
Map.get :bar m -- return "foo"

-- put
m1 = Map.put :key "val"

-- keys
keys = Map.keys m

-- values
values = Map.values m
```
