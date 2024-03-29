# Изучение git. Шпаргалка команд


1. ```git init``` - создает новый git репозиторий в локальной папке.

2. ```git status``` - показывает состояния файлов в рабочей директории какие файлы изменены, но не добавлены отслеживаются, какие ожидают коммита. 

3. ```git add 'filename_or_mask.ext'``` - добавляет содержимое директории или файла в отслеживание для последующего коммита. 

4. ```git commit -m "summary"``` - фиксирует изменения с указанным текстом.
Могут быть использованы как "Контрольные точки" проекта, к которым можно в любой момент вернуться.

5. ```git push``` - вносит изменения в удаленный репозиторий

6.  ```git pull``` - получает изменения с удаленного репозитория
Может быть использовано для получения измений, внесенных в код программы другими программистами

7.  ```git diff HEAD ``` - используется для вычисления разницы между любыми двумя коммитами. С тэгом HEAD изменения в проекте сравниваются с последним коммитом

8.  ```git checkout filename.ext``` - отменяет изменения в выбранном файле в соответсвии с предыдущим коммитом.
Может быть использована когда уже после публикации была обнаружена критическая ошибка в конкретном файле или репозитории, влияющая на работу программы и необходимо откатить изменния.

9.  ```git branch -a``` - показывает то, в какой ветке мы находимся, показывает все ветки если ввести ключ "-a"

10. ```git branch newbranch``` - создает новую ветку с названием "newbranch".
Может быть использована, например, когда ведется разработка уникальной фичи, но она не должна нарушить работспособность существуещего приложения.

11.  ```git clone https://github.com/link_to_repo``` - скачивает удаленный репозиторий github в папку.
Может быть использована при начале работы с уже существующим проектом.

12.  ```git remote origin https://github.com/link_to_repo``` - привязывает удаленный репозиторий к папке.
Может быть использована когда проект готов для публикации на локальной машине и необходимо им поделиться

13.  ```git revert commit-tag``` - откатить существующий под именем "commit-tag" коммит.
Может быть использована когда уже после публикации была обнаружена критическая ошибка, влияющая на работу программы и необходимо откатить изменния.

14.  ```git merge new-feature``` - слияние веток, разрешение возможных конфликтов. Команда объединяет текующую ветку и ветку new-feature.

15.  ```git log``` - используется для получения информацию об истории коммитов за определенный отрезок времени.



