# App MariaDB

Esse repositório tem o arquivo yaml necessários para a criação de um container docker com o banco de dados [MariaDB](https://mariadb.org/) e o gerenciador de bancos de dados [PhpMyAdmin](https://www.phpmyadmin.net/), que pode ser utilizado para rodar a aplicação fixada no [meu perfil do gitHUB](https://github.com/AlexsanderCDambros)

- [Frontend - Angular](https://github.com/AlexsanderCDambros/app)
- [Backend - Java Spring](https://github.com/AlexsanderCDambros/appbackend)

## Como utilizar

1. Instalar o Docker no seu computador, [link para o site oficial](https://www.docker.com/)
2. Faça o download desse repositório para o seu computador com o comando: ```git clone https://github.com/AlexsanderCDambros/appmariadb.git```
3. Abra um terminal ou prompt de comando e navegue até o diretório onde clonou o repositório e o arquivo docker-compose.yml está.
4. Execute o seguinte comando para iniciar o servidor MariaDB: ```docker-compose up -d```

Se tudo correr bem, basta acessar em um navegador o link [http://localhost:8080/index.php?](http://localhost:8080/index.php?), que você terá acesso ao PhpMyAdmin e poderá manipular o MariaDB.

## Observações

- O MariaDB irá rodar na porta 3306 e o PhpMyAdmin na porta 8080, caso haja alguma outra aplicação rodando nessas portas, você pode alterar de forma simples no arquivo docker-compose.yml

- Também é possível alterar senhas e usuários através do arquivo docker-compose.yml
  