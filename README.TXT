
1. Установить docker и docker-compose
2. Склонировать этот проект в любуя папку
3. Перейти в папку EFKO-docker-test "cd EFKO-docker-test"
4. Склонировать базовый проект yii2 "git clone https://github.com/yiisoft/yii2-app-basic.git"
5. Выполнить "sudo docker-compose up --build"
6. Иногда дополнительно нужно дать права на папку yii2-app-basic после установки зависимостей "sudo chmod -R 777 *"

Если необходимо создать базу yii2basic с помощью adminer "http://127.0.0.1:6080" или скопировать базу в папку "databases"
После запуска docker-compose проект будет доступен по адресу "http://127.0.0.1:8080"

Также можно запустить тестовый проект "Отпуск" , для этого на 4м шаге нужно вместо базового проекта yii2
склонировать https://github.com/nnuser/EFKO-Yii2-test.git и в файле .env раскомментировать строку "#APP_PATH_HOST=./EFKO-Yii2-test" и
закомментировать "APP_PATH_HOST=./yii2-app-basic"

Примечания!
Первый раз composer долго загружает зависимости.
На Windows возможно нужна будет дополнительная настройка.

