Criação de um html escaper com node. 
A execução pode ser feita já com argumentos de entrada e saída na linha de comando.
O primeiro argumento é de entrada e deve ser o nome do arquivo que você quer fazer a limpeza do html. O segundo argumento é o arquivo de saída, que vai o conteúdo html limpo.
É possível não colocar nenhum argumento ou colocar apenas o argumento de entrada, sem o de saída. Contudo, não é possivel colocar apenas o de saída.
Exemplo de execução sem os argumentos: node html-escaper.js
Exemplo de execução com os dois argumentos: node html-escaper.js teste.html saida.txt
Exemplo de execução apenas com o argumento de entrada: node html-escaper.js teste.html