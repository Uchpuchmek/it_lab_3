# Лабораторная работа 3
## Выполнила студентка группы ИС-22 Разваляева Мира

## Задача 1
![alt text](/images/1.png)
- Отправить образ не получилось
![alt text](/images/2.png)

## Задача 2
![alt text](/images/3.png)
- Не удаляя, переименуйте контейнер в "custom-nginx-t2".
![alt text](/images/4.png)

 Выполните команду```date +"%d-%m-%Y %T.%N %Z"...```
![alt text](images/6.png)

- Убедитесь с помощью curl или веб браузера, что индекс-страница доступна.
![alt text](images/7.png)

## Задача 3
- Подключитесь к контейнеру и нажмите комбинацию Ctrl-C.
![alt text](images/8.png)
- Выполните ```docker ps -a``` и объясните своими словами почему контейнер остановился.
![alt text](images/9.png)

- Перезапустите контейнер.
![alt text](images/10.png)

- Зайдите в интерактивный терминал контейнера "custom-nginx-t2" с оболочкой bash.
![alt text](images/11.png)

- Установите любимый текстовый редактор(vim, nano итд) с помощью apt-get.
![alt text](images/12.png)

8. Запомните(!) и выполните команду ```nginx -s reload```, а затем внутри контейнера ```curl http://127.0.0.1:80 ; curl http://127.0.0.1:81```.
![alt text](images/14.png)
![alt text](images/15.png)

- Проверьте вывод команд: ```ss -tlpn | grep 127.0.0.1:8080``` , ```docker port custom-nginx-t2```, ```curl http://127.0.0.1:8080```. Кратко объясните суть возникшей проблемы.
![alt text](images/16.png)

- Удалите запущенный контейнер "custom-nginx-t2", не останавливая его.(воспользуйтесь --help или google)
![alt text](images/17.png)
