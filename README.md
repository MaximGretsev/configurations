# configurations Чт 29 дек 2022 10:49:22 MSK

## Special for test-task Dr. Web. 

Тестовое задание по настройке сохранения изменений локальной директории. 

Суть: у нас есть некоторая локальная директория, изменения которой мы хотим отслеживать. 

Есть: скрипт на shell, который каждый час проверяет эту директорию, если внутри нее были сделаны изменения, клонирует измененные файлы в локальный репозиторий, далее, отправляет все в гит. 

На каждую дату, в гит создается отдельная ветка в этом репозитории. В мастере лежат "рабочие" не измененные файлы. 
