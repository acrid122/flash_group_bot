# flash_group_bot
Данный бот предназначен для групп годового курса Flash.
Чтобы бот работал корректно необходимо:
1) Выгрузить отчет из своего класса Stepik и назвать его "Текущая ситуация" (или же как-то по-другому, правда, надо будет поменять имя в скрипте)
2) Выгрузить журнал в другой excel файл и назвать его как угодно. В первой строке после комментарий "Excel info members" задать имя этого файла
3) Работа с приложением Stepik:
https://stepik.org/oauth2/applications/ Переходим по этой ссылке и создаем приложение 
  В первой графе ставим confidential, во второй - client-credentials
Копируем данные токены в соответствующие поля файла my_token
