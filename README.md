[![author](https://img.shields.io/badge/author-brunarigo-purple.svg)](https://www.linkedin.com/in/brunamoreirarigo/)

Olá, seja muito bem vindo e bem vinda!

Neste repositório você encontrará o projeto desenvolvido para aplicar os conceitos e técnicas de Data Science aprendidadas durante o Bootcamp Alura de Data Science Aplicada 2.
Essas técnicas abrangem os estudos de Python e Pandas, focados nos seguintes itens:
*   Aquisição e leitura de Dados reais (DATASUS)
*   Visualizações de Dados
*   Manipulação de Dados
*   Análise de Gráficos e Criação de Hipóteses
*   Manipulação e Intepretação de Gráficos


# <p align="left"> O Projeto: Análise de dados do DATASUS para as cidades do ABC Paulista
  
<p align="center">
 <img src = "https://newsservice.com.br/wp-content/uploads/2020/08/reducao-de-custos-em-hospitais-como-fazer-otimizacoes-na-area-administrativa.jpg">
</p>
  
A idéia inicial do Projeto é entender os valores gastos com procedimentos hospitalares no SUS em caráter de Atendimento de Urgência durante o período crítico em que tivemos o maior pico de casos de COVID-19 até o momento (Set/20 a Fev/21), para as cidades da região do ABC Paulista, e como esses valores foram gastos e direcionados (ou não) aos habitantes de cada cidade.

Através dessa análise, tem-se a intenção de iniciar o estudo para entender se os valores repassados ao munícipio são suficientes para manter o atendimento à saúde da população desse mesmo município e, se não, identificar quais são os municípios que tem a situação mais crítica da região e utilizar dessa informação para criar alternativas de lidar com essa situação, mantendo assim o atendimento básico aos habitantes mesmo em situações críticas como uma Pandemia.

Com essa análise também foi possível evidenciar o comportamento dos habitantes quando não encontram atendimento disponível na sua cidade. 

## <p align="left"> Dados Utilizados
  
Todos os dados foram extraídos do DATASUS e podem ser encontrados [aqui](http://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=11633&VObj=http://tabnet.datasus.gov.br/cgi/deftohtm.exe?sih/cnv/qi)
  
Para esse projeto foram realizadas 2 exportações de dados para análise, sendo elas:

1.   Dados Consolidados AHI (RD), por local de Internação
2.   Dados Consolidados AIH (RD), por local de Residência

Os filtros utilizados para as extrações foram:

*   Período Janeiro 2020 - Março 2021
*   Ano/Mês Atendimento
*   Valor Total
*   Municípios do ABC Paulista
*   Caráter Atedimento - Urgência

## <p align="left"> Motivação

O IBGE (Instituto Brasileiro de Geografia e Estatística) divulgou em 27/08/2020 as estimativas das populações residentes nos 5.570 municípios brasileiros, com referência em 1º de julho de 2020. Nessa data, a população do Brasil chegou a 211,8 milhões de habitantes e a soma das sete cidades do *Grande ABC* a 2.807.712, sendo:

*   São Bernardo do Campo: 844.483
*   Sando André: 721.368
*   Mauá: 477.552
*   Diadema: 426.757
*   São Caetano 161.957
*   Ribeirão Pires: 124.159
*   Rio Grande da Serra: 51.436
  
Fonte: https://www.dgabc.com.br/Noticia/3532606/grande-abc-tem-2-8-milhoes-de-habitantes-segundo-ibge

A motivação para a escolha do tema e escopo do projeto foi, após acompanhar o pico que tivemos de casos de COVID-19 na região, ver algumas notícias na mídia que levantaram a informação de que algumas cidades da região estavam recusando atendimento a habitantes de outras cidades. Veja esse exemplo:
  
*"Em São Bernardo do Campo a ocupação de leitos chegou a 87% na rede pública e 91% na rede privada na segunda-feira (22). De acordo com a Prefeitura, 25% dos pacientes internados vem de outros municípios. O Hospital Anchieta, que tem 19 leitos para Covid-19, está com todos ocupados nesta terça-feira (23). A cidade não receberá mais pacientes de Mauá e Diadema."*
  
Fonte: https://g1.globo.com/sp/sao-paulo/noticia/2021/02/23/cidades-do-abc-chegam-ao-maior-nivel-de-ocupacao-de-leitos-de-uti-para-a-covid-19-em-onze-meses-de-pandemia.ghtml

É compreensível que, mesmo em uma região com tantas cidades e tantos habitantes, (como habitante do ABC Paulista) posso dizer que não estávamos preparados e não tínhamos estrutura para atender a necessidade de toda a população. Mas, agora que os dados referente à esse período já foram registrados, o que podemos tirar disso?

A Pandemia da COVID-19 infelizmente está longe de acabar e é preciso usar do que já temos para nos preparar para o que podemos enfrentar pela frente.
Quais foram as cidades que mais sofreram por precisar buscar atendimento nas cidades vizinhas? 
Onde tivemos a situação mais crítica? Em quais cidades os habitantes tiveram os maiores prejuízos por precisarem se deslocar em busca de atendimento? 
Em quais cidades houve um aumento considerável dos gastos por, além de enfrentarmos uma situação de crise no sistema de saúde, sobrecarregar o sistema de atendimento por precisar dar conta dos habitantes de cidades vizinhas? Seria uma possibilidade viável criar cidade-polo de atendimento para tentar resolver essa situação? E quem sabe hospitais de campanha nas cidades que mais sofreram?
  
Entender o foco do problema nos dá a capacidade de abrir espaço para poder buscar soluções. 
E é isso que será abordado nesse projeto.

Aproveito para agradecer a sua presença até aqui!
Sinta-se a vontade para sugerir melhorias e manter contato.
  
Obrigada!
  
[Ir para o Notebook do Projeto](https://github.com/brunarigo/DS-project01-datasus-analysis/blob/main/Notebooks/Project01_Datasus_Analysis.ipynb)
