### ✅Relação de Documentos Emitidos:
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)
#### Filtros:

1.  Período 
   
    >**Observação:** (Data - *type: Date* -Data da emissão do DAM'S) <br>
    ![alt text](Fotos/image.png)

2.  Tributo 
    >**Observação:** <br>   *Multiplo* _select_ -- classificação de receita (tipo do tributo *IPTU, TFF, ...)*<br>
    ![alt text](Fotos/image-1.png)<br>
    ![alt text](Fotos/image-2.png)


3.  Exercicio 
    > **Observação:** Seleciona *Ano (2024, 2023, 2022, ...)* <br>
    Filtro da competencia<br>
    ![alt text](Fotos/image-3.png)<br>
    ![alt text](Fotos/image-4.png)

4.  D.A. 
    > **Observação:** *Checkbox* Caso seja uma D.A. deve-se colocar apenas D.A. do tipo do tributo marcado acima em **Tributos**<br>
    ![alt text](Fotos/image-5.png)

5.  Parcela 
    >**Observação:** *Checkbox* desmarcado,<br>  *Texto ao lado:* _"Exibir Parcelas?"_<br>

6.  Inscrição 
    >**Observação:** *(Do lançamento do DAM)*, possibilidade de colocar apenas uma inscrição.
    <br> 
    Exemplo abaixo sistema antigo:<br> 
    ![alt text](/Fotos/inscrição.png)
    
7.  Atividade Principal 
    >**Observação:** _Multipla opções_, podendo selecionar varios CNAES_PRINCIPAL. <br>
    ![alt text](/fotos/atividade_principal.png)

8.  Situação 
    >**Observação:** _Multiplo select_, Filtrando as situação dos DAM's <br>
    *(Sem filtro[Todos], Pagos, aberto e vencidos)*
        1. Podendo Filtrar: Pagos + Aberto ou Abertos + vencidos

9.  Faixa de valor:
    > **Observação:** Filtro de valor_cota, Filtrando do menor valor até maior valor.<br>
    ![alt text](/Fotos/faixa_valor.png)

10. Ordenar 
> **Observação:** Select para ordenar por (numero do DAM, contribuinte ou vencimento do DAM'S) apenas uma escolha de organização, 'orde by'.   


 ####   Layout PDF:
**Campos:** 
 ```
1.  Contribuinte - Nome do Contribuinte e CPF/CNPJ;
2.  N. Documento - Numero do DAM;
3.  Tributo      - Sigla do Tributo  (Trazendo D.A. caso seja uma D.A ou Parc de parcelamento );
4.  Emissão      - Data de emissão DAM;
5.  Parcela      - Caso tenha parcela, trazer quantidade, *exemplo:*"1/10" ou Unica.
6.  Valor        - Valor da cota original 
7.  Multa, juros e correção  - Campos valor de Juros, multa e correção da Cota;
8.  Valor Pao    - Valor pago da cota; 
9.  Venc.        - Vencimento original;
9.  Inscrição    - Inscrição armazenado no "lançamento" da cota;  
```
![alt text](/Fotos/emitidos.png)

 