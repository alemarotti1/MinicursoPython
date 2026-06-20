# Lógica Básica

O python é uma linguagem de script. Dessa forma, ela não é compilada, sendo interpretada pelo interpretador python(o mesmo vem instalado por padrão na maioria das distribuições linux, porém precisa ser instalada no windows).

## Executando e "Hello World"
para iniciar o interpretador basta digitar "python"(ou "python3", dependendo do terminal). Caso você escreva o comando sem parametros, o interpretador irá abrir pra permitir para o usuário digitar comandos. 
A outra opção é digitar "python nomedeumarquivo.py". Ao fazer isso, o comando lerá o arquivo informado e o executará.


Primeiro comando: Hello world

O primeiro comando que vamos aprender serve para exibir informações na tela. Esse comando é a função 'print()'. Para usar essa função, basta chama-la pasasndo uma string como parâmetro, da seguinte forma:
```
print("texto")
```

Exercícios:
1. Crie um arquivo chamado "exercicio1.py" adicione uma linha chamando a função 'print()', passando '"Ola mundo"' como parâmetro.
2. Execute o arquivo usando 'python exercicio1.py'


## Sintaxe 
O básico da sintaxe do python é diferente da maioria das outras linguagens de programação. As principais diferenças são:

Não precisa declarar variáveis, nem usar ponto e vírgula no final das linhas.
Dessa forma, quando vamos criar uma variável, podemos simplesmente criá-la simplesmente digitando o nome que nós desejamos que a variável tenha e atribuir um valor a ela com uma atribuição, dá seguinte forma:

```
variavel="valor"
```

Além disso, podemos criar comentários no código utilizando o simbolo de jogo da velha, assim:

```
# Isso é um comentário que sera ignorado pelo interpretador de python
```

### Tipos Comuns de Variáveis
Apesar de não ser necessário declarar os tipos das variáveis, os valores armazenados dentros das variáveis possuem tipos diferentes. Esses tipos podem ser verificados com a função "type()". Por exemplo, caso executassemos o seguinte código:
```
variavel="Ola mundo"
type(variavel)
```
Nós obteriamos o resultado "str", que é equivalente ao tipo de strings.

Os tipo que mais vamos utilizar são os seugintes:

1. String; Int; Float, bool; Os tipos básicos mais comuns
2. Listas; Dicionários; Tuplas; Os tipos de agrupamentos
3. Range; Tipo que gera um iterador que vamos usar com frequência em loops



### Blocos de código
Além de não precisar declarar variáveis, não precisamos usar chaves para definir blocos, assim o python utiliza indentação para definir diferentes blocos de código. Podemos usar tanto espaços quanto tabs para indentar, porém devemos ser consistentes na nossa escolhas. 

__Usando instruções de bloco__:
Para exemplificar as instruções de bloco, vamos utilizar os condicionais. para utilizar condicionais, podemos usar os comandos "if" "elif" e "else", podemos fazer isso da seguinte forma:

```
if condicao:
  comandos
```
Diferentemente de outras linguagens de programação, nós não precisamos usar parentesis. Ou seja, um código real usando o if ficaria assim:
```
if True: #True e False em python começam com letras maiusculas
  print("ola mundo") #tudo que queremos que esteja dentro do if, deve ser identado um nível a mais
```

Porém precisamos tomar cuidado com a quantidade de espaços dentro do mesmo bloco de código. Todas as linhas dentro de um mesmo bloco devem possuir a mesma quantidade de identações. Além disso, também não podemos misturar tabulações e espaços.







