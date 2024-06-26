# RobotMotorsControl
Test repository
Шаги выполнения заданий
1. Создана учетная запись на GitHub. Создан репозиторий RobotMotorsControl. Репозиторий клонирован в репозиторий на АРМ (git clone https://github.com/KindDentist/RobotMotorsControl.git)
2. Создан файл в папке локального репозитория motors_control.py. В файл внесена строка "There will be a script here! Someday."
3. Файл добавлен в локальный репозиторий, использованы команды git add, git commit. Произведена выгрузка данных на удаленный репозиторий (git push origin main).
   3.1. Создан токен для авторизации при работе с удаленным репозиторием.
4. Создана новая ветка improvements (git branch improvement; git checkout improvement)
5. В новой ветке в файл motors_control.py добавлена строка "We are one step closer to the goal!"
6. Внесенные изменения сохранены в репозиторий (git add, git commit). Добавлено описание действий в README.md
7. Произведено слияние веток main и improvements. (Произведен переход в ветку main, осуществлено слияние с помощью команды git merge improvements).
8. Все было хорошо.
9. Завершено слияние, результат выгружен на удаленный сервер git push origin main.
10. Закончено оформление краткого отчета.

Цели проекта: сбор информации об оборудовании, схемах монтажа, разработка программной части управления моторми.
Описание структуры проекта RobotMotorsControl могу дать лишь исходя из опыта работы с Arduino. 
Предположительно, материалы можно будет разделить на две части - информацию об оборудовании и скрипты. В материалах проекта об оборудовании должны быть информация о моторах - картинки, схемы распиновки, чертежи моторов для 3D-моделирования. Описание контроллеров, схемы распиновки контроллеров, чертежи для построения 3D-моделей. В случае необходимости, даташиты контроллеров. Необходимы схемы подключения моторов к контроллерам, с описанием решения возможных проблем, связанных с полярностью подключения, например. 
В разделе со скриптами - вся программная часть. Кроме самих скриптов, стоит сохранить информацию о физико-математических моделях, описывающих процессы поворотов, движения дронов, чтобы потом каждый раз заново не "придумывать" формулы.
