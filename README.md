# Контрольная работа №1
## Сушкевич Алексей, 13 группа

Был написан сценарий командной строки на языке Bash, который выполняет поиск файлов с длинными именами в указанных каталогах. Путь к каталогам и количество символов передаются в качестве аргументов. Сценарий ограничен обработкой только 3-х аргументов. Если количество аргументов больше 3-х, выводится сообщение об ошибке и сценарий завершает работу. 

### [Ссылка на файл сценария](https://github.com/AlekseySushkevich/temp_sp_kr1/blob/main/SushkevichKR1)

В данном сценарии мы используем команду find, чтобы найти все файлы в указанных каталогах. Затем мы используем awk, чтобы разделить полное имя файла и вычислить количество символов в его имени. Результаты сортируются с помощью sort по количеству символов и выводятся на стандартный вывод, а также записываются в файл sorted_output.txt с помощью tee.

### Результат тестирования:
![Результат тестирования](https://github.com/AlekseySushkevich/temp_sp_kr1/blob/main/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202023-11-02%2018-39-57.png)
