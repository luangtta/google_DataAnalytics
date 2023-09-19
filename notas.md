##### **Autor:** _Leo Nunes Galvão_


# Projeto Google Data Analytics

Estudo de Caso para Certificação em Data Analytics.   

## 1- Fontes dos dados

_**(Consultas:** 09/09/2023 - 17/09/2023)_


### A) Histórico de Leis

* Constituições Brasileira: [Senado](https://www12.senado.leg.br/noticias/glossario-legislativo/constituicoes-brasileiras)
* Leis: [Congresso Nacional - Normas](https://normas.leg.br/busca?q=&anoInicial=2023&anoFinal=2023&pagina=0&pageSize=100)

\* _Obs.: Para as datas anteriores a 1889, foi feita a edição através da url. Veja o exemplo:_   


```
https://normas.leg.br/busca?q=&anoInicial=1889&anoFinal=2023&pagina=0&pageSize=100
```    
<br> 

Na URL exemplo acima, o resultado são as Leis e Normas entre os anos 1889 e 2023, mas para acessar algum período anterior a 1889:   
Em `anoInicial=1889` e `anoFinal=2023` basta substituir por outros de seu interesse. Veja exemplo:     

```
https://normas.leg.br/busca?q=&anoInicial=1821&anoFinal=1821&pagina=0&pageSize=10
```

Nesse caso, o limite disponível é 1821.   
<br>


### B) Saneamento Básico   

* 2000 e 2008: [IBGE - Sidra](https://sidra.ibge.gov.br/tabela/1354)
* 2017: [IBGE - Sidra](https://sidra.ibge.gov.br/tabela/1361)
<br>

### C) BNDES

* [BNDES e Exportações de Serviços](https://aberto.bndes.gov.br/aberto/caso/exportacao/)
<br>

### D) Segurança Pública

* Mortalidade: [Min Saúde - DataSus](http://tabnet.datasus.gov.br/cgi/deftohtm.exe?sim/cnv/obt10uf.def)
* Taxa Homicídio Mundial: [World Bank.org](https://data.worldbank.org/indicator/VC.IHR.PSRC.P5?most_recent_value_desc=false)
* População _(anos anteriores)_: [IBGE - Sidra](https://sidra.ibge.gov.br/tabela/6579#resultado)
* População _(últimos anos)_: [IBGE](https://www.ibge.gov.br/apps/populacao/projecao/index.html?utm_source=portal&utm_medium=popclock)
* População _(censo)_: [IBGE](https://www.ibge.gov.br/busca.html?searchword=censo+popula%C3%A7%C3%A3o)
* População _(dados)_ [IBGE](https://agenciadenoticias.ibge.gov.br/agencia-noticias/2012-agencia-de-noticias/noticias/37237-de-2010-a-2022-populacao-brasileira-cresce-6-5-e-chega-a-203-1-milhoes)
* População _(dados históricos)_: [IBGE](https://memoria.ibge.gov.br/historia-do-ibge/historico-dos-censos/dados-historicos-dos-censos-demograficos.html)
* População - Brasil 500 anos: [IBGE](https://brasil500anos.ibge.gov.br/estatisticas-do-povoamento/evolucao-da-populacao-brasileira.html)
* População _(2007)_: [IBGE](https://sidra.ibge.gov.br/tabela/793#resultado)
<br>

### E) Economia - PIB, Contas, Despesas e Dívidas Públicas, Desemprego

* PIB: [IBGE](https://www.ibge.gov.br/estatisticas/economicas/contas-nacionais/9300-contas-nacionais-trimestrais.html?edicao=35642&t=resultados) _(ver Tabelas Com Dados Atualizados)_
* Despesas: [Portal da Transparência](https://portaldatransparencia.gov.br/orcamento/despesas?paginacaoSimples=true&tamanhoPagina=&offset=&direcaoOrdenacao=asc&de=2023&ate=2023&orgaos=OS26000&colunasSelecionadas=ano%2CorgaoSuperior%2CorgaoVinculado%2Cfuncao%2CsubFuncao%2Cprograma%2Cacao%2CcategoriaEconomica%2CgrupoDespesa%2CelementoDespesa%2CorcamentoInicial%2CorcamentoAtualizado%2CorcamentoRealizado%2CvalorEmpenhado%2CpercentualRealizado&ordenarPor=ano&direcao=desc)
* Dívida Pública: [Banco Central do Brasil](https://www.bcb.gov.br/estatisticas/tabelasespeciais) _(ver Evolução da dívida pública - tabelas adicionais)_
* Quitação Dívida FMI _(Lula)_: [Câmara dos Deputados](https://www.camara.leg.br/radio/programas/266702-quitacao-antecipada-de-divida-com-fmi-causa-polemica-05-18)
* Desemprego: [IBGE](https://www.ibge.gov.br/estatisticas/sociais/trabalho/9173-pesquisa-nacional-por-amostra-de-domicilios-continua-trimestral.html?=&t=series-historicas&utm_source=landing&utm_medium=explica&utm_campaign=desemprego)
<br>

### F) Educação

* Leitura: [PISA - OCDE](https://pisadataexplorer.oecd.org/ide/idepisa/report.aspx?p=1-RMS-1-20183,20153,20123,20093,20063,20033,20003-PVREAD-TOTAL-AUS,AUT,BEL,CAN,CHL,COL,CZE,DNK,EST,FIN,FRA,DEU,GRC,HUN,ISL,IRL,ISR,ITA,JPN,KOR,LVA,LTU,LUX,MEX,NLD,NZL,NOR,POL,PRT,SVK,SVN,ESP,SWE,CHE,TUR,GBR,USA,ALB,QLB,DZA,ARG,QRG,BAK,BLR,BIH,BRA,BRN,QCH,QCI,BGR,TAP,CRI,HRV,QCY,DOM,GEO,HKG,IDN,JOR,KAZ,QAZ,KSV,LBN,MAC,MYS,QYS,MLT,MDA,MNE,MAR,MKD,PAN,PER,PHL,QAT,ROU,RUS,SAU,SRB,SGP,THA,TTO,TUN,UKR,ARE,URY,VNM-MN_MN-Y_J-0-0-37&Lang=1033)
* Matemática: [PISA - OCDE](https://pisadataexplorer.oecd.org/ide/idepisa/report.aspx?p=1-RMS-1-20183,20153,20123,20093,20063,20033,20003-PVMATH-TOTAL-AUS,AUT,BEL,CAN,CHL,COL,CZE,DNK,EST,FIN,FRA,DEU,GRC,HUN,ISL,IRL,ISR,ITA,JPN,KOR,LVA,LTU,LUX,MEX,NLD,NZL,NOR,POL,PRT,SVK,SVN,ESP,SWE,CHE,TUR,GBR,USA,ALB,QLB,DZA,ARG,QRG,BAK,BLR,BIH,BRA,BRN,QCH,QCI,BGR,TAP,CRI,HRV,QCY,DOM,GEO,HKG,IDN,JOR,KAZ,QAZ,KSV,LBN,MAC,MYS,QYS,MLT,MDA,MNE,MAR,MKD,PAN,PER,PHL,QAT,ROU,RUS,SAU,SRB,SGP,THA,TTO,TUN,UKR,ARE,URY,VNM-MN_MN-Y_J-0-0-37&Lang=1033)
* Ciências: [PISA - OCDE](https://pisadataexplorer.oecd.org/ide/idepisa/report.aspx?p=1-RMS-1-20183,20153,20123,20093,20063,20033,20003-PVSCIE-TOTAL-AUS,AUT,BEL,CAN,CHL,COL,CZE,DNK,EST,FIN,FRA,DEU,GRC,HUN,ISL,IRL,ISR,ITA,JPN,KOR,LVA,LTU,LUX,MEX,NLD,NZL,NOR,POL,PRT,SVK,SVN,ESP,SWE,CHE,TUR,GBR,USA,ALB,QLB,DZA,ARG,QRG,BAK,BLR,BIH,BRA,BRN,QCH,QCI,BGR,TAP,CRI,HRV,QCY,DOM,GEO,HKG,IDN,JOR,KAZ,QAZ,KSV,LBN,MAC,MYS,QYS,MLT,MDA,MNE,MAR,MKD,PAN,PER,PHL,QAT,ROU,RUS,SAU,SRB,SGP,THA,TTO,TUN,UKR,ARE,URY,VNM-MN_MN-Y_J-0-0-37&Lang=1033)
<br>


### G) Reforma Agrária
* Sobre os índices: [INCRA](https://www.gov.br/incra/pt-br/assuntos/reforma-agraria)
* Sobre os índices: [Sistema Brasileito do Agronegócio](https://sba1.com/noticias/noticia/23145/Incra-bate-recorde-na-entrega-de-titulos-de-terras-no-governo-Bolsonaro)
* Notícias: [CNN](https://www.cnnbrasil.com.br/politica/fatos-primeiro-bolsonaro-acerta-sobre-numeros-de-titulacao-de-terras-mas-omite-dados-de-reforma-agraria/)
* Dados históricos: [Confederação da Agricultura e Pecuária do Brasil](https://www.cnabrasil.org.br/assets/arquivos/artigostecnicos/artigo-21_0.47033300%201514912077.pdf)
<br>  


### H) Programa Social/ Salário Mínimo  
  
* Salário Mínimo: [IPEA (Ministério do Planejamento e Orçamento)_](http://www.ipeadata.gov.br/ExibeSerie.aspx?serid=1739471028)
* Programa Social: [Governo Federal](https://www.gov.br/pt-br/noticias/assistencia-social/2023/06/bolsa-familia-de-junho-tem-maior-valor-medio-da-historia-r-705-40)  
<br>  
    

### I) Pesquisa sobre Perfil Eleitores

Como se trata de pesquisas de rua realizadas por instituições privadas, não é possível afirmar que não haja viés.
De qualquer forma, tais instituições são as mais conhecidas.

* Perfil geral: [Globo](https://valor.globo.com/politica/noticia/2023/09/15/datafolha-brasil-tem-29percent-de-petistas-e-25percent-de-bolsonaristas.ghtml![image](https://github.com/luangtta/google_DataAnalytics/assets/130844487/17538bed-22be-4bff-b198-419edeb46944))
* Perfil geral: [Folha](https://www1.folha.uol.com.br/poder/2022/05/datafolha-lula-vai-melhor-entre-quem-recebe-auxilio-brasil-e-tem-medo-da-covid.shtml)
* Presidiários: [Globo](https://oglobo.globo.com/politica/bolsonaro-ou-haddad-veja-em-quem-os-presos-brasileiros-votaram-23359518)
* Presidiários: [Câmara dos Deputados](https://www.camara.leg.br/noticias/143233-voto-de-presos-provisorios-diversifica-perfil-do-eleitor-brasileiro/)
<br>


## 2- Execução

**Toda a limpeza, tratamento, análise, gráficos foram realizados pelo autor**
**Softwares utilizados:** Calc _(LibreOffice)_, Excel, Google Sheets, Tableau**

### A) Histórico de Leis

Através do portal, apenas a quantidade de leis por ano foram consideradas para gerar o gráfico.   
Sem necessidade de tratamento nesses dados.  
<br>


### B) Saneamento Básico

\* Obs.: O IBGE disponibiliza **apenas** os anos 2000, 2008 e 2017. Dessa forma:

* Para 2000 e 2008 foi utilizada a _"Tabela 1354 - Número de municípios, total e os com coleta de esgoto sanitário, por tipo de rede coletora"_.  
* Para 2017, a tabela utilizada para os outros anos não estava mais disponível; dessa forma, a tabela que entrega os mesmos dados é a _"Tabela 1361 - Número de municípios, total e os com coleta de esgoto sanitário, por tipo de constituição jurídica das entidades prestadoras de serviço de esgotamento sanitário"_.  

Ambas as tabelas detalham e relacionam o número total de municípios do país com os que possuem coleta de esgoto.  

**O processo de tratamento consistiu em:**  
* Encontrar o número de municípios sem coleta de esgoto, bastando apenas calcular a diferença entre os resultados coletados;
* Encontrar o percentual de municípios com e sem coelta de esgoto para estabelecer a relação apresentada no gráfico.
<br>


### C) BNDES  

Através dos dados disponibilizadas pelo portal do BNDES, foi montada uma tabela relacionando o montante emprestado com os países para gerar o gráfico.
Sem necessidade de tratamento nesses dados.  
<br>


### D) Segurança Pública  

Para os índices nacionais sobre mortalidade: foram utilizados apenas os dados do portal DataSus/ Tabnet: Sistema de Informações Sobre Mortalidade - SIM.  
No site, há vários filtros. A tabela foi gerada com os seguintes:
* Mortalidade - Brasil:
  * Linha: Categoria CID-10
  * Coluna: Unidade da Federação
  * Conteúdo: Óbitos por Ocorrência _(*)_
* Períodos Disponíveis:
  * Todos os disponibilizados pelo DataSus _(1996 até 2021)_
* Seleções Disponíveis: Padrão do Sistema _(sem alterações)_

**O processo de tratamento consistiu em:**  
* Para **HOMICÍDIOS**: filtrar os dados da "Categoria CID_10" entre "X85 e Y09", e "Y35" - que representam os óbitos através de todas as formas de agressões disponíveis, incluindo "Intervenção Legal".  
* Para **ARMAS DE FOGO**: filtrar os dados da "Categoria CID_10" entre "X93 e X95" - que representam os óbitos através de agressões por armas de fogo.
* A coluna "TOTAL" apresenta a somatória de todo país.
* A Taxa "Óbitos/100 mil habitantes" para ambos os casos, foi obtida através do cálculo:
`Nº Óbitos Total no ano/ Total Habitantes no país no ano X 100.000`

Para o comparativo entre os países foram utilizados os dados do portal "WorldBank.org".  
No site, há vários filtros. A tabela foi gerada com os seguintes:
* "Intentional homicides _(per 100,000 people)"_  
* Período: Todo disponibilizado pelo sistema _(1990 até 2021)_  
* Em "All Countries and Economies" classificar pelos maiores e menores em "Most Recent Value"
* Com o resultado, utilizar 1 de cada paíss com menor _(Japão)_ e maior índices _(Jamaica)_. Os demais escolhidos foram:
  * EUA: por ser referência em várias áreas  
  * Peru: por ser da América do Sul
  * África do Sul: por ser conhecida pelos conflitos
* Voltar a barra de filtro/ pesquisa do portal e digitar os países, incluindo o Brasil
* O gráfico utilizado no estudo foi o mesmo gerado pelo portal do "WorldBank.org"
<br>

### E) Economia

Para "Dívida Pública - Valores" e "Dívida Pública x PIB (%) os dados foram coletados no site do Banco Central.  
A tabela utilizada: "Tabela 1- Estoques da DBGG, segundo a metodologia utilizada pelo BCB"
* Em "Assunto"
  * Dívida Líquida e Necessidades de Financiamento do Setor Público
      * ​Evolução da dívida pública - tabelas adicionais (baixar planilha)
* A planilha utilizada foi: "Tabela 1- Estoques da DBGG, segundo a metodologia utilizada pelo BCB"


**O processo de tratamento consistiu em:**   
* Para os anos entre 2000 e 2006: utilizar os dados contidos nas colunas "R$ milhões e %PIB" no agrupamento "Total" em "Metodologia vigente ate 2007".   
* Para os demais anos _(2007 até 2022)_ utilizar os dados contidos nas colunas "R$ milhões e %PIB" no agrupamento "Total" em "Metodologia atual".   
* Os dados extraídos geram os 2 gráficos.  
  
  
Para "PIB - Valor Corrente", os dados foram coletados no portal do IBGE.  
A tabela utilizada: "Tabelas Completas _(tabelas com dados atualizados)"_ em SCNT - Sistema de Contas Nacionais Trimestrais

**O processo de tratamento consistiu em:**  
* Dentre as planilhas disponíveis no arquivo baixado, utilizar "Valores Correntes"  
* A coluna "PIB" apresenta todos os anos disponibilizados pelo sistema _(1995 até o presente - 2023)_  
* Constam ali o acumulado nos trimestres bem como a consolidação anual, sendo este último utilizado na análise, com seu respectivo ano.


Para "Desemprego", os dados foram coletados do portal do IBGE.  
A tabela utilizada: "PNAD Contínua - Pesquisa Nacional por Amostra de Domicílios Contínua" - Série Histórica - Taxa de Desocupação

**O processo de tratamento consistiu em:**  
_Obs.: A planilha apresenta os dados trimestrais, acumulados, mantendo uma parcela sobreposta entre dois períodos de divulgação subsequentes._  

* Limpeza contou com a eliminação da sobreposição dos dois períodos.
    
<br>

### F) Educação  

No site do PISA - OCDE em "OECD - Skill Surveys" há diversos filtros. Utilizar:
1. Select Criteria:
  * Subject: Reading, Mathematics, Science
  * Age: 15 years
  * Category: Scales >> Overall Scores:
      * PISA Reading Scale: Overall Reading
      * PISA Mathematics Scale: Overall Mathematics
      * PISA Science Scale: Overall Science
  * Group: OECD e Partners
2. Select Variables:
  * Category: Student and Family Characteristics >> Student Demographics >> All Students
3. Edit Reports: manter os 3 relatórios selecionados
4. Build Reports

**O processo de tratamento consistiu em:**
_(A partir do relatório gerado)_
* Separação de cada competência _(matemática, ciências e leitura)_ por ano
* Exclusão dos dados nulos e ausentes de cada tabela
* Exclusão da coluna "Standard Error"
* Organização por ordem decrescente da coluna "Average" _(média)_ 
* Para o gráfico foi gerado apenas os dados relativos ao Brasil, sua colocação e o número de países com notas em cada ano
<br>


### G) Reforma Agrária

Os dados utilizados foram coletados dos sites do INCRA, da Confederação da Agricultura e Pecuária do Brasil e da CNN.  
Os dados foram apenas organizados em "Desapropriação", "Assentamento" e "Titulação".  
A explicação para cada termo foi coletado no site do próprio INCRA.  
<br>  
    
     
### H) Programa Social/ Salário Mínimo  

Programa Social: foram considerados os valores da forma que foram apresentados para geração do gráfico.  
Salário Mínimo: foram considerados os valores do mês de dezembro de cada ano como referência.   
<br>  
  
      
### I) Eleitores  
  
**O processo de tratamento consistiu em:**
* Para essa análise foi considerada apenas o partido que mais venceu as eleições presidenciais e o perfil de seu eleitor.
* Dentre todos os perfis de eleitores apresentados pelos Institutos de Pesquisas, foram considerados apenas aqueles que apresentavam a maior diferença.  
* Os gráficos apresentam apenas o perfil do eleitor deste partido, e dessa forma, todo o restante foi considerado, "outros partidos" - pois não é relevante para o objetivo da análise.
