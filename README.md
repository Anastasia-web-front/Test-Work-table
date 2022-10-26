# Test-Work

1. Билеты на событие

В данном примере я объеденила две задачи:

1)Добавляю дополнительные поля для льготный и групповых билетов ;

2)Отмечаю баркоды для каждого билета соответствущими символами, в качестве разделителя использую '.' ;

[tickets.zip](https://github.com/Anastasia-web-front/Test-Work-table/files/9873112/tickets.zip)


2. Время из A в B

Репозиторий со страницей покупки билетов:
https://github.com/Anastasia-web-front/Test-Work-tickets


3. Верстка макета:

https://github.com/Anastasia-web-front/Test-Work-layout


4. Мое решение проблемы с горизонтальным скроллом:

В CSS:

@media (max-width: 400px){
  html, body{
     overflow-x: hidden;
  }
  table{
    table-layout: fixed;
    width: 20%;
 }
  td{
    overflow: hidden;
    white-space: wrap;
  }
}
