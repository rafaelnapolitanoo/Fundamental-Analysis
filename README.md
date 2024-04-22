# Fundamental Analysis
 
um dos meus projetos pessoais que me auxiliará a fazer a analise fundamentalista de uma empresa antes de investir (um merge entre programação e economia).

O código deverá Entender os fundamentos financeiros de:

Lucro líquido, Receita, Margem de lucro ,ROE (retorno sobre patrimônio líquido), EBITDA (lucro antes de juros, impostos, depreciação e amortização) ,Endividamento (Dívida/ Patrimônio líquido), Liquidez (índice de liquidez corrente), Múltiplos de avaliação (P/L, P/B, etc.)

Se inicia com um input para o usuario onde o mesmo digitara a tag da ação desejada, logo mais ultilizando uma API pegaremos todos os indicadores dessa acao (oriundas do site fundamentus) e armazenaremos elas.

Após ja ter os valores minimos de cada um dos indicadores desejados (todos fixos em uma função) 
fará um comparativo por meio de graficos entre a ação escolida e outras 3 do mesmo setor, logo, teremos uma comparação justa entre os indicadores de cada uma.

Ultilizarei a biblioteca pandas para analisar e tratar os diversos dados recebidos após a requisição e usarei matplotilib ou seaborn para execução dos graficos.

Pretendo ,ao finalizar, transformar em um arquivo executavel com aplicação gráfica do tkinter ou então colocar em um dominio para o código não ficar tão lento e demorado.
