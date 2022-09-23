# lamp-environment
Ambiente com configuração do LAMP, para estudos em PHP.

- Clone o repositório PHP learn dentro do diretório www para rodá - lo.

## para inicializar o container:
```
sudo docker-compose up -d
```
- O phpMyAdmin se localizará em: [http://localhost:8000](http://localhost:8000)
- Você pode acessar os arquivos wem através de: [http://localhost:8001](http://localhost:8001)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 
