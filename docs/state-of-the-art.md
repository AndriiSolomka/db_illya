# Аналіз предметної області

## Вступ

*[Вступ повинен містити короткий огляд всього документу.]*

Системи управління відкритими даними призначені для зберігання, обробки та забезпечення доступу до публічної інформації у зручному для використання та повторного аналізу форматі. У документі буде розглянуто ключові концепції та терміни, визначено основні підходи до управління відкритими даними, оцінено різні системи з точки зору функціональних та нефункціональних вимог (FURPS) .

## Основні визначення

*[Розділ містить визначення термінів та скорочень, які використовуються при аналізі предметної області.]*

Відкриті дані – це дані, які доступні для безкоштовного використання, обробки та поширення без обмежень щодо авторських прав, патентів чи інших форм контролю. Вони можуть бути використані будь-ким для аналізу, дослідження або створення нових продуктів і послуг.

База даних – це організоване зібрання структурованої інформації, що зберігається та керується системою управління базами даних (СУБД). Бази даних використовуються для зберігання, обробки та управління даними, забезпечуючи їх доступність та цілісність. Вони є основою для багатьох додатків, служб та систем, що потребують зберігання великих обсягів даних. Існують різні типи баз даних, такі як реляційні (наприклад, MySQL, PostgreSQL) та нереляційні (наприклад, MongoDB, Cassandra), що впливають на їх використання в залежності від потреб користувачів та специфіки даних.

Система управління відкритими даними (Open Data Management System, ODMS) – це програмний комплекс, що забезпечує збір, зберігання, обробку, публікацію та управління відкритими даними. Вона дозволяє організаціям і державним установам ефективно управляти даними, що публікуються для загального доступу, сприяючи прозорості, відповідальності та інноваціям.

API (Application Programming Interface) – це інтерфейс програмування додатків, який дозволяє програмам взаємодіяти між собою, обмінюючись даними та викликаючи функції один одного. API визначає набір правил і протоколів, які дають можливість одній програмі або сервісу використовувати функціональність іншої програми без необхідності знати, як вона працює всередині.

Метадані – це дані про дані, що описують характеристики, структуру, походження, контекст або інші аспекти самих даних. Вони забезпечують більш детальне розуміння та організацію інформації, полегшуючи її пошук, інтерпретацію та управління.

Основні види метаданих:
Описові метадані – дають інформацію про зміст і характеристики даних, допомагаючи користувачам зрозуміти, що являють собою дані. Наприклад, це може бути назва набору даних, автор, дата створення, ключові слова тощо.

Структурні метадані – описують, як організовані дані. Вони визначають структуру файлів, формат запису, зв’язки між об'єктами або елементами даних. Наприклад, це може бути схема бази даних або структура XML-документа.

Адміністративні метадані – забезпечують інформацію для управління даними, їх обробки та використання.

Object-Relational Mapping (ORM) – це технологія програмування, яка дозволяє взаємодіяти з базою даних, використовуючи об'єкти у коді замість написання SQL-запитів. ORM автоматично перетворює об'єкти в реляційні записи в базі даних та навпаки, спрощуючи доступ до даних і роблячи роботу з базою більш зрозумілою для розробників. Основна ідея ORM полягає в тому, що кожен клас у програмі відповідає таблиці в базі даних, а кожен об'єкт цього класу – це запис у цій таблиці.

## Підходи та способи вирішення завдання


### Збір даних

### Опитування

### Приклад використання

- Збір інформації про задоволеність клієнтів.

### Інструменти

- Google Forms
- SruveyMonkey
- Typeform

### Переваги

- Легкість у створенні та розповсюдженні
- Можливість отримання специфічних даних

### Недоліки

- Висока залежність від респондентів.
- Можливість упередженості у відповідях.

### Аналіз соціальних мереж

### Приклад використання

- Вивчення громадської думки щодо політичних кампаній.

### Інструменти

- Brandwatch
- Hootsuite
- Sprout Social

### Переваги

- Широкий обсяг даних.
- Можливість швидкого реагування на зміни.

### Недоліки

- Складність у фільтрації релевантних даних.
- Високий рівень шуму (недостовірної інформації).

### Web-scraping

### Приклад використання

- Збір інформації з веб-сайтів про ціни на товари.

### Інструменти

- Beautiful Soup, Scrapy.

### Переваги

- Можливість збору великих обсягів даних, автоматизація процесу.

### Недоліки

- Правові питання, ризик отримання неактуальної або неповної інформації.

### Сенсори та IoT

### Приклад використання

- Моніторинг якості повітря за допомогою сенсорів.

### Інструменти

- Arduino, Raspberry Pi.

### Переваги

- Збір даних в реальному часі, висока точність.

### Недоліки

- Вартість обладнання, необхідність технічних знань.

### Державні ресурси

### Приклад використання

- Оприлюднення статистичних даних про економіку.

### Інструменти

- Портали відкритих даних (data.gov).rduino, Raspberry Pi.

### Переваги

-  Офіційні джерела, надійність даних.

### Недоліки

