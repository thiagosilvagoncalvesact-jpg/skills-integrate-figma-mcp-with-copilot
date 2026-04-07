# Step 4: Revisar e Publicar

_Revise seu trabalho e finalize o exercício_ ✅

## Teoria: Code Review com contexto de Design

Quando trabalhamos com **design systems**, o code review ganha uma dimensão extra: além de verificar se o código está correto, precisamos validar se ele **reflete o design**.

No seu PR, isso significa checar:
- As cores hardcoded foram substituídas por variáveis `var(--sds-*)`?
- O visual está consistente com o que o `get_design_context` mostrou?
- A funcionalidade original foi preservada?

Esse é o mesmo fluxo que equipes profissionais usam quando integram design systems — o design é a **fonte de verdade**, e o código precisa estar alinhado.

---

## Atividade

### 4.1 — Revisar o Pull Request

Antes de fazer merge, revise o PR que você abriu no Step 3:

1. Acesse o Pull Request na aba **Pull Requests**
2. Na aba **Files changed**, verifique:
   - O `styles.css` usa variáveis `var(--sds-color-*)` no lugar de cores hardcoded?
   - O visual do site reflete o Design System do Figma?
   - A funcionalidade (signup, listagem) continua funcionando?
3. Se quiser ajustar algo, use o Copilot e faça push na mesma branch

### 4.2 — Fazer merge do PR

1. Na página do Pull Request, clique em **Merge pull request**
2. Confirme o merge
3. Opcionalmente, delete a branch `redesign/design-system`

### 4.3 — Comentar na issue do exercício

Para finalizar, vá até a **Issue #1** do exercício (onde você recebeu as instruções) e deixe um comentário contando o que você aprendeu. Por exemplo:

```
Concluí o exercício! Aprendi a usar o Figma MCP para extrair
design tokens com get_variable_defs e redesenhar um site existente
usando get_design_context como referência visual.
```

---

## Validação

Depois de comentar na issue, o workflow do exercício vai:
- ✅ Detectar seu comentário
- ✅ Postar uma mensagem de revisão final com o resumo do que você aprendeu
- ✅ Finalizar o exercício

Parabéns por chegar até aqui! 🎉
