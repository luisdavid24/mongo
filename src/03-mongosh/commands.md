##Connect to container

```sh
docker-compose exec mongodb bash
```

##Conect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://luislm2412:<db_password>@cluster0.dqn50.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_store");
db.productos.find();

```
