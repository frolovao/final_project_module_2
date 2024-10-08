# HR-аналитика компании.
HR-аналитики компании «Работа с заботой» помогают бизнесу оптимизировать управление персоналом: бизнес предоставляет данные, а аналитики предлагают, как избежать финансовых потерь и оттока сотрудников. 

**Первая задача:** построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика.   
**Вторая задача:** построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.

**Описание данных:** 
* *Задача 1:*
  * `id` — уникальный идентификатор сотрудника;
  * `dept` — отдел, в котором работает сотрудник;
  * `level` — уровень занимаемой должности;
  * `workload` — уровень загруженности сотрудника;
  * `employment_years` — длительность работы в компании (в годах);
  * `last_year_promo` — показывает, было ли повышение за последний год;
  * `last_year_violations` — показывает, нарушал ли сотрудник трудовой договор за последний год;
  * `supervisor_evaluation` — оценка качества работы сотрудника, которую дал руководитель;
  * `salary` — ежемесячная зарплата сотрудника;
  * `job_satisfaction_rate` — уровень удовлетворённости сотрудника работой в компании, целевой признак. 
  
  
* *Задача 2:*
  * `id` — уникальный идентификатор сотрудника;
  * `dept` — отдел, в котором работает сотрудник;
  * `level` — уровень занимаемой должности;
  * `workload` — уровень загруженности сотрудника;
  * `employment_years` — длительность работы в компании (в годах);
  * `last_year_promo` — показывает, было ли повышение за последний год;
  * `last_year_violations` — показывает, нарушал ли сотрудник трудовой договор за последний год;
  * `supervisor_evaluation` — оценка качества работы сотрудника, которую дал руководитель;
  * `salary` — ежемесячная зарплата сотрудника;
  * `quit` — увольнение сотрудника из компании, целевой признак.

**План исследования:**
1. Загрузка файлов с данными для первой задачи.
2. Предобработка данных.
3. Исследовательский анализ всех признаков.
4. Подготовка данных в пайплайне.
5. Обучение моделей для первой задачи.
6. Выводы по первой задаче.
7. Загрузка файлов с данными для второй задачи.
8. Предобработка данных для второй задачи.
9. Исследовательский анализ данных.
10. Добавление нового входного признака.
11. Подготовка данных в пайплайне для второй задачи.
12. Обучение моделей для второй задачи.
13. Выводы по второй задаче.
14. Общий вывод.
