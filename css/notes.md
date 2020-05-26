# CSS

* **rem -** unidade de medida que referencia as configurações do browser. Ou seja, uma fonte de 3rem é uma fonte com o tamanho 3 vezes maior do que a fonte definida no browser do usuário. Caso, as configurações do browser seja igual a 14px (que é o padrão), uma fonte 3rem equivale a 42px.
* **em -** unidade de medida que referencia as configurações do elemento anterior. Ou seja, se a estrutura do HTML seguir a estrutura abaixo:

```html
<div>
<p>Olá mundo!<p>
<span>Seja bem vindo<span>
</div
```

```CSS
div p {
font-size: 2rem;
}

div span {
font-size: 1.5em;
}
```

Neste exemplo, considerando o tamanho da fonte definida no navegador como 14px, o texto "Olá mundo!" terá uma fonte no tamanho de 28px, enquanto o texto "Seja bem vindo" aparecerá com o tamanho de 1.5 rem, ou seja 21px.