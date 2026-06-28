# SoundWave Studio

## Escopo Fechado

**Objetivo:** Site institucional de uma escola de música independente em Guaramirim, com foco em captação de novos alunos. O usuário pode conhecer os cursos disponíveis, os professores, a história da escola e entrar em contato para se matricular.

**Público-alvo:** Pessoas de 14 a 40 anos interessadas em aprender música, de iniciantes a intermediários.

**Paleta de cores:**
- `#0D0D0F` — fundo principal
- `#A259FF` — roxo elétrico (destaque/CTA)
- `#FF5C8A` — rosa (gradiente secundário)
- `#FFD166` — dourado (badges de status)
- `#EAEAF0` — texto principal

A paleta escura com roxo elétrico foi escolhida por remeter à identidade visual de ferramentas de áudio (DAWs como Ableton), criando familiaridade imediata com o público músico.

**Tipografia:**
- **Syne** (headings e botões) — geométrica e contemporânea, comum em marcas culturais e festivais
- **DM Sans** (corpo de texto) — alta legibilidade em tela, complementa a Syne sem competir

**Framework:** Nenhum. HTML5, CSS3 e JavaScript puro.

---

## Detalhamento do Site

O site é uma SPA (Single Page Application): um único arquivo HTML alterna entre as páginas via JavaScript, sem recarregamento.

**Home** — Hero com chamada principal, estatísticas da escola, grid de professores com filtro por gênero musical (Rock, Jazz, Eletrônica, MPB, Clássica) e agenda de próximos shows e eventos.

**Cursos** — Grid com 6 cursos (Guitarra, Piano, Produção Musical, Técnica Vocal, Contrabaixo e Beat Making). Possui filtro por categoria (Instrumento, Produção, Vocal). Ao clicar em um curso, abre um modal com detalhes completos e botão de matrícula.

**Sobre** — História da escola, os 4 pilares institucionais, cards dos 4 professores com foto e bio, e linha do tempo de 2013 a 2025.

**Contato** — Informações de endereço, telefone e e-mail, e formulário com validação em JavaScript (nome, e-mail com Regex, telefone com formato brasileiro, mensagem com mínimo de 20 caracteres e contador de caracteres). Feedback visual por campo e toast de confirmação ao enviar.

---

## Integrantes

| Rafael Fernando Safanelli | | fez tudo.


