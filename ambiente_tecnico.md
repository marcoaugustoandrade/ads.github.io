# Tutorial acesso a VM estudantes

Para editar os arquivos no seu ambiente de desenvolvimento, siga as instruções abaixo:

## Acesso ao Ambiente de Desenvolvimento
1) Acesse o endereço `https://nome-sobrenome.tecnico.fslab.dev/code` para editar os arquivos de seu container.


## Deploy de Web Sites
Se deseja hospedar um site estático, saiba que o endereço `https://nome-sobrenome.tecnico.fslab.dev` redireciona para o servidor web Nginx que está instalado em seu ambiente. Para visualizar as alterações, siga os passos abaixo:

1) Edite os arquivos que estão localizados em `/home/nome-sobrenome/Desktop/public_html`.
2) Você também pode criar subpastas em `/home/nome-sobrenome/Desktop/public_html` para hospedar múltiplos sites estáticos.
3) Por exemplo, se você criar uma subpasta chamada `pizzaria` com um arquivo `index.html`, poderá acessá-la através de `https://nome-sobrenome.tecnico.fslab.dev/pizzaria`.


## Acesso ao Banco de Dados MySQL
Para acessar o painel de administração do MySQL e criar bancos de dados, siga as instruções abaixo:

1) Acesse o painel de administração do MySQL através do link `https://phpmyadmin.tecnico.fslab.dev`, utilizando suas credenciais `nome-sobrenome` e senha.
2) Você pode criar bancos de dados com o sufixo `nome-sobrenome_nome-da-database` e utilizar os diversos recursos disponíveis no MySQL, como tabelas, views, triggers, etc.
3) Para acessar o MySQL a partir do seu ambiente de desenvolvimento, utilize o seguinte comando no terminal: `mysql -u nome-sobrenome -h mysql -p`.
4) O host a ser utilizado em suas aplicações, como APIs REST, é `mysql:3306`.


## Deploy de APIs

Para publicar APIs, siga estas instruções:

1) Faça o deploy da sua API em uma porta, por exemplo, a porta `3020`.
2) Acesse a API pelo endereço `https://nome-sobrenome-PORTA.fslab.dev/`.

Por exemplo, se você publicar uma API na porta 3020, poderá acessá-la em `https://nome-sobrenome-3020.fslab.dev`.
