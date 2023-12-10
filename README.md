# Lab6_3D-Letter
### Средства разработки
Фреймворк Qt и язык C++
### Возможности проекта
* Отрисовка буквы Ш в пространстве Oxyz. Началом буквы считается нижняя левая дальняя вершина (по умолчанию имеет координату (0, 0, 0));
* Возможно приблизить/отдалить изображение (колесиком мыши либо клавишами + и - соответственно);
* Возможно вращать изображение в целом;
* Реализованы целочисленные поля для ввода значений. Ограничения на ввод: перемещение - от -10 до 10, масштабирование - от 1 до 5, вращение вокруг осей - от -360° до 360°;
* Выполнение преобразований происходит при нажатии на соответствующие кнопки. Одновременно с этим пересчитываются матрицы преобразований относительно лишь текущего преобразования. Значения в полях ввода сбрасываются к значениям по умолчанию;
### Особенности проекта
* Для удобства рассмотрения проекций буквы, ее трехмерное изображение скрывается;
* Для лучшего восприятия рисунка, на нем не могут одновременно присутствовать трехмерное и проекционное изображение;
* Масштабирование изменяет размер буквы с сохранением текущей вершины начала буквы;
* Масштабирование, как увеличение, реализуется кнопкой "Scale Forward". Масштабирование, как уменьшение, реализуется кнопкой "Scale Backward";
* Матрицы преобразований указаны для однородных координат;
* Координатные оси расчитаны на значения от -10 до 10. Единичный отрезок равен 0.25;
