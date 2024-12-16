PROJETO BANCO DE DADOS
Clone o repositório
Faça o clone do repositório para sua máquina local usando o comando git clone <URL_DO_REPOSITÓRIO>.

Configurar e instalar dependências no back-end

Acesse a pasta do back-end.
Execute o comando mvn install na pasta banco para instalar todas as dependências necessárias.
Configurar o arquivo de propriedades do back-end

Navegue até o arquivo src/resources/application.properties.
Atualize os valores de url, username e password para corresponderem ao banco de dados PostgreSQL que você configurou.
Atualizar a configuração de origem permitida (CORS)

No arquivo src/java/apresentacao/WebConfig.java, localize a configuração allowedOrigin.
Altere o valor para corresponder à porta onde seu front-end será executado.
Instalar dependências do front-end

Navegue até a pasta front-end.
Execute o comando yarn install ou npm install, dependendo da sua preferência ou ferramenta configurada.
Executar o front-end

Abra o arquivo HTML principal do projeto no diretório do front-end.
Utilize a extensão Live Server do VSCode para iniciar o front-end no navegador.
Executar o back-end

Localize o arquivo src/apresentacao/AcessoADado.java.
Execute-o diretamente no VSCode utilizando a opção Run Java.
