
1. Установить docker и docker-compose
2. Склонировать этот проект в любуя папку
3. Перейти в папку EFKO-docker-test "cd EFKO-docker-test"
3. Склонировать базовый проект yii2 "git clone https://github.com/yiisoft/yii2-app-basic.git"
4. Выполнить "sudo docker-compose up --build"
6. Иногда дополнительно нужно дать права на папку yii2-app-basic после установки зависимостей "sudo chmod -R 777 *"

Примечания!
Первый раз composer долго загружает зависимости.
На Windows возможно нужна будет дополнительная настройка.

Если необходимо скопировать базу в "databases" или просто создать базу yii2basic с помощью adminer "http://127.0.0.1:6080"
Проект будет доступен по адресу "http://127.0.0.1:8080"