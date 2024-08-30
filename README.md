#### Desenvolver o restante do CRUD para projetos e testá-lo utilizando o Insomnia.

Exo API 

GET - listar projetos
http://localhost:5038/api/projetos/
 

POST - cadastrar projeto
https://localhost:5038/api/projetos/

```JSON
{
"nomeDoProjeto": "Projeto D - Senai FIT",
"area": "Saúde",
"status": true
}
```


GET - listar projeto por ID
https://localhost:5038/api/projetos/4


PUT - atualizar projeto por ID
https://localhost:5038/api/projetos/4

```JSON
{
"nomeDoProjeto": "Projeto D - Senai Games",
"area": "Entretenimento",
"status": false
}
```

DELETE - deletar projeto por ID
https://localhost:5038/api/projetos/4

GET - listar projetos
https://localhost:5038/api/projetos
 

POST - cadastrar projeto
https://localhost:5038/api/projetos/

```JSON
{
"nomeDoProjeto": "Projeto D - Senai FIT",
"area": "Saúde",
"status": true
}
```


#####CRUD USUARIOS

GET - listar usuarios
https://localhost:5038/api/usuarios/


POST - cadastrar usuarios
https://localhost:5038/api/usuarios/

```JSON
{
"email": "email_tres@sp.br",
"senha": "1234"
}
```
![Insomnia](https://github.com/diegobrl/insomniacrud-api/blob/main/Screenshot/foto002.png)

