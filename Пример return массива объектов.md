#Пример #Habr
```java
public static Vector[] generate(int n){  
    Vector[] vectors = new Vector[n];  
 for (int i = 0; i < n; i++) {  
        vectors[i] = new Vector(Math.random(),Math.random(),Math.random());  
 }  
    return vectors;  
}
```