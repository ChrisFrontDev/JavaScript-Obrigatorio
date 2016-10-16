# Hora da Iteração!

Uma das coisas que um desenvolvedor mais utiliza diariamente é a **iteração** em Arrays.

![](http://2.bp.blogspot.com/-qCGrD75WMDk/VNjgHBQ_YDI/AAAAAAAACoA/qzwZ1Fa690c/s1600/png_hora_de_aventura_echo_por_micatinistaa_by_micatinistaa-d6led9j.png)

Primeiramente quero perguntar para você:

> Quais sao as funções que o JavaScript nos provê para isso?


**Vamos iniciar pelo mundialmente reconhecido...** 

![](http://imguol.com/c/noticias/2014/09/30/comediante-e-deputado-federal-tiririca-pr-sp-1412101756570_956x500.jpg)

## for

```js
var arr = [1, 2, 3];
.map():

arr.map(function(i) {
  console.log(i);
});
// 43 characters

.forEach():

arr.forEach(function(i) {
  console.log(i);
});
// 47 characters

for():

for (var i = 0, arr.length; i < l; i++) {
  console.log(arr[i]);
}
// 70 characters
```

```js
var arr = [1, 3, 2];

console.log(
  // This one works:
  arr
  .map(function (i) {
    return i + i;
  })
  // Chaining!
  .sort()
);
// => [ 2, 4, 6 ]

console.log(
  // This one does not:
  arr
  .forEach(function (i) {
    return i + i;
  })
  // This is where forEach breaks:
  .sort()
);
// => TypeError: Cannot read property 'sort' of undefined
```
