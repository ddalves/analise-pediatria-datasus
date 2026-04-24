# analise-pediatria-datasus
Ao longo dos anos atuando na pediatria, eu e minha equipe sempre tivemos a percepção de um aumento da sazonalidade de doenças respiratórias durante os meses de outubro e novembro. Para sanar minha curiosidade e aproveitando meus treinamentos para aprendizado em Python, decidi extrair arquivos em CSV no TabNet (DataSUS) para validar ou descartar esta hipótese.

O desafio começou na extração de dados oficiais. Analisei as internações no estado de São Paulo por doenças do aparelho respiratório, focando:
     Período: Outubro e Novembro (2011 a 2025).
     Público: Faixa etária de menores de 1 ano até 9 anos.

     Desafios Técnicos (Data Wrangling)
Arquivos em CSV bruto vindos do DataSUS precisam de um tratamento rigoroso antes da manipulação. Utilizando a biblioteca Pandas, realizei:

Remoção de metadados (cabeçalhos e rodapés do TabNet).

Conversão de tipos de dados.

Tratamento de encoding (latin1) para leitura correta dos caracteres.

Para a perspectiva visual, utilizei a biblioteca Matplotlib para criar gráficos que transformam números em evidências, tornando-os mais compreensíveis e acessíveis.

🚀 Próximos Passos
Para entender melhor esta queda (ou talvez descobrir se, comparado aos outros meses daquele mesmo ano, houve na verdade um aumento relativo), pretendo continuar meu treinamento e aperfeiçoando minhas análises.

Este projeto abre portas para novas perguntas:

O comportamento foi o mesmo em outras faixas etárias?

Como se deu a retomada nos anos subsequentes (2021-2022)?

Sigo estudando para que a análise de dados seja uma ferramenta cada vez mais forte na minha prática profissional.
