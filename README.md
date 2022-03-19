# CI4 - Ecommerce

## Installation instructions

```
git clone https://github.com/narayangit/ci4_estore
cd ci4_estore
composer install
cp env .env
(Manualy create a database)
(Manualy edit .env)
php spark migrate -n IonAuth
php spark migrate
Windows: php spark db:seed IonAuth\Database\Seeds\IonAuthSeeder
Linux: php spark db:seed IonAuth\\Database\\Seeds\\IonAuthSeeder
```

## User login
```
admin@admin.com
password
```
