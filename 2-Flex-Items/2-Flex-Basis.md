#  2 • flex-basis

Indica o tamanho inicial do flex item antes da distribuição do espaço restante.

Quando definimos o flex-grow: 1; e possuímos auto no basis, o valor restante</br>
para ocupar o container é distribuído ao redor do conteúdo ao flex-item.

```js 
flex-basis: auto;
// Esse é o padrão, ele faz com que a largura da base seja igual a do item. Se o item não tiver tamanho especificado, o tamanho será de acordo com o conteúdo.
flex-basis: unidade;
// Pode ser em %, em, px e etc.
flex-basis: 0;
// Se o grow for igual ou maior que 1, ele irá tentar manter todos os elementos com a mesma largura, independente do conteúdo (por isso 0 é o valor mais comum do flex-basis). Caso contrário o item terá a largura do seu conteúdo.
```

<img width="700px" src="https://user-images.githubusercontent.com/57417305/81511105-432abc00-92ed-11ea-950d-53477320304d.png" />

## Veja também em:
<img width="200px" src="https://user-images.githubusercontent.com/57417305/80937857-23573d80-8dad-11ea-8473-123454e87187.png"/>

[• LINK AQUI](https://codepen.io/Gohara/pen/LYpmXXx)
