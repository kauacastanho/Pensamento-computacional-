<h1> Controle de fluxo, listas e laços aninhados </h1>

<h2> Listas Aninhadas </h2>

- Listas aninhadas, são listas onde cada elemento armazena outra lista.
- Quando a variável armazena 2 dimensões, também chamamos de matrizes (similar à tabelas).

<br>
<br>

* Cada elemento de ‘total_sales’ (linhas) armazena o histórico de vendas de cada vendedor.

* Cada valor representa uma venda.

* As linhas podem possuir tamanhos diferentes

````
total_sales = [
    [100, 25, 40, 7], 
    [33, 201, 48],
    [175, 29, 94, 88, 62],
]
````
<br>
<br>

<h1> Laços Aninhados </h1>

- Ou nested-loops, ocorrem quando executamos laços de repetição dentro de outros laços mais externos.
- Cada laço possui seu próprio controle de repetição.

<br>
<br>

````
total_sales = [
    [100, 25, 40, 7],
    [33, 201, 48],
    [175, 29, 94, 88, 62],
]
````
````
for sales_per_seller in total_sales: 
    for sale in sales_per_seller:
        print (sale)
````

<br>
<br>

<h1> Laços: Variáveis Acumuladoras </h1>

- Variáveis que armazenam valores acumulado, frequentemente em laços de repetição

<br>

````
month_sales = [100, 220, 143, 94, 65]
total_sold = 0

for sale in month_sales:
    total_sold += sale
print("Total sold this month: ", total_sold)
````

<h1> Laços: Variáveis Contadoras </h1>

- Utilizadas para contar o número de ocorrências de uma condição. 
- Similar as variáveis acumuladoras, porém somando ‘1’ a cada iteração.

````
month_sales = [100, 220, 143, 94, 65]
sale_quantity = 0

for sale in month_sales:
    sale_quantity += 1
print("Quantity of sales this month: ", sale_quantity)
````
<br>

<h1> Laços: Variáveis sinalizadoras </h1>

- Também chamadas de ‘flags’, armazenam um boolean sinalizando se uma situação ocorreu ou não.

````
temperatures = [10, 5, -3, 8, 2]
has_negative_temperature = False

for temperature in temperatures:
    if temperature < 0:
        has_negative_temperature = True
    print ("Temperature", temperature)
if has_negative_temperature:
    print ("Below-zero temperature found.")
````
<br>

<h1> Controle de fluxo: break </h1>

- Comando usado para interromper um laço de repetição
- Serve tanto para ‘while’ quanto ‘for’

```
numero secreto = 42

while True:
    palpite = int(input ("Qual é a senha?: "))
    if palpite == numero_secreto:
        print ("Você acertou!")
        break
    print ("Tente novamente.")
```
<br>

<h1> Controle de fluxo: continue </h2>

- Comando usado para ‘pular’ para a próxima iteração

```
soma_impares = 0

for i in range (1, 20):
    if・1-%・2・==・0：
        continue
    soma_impares += i
```