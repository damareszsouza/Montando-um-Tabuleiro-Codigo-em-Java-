# Montando-um-Tabuleiro-Codigo-em-Java-

Montando o Tabuleiro
O próximo método que precisamos implementar deve gerar um tabuleiro, baseado na palavra sorteada.  O tabuleiro deverá ser um vetor de char com o mesmo tamanho do vetor onde a palavra sorteada está armazenada. Ele deve ser preenchido com caracteres de sublinhado (_). Assim, podemos escrever o código do método, que é mostrado abaixo.



static char[] montaTabuleiro(char[] palavra) {

       char[] tabuleiro = new char[palavra.length];

       for(int cont = 0; cont < tabuleiro.length; cont++) {

             tabuleiro[cont] = ‘_’;

       }

       return tabuleiro;

}


Veja como criamos o vetor a ser retornado. Colocamos dentro dos colchetes, não um número, mas palavra.length. Lembre-se de que essa instrução retorna o tamanho do vetor palavra. Assim, o novo vetor será criado com o mesmo tamanho do vetor passado como parâmetro.
