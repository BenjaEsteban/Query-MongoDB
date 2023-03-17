## Conect to container

´´´ sh
docker-compose exec mongodb bash
´´´

## Conect with mongosh

´´´sh
mongosh "--link de conección--"
´´´

´´´sh
show dbs
show collections
´´´

## Con use nos conectamos a una base de datos 
## Con find() obtenemos los documentos de las colecciones 
´´´sh
use("")
db.products.find()  
´´´