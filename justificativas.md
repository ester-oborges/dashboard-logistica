### Dashboard para Logística com Power BI

<img width="4150" height="2400" alt="mp4" src="https://github.com/user-attachments/assets/e329e94c-67bd-41d4-8efb-b2a5c96278ba" />

A proposta do exercício era revisar e reconstruir um dashboard problemático entregue para uma empresa de logística. O objetivo era identificar erros de visualização, legibilidade e organização das informações, justificando cada alteração realizada.

O dashboard precisava apresentar os seguintes KPIs:
1. Total de entregas no prazo por canal de entrega
2. Percentual de entregas antecipadas por equipe de entrega
3. Total de entregas por mês
4. Total de entregas dos Top 5 vendedores
5. Total de entregas com atraso por cidade
6. Percentual de entregas por status de entrega

O dashboard original apresentava diversos problemas de visualização e experiência do usuário, como excesso de informação condensada, falta de hierarquia visual, baixa legibilidade, gráficos inadequados para alguns tipos de dados, pouco espaçamento entre elementos e dificuldade para encontrar informações rapidamente.

Para tornar a leitura mais confortável e intuitiva, reduzi a densidade visual, permitindo que o usuário "batesse o olho" e captasse rapidamente os principais indicadores. Também criei espaçamentos mais equilibrados entre gráficos, textos e bordas, para trazer mais respiro para a composição visual.

Organizei os elementos seguindo uma hierarquia mais clara, exibindo primeiramente os principais KPIs e os botões de segmentação interativos. Dessa forma, o usuário identifica rapidamente os indicadores mais importantes e percebe imediatamente que existem filtros disponíveis para interação.

Cada gráfico foi escolhido pensando na melhor forma de leitura para aquele tipo de dado:
- **Gráfico de linha** <br>
  Utilizado para representar informações temporais, facilitando a percepção de evolução mensal das entregas.
- **Gráfico de rosca** <br>
  Aplicado em uma visualização com apenas 3 categorias. Isso evitou um gráfico visualmente carregado e melhorou a leitura proporcional dos dados.
- **Gráficos de barras e colunas** <br>
  Para melhorar a legibilidade e evitar sobrecarga visual, a escolha entre barras e colunas foi feita considerando o espaço necessário e a quantidade de informações nos eixos:
  - quando havia mais informações no eixo X → gráfico de colunas
  - quando havia mais informações no eixo Y → gráfico de barras
- **Tabelas complementares** <br>
  Foram adicionadas duas tabelas para enriquecer o dashboard:
  - a tabela de cidades com atraso exibe todas as cidades com entregas atrasadas, quantidade de atrasos por cidade, ordenação da maior para a menor quantidade e barra de rolagem para consulta completa.
  - a tabela top 5 vendedores exibe os IDs dos 5 vendedores que mais fizeram entregas, a quantidade de entregas de cada um e um rating por estrelas.

Obs: O sistema de rating foi desenvolvido com base em técnicas aprendidas durante o curso.

A variedade de formatos visuais também foi utilizada como ferramenta de navegação cognitiva, pois quando diferentes tipos de gráficos representam diferentes tipos de informação, o usuário consegue localizar dados mais rapidamente através da associação visual. <br> Exemplo: "A informação que procuro estava naquele gráfico de rosca." → Isso reduz o esforço visual e melhora a experiência de análise.

Por fim, foi aplicada uma segmentação interativa por botão permitindo ao usuário alternar entre os dados de 2019 e 2020. Todos os gráficos e indicadores interagem dinamicamente com esse filtro.
