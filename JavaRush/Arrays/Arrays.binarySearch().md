#JavaRush 
[[2022-07-09]]
Вот как выглядит его вызов:

```java
int index = Arrays.binarySearch(имя, значение);
```

Где `имя` — это имя массива, который нужно передать уже отсортированным (например, с помощью функции `Arrays.sort()`). `значение` — это тот элемент, который ищется в массиве. Метод возвращает результат — индекс искомого элемента в массиве (номер ячейки массива).