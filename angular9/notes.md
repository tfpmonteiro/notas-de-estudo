# Angular 9

Maior nível de encapsulamento, uma vez que o framework é voltado para a criação de módulos e componentes.</li>

## Component

Trata-se de uma estrutura composta, na maioria da vezes por três arquivos:

* HTML
* CSS
* TS

 A criação do componente implica na criação de uma tag especial, que será utilizada sempre para referenciar o mesmo:
**< app-nome-componente >< /app-nome-componente >**
  
![](https://uploaddeimagens.com.br/images/002/668/165/original/component.png?1590278530)

## Módulos

* Declarations: todos os componentes, diretivas e pipes que compõem o módulo.
* Exports: referencia os componentes, diretivas e pipes que poderão ser exportados.
* Imports: referencia os módulos que estão sendo importados para utilização no módulo em questão.
* Providers: referencia os services que serão utilziados no módulo.
* Bootstrap: define o componente que será carregado no módulo (seu uso é necessário apenas no módulo inicial da aplicação).

### Tipos de diretivas

* **Diretivas de atributo:** Altera a aparência e o comportamento de um elemento, componente ou outra diretiva.
* **Diretivas estruturais:** Altera o layout adicionando e removendo elementos do DOM.

### Decorator

É um padrão de projeto que tem como objetivo evitar o uso de herança, trabalhando com composição.

### Observables

* Orientado a evento;
* Reusável;
* Trabalha com uma stream de dados;
* Permite uma gama maior de uso de operadores;

### Services

São classes que têm como principal objetivo **organizar** e **compartilhar** métodos e dados entre componentes.
