readme.txt
==========================
Внимание!
Это не то что запускается на сервере в примере, а то как это может быть.
Так как интеграция происходила в существующий проект, то прошу простить за недостающию куски кода (в основном модели)

По коду уточню также что:
- все данные изначально хранятся в PostgreSQL но чтобы не грузить основной сервер БД для этого примера я вынес данные в Mongo
- данные в БД изанчально были разношерстные (напимер взятые в кавычки или с немного битой кодировкой), я их никак не обрабатывал
- поиск по запросам к монге не кешируется и поиск прямой как гвоздь
- Кастомная команда Django - tomongo собственно конвертер из базы в монго - без заморочек

Вроде все. Надеюсь что кому нибудь пригодится :) 