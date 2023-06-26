# Trabalho G2 Docker Compose

Aluno: Marco Antonio Flores da Silva
RA: 1132018

# ScadaBR e MariaDB

O objetivo deste trabalho é implantar o sistema supervisório ScadaBR e o banco de dados MariaDB através do Docker Compose.

Ao executar o comando docker-compose up, o Docker Compose baixará as imagens necessárias (se ainda não estiverem presentes no sistema) e iniciará os contêineres de acordo com as configurações definidas no arquivo YAML.

O serviço "scadabr" utiliza a imagem "carloskze/scadabr:latest" e tem várias variáveis de ambiente definidas, incluindo informações de conexão com o banco de dados MariaDB (host, porta, nome do banco de dados, usuário e senha) e as credenciais de administrador do ScadaBR.

O serviço "mariadb" utiliza a imagem oficial do MariaDB e também possui variáveis de ambiente configuradas, como a senha do usuário root, o nome do banco de dados, o usuário e a senha do banco de dados do ScadaBR.
