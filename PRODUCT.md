# PRODUCT.md — Site institucional: Odontologia Dra. Letícia Borges Queiroz

> Arquivo de estratégia para a skill Impeccable. Ler antes de qualquer comando de design.
> Versão revisada — direção visual agora ancorada em assets reais (logo e fachada),
> não em uma paleta genérica de segmento.

## Quem é a cliente

Cirurgiã-dentista (CRO/SP 71554, especialista em Ortodontia) atuando em Miguelópolis-SP,
formada pela Faculdade de Odontologia de Barretos. Reputação local muito forte (5.0★, 18
avaliações no Google — volume alto para o porte da cidade). Hoje só existe online via um
perfil em diretório (Ident), sem site próprio. Clínica com fachada própria e identidade
visual já desenvolvida (ver assets).

- **A CONFIRMAR COM A CLIENTE:** se atende convênio ou só particular.

## Assets fornecidos (usar como fonte primária de direção visual — obrigatório)

- `fachada.jpg` — fachada da clínica ("Odontologia Especializada"): parede revestida em
  mosaico de pedra irregular, em tons terrosos de bronze, cobre e marrom escuro — textura
  real, não plana. Estrutura branca/cinza-clara, colunas quadradas verde-oliva-acinzentado,
  jardineiras com plantas ornamentais (tipo capim/grama ornamental), piso em porcelanato
  cinza-escuro.
- `logo.png` — logo real da clínica: dente estilizado em tom dourado, com retângulo branco
  arredondado sobreposto contendo "ODONTOLOGIA" e "ESPECIALIZADA" em tipografia serifada
  marrom-escuro. Fundo transparente.
- `especialidades.png` — material promocional publicado pela própria Dra. Letícia em rede
  social, listando 8 especialidades (ver seção "Conteúdo já disponível").

**Esta paleta e essa textura são a fonte da direção visual — não uma paleta pastel
clínica genérica.** O site deve parecer a extensão digital dessa fachada real, não um
consultório odontológico abstrato de banco de imagens.

## Audiência

- Moradores de Miguelópolis e região buscando um dentista de confiança — famílias,
  adultos e provavelmente pais buscando ortodontia para filhos adolescentes.
- Público que decide por indicação e reputação; alguns com receio histórico de consultas
  odontológicas — o site precisa neutralizar isso, não reforçar frieza clínica.
- Acesso majoritariamente via celular.

## Propósito do site

Transformar a reputação já existente (18 avaliações 5 estrelas) em agendamentos. CTA
principal: WhatsApp para agendar avaliação/consulta.

## Voz de marca / tom

- Acolhedor, mas também **enraizado no lugar** — uma marca que se orgulha de ser local,
  não uma clínica genérica que poderia estar em qualquer cidade.
- Confiança técnica com calor humano; evitar linguagem fria/hospitalar.

## Direção visual concreta (token system)

- **Paleta** (derivada do logo e da fachada, 5 cores nomeadas):
  - `oliva-campo` #9CB13A — cor de assinatura, escolha de design ancorada nos tons
    verde-acinzentados da fachada (colunas, jardineiras)
  - `bronze-pedra` #6B4A32 — tom da fachada em mosaico, para fundos/seções escuras
  - `creme-quente` #F1EDE3 — não confundir com o cream-serif-cliché (#F4F1EA):
    aqui é derivado do reboco claro da fachada, mais neutro/acinzentado
  - `verde-jardineira` #5C6B4F — verde acinzentado das colunas/plantas, para acentos
    secundários e ícones
  - `grafite` #2B2A28 — texto principal, tirado do piso escuro
- **Tipografia**: display sans-serif condensada bold (ecoando o "Dra. Letícia B. Queiroz"
  da placa) para títulos; corpo em uma humanist sans (ex: Inter, Source Sans) para
  legibilidade e calor.
- **Layout**: hero com textura sutil de mosaico de pedra (derivada da foto da fachada,
  tratada como padrão de fundo discreto, não decoração pesada) atrás do headline.
- **Elemento de assinatura**: divisor de seção com silhueta de horizonte/campo ondulado
  (SVG), reforçando a identidade rural e agrícola da região de Miguelópolis.

## Registro

**Brand surface** — site institucional de confiança, não app de produto.

## Anti-referências (específicas deste cliente)

- Não usar azul clínico "hospitalar" ou branco-gelo genérico — a marca já rejeitou essa
  direção ao escolher tons terrosos/oliva no próprio logo.
- Não usar ícone de dente genérico de stock (a cliente já tem um logo próprio distinto;
  usá-lo, não substituir por clip-art).
- Evitar os 3 clichês de design gerado por IA (fundo creme + serifada + terracota tipo
  #D97757; fundo quase-preto + acento neon; layout jornal com colunas densas) — a
  paleta derivada da fachada real já naturalmente foge desses padrões, mas vale
  reforçar explicitamente.
- Não inventar texto institucional vazio tipo "excelência no atendimento odontológico
  com foco no paciente" sem informação concreta.

## Conteúdo já disponível (fonte: Google Maps + Ident + fachada + rede social)

- Nome: Odontologia Dra. Letícia Borges Queiroz — Odontologia Especializada
- CRO/SP: 71554
- Endereço: R. José Francisco Peixoto, 795 - Centro, Miguelópolis - SP
- Telefone/WhatsApp: +55 16 99231-4853
- Avaliação Google: 5.0★ (18 avaliações)
- Formação: Faculdade de Odontologia de Barretos
- Tempo de experiência: +15 anos (fonte: CRO/SP)
- Especialidades (fonte: material promocional da própria Dra. Letícia):
  - Ortodontia
  - Ortopedia Funcional dos Maxilares
  - Harmonização Facial
  - Estética Dental
  - Prótese
  - Tratamento de Canal
  - Clareamento Dental
  - Lentes de Contato

## Pendências antes do design final (A CONFIRMAR COM A CLIENTE)

- [x] ~~Lista completa de procedimentos/serviços~~ (confirmada via material da própria Dra.)
- [x] ~~Tempo de carreira~~ (confirmado: +15 anos, fonte CRO/SP)
- [ ] Texto "sobre" (diferenciais, abordagem com pacientes ansiosos)
- [ ] Fotos internas do consultório e/ou foto profissional (além da fachada já obtida)
- [ ] Horário de funcionamento
- [ ] E-mail e se atende convênios
- [ ] Autorização para publicar nome, avaliações e dados no site

## Infraestrutura de publicação

- Hospedagem/CDN: Cloudflare Pages
- Stack a critério do desenvolvedor, compatível com deploy estático em Cloudflare Pages
