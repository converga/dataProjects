# Машинное обучение в бизнесе
## Цель
Предоставлены пробы нефти в трёх регионах. На основе данных геологической разведки выбрать лучший район для добычи нефти
## Вывод
Итого, была проведена следующая работа:

1. Изучили данные, выявили незначительное число дубликатов
2. Обучили модель для каждого региона, без использования масштабирования, тк толку от нее не было
3. Выявили среднее число добываемой нефти в каждом регионе. Выявили так же точку безубытычности и на первый взгляд, ни один регион не соответствовал ей
4. С помощью техники бутстрепа мы пересмотрели регионы с точки зрения количества добываемой нефти, рисков и доверительного интервала и пришли к выводу, что лучший кандидат для добычы - __регион 2__.
## Стек используемых технологий
`pandas` `Scikit-learn` `matplotlib` `seaborn` `numpy` `бутстреп`
## Статус проекта
**Завершен**