Higher order functions are functions which accept a function as argument or return a function as response.

```scala
def compose[A,B,C](f: B => C, g: A => B): A => C =
    (x: A) => f(g(x))
```
