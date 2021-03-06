**Лабораторная работа № 6**


## Алгоритмы сортировки

**По этой лабораторной работе нужно сдать отчет в виде четырех файлов:**

- [`1selection.md`](./1selection.md)
- [`2insertion.md`](./2insertion.md)
- [`3bubble.md`](./3bubble.md)
- [`4quick.md`](./4quick.md)

в широко используемом формате разметки Markdown. 

Цель работы – изучить алгоритмы сортировки. Для этого у нас в репозитории готово решение, в котором реализованы некоторые из них.

Откройте папку репозитория в Проводнике и откройте решение sort.sln (если у вас VS версии ранее 2019) или sort2019.sln (если у вас Visual Studio 2019): \
![Файлы решения](images/solution.png "Файлы решения")

Проект разделен на части, так что каждая функция сортировки находится в отдельном файле с соответствующим именем, а файл [`utils.cpp`](./sort/utils.cpp) содержит функции `swap` и `print`. Заголовочный файл [`sort.h`](./sort/sort.h) содержит *объявления* (но не реализации) всех функций, чтобы их можно было использовать в других файлах проекта.
![Структура решения](images/sol_structure.png "Структура решения")

О сортировке пузырьком и вставками можно посмотреть следующее [видео из курса CS50](https://www.youtube.com/watch?v=D1u3H9_wmUU). Забавные видео, иллюстрирующие алгоритмы сортировки (и не только) можно посмотреть на канале
[AlgoRythmics](https://www.youtube.com/user/AlgoRythmics/videos)

В этой лабораторной работе 18 заданий, разделенных на 4 части.
