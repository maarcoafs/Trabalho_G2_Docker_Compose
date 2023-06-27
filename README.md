#Começando com docker-compose, usando python/flask e redis

Compose é uma ferramenta para definir e executar aplicações Docker de vários contêineres. Você usa um arquivo Compose para configurar os serviços da sua aplicação. Em seguida, usando um único comando, você cria e inicia todos os serviços.

Neste repositório, há um aplicativo web básico em python flask no arquivo app.py, um Dockerfile para as especificações do contêiner para esse aplicativo (que é baseado em uma imagem python), um arquivo de requisitos para a instalação de requisitos adicionais do Docker para o aplicativo (flask, redis) e um arquivo docker-compose para a especificação dos contêineres compostos, que inclui os contêineres flask e redis.
