# Анализ онлайн-магазна книг
Когортный анализ, RFM-анализ
## Стек:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?logo=seaborn&logoColor=white&style=for-the-badge)

## Применялись следующие подходы:
+ когортный анализ
+ Retention Rate
+ RFM-анализ

## В ходе проекта решил следующие задачи:
+ Предобработка данных в датафрейме.
+ Выявил количество пользователей, которые совершили покупку только один раз.
+ Какое количество заказов не доставляется пользователям в среднем и по каким причинам (вывели детализацию причин).
+ По каждому товару определим, в какой день недели товар чаще всего покупается.
+ Сколько у каждого из пользователей в среднем покупок в неделю (по месяцам).
+ Используя pandas и seaborn, провел когортный анализ пользователей. В период с января по декабрь выяви когорту с самым высоким retention на 3й месяц.
+ Построил RFM-сегментацию пользователей, чтобы качественно оценить свою аудиторию.

### Итогом работы является: определили, что большая часть заказов не доставляются пользователям именно логистической службой. Исходя из расчета среднего количества покупок и RFM-анализа, можем применить программу лояльности к пользователям. Используя когортный анализ самый высокий Retention Rate показала когорта октября 2017. 

Ознакомиться с файлом решения тут:
[e-commerce](project_e_commerce.ipynb)
--------------------

