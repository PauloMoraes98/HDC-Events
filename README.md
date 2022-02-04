# Como configurar e executar.

1º Passo: Configurar no .ENV (Ex.: .env.example) as informações do banco de dados, sendo elas:
(DB_CONNECTION=mysql; DB_HOST=127.0.0.1; DB_PORT=3306; DB_DATABASE=hdcevents; DB_USERNAME=root; DB_PASSWORD=).
------------------------------------------------------------------------------------------------------------
2º Passo: Executar as migrations no CMD atravé do seguinte comando: php artisan migrate.
------------------------------------------------------------------------------------------------------------
3º Passo: Executar a aplicação no CMD através do comando: php artisan serve.
------------------------------------------------------------------------------------------------------------
4º Passo: Abrir no navegador o HTTP://XXX.X.X.X:XXXX disponibilizado através do passo anterior. 
