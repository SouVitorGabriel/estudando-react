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

---

Colocarei o meu primeiro projeto local em algum lugar aqui e depois troco por um link

------------

## Sobre Componentes
---
### Funcionais vs classes

Funcionais são mais usados pois são mais legíveis e simples de escrever, 99% das coisas podem ser feitas usando componentes de função ao invés de classes.

### **Preciso estudar:**
 * Hooks;
 * Props sem usar a palavra props, como no exemcplo abaixo:

 ```javascript
(function Olar = ({quem}) => {
    console.log("Olar :" + {quem} `e Olar ${quem} de novo`);
})();
```

### **Preciso estudar #2:**
 * Desestruturação de propriedades;
 * *"Template string"* e coisas escritas entre crases
 * Pesquisar sobre CSS *$::after*