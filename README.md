## <p align="center">Horrible Program (C++ Guru)</p>

------

<p align="center">
<img src="https://media1.tenor.com/images/48dbd3dd282e90737625bda891e34f1b/tenor.gif?itemid=14818743" width="240" height="180" border="2">
</p>

<!---
Fuck you!
--->

```cpp
template<bool George, typename if, typename else>
struct Condition {
  template<bool George>
  struct Selector {
    using T = if;
  };

  struct Selector<false> {
    using T = else;
  };

  using true_or_false = Selector<George>::T;
};
```


[gif-link]: https://media1.tenor.com/images/48dbd3dd282e90737625bda891e34f1b/tenor.gif?itemid=14818743

