# Sobre Mim

Olá, sou Carlos Willian. Tenho vasta experiência na área de faturamento hospitalar, atuando na gestão, análise e auditoria das contas médicas, sempre em conformidade com as normas e exigências dos convênios. Sou formado em Administração pelo Instituto Federal da Paraíba e possuo certificações nas áreas de Gestão e Tecnologia.

Apaixonado por tecnologia e ciência, busco constantemente utilizar a tecnologia ao meu favor para resolver problemas e otimizar processos. Estou sempre atento às demandas do mercado de trabalho para a minha área, buscando adaptar e expandir minhas habilidades conforme necessário. Utilizo dados e ferramentas tecnológicas para criar soluções eficientes e estratégicas, contribuindo para a tomada de decisão informada e a melhoria contínua dos processos no setor de faturamento.

Meu objetivo é contribuir para o desenvolvimento e inovação na área da saúde, utilizando dados e tecnologia para otimizar resultados e melhorar a qualidade dos serviços prestados.


# Experiências Profissionais

Auxiliar de Contas Médicas | Hospital Nossa Senhora das Neves | Janeiro de 2019 - Hoje

Atuo na análise detalhada do processo de faturamento, investigando as causas de pendências hospitalares e otimizando o ciclo financeiro do hospital.

  **Minhas responsabilidades incluem:**

 - **Monitorar e analisar o processo de faturamento:** Acompanho de perto cada etapa do pagamento, identificando possíveis falhas ou atrasos para garantir a eficiência do processo.
- **Investigar as causas das pendências:** Realizo uma análise aprofundada para determinar os motivos que impedem o faturamento de contas médicas, coletando informações de diversas áreas do hospital.
- **Tratar e resolver as pendências:** Com base na investigação, busco soluções eficientes para solucionar os problemas encontrados, garantindo que as contas sejam processadas corretamente.
- **Analisar a jornada do paciente no ciclo financeiro hospitalar:** Compreendo a trajetória da conta do paciente no sistema financeiro do hospital, desde a admissão até o faturamento, para obter uma visão completa da situação e identificar áreas de melhoria.
- **Analisar OPMEs (Órteses, Próteses e Materiais Especiais):** Examino o uso de OPMEs no hospital, resolvendo pendências de inadimplência e fornecendo feedback às áreas responsáveis quando o faturamento de OPMEs não é bem executado.
- **Emitir relatórios gerenciais:** Elaboro relatórios precisos e concisos, com base em dados coletados, para fornecer insights e informações relevantes sobre o processo de faturamento de contas médicas, auxiliando na tomada de decisões estratégicas.

Meu objetivo é garantir que todas as contas médicas sejam faturadas de maneira eficiente e precisa, contribuindo para a otimização dos resultados financeiros do hospital.

 ## Outras Experiências:
 
Estagiário de Cobranças | Junho de 2018 - Julho de 2018 (2 meses)
Estagiário de Contabilidade | Outubro de 2015 - Junho de 2018 (2 anos e 9 meses)
Estagiário de Vendas | Janeiro de 2012 - Dezembro de 2014 (3 anos) 

# Formação Academica

**Bacharel Em Administração | IFPB - Instituto Federal de Educação da Paraíba | 2015 - 2021**

### Cursos em Andamento

*  EBA (Estatística do Básico ao Avançado) - Renata Biaggi

### Cursos Concluídos

* Introdução à Gestão de Projetos (ENAP - 2020)
* Análise de Dados e Power BI (Escola Conquer - 2022)
* Business Intelligence (FIAP - 2021)
* Saúde Suplementar (ENS - 2022)
* Planejamento Estratégico - (Escola Conquer – 2022)
* Gestão Tática e Operacional - (Escola Conquer – 2022)
* Gestão Financeira (Escola Conquer – 2022)
* Gestão Para Resultados (Escola Conquer – 2022)
* Excel 2019: Gestão e Análise de Dados – (LinkedIn – 2022)
* Desenvolvimento Pessoal (Alura - 2023)
* Business Agility (Alura - 2023)

# Projetos

### Análise de Dados com SQL do Brasileirão (2010-2019)

A análise de dados do Brasileirão (2010-2019) utilizando SQL e Google BigQuery revelou insights sobre o total de gols, a média de idade dos jogadores e os maiores públicos anuais. Os dados foram visualizados em gráficos no Excel, facilitando a compreensão das tendências do campeonato. Os resultados fornecem uma compreensão profunda do Brasileirão, auxiliando na tomada de decisões estratégicas e no engajamento do público.


  #### Gols Por Ano

