## Описание проекта
Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Они хотят построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».
В вашем распоряжении данные о поведении клиентов, которые уже перешли на эти тарифы. Нужно построить модель для задачи классификации, которая выберет подходящий тариф. Предобработка данных не понадобится — вы её уже сделали.
Необходимо построить модель с максимально большим значением accuracy. 
Цель: 
- достичь минимум 0.75 accuracy
- опробовать разные модели


## Описание данных
Каждый объект в наборе данных - информация о поведении одного пользователя в месяц
Известно:
- calls - кол-во звонков
- minutes - суммарная длительность звонков в минутах
- messages - кол-во смс-сообщений
- mb_used - израсходованный интернет трафик в Мб
- is_ultra - какой тариф использовался в течении месяца