# conversao-temperatura

## Curso Iniciativa DevOps/ Aula 01 - Docker

Criar imagem do Dockerfile utilizando o comando:

```
docker build -t tayssaavila/conversao-temperatura:v1 .
```

E executar a imagem com o comando:
```
docker container run -d -p 8080:8080 tayssaavila/conversao-temperatura:v1
```

Após isso a aplicação estará disponível em `localhost:8080`


