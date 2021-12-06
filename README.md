# Validator
### Простой валидатор PHP 
Передавайте нужные Вам данные в нужные методы, валидатор всё сделает за Вас
```php
$email = Validator::validateString($_POST['email']);
$password = Validator::validatePassword($_POST['password']);
```