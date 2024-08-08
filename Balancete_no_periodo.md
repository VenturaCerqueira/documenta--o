### **Balancete no período:**
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)
####    Filtros:
1.  **Período:** 
    >**Observação:** (Data - *type: Date* -Data da emissão do DAM'S) <br>
    ![alt text](Fotos/image.png)

2.  **Banco:**
    >**Observação:** Seleciona mutipla escolha dos bancos.<br>
    **Exemplo:** *Banco do Brasil, Caixa Econimica, Bradesco e outros bancos.*<br>
    ```
    Banco --> nome 
    ``` 

3. **Classificação pagamento:**
> **Observação:** Select para ordenar por "data_pagamento" ou "data_crédito"

4.  **Situação:**
    >**Observação:** *Select para trazer **DAM'S com situação em** :  abertos, pagos/geral ou pagos/diários.*

```
    input type="radio" 

```
 
####   Layout PDF:
**Campos:** 
 ```
1.  Descrição da Receita / Tributo  -   Descrição da receita ou Sigla;
2.  Arrecadador                     -   Banco;
3.  Natureza                        -   Natureza Juridica; 
3.  Qtd.                            -   Quantidade de DAM's;
4.  Valor Tributo                   -   Valor Original da Cota; 
5.  Desconto (-)                    -   Desconto da Cota;
6.  Multa(+)                        -   Multa da cota;
7.  Juros(+)                        -   Juros da cota;
8.  Correção (+)                    -   Correção monetaria da Cota;
9.  Valor Pago                      -   Valor pago da Cota;
```
![alt text](/Fotos/balancete.png)