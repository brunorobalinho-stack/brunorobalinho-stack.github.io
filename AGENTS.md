# Regras deste repo (Sistema Bruno / Argus-Terceiriza)

Contexto: projeto do Bruno Robalinho (Argus/Terceiriza, Recife/PE). Respostas e commits em PT-BR.

## Código (pétreas)
- Código em inglês; comentários e docstrings em PT-BR.
- `logging` em produção, nunca `print()` (print só em camada CLI, dentro de `main()`).
- Timestamps: `datetime.now(timezone.utc)`, nunca `datetime.utcnow()`.
- Datas em DD/MM/AAAA; moeda em R$ 1.234,56.

## Fluxo de trabalho
- Ler antes de mexer; passo pequeno; diff conferido antes de gravar.
- Teste antes de merge, suíte completa. Teste vermelho = tarefa não concluída.
- Não inventar estado: sem certeza, escrever "precisa verificar: [o quê]".
- Não reescrever o que funciona; melhorar só o que atrapalha, preservando o resto.
- Não apagar log, histórico ou decisão sem justificar e pedir confirmação.
- Em arquivo recorrente (planilha, relatório), preservar a estrutura existente (abas, posições, referências); mudança estrutural se declara ANTES de produzir.

## Autonomia
- Ação externa (enviar, protocolar, publicar, pagar, assinar) é decisão humana do Bruno, sempre. Rascunho pode; envio não.
- Dado pessoal de empregado (CPF, salário, holerite) nunca vai para chat, commit, issue ou log.
