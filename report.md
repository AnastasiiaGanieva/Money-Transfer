**Отчёт о тестировании приложения Money Transfer**

**Краткое описание**
Было проведено функцинальное тестирование кода функции сложения целочисленных типов данных (int) с выведением результата в консоль

**Результаты:**

1. 100% fail даже при замене тип на Long
2. https://github.com/AnastasiiaGanieva/Money-Transfer/issues/1

**Рекомендации**
Проставить тип данных ко всем значениям "long":
public class Main {
    public static void main(String[] args) {
        long score = 2_000_000_000;
        long sum = 500_000_000;
        long total = score+ sum;
        System.out.println(total);
    }
}
