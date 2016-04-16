# JavaScript Funcional

O nome já diz, programação funcional utiliza a aplicação de **funções**.


Na programação funcional, a menor parte do sistema é uma **Função**.

No **JavaScript** uma função nada mais é que um objeto que possui atributos como:

- arguments

- name

- length

##Funções

- apply - é aceito um array como parâmetro

- call - é passado uma lista como parâmetro

Para criar uma funão:

```
function HelloWorld(data){
	alert('Hello ' + data);
}
```
**TODA FUNÇÃO PRECISA RETORNAR UM VALOR!!!**


Como setar um valor a uma variável {var idade = 30;} utilizando funções: 

**Função identidade**

```
function setIdade(idade){
	return idade;
}

var idade = setIdade(30); // criação de uma espécie de CONTRATO

```

Usando uma função como **argumento** de uma outra função:

```
function maioridade(idade){
	return idade >= 18;
}

maioridade(setIdade(30));

```

