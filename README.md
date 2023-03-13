# Remontagem de Genoma
🧬🔬🖥 Remontagem de genoma utilizando Caminho Euleriano em Python.

## Execução:
### Execução de Teste
Na execução de teste é possível realizar uma grande quantidade de testes para verificar se a remontagem realizada pelo programa está correta ou não.

#### Execução
 - No arquivo ´mainReconstrucao.py´ coloque o parâmtro `teste` com o valor `True`.
 ##### A função mainTesteRemontagem:
 - O primeiro parâmetro da função diz respeito ao arquivo de entrada que será usado.
 - O segundo parâmetro, diz respeito a quantidade de iterações de teste desejada.
 - O terceiro e quarto parâmetro são a quantidade mínima e máxima de bases desejadas, respectivamente.
 - O quinto e sexto parâmetro recebem o valor mínimo e máximo do K, respectivamente.
 
 ### Execução Principal
 O objetivo da execução principal é receber um genoma quebrado em K-mers e remontá-lo, retornando o genoma completo.
 
 #### Execução
 
 ##### Com uma entrada já criada:
 - No arquivo `mainReconstrucao.py` coloque o parâmtro `teste` com o valor `False` e o parâmetro `entrada` com o valor `True`.
 ##### A função mainReconstrução:
 - O parâmetro único diz respeito ao arquivo de entrada que terá as sequências a serem remontadas pelo programa de reconstrução.

##### Com uma entrada a ser gerada:
- No arquivo `mainReconstrucao.py` coloque o parâmtro `teste` com o valor `False` e o parâmetro `entrada` com o valor `False`. Com isso, a entrada será gerada com a função `GeraEntrada`.

 ##### A função GeraEntrada:
- O primeiro parâmetro diz respeito a quantidade de bases que serão geradas.
- O segundo parâmetro é o valor de K que será usado.
