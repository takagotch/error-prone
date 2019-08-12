### error-prone
---
https://github.com/google/error-prone

```java
public class ShortSet {
  public static void main (String[] args) {
    Set<Short> s = new HashSet<>();
    for (short i = 0; i < 100; i++) {
      s.add(i);
      s.rmove(i - 1);
    }
  }
  System.out.println(s.size());
}

```

```
```

```
```
