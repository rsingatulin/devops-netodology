Задание
1. Работа c HTTP через телнет.
Подключитесь утилитой телнет к сайту stackoverflow.com telnet stackoverflow.com 80
Отправьте HTTP запрос
GET /questions HTTP/1.0
HOST: stackoverflow.com
[press enter]
[press enter]
В ответе укажите полученный HTTP код, что он означает?

HTTP/1.1 403 Forbidden - ответ означает, что доступ закрыт

![This is an image]
(https://github.com/rsingatulin/devops-netology/blob/main/03-sysadmin-06-net/403.png)

2. Повторите задание 1 в браузере, используя консоль разработчика F12.
- откройте вкладку Network
- отправьте запрос http://stackoverflow.com
- найдите первый ответ HTTP сервера, откройте вкладку Headers
- укажите в ответе полученный HTTP код
- проверьте время загрузки страницы, какой запрос обрабатывался дольше всего?
- приложите скриншот консоли браузера в ответ.

![This is an image]
(https://github.com/rsingatulin/devops-netology/blob/main/03-sysadmin-06-net/stakoverflow-browser.png)
(https://github.com/rsingatulin/devops-netology/blob/main/03-sysadmin-06-net/stakoverflow-request.png)

3. Какой IP адрес у вас в интернете?
5.18.179.121
![This is an image]
(https://github.com/rsingatulin/devops-netology/blob/main/03-sysadmin-06-net/whoer.png)

4. Какому провайдеру принадлежит ваш IP адрес? Какой автономной системе AS? Воспользуйтесь утилитой whois
JSC "ER-Telecom"
AS41733

![This is an image]
(https://github.com/rsingatulin/devops-netology/blob/main/03-sysadmin-06-net/whois.png)

5. Через какие сети проходит пакет, отправленный с вашего компьютера на адрес 8.8.8.8? Через какие AS? Воспользуйтесь утилитой traceroute

![This is an image]
(https://github.com/rsingatulin/devops-netology/blob/main/03-sysadmin-06-net/traceroute.png)

6. Повторите задание 5 в утилите mtr. На каком участке наибольшая задержка - delay?

AS41733  5.19.0.122

![This is an image]
(https://github.com/rsingatulin/devops-netology/blob/main/03-sysadmin-06-net/mtr.png)

7. Какие DNS сервера отвечают за доменное имя dns.google? Какие A записи? Воспользуйтесь утилитой dig

![This is an image]
(https://github.com/rsingatulin/devops-netology/blob/main/03-sysadmin-06-net/dig.png)

8. Проверьте PTR записи для IP адресов из задания 7. Какое доменное имя привязано к IP? Воспользуйтесь утилитой dig

![This is an image]
(https://github.com/rsingatulin/devops-netology/blob/main/03-sysadmin-06-net/ptr.png)

