---
name: Odontologia Dra. Letícia Borges Queiroz
description: Site institucional — Odontologia Especializada em Miguelópolis-SP, com identidade visual enraizada no campo e na fachada real da clínica.
colors:
  oliva-campo: "#9CB13A"
  bronze-pedra: "#6B4A32"
  creme-quente: "#F1EDE3"
  verde-jardineira: "#5C6B4F"
  grafite: "#2B2A28"
  white: "#fff"
typography:
  display:
    fontFamily: "'Barlow Semi Condensed', sans-serif"
    fontWeight: 700
    fontSize: "clamp(2.25rem, 5vw + 0.5rem, 4.5rem)"
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "'Barlow Semi Condensed', sans-serif"
    fontWeight: 700
    fontSize: "clamp(1.75rem, 3.5vw + 0.25rem, 3rem)"
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  body:
    fontFamily: "'Source Sans 3', sans-serif"
    fontWeight: 400
    fontSize: "1rem"
    lineHeight: 1.6
rounded:
  sm: "8px"
  card: "12px"
  full: "999px"
spacing:
  xs: "clamp(0.25rem, 0.3vw, 0.5rem)"
  sm: "clamp(0.5rem, 0.6vw, 0.75rem)"
  md: "clamp(1rem, 1.2vw, 1.5rem)"
  lg: "clamp(1.5rem, 2vw, 2.5rem)"
  xl: "clamp(2rem, 3vw, 4rem)"
  "2xl": "clamp(3rem, 5vw, 6rem)"
  "3xl": "clamp(4rem, 7vw, 8rem)"
components:
  button-primary:
    backgroundColor: "{colors.oliva-campo}"
    textColor: "#fff"
    rounded: "{rounded.full}"
    padding: "0.75em 1.5em"
  button-primary-hover:
    backgroundColor: "{colors.oliva-campo}"
    textColor: "#fff"
  button-outline:
    backgroundColor: transparent
    textColor: "{colors.oliva-campo}"
    rounded: "{rounded.full}"
  card:
    backgroundColor: "#fff"
    rounded: "12px"
    padding: "var(--space-lg)"
---

# Design System: Odontologia Dra. Letícia Borges Queiroz

## 1. Overview

**Creative North Star: "A Fachada Viva"**

O sistema visual traduz a fachada real da clínica — mosaico de pedra em tons bronze, colunas verde-oliva, jardineiras — para a tela. Não é uma paleta odontológica genérica; é a extensão digital de um lugar real em Miguelópolis-SP.

A marca recusa azul clínico, branco-gelo hospitalar e o clichê cream-serif-terracota da IA. Em vez disso, ancora-se em cinco cores nomeadas extraídas diretamente da fachada fotografada. O logo real (dente dourado com "ODONTOLOGIA ESPECIALIZADA") carrega a identidade da clínica. O resultado é uma identidade que respira o orgulho de ser local — uma odontologia que pertence à terra, não a um template.

**Key Characteristics:**
- Paleta derivada de assets reais (logo + fachada), não de tendência de segmento
- Tipografia display condensada bold que ecoa a placa da clínica
- Divisores de seção com silhueta de horizonte/campo como elemento de assinatura
- Hero com foto real da fachada, nunca placeholder genérico
- CTA WhatsApp onipresente, mobile-first, sem atrito
- Placeholders sinalizados com borda tracejada e rótulo "A CONFIRMAR", sem conteúdo inventado

## 2. Colors: A Paleta do Campo

Cinco cores nomeadas, cada uma ancorada em um elemento físico da clínica. Estratégia: **Committed** — o oliva-campo carrega 30-60% da superfície de destaque (botões, ícones, estrelas, texto de acento).

