# Data Science
 Material didático sobre o que é Data Science, etapas e como construir um projeto!
 
# O que é Data Science?
Data science/Ciência de dados é a área da computação que estuda dados e informações
de "negócio" em diversas áreas e setores de empresas ou organizações. O profissional é o data scientist/cientista de dados.<br>
Cabe ao data scientist saber lidar com esses dados desde o processo de captura, transformação, geração 
e por fim, a análise. <br>
Ciência de dados engloba algumas disciplinas como:

- Computação;
- Estatística;
- Matemática;
- Conhecimento do Negócio.
     
 # Etapas de um projeto data science
![Captura de tela_20221214_140713](https://user-images.githubusercontent.com/115194365/207661081-2656cc64-673a-4c24-88e9-676664fb895b.png)

- <b>Questão de negócio:</b> Solicitação de solução um problema por parte de uma empresa.<br>
- <b>Entendimento do negócio:</b> Antes de dar um passo a frente, entenda o négocio para entender o problema. Nessa etapa é muito comum as pessoas trazerem as soluções dos problemas do que o problema em si, um exemplo análogo comum em oficinas, se um carro quebra é comum as pessoas irem até o mecânico com a solução: - "quebrou mas acho que é so um parafuso folgado". Geralmente essas pessoas não são as mais indicadas para te fornecerem uma solução.<br>
- <b>Coleta dos dados:</b> Consiste mesmo em buscar a fonte de informações disponíveis, seja em planilhas, em banco de dados, em bigdata ou até mesmo fazendo web scraping.<br>
- <b>Limpeza dos dados:</b> Inicia-se o trabalho de análise, manter ou descartar aquele dado (ou dados)? O quão relevante aquele dado é para nossa resolução do problema?<br>
- <b>Exploração dos dados:</b> Nessa etapa o data scientist absolve mais conhecimento sobre o problema, gera insights pro negócio e consegue definir quais algoritimos de machine learning serão utilizados. Essa é uma das principais etapas e muitas das vezes um projeto de data science é resolvido na etapa de exploração de dados ems a necessidade de passar por machine learning, ML é apenas uma ferramenta de data science.<br>
- <b>Modelagem dos dados:</b> Consiste na preparação dos dados para a próxima etapa, por exemplo, se temos dados que deveriam ser numéricos e estão como object, devemos converter-los ou os algoritmos de ML não irão compreender esses dados. <br>
- <b>Algoritimos de ML:</b> Submeter sua base de dados já pronta aos algoritimos escolhidos.
- <b>Avaliação do algoritmo:</b> Avaliar a acuracity dos algoritmos, observar sua performace e observar se realmente houve o aprendizado.<br>
- <b>Modelo em produção:</b> Disponibilizar o modelo para que as pessoas possam usa-lo em seu dia a dia.

# Ferramentas de data science

Uma das principais ferramentas para se trabalhar com análise de dados em Python é o Pandas, abaixo segue 
o link de um material sobre a biblioteca Pandas que preparei pra vocês:

<a href="https://github.com/dev-daniel-amorim/Analise_de_dados"> - Material Pandas</a>

# Dica

Uma ferramenta muito interessante para apresentação de resutados de um projeto Data Science é o Power BI.<br>
- Mas o que é Power BI?<br>

É uma ferramenta (software) conector, que trabalha junto com os dados transformando-os em informações coerentes, visualmente envolventes, possibilitando a gestão de indicadores de forma prática. O Power BI se conecta com inúmeras fontes de dados como: planilhas de Excel, páginas da web e diversos bancos de dados.<br>
Há meios de conectar os projetos Python com a ferramenta Power Bi, tornando mais prático a importação dos dados, porém ainda encontra-se em fase de desenvolvimento até a data deste post por este motivo ainda não é o mais indicado por apresentar muita lentidão na migração dos dados.<br>

# Vertentes do Data Science

Dividindo data science em etapas  temos:

## Insights 
Etapas até modelagem de dados.<br>

![Captura de tela_20221214_161156](https://user-images.githubusercontent.com/115194365/207691947-8005aacb-206d-4c74-a8ef-47be847f430b.png)

Como criar um projeto de insights:
- Simular um problema de negócio;
- Identificar a causa do problema;
- Coletar dados (Para estudo vc pode usar Reddit, Kaggle, Google Datasets);
- Tratar os dados;
- Levantar hipótese sobre comportamento do negócio;
- Fazer uma análise exploratórias de dados para validar ou descartar as hipóteses;
- Descrever os insigths e sua proposta para solução do problema.

### Projeto de Insight:

<a href="https://github.com/dev-daniel-amorim/DS-Projeto-Insights-01"> - Projeto Insights 01 (Daniel Amorim) </a>

## Data Engineering: 
Apesar de ser uma área diferente de data science é interessante o cientista de dados entender um pouco de pipeline de dados, coleta de dados de diversas fontes, requisições em API´s, query em banco de dados, unir as informações, armazenar e preparar todo dataset a ser analizado (lembrando que esta é uma função do data engineering).<br>

Como criar um projeto de data engineering:
- WebScraping, coletar dados de fontes externas na web;
- Salvar dados em um banco de dados local;
- Atualizar dados com frequencia, pipelines que atualizam todos os dias;
- Limpar dados;
- Explorar os dados.

### Projeto de Data Engineering:

🚧 EM BREVE DISPONIBILIZAREI AQUI PROJETOS DE DATA ENGINEERING

## Machine Learning:
Envolte toda etapa de insights e data engineering, mas desta vez envolvendo aprendizado de máquina (IA) se utilizando de meios matemáticos e estatísticos que se concentram no uso de dados e algoritimos para "imitar" a maneira como os humanos aprendem, melhorando gradualmente sua precisão.

![Captura de tela_20221214_175437](https://user-images.githubusercontent.com/115194365/207711987-c0926256-7100-49f6-9e41-0716582d8488.png)

### Inicialmente temos que entender que o computador aprende de 3 formas:

- 1º aprendizado supervisionado: Quando passamos dados rotulados (um gabarito) onde temos as perguntas já com as respostas. Ex capcha de login. Esse modelo exige uma grande ***diversidade de informações. (principais métodos supervisionados: árvore de decisão, Naive bayes, regressão linear)
    
- 2º aprendizado não supervisionado: Passamos uma base sem respostas, por observação da máquina, por exemplo: Mulher compra mais maquiagem, homem compra mais ferramentas, um site vai oferecer o que mais aquele "grupo" de usúarios procura. O computador separa em grupos por características, por exemplo: ifood, algumas pessoas compram mais ou por cupom ou oferecendo frete grátis outras nem compram.
    
- 3º aprendizado por reforço: Vamos ensinando ao computador por meio de reforço positivo ou negativo, exemplo, recomendação de vídeo do youtube, o youtube mostra vídeos, se eu não assistir é pq não gosta, se assistir é pq eu gosta, assim o youtube vai aprendendo por reforço o que o usuário mais gosta.

Como criar um projeto de machine Learning:
- Obter os insights da empresa em questão;
- Escolher os modelos de aprendizado a serem usados;
- Aplicar aos insights algoritimos de machine learning;
- Avaliar o desempenho dos modelos usando as métricas corretas.

Objetivo: Saber relacionar acuracity de um modelo à perfomace de negócio, ou seja, o quanto um modelo de 90% de acuracity pode trazer em benefícios financeiros (o que o mercado entende e espera).

### Projeto de Machine Learning:

Abaixo link de um projeto de Machine Learning desenvolvido por (Daniel Amorim), autor deste post:<br>
<a href="https://github.com/dev-daniel-amorim/Analise_e_aprendizado_de_maquina"> - Projeto machine learning (Daniel Amorim) </a>

🚧 PROJETO COMPLETO PORÉM EM FASE DE MELHORIAS.

## Projetos End-to-End:
Consiste em produzir a parte visual onde as pessoas possam consulltar facilmente seu modelo no dia a dia, para isso podemos usar tecnologias como Django, Flask entre outros.

Abaixo um vídeo de um projeto End-to-end, desenvolvido por mim onde o usuário final pode entrar com os dados desejados (no caso features de um imóvel) e obter a cotação do mesmo com base nas características passadas:

https://user-images.githubusercontent.com/115194365/207130687-a92a628e-03ae-4b91-add5-50a664a38565.mp4







