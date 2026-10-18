<img width="1342" height="589" alt="Captura de tela 2026-10-18 124937" src="https://github.com/user-attachments/assets/744771a1-d9ce-4f8a-8652-1a89d777cb60" />
# Dashboard_porsche_html
1. Quais perguntas de negócio foram escolhidas e por quê?
Foram selecionadas três perguntas principais para transformar os dados de vendas em informações úteis para a gestão comercial.
1. Quais modelos concentram o maior faturamento e como o preço médio varia conforme o modelo e o ano do veículo?
Essa pergunta permite identificar os modelos que mais contribuem para a receita, comparar preços médios e compreender quais categorias de veículos têm maior relevância financeira.
2. Como se distribuem as vendas e o faturamento por Estado e Cidade, e quais modelos são preferidos em cada região?
Essa análise ajuda a identificar os mercados geográficos com maior volume de vendas e faturamento, além de revelar possíveis preferências regionais que podem orientar estratégias comerciais.
3. Qual é a participação de cada método de pagamento nas vendas e no faturamento, e como essa escolha varia conforme a faixa de preço?
Essa pergunta permite compreender os meios de pagamento mais utilizados, identificar diferenças entre as faixas de preço e apoiar decisões relacionadas às condições de pagamento oferecidas aos clientes.
Para responder a essas perguntas, a dashboard apresenta quatro KPIs principais: faturamento total, ticket médio, unidades vendidas e método de pagamento mais utilizado. Também utiliza gráficos interativos, filtros e uma tabela detalhada para facilitar a análise.
2. Qual foi o prompt utilizado e o que mudou até a versão final?
O prompt final foi desenvolvido progressivamente, partindo de uma dashboard comercial da Porsche e evoluindo para uma solução executiva mais completa.
Prompt consolidado:
Crie uma dashboard executiva e interativa em um único arquivo HTML, utilizando Tailwind CSS para o design e Chart.js para os gráficos, com base em uma planilha de 100 vendas de veículos Porsche.
Utilize um tema escuro premium, com identidade visual inspirada na Porsche e componentes de organização semelhantes aos do Power BI.
Inclua quatro KPIs: faturamento total, ticket médio, unidades vendidas e método de pagamento mais utilizado.
Adicione filtros interativos por Estado, Modelo, Ano do veículo e Método de pagamento. Todos os indicadores, gráficos e tabelas devem ser atualizados dinamicamente conforme os filtros selecionados.
Apresente quatro gráficos principais: faturamento por modelo, unidades e faturamento por Estado, distribuição do faturamento por método de pagamento e evolução do preço médio por modelo e ano do veículo.
Inclua análises complementares por Cidade, preferência regional de modelos e método de pagamento por faixa de preço.
Adicione uma galeria com imagens reais dos modelos Porsche, atualizada conforme os filtros e o modelo selecionado. Utilize imagens de alta resolução disponíveis na web, com alternativas caso alguma fonte não carregue.
Finalize com uma tabela responsiva, busca rápida, paginação e exportação dos registros filtrados em CSV. Entregue o código HTML, CSS e JavaScript completo em um único arquivo chamado index.html.




Principais mudanças até a versão final:
- A estrutura inicial foi ampliada de uma análise de vendas por cidade e modelo para uma visão executiva com quatro KPIs e quatro gráficos.
- Os filtros foram organizados em uma barra superior e conectados aos elementos da dashboard.
- O visual foi refinado com tema escuro, tons de vermelho, tipografia elegante e componentes inspirados no Power BI.
- Foi adicionada uma galeria de imagens por família de veículos Porsche, com fontes externas e alternativas de carregamento.
- Foram incorporadas análises complementares por cidade e faixa de preço, além de pesquisa, paginação e exportação CSV.
3. Que tratamento a base precisou antes de ir para a IA?
A planilha já possuía uma aba chamada Sanitized, com dados preparados para análise. Portanto, não foi necessário reconstruir a base do zero.
O tratamento realizado para a dashboard envolveu:
- Seleção e mapeamento: foram utilizados os 100 registros e os campos relevantes, convertendo os nomes das colunas em propriedades consistentes para o JavaScript.
- Datas inválidas: 24 registros apresentavam datas de venda inválidas. Esses valores foram representados como nulos, sem inventar datas para completar a base.
- Valores monetários: os preços foram mantidos como valores numéricos para permitir cálculos de faturamento e ticket médio.
- Categorias: foram preservados os nomes dos modelos, as cidades, os estados e os métodos de pagamento existentes na fonte.
- Dados incompletos: o campo de status apresentava 23 valores ausentes ou problemáticos, incluindo registros classificados como Não informado e um valor #NAME?.
A base contém cidades e estados dos Estados Unidos, e os valores foram tratados como dólares americanos (US$), não como reais. Essa interpretação foi mantida para evitar uma conversão monetária sem taxa de câmbio definida.
Os registros com datas inválidas foram mantidos nos totais e nas análises que não dependem da data. Não foram inventados valores para corrigir essas inconsistências.
4. Foi utilizado o ChatGPT com Canvas, um agente com skill ou os dois?
Foi utilizado o ChatGPT diretamente para desenvolver o código da dashboard, com apoio de ferramentas de execução e geração de arquivos.
Não foi utilizado o Canvas nem um agente especializado com skill. O resultado foi produzido como um arquivo HTML contendo a estrutura da interface, os estilos, os dados incorporados e a lógica JavaScript para filtros, gráficos e tabela.
5. Qual é o endereço da dashboard publicada?
A dashboard foi gerada como arquivo HTML, mas não foi publicada em um endereço público na internet. Portanto, ainda não existe uma URL pública de acesso.
O arquivo final pode ser acessado aqui:
Abrir ou baixar a dashboard — index.html
