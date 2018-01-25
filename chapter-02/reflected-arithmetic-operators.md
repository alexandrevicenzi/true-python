# Reflected Arithmetic Operators

These methods are called to implement the binary arithmetic operations with reflected (swapped) operands.
This means that operands switch sides.
In most cases, the result of a reflected operation is the same as its normal equivalent.

The normal addition is `a + b` and the reflected addition equivalent would be `b + a`.

> **Note**  
> Ternary `pow()` will not try calling `__rpow__()`.

#### `object.__add__(self, other)`

Addition using `+` operator.

```python
a + b
```

#### `object.__sub__(self, other)`

Subtraction using `-` operator.

```python
a - b
```

#### `object.__mul__(self, other)`

Multiplication using `*` operator.

```python
a * b
```

#### `object.__matmul__(self, other)`

Matrix Multiplication using `@` operator.

```python
a @ b
```

#### `object.__truediv__(self, other)`

Division using `/` operator (floating point division).

```python
a / b
```

#### `object.__floordiv__(self, other)`

Division using `//` operator (floor division also called interger division).

```python
a // b
```

#### `object.__mod__(self, other)`

Modulo using `%` operator.

```python
a % b
```

#### `object.__divmod__(self, other)`

Equivalent to using `__floordiv__()` and `__mod__()` and it's called by `divmod()` built-in function.

```python
divmod(a, b, c)
```


#### `object.__pow__(self, other[, modulo])`

Exponentiation using `**` operator or `pow()` built-in function.

```python
a ** b
```

#### `object.__lshift__(self, other)`

Left Shift, using `<<` operator.

```python
a << b
```

#### `object.__rshift__(self, other)`

Right Shift, using `>>` operator.

```python
a >> b
```

#### `object.__and__(self, other)`

Bitwise And using `&` operator.

```python
a & b
```

#### `object.__xor__(self, other)`

Bitwise Exclusive Or using `^` operator.

```python
a ^ b
```

#### `object.__or__(self, other)`

Bitwise Or using `|` operator.

```python
a | b
```
