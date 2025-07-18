# Análise de E-commerce Brasileiro Olist


Formação em Business Intelligence IEFP:

Durante a formaão de 300 horas em Business Intelligence do IEFP, desenvolvi competências técnicas que me pertimitram transformar dados em informação estratégica voltada 
à tomada de decisão com grande volume de dados. Nessa formação aprendi a utilizar a ferramenta do Power BI, entre outros, que permite recolher, armazenar e transformar dados, com fooco na criação de dashboard interativos, dinâmicos e colaborativos. Ao longo da formação tive a oportunidade de afundas nos seguintes temas:

- Aplicação de ferramentas para suporte à decisão
- Planemanento de soluções de armazenamento de dados
- Integração e tranformação de dados de múltiplas origens
- Construção de modelos dimensionais
- Criação de relatórios e dashboards eficazes
- Storytelling com dados e visualização estratégica de informação
- Execução de análises avançadas orientadas ao negócio

Desenvoli vários projetos práticos, baseados em conjunto de diversos dados que permitem aplicar todo o ciclo de desenvolvimento de uma análise de Business Intelligence, desde a modelação até à entrega de insights visuais.

Um dos maiores projetos foi baseado na base de dados da E-commerce Brasileiro "Olist", sobre o qual gostaria de aprofundar mais.


# 🛍️ Projeto Final – Análise de E-commerce Brasileiro (Olist)

Este projeto foi desenvolvido como parte da UFCD 10804 – Projeto de Business Intelligence. Utilizando uma base de dados real da plataforma Olist (disponível no Kaggle), o objetivo foi criar um dashboard analítico no Power BI que oferecesse insights estratégicos sobre vendas, logística e comportamento do consumidor.

---

## 🎯 Objetivo do Projeto

Desenvolver um painel de Business Intelligence interativo que permita acompanhar o desempenho de vendas da Olist, identificar gargalos e oportunidades, e apoiar a tomada de decisão estratégica com base em dados reais de e-commerce.

---

## 🗂️ Etapas Realizadas

### 1. Planeamento do Projeto

Iniciei o trabalho com um planejamento estruturado, definindo objetivos, prazos, entregas e recursos necessários. Essa etapa foi essencial para guiar todas as fases do projeto com clareza e foco.

### 2. Elaboração do Documento de Projeto

Elaborei um documento técnico contendo:
- **Escopo do Projeto**: definição dos limites e objetivos da análise;
- **Dicionário de Dados**: descrição dos campos, tabelas e relações no modelo de dados;
- **Protótipo Inicial**: criação de um wireframe de forma manual, antecipando o layout e os elementos visuais do painel no Power BI, para aceite da direção.

### 3. Modelagem e Análise de Dados

A análise prática começou com a importação dos arquivos CSV no Power BI. Modelei os dados com base em uma estrutura estrela, relacionando tabelas fato e dimensão. Em seguida, criei medidas DAX para compor os principais KPIs, incluindo:

- Receita Total
- Número de Pedidos
- Ticket Médio por Pedido
- Tempo Médio de Entrega
- Avaliação Média dos Clientes
- Receita por Categoria e Região

### 4. Criação do Dashboard e Design Visual

Construi o painel no Power BI focando na clareza e interatividade. Para enriquecer a apresentação, desenvolvi um fundo personalizado no **Figma**, integrando elementos visuais que reforçam a identidade da Olist e melhoram a experiência do usuário.

---

## 📈 Insights Obtidos

- Regiões e categorias com maior volume de vendas;
- Impacto do tempo de entrega na satisfação dos clientes;
- Análise de sazonalidade e evolução mensal das vendas;
- Comportamento de pagamento dos consumidores.

---

## 🛠️ Ferramentas Utilizadas

- Power BI Desktop  
- DAX  
- Excel  
- Figma  
- Kaggle  

🔗 [Base de dados – Kaggle: Olist Brazilian E-commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)


