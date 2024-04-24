# Fundamental Analysis
 
um dos meus projetos pessoais que me auxiliará a fazer a analise fundamentalista de uma empresa antes de investir (um merge entre programação e economia).

O código deverá Entender os fundamentos financeiros de:

Lucro líquido, Receita, Margem de lucro ,ROE (retorno sobre patrimônio líquido), EBITDA (lucro antes de juros, impostos, depreciação e amortização) ,Endividamento (Dívida/ Patrimônio líquido), Liquidez (índice de liquidez corrente), Múltiplos de avaliação (P/L, P/B, etc.)

Se inicia com um input para o usuario onde o mesmo digitara a tag da ação desejada, logo mais ultilizando uma API pegaremos todos os indicadores dessa acao (oriundas do site fundamentus) e armazenaremos elas.

Após ja ter os valores minimos de cada um dos indicadores desejados (todos fixos em uma função) 
fará um comparativo por meio de graficos entre a ação escolida e outras 3 do mesmo setor, logo, teremos uma comparação justa entre os indicadores de cada uma.

Ultilizarei a biblioteca pandas para analisar e tratar os diversos dados recebidos após a requisição e usarei matplotilib ou seaborn para execução dos graficos.

Pretendo ,ao finalizar, transformar em um arquivo executavel com aplicação gráfica do tkinter ou então colocar em um dominio para o código não ficar tão lento e demorado.



This personal project aims to assist in fundamental analysis of companies before investing, merging programming and economics. The code is designed to comprehend financial fundamentals such as net profit, revenue, profit margin, ROE (return on equity), EBITDA (earnings before interest, taxes, depreciation, and amortization), debt ratio (debt/equity), liquidity (current ratio), and valuation multiples (P/E, P/B, etc.). It starts with user input to select the desired stock ticker, using an API to fetch financial indicators from the Fundamentus website and storing them. Next, it compares the indicators of the selected stock with three others from the same sector using graphs, providing a fair comparison. The project employs the pandas library for data analysis and matplotilib or seaborn for graphs. The ultimate goal is to transform it into an executable file with a graphical interface using tkinter or host it on a domain for improved code efficiency.