-  Можливі затримки у публікації, обмежена частота оновлення.

### Зберігання даних

Система збереження данних є важливим інструментом для забезпечення доступу до інформації, яка має суспільну цінність.

### Основні підходи до зберігання даних

- Реляційні бази даних: Реляційні бази даних є традиційним методом зберігання даних, де інформація організована у таблиці, що пов'язані між собою. Цей підхід забезпечує структурованість, цілісність та зручність в отриманні даних через SQL-запити.
- Нереляційні (NoSQL) бази даних: Нереляційні бази даних, такі як MongoDB або Cassandra, дозволяють зберігати дані у вигляді документів, графів або ключ-значення. Вони є більш гнучкими і підходять для великих обсягів неструктурованих даних.
- Хмарне зберігання: Використання хмарних сервісів, таких як AWS, Google Cloud або Azure, дозволяє зберігати дані на віддалених серверах. Це забезпечує високу доступність, масштабованість та зменшує витрати на інфраструктуру.
- Локальне зберігання: У деяких випадках дані зберігаються локально на серверах організацій. Цей підхід може бути більш безпечним для чутливої інформації, але може мати обмеження щодо доступності та масштабованості.

### Моделі зберігання даних

- Модель "таблиця": У реляційних базах даних дані організуються у вигляді таблиць з рядками та стовпцями. Це дозволяє легко виконувати запити, фільтрацію та агрегацію даних.
- Модель "документ": Використовується в нереляційних базах даних, де дані зберігаються у форматі JSON або XML. Ця модель дозволяє зберігати складні структури даних та є ідеальною для веб-додатків.
- Модель "граф": Застосовується для зберігання даних, пов'язаних між собою, таких як соціальні мережі. Графові бази даних, наприклад Neo4j, дозволяють ефективно аналізувати зв'язки між об'єктами.
- Модель "ключ-значення": Ця проста модель використовується в базах даних, де дані зберігаються у вигляді пар "ключ-значення". Вона забезпечує високу швидкість доступу і підходить для кешування та простих запитів.

### Аналіз даних

Аналіз даних є критично важливим етапом у системі управління відкритими даними. Він дозволяє виявляти тренди, моделі та залежності, що сприяє прийняттю обґрунтованих рішень.
Завдяки аналізу даних можна отримати цінну інформацію, яка допомагає в різних сферах, включаючи економіку, науку та соціальні дослідження.

### Методи аналізу даних

- Описова статистика: Використовується для узагальнення та опису основних характеристик набору даних. Наприклад, середнє значення, медіана, мода, стандартне відхилення.
- Інфографіка: Візуалізація даних через графіки, діаграми та карти, що полегшує сприйняття інформації та виявлення патернів.
- Кореляційний аналіз: Досліджує зв’язки між різними змінними, що дозволяє виявити, чи є залежність між ними.
- Регресійний аналіз: Визначає залежність однієї змінної від іншої, що допомагає передбачати результати на основі історичних даних.
- Кластерний аналіз: Групує дані в класи, що допомагає виявити схожість між об'єктами та виділити групи з подібними характеристиками.
- Аналіз часових рядів: Досліджує дані, зібрані у різні моменти часу, що дозволяє виявити сезонні тренди та циклічні зміни.
- Машинне навчання: Використання алгоритмів для автоматичного виявлення закономірностей у даних, зокрема класифікації, регресії та кластеризації.
- Текстовий аналіз: Аналіз неструктурованих даних, таких як текстові документи, що дозволяє видобувати цінну інформацію з текстів.
- Аналіз великих даних (Big Data): Застосування спеціальних технологій та інструментів для обробки та аналізу великих обсягів даних, що дозволяє отримувати нові інсайти.

### Обробка даних

Обробка даних у системі управління відкритими даними включає етапи збору, попередньої обробки, аналізу, візуалізації, зберігання та публікації даних.
Цей процес дозволяє забезпечити якість і доступність даних для користувачів.

### Основні етапи обробки даних

- Збір даних: На першому етапі необхідно зібрати дані з різних джерел. Це можуть бути опитування, сенсори, веб-сайти, бази даних тощо.
- Попередня обробка: Цей етап включає очищення даних від помилок, неповних або некоректних записів. Важливо також стандартизувати формати даних для подальшої роботи.
- Аналіз даних: На цьому етапі дані піддаються аналізу за допомогою статистичних методів та алгоритмів. Це може включати в себе виявлення закономірностей, трендів або аномалій.
- Візуалізація даних: Візуалізація допомагає зрозуміти результати аналізу. Графіки, діаграми та інші візуальні інструменти роблять інформацію більш доступною для сприйняття.
- Зберігання даних: Оброблені дані повинні бути збережені у безпечному місці, щоб забезпечити їх доступність та цілісність. Це можуть бути реляційні бази даних, хмарні рішення або локальні сервери.
- Публікація даних: Останній етап — це публікація відкритих даних для загального доступу. Важливо забезпечити зручний доступ до даних через API, веб-портали або інші платформи.

### Інструменти для обробки даних

