# name-blocker
<h2>Блокиратор названия беседы ВК</h2>
<br>Данный скрипт предназначен для блокировки названия беседы в социальной сети ВК.
<br>Данный скрипт предназначен для выполнения под операционной системой семейства Debian.
<br>Выполните: 
<br><code>apt-get install python3</code>
<br><code>apt-get install python3-pip</code>
<br><code>pip3 install vk</code>
<br>После этого скачайте этот проект и откройте файл blocker.py. В нём отредактируйте строку 14. Вместо 12345 укажите id вашей беседы. Для этого откройте вашу беседу в браузере и найдите в ссылке id. vk.com/im?sel=c155 - в данном случае id=155.
<br>В строке 17 задаём имя беседы, которое мы хотим закрепить.
<br>Запускаем файл starter.sh и ждём несколько секунд.
<br>Система вас перенаправит в браузер. Надо будет авторизироваться в ВК и согласиться с предоставлением доступа. Теперь скопируйте ссылку в окно программы и нажмите Enter.
<br>Поздравляю. Теперь вы всё настроили. Скрипт работает. Проверьте его путем изменения названия беседы. Для повторного запуска запустите файл starter.sh.