# Телеком
## Цель
Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.
## Вывод
* В рамках этой работы мы произвели первичный просмотр данных, составили краткий план действий, которому по сути придерживались, лишь иногда дополняя деталями
* Подготовили данные, добавили целевой признак, добавили новый признак - количество оплаченных дней (что в итоге стал самым важным для решения задачи), объединили данные, убрали лишние данные
* Провели исследовательский анализ данных, сделали несколько предположений о том, какие пользователи склонны уходить, а какие - нет. Например, мы явно увидели, что чем больше дней оплачивал пользователь, тем меньше вероятность его отвала.
* Рассмотрели 4 модели машинного обучения, лучшей из которых показала себя Catboost с результатом в `ROC AUC` $0.9$
* Выяснили самые важные признаки для решения этой задачи: длительность пользования клиентом услугами и сколько он платит ежемесячно
## Стек используемых технологий
*`pandas` `Scikit-learn` `matplotlib` `seaborn` `numpy` `catboost`*
## Статус проекта
**Завершен**