Dashboard - Análise de Vendas da Olist
<img src="page "Olist_Svetlana_page-0001.jpg" alt="Objetivos" width="800"> </p>

Aqui foram definidos os principais objetivos a  atingir com a análise da base de dados da E-Commerce Brasileiro Olist, entre os quais obter informações sobre os clientes, definidr o Top 10 de clientes, vendedores e regiões com maiores vendas, análise de vendas, produtos e avaliações dos mesmos por parte dos clientes.

<img src="Olist_Svetlana_page-0002.jpg" alt="Clientes" width="800"> </p>
O dashboard da Olist mostra que a empresa possui 99,44 mil clientes e 112,65 mil pedidos realizados. Houve crescimento significativo entre 2016 e 2018, com destaque para o aumento de clientes e pedidos principalmente em 2017 e 2018. O valor médio de compra é de R$ 140,64. O tempo de espera diminuiu ao longo dos anos, com média total de -11,88 dias. A região Sudeste lidera em volume de vendas, enquanto a região Norte apresenta o maior tempo de espera.

<img src="Olist_Svetlana_page-0003.jpg" alt="Vendas" width="800"> </p>
O estado de São Paulo lidera tanto em número de vendedores quanto de clientes, com ampla vantagem sobre os demais. No total, o valor das vendas entre 2016 e 2018 somou R$ 16 milhões, com destaque para 2018, que sozinho movimentou mais de R$ 8,6 milhões.
O ticket médio por pedido foi crescendo ao longo dos anos: R$ 0,58 (2016), R$ 72,39 (2017) e R$ 87,61 (2018), totalizando R$ 160,58. O mapa à direita reforça a concentração de vendas nas regiões Sudeste e Sul do Brasil, principalmente em SP, RJ e MG.

<img src="Olist_Svetlana_page-0004.jpg" alt="Avaliações" width="800"> </p>
A plataforma recebeu um total de 99,22 mil avaliações, sendo 57 mil com 5 estrelas e 11 mil com 1 estrela, resultando em uma média geral de 4,09.
As avaliações 5 estrelas são as mais frequentes ao longo dos meses, com destaque nos meses de março a agosto.
Na comparação regional, todas as regiões melhoraram suas notas de 2016 para 2017. No entanto, a região Nordeste apresentou queda contínua em 2017 e 2018, enquanto Centro-Oeste, Sudeste e Sul mantiveram notas mais altas e estáveis a partir de 2017.

<img src="Olist_Svetlana_page-0005.jpg" alt="Produtos" width="800"> </p>

Dentro dos produtos vendidos, destaca-se a categoria de cama, mesa_banho, automotivo e beleza_saude, como produtos com maior procura, especialmente no mês de novembro. É percetível que a queda de vendas ocorre no mês de setembro, possivelmente devido às promoções do mês de agosto. Destaca-se que a categoria cama_mesa_banho atingiu o valor rotal de venda de 590.280,44, com o valor médio de venda de 113,02 R$.

<img src="Olist_Svetlana_page-0006.jpg" alt="Global" width="800"> </p>
Entre 2016 e 2018, o valor total de pagamentos realizados na Olist somou aproximadamente R$ 16,01 milhões, sendo o cartão de crédito o método de pagamento mais utilizado, seguido por boleto, voucher, cartão de débito e métodos não definidos. A maioria dos pedidos (110.197) foi concluída com sucesso (entregues), com volumes significativamente menores nos status de enviados, cancelados, faturados, processando, indisponíveis e aprovados. Os produtos também refletiram essa tendência, com predominância de entregas concluídas. Em termos de faturamento por status do pedido, os pedidos entregues geraram a maior receita, totalizando mais de R$ 15,4 milhões. Regionalmente, a maior parte das vendas ocorreu no Sudeste (R$ 10,34 milhões), seguido pelas regiões Sul, Nordeste, Centro-Oeste e Norte.
