# estudando-react
Repositório de anotações dos estudos de React para Web, inicialmente com o Bootcamp da DIO.me, porém aberto a futuro estudos.



## Sobre funções
---
### Existem funções anônimas e autoinvocada
Essas funções geralmente são usadas para isolar o que seria um Main() do arquivo .js. Exemplo:
```javascript
(function(){
    console.log("Olar!");
})();
```