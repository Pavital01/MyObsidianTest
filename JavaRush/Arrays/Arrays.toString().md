#JavaRush 
[[2022-07-09]]
```java
int[] array = {1, 2, 3};
String str = Arrays.toString(array);
```

Переменная `str` будет содержать строковое значение:

```
"[1, 2, 3]"
```
___
```java
int[] array = {};
String str = Arrays.toString(array);
```

Переменная `str` будет содержать строковое значение:

```
"[]"
```
___
```java
String[] array = {"Привет", "Как", "Дела"};
String str = Arrays.toString(array);
```

Переменная `str` будет содержать строковое значение:

```
"[Привет, Как, Дела]"
```