🚀 Passo a Passo do Projeto – Copa do Mundo
🧠 1. Definição do Problema (ANTES de abrir o Excel)

Não pule isso.

Defina perguntas claras:

Quais seleções foram mais dominantes na história?
O número de gols aumentou ao longo do tempo?
Existe algum padrão de domínio por continente?
Quem são os jogadores mais consistentes?

👉 Isso guia todo o projeto.

📂 2. Entendimento dos Dados

Abra seus arquivos Excel e analise:

Quais tabelas você tem?
Jogos
Jogadores
Times
Edições
Quais colunas existem?
Tem dados faltantes?
Tem duplicados?

👉 Aqui você começa a pensar como modelador de dados.

🧹 3. Limpeza e Tratamento (Excel)

Aqui você transforma dados “crus” em dados utilizáveis.

No Excel:
Remover duplicados
Corrigir nomes inconsistentes (ex: “Brazil” vs “Brasil”)
Padronizar datas
Criar colunas novas:
Ano da copa
Total de gols por jogo
Resultado (vitória/empate/derrota)
Continente do time (manual ou tabela auxiliar)

👉 Use:

PROCV / XLOOKUP
Tabelas estruturadas
Filtros e validação
🧱 4. Modelagem dos Dados (MUITO IMPORTANTE)

Pense como um mini Data Warehouse:

Estrutura ideal:
Fato_Jogos
Data
Time A
Time B
Gols
Dim_Time
Nome do time
Continente
Dim_Jogador
Dim_Edicao

👉 Relacionamentos depois no Power BI.

💡 Esse passo é o que mais diferencia júnior de iniciante.

📤 5. Importação para o Power BI
Importar os arquivos tratados
Conferir tipos de dados
Criar relacionamentos entre tabelas

👉 Exemplo:

Fato_Jogos → Dim_Time
Fato_Jogos → Dim_Edicao
📐 6. Criação de Métricas (DAX)

Agora começa a análise de verdade.

Exemplos:

Total de gols
Média de gols por jogo
Vitórias por seleção
Taxa de vitória
Participações em Copas

💡 Diferencial:

Ranking dinâmico de seleções
Crescimento de gols ao longo do tempo
📊 7. Construção do Dashboard

Monte páginas com propósito:

Página 1 – Visão Geral
Total de copas
Total de gols
Seleção com mais títulos
Página 2 – Seleções
Ranking
Vitórias
Comparação entre países
Página 3 – Evolução Histórica
Gols por edição
Tendências ao longo dos anos
Página 4 – Jogadores (se tiver dados)
Artilheiros
Participações
🎯 8. Geração de Insights

Essa é a parte mais ignorada (e mais importante).

Exemplos:

“Seleções europeias dominaram após 2000”
“Número médio de gols aumentou após X edição”
“Brasil tem maior consistência, não só títulos”

👉 Coloque esses insights no README.

🖼️ 9. Documentação do Projeto (GitHub)

No seu repositório:

Explicar objetivo
Explicar dados
Explicar processo
Colocar prints do dashboard