The `type`{.python} function tells you the type of any value or variable passed to it as an argument. This is useful for understanding what kind of data you're working with.

# Basic Usage

```py-cell
print(type(5))
print(type(3.14))
print(type("hello"))
```

The output `<class 'int'>`{.python} means "the `int`{.python} class".

# With Variables

You can check the type of the object referenced by any variable:

```py-cell
x = 42
y = 42.0
z = "42"

print(type(x))
print(type(y))
print(type(z))
```

# With Expressions

You can check the type of the result of an expression:

```py-cell
print(type(5 + 3))
print(type(5 / 3))
```