# LegalDataScience

Análise de Eficiência de Casos Jurídicos - 

Visão Geral

Este projeto, desenvolvido para o escritório DL, utiliza técnicas de ciência de dados para analisar a eficiência de casos jurídicos, transformando dados em insights acionáveis que otimizam a alocação de recursos, priorização de casos e processos operacionais. O projeto segue a metodologia CRISP-DM e inclui um dashboard interativo construído com Streamlit, usando uma estética profissional em escala de cinza com um tom de uva bordô.

Objetivos


Identificar padrões em duração, custo, horas trabalhadas e taxa de sucesso de casos.



Segmentar casos por complexidade para alocação estratégica de advogados.



Propor melhorias operacionais, como automação de processos demorados.



Apoiar a tomada de decisão com análises baseadas em dados.

Metodologia CRISP-DM





Compreensão do Negócio: Definir questões como "Quais casos consomem mais recursos?" e "Como priorizar casos com maior taxa de sucesso?".



Compreensão dos Dados: Uso de dados fictícios simulando casos jurídicos (tipo, duração, custo, etc.).



Preparação dos Dados: Normalização de variáveis e criação de clusters de complexidade.



Modelagem: Análise exploratória e clustering com K-Means.



Avaliação: Geração de insights e validação com visualizações.



Implantação: Dashboard interativo com Streamlit para exploração dos dados.

Resultados

Insights





Alta Complexidade (~291 dias, ~R$14.859): Casos longos e caros, requerem advogados sêniores.



Média Complexidade (~103 dias, ~R$11.660): Casos rápidos, mas com custo elevado por hora, sugerindo foco em eficiência.



Baixa Complexidade (~207 dias, ~365 horas, ~R$7.604): Casos laboriosos, ideais para automação ou delegação a juniores.



Priorização: Casos de Contratos têm alta taxa de sucesso (~70%), sugerindo foco estratégico.

Visualizações

Gráficos em escala de cinza com tom de uva bordô, exibidos no dashboard e salvos em outputs/:





Gráfico 1: Duração média por tipo de caso (duration_by_case_type.png).



Gráfico 2: Custo vs. horas trabalhadas, segmentado por complexidade (cost_vs_hours.png).



Gráfico 3: Taxa de sucesso por tipo de caso (success_rate.png).



Gráfico 4: Heatmap de correlações (correlation_heatmap.png).



Gráfico 5: Distribuição de casos por complexidade e tipo (cluster_distribution.png).