```SQL
SELECT ano_campeonato,
SUM(gols_man + gols_vis) AS total_gols
FROM "basedosdados.mundo_transfermarkt_competicoes"."brasileirao_serie_a"
WHERE ano_campeonato BETWEEN 2010 AND 2019
GROUP BY ano_campeonato;
```
 #### Média de idade por ano
 
```SQL
SELECT ano_campeonato, AVG(subquery.total_idade) AS media_total_idade
FROM (
	SELECT ano_campeonato, (idade_media_titular_man + idade_media_titular_vis)/2 AS total_idade
	FROM basedosdados.mundo_transfermarkt_competicoes.brasileirao_serie_a
	WHERE ano_campeonato BETWEEN 2010 AND 2019
) AS subquery
GROUP BY ano_campeonato;
```
 #### Média de idade por ano
 
```SQL
 SELECT ano_campeonato, MAX(publico) AS Maior_publico
FROM "basedosdados mundo_transfermarkt_competicoes. 'brasileirao_serie_a'
WHERE ano_campeonato BETWEEN 2010 AND 2019
GROUP BY ano_campeonato;
```

### Painel Hospitalar de Análise de Cirurgias

O Painel Hospitalar de Análise de Cirurgias foi desenvolvido para organizar e analisar dados de cirurgias, fornecendo insights estratégicos. Utilizando Excel e dados gerados pelo ChatGPT, o painel apresenta estatísticas e tendências através de tabelas dinâmicas e gráficos interativos. Resultados incluem melhor organização dos dados, identificação de tendências, e tomada de decisões mais eficazes, beneficiando a gestão hospitalar e o atendimento aos pacientes. Habilidades envolvidas incluem análise de dados, design de painéis e visualização de dados.

### Case de Análise de Dados: Dashboard de Indicadores de Glosa

O desenvolvimento de um dashboard interativo para análise de indicadores de glosa visou identificar oportunidades de redução de custos e otimização de processos. A ferramenta, criada para uma empresa fictícia, utiliza dados detalhados sobre glosas e apresenta visualizações intuitivas e filtros flexíveis. Os principais resultados incluem a identificação de padrões e motivos de glosa, fornecendo insights estratégicos para a tomada de decisões, redução de custos e melhoria de processos internos. O projeto destacou a importância da análise de dados e visualização para a gestão eficiente de pagamentos.

### Case de Portfolio: Dashboard de Pendências Administrativas Hospitalares em Power BI

O dashboard de pendências administrativas hospitalares em Power BI foi desenvolvido para monitorar o status das pendências, auxiliando na gestão financeira e operacional do hospital. Ele apresenta dados complexos de forma clara, permite análise e segmentação, e oferece uma experiência interativa. As soluções incluem gráficos de faturamento, pendências mensais e maiores contas por paciente, além de uma visualização hierárquica por setor e um painel detalhado de pendências. Os resultados incluem monitoramento em tempo real, decisões mais eficazes, melhor controle financeiro e comunicação aprimorada. Os benefícios abrangem gestão financeira otimizada, operacionalidade aprimorada, melhor experiência para os pacientes e melhoria da imagem do hospital.

### Case de Análise de Dados: Dashboard do Brasileirão 2006 a 2022 

A análise dos dados do Campeonato Brasileirão Série A de 2006 a 2022 revelou que Corinthians, Palmeiras, São Paulo e Flamengo se destacaram com 3 títulos cada. Internacional e Santos foram os mais vezes vice-campeões, enquanto o Avaí teve mais rebaixamentos (5). São Paulo teve o melhor aproveitamento nos pontos corridos (54,3%). A região Sudeste liderou em número de representantes e títulos, com São Paulo como o estado com mais clubes na Série A. A análise abordou campeões anuais, clubes rebaixados, desempenho anual e variações regionais e estaduais.

###### Habilidades 

| Tecnologia        | Nível           | Experiência |
|:------------------|:----------------|:------------|
| Excel             | Avançado        | 5 Anos      |
| SQL               | Básico          | 1 Ano       |
| Power BI          | Intermediário   | 2 Anos      |
| Python            | Básico          | 1 Ano       |

