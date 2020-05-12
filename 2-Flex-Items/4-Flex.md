# 4 • flex

Atalho para as propriedades **flex-grow**, **flex-shrink** e **flex-basis**. Geralmente você verá<br>a propriedade flex nos **flex-itens** ao invés de cada um dos valores separados.

Para melhor consistência entre os browsers, é recomendado utilizar a propriedade<br>flex ao invés de cada propriedade separada.

No exemplo é possível ver as mesmas configurações do exemplo do flex-basis<br>porém agora utilizando apenas a propriedade flex.

```php
flex: 1;
// Define flex-grow: 1; flex-shrink: 1; e flex-basis: 0; (em alguns browsers define como 0%, pois estes ignoram valores sem unidades, porém a função de 0 e 0% é a mesma.)
flex: 0 1 auto;
// Esse é o padrão, se você não definir nenhum valor de flex ou para as outras propriedades separadas, o normal será flex-grow: 0, flex-shrink: 1 e flex-basis: auto.
flex: 2;
// Define exatamente da mesma forma que o flex: 1; porém neste caso o flex-grow será de 2, o flex-shrink continuará 1 e o flex-basis 0.
flex: 3 2 300px;
// flex-grow: 3, flex-shrink: 2 e flex-basis: 300px;
```

<img width="700px" src="https://user-images.githubusercontent.com/57417305/81715180-4ab5a680-944e-11ea-9940-ffa55adf632b.png" />

## Veja também em:
<img width="200px" src="https://user-images.githubusercontent.com/57417305/80937857-23573d80-8dad-11ea-8473-123454e87187.png"/>

[• LINK AQUI](https://codepen.io/Gohara/pen/ZEbRddd)
