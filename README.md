# **Приложение Miles**

**Условие**: за каждые 20 рублей, потраченные на покупку билета, начисляется 1 бонусная миля. При расчёте бонусных миль цена билета указывается без копеек.

**Код приложения** [Miles](https://github.com/maxim-valov/Miles/blob/master/src/Main.java):

```java
public class Main {
    public static void main(String[] args) {
        int price = 14998;
        int mile = 20;
        int bonus = price / mile;
        System.out.println( "Bonus miles:" + bonus);
    }
}
```

***Примечание**: Тип **int** выбран так, как в расчётах будут использоваться только целые числа и граничных значений данного типа достаточно для работы с переменными "price" и "mile". 