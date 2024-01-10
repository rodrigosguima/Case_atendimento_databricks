# Case_atendimento_databricks
Relatório trás informações sobre algumas métricas de atendimentos (CX)

1 - Qual o contact rate da Operação e o que você sugeriria para que ele reduzisse?

R.: Contact rate (taxa de contato) é uma taxa de contato do usuário com o atendimento, ou seja, é a "demanda atendida" em relação a "base de clientes ativos". 
O cálculo é feito da seguinte forma:
- (Demanda atendida/base de clientes ativos)x100
No mês de janeiro/23 tivemos uma "Demanda atendida" = 71335 e "clientes ativos" = 250000,o que resultou em um "Contact rate" de 28,5%;
No mês de fevereiro/23 tivemos uma "Demanda atendida" = 57587 e "clientes ativos" = 253000,o que resultou em um "Contact rate" de 22,7%;
No mês de marco/23 tivemos uma "Demanda atendida" = 61925 e "clientes ativos" = 240000,o que resultou em um "Contact rate" de 25,8%;
No mês de abril/23 tivemos uma "Demanda atendida" = 63352 e "clientes ativos" = 265000,o que resultou em um "Contact rate" de 23,9%;
No mês de maio/23 tivemos uma "Demanda atendida" = 67484 e "clientes ativos" = 267000,o que resultou em um "Contact rate" de 25,2%;
No mês de junho/23 tivemos uma "Demanda atendida" = 69620 e "clientes ativos" = 267000,o que resultou em um "Contact rate" de 26,0%;
No mês de julho/23 tivemos uma "Demanda atendida" = 82319 e "clientes ativos" = 268000,o que resultou em um "Contact rate" de 30,7%;
No mês de agosto/23 tivemos uma "Demanda atendida" = 67523 e "clientes ativos" = 282000,o que resultou em um "Contact rate" de 23,9%;

Com uma média de 25,8% no período(jan23 a ago23)

2 - O capacity está adequado para suportar a demanda de atendimento?

R.: Capacity, é quando referimos a quantidade de "agentes".
Observando os dados fornecidos de jan/23 a ago/23, fica claro que o capacity não está adequado para suportar a demanda de atendimento, foi notório que até abril/23 a quantidade de demandas recebidas eram volumosamente grande, chegando próximo ou ultrapassando o total de clientes ativos.
Podemos observar também que alguma medida foi tomada a partir do mês de abril porque em maio a quantidade de demanda recebida diminuiu 56%, junho 44%, julho 49%, agosto 60% - cálculos feitos tomando por base o mês de abril, último mês com demanda recebidas em alta no período.
É perceptível o aumento da quantidade de agentes a partir de abril/23 porém o percentual atendido pode e deve ser muito melhorado onde o maior percentual atendido foi em julho/23 com 74%.

3 - Algum indicador está correlacionado com CSAT (customer satisfaction)? Se sim, como?

R.: CSAT se trata da satisfação do cliente com o produto.
Alguns indicadores estão correlacionados com o CSAT como:
 "duração do chat (minutos)": O tempo que leva para resolver as consultas ou problemas dos clientes pode impactar significativamente a satisfação    do cliente. Quanto mais rápido a empresa resolver as questões dos clientes, maior a probabilidade de receber uma pontuação CSAT mais alta. De acordo com os dados analisados podemos ver que o tempo de atendimento varia em média de 6 a 8 minutos;
"qualidade": Avaliações específicas da qualidade do produto ou serviço oferecido podem estar correlacionadas com o CSAT. Clientes satisfeitos geralmente classificam o produto ou serviço como de alta qualidade. Aqui podemos ver que até maio esta métrica não tinha monitoria e a partir de junho o CSAT apresentou melhora, muito provável pela monitoria efetiva da qualidade.

4 - Alguma sugestão para reduzir o % de demanda perdida?

R.:
1) Avaliar se os agentes estão dimensionados para as demandas recebidas, se necessário, considere contratar mais funcionários ou terceirizar parte do atendimento com escalas de trabalho flexíveis para atender às demandas em horários de pico;
2) Desenvolvendo um sistema de priorização de demandas com base em critérios como urgência e impacto no cliente garantindo que as demandas mais importantes sejam tratadas primeiro;
3) Vinculado com a ideia de chatbot/IA de uma das respostas anteriores, a própria automação pode responder e finalizar a demanda sem a necessidade de intervenção humana. Isso reduziria o gargalo no atendimento e os agentes teriam tempo para demandas mais complexas;
4) Fornecendo treinamento adicional à equipe para melhorar suas habilidades de atendimento ao cliente e comunicação com práticas de gerenciamento de tempo eficazes para garantir que as demandas sejam atendidas de maneira mais ágil;
5) Criação de KPI's para medir o progresso na redução de demandas perdidas com monitoramento regular;
6) Realizar análises para identificar as razões pelas quais as demandas são perdidas e se for o caso, ajustar as estratégias com base nesses insights;
7) Solicitar feedback dos clientes para entender melhor suas necessidades e expectativas, isso pode ajudar a identificar áreas de melhoria no atendimento;
8) Estabelecer um plano de contingência para lidar com situações de sobrecarga inesperada de demandas, garantindo que nenhuma seja perdida durante picos de atividade;
9) Implementação da pesquisa NPS para acompanhar o nível de satisfação a longo prazo e do sentimento geral da marca.

5 - De forma geral, olhando para área como o seu negócio, monte um plano de ação para que esse time seja mais eficiente e com mais qualidade

R.:
Melhorar a eficiência e a qualidade do atendimento ao cliente é fundamental, observando o dashboard e nos baseando nos dados apresentados podemos apontar alguns pontos de ação para melhoria contínua:

Ponto 1: Elencar o top 10 de problemas que são recorrentes no atendimento e identificar se possuem problemas no produto. Caso seja, estruturar        números e evidências e solicitar ao time de produto/engenharia uma melhoria das features deixando as funções mais claras e até mesmo corrigindo bugs que levam o cliente a entrar em contato com o atendimento;
Ponto 2: Criar dashboard/KPI's de métricas (Tempo médio de atendimento, Tempo médio de espera do atendimento; Pontuação CSAT; Customer Health Score; Net Promoter Score (NPS); Taxa de retenção dos clientes; Taxa de abandono) para identificar e tratar possíveis gargalos;
Ponto 3: Definir metas claras específicas, mensuráveis, alcançáveis, relevantes e com prazo para melhorar o tempo de atendimento ao cliente, investindo em treinamento contínuo para a equipe;
Ponto 4: Melhoria das documentações que os atendentes utilizam para resolver problemas, revisando essas documentações periodicamente para garantir que o passo a passo da resolução do problema esteja sempre atualizado e consequentemente mais assertivo;
Ponto 5: Criar chatbots/IA para automatizar tarefas repetitivas e que os clientes possam resolver os atendimentos sem intervenção humana;
Ponto 6: Se basear em dados para identificar tendências, padrões e métricas que precisem de melhoria, ajustando continuamente as estratégias com base nos insights obtidos através desses dados de atendimento ao cliente.

Link: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/6605712877054562/4421081028949028/6665719610652/latest.html
