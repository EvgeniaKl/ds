# Учебные проекты курса "Специалист по Data Science"

<table>
<tr>
<td><b>Номер</b></td>
<td><b>Тема</b></td>
<td><b>Название/ссылка</b></td>
<td><b>Описание проекта</b></td>
<td><b>Используемые инструменты</b></td>
<tr>
<td><b>1</b></td>
<td>Предобработка данных</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/Исследование%20надежности%20заемщиков.ipynb" target="_blank"><b>Исследование надежности заемщиков</b></a></td>
<td>Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку. </td>
<td><b>pandas, numpy</b>
<tr>
<td><b>2</b></td>
<td>Исследовательский анализ данных</td> 
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/2%20Исследовательский%20анализ%20данных.ipynb" target="_blank"><b>Исследовательский анализ данных</b></a></td>
<td>В распоряжении данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Вам нужно научиться определять рыночную стоимость объектов недвижимости. Для этого проведите исследовательский анализ данных и установите параметры, влияющие на цену объектов. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 
По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта и других объектов — эти данные автоматически получены из геосервисов. Количество парков и водоёмов также заполняется без участия пользователя.</td>
<td><b>библиотеки</b>
<tr>
<td><b>3</b></td>
<td>Статистический анализ данных</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/Исследование%20надежности%20заемщиков.ipynb" target="_blank"><b>Исследование надежности данных</b></a></td>
<td>Вы аналитик популярного сервиса аренды самокатов GoFast. Вам передали данные о некоторых пользователях из нескольких городов, а также об их поездках. Проанализируйте данные и проверьте некоторые гипотезы, которые могут помочь бизнесу вырасти. Чтобы совершать поездки по городу, пользователи сервиса GoFast пользуются мобильным приложением.</td>
<td><b>библиотеки</b>
<tr>
<td><b>4</b></td>
<td>Сборный проект №1</td> 
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/4%20Сборный%20проект.ipynb" target="_blank"><b>Сборный проект №1</b></a></td>
<td>Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.Перед вами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и вы планируете кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года. В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».</td>
<td><b>библиотеки</b>
<tr>
<td><b>5</b></td>
<td>Линейные модели в машинном обучении</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/Исследование%20надежности%20заемщиков.ipynb" target="_blank"><b>Прогнозные модели для отбора бурёнок в поголовье.</b></a></td>
<td>Вы работаете в IT-компании, которая выполняет на заказ проекты по машинному обучению. К вам обратился фермер, владелец молочного хозяйства «Вольный луг». Он хочет купить бурёнок, чтобы расширить поголовье стада коров. Для этого он заключил выгодный контракт с ассоциацией пастбищ «ЭкоФерма».
Условия позволяют фермеру очень тщательно отобрать коров. Он определяет качество молока по строгой методике, и при этом ему нужно выполнять свой план развития молочного хозяйства. Фермер хочет, чтобы каждая бурёнка давала не менее 6000 килограммов молока в год, а её надой был вкусным — строго по его критериям, ничуть не хуже. А продавцы и технологи так и норовят приукрасить своих коровок!
Поэтому он просит вас разработать модель машинного обучения, которая поможет ему управлять рисками и принимать объективное решение о покупке. «ЭкоФерма» готова предоставить подробные данные о своих коровах. Вам нужно создать две прогнозные модели для отбора бурёнок в поголовье:
Первая будет прогнозировать возможный удой коровы (целевой признак Удой);
Вторая — рассчитывать вероятность получить вкусное молоко от коровы (целевой признак Вкус молока).
С помощью модели нужно отобрать коров по двум критериям:
средний удой за год — не менее 6000 килограммов;
молоко должно быть вкусным.</td>
<td><b>библиотеки</b>
<tr>
<td><b>6</b></td>
<td>Обучение с учителем: качество модели</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/Исследование%20надежности%20заемщиков.ipynb" target="_blank"><b>Персонализация предложений постоянным клиентам, чтобы увеличить их покупательскую активность.</b></a></td>
<td>Интернет-магазин «В один клик» продаёт разные товары: для детей, для дома, мелкую бытовую технику, косметику и даже продукты. Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. Возможный выход — удерживать активность постоянных клиентов. Сделать это можно с помощью персонализированных предложений.
«В один клик» — современная компания, поэтому её руководство не хочет принимать решения просто так — только на основе анализа данных и бизнес-моделирования. 
Необходимо разработать решение, которое позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность.</td>
<td><b>библиотеки</b>
<tr>
<td><b>7</b></td>
<td>Сборный проект №2</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/Исследование%20надежности%20заемщиков.ipynb" target="_blank"><b>HR-аналитика</b></a></td>
<td>HR-аналитики компании «Работа с заботой» помогают бизнесу оптимизировать управление персоналом: бизнес предоставляет данные, а аналитики предлагают, как избежать финансовых потерь и оттока сотрудников. В этом HR-аналитикам пригодится машинное обучение, с помощью которого получится быстрее и точнее отвечать на вопросы бизнеса.
Компания предоставила данные с характеристиками сотрудников компании. Среди них — уровень удовлетворённости сотрудника работой в компании. Эту информацию получили из форм обратной связи: сотрудники заполняют тест-опросник, и по его результатам рассчитывается доля их удовлетворённости от 0 до 1, где 0 — совершенно неудовлетворён, 1 — полностью удовлетворён. 
Несколько задач. Первая — построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика. 
Почему бизнесу это важно: удовлетворённость работой напрямую влияет на отток сотрудников. А предсказание оттока — одна из важнейших задач HR-аналитиков. Внезапные увольнения несут в себе риски для компании, особенно если уходит важный сотрудник.
Вторая задача — построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.</td>
<td><b>библиотеки</b>
<tr>
<td><b>8</b></td>
<td>Машинное обучение в бизнесе</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/Исследование%20надежности%20заемщиков.ipynb" target="_blank"><b>Выбор локации для скважины</b></a></td>
<td>Допустим, вы работаете в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину. 
Шаги для выбора локации обычно такие:
В избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов;
Строят модель для предсказания объёма запасов в новых скважинах;
Выбирают скважины с самыми высокими оценками значений;
Определяют регион с максимальной суммарной прибылью отобранных скважин.
Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap.</td>
<td><b>библиотеки</b>
<tr>
<td><b>9</b></td>
<td>Численные методы</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/9%20Численные%20методы.ipynb" target="_blank"><b>Определение стоимости автомобилей</b></a></td>
<td>Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение, чтобы привлечь новых клиентов. В нём можно будет узнать рыночную стоимость своего автомобиля. 
Постройте модель, которая умеет её определять. В вашем распоряжении данные о технических характеристиках, комплектации и ценах других автомобилей.
Критерии, которые важны заказчику:
качество предсказания;
время обучения модели;
время предсказания модели.</td>
<td><b>библиотеки</b>
<tr>
<td><b>10</b></td>
<td>Временные ряды</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/10%20Временные%20ряды.ipynb" target="_blank"><b>Прогнозирование заказов такси</b></a></td>
<td>Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. Постройте модель для такого предсказания.
Значение метрики RMSE на тестовой выборке должно быть не больше 48.</td>
<td><b>библиотеки</b>
<tr>
<td><b>11</b></td>
<td>Машинное обучение для текстов</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/11%20Машинное%20обучение%20для%20текстов.ipynb" target="_blank"><b>Проект для «Викишоп»</b></a></td>
<td>Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 
Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.</td>
<td><b>библиотеки</b>
<tr>
<td><b>12</b></td>
<td>Компьютерное зрение</td>
<td><a href="https://github.com/EvgeniaKl/ds/blob/main/12%20Компьютерное%20зрение.ipynb" target="_blank"><b>Определение возраста покупателей</b></a></td>
<td>Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы: анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы; контролировать добросовестность кассиров при продаже алкоголя.
Постройте модель, которая по фотографии определит приблизительный возраст человека. В вашем распоряжении набор фотографий людей с указанием возраста.</td>
<td><b>библиотеки</b>
