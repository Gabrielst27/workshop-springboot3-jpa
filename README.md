# Web Service com Spring Boot e JPA/Hibernate
https://github.com/Gabrielst27/workshop-springboot3-jpa/blob/main/LICENSE

# Sobre o projeto
Esta é uma aplicação backend web, desenvolvida em linguagem Java utilizando a ferramenta Spring Boot, além da API JPA e o mapeamento objeto-relacional Hibernate.

A aplicação consiste em um banco de dados web que relaciona pedidos de compra com clientes, produtos, categorias de produtos e usuários, sendo que o pedido pode ou não ter pagamento. Além disso, é possível definir o pedido como PAGAMENTO PENDENTE, PAGO, ENVIADO, ENTREGUE e CANCELADO.

# Modelo e instanciação de Domínio
![Modelo de Domínio](https://github.com/Gabrielst27/workshop-springboot3-jpa/blob/main/Modelo%20de%20Dom%C3%ADnio.png)

![Instanciação de Domínio](https://github.com/Gabrielst27/workshop-springboot3-jpa/blob/main/Instancia%C3%A7%C3%A3o%20de%20dom%C3%ADnio.png)


# Layout
![Layout](https://github.com/Gabrielst27/workshop-springboot3-jpa/blob/main/Layout.png)

# Testando a aplicação
## Recursos necessários
Spring Tool Suite 4; JDK 17 (LTS); Git Bash

## Clonando o projeto
Abra o terminal Git Bash na pasta em que deseja clonar o projeto e digite o seguinte comando: git clone git@github.com:Gabrielst27/workshop-springboot3-jpa.git

## Subindo a aplicação
Após iniciar o Spring Tool Suíte e abrir a pasta do projeto que foi clonada, clique no seguinte botão:
![Subindo a aplicação](https://github.com/Gabrielst27/workshop-springboot3-jpa/blob/main/Subindo%20a%20aplica%C3%A7%C3%A3o.png)

## Localizando a porta
Feito isso, a aplicação começará a ser preparada para subir ao servidor da máquina, e uma seta verde apontando para cima irá aparecer abaixo de "local". Ao lado da seta estará o nome da workshop na qual o projeto está contido ("course"), e ao lado, estará a porta na qual a aplicação está localizada. Também é possível descobrir a porta abrindo a janela de console e procurando o retorno "Tomcat started on port...", como mostra a imagem abaixo:
![Localizando a porta](https://github.com/Gabrielst27/workshop-springboot3-jpa/blob/main/Localizando%20a%20porta.png)

## Pesquisando o caminho da aplicação
Após descobrir a porta na qual a aplicação está localizada, basta pesquisar o caminho na seguinte formatação: localhost:porta/h2-console
![Pesquisando o caminho](https://github.com/Gabrielst27/workshop-springboot3-jpa/blob/main/Pesquisando%20o%20caminho.png)

## Se conectando ao H2-Console
Após pesquisar o caminho no navegador, será aberta a página do console H2. Preencha o formulário exatamente como mostra a imagem a seguir, e depois clique em "Connect".
![Conectando](https://github.com/Gabrielst27/workshop-springboot3-jpa/blob/main/Conectando.png)
Lembrando que as informações de preenchimento do formulário acima podem ser encontradas em src/main/resources/application.properties. Feito isso, você já terá acesso ao banco de dados, onde terão alguns dados exemplo pré-definidos
