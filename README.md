
# shiny

Recursos:

- Falar que o mapa já foi pre-carregado (pasta `./grafico/`), deixando
  seu arquivo no projeto, já que instalá-lo demorava alguns segundos;
- pasta `./data/` apresenta 3 bancos de dados `banco_exemplo.csv` (é ele
  que é carregado ao apertar no botão `carregar exemplo`),
  `banco_não_csv.tsv` (banco utilziado para validar o que ocorre ao
  tentar carregar aquivo que não é csv) e `banco_de_dados.csv` (uma
  alternativa de banco de dados, como se fosse o banco de dados da
  pessoa);
- tabela inicial (generalizar valores por meio do YAML)
- Gráfico de mapa;
- Precisa ter uma coluna com o código do estado chamada `code_state` e
  `code_region` (generalizar por meio do YAML);
- Leitura de um banco de dados em csv (colocar aviso caso o banco não
  seja csv);
- Banco exemplo, para o primeiro uso
- Todas as variáveis do banco precisam ser numéricas, usar o arquivo
  YAML para configurar variáveis a serem retiradas;
- Quando já há dados carregados e aperta-se para carregar os dados do
  exemplo, aparece uma caixa de dialogo pergutnando ao usuários se ele
  quer sobrescrever os dados;
- ao tentar carregar dados, se for CSV o botão pisca verde e aparece uma
  confirmação, se não for csv o botão pisca vermelho e aparece um aviso;
- Não esquecer de excluir a pasta `./testes/`;
- Colocar url para acessar o shiny desenvolvido pelo shiny app
  (<https://jsicas.shinyapps.io/shiny/>);
