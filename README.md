# Resumo-CPP
Intuito do repositório será guardar resumos e explicações sobre  C#

## Criação de Váriavel

<p align="justify">Variável só acessada dentro da própria classe, vem por padrão com modificador private</p>

```js

[TIPO DA VARIAVEL][NOME DA VARIAVEL] = [VALOR];

```

## Tipo de Váriaveis

- int
- double
- string
- bool
- float
- char

## Sequencia de escape

- \n	 Nova linha
- \t	 Tabulação
- \b	 Backspace
- \"	 Aspa dupla
- \'	 Aspa simples
- \?	 Ponto de interrogação
- \\	 Barra invertida

## Função

```js

[TIPO DE RETORNO][NOME DA FUNÇÃO](){
  //SCRIPT
}

```

## Condicional

```js
if(){
  //script
}else{
  //script
}

switch() {
  case x:
    //script
    break;
  case y:
    //script
    break;
  default:
    //script
}

```

## Listas

```js
ARRAY
[TIPO DE VALORES CONTIDOS][NOME] = new[TIPO]{[VALOR],[VALOR]}

LIST
List<[TIPO]>[NOME] = new List<[TIPO]>(){[VALOR],[VALOR]}

```

## Laço de Repetição

```js

foreach(int i in [ARRAY]){
  //script
}

for(int i = 0; i < [ARRAY].length; i++){
  //script
}

```

## Classe

```js

Public class [NOME]{
  //script
}

```
>[!NOTE]
>Para chamar metodos public de outra classe:
>[CLASS] [NOME]

## Metodo Main

<p align="justify">Desempenha o ponto de entrada em um programa em C#, assinatura padrão do método:</p>

```js

static void Main(string[] args){
  //script
}

```

## Criação do projeto

```bash

dotnet new [NOME]

```

## Compilar projeto

```bash

dotnet build

```

## Rodar Projeto

```bash

dotnet run

```
