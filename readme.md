#  Инстукция

##  Создание SSH-ключей:
1. Откройте терминал (или Git Bash, если вы используете Windows).
2. Введите команду: ssh-keygen -t rsa -b 4096 -C "ваш_email@example.com".
3. Будет предложено указать путь для сохранения ключей. По умолчанию это ~/.ssh/id_rsa для приватного ключа и ~/.ssh/id_rsa.pub для публичного.
4. Если вы хотите использовать другое имя, укажите путь и имя файла (например, ~/.ssh/github_rsa).
Программа также спросит вас о пароле-фразе. Это дополнительный уровень защиты для вашего ключа.

## Добавление публичного ключа на GitHub:
1. Откройте файл ~/.ssh/id_rsa.pub (или файл, который вы указали при создании ключей).
2. Скопируйте содержимое этого файла.
3. Войдите в свой аккаунт на GitHub.
4. Перейдите в настройки аккаунта, затем в раздел "SSH and GPG keys".
5. Нажмите "New SSH key" и вставьте скопированный ключ.
6. Дайте ключу понятное имя (например, "Мой ключ для GitHub").