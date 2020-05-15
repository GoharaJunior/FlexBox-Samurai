# 6 • align-self

O align-self serve para definirmos o alinhamento específico de um único flex item dentro do nosso container.<br>
Caso um valor seja atribuído, ele passara por cima do que for atribuído no align-items do container.

Vale lembrar que o alinhamento acontece tanto em linha quanto em colunas. Por exemplo o flex-start quando<br>
os itens estão em linhas, alinha o item ao topo da sua linha. Quando em colunas, alinha o item ao início<br>
(esquerda) da coluna.

```php
align-self: auto;
// Valor inicial padrão. Vai respeitar o que for definido pelo align-items no flex-container.
align-self: flex-start;
// Alinha o item ao início.
align-self: flex-end;
// Alinha o item ao final.
align-self: center;
// Alinha o item ao centro.
align-self: baseline;
// Alinha o item a linha de base.
align-self: stretch;
// Estica o item.
```

<img width="700px" src="https://user-images.githubusercontent.com/57417305/82095945-7945b280-96d6-11ea-91ac-9c51e10a249f.png" />

## Veja também em:
<img width="200px" src="https://user-images.githubusercontent.com/57417305/80937857-23573d80-8dad-11ea-8473-123454e87187.png"/>

[• LINK AQUI](https://codepen.io/Gohara/pen/RwWeNeL)

