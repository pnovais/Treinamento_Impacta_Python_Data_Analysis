# Exercícios Extra - 01
--------------------------
## Pandas

Por Patricia Novais.

--------------------------

1. Crie um dataframe para cada um dos arquivos 
   - nba_2015_a.csv
   - nba_2015_b.csv
   - nba_2015_c.csv
   - nba_2015_d
   - bust_nba_2015.csv
   
  Chame esses dataframes de **df_a**, **df_b**, **df_c**, **df_d** e **bust**, respectivamente.
2. Concatene os arquivos df_a, df_b e df_c usando a função concat(). Salve um dataframe chamado **df**.
3. Use a função *info()* e verifique que tipos de dados temos no dataframe df.
4. Utilize a função *describe()* e verifique algumas estatísticas básicas do dataframe.
5. Verifique se há dados duplicados. Caso sim, quantos?
6. Crie um novo dataframe, **df2**, apenas com os dados não duplicados.
7. O dataframe df2 possui dados faltantes ou nulos? Caso sim, quantos e em quais variáveis?
8. Crie um novo dataframe, **df3**, em que os dados faltantes na coluna *Draft Year* sejam substituídos pelo valor *unknown*.
9. Crie um novo dataframe, **df4**, em que os dados faltantes na coluna *Role Player* sejam substituídos pelo valor *-1*.
10. Faça a concatenação do dataframe df_total com o dataframe bust utilizando a função *merge()* e a variável *ID*. Chame esse novo dataframe de **df_final**.
11. Utilizando o dataframe df_final, faça algumas pequenas análises (**sempre escrevendo pequenas frases com as principais informação/conclusões obtidas**):
  - Renomei a coluna *Player* para *jogador*
  - Renomei a coluna *Draft Year* para *draft_year*
  - Renomei a coluna *Projected SPM* para *projected_spm*
  - Verifique a frequência de dados segundo a variável *Position*. A distribuição é equilibrada ou não?
  - Verifique a frequência de dados segundo a variável *draft-year*. Quais os 2 anos com mais dados?
  - Qual a média da variável *Bust*?
  - Qual a média da variável *projected_spm*?
  