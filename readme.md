# Содержание

* [Модули](#модули)
* [Packet Tracer](#packet-tracer)
* [FAQ](#faq)

# Модули

В зависисмости от вашей программы обучения у вас будет до 4 модулей:
1. Введение в сетевые технологии
2. Основы маршрутизации и коммутации
3. Построение масштабируемых сетей
4. Построение распределенных сетей

По каждому из этих модулей необходимо будет выполнить обязательные лабораторныей раьоты и экзамен.

# Packet Tracer

* Для выполнения лабораторных работ в рамках прохождения обучения вам необходимо установить эмулятор сетевого
  оборудования Cisco Packet Tracert. [Ссылка на дистрибутив](https://cloud.tusur.ru/index.php/s/iYi6iHfzZaPRLLw)
* Программа Cisco Packet Tracert требует аутентификации с учетной записью Cisco. Но так как Cisco остановила свою
  деятельность в РФ, то штатным образом запустить Packet Tracert невозможно. Для корректной работы программы необходимо
  заблокировать доступ Packet Tracert в интернет. Для этого необходимо настроить межсетевой экран в вашей операционной
  системе. [Инструкция по настройке МЭ для PT в Windows](#инструкция-по-настройке-мэ-для-pt-в-ос-windows). Если у вас
  другая операционная система или установлен антивирус со встроенным межсетевым экраном, то обратитесь к документации
  производителя.
* [Ссылка на серию обучающих видео по PT](http://tutorials.ptnetacad.net/)

### Инструкция по настройке МЭ для PT в ОС Windows

1. Переходим в ***Панель управления***
2. Переходим в ***Брандмауэр Защитника Windows*** -> ***Дополнительные параметры***.
   ![img](/assets/images/block_pt_win_01.png)
2. В новом окне выбираем ***Правила для исходящего подключения*** -> ***Создать правило***.
   ![img](/assets/images/block_pt_win_02.png)
3. Задаем параметры новому правилу:
   ![img](/assets/images/block_pt_win_03.png)

# FAQ

### Как проходит обучение?

Вы самостоятельно изучаете теоретический материал, выполняете задания и лабораторные работы. При появлении вопросов вы их задаете мне в телеграм, мы их разбираем, при необходимости даю дополнительный материал.

### Как и куда задавать вопросы?
Все возникающие вопросы задавать мне в телеграм. В течении дня я на них буду давать вам ответ. Бывают ситуации когда в потоке всех сообщений я пропустил ваше сообщение и не ответил в указанный срок, в этом случае прошу сообщение продублировать.

### В каком формате сдавать лабораторные задания?

Сдавать необходимо сохраненный файл выполненного задания и скриншот раздела Check results с полученными баллами за задание.    
<ins>***Работы, сданные без скриншота, приниматься не будут.***</ins>    
![img](/assets/images/FAQ_hw1.png)

### Какие лабораторные задания необходимо выполнять?

Обязательные лабораторные задания находятся в разделе **Лабораторные работы в Packet Tracer**. Их обязательно необходимо выполнить и сдать. Остальные задания сдавать не надо и выполняются по желанию. Но я очень рекомендую выполнять все задания.    
![img](/assets/images/FAQ_hw2.png)

### PT не дает сохранить работу

Необходимо [запретить](#packet-tracer) PT доступ в интернет.

### Как часто проверяются лабораторные работы?

Работы проверяются 1 раз в неделю.

### Из чего строится итоговая оценка за курс
Каждый модуль оцениваетс по результатам экзамена. В экзамене у вас будет 3 попытки, засчитывается максимальный результат. Также для заверщения модуля вам необходимо выполнить все обязательные Лабораторные работы.
