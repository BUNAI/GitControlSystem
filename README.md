# Описание работы класса SalesManager:
*Класс отбирает менеджера с максимальным количеством продаж:*
```java

protected int[] sales;

public SalesManager(int[] sales) {
        this.sales = sales;
        }

public int max() {
        int max = -1;
        for (int sale : sales) {
        if (sale > max) {
        max = sale;
        }
        }
        return max;
        }
```

![JAVA](https://camo.githubusercontent.com/d688422f947e1ab82d123189bcb18b6020dcf283bb784c7e9c9b188e0569d156/687474703a2f2f77696b692e737461742e75636c612e6564752f6469737472696275746f6d652f75706c6f6164732f612f61322f4a4156415f616e696d617465642e676966)