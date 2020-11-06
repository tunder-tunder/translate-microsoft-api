### Используя API Microsoft Azure реализовать приложение для перевода текста. Документация доступна по адресу  https://docs.microsoft.com/ru-ru/azure/cognitive-services/translator/reference/v3-0-reference

Демонстрация работы с API через программу curl показана в видео  https://youtu.be/3tZHJmT0nfA

Код доступа 82e622ccc27b4ad0af0918182329a742 и регион westeurope

- [x] Исходный текст берётся из файла
- [x] Язык задаётся параметром командной строки
- [x] Вывод в отдельный текстовый файл (имя файла программа формирует сама или задаётся при старте)
- [x] Требуется поддержка многострочного текста
- [x] Ключи к API задаются в виде переменных в программе

Заготовка программы на Java:  https://git.io/JTFoG , программа может быть написана на любом языке (Python, PHP, C++, C#)

В качестве ответа приложите: [исходный код](translate.py) и пример работы программы как минимум для трёх направлений перевода (?)

# [файл с фразами для перевода](input.txt)
# [файл с переведенными фразами](translations.txt)
# [файл вывода терминала](output.txt)