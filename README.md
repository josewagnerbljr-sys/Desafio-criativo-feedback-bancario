# Desafio Criativo: Extraindo Insights do Feedback de Clientes Bancários

Prompt estruturado para orientar uma IA a analisar feedbacks de clientes bancários e transformá-los em insights acionáveis, com critérios de análise claros e cuidados com dados sensíveis (LGPD).

Desafio proposto pela [DIO](https://www.dio.me/).

## Objetivo

Construir, passo a passo, um prompt capaz de fazer uma IA:

- classificar feedbacks por tema, sentimento, urgência, canal e produto;
- identificar padrões, problemas recorrentes, elogios e oportunidades;
- apontar evidências nos comentários fornecidos;
- sugerir ações práticas e priorizadas para as áreas responsáveis;
- proteger dados pessoais e não inventar informações.

## Como o prompt foi construído

| Passo | Etapa | O que define |
|---|---|---|
| 1 | Intenção | O que a IA deve produzir, para quem e com qual finalidade |
| 2 | Contexto e restrições | Dados disponíveis, critérios de análise e limites da resposta |
| 3 | Prompt final | União de todas as peças em um único comando claro |

## Estrutura do repositório

```
.
├── README.md
└── desafio-criativo-feedback-bancario.md   # Passos 1, 2 e prompt final
```

## Resumo do prompt final

- **Papel da IA:** analista de dados e de experiência do cliente em um banco.
- **Escopo:** feedbacks sobre aplicativo, Pix, tarifas e atendimento (chat, SAC e ouvidoria).
- **Público:** equipes de Experiência do Cliente, Produto e Atendimento.
- **Critérios de classificação:** tema, sentimento, urgência, canal e produto citado.
- **Formato da resposta:** resumo executivo (até 5 linhas), tabela com tema, sentimento, frequência, evidência, prioridade e ação sugerida, e as 3 prioridades mais importantes.

O texto completo do prompt está em [`desafio-criativo-feedback-bancario.md`](desafio-criativo-feedback-bancario.md).

## Cuidados e restrições

- Usar apenas os dados fornecidos.
- Não inventar números, causas ou conclusões.
- Não expor dados pessoais ou sensíveis (nome, CPF, conta, cartão, contato); se aparecerem, substituir por `[DADO OMITIDO]`.
- Não ignorar comentários negativos nem destacar só os elogios.
- Informar limitações quando os dados forem insuficientes.
- Usar linguagem simples, direta e voltada para a tomada de decisão.

## Como usar

1. Abra o arquivo [`desafio-criativo-feedback-bancario.md`](desafio-criativo-feedback-bancario.md) e copie o texto da seção **Passo 3: Prompt final**.
2. Cole o prompt em uma IA de sua preferência.
3. Anexe ou cole os feedbacks, já sem dados pessoais.
4. Revise o resultado e ajuste os critérios, o formato ou as restrições conforme a sua necessidade.

## Aprendizados

- Um bom prompt nasce de intenção clara, contexto e instruções específicas.
- Definir o formato da resposta e o que a IA deve evitar melhora a qualidade e a segurança do resultado.
- Tratar dados sensíveis desde a entrada da análise reduz riscos de exposição.

## Autor

[josewagnerbljr-sys](https://github.com/josewagnerbljr-sys)
