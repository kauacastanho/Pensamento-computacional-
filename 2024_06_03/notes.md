<h1>  Funções built-in e uso de import </h1>


<br>
<br>


<h2> Comando import: motivação </h2>

Conforme programas ganham mais complexidade e 
funcionalidades, se torna necessário separar métodos em 
múltiplos arquivos.

Entre os benefícios, podemos citar:

- Organização e Legibilidade: o código se torna mais organizado e legível. Agrupe funcionalidades relacionadas para facilitar a compreensão do projeto.

<br>

![alt text](image.png)

Benefícios (continuação):

- Reutilização de Código: possibilita reutilizar funcionalidades em diferentes partes do seu projeto ou até mesmo em projetos diferentes.
- Colaboração: permite que membros da equipe trabalhem em diferentes partes do código simultaneamente, sem interferir uns com os outros.
- Facilidade de Teste e Depuração: facilita os testes e a depuração (debug), pois você pode isolar e testar cada parte independentemente. 
- Desempenho: Em alguns casos, pode melhorar o desempenho do programa. Isso ocorre porque apenas as partes do código relevantes são carregadas na memória quando necessário.

<br>
<br>

<h2> Import </h2>

Comando usado para carregar módulos de outros arquivos. 

<br>

![alt text](image-1.png)

<br>
<br>

<h2> Arquivo __init__.py </h2>

O arquivo __init__.py é um arquivo especial em Python 
que indica ao interpretador que a pasta contendo este 
arquivo é um pacote Python (package). 

O __init__.py pode estar vazio ou conter inicialização 
do pacote.

É um arquivo obrigatório para que o Python reconheça 
a pasta como um pacote e permita a importação 
de módulos dele.

<br>

![alt text](image-2.png)

<br>
<br>

<h2> Funções: recursividade </h2>

Funções podem executar outras funções ou chamar a elas mesmas. Quando isso ocorre,chamamos de recursividade.

Recursividade SEMPRE 
possui um caso base 
que termina a recursão

<br>

![alt text](image-3.png)

<br>

![alt text](image-4.png)

<br>

Exemplo de recursividade: Fatorial

Exercício: use recursividade para calcular o fatorial

<br>

![alt text](image-5.png)

<br>

Exemplo de recursividade: Fatorial

Comentem: E n for um número negativo?

<br>

![alt text](image-6.png)