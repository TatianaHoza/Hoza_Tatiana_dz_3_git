***This is first commit***
commit from github!
# Инструкция по работе с GIT

__GIT-система контроля версий__

*Для чего?*

* Возможность хранить различные версии проекта

* Возможность возвращаться к сохраненным версиям проекта

__Основные команды__

* _git --version_ - посмотреть наличие и версию GIT
* _git init_ - инициализация (запуск в папке)
* _git status_ - просмотр файлов в папке
* _git add fail_name_ - добавить файл
* _git add ._ - сохранение актуальных изменений
* _git commit -m 'комментарий к изменению'_ - комментарий к изменению состояния
* _git log_ - журнал изменений
* _git chekout №_коммита_(название ветки) - возврат на актуальное состояние, переход на определенную ветку
* _git diff_ - разница между текущим состоянием файла и тем, которое сохранено
* _git clone_ - клонирование репозитория на ПК
* _git branch_ - просмотр доступных веток
* _git branch название_новой_ветки_ - создание новой ветки
* _git branch -d_ - удаление ветки
* _git marge_ - слияние веток

# Задание ко 2 семинару

Создали ветку *second* с помощью команды **git branch**

Создали ветку *third* с помощью команды **git branch**

Создали ветку *conflict* с помощью команды **git branch**

# Задание к 3 семинару

* _git pull_ - скачать все из текущего репозитория и автоматически сделать merge с нашей версией
* _git push_ - команда позволяет отправить нашу версию репозитория на внешний репозиторий

__Как сделать pull request__

* Делаем __fork__ репозитория
* Делаем __clone__ своей версии репозитория
* Создаем новую ветку и в неё вносим изменения
* Фиксируем изменения(делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку _pull request_