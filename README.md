# Hasks Ai hackathon solution
# Team WhileTrue

Инструкция по развёртыванью и запуску решения

1. установить docker и docker-compose
2. выполнить в папке с решением:
   docker-compose build
   docker-compose up -d
3. открыть в браузере http://localhost:8000/charity/  (форма для отправки запроса, загрузка ответа до 5 мин.)
   также доступно API: 
   получение JSON GET-запросом вида: http://localhost:8000/charity/?orgname=НазваниеоОрганизации&inn=ИНН

   
