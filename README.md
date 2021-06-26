# Algoritmo de Curva Koch
Algoritmo recursivo capaz de gerar imagens da curva de Koch.

## Instruções para execução:

**Necessário:**
- JDK 11

**Baixe o reposirório e certifique-se de ter na mesma pasta os seguintes arquivos:**

```bash
Main.java
Image.java 
ImageEx.java 
entrada.txt
```
O arquivo ‘entrada.txt’ deve conter linhas de comando para o devido funcionamento do programa.

**Em seguida é necessário estar no mesmo diretório dos arquivos mencionados acima e compilar “Main.java” com o seguinte comando no terminal:**
```bash
javac Main.java
```

**Por conta de erros de StackOverFlow, é necessária uma memória de 25MB para a criação de uma imagem de 500x500 pixels, e portanto, é necessário rodar o programa com a
seguinte linha de comando:**
```bash
java -Xss25M Main entrada.txt saida.png
```
O arquivo de entrada é apresentado ao programa como o primeiro argumento da linha de comando, logo, o arquivo de saída é, consequentemente, o segundo argumento dessa, 
definindo o nome do arquivo em que será salvo a imagem produzida pelo programa.
