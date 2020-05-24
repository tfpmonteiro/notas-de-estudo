<h2>Angular 9</h2>
Maior nível de encapsulamento, uma vez que o framework é voltado para a criação de módulos e componentes.</li>


<h4>Component</h4>
Trata-se de uma estrutura composta, na maioria da vezes por três arquivos:
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>TS</li>
</ul>
 
 A criação do componente implica na criação de uma tag especial, que será utilizada sempre para referenciar o mesmo:<br>
 <strong> < app-nome-componente >< /app-nome-componente > </strong>
  
<img src="https://uploaddeimagens.com.br/images/002/668/165/original/component.png?1590278530">

<h4>Módulos</h4>
<ul>
  <li>Declarations: todos os componentes, diretivas e pipes que compõem o módulo.</li>
  <li>Exports: referencia os componentes, diretivas e pipes que poderão ser exportados.</li>
  <li>Imports: referencia os módulos que estão sendo importados para utilização no módulo em questão.</li>
  <li>Providers: referencia os services que serão utilziados no módulo.</li>
  <li>Bootstrap: define o componente que será carregado no módulo (seu uso é necessário apenas no módulo inicial da aplicação).</li>
</ul>
