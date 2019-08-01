***
# Экспериментальное задание по созданию простого Web – сайта.
***
## Задача:
1. Создать автоматический скрипт для удаленной настройки «пустой» версии Linux.
2. Создать в Docker несколько контейнеров, с доступом по http порту 8080 от Django. Все компоненты должны быть связаны локальной сетью:
  * Nginx
  * Python+Django
  * PostgreSQL
3. Web приложение должно отображать 1 страничку с Hello World.
***
## Реализация:
*`Внимание! Проект реализован и адаптирован для Linux Ubuntu 18.04.2 TLS`*

Для начало развертывания проекта необходимо:

* Создать директорию для размещения общей конструкции проекта и файлов для автоматического запуска установщика;
* Скачать в созданную папку архивный файл -> [archive.tar.gz](https://github.com/glotovsa/mysite_test/blob/master/archive.tar.gz)
* Скачать в созданную папку Bash скрипт для запуска установщика -> [start_web.sh](https://github.com/glotovsa/mysite_test/blob/master/start_web.sh)

***`Важно! Оба файла должны располагаться в одной директории!`***
