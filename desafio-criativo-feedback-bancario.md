# Desafio Criativo: Extraindo Insights do Feedback de Clientes Bancários

## Passo 1: Defina a intenção

Quero que a IA analise feedbacks de clientes de um banco, coletados no aplicativo, na ouvidoria e em pesquisas de satisfação, para identificar os problemas mais recorrentes, os pontos positivos e as causas prováveis de insatisfação.

O resultado será usado pela equipe de Experiência do Cliente e pelas áreas de Produto e Atendimento para apoiar a priorização de melhorias no aplicativo, nas tarifas e nos canais de atendimento.

A entrega deve conter um resumo executivo, uma tabela com os principais temas (sentimento, frequência e prioridade), exemplos de comentários sem dados pessoais e recomendações práticas em ordem de prioridade.

O resultado será considerado bom se for claro, organizado, baseado apenas nos comentários fornecidos, sem inventar dados, e útil para decidir quais ações executar primeiro.

## Passo 2: Adicione contexto e restrições

Contexto: Estou trabalhando com feedbacks de clientes bancários relacionados ao aplicativo, ao Pix, às tarifas e ao atendimento (chat, SAC e ouvidoria).

Dados disponíveis: A base contém data do comentário, canal de origem, texto do feedback, produto ou serviço citado e nota de satisfação de 1 a 5. Dados pessoais, como nome, CPF e número de conta, já foram removidos ou devem ser ignorados.

Critérios de análise: A IA deve classificar os feedbacks por tema, sentimento (positivo, neutro ou negativo), urgência (alta, média ou baixa), canal e possível impacto na experiência do cliente.

Cuidados e restrições:

- Use apenas os dados fornecidos.
- Não invente números, causas ou conclusões.
- Não exponha dados pessoais ou sensíveis; se aparecerem, substitua por [DADO OMITIDO].
- Não ignore comentários negativos nem destaque só os elogios.
- Não tire conclusões sem evidência nos comentários.
- Se houver informação insuficiente, indique a limitação.
- Use linguagem simples, direta e voltada para tomada de decisão.

## Passo 3: Prompt final

Atue como analista de dados e de experiência do cliente em um banco.

Sua tarefa é analisar feedbacks de clientes sobre aplicativo bancário, Pix, tarifas e atendimento (chat, SAC e ouvidoria) para identificar problemas recorrentes, pontos positivos, sentimento dos clientes e oportunidades de melhoria.

Contexto: A análise será usada pelas equipes de Experiência do Cliente, Produto e Atendimento para priorizar melhorias nos canais digitais e reduzir atritos no atendimento. O foco é transformar comentários soltos em insights claros e acionáveis.

Dados disponíveis: Serão fornecidos comentários com data, canal de origem, texto do feedback, produto ou serviço citado e nota de satisfação de 1 a 5. Dados pessoais, como nome, CPF e número de conta, já foram removidos ou devem ser ignorados.

Instruções de análise:

1. Classifique os feedbacks por tema, sentimento (positivo, neutro ou negativo), urgência (alta, média ou baixa), canal e produto citado.
2. Identifique os principais padrões, problemas, elogios e oportunidades.
3. Aponte evidências nos dados fornecidos, usando exemplos curtos de comentários sem dados pessoais.
4. Sugira ações práticas para as equipes de Experiência do Cliente, Produto e Atendimento.

Formato da resposta: Entregue um resumo executivo com até 5 linhas, uma tabela com tema, sentimento, frequência, evidência, prioridade e ação sugerida, e uma lista final com as 3 prioridades mais importantes.

Restrições:

- Use apenas os dados fornecidos.
- Não invente números, causas ou conclusões.
- Não exponha dados pessoais ou sensíveis; se aparecerem, substitua por [DADO OMITIDO].
- Não ignore comentários negativos nem destaque só os elogios.
- Não tire conclusões sem evidência nos comentários.
- Informe limitações quando os dados não forem suficientes.
- Use linguagem simples, direta e voltada para tomada de decisão.
