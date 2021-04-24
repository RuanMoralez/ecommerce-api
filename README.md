How to configuration new user for laravel project:

Define criptography for password:

    ALTER USER 'nome_do_usuario'@"localhost" IDENTIFIED WITH mysql_native_password BY '123' 


Grant full privilegies to user:

    GRANT ALL PRIVILEGES ON nome_do_banco.* TO 'nome_do_usuario'@'localhost' 

<br>

<H2> Routes USER: </H2>
 
GET Users: 

    http://127.0.0.1:8000/api/auth/users
    
POST Login:

    http://127.0.0.1:8000/api/auth/login
    
POST Register:
    
    http://127.0.0.1:8000/api/auth/register

<br>

<H2> Routes PRODUCT: </H2>

GET Products:

    http://127.0.0.1:8000/api/auth/products
    
POST Register:
    
    http://127.0.0.1:8000/api/auth/products/register
