# Портфолио: аналитик данных

## Обо мне

Привет! Меня зовут Андрей Гришин, я начинающий аналитик данных. 
Мне 37 лет, проживаю в г. Пензе, Россия. 

Окончил Пензенский государственный универсисет по специальности Математические методы в экономике. 

Сейчас работаю в производстве, занимаюсь анализом причин невыполнения планов, создаю модели бюджетных и производственных планов и немного прогнозированием. 

В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
Инструменты анализа данных: SQL, Excel:

Языки программирования и библиотеки: Python

Системы управления базами данных: MySQL, PostgreSQL



## Мои проекты



**Проект 1: Калькулятор юнит-экономики онлайн-школы. Среда решения MS Excel.**

Что нужно было сделать:
На основе имеющихся данных онлайн-школы нужно сделать калькулятор юнит экономики, который на основании введения новых данных автоматически пересчитывал модель.  

Задача №1 Составить Новый план маркетинга

Задача №2. Пресчитать план найма учителей

Решение задачи было разбито на несколько блоков.
Первый блок состоял в получении значений отдельных показателей. Так мною были посчитаны Средний CPA, Конверсия в покупку, Retention, Lifetime, интенсивность, стандартная цена.

После получения данных значений на отдельной книге мною был собран кальулятор, введены ячейки Изменений, введены ячейки для автоматического пересчета данных.

На основании полученных результатов были сформированы основные показатели работы онлайн-школы в двух формация "как есть" и "как будет". Ключевыми значениями калькулятора являются показатели CAC, ЗП учителей(переменные затраты), ФОТ остального персонала(постоянные затраты), Маржа.

**Для решения первой задачи** в список параметров калькулятора добавлен показатель “Поправочный  коэф-т на привлечение", который может меняться пользователем. Далее к данному показателю был привязан динамический расчёт количества новых студентов за период 05.21-04.22.

