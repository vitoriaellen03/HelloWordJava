Nesse pojeto escreve "Hello, World!" na tela, já que todo programador sabe que é essencial escrever essa frase quando se começa uma linguagem nova :D

<b>Comandos usadas:</b> 
<br>
<b>App</b> - Nome dada a classe do aplicativo em Java

<b>Classes e atributos:</b>
<br>
  public static void main(String[] args) throws Exception { <br>
        System.out.println("Hello, World!"); <br>
        } <br>
  }<br>

<b>public</b> - Este é um modificador de acesso que indica que a classe ou método é acessível a partir de qualquer outra classe. No caso, a função main está definida como pública, o que significa que pode ser chamada de fora da classe. 

<b>static</b> - Este é um modificador que indica que o método ou variável pertence à classe em vez de uma instância específica da classe. O método main é geralmente definido como estático porque é chamado antes que qualquer objeto da classe seja criado.

<b>main ()</b> - Este é o ponto de entrada para a execução do programa Java. É onde a execução do programa Java começa. O método main é sempre chamado pelo sistema quando você executa um programa Java.

<b>String [] args</b> - Este é um parâmetro da função main. É uma matriz de strings que permite que você passe argumentos de linha de comando para o programa Java quando ele é iniciado. O array args contém os argumentos fornecidos quando o programa é executado a partir da linha de comando.

<b>throws Exception</b> - Indica que o método main pode lançar uma exceção do tipo Exception. Isso é uma declaração que informa que o método pode gerar uma exceção e que, se isso ocorrer, a exceção será tratada pelo ambiente de execução.

<b>Sysrem.out.println("")</b> - Esta linha imprime a mensagem "Hello, World!" no console. System.out é um objeto que representa a saída padrão, e println é um método que imprime uma linha na saída padrão, seguido por uma quebra de linha.

<b>""</b> - As aspas duplas definem oque é texto, geralmente imprime os valores como são exatamente.

<b>"Hello, World!"</b> - É uma cadeia de caracteres (string) que será impressa no console quando o programa for executado.
