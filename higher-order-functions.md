Higher order functions are functions which accept a function as argument or return a function as response.

```
def compose(f: B => C, g: A => B): A => C =
    (x: A) => f(g(x))
```