**Для решения второй задачи** на отдельном листе создан калькулятор рассчета найма учителей. В калькулятор Найма преподавателей так же внесена возможность изменять входных параметры: Пропускную способность П и Retention П - с помощью дополнительного столбца с процентными изменениями.

 
Итог №1 Получен калькулятор рассчета нового плана маркетинга.
![image](https://github.com/Zergusa/Zergusa/assets/138280716/2d88541c-2a45-4b63-bd96-89705851b7b6)
Итог №2 Получен калькулятор пересчета плана найма учителей.
![image](https://github.com/Zergusa/Zergusa/assets/138280716/c5725ba2-caf7-4893-9a61-719e3c87875f)


**Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра. **Cреда решения MS Excel, MS PowerPoint**.**		

Что нужно было сделать:
На основе имеющихся "сырых" данных собрать калькулятор юнит-экономики онлайн-калькулятора.  



Задача №1 Предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность 

Задача №2. Cобрать налядную визуализацию, где будет показано, кто, где и в каком объеме смотрит фильмы на платформе.

Как решал: краткое описание решения (автореферат)
Для подготовки общего решения мною было сделано несколько блоков:

**в первом блоке** я провел анализ имеющихся данных с помощью сводных таблиц: посчитал количество подписок в каждый месяц, количество просмотров в каждый месяц, количество уникальных просматривающих пользователей в каждый месяц,
дата первого просмотра для каждого юзера, количествово первых просмотров для пользователя в каждый месяц, среднее количество просмотров на одного юзера в каждом месяце.

**во втором блоке** я приступил к созданию самого калькулятора юнит-экономики, для этого посчитал еще несколько метрик таких как количество повторных оплат в каждом месяце, Retention для каждого месяца, 
cреднее геометрическое Retention, Лайфтайм, LTR, CAC, Маржинальность. Добавил ряд визуализаций. И ввел в настройку заданий 25% маржинальность. 
![image](https://github.com/Zergusa/Zergusa/assets/138280716/3785a152-5df7-4bbd-9382-9961dbbf025b)

**В третьем блоке** я приступил к визуализации данных и собрал презентацию по имеющимся данным.
![image](https://github.com/Zergusa/Zergusa/assets/138280716/5eaee5f7-8c5d-4a95-829a-f11b0e827d00)
![image](https://github.com/Zergusa/Zergusa/assets/138280716/c5521f9f-f18a-452d-8de9-40512720e8cc)
![image](https://github.com/Zergusa/Zergusa/assets/138280716/cf9c6c38-3f4a-473e-9cd0-e52d18259028)
![image](https://github.com/Zergusa/Zergusa/assets/138280716/02fb22b2-76b9-4513-b4d5-fdba03143247)
![image](https://github.com/Zergusa/Zergusa/assets/138280716/90d1c402-d745-4572-b90d-da627b09b883)

В результате мной создан калькулятор юнит-экономики и создана наглядная визуализация выведенная в отдельную презентацию. 



**Проект 3: Когортный анализ онлайн-кинотеатра.Среда PostgreSQL**

Что нужно было сделать: 
Задача 1. Для каждого партнера онлайн-кинотеатра необходимо рассчитать, какой процент клиентов дошел до второй покупки, до третьей покупки и т. д.
Задача 2. Найдите количество уникальных значений заданного поля только с помощью функций row_number и rank.

В ходе решения проекта я объединил две таблицы для получения полной информации о партнерах онлайн-кинотеатра(названии), а так же проставил ранжировку(количество покупок) по каждому клиенту. Далее я посчитал отношение количества покупок(первая, вторая и т.д.) у каждого парнера к общему количеству покупок и сделал группировку. 
![image](https://github.com/Zergusa/Zergusa/assets/138280716/00384365-663e-4509-b75c-253178ddfa1a)
![image](https://github.com/Zergusa/Zergusa/assets/138280716/0e2850c1-5b80-4994-8735-925c9aaf3cbe)
По второму заданию я в СТЕ проставил ранжировку с помощью функций row_number и rank, а в самой функции их сравнил. Как итог получилось уникальное значение заданного поля. 
![image](https://github.com/Zergusa/Zergusa/assets/138280716/f51fbdd1-60ec-4d36-b000-52b57fba61ea)



**Проект 4: Построение витрины для модели машинного обучения в банке. Среда PostgreSQL**

Что нужно было сделать: Взять данные из таблицы и написать скрипт, который сделает витрину по требуемым полям.

Для решения мною был проведен анализ имеющихся данных в таблицах.
Я создал отдельную CTE которая объединила две таблицы в одну и затем вычисляла данные необходимые для витрины.
Далее отдельной функцией, я вытащил из CTE необходимые данные и вывел витрину.
![image](https://github.com/Zergusa/Zergusa/assets/138280716/b7bf4326-795c-4ac0-9b80-d389e11f38ef)
https://metabase.sky.pro/question/68636


**Проект 5: Моделирование изменения балансов студентов. Среда PostgreSQL**

Что нужно было сделать: Смоделировать изменение балансов студентов. Баланс — это количество уроков, которое есть у каждого студента.

Задача №1 Вывести как менялось общее количество уроков на балансах студентов подневно.

Задача №2 Создать визуализацию (линейную диаграмму) итогового результата. Сделать выводы. 

Решение задачи так же выполнялось по блокам. Для того чтобы код был понятным применялось CTE.

Первым шагом я определил когда была первая транзакция для каждого студента.

Вторым шагом собрал таблицу с датами за каждый календарный день 2016 года без привязки к конкретному студенту.

Третьим шагом объединил данные таблицы.

Четвертым шагом нашел все изменения балансов, связанные с успешными транзакциями

Пятым шагом нашел баланс студентов, который сформирован только транзакциями. 

Шестым шагом нашел изменения балансов из-за прохождения уроков.

Седьмым шагом создал базу хранения кумулятивной суммы количества пройденных уроков.

Восьмым шагом вычислил баланс каждого студента. 

Девятым шагом вычеслил как менялось общее количество уроков на балансах студентов.

**Ссылка на проект: https://metabase.sky.pro/question/67456**

В результате проделанной работы мною подготовлен баланс общего количества уроков
![image](https://github.com/Zergusa/Zergusa/assets/138280716/94d97538-0f11-4f90-9ebd-2faac2745a7b)

Подготовлена визуализация итогового результата.

![image](https://github.com/Zergusa/Zergusa/assets/138280716/6db80623-55a5-4e3c-8b07-58c70d15886f)

Сделаны выводы: 
1.	При пополнении баланса не расходуются в полном объеме оставшиеся уроки. Соответственно необходимо выяснить в чем причина данной ситуации(плохие учителя, не организован процесс самих уроков либо другие причины)
   
2.	В апреле, июле, октябре и ноябре были скачки по оплатам уроков. Рекомендации проверить какие были акции или мероприятия проведены в данные периоды и транслировать их.
   
3.	В конце года наблюдается резкое падение проведение занятий. Возможно это связано с новогодними праздниками, однако рекомендуется провести дополнительное исследование причин.

**Проект 6: Анализ А/В теста проведенного ритейлером. Среда решения Python, Jupiter Notebook.**

Что нужно было сделать:
Проанализировать и визуализировать результаты, провести сегментацию, а также сделать выводы и сформулировать рекомендации для дальнейших запусков АБ Теста. Построить таблицу, которая будет выгружать результаты АБ Теста в MS Excel.  

Задача №1. Импортировать данные из MS Excel. Очистить данные от нуловых и некорректных данных. 

Задача №2. Визуализировать получившиеся данные

Задача №3. Провести анализ результатов А/В тестов с сегментацией: общий анализ, анализ с разбивкой по городам

Задача №4. Выгрузка таблицы в MS Excel


Для решения данной задачи в первую очередь импортировал данные из MS Excel при помощи Pandas. Каждый лист выгрузил в отдельный датафрейм. Тут же очистил каждый датафрейм от нуловых значений.

Вторым этапом при помощи groupby группируем данные по городам и строим визуализацию при помощи библиотеки pyplot.

Третим этапом формируем общий датафрейм из трех имеющихся для дальнейшего анализа: делаем группировку по клиентам с суммой платежей, присоединяем к к основному датафрейму суммы платежей клиентов при помощи методом .merge, заменяем платежи клиентов которые не совершили покупку с NaN на 0 при помощи метода .fillna. Добавляем к датафрейму место расположения торговых точек по городам. Создаем колонку Флаг о совершении либо отсутствии оплаты при помощи метода where из библиотеки Numpy.

Четвертым этапом при помощи цикла for определяем торговые точки, где либо не происходила оплата, либо отсутствуют клиенты из тестовой или контрольной группы. При помощи метода .isin убираем из датафрейма некорректные и нуловые значения.

Пятым этапом для автоматизации процесса создаем функции которые будут сравнивать данные контрольной и тестовой группы и делать выводы о подтверждении либо отклонении нулевой гипотезы о том, что распределдения равны.

Шестым этапом собираем в единый датафрейм получившиеся данные по заданной таблице и делаем экспорт в MS Excel.

Результатом работы является файл MS Excel в который загружено 3 листа: 1 лист положительные итоги А/В тестирования, нейтральные и отрицательные
https://github.com/Zergusa/Zergusa/blob/main/Задание%206.ipynb


## Контактная информация
Email: A.V.Grishin1986@yandex.ru
