Отчёт о тестировании Money Transfer
<8/25> - <8/25> было проведено  тестирование  Money Transfer 

На тестирование затрачено: 30 мин

на основании легенды было составлено следующее приложение, позволяющее воспроизвести ситуацию пополнения баланса:

public class Main {
    public static void main(String[] args) {
        int balance = 2_000_000_000;
        int refill = 500_000_000;
        int total = balance + refill;
        System.out.println(total);
    }
    }
    
    
    после запуска, приложение показывает следующий результат:
    "C:\Program Files\Java\jdk-11.0.1\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\lib\idea_rt.jar=53482:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\dsnay\IdeaProjects\javaforqa\out\production\javaforqa Main

-1794967296

Process finished with exit code 0

Bug Report https://github.com/dsnaydina/Javaforqa_-HT-2/issues/1#issue-687562178

 
    
   рекомендации -проверить тип переменных в приложении. 