### Primary
- **Oliva Campo** (#9CB13A): Cor de assinatura, ancorada nos tons verde-acinzentados da fachada (colunas, jardineiras). Usada em botões CTA, estrelas de avaliação, texto de destaque no hero, divisores de seção e ícones. É a voz da marca — aparece onde a ação importa.

### Neutral
- **Bronze Pedra** (#6B4A32): Tom do mosaico da fachada. Usado no footer como fundo escuro, em overlays do hero e em bordas sutis. Traz o peso da pedra real para a interface.
- **Creme Quente** (#F1EDE3): Derivado do reboco claro da fachada — mais neutro e acinzentado que o cream-serif-cliché (#F4F1EA). Fundo principal do site, seções alternadas. Não é "quente" por convenção; é quente porque a fachada real é assim.
- **Verde Jardineira** (#5C6B4F): Verde acinzentado das colunas e plantas da fachada. Usado em texto secundário, ícones inativos e labels. Função de suporte — nunca compete com o oliva-campo.
- **Grafite** (#2B2A28): Tirado do piso escuro da fachada. Texto principal, headings. Contraste máximo sem ser preto puro (#000).

### Named Rules
**A Regra da Fachada.** Toda cor tem lastro em um elemento físico da clínica. Nenhuma cor entra na paleta por "combinação harmônica" ou tendência. Se não está na fachada ou no logo, não está no site.

**A Regra Anti-Clichê.** Proibidos: azul clínico (#2196F3 e família), branco-gelo (#FAFAFA puro), cream-serif (#F4F1EA com serifada), terracota IA (#D97757). A paleta derivada da fachada real naturalmente escapa desses padrões — o trabalho é não deixá-los voltar pela porta dos fundos.

## 3. Typography: A Placa e o Texto

**Display Font:** Barlow Semi Condensed (com fallback sans-serif)
**Body Font:** Source Sans 3 (com fallback system-ui)

**Character:** A display condensada bold ecoa a tipografia da placa "Dra. Letícia B. Queiroz" na fachada — letras que existem no mundo real, não uma escolha de catálogo. A body humanist sans (Source Sans 3) traz calor e legibilidade, com terminais ligeiramente abertos que respiram no mobile.

### Hierarchy
- **Display** (700, clamp(2.25rem, 5vw + 0.5rem, 4.5rem), 1.15): Hero headline. Letter-spacing -0.02em. Max-width ~20ch.
- **Headline** (700, clamp(1.75rem, 3.5vw + 0.25rem, 3rem), 1.15): Títulos de seção (h2). Text-wrap: balance.
- **Title** (700, clamp(1.25rem, 2vw + 0.25rem, 1.75rem), 1.15): Subtítulos e cards (h3).
- **Body** (400, 1rem, 1.6): Texto corrido. Max-width 65ch. Text-wrap: pretty.
- **Label** (600, 0.875rem, normal): Metadados, badges, legendas. Source Sans 3 Semibold.

### Named Rules
**A Regra da Placa.** Display headings usam Barlow Semi Condensed Bold — a mesma família de personalidade da placa física da clínica. Nenhuma serifada "elegante" substitui essa âncora no mundo real.

## 4. Elevation

Sistema plano por padrão, com elevação sutil onde a hierarquia pede. Sem sombras decorativas; cada sombra cumpre uma função estrutural.

### Shadow Vocabulary
- **card-rest** (`0 1px 4px rgba(107, 74, 50, 0.08)`): Cards e badges em repouso. Quase imperceptível — só o suficiente para separar do fundo creme-quente.
- **card-hover** (`0 4px 20px rgba(107, 74, 50, 0.1)`): Elevação ao hover em cards interativos.
- **cta-glow** (`0 2px 12px rgba(156, 177, 58, 0.35)`): Botões CTA primários. Brilho verde-oliva que sinaliza ação.
- **cta-glow-hover** (`0 4px 18px rgba(156, 177, 58, 0.45)`): Intensificação ao hover.
- **image-shadow** (`0 4px 24px rgba(107, 74, 50, 0.15)`): Imagens com destaque (fachada na seção sobre).

### Named Rules
**A Regra da Sombra com Propósito.** Sombras só aparecem onde há interação ou separação estrutural real. Nada de shadow "para dar profundidade" sem função. A fachada real não tem sombra — o site também não, por padrão.

## 5. Components

### Buttons

- **Shape:** Full pill (border-radius: 999px). A forma circular remete a acolhimento, não a arestas clínicas.
- **Primary (CTA):** Fundo oliva-campo (#9CB13A), texto branco, sombra cta-glow. Padding: 0.75em 1.5em. Hover: translateY(-1px) + shadow intensify. Transition: transform 0.2s ease, box-shadow 0.2s ease.
- **Outline:** Borda 2px oliva-campo, texto oliva-campo, fundo transparente. Hover: preenche com oliva-campo, texto branco.
- **Fixed Mobile:** Posicionado fixed bottom-right no mobile (z-index 50). Escondido em desktop (≥768px). Sombra mais intensa (0 4px 24px) para destacar do conteúdo.

### Cards

- **Default:** Fundo branco (#fff), border-radius 12px, border 1px rgba(107, 74, 50, 0.12), padding-lg, sombra card-rest. Hover: sombra card-hover.
- **Placeholder (dashed):** Fundo rgba(241, 237, 227, 0.5), border dashed 1.5px rgba(156, 177, 58, 0.3). Sinaliza conteúdo pendente — border tracejada é a linguagem visual de "a preencher".
- **Featured (review):** Como default, com sombra card-rest. Destaque para o review real do Google.

### Navigation

- **Style:** Fixed top, backdrop-filter blur(12px), background rgba(255,255,255,0.92), border-bottom sutil (rgba(107,74,50,0.1)). Minimalista: logo à esquerda, WhatsApp à direita.
- **Mobile:** Mantém a mesma estrutura. Sem hamburger menu — página única, scroll é a navegação.

### Dividers (Horizon)

- **Style:** SVG inline com duas curvas sobrepostas em oliva-campo com opacidades 0.18 e 0.12. Silhueta de horizonte ondulado — elemento de assinatura que reforça a identidade rural da região de Miguelópolis.
- **Uso:** Entre hero e conteúdo, e entre seções principais. Altura fluida (clamp(32px, 5vw, 60px)).

### Badges

- **Style:** Fundo branco, border-radius 8px, padding-sm + md horizontal, sombra card-rest. Layout flex column centralizado.
- **Tipografia:** Valor em Barlow Semi Condensed Bold (oliva-campo), label em Source Sans 3 Semibold (grafite), sub em 0.6875rem (verde-jardineira).

### Placeholder Banners

- **Style:** Borda tracejada 1.5px oliva-campo, fundo rgba(156, 177, 58, 0.05), padding-sm + md horizontal. Ícone de informação à esquerda. Texto com label "A CONFIRMAR COM A CLIENTE" em negrito.
- **Propósito:** Sinalizar conteúdo pendente sem inventar. A borda tracejada + cor oliva são o sistema visual de "aguardando".

## 6. Do's and Don'ts

### Do:
- **Do** usar a foto real da fachada (`fachada.jpg`) no hero e na seção sobre — nunca substituir por banco de imagens genérico.
- **Do** usar o logo real da cliente (`logo.png`, dente dourado com "ODONTOLOGIA ESPECIALIZADA") — nunca substituir por clip-art de dente genérico.
- **Do** usar os divisores de horizonte entre seções como elemento de assinatura recorrente.
- **Do** sinalizar todo conteúdo pendente com o sistema de placeholder (borda tracejada + label "A CONFIRMAR COM A CLIENTE").
- **Do** manter o CTA WhatsApp sempre visível (nav desktop + botão fixed mobile).
- **Do** usar `text-wrap: balance` em headings e `text-wrap: pretty` em body para evitar órfãs.
- **Do** respeitar `prefers-reduced-motion: reduce` em todas as animações e transições.

### Don't:
- **Don't** usar azul clínico "hospitalar" ou branco-gelo genérico — a marca já rejeitou essa direção ao escolher tons terrosos/oliva na fachada.
- **Don't** usar ícone de dente genérico de stock — a cliente já tem um logo próprio distinto; usá-lo, não substituir por clip-art.
- **Don't** cair nos 3 clichês de design gerado por IA: fundo creme + serifada + terracota (#D97757); fundo quase-preto + acento neon; layout jornal com colunas densas.
- **Don't** inventar texto institucional vazio ("excelência no atendimento odontológico com foco no paciente") sem informação concreta.
- **Don't** usar `border-left` ou `border-right` >1px como acento colorido em cards, listas ou callouts.
- **Don't** usar `background-clip: text` com gradiente para texto decorativo.
- **Don't** usar glassmorphism como padrão decorativo.
- **Don't** colocar eyebrow (label uppercase tracked) acima de toda seção como gramática visual.
- **Don't** usar cards aninhados dentro de cards.
- **Don't** substituir a foto da fachada por placeholder genérico ou bloco de cor sólida onde deveria haver imagem real.
