# Repositório de Skills

Este repositório armazena skills e agentes personalizados para uso com Codex, Antigravity e outros ambientes de automação com IA.

## Skills disponíveis

### Agente Financeiro

Caminho: `agente-financeiro/`

Serve para apoiar análises financeiras, revisão de premissas, criação de relatórios, memorandos de crédito, estudos de mercado, valuation e checagem de conformidade.

A skill foi estruturada para separar fatos, estimativas e premissas, evitando conclusões sem base nos dados fornecidos. Também inclui regras para não gerar recomendações personalizadas de investimento e para sempre destacar riscos, limitações e pontos que exigem validação humana.

Arquivos principais:

- `SKILL.md`: instrução principal da skill.
- `prompts/analyst.md`: prompt para análise financeira.
- `prompts/reviewer.md`: prompt para revisão de consistência.
- `prompts/compliance_check.md`: prompt para checagem de compliance.
- `templates/financial-report.md`: modelo de relatório financeiro.
- `templates/investment-summary.md`: modelo de sumário de investimento.
- `examples/credit-memo.md`: exemplo de memorando de crédito.
- `examples/valuation-review.md`: exemplo de revisão de valuation.
- `examples/market-research.md`: exemplo de pesquisa de mercado.

## Uso geral

Para usar no Codex, coloque a skill como contexto do projeto e peça para o agente seguir as instruções do `SKILL.md`.

Para usar no Antigravity, carregue a pasta da skill e use o `SKILL.md` como instrução principal. Os arquivos da pasta `prompts/` podem ser usados para alternar o papel do agente entre analista, revisor e compliance.

## Observação

As skills deste repositório são ferramentas de apoio. Quando envolver análise financeira, jurídica, contábil ou regulatória, os resultados devem ser revisados por um profissional responsável antes de uso real.
