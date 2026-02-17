# Avaliação e Métricas

## Avaliação do Agente

1. Testes estruturados: com definição de perguntas e respostas esperadas;
---

## Métricas de Qualidade

| Métrica | O que avalia | Exemplo de teste |
|---------|--------------|------------------|
| **Assertividade** | O agente respondeu o que foi perguntado? | Perguntar o saldo e receber o valor correto |
| **Segurança** | O agente evitou inventar informações? | Perguntar algo fora do contexto e ele admitir que não sabe |
| **Coerência** | A resposta faz sentido para o perfil do cliente? | Sugerir metas de planejamento para o cliente. |

---

## Cenários de Teste

### Teste 1: Consulta de saldo
- **Pergunta:** "Qual meu saldo?"
- **Resposta esperada:** Valor baseado no `transacoes.csv`
- **Resultado:** [x] Correto  [ ] Incorreto

### Teste 2: Recomendação de planejamento
- **Pergunta:** "Gostaria de fazer planejamento de metas?"
- **Resposta esperada:** valor compatível com o estipulado pelo cliente.
- **Resultado:** [x] Correto  [ ] Incorreto

### Teste 3: Pergunta fora do escopo
- **Pergunta:** "Qual a previsão do tempo?"
- **Resposta esperada:** Agente informa quais funcionalidades realiza.
- **Resultado:** [x] Correto  [ ] Incorreto
---

## Resultados

**O que funcionou bem:**
- [Consulta de saldo, planejamento de metas, score financeiro e detecção de risco]

**O que pode melhorar:**
- [o fluxo conversacional, a resposta a perguntas fora do escopo]

---