- Excel: зручний для аналізу та візуалізації даних.
- Python: з бібліотеками, такими як pandas для обробки даних та SQLAlchemy для роботи з базами даних.
- MySQL: система управління реляційними базами даних.
- PostgreSQL: потужна реляційна база даних з розширеними можливостями.
- SQLite: легка база даних, що підходить для невеликих проєктів.

### Забезпечення доступу

Системи забезпечення доступу до відкритих даних є важливими для забезпечення прозорості та ефективності використання інформації.
Вони забезпечують контроль за доступом до даних, що має суспільну цінність, і сприяють розвитку інновацій. Для їх ефективної роботи потрібні надійні механізми контролю доступу.

### OAuth

Стандарт для авторизації, що дозволяє стороннім додаткам отримувати обмежений доступ до ресурсів без надання облікових даних користувача. Використовується в багатьох веб-сервісах.

### Основні компоненти

- Ресурсний сервер
- Сервер авторизації
- Клієнт
- Користувач

### Переваги

- Гнучкість у налаштуваннях доступу
- Можливість інтеграції з різними сервісами

### Недоліки

- Складність в налаштуванні
- Можливість зловживання токенами

### OpenID Connect

Протокол, що базується на OAuth 2.0, який дозволяє користувачам аутентифікуватися через сторонній ідентифікаційний провайдер, спрощуючи вхід на різні ресурси.

### Основні компоненти

- Ідентифікаційний провайдер
- Ресурсний сервер
- Клієнт

### Переваги

- Підтримка одноразових логінів
- Зручність для користувачів

### Недоліки

- Залежність від третьої сторони
- Потенційні проблеми з конфіденційністю

### LDAP (Lightweight Directory Access Protocol)

Протокол для доступу та управління інформацією в каталогах, зазвичай використовується для централізованого управління доступом до ресурсів у мережі.

### Основні компоненти

- LDAP-сервер
- Клієнтські застосунки

### Переваги

- Централізоване управління доступом
- Легкість у масштабуванні

### Недоліки

- Вимоги до налаштування серверів
- Може бути складним для початківців

## Порівняльна характеристика існуючих засобів вирішення завдання

### CKAN

CKAN (Comprehensive Knowledge Archive Network) — одна з найбільш популярних платформ для управління відкритими даними, яка широко використовується урядами та організаціями.

### Основні характеристики:

- Підтримує багатоформатність даних.
- Інтеграція з API.
- Можливість користувацького налаштування.

### DKAN

DKAN — це рішення на базі Drupal, яке пропонує інтуїтивно зрозумілий інтерфейс для управління даними.

### Основні характеристики:

- Легка інтеграція з Drupal.
- Широкі можливості для кастомізації.
- Зручний для користувачів.

### DataHub

DataHub — це платформа, яка фокусується на збиранні, обробці та публікації даних.

### Основні характеристики:

- Висока продуктивність.
- Гнучка структура даних.
- Інтеграція з зовнішніми API.

| Платформа	| **Functionality**            	                     | **Usability**                   | **Reliability** | **Performance**        | **Supportability**    |
|-----------|----------------------------------------------------|---------------------------------|-----------------|------------------------|-----------------------|
| CKAN      | Інтеграція з API (реалізована)                     | Інтуїтивно зрозумілий інтерфейс | Стабільна       | Висока продуктивність  | Активна спільнота     |
| DKAN      | Інтеграція з API (реалізована, проте має недоліки) | Зручний для користувачів        | Стабільна       | Помірна продуктивність | Обмежена документація |
| DataHub   | Інтеграція з API (реалізована)                     | Інтуїтивно зрозумілий інтерфейс | Стабільна       | Висока продуктивність  | Активна підтримка     |

## Висновки

Система управління відкритими даними є ключовим інструментом для забезпечення прозорості, підвищення ефективності та сприяння інноваціям у суспільстві.
Вона дозволяє організаціям, державним установам та громадськості отримувати доступ до важливої інформації, що сприяє прийняттю обґрунтованих рішень.
Ефективна реалізація таких систем потребує інтеграції технологій, забезпечення безпеки даних та активної участі користувачів.
Завдяки цьому, відкриті дані можуть стати потужним каталізатором соціально-економічного розвитку,
полегшуючи співпрацю між різними секторами та підвищуючи рівень довіри до державних інституцій.

## Посилання

- [Відкриті дані](https://en.wikipedia.org/wiki/Open_data)
- [Збір Даних](https://www.researchgate.net/publication/359596426_Data_Collection_Methods_and_Tools_for_Research_A_Step-by-Step_Guide_to_Choose_Data_Collection_Technique_for_Academic_and_Business_Research_Projects)
- [SQL бази даних](https://en.wikipedia.org/wiki/SQL)
- [Web scraping](https://en.wikipedia.org/wiki/Web_scraping)
- [CKAN](https://docs.ckan.org/en/2.11/)
- [DKAN](https://dkan.readthedocs.io/en/latest/)
- [DataHub](https://datahubproject.io/docs/features)