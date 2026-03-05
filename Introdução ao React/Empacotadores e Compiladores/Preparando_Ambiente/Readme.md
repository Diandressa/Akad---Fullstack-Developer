# Compiladores

Traduzam um código com uma linguagem de alto nível para uma de baixo nível (um executável binária ou arquivo batchcode).

# Transpiladores

Converte de uma linguagem de alto nível de abstração para outro de alto nível também. Ex.: ES6+ para ES5 ou versões anteriores.

# Navegador

Precisamos compilar um código para um que o navegador entenda.

# Linguagem Interpretada x Linguagem Compilada

A linguagem Interpretada traduz o código linha a linha para código de máquina antes de executar, em tempo real. 

A linguagem Compilada traduz de uma só vez o código para linguagem antes de executar

# Compilador Just-In-Time (JIT)

Mistura as linguagens Interpreta e Compilada. O código começa sendo interpretado.
As partes mais usadas são compiladas para código de máquina em tempo de execução.

> O JIT observa quais partes do código rodam muitas vezes e transforma só essas partes em código de máquina otimizado enquanto o programa já está rodando.

# Babel

Compilador Javascript que converte código ECMAScript 2015 ou superior para versões compatíveis com os navegadores, versões anteriores.