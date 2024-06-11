<h1> Manipulação de arquivos <h1>


<br>
<br>


<h2> Criar arquivos <h2>

<br>
<br>

![alt text](image.png)

<br>
<br>

<h2> Criar arquivos: modos de abertura <h2>

<br>
<br>

![alt text](image-1.png)

<br>
<br>

https://docs.python.org/3/library/functions.html#open

<br>
<br>

<h2> Ler arquivos <h2>

<br>
<br>

![alt text](image-2.png)

<br>
<br>

<h2> Quebra de linha <h2>

<br>
<br>

'''
    
    Refere-se ao caractere ou caracteres usados para indicar o final de uma linha de texto.

    Em Linux e macOS o '\n' faz a quebra de linha.
    No Windows ocorre com o caractere de retorno de carro '\r' seguido da nova linha '\n' ('\r\n')

    read() e readline() retorna o conteúdo incluindo os caracteres de quebra de linha
'''

<br>
<br>

<h2> Ler arquivos <h2>

<br>
<br>

![alt text](image-3.png)

<br>
<br>

<h2> Alterar arquivos <h2>

<br>
<br>

![alt text](image-4.png)

<br>
<br>

<h2> Exemplo completo <h2>

<br>
<br>

![alt text](image-5.png)

<br>
<br>

<h2> Bloco with <h2>

<br>
<br>

'''
    Garante que a Garbage Collection ocorra para o arquivo assim que o bloco terminar. 
    Dispensa a necessidade do close()
    Pode ser utilizado com outros recursos, como conexão com DB.

'''

<br>
<br>

![alt text](image-6.png)

<br>
<br>

<h2> Verificar existência <h2>

<br>
<br>

'''
    Retorna um bool informando se o arquivo (ou pasta) existe.
'''

<br>
<br>

![alt text](image-7.png)

<br>
<br>

<h2> Criação de pasta <h2>

<br>
<br>

'''
    Cria a pasta com o nome informado ou falha se já existir
'''

<br>
<br>

![alt text](image-8.png)
