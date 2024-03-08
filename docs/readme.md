## Introduction to Data Structures
![img.png](img.png)
![img_1.png](img_1.png)

## Introduction to Algorithms
![img_2.png](img_2.png)
![img_3.png](img_3.png)

## Analysis of Algorithms
![img_4.png](img_4.png)
![img_5.png](img_5.png)
![img_6.png](img_6.png)

## Time Complexity
![img_7.png](img_7.png)

```java
public class TimeComplexity {

    public static void main(String[] args) {
        double now = System.currentTimeMillis();
        int n = 999999999;

        System.out.println(printSum(n));
        System.out.println("Time Taken " + (System.currentTimeMillis() - now) + "ms");

        double now2 = System.currentTimeMillis();
        System.out.println(printSum2(n));
        System.out.println("Time Taken " + (System.currentTimeMillis() - now2) + "ms");
    }

    public static int printSum(int n) {
        int sum = 0;
        for (int i = 1; i <= n; i++) {
            sum = sum + i;
        }
        return sum;
    }

    public static int printSum2(int n) {
        return n * (n + 1) / 2;
    }
}

```
```shell
-1243309312
Time Taken 285.0ms
904174336
Time Taken 0.0ms
```

## Space Complexity

![img_8.png](img_8.png)