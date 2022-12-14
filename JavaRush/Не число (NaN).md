---
created: 2022-07-10T17:14:58+03:00
updated: 2022-07-10T17:14:58+03:00
---
#JavaRush 
Любые операции с бесконечностью дают бесконечность. В целом да, но не все.

Числа с плавающей точкой могут хранить еще одно специальное значение — `NaN`. Это сокращение от Not a Number (не число).

В математике, если разделить бесконечность на бесконечность, должна возникнуть неопределенность.

Ну, а в Java, если разделить бесконечность на бесконечность, будет `NaN`.

Примеры:

Код

Примечание

```java
System.out.println(0.0 / 0.0);
```

```
NaN
```

```java
double infinity = 1d / 0d;
System.out.println(infinity / infinity);
```

```

NaN
```

```java
double a = 0.0 / 0.0;
double b = a * 10;
double c = b - 100;
double d = a + infinity;
```

```
a == NaN
b == NaN
c == NaN
d == NaN
```

Любая операция с `NaN` дает `NaN`.