# Задание 1
Запустите два simple python сервера на своей виртуальной машине на разных портах
Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
Настройте балансировку Round-robin на 4 уровне.
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

[haproxy.cfg](https://github.com/ZorgIVA/Haproxy/blob/master/img/haproxy1.cfg)

<img src = "img\1_1.jpg" width = 100%>

<img src = "img\1_2.jpg" width = 100%>

# Задание 2
Запустите три simple python сервера на своей виртуальной машине на разных портах
Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

[haproxy.cfg](https://github.com/ZorgIVA/Haproxy/blob/master/img/haproxy2.cfg)

<img src = "img\2_1.jpg" width = 100%>

<img src = "img\2_2.jpg" width = 100%>