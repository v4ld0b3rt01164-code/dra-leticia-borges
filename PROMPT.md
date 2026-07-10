# Prompt — Construção do site (Agente de codificação + Impeccable)

Cole este prompt no seu agente de codificação, dentro da pasta do projeto — com
`PRODUCT-leticia-borges-queiroz.md` (renomeado para `PRODUCT.md` na raiz) e
`dent-leticia-borges-queiroz.json` já presentes, além dos arquivos de imagem da
fachada/logo salvos em uma pasta de assets (`/assets`, `/public` ou equivalente).

---

Estou construindo o site institucional da Odontologia Dra. Letícia Borges Queiroz
(Miguelópolis-SP), a ser publicado no Cloudflare Pages.

**Passo 0 — obrigatório antes de tudo:** liste todos os arquivos de imagem/logo que
existem na pasta de assets do projeto e me diga exatamente quais encontrou, com nome
de arquivo. Se não encontrar nenhum, pare e me avise antes de continuar. Para cada
imagem: abra e descreva o que vê (cores com hex aproximados, estilo, o que comunica).
O `PRODUCT.md` já traz essa análise para a fachada e o logo — confirme que ela bate
com o que você está vendo nos arquivos reais antes de seguir.

Depois leia `PRODUCT.md` (estratégia de marca, incluindo a seção "Direção visual
concreta" com paleta, tipografia e elemento de assinatura já definidos a partir dos
assets reais) e `dent-leticia-borges-queiroz.json` (dados extraídos do Google Maps).

Siga este fluxo, nesta ordem, sem pular etapas (comandos da skill Impeccable):

1. **`/impeccable init`** — se ainda não houver `PRODUCT.md`/`DESIGN.md`
   reconhecidos, rode para gerar a estrutura, usando o `PRODUCT.md` fornecido como
   base real — não substitua o conteúdo, só complemente se necessário.
2. **`/impeccable shape`** — produza um brief de design a partir do `PRODUCT.md` e
   do JSON. **A paleta, tipografia e elemento de assinatura já estão definidos no
   `PRODUCT.md` — use-os literalmente, não proponha uma paleta alternativa.** Os
   campos marcados `"A CONFIRMAR COM A CLIENTE"` devem virar placeholders visíveis e
   claramente sinalizados — não invente conteúdo para esses campos.
3. **`/impeccable craft`** — desenhe e construa a primeira versão do site. As fotos
   de fachada fornecidas devem ser usadas de fato no layout (hero e/ou seção
   institucional), não substituídas por placeholder ou banco de imagens.
4. Depois da primeira versão construída: **`/impeccable document`** — gere o
   `DESIGN.md` real a partir do que foi implementado.
5. **`/impeccable critique`** seguido de **`/impeccable polish`**.
6. **`/impeccable audit`** — cheque estados de erro, i18n/PT-BR, responsividade e
   performance antes de publicar.

## Checklist final obrigatório (responda antes de finalizar)

- [ ] Quais arquivos de asset foram inventariados e onde cada um foi usado no layout
- [ ] A paleta e tipografia batem com as definidas no `PRODUCT.md` (oliva-campo,
      bronze-pedra, creme-quente, verde-jardineira, grafite) — sem substituição por
      default genérico
- [ ] O elemento de assinatura (silhueta de horizonte/campo) foi incorporado em algum
      ponto do layout
- [ ] Nenhuma imagem de banco genérica foi usada onde já havia material próprio

## Requisitos técnicos

- Stack compatível com deploy estático no **Cloudflare Pages**.
- Registro: **brand surface** — ver `PRODUCT.md`.
- Página única, objetiva, **mobile-first**.
- CTA principal sempre visível: **WhatsApp/telefone** (`+55 16 99231-4853`).

## Dados da cliente

Ver `dent-leticia-borges-queiroz.json` na raiz do projeto.
