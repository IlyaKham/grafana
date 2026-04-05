# Домашнее задание "Средство визуализации Grafana" --- 'Хамуро ИА'
### Задание 1
Используя директорию help внутри этого домашнего задания, запустите связку prometheus-grafana.
Зайдите в веб-интерфейс grafana, используя авторизационные данные, указанные в манифесте docker-compose.
Подключите поднятый вами prometheus, как источник данных.
Решение домашнего задания — скриншот веб-интерфейса grafana со списком подключенных Datasource.
### Ответ
<img width="1053" height="404" alt="Снимок экрана 2026-04-05 111137" src="https://github.com/user-attachments/assets/97692693-ac55-4c65-9cac-e8144df05b6f" />

### Задание 2
Изучите самостоятельно ресурсы:

PromQL tutorial for beginners and humans.
Understanding Machine CPU usage.
Introduction to PromQL, the Prometheus query language.
Создайте Dashboard и в ней создайте Panels:

утилизация CPU для nodeexporter (в процентах, 100-idle);
CPULA 1/5/15;
количество свободной оперативной памяти;
количество места на файловой системе.
Для решения этого задания приведите promql-запросы для выдачи этих метрик, а также скриншот получившейся Dashboard.
### Ответ
<img width="1505" height="782" alt="Снимок экрана 2026-04-05 111402" src="https://github.com/user-attachments/assets/175f7a7a-6036-497f-abc7-8237f72d5960" />
<img width="1511" height="739" alt="Снимок экрана 2026-04-05 112702" src="https://github.com/user-attachments/assets/72108028-5a91-4ce4-bb1d-904a3167adbe" />
<img width="1500" height="821" alt="Снимок экрана 2026-04-05 112651" src="https://github.com/user-attachments/assets/5748251e-40a9-413a-b5ba-b54236326dc7" />
<img width="1510" height="863" alt="Снимок экрана 2026-04-05 111624" src="https://github.com/user-attachments/assets/9a4f751d-c9db-4d18-9701-57f1a4b5976b" />

### Задание 3
Создайте для каждой Dashboard подходящее правило alert — можно обратиться к первой лекции в блоке «Мониторинг».
В качестве решения задания приведите скриншот вашей итоговой Dashboard.
### Ответ
<img width="1636" height="554" alt="Снимок экрана 2026-04-05 123430" src="https://github.com/user-attachments/assets/6f5d6478-6433-4d58-a64c-ade643b9355e" />
<img width="1636" height="264" alt="Снимок экрана 2026-04-05 123438" src="https://github.com/user-attachments/assets/020f0f7c-a1ab-43d1-b7f2-56f8faf58ddc" />

### Задание 4
Сохраните ваш Dashboard.Для этого перейдите в настройки Dashboard, выберите в боковом меню «JSON MODEL». Далее скопируйте отображаемое json-содержимое в отдельный файл и сохраните его.
В качестве решения задания приведите листинг этого файла.

### Ответ
Прикрпил файл в репозиторий dashboard.json
