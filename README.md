# klaster

### Задание 1
1. Запустите два simple python сервера на своей виртуальной машине на разных портах
2. Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
3. Настройте балансировку Round-robin на 4 уровне.

   
![image](https://github.com/AnastasiyaEvsseva/klaster/assets/151757353/6c0776b6-9ee0-499f-a0a6-9c72e3ebfb92)

![haproxy1](https://github.com/AnastasiyaEvsseva/klaster/assets/151757353/1cd89de1-de42-4675-b20c-63b1976958f6)

### Задание 2
1. Запустите три simple python сервера на своей виртуальной машине на разных портах
2. Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
3. HAproxy должен балансировать только тот http-трафик, который адресован домену example.local

![haproxy2](https://github.com/AnastasiyaEvsseva/klaster/assets/151757353/d54486d7-f4d9-44c0-b9bb-3e41d63531ec)
