# Короткий отчёт по ЛР 2

## Что я сделала

Собрала папку module01_environment по заданию. Внутри-notebook
из первой работы, два файла с данными, README и version_log.


## Что где лежит

    module01_environment/
    ├── README.md
    ├── short_report.md
    ├── notebooks/
    │   └── lr01_runtime_order_ivanov.ipynb
    ├── data/
    │   ├── sample_text.txt
    │   └── mini_corpus.tsv
    └── docs/
        └── version_log.md

## Как открыть

Открыть notebook в Colab. Проверить, что папка
data лежит рядом с notebooks, иначе файлы не найдутся. Дальше
Runtime → Restart and run all.

## Как понять, что работает

Запускается без ошибок. В выводе видно строку из sample_text.txt
и две строки из mini_corpus.tsv. Если вместо этого FileNotFoundError,
значит, папку data забыли положить рядом.

## Ограничения

Проверяла в Colab. Библиотеки
никакие не подключала.Пути относительные —
если вытащить notebook из папки, чтение файла выдаст ошибку.

## Версии

В version_log три записи. Первая - про структуру папок, вторая-
про данные и Markdown-пояснения в notebook, третьч-про README
и проверку Run all.

## Данные

Личных данных нет. В sample_text.txt одна учебная фраза,
в mini_corpus.tsv две карточки.
