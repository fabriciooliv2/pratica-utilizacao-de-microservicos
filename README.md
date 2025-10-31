Prática: Utilização de Microsserviços com Docker
Este projeto tem como objetivo demonstrar, de forma prática, a utilização de microsserviços em um ambiente Dockerizado, utilizando tecnologias como PHP, Nginx e MySQL.
📦 Estrutura do Projeto
O repositório contém os seguintes arquivos principais:

index.php: Interface web simples para interação com o microsserviço.
nginx.conf: Arquivo de configuração do servidor Nginx.
dockerfile: Define a imagem Docker personalizada para o serviço PHP.
banco.sql: Script de criação da tabela dados no banco de dados MySQL.
Utilização Prática no Cenário de Microsserviços.txt: Documento explicativo sobre o projeto.

🚀 Tecnologias Utilizadas

Docker: Para criação e gerenciamento dos containers.
PHP: Linguagem utilizada no serviço web.
Nginx: Servidor web para servir o conteúdo PHP.
MySQL: Banco de dados relacional para persistência de dados.

🛠️ Como Executar o Projeto


Clone o repositório:
Shellgit clone https://github.com/fabriciooliv2/pratica-utilizacao-de-microservicos.gitcd pratica-utilizacao-de-microservicosMostrar mais linhas


Configure os containers com Docker Compose (se disponível) ou manualmente:

Crie os containers para o PHP, Nginx e MySQL.
Certifique-se de que o nginx.conf está corretamente apontando para o serviço PHP.
Execute o script banco.sql no MySQL para criar a tabela necessária.



Acesse o serviço via navegador:

O serviço estará disponível em http://localhost (ou conforme configurado no Docker).



📚 Objetivo Educacional
Este projeto foi desenvolvido como parte de uma prática de aprendizado sobre arquitetura de microsserviços, visando:

Compreender a separação de responsabilidades entre serviços.
Aprender a configurar múltiplos containers com Docker.
Integrar serviços web com banco de dados em ambientes isolados.

📄 Licença
Este projeto é apenas para fins educacionais e não possui uma licença específica.
