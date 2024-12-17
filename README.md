#Лабораторная работа 5
##Задание 1
В папке .git/hooks создал файл pre-commit и вписал туда bash-скрипт, проверяющий корректность типа файла, наличие в нем текста:

![image](https://github.com/user-attachments/assets/79100ce8-268e-41a9-93e3-47e60a10ac9c)

Попытка закомитить пустой файл неверного формата, пустой файл, непустой файл верного формата:

![image](https://github.com/user-attachments/assets/aeaeca22-9911-4db9-8dc1-aa15f7b4cbd2)

##Задание 2
Инициализировал git flow в папке репозитория

![image](https://github.com/user-attachments/assets/81a07de6-8712-4114-bdd9-230633f92eea)

Cоздал ветку feature - task_management, закоммитил в ней новый файл

![image](https://github.com/user-attachments/assets/be817c1f-0fbe-4636-8d0f-8bcc16058172)

Закрыл ветку

![image](https://github.com/user-attachments/assets/b354155d-2abd-4a27-860d-6072b5bf3715)

Создал ветку release - version1.0.0, создал и добавил файл с текущей версией, закоммитил его и закрыл ветку

Создал ветку hotfix1.0.1, внес исправления в файл и добавил его, закоммитил изменения и закрыл ветку.
Указал тег и сообщение коммита в открывшемся внутри терминала Vim.

![image](https://github.com/user-attachments/assets/5d675f08-8145-4721-8e76-0afb9b2eba11)

Слил ветку develop c main, отправил изменения в github-репозиторий

![image](https://github.com/user-attachments/assets/13099e92-92e1-435f-a07a-182dde3965d7)
