# Javascript_Type_Casting

<br/>

Type Casting, em JavaScript, é a conversão de um tipo de dado para outro. Isso pode ser necessário em diversas situações, como quando se deseja realizar uma operação entre variáveis de tipos diferentes, ou quando se precisa garantir que um valor é de um tipo específico.

Existem duas formas de Type Casting em JavaScript: o Type Coercion, que é uma conversão implícita de tipos feita pelo próprio JavaScript, e o Type Conversion, que é uma conversão explícita de tipos realizada pelo programador.

<br/>

> **Type Coercion**:

<br/>

O Type Coercion ocorre quando o JavaScript tenta realizar uma operação envolvendo variáveis de tipos diferentes, e automaticamente converte um ou mais valores para um tipo compatível com a operação. Por exemplo:

<br/>

```
const a = 5;
const b = "10";
const c = a + b;

console.log(c); // imprime "510"
```

<br/>

Nesse caso, o JavaScript converte o valor da variável a para uma string antes de concatená-la com a string da variável b.

<br/>

> **Type Conversion**:

<br/>

O Type Conversion, por sua vez, é uma conversão explícita realizada pelo programador. Existem diversas formas de realizar Type Conversion em JavaScript, como os exemplos a seguir:

Convertendo uma string para um número usando a função parseInt:

<br/>

```
const a = "10";
const b = parseInt(a);

console.log(b); // imprime 10
```

<br/>

Convertendo um número para uma string usando a função toString:

<br/>

```
const a = 10;
const b = a.toString();

console.log(b); // imprime "10"
```

<br/>

Convertendo uma string para um número usando o operador +:

<br/>

```
const a = "10";
const b = +a;

console.log(b); // imprime 10
```

<br/>

Convertendo um número para uma string usando o operador +:

<br/>

```
const a = 10;
const b = "" + a;

console.log(b); // imprime "10"
```

<br/>

É importante lembrar que, em alguns casos, a conversão de tipos pode levar a resultados inesperados ou imprecisos, como no caso do Type Coercion em operações envolvendo strings e números. Por isso, é importante entender bem as regras de conversão de tipos em JavaScript e utilizar Type Conversion de forma consciente e cuidadosa.

<br/>
