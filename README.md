# Git-Education
# **Мануал. Git для работы с документацией IT**   
## **Что такое Git**   
**Кратко**: Git - система контроля версий.   
**Развернуто**: Git - программа, используемая для контроля версий продуктов IT в процессе их написания и с выбором окончательной версии продукта.   
- Сегодня с помощью Git контролируется как программный код, так и IT-документация (на основе принципов Git возник принцип **docs-as-code**).   
- Git широко используется во всем мире как система контроля версий.             
## **Что обеспечивает Git**   
- Возможность версионирования IT-продукта во время его написания для эффективного устранения ошибок, выбора наилучшего варианта продукта из разных версий и других.
- Возможность коллективной работы над IT-продуктом: каждый разработчик в команде контролирует отдельную версию, затем одна из данных версий становится окончательной и идет в production.     
- Возможность смены версий при появлении ошибок или при анализе различных версий продукта     
## **Общие принципы работы с Git**   
`Далее используется общее слово **текст** для обозначения кода, текста, таблиц, иллюстраций и других компонентов IT-продукта.`  
- Версии редактируются и хранятся в репозиториях IT-продукта (на ПК это обычная папка для работы с Git, на сайте Git - создаваемый пользователем раздел). 
- Для работы с версиями используются **локальные и удаленные репозитории**, между которыми происходит обмен версиями: в локальном репозитории находятся *черновые* версии текста, в удаленный репозиторий выливается **основная версия**.  
- Для разграничения версий текста в Git создаются **ветки** разработки или **branches**. Одна версия текста равна одной ветке.   
- Фиксирование изменений в версии и отправка этих изменений в другую версию происходит в несколько команд. Команды выполняются в окне Terminal (консоль) 
- При возникновении "конфликтов" версий разработчики выполняют команды в консоли по автомтическому разрешению конфликтов, а также договариваются    
- **Программы Git**: Git GUI, Git Extension, Git, встроенный в программу разработки кода VS Code и другие.    
 
## **Понятия, используемые в GIT**
## **Начало. Установка и настройка GIT**   
## **Репозитории локальный и удаленный**
## **Первое заполнение информации**
## **Создать ветку в локальном репозитории**
## **Индексировать изменения**
## **Коммитить изменения**
## **Замержить изменения**
## **Решить возникшие конфликты**
## **Запушить из локального репозитория в удаленный**
  
git add .   
git clone   
git branch   
git checkout      
git add   
git commit   
git remote   
git push   
git pull   
git status   
git merge  
git init  


3 вариант
Установка   
Настройка   
Создание репозитория   
Рабочий процесс   
git add: добавление файлов в индекс   
git status: проверка статуса репозитория   
git commit: добавление файлов в репозиторий   
git log: просмотр журнала коммитов   
git show: просмотр коммита   
git diff: просмотр изменений до коммита   
git difftool: запуск внешнего инструмента сравнения файлов   
git restore: отмена изменений   
git rm: удаление файлов из индекса   
git reset: откат коммита   
   
git branch <branch_name>: создание новой ветки   
git branch: просмотр веток   
git checkout: переключение между ветками   
git merge: слияние репозиториев   
git branch -d <branch_name>: удаление ветки   
Удалённый репозиторий   
git remote add origin url: привязка локального и удалённого репозитория  
git remote: просмотр удалённых репозиториев   
git remote — v: просмотр удалённых URL-адресов   
git push: отправка изменений в удалённый репозиторий   
git pull: получение изменений из удалённого репозитория   
Практика по основным командам Git   
-a   
-m      
-u    

