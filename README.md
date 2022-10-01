Детектирование аномалий в данных
===============================


Команда проекта
------------------

|Имя, фамилия         | Логин          |
| -------------       |:------------------:| 
| Виктория Инюцина    | [vsinyutsina](https://github.com/vsinyutsina)       | 
| Артур Хлебников     | [arti752](https://github.com/arti752)         |  
| Сергей Писаренко    |[phleelapsmee](https://github.com/phleelapsmee)      | 

Введение
------------------
Детектирование аномалий - важное направление в современном анализе данных, целью которого является поиск отклонений от основных распеределений данных и/или от общего нормального "поведения" объектов. Детектирование аномалий доказало свою значимость во многих областях, таких как обнаружение сетевых вторжений, выявление мошенничества с кредитными картами и поиск дефектов технологического оборудования.

Цель
------------------
Выявить мошеннические транзакции с помощью semi-supervised learning на основе [датасета](https://www.kaggle.com/competitions/ieee-fraud-detection/overview) от e-commerce компании Vesta Corporation

Основные этапы проекта
----------------------
#### 1. Анализ и предобработка данных
* Первичный анализ данных
* EDA подозрительных транзакций
* Общее описание признаков и статистик
* Нормализация данных
* Поиск линейно независимых признаков
* Feature engineering
#### 2. ML моделирование
* Поиск и построение линейной модели бинарной классификации
* Выбор метрик для оценки работы моделей
* Определения бенчмарка
* что-то про ML
#### 2.5 GO/Временные ряды
* Опиционально
#### 3. DL моделирование
* Внедрение DL-моделей: построение и подбор параметров, выбор наилучшей
* Обучение GAN-моделей: генерирование транзакций и выявление аномалий
* Что-то про DL
#### 4. Реализация веб-сервиса
* Создание веб-сервиса с возможностью выбора и генерирования параметров для ML/DL-моделей

Результаты
------------------
Web-сервис на котором реализована GAN модель с двумя нейронными сетями: одна создает выборку транзакций, другая выискивает аномалии
