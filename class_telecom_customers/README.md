# Описание проекта - Классификаиция клиентов телеком компании

Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами.
Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям один из новых тариф.

## Данные

Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц. Известно:

- сalls — количество звонков,
- minutes — суммарная длительность звонков в минутах,
- messages — количество sms-сообщений,
- mb_used — израсходованный интернет-трафик в Мб,
- is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

## Задача

На основе данных предложить клиенту тариф.

## Используемые библиотеки
*Pandas*, *Scikit-learn*, *Matplotlib*
