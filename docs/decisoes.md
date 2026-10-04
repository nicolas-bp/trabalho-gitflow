# Decisões sobre os Conflitos

## Conflito 1 — app.js

**Alternativas consideradas:**
- Manter a implementação da Equipe B.
- Manter a implementação da Equipe C.
- Combinar as funcionalidades das duas equipes.

**Decisão final:**

Foi mantida a função `updateCount`, substituindo `setCount`, conforme solicitado pela Equipe B.

Também foi mantido o incremento do contador de 2 em 2.

Da Equipe C, foi mantida a funcionalidade de tema ajustável, incluindo a alteração do texto do botão entre "Modo Escuro" e "Modo Claro".

**Racional:**

A decisão permite preservar as funcionalidades das duas equipes sem perder as alterações exigidas pela atividade.

---

## Conflito 2 — index.html

**Alternativas consideradas:**
- Manter o título da Equipe B: `Mini App – Equipe B`.
- Manter o título da Equipe C: `Mini App – Modo Escuro`.

**Decisão final:**

Foi escolhida a versão da Equipe C:

`Mini App – Modo Escuro`

**Racional:**

Essa versão mantém a funcionalidade relacionada ao tema escuro. O comportamento do título quando o usuário retornar ao modo claro será corrigido posteriormente no hotfix da atividade.

---

## Conflito 3 — styles.css

**Alternativas consideradas:**
- Manter a cor primária verde da Equipe B.
- Manter a cor primária vermelha da Equipe C.

**Decisão final:**

Foi escolhida a alteração da Equipe C:

`--primary: #e74c3c;`

**Racional:**

A alteração mantém a personalização visual proposta pela Equipe C após a integração das funcionalidades.

---

## Registro da Resolução

Os três conflitos foram resolvidos manualmente durante a integração das branches:

- `feature/incremento-rename`
- `feature/tema-ajustavel`

Foram preservadas as funcionalidades consideradas necessárias das duas equipes.

**Arquivos envolvidos:**
- `app.js`
- `index.html`
- `styles.css`

**Commit da resolução:**

`4e27492 merge: resolve conflitos entre equipes`

**Responsável pela resolução:** Equipe A

**Data:** 04/10/2026