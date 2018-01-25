# Comparison Operators

These methods are also called "rich comparison" methods and they are useful to implement when you want to compare custom objects.
By convention, these methods should return `False` or `True` to avoid extra calls to determine if the result is true or false.

#### `object.__lt__(self, other)`

Less than using `<` operator.

```python
a < b
```

#### `object.__le__(self, other)`

Less than or equal to using `<=` operator.

```python
a <= b
```

#### `object.__eq__(self, other)`

Equality using `==` operator.

```python
a == b
```

#### `object.__ne__(self, other)`

Inequality using `!=` operator.

```python
a != b
```

#### `object.__gt__(self, other)`

Greater than using `>` operator.

```python
a > b
```

#### `object.__ge__(self, other)`

Greater than or equal to using `>=` operator.

```python
a >= b
```

#### `object.__bool__(self)`

Truth value testing, must return `False` or `True`.

```python
if a:
    do_stuff_1()
else:
    do_stuff_2()
```

## Try it!

<iframe height="800px"
        width="800px"
        src="https://repl.it/@alxvicenzi/comparison-operators?lite=true"
        scrolling="no"
        frameborder="no"
        allowtransparency="true"
        allowfullscreen="true"
        sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
