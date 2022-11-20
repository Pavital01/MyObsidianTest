#JavaRush 
[[2022-07-09]]
```java
Integer[] array = {1, 2, 3};
String str = Arrays.deepToString(array);
```

Переменная `str` будет содержать строковое значение:

```
"[1, 2, 3]"
```
___
```java
int[][] array = { {1, 1}, {2, 2}, {3, 3} };
String str = Arrays.deepToString(array);
```

Переменная `str` будет содержать строковое значение:

```
"[[1, 1], [2, 2], [3, 3]]"
```
___
```java
int[][][] array = { {{1, 2, 3}, {1}}, {{}} };
String str = Arrays.deepToString(array);
```

Переменная `str` будет содержать строковое значение:

```
"[[[1, 2, 3], [1]], [[]]]"
```