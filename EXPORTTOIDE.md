# EXPORTAR PARA IDE
1. Primeiramente abra o CodeBlocks.

2. Crie um projeto vazio (File -> New -> Project... -> Empty Project).

3. Escolha o nome desejado para o projeto, e selecione o local para que seja salvo esse processo.

4. Na barra lateral da esquerda, clique com o botão esquerdo em cima do nome projeto que acabou de se criar.

5. Clique na opção adicionar arquivos.

6. Para que o programe compile é obrigatório adicionar um link. (Settings -> Compiler... -> Linker settings -> Other link options -> Escreva: -lm)

6. Selecione os arquivos (os .c e os .h), com **exceção** do main.c.

7. Para exportar o arquivo que se calcula a mantissa (main.c) repita as etapas 1-5, só que na etapa 6 adicione o arquivo main.c ao invés do test.c.
