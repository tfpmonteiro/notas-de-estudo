<h2>Criando uma fake REST API através do json server</h2>
Rodar o beckend em um json-server é vantajoso quando precisamos de uma api para testar as implementações no frontend de forma rápida. 
<em>Por exemplo:</em> na realização de cursos rápidos ou para implementar e testar telas avulsas (login).

Para inicialiar o projeto com json-server, precisamos primeiro inicializar o npm no projeto. Para isso, basta rodar o comando
<h4>npm init -y</h4>
<em>o comando -y irá aceitar todas as sugestões padrão de instalação (next, next, next...)</em>

Ao final do comando, será adicionado o arquivo package-lock.json na pasta onde o comando foi criado. Em seguida, precisamos instalar o json server com o comando
<h4>npm i json-server</h4>

Com o json-server instalado, podemos criar um arquivo .json em qualquer lugar do projeto (preferencialmente em uma pasta separada, ou na raíz do projeto).
Precisamos também inicializar esse json, como no exemplo:

{
  "products": [
    {
      "id": 1,
      "name": "SSD Kingston",
      "price": 249.5
    }
  ]
}

Para iniciar o json server, basta adicionar o script abaixo no arquivo package.json
<h4>"start": "json-server --watch <em>< nome do arquivo json ></em> --port 3001></h4>
com isso, ao rodar o comando <h4> npm start </h4>no terminal de comando, ao iniciar a aplicação o npm irá iniciar o json server na porta 3001, sempre observando as alterações no arquivo criado para armazenar os dados da aplciação
