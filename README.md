# Histórico dos Regimes Próprios Brasileiros

Trata-se de uma pesquisa simples na base de dados disponibilizada pela Secretaria Especial de Previdência e Trabaho do Ministério da Economia.
A página html está disponível [aqui](https://rafaelneumann.github.io/historico_rpps/). 

## Estrutura

O arquivo html contém o mínimo de CSS e todo o código Javascript, mas a base de dados disponível em _xlsx_ foi tranformada em um arquivo _tsv_, depois transformado em ASCII URL seguro e em seguida base 64. Esse formato é suficiente para que não seja necessária uma base de dados. O navegador do cliente executa todos processamentos.
