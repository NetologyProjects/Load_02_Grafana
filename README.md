[Источник](https://github.com/netology-code/loadqa-homeworks/tree/main/2.Load%20environment)

#### ---Команды docker
`docker compose up -d` - запуск файла настройки docker-compose.yml из текущей папки\
`docker compose down` - остановка и удаление контейнеров, запущенных командой указанной выше\
`docker ps` - состояние докера\
`docker restart telegraf` - перезапуск контейнера telegraf\
***

# Домашнее задание к лекции 2 «‎Подготовка стенда нагрузочного тестирования»

### Задание

1. Развернуть систему мониторинга на базе `telegraf` + `influxDB`.
2. Развернуть систему мониторинга на базе  `node-exporter` + `prometheus`.
3. Для отображения использовать дашборды `grafana`.
4. Настроить мониторинг на отображение всех аппаратных метрик вашего сервера (компьютера).
5. **Для telegraf**: сделать частоту отправки метрик каждые 60 секунд, подключить метрики оперативной памяти и swap, жёсткого диска и сети.
6. **Для prometheus**: сделать частоту отправки метрик каждые 36 секунд.
7. Сделать скриншоты состояния метрик системы в покое длительностью минимум 15 минут.

### Отправка задания на проверку

Нужно запушить репозиторий с конфигурацией, дашбордами и скриншотами на GitHub и отправить на проверку ссылку на репозиторий.

### Дополнительная информация
1. [Инструкция по работе систем мониторинга с `grafana`](https://grafana.com/docs/grafana/latest/getting-started/).
2. [Описание методологии сбора метрик](https://habr.com/ru/company/itsumma/blog/596845/).
3. [Описание моделей мониторинга](https://habr.com/ru/post/551264/).
4. [Описание подходов к логированию](https://habr.com/ru/post/551264/).
5. [Описание конфигурации тестового стенда](http://www.protesting.ru/automation/practice/test_stand_configuration.html).
6. [Подход к созданию тестового стенда](https://habr.com/ru/company/rtlabs/blog/577580/).

<details>
  <summary>Подсказка.</summary>

  Используйте примеры из  папки [./samples](./samples) для начальной настройки мониторинга.
</details>

### Критерии оценки

1. Зачёт — выполнены все задания, ответы даны в развёрнутой форме, в выполненных заданиях нет противоречий и нарушения логики.
2. На доработку — задание выполнено частично или не выполнено совсем, в логике решения есть противоречия и существенные недостатки.

Любые вопросы по решению задач задавайте в чате учебной группы.
