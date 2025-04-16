# sq-ch12-ex1

Используя СУБД H2 и PostgreSQL в пямяти, создаем REST точку для записи и чтения в БД

curl -X POST 'http://localhost:8080/purchase' \
-H 'Content-Type: application/json' \
-d '{
"product" : "Spring Security in Action",
"price" : 25.2
}'


curl 'http://localhost:8080/purchase'

curl -X POST 'http://localhost:8080/purchase' \
-H 'Content-Type: application/json' \
-d '{
"product" : "My Book Name",
"price" : 5.23
}'
