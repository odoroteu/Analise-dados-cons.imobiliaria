Prezado, 

O projeto a seguir trata-se de uma análise dados fictícios baseados na metodologia de uma empresa correspondente/parceira bancária no ramo imobiliário. 

Utilizei a estrutura de armazenamento de dados utilizada na última empresa em que trabalhei para realizar o dashboard (devido a LGPD* não pude utilizar os dados reais).


Passos realizados para construção do Dashboard a seguir:

1° Tratamento dos dados recebidos, em excel, via PowerQuery.
2° Modelagem dos dados, relacionamento entre as tabelas existentes. 
3° Criação das principais métricas utilizadas neste mercado, via DAX
4° Criação dos visuais (gráficos)

OBS: O background utilizado gerei com auxilio da ferramenta 

OBJETIVO:
Como a remuneração de empresas desse segmento é em baseado no valor de financiamento os indicadores as métricas são baseados neste valor. 

Para fornecer informações relevantes ao gestor na tomada de informações: 

Bancos:
Verificar quais os bancos possuem maior volume de financiamento. Esta informação nos permite inferir quais o bancos com melhores condições (taxa de juros efetiva, nível de restrição, percentual de financiamento permitido). 

Fonte de Cliente(Canais de Cliente):
Estabelecido as formas de chegada do cliente, conseguimos verificar o volume por segmentação. Através desta informação podemos verificar a contribuição por segmentação, informação extremamente relevante para empresa para tomada de decisões em relação a cada nicho mercado e como agir. 

Corretor: 
Semelhante ao visto em forma de cliente, conseguimos verificar os principais corretores imobiliários. A informação do corretor traz um pouco mais de detalhamento a informação (algo mais específico), por se tratar de mercado imobiliário, podemos ter corretores autônomos, imobiliárias, desta forma conseguimos analisar aqueles mais ativos com a empresa seguir.


Baseado nestas informações, criamos os seguintes informações:

Visual 01 (2025)

Baseado na meta estabelecida pela empresa, apresentamos baseado nas informações citadas as seguintes informações


Acumulado baseado até o mês escolhido. 
- O  quanto já foi realizado da meta em percentual
- O volumen de financiamento total até o presente mês escolhido
- N° de processos(Quantidade de clientes) até o momento
- Ticket Médio: O valor médio de financiamento por cada processo, informação muito importante para o setor comercial ter uma ideia de quantos cliente mensalmente precisa conquistar.
- Valor da meta definida.

Já através dos gráficos apresentamos:
Comparativo mês x mês do ano atual com o ano anterior
Acumulado do volume de financiamento por banco
Acumulado do volume de financiamente por fonte de indicação
Ranking dos principais corretores até o momento definido

Já no visual 02 (Geral), apresentamos:

Coloquei esse nome "Geral" por se tratar de uma visualização mais ampla. 

Realizmos o comparativo do volume de financiamento, número de processos e ticket médio, tanto em valor, como em % com o ano anterior.

Já nos gráficos apresentamos o volume de financiamento de toda base de dados, por ano. 

Realizamos o comparativo do ano atual com o ano anterior de forma geral, sem filtrar os meses que não foram selecionados. Na parte de banco, apresentamos da mesma forma. 


Já no cenário de Fonte de Cliente apresentamos comparando com a meta.

