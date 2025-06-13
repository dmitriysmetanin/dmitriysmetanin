## Привет! Я Дмитрий 👋🏻
> [!IMPORTANT]
> Data Engineer с опытом построения ETL-систем и хранилищ данных для госсектора и образования.<br>
> Разрабатываю DWH и ETL-пайплайны, витрины данных и BI.<br>
> С опытом в fullstack (Python&Django) и ML (PyTorch), что позволяет проектировать комплексные data-решения.<br>

## Технологии 🔨:
- **БД**: PostgreSQL, MS SQL, MongoDB, Milvus;
- **Обработка данных**: Airflow, Spark, Kafka;
- **Инфраструктура**: Docker, Kubernetes (базовое развертывание), Yandex Cloud;
- **Мониторинг**: Prometheus, Loki, Grafana, K6;
- **BI**: Yandex Datalens;

## Опыт 🦉:
Минобрнауки России | Инженер данных | Октябрь 2022 — н.в.
<p><b>— Проектирование и разработка хранилищ данных</p></b>
<p>- Спроектировал и разработал хранилища OLTP / DWH на PostgreSQL на моделях 3NF и DataVault (140+ таблиц), что обеспечило целостность данных и удобство для аналитики.</p>
<p>- Настроил CDC через Kafka для real-time загрузки данных из OLTP-системы в DWH, сократив задержку обновления данных с часов до минут.</p>

<p><b>— Разработка ETL/ELT-процессов</p></b>
<p> - Разработал пайплайны в Airflow для обработки 2M+ записей/день из VK, Telegram и других источников, что предотвратило 3 кризисные ситуации и обеспечило стабильную отчетность.</p>
<p> - Развернул Spark-кластер и оптимизировал обработку данных с помощью SparkSQL, ускорив выполнение аналитических запросов на 70%.</p>

<p><b>— BI-инструменты и мониторинг данных</p></b>
<p> - Внедрил дашборды в Yandex DataLens, которые используются Минобрнауки для мониторинга социальных рисков в 14 регионах России.</p>
<p> - Настроил мониторинг инфраструктуры через Prometheus + Grafana, сократив среднее время реакции на инциденты с 8 часов до 1 часа.</p>

<p><b>— Инфраструктура и DevOps</p></b>
<p> - Контейнеризировал 14 сервисов с помощью Docker, настроив health-checks и достигнув uptime 99.9%.</p>


## Примеры работ 👨‍💻:

<details>

<summary><b>БД</b> (PostgreSQL MS SQL & MongoDB & Milvus)</summary>

### PostgreSQL

...

### MS SQL

...

### MongoDB

...

### Milvus

Система распознавания лиц (CV):
- создание эмбеддингов через ResNet-50;
- однозначная идентификация человека по лицу + поиск подобных лиц;
- поиск на базе индексов Milvus.
<img src="assets/images/milvus.png">


</details>

<details>

<summary><b>Обработка данных</b> (Airflow & Spark & Kafka)</summary>

### Apache Airflow

<div style="display:flex; flex-direction:column;">
  <div style="display:flex; flex-direction:row;">
    Создание бэкапов по расписанию и загрузка в облачное хранилище
    <img src="assets/images/airflow-backups.png" style="width: 50%;">
  </div>
  <div style="display:flex; flex-direction:row;">
    
  </div>
</div>

### Apache Spark

...

### Apache Kafka

...

</details>

<details>

<summary><b>Мониторинг</b> (Prometheus & Loki & Grafana)</summary>

### Prometheus

...

### Loki

...

### Grafana

...

</details>

<details>

<summary><b>BI</b> (Yandex Datalens & Google Sheets & Matplotlib & Seaborn)</summary>

### Yandex Datalens
Интерактивные дашборды:
- контроль исполнения задач подразделениями;
- мониторинг эффективности работы в корпоративной системе.
<img src="assets/images/datalens.jpg">

</details>

<details>

<summary><b>Тестирование</b> (K6 & PgBench & Selenium)</summary>

### K6

Нагрузочное тестирование веб-приложений:
- проверка latency запросов к API / страницам;
- поиск медленных страниц для оптимизации;
- оценка максимальной пропускной способности системы.
<img src="assets/images/grafana-k6.png">

### PgBench

...

</details>

## Образование 👨‍🎓
Казанский (Приволжский) федеральный университет<br>
Бакалавр "Программная инженерия"<br>
<br>
Курсы:<br>
«Инженер облачных сервисов» | [Yandex Cloud](https://start.practicum.yandex/ycloud/)<br>
«Managed Service for Kubernetes» | [Yandex Cloud](https://yandex.cloud/ru/training/kubernetes)<br>
«Введение в параллельное программирование (OpenMP и MPI)» | [ТГУ](https://stepik.org/course/115024/syllabus)
