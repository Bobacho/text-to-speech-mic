# Преобразование текста в речь с использованием виртуального микрофона

Этот проект представляет собой скрипт на языке Python, который преобразует текст в речь и выводит его в виртуальный микрофон. 
Скрипт использует инструменты ffmpeg и VB-Cable, поэтому перед использованием убедитесь, что они установлены на вашем компьютере.

## Установка зависимостей

Перед началом использования скрипта, убедитесь, что у вас установлены следующие инструменты:

- [ffmpeg](https://www.gyan.dev/ffmpeg/builds/): Мультимедийный фреймворк для обработки аудио и видео файлов.
- [VB-Cable](https://vb-audio.com/Cable/): Виртуальное аудиоустройство для перенаправления аудио сигналов.

## Установка Python зависимостей

1. Установите Python на вашем компьютере, если он еще не установлен. Вы можете загрузить Python с [официального сайта](https://www.python.org/downloads/).

2. Установите необходимые библиотеки:
```pip install -r requirements.txt```

## Установка FFMPEG - Windows:

A. Распакуйте загруженный архив и переименуйте папку FFmpeg в "ffmpeg". Обратите внимание на полный путь к папке ffmpeg.

B. Добавьте путь к папке ffmpeg в системную переменную PATH:

-Откройте "Панель управления" -> "Система" -> "Дополнительные параметры системы" -> "Переменные среды".
- В разделе "Системные переменные" найдите переменную PATH и нажмите "Изменить".
- Добавьте полный путь к папке ffmpeg (например, C:\путь\к\папке\ffmpeg) в качестве нового значения переменной PATH. Обратите внимание на то, что каждый путь разделяется точкой с запятой (;).
- Нажмите "ОК" для сохранения изменений.
## Установка FFFMPEG - Linux (Ubuntu/Debian):

Установите FFmpeg с помощью следующей команды: ```sudo apt-get install ffmpeg```
