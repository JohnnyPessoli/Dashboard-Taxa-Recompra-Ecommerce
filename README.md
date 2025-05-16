# Relatório de Vendas

## Descrição
Este dashboard, desenvolvido em **Power BI**, analisa detalhadamente os dados de vendas, com foco especial na recompra e na segmentação de clientes. O relatório integra informações provenientes de **planilhas Excel** e de um **banco MySQL**, utilizando um rigoroso processo de **ETL** para garantir a qualidade e a consistência dos dados. Os indicadores calculados – como tempo médio de recompra, ticket médio, e a proporção de clientes novos versus recorrentes – são essenciais para embasar decisões estratégicas e ajustar ações de marketing e fidelização.

## Como Foi Desenvolvido
- **Fontes de Dados:** Dados de vendas foram extraídos de planilhas Excel e registros do banco MySQL.
- **ETL:** No Power BI, foram aplicados processos de limpeza, transformação e unificação dos dados, garantindo que todas as informações estejam padronizadas e atualizadas.
- **Modelagem e Cálculos dos Indicadores:**
  - **Tempo Médio de Recompra:** Calculado a partir da diferença entre as datas das compras sucessivas, permitindo identificar a frequência de recompra e avaliar a fidelidade dos clientes.
  - **Ticket Médio:** Derivado da divisão do total de vendas pelo número de transações, auxiliando a mensurar o valor médio gasto por cliente.
  - **Segmentação de Clientes:** Os clientes foram categorizados como novos ou recorrentes com base em seus históricos de compra, possibilitando análises comparativas e a identificação de padrões de comportamento.
- **Visualizações:** Foram utilizadas diversas representações gráficas, incluindo gráficos de linhas e barras, para ilustrar a evolução das vendas, a distribuição dos clientes por categoria e os principais indicadores de performance.

## Resultados
- **Insights sobre Recompra:** A análise dos cálculos permite identificar o tempo médio de recompra, contribuindo para entender a fidelidade do cliente e definir estratégias de retenção.
- **Aprimoramento de Estratégias:** Os indicadores, como o ticket médio e a segmentação de clientes, fornecem subsídios para o desenvolvimento de campanhas personalizadas, visando a maximização das vendas e o aumento da recorrência.
- **Monitoramento de Performance:** O dashboard possibilita o acompanhamento contínuo do desempenho mensal, facilitando a identificação de tendências de crescimento ou declínio e permitindo ajustes rápidos na estratégia de vendas.

## Screenshots
![image](https://github.com/user-attachments/assets/150b1f4d-3b23-414c-901c-dabf5f64e101)

## Como Executar
1. Abra o arquivo `.pbix` no Power BI Desktop.
2. Configure as conexões para as fontes de dados (Excel e MySQL).
3. Clique em **Refresh** para atualizar os dados.
4. Navegue pelas páginas do relatório para visualizar os indicadores e segmentações.


