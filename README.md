# get started

1. Clonar o repositório do git
2. Abra o terminal na pasta do projeto
2. rode o comando: `composer install`
3. copie o .env.example e renomei-o para .env


## comandos de migration

### Criar migration 
`php artisan make:migration nome_da_migration`

### Criar migration  de create (Sem usar a nomeclatura)
`php artisan make:migration nome_da_migration` --create=NOME_DA_TABELA

### Criar migration de alter
`php artisan make:migration nome_da_migration --alter=NOME_DA_TABELA`

### Executar migrations
`php artisan migrate`

### Desfazer migrations
`php artisan migrate:rollback`

### Dropar o banco e executar as migrations novamente
`php artisan migrate:frush`
