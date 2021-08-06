# kuber-14.4

задача1

создаем сервис-аккаунт

kubectl create serviceaccount netology

получаем список сервис-аккаунтов

kubectl get serviceaccount

получаем информацию в формате ямал и джейсон

kubectl get serviceaccount netology -o yaml

kubectl get serviceaccount default -o json

выгружаем информацию в файл

kubectl get serviceaccounts -o json > serviceaccounts.json

kubectl get serviceaccount netology -o yaml > netology.yml

удаляем сервис-аккаунт

kubectl delete serviceaccount netology

загружаем сервис-аккаунт из файла

kubectl apply -f netology.yml

в файле 14413.jpg и 14417.jpg скрин запущеных обьектов

задача2

запустили образ федоры

посмотрели переменные среды

получили их значение

подключились по апи

в файле 14423.jp скрин запущеных команд



