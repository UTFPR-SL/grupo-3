# COMO EXECUTAR
Antes de executar é necessário [compilar](https://github.com/UTFPR-SL/grupo-3/blob/main/HOWTOCOMPILE.md) e [exportar](https://github.com/UTFPR-SL/grupo-3/blob/main/EXPORTTOIDE.md), e o processo é o mesmo do Windows tanto para o Linux (Usando a IDE [CodeBlocks](https://www.codeblocks.org/)), tanto para compilar e quanto pra executar.
Esse processo é válido tanto para o arquivo de teste, quanto para o arquivo main.c que calcula a mantissa.


## Windows e Linux
1. Após exportar e compilar o novo projeto, clique no ícone de *play* (também chamado de *Run*).
![](https://github.com/UTFPR-SL/grupo-3/blob/main/images/21.png)

2. Veja o resultado na parte **Build log**.
![](https://github.com/UTFPR-SL/grupo-3/blob/main/images/22.png)

3. Se nada ocorrer de errado será irá aparecer um terminal com a resposta.
![](https://github.com/UTFPR-SL/grupo-3/blob/main/images/19.PNG)

## Linux (executar usando terminal)

1. Abra o terminal

2. Acesse o diretório onde foi clonado
```
$ git clone https://github.com/UTFPR-SL/grupo-3.git
$ cd grupo-3
```

3. Digite o comando abaixo para compilar:
```
$ make compile
```

4. Por fim, digite o nome do programa e o valor que deseja calcular mantissa:
```
$ ./main 9310831289312.432432
```