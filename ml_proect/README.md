# Итоговый проект курса "Машинное обучение в бизнесе"

### Задача: предсказать вероятность смены работы по характеристикам сотрудника. Бинарная классификация
Данные: Kaggle - https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists
Задача: предсказать вероятность смены работы по характеристикам сотрудника. Бинарная классификация

Используемые признаки:

 * city_development_index (float)
 * training_hours (int)
 * gender (text)
  * education_level (text)
  * enrolled_university (text)
  * major_discipline (text)
 * experience (text)
 * relevent_experience (text)
 * last_new_job (text)
 * company_size (text)
 * company_type (text)
 * city (text)

Преобразования признаков: OneHotEncoder, CatBoostEncoder, кастомный энкодер для поля 'experience'

Модель: CatBoost


### Клонируем репозиторий


    $ git clone https://github.com/ennsyuliya/Machine-learning-business.git ml_project
    $ cd ml_api_project


### Запускаем контейнер


    $ docker-compose up -d
     


