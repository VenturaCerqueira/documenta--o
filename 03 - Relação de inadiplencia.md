###  ✅Listagem de inadimplência: 
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)
#### Filtros:
1.  **Período:**
    >**Observação:** (Data - *type: Date* - Data de vencimento do DAM'S) <br>
    ![alt text](Fotos/image.png)

2.  **Tributo:**
    >**Observação:** <br>   *Multiplo* _select_ -- classificação de receita (tipo do tributo *IPTU, TFF, ...)*<br>
    ![alt text](Fotos/image-1.png)<br>
    ![alt text](Fotos/image-2.png)

3.  **Exercicio:** 
    > **Observação:** Seleciona *Ano (2024, 2023, 2022, ...)* <br>
    Filtro da competencia<br>
    ![alt text](Fotos/image-3.png)<br>
    ![alt text](Fotos/image-4.png)

4.  **D.A.:**  
    > **Observação:** *Checkbox* Caso seja uma D.A. deve-se colocar apenas D.A. do tipo do tributo marcado acima em **Tributos**<br>
    ![alt text](Fotos/image-5.png)

5.  **Parcela:** 
    >**Observação:** *Checkbox* desmarcado,<br>  *Texto ao lado:* _"Exibir Parcelas?"_<br>

6.  **Inscrição:**
    >**Observação:** *(Do lançamento do DAM)*, possibilidade de colocar apenas uma inscrição.<br> 
    Exemplo abaixo sistema antigo:<br> 
    ![alt text](/Fotos/inscrição.png)
    
7.  **Atividade Principal:**
    >**Observação:** _Multipla opções_, podendo selecionar varios CNAES_PRINCIPAL. <br>

8.  **Faixa de valor:**
    > **Observação:** Filtro de valor_cota, Filtrando do menor valor até maior valor.<br>
    ![alt text](fotos/faixa_valor.png)

9. **Ordenar:** 
    > **Observação:** Select para ordenar por (nome_contribuinte, DAM'S ou inscrição) apenas uma escolha de organização, 'orde by'.

  
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
10. Arrecadador Totalizador         -   Todos bancos do relatorio
11. Dia                             -   Data Credito
12. Qtd                             -   Quantidade de Cota cada banco
13. Valor Tributo                   
14. Desconto    
15. Multa
16. Juros 
17. Correção
18. Valor Pago
19. Total de lançamento do dia      - Totalizador dos campos 
20. Total Geral dos Lançamentos     - Total de todos os lançamentos do relatorio, todos os bancos. 
```  
