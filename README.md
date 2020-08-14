# elasnocongresso-dados

# O que você encontra aqui #

Olá! Esses são alguns dos scripts que utilizei para limpar e trabalhar com os dados da Câmara dos Deputados de projetos de lei que tratam dos direitos das mulheres no projeto <a href="https://www.elasnocongresso.com.br">Elas no Congresso</a>. Veja todas as reportagens <a href="https://www.elasnocongresso.com.br/acompanhe">aqui</a>.

## Regex ##

No arquivo <a href="https://github.com/baliborio/elasnocongresso-dados/blob/master/selecionadoprojetosportema_regex.ipynb">selecionadoprojetosportema_regex.ipynb</a> você pode ver como fizemos para selecionar os projetos de lei que tratam especificamente dos temas que trabalhamos nas reportagens: aborto, violência contra a mulher a participação política, por exemplo. Utilizando regex, selecionamos apenas projetos de lei com termos específicos.

## Tabelas dinâmicas e visualizações ##

Já no <a href="https://github.com/baliborio/elasnocongresso-dados/blob/master/tabelasdinamicas_visualizacoes.ipynb"> tabelasdinamicas_visualizacoes.ipynb</a> você pode ver alguns exemplos de tabelas dinâmicas e visualizações básicas que usamos com as bases de dados desses temas específicos. Aqui, no caso, com a base de dados de projetos que citam Lei Maria da Penha e usamos para essa matéria <a href="https://azmina.com.br/reportagens/projetos-de-lei-para-alterar-lei-maria-da-penha-disparam-no-congresso/">aqui</a>.

## De onde surgiram esses dados? ##

Eles foram capturados utilizando <a href="https://www.elasnocongresso.com.br">a API de dados abertos</a> da Câmara dos Deputados. 

Nós utilizamos a API para a construção da <a href="https://twitter.com/elasnocongresso">robô @elasnocongresso</a> no Twitter.
O código está aberto no GitHub da <a href="https://github.com/revistaazmina/elasnocongressobot">Revista AzMina</a>.
