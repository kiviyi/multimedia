# Студент группы М8О-401Б-21 Ворошилов Кириллд Сергеевич

В этом репозитории лежат выполненные лабораторные работы 1-5 по курсу "Методы, средства и технологии мультимедиа"

# Условие

**1. Выбор начальных условий**

a. Выбор набора данных для задачи классификации  
   Уникальный для каждого студента.  
   Обоснование: реальная практическая задача.  

b. Выбор набора данных для задачи регрессии  
   Уникальный для каждого студента.  
   Обоснование: реальная практическая задача.  

c. Выбор метрик качества и обоснование их выбора  

**2. Создание бейзлайна и оценка качества**

a. Обучение моделей из sklearn для классификации и регрессии на выбранных наборах данных  

b. Оценка качества моделей по выбранным метрикам на выбранных наборах данных  

**3. Улучшение бейзлайна**

a. Формулирование гипотез  
   - Препроцессинг данных  
   - Визуализация данных  
   - Формирование новых признаков  
   - Подбор гиперпараметров на кросс-валидации  

b. Проверка гипотез  

c. Формирование улучшенного бейзлайна по результатам проверки гипотез  

d. Обучение моделей с улучшенным бейзлайном для классификации и регрессии  

e. Оценка качества моделей с улучшенным бейзлайном по выбранным метрикам  

f. Сравнение результатов моделей с улучшенным бейзлайном с результатами из пункта 2  

g. Сделать выводы  

**4. Имплементация алгоритма машинного обучения**

a. Самостоятельная имплементация алгоритмов машинного обучения для классификации и регрессии  

b. Обучение имплементированных моделей на выбранных наборах данных  

c. Оценка качества имплементированных моделей по выбранным метрикам  

d. Сравнение результатов имплементированных моделей с результатами из пункта 2  

e. Добавление техник из улучшенного бейзлайна (пункт 3)  

f. Обучение моделей для классификации и регрессии с учетом улучшений  

g. Оценка качества моделей с улучшенным бейзлайном  

h. Сравнение результатов моделей с результатами из пункта 3  

i. Сделать выводы  


# Подведение итогов

В следующей таблице в ячейках, относящихся к классифкации я буду отображать **accuracy**; в ячейках, относящихся к регрессии я буду отображать **MSE**

*Метрика качества на тестовом наборе данных*
<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
        <th>Самостоятельная имплементация алгоритма с улучшенным бейзлайном</th>
    </tr>
    <tr>
        <td rowspan="2">KNN</td>
        <td>классификация</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>1.11868</td>
        <td>1.11868</td>
        <td>0.419469</td>
        <td>0.419469</td>
    </tr>
    <tr>
        <td rowspan="2">Линейные модели</td>
        <td>классификация</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>0.3</td>
        <td>0.5</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.76456</td>
        <td>0.59429</td>
        <td>0.5639</td>
        <td>0.46143</td>
    </tr>
    <tr>
        <td rowspan="2">Решающее дерево</td>
        <td>классификация</td>
        <td>1.0</td>
        <td>0.967</td>
        <td>1.0</td>
        <td>0.967</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.48226</td>
        <td>0.426199</td>
        <td>0.49295</td>
        <td>0.427564</td>
    </tr>
    <tr>
        <td rowspan="2">Случайный лес</td>
        <td>классификация</td>
        <td>1.0</td>
        <td>0.967</td>
        <td>1.0</td>
        <td>1.0</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.492896</td>
        <td>0.42178</td>
        <td>0.29329</td>
        <td>0.318576</td>
    </tr>
    <tr>
        <td rowspan="2">Градиентный бустинг</td>
        <td>классификация</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
        <td>1.0</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.294</td>
        <td>0.2596</td>
        <td>0.294</td>
        <td>0.2591</td>
    </tr>
</table>


<br><br>
