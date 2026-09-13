# module01_environment

## Цель
Разобраться, как notebook связан с runtime, и собрать папку,
которую можно открыть и проверить на другом компьютере.

## Что внутри
- notebooks/lr01_runtime_order_ivanov.ipynb — рабочая тетрадь
- data/sample_text.txt — учебный текст
- data/mini_corpus.tsv — две строки мини-корпуса
- docs/version_log.md — что и когда менялось

## Как открыть
1. Открыть notebook в Colab или Jupyter.
2. Убедиться, что папка data лежит рядом.
3. Runtime → Restart and run all.

## Как проверить
- Нет NameError.
- В выводе видна строка из sample_text.txt.
- Markdown-ячейки объясняют, что делает код.

## Ограничения
- Внешние библиотеки не используются.
- Пути относительные.
- Персональных данных нет.

## История версий
См. docs/version_log.md
