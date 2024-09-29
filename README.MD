# Projeto Aplicado I
## Análise dos Registros Públicos de Pagamentos de Diárias e Passagens em Viagens Realizadas a Serviço, dentro da Administração Pública Federal, em 2023.

## Identificação do projeto
Instituição: Universidade Presbiteriana Mackenzie

Aluno: Gustavo J. Fermiano

RA: 10440929

## Introdução
Anualmente, são gastos mais de R$ 1 bilhão de reais em pagamentos de diárias e passagens para atender servidores do quadro das instituições da Administração Direta e Indireta do Governo Federal. 

As diárias são valores pagos a servidores públicos para cobrir despesas relacionadas à alimentação, hospedagem e outras despesas de pequeno vulto, quando os servidores precisam atuar fora de suas sedes de trabalho. 

Regulamentadas por lei, essas diárias variam de acordo com o cargo, o destino, e principalmente, ao número de dias do afastamento. 

Já as passagens visam a cobrir os custos de transporte dos servidores durante estas viagens a serviço. Esses gastos podem ser intermediados por outras empresas, e aplicam-se a uma variedade de modais de transporte, em especial o modal rodoviário e as passagens aéreas. 

Essas despesas, destinadas a custear viagens a serviço, passam por diversas instâncias de controladoria e fiscalização, que visam a evitar o mau uso dos recursos públicos. Devido ao grande volume de viagens a serviços realizadas todos os anos, demandam-se análises mais sofisticadas para detectar pagamentos irregulares ou indevidos.

Este trabalho se propõe a realizar a Análise Exploratória de Dados do dataset de Diárias e Viagens a Serviço do ano de 2023, disponibilizado pelo Governo Federal através do Portal da Transparência, aprofundando-se e produzindo informações sobre a distribuição desses pagamentos ao longo deste exercício, pela perspectiva da estatística descritiva. 

## Proposta Analítica

O dataset utilizado está disponibilizado foi a base de dados de viagens a serviço do ano de 2023, disponibilizado no site do Portal da Transparência do Governo Federal: https://portaldatransparencia.gov.br. Este portal integra e apresenta dados de diversos sistemas utilizados pelo Governo Federal para a sua gestão financeira e administrativa. A frequência de atualização desses dados é diária, semanal ou mensal, a depender de cada tema investigado.

Este dataset, que compila as informações de passagens e diárias e serviços de todos os ministérios da administração pública federal, depende dos órgãos fornecidos pelos diferentes ministérios e órgãos da administração pública federal, e é mantido pela Controladoria Geral da União (CGU).

O link direto de acesso à base de dados utilizada é: https://portaldatransparencia.gov.br/download-de-dados/viagens/2023. O arquivo se encontra em formato *.CSV, possui origem aberta e pública, isto é, pode ser acessado por qualquer cidadão brasileiro, independentemente de solicitação. Sua sensibilidade é limitada pelos dados sigilosos, pois como já citado anteriormente, as leis federais, amparadas pela Constituição, determinam a publicidade como preceito geral, e o sigilo como exceção. Os dados provém dos registros de diárias no Sistema de Concessão de Diárias e Passagens – SCDP e a execução financeira é realizada pelo Sistema Integrado de Administração Financeira do Governo Federal – SIAFI.

Através da análise exploratória dos dados disponíveis no Portal da Transparência, o estudo tem como objetivo identificar padrões e insights dentro da base de dados de viagens a serviço do Governo Federal no ano de 2023. Conforme definido na etapa 1, as metas estabelecidas pelo estudo são: 

- Identificar os órgãos superiores com maiores gastos anuais com diárias e passagens. 	

- Identificar a dispersão dos pagamentos (média, mediana, desvio padrão), mapeando a distribuição da aplicação desses recursos por faixas de pagamento

- Identificar destinos mais frequentes das viagens a serviço.
	- Identificar a evolução destes pagamentos ao longo do ano de 2023, verificando fatores de sazonalidade ou contenção de recursos.
