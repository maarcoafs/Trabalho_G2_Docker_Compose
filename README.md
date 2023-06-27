# Trabalho G2 Docker Compose
## Flask e Redis

## Aluno: Marco Antonio Flores da Silva
## RA: 1132018

Compose é uma ferramenta para definir e executar aplicações Docker de vários contêineres. Você usa um arquivo Compose para configurar os serviços da sua aplicação. Em seguida, usando um único comando, você cria e inicia todos os serviços.

Neste repositório, há um aplicativo web básico em python flask no arquivo app.py, um Dockerfile para as especificações do contêiner para esse aplicativo (que é baseado em uma imagem python), um arquivo de requisitos para a instalação de requisitos adicionais do Docker para o aplicativo (flask, redis) e um arquivo docker-compose para a especificação dos contêineres compostos, que inclui os contêineres flask e redis.

1 - Crie os arquivos localmente.

2 - Execute docker-compose build para construir os contêineres especificados no arquivo docker-compose.

3 - Execute docker-compose up para iniciar os contêineres (adicione -d para executá-los em segundo plano. Em seguida, execute docker-compose stop quando terminar.)

4 - Acesse http://localhost:5000 para ver a resposta do aplicativo web.
