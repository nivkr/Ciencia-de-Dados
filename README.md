# Bem Vindoo
Ao meu diario de estudos em Ciencia de Dados.

### Apresentação
Hellou. Eu sou a Nicoly Régia, estou me formando em Análise e Desenvolvimento de Sistemas no IFRS, sou analista de Dados há mais de 3 anos e quero migrar para ciencia de dados.


### Inicio
Irei documentar aqui minha evolução nos estudos e tentar deixar uma trilha/passo a passo para quem quiser estudar ou estiver em migração de carreira, assim como eu.

### Canais do Youtube que recomento:
- Profa Cibele Russo da USP:
- Prof Rafael Pinto IFRS:
- Teo Calvo: teomewhy


#Fundamentos em Ciência de Dados - Cibele Russo
youtube: link
![https://github.com/cibelerusso/FundamentosemCienciasdeDados/blob/main/Notebooks/Fundamentos_em_Ci%C3%AAncias_de_Dados_Aula_1.ipynb]


Data Analytics
Data Analytics é a área que analisa dados para extrair informações úteis, identificar padrões e apoiar a tomada de decisão.

Em outras palavras, é o processo de transformar dados em conhecimento.

Definição simples
Data Analytics = coleta + organização + análise + interpretação de dados

O objetivo é responder perguntas como:

O que aconteceu?
Por que aconteceu?
O que pode acontecer no futuro?
O que devemos fazer com base nesses dados?
Tipos principais de Data Analytics
Costuma-se dividir em quatro tipos:

1. Análise Descritiva (Descriptive Analytics)
Responde o que aconteceu.

Exemplos:

Média de vendas do mês
Número de usuários de um aplicativo
Taxa de aprovação de alunos
Ferramentas comuns:

gráficos
tabelas
dashboards
2. Análise Diagnóstica (Diagnostic Analytics)
Responde por que aconteceu.

Exemplos:

Por que as vendas caíram?
Qual fator está associado à evasão escolar?
Ferramentas:

correlação
análise exploratória de dados (AED)
regressão

3. Análise Preditiva (Predictive Analytics)
Responde o que provavelmente acontecerá.

Usa modelos estatísticos e machine learning.

Exemplos:

prever inadimplência
prever demanda
prever churn de clientes
Modelos comuns:

regressão
árvores de decisão
redes neurais
ARIMA
4. Análise Prescritiva (Prescriptive Analytics)
Responde o que devemos fazer.

Envolve otimização e decisão.

Exemplos:

qual preço maximiza lucro
qual rota minimiza custo
qual estoque manter


Ferramentas usadas em Data Analytics
Algumas ferramentas comuns:

Python (Pandas, NumPy, Scikit-learn)
R
SQL
Power BI
Tableau
Excel
Exemplo simples
Suponha dados de vendas de uma loja.

Com Data Analytics podemos:

calcular faturamento médio
identificar produtos mais vendidos
prever vendas futuras
definir o melhor estoque
Definição curta
Data Analytics é o processo de examinar dados para descobrir padrões, gerar insights e apoiar decisões baseadas em evidências.

Uma forma de conectar com a estatística:

Data Analytics é a aplicação do método científico aos dados, utilizando estatística, computação e visualização para transformar dados em conhecimento.

Um pouco mais sobre Análise Descritiva e Análise Preditiva
1. Análise Descritiva
A Análise Descritiva tem como objetivo principal resumir os dados para extrair padrões de eventos que já ocorreram. Nessa categoria, os resultados são obtidos diretamente pela aplicação de algoritmos aos dados brutos, gerando estatísticas, visualizações ou agrupamentos. As principais técnicas descritivas incluem:

Estatística Descritiva: Utilizada para descrever conjuntos de dados (amostras) por meio de sumarização e visualização, podendo ser univariada (uma variável ou atributo), bivariada (pares de variáveis ou atributos) ou multivariada (mais de duas variáveis ou atributos).

Visualização de Dados: Usa gráficos como histogramas, box-plots, gráficos de dispersão e heatmaps para fornecer insights visuais sobre a distribuição e relação dos dados.

Agrupamento (Clustering): Técnica que visa encontrar agrupamentos de dados (grupos de instâncias) semelhantes dentro de um conjunto de dados, sendo amplamente aplicada em áreas como o marketing para segmentação de clientes.

Mineração de Padrões Frequentes: Focada em capturar as associações e padrões que ocorrem com maior regularidade nos dados, como na análise de cestas de compras no mercado varejista.

2. Análise Preditiva
A Análise Preditiva foca na extração de modelos a partir dos dados para realizar previsões sobre o desconhecido ou o futuro. Ao contrário da descritiva, ela utiliza dados rotulados (treinamento) para induzir um modelo que possa associar corretamente os atributos de novos objetos a um rótulo de saída. As tarefas preditivas são subdivididas em:

Regressão: Envolve a predição de um valor quantitativo (numérico), como o preço de um ativo, o tempo de viagem ou indicadores macroeconômicos.

Classificação: O objetivo é atribuir uma categoria ou rótulo qualitativo (classe) a um novo objeto, como decidir se um e-mail é spam ou não, diagnosticar se um paciente está doente ou prever se uma transação financeira é fraudulenta.

Em resumo, enquanto a tecnologia de Big Data foca na coleta e gerenciamento (volume, variedade e velocidade), o Data Analytics e a Ciência de Dados utilizam essa taxonomia para identificar padrões e comportamentos úteis nos dados.


------
[https://github.com/cibelerusso/FundamentosemCienciasdeDados/blob/main/Notebooks/Fundamentos_em_Ci%C3%AAncias_de_Dados_Aula_2.ipynb]

O método científico: Métodos, Técnicas e Algoritmos
Antes de começarmos a programar ou aplicar modelos em ciência de dados, é importante compreender alguns conceitos fundamentais que aparecem com frequência na literatura e na prática: métodos, técnicas e algoritmos.

Embora esses termos sejam frequentemente utilizados como sinônimos no dia a dia, eles possuem significados distintos.

Existe uma distinção clara entre esses termos, embora eles estejam intimamente relacionados no contexto da análise de dados e programação:

Método ou Técnica: É definido como um procedimento sistemático que permite alcançar um objetivo pretendido. O método descreve, de forma geral, como realizar uma determinada tarefa. Por exemplo, o cálculo da média de idades de um grupo é um método.

Algoritmo: É um conjunto de instruções passo a passo, auto-contido e facilmente compreensível por humanos, que permite a implementação de um determinado método. Os algoritmos são projetados para serem facilmente traduzidos para qualquer linguagem de programação.



Problema
Estourar pipoca.

Métodos possíveis
Método 1: aquecimento no fogão (panela)
Utiliza uma panela e uma fonte de calor do fogão para aquecer os grãos de milho.

Método 2: aquecimento no micro-ondas
Utiliza radiação de micro-ondas para aquecer os grãos até que estourem.

O que é um método?
Um método é um procedimento geral utilizado para alcançar um objetivo.
Ele descreve a ideia ou estratégia de solução, mas não necessariamente todos os detalhes da execução.

Exemplo de método para estourar pipoca

Aquecer os grãos de milho até que atinjam a temperatura necessária para estourar, utilizando uma fonte de calor adequada e evitando que queimem.

Observe que o método descreve a estratégia geral, mas não especifica exatamente quais passos devem ser seguidos.

Algoritmo
Um algoritmo é um conjunto finito de instruções passo a passo que descreve exatamente como executar uma tarefa.


Pensamento Científico na Ciência de Dados
Com base nas fontes fornecidas, o método científico aplicado à análise de dados é fundamentado na estatística, especificamente na aprendizagem indutiva, que busca generalizar conhecimento a partir de amostras.

Os principais componentes do pensamento científico na ciência de dados:

Indução (Inferência Estatística): processo de generalizar conhecimento a partir de uma amostra para inferir padrões ou estimativas para a população. Em ciência de dados, ocorre quando modelos aprendem padrões a partir de dados históricos.

Dedução: processo inverso da indução. Parte de um modelo ou conhecimento geral para prever ou classificar casos específicos.

Analytics (Extração de Padrões): uso de métodos analíticos para organizar, transformar e interpretar dados, extraindo conhecimento útil a partir de dados brutos.

Analytics é definida como a ciência que analisa dados brutos para extrair conhecimento útil (padrões).

Gestão de Incerteza e Ruído: reconhecimento de que dados reais possuem imprecisões, exigindo equilíbrio entre viés (modelo muito simples) e variância (modelo muito sensível aos dados).

Validação e Generalização: verificação de que o modelo não apenas memoriza os dados, mas generaliza bem para novos dados.

Indução e Dedução
Indução (Inferência Estatística): É o processo de generalizar o conhecimento obtido de uma amostra para toda a população. Como as populações costumam ser muito grandes ou proibitivamente caras para serem totalmente pesquisadas, a ciência utiliza a amostragem para estimar valores populacionais.

Dedução: É o inverso da indução; ela particulariza da população para a amostra. As probabilidades, por exemplo, tratam de problemas dedutivos ao tentar prever a natureza de uma amostra sabendo-se as características da população.


Metodologias Estruturadas
O método científico em dados não é aleatório; ele segue frameworks rigorosos para garantir a validade do conhecimento descoberto:

Processo KDD (Knowledge Discovery from Data): Uma metodologia acadêmica que propõe nove etapas sequenciais, embora permita retroceder passos para refinar o processo. As etapas incluem

Aprender o domínio da aplicação: Entender os objetivos e as características do problema

Criar um conjunto de dados alvo: Identificar quais dados e atributos são necessários e como serão coletados

Limpeza e pré-processamento de dados: Lidar com valores ausentes, ruídos e definir tipos de dados

Redução e projeção de dados: Selecionar características relevantes e remover atributos irrelevantes

Escolher a função de mineração de dados: Decidir o tipo de método (ex: sumarização, agrupamento, classificação ou regressão)

Escolher o(s) algoritmo(s) de mineração de dados: Selecionar os métodos específicos que se ajustam aos dados

Mineração de dados: Aplicar os algoritmos para extrair padrões e ajustar parâmetros

Interpretação: Avaliar a utilidade e o significado dos resultados para o usuário final

Uso do conhecimento descoberto: Integrar o novo conhecimento no sistema operacional ou em relatórios

CRISP-DM: (CRoss-Industry Standard Process for Data Mining) Uma metodologia voltada para a indústria que organiza o projeto em seis fases cíclicas:

Compreensão do negócio (Business understanding): Definir o problema sob a perspectiva do negócio e traduzi-lo para um problema de análise de dados

Compreensão dos dados (Data understanding): Coletar dados iniciais e realizar uma análise exploratória para obter os primeiros insights e verificar a qualidade

Preparação dos dados (Data preparation): Selecionar, limpar e transformar os dados para que possam ser inseridos nas ferramentas de modelagem

Modelagem (Modeling): Selecionar e aplicar técnicas de análise, ajustando os hiperparâmetros necessários

Avaliação (Evaluation): Verificar se a solução obtida atende aos requisitos e objetivos do negócio definidos inicialmente

Implantação (Deployment): Integrar a solução de análise nos processos de negócio da empresa



















