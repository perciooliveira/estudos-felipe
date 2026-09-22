# Estado Atual do Projeto — Estudos Felipe

Anexe este arquivo no **Knowledge** do Projeto no Claude.ai. Ele é a "memória" de tudo que foi feito até aqui, pra que qualquer conversa nova já entre com o contexto completo.

---

## Onde está hospedado

**Repositório GitHub:** `https://github.com/perciooliveira/estudos-felipe` (público)

O site é servido diretamente pelas páginas HTML no repo. Cada arquivo é auto-suficiente (HTML + CSS + JS inline). KaTeX é carregado via CDN.

## Matérias implementadas

### 📚 História — `estudo_historia_p2t1.html`
**Prova P2 do Tri 1** — Antiguidade Oriental e Clássica.
- Módulos: 6 (Persas), 7 (Fenícios), 8 (Grécia I: períodos e sociedade), 9 (Grécia II: política e cultura).
- Features: 11 abas incluindo Visão Geral, Conteúdo Detalhado, Períodos da Grécia, Mapas Mentais SVG, Flashcards (45 cards), Comparações (Persas × Fenícios, Atenas × Esparta), Linha do Tempo, Cultura Grega, Mnemônicos, Legado, Quiz Final (22 perguntas).
- Paleta: vermelho (Persas), ciano (Fenícios), roxo (Grécia), azul (Atenas), vermelho escuro (Esparta).

### ⚛️ Física — `fisica.html`
**Prova P2 do Tri 1** — cobre 2 professores diferentes.
- Física A (Prof. Alan) — Cinemática: MRU (M5, 6, 7) e MRUV (M8).
- Física B (Prof. Scotti) — Termologia: Dilatação (M3) e Calorimetria (M4).
- Features: 9 abas com Visão Geral, Conteúdo, Formulário, Gráficos SVG interativos (s×t, v×t, a×t), Mapas Mentais, Flashcards (30 cards com filtros por tema), Exemplos Resolvidos, Mnemônicos, Quiz Final (15 perguntas).
- Paleta: azul-ciano (Movimento), rosa-laranja (Termologia).

### 🏛️ Filosofia — `filosofia.html`
**Prova P1 do Tri 2** — Modernidade política e ética.
- Módulos: 20 (Hobbes), 21 (Iluminismo/Locke), 22 (Liberais), 23 (Rousseau), 26 (Kant).
- Features: 4 abas enxutas (Visão Geral, Filósofos-Chave, Exercícios do Roteiro com 25 questões e resposta comentada, Resumo dos Módulos).
- Diferencial: cards de exercício com enunciado literal, todas alternativas, botão "Ver resposta" que revela correta em verde + explicação.
- Paleta: por filósofo (Hobbes vermelho, Locke verde-água, Rousseau verde, Liberais laranja, Kant roxo).

### 📐 Matemática — `matematica.html`
**Prova P2 do Tri 2** — Álgebra + Geometria (2 professores).
- Matemática A (Prof. Vinni) — Funções: M17 (Afim), M18 (Aplicações), M19 (Linear/Constante), M20 (Quadrática I), M21 (Vértice), M23-24 (Máx/Mín).
- Matemática B (Prof. Dodl) — Geometria plana: M20-21 (Triângulos), M22-23 (Polígonos), M24 (Circunferência), M25 (Pontos Notáveis), M26 (Quadriláteros), M27 (Tales).
- Features: 7 abas incluindo Visão Geral, Resumos separados (Álgebra e Geometria), Exercícios do Roteiro (~60 questões com botão Ver original + Dica + Passo a passo + Resposta), Simulados (3 provas simuladas de 14 questões cada, imprimíveis), Corrigir Simulado, Fórmulas & Radar de Armadilhas.
- **Especial:** modal de imagem com zoom automático inicial (preenche largura), suporte a galeria por módulo (setas ‹ ›), fotos das 81 páginas do livro em `img/pages/IMG_XXXX.jpg`.
- Laboratório interativo de parábola com sliders para a, b, c (mostra Δ, vértice, raízes, concavidade em tempo real).
- Paleta: azul (Álgebra), verde (Geometria).

### 🧪 Química — `quimica_rec_t2.html` (RECUPERAÇÃO)
**Recuperação do Tri 2** — primeira matéria da nova modalidade "recuperação". Não existe material regular de Química (P1/P2); esta página é exclusivamente de recuperação.
- Química A (Prof.ª Angelise) — M11 (propriedades periódicas), M13 (octeto), M14-15 (Lewis), M17 (ligação metálica), M18 (geometria), M19 (polaridade), M20 (forças intermoleculares), M21 (PF/PE), M22 (sigma/pi), M23 (hibridização).
- Química B (Prof. Guilherme) — M6 (separação de misturas), M7 (isótopos), M8 (massa molecular), M9 (mol/massa molar), M10 (fórmulas).
- 10 abas: Visão Geral, Mapa de Conteúdo, P1 comentada, P2 comentada, Conceitos-chave, **Dicas**, Recuperação ativa, Reforço N1·N2·N3, Simulado, Gabaritos.
- Paleta: verde-esmeralda → lima (`#34d399` → `#a3e635`); cromo de recuperação em âmbar/vermelho (`#f59e0b` → `#ef4444`).
- Figuras das provas embutidas como data-URI base64 (~100 KB); matrizes da Q3 da P1 e tabela periódica esquemática da Q5 **redesenhadas em HTML/CSS** (o scan tinha marcas de caneta).
- ⚠️ O arquivo da P1T2 nomeado "GABARITO" era na verdade a prova respondida pelo aluno, não a folha de respostas. As respostas da P1 foram resolvidas e conferidas manualmente e estão sinalizadas como tal.

### 📐 Matemática — `matematica_rec_t2.html` (RECUPERAÇÃO)
**Recuperação do Tri 2.** Convive com o material regular `matematica.html` — o card do hub tem os dois links.
- Matemática A (Prof. Vinni) — conjuntos, intervalos, conjuntos numéricos, funções afim e quadrática.
- Matemática B (Prof. Dodl) — trigonometria no triângulo retângulo, leis dos senos e cossenos, retas paralelas cortadas por transversal, triângulos, polígonos e pontos notáveis. *(Circunferência, quadriláteros e Tales caíram nas provas mas ficaram fora da recuperação.)*
- Mesmas 10 abas. Paleta azul → verde (`#60a5fa` → `#34d399`).
- 16 questões reais comentadas, 18 de reforço, 8 no simulado. Após o filtro da PRT2 (22/08): **8 conceitos e 9 cards de Dicas**.
- 🔁 **Filtrado pela PRT2:** saíram Mat B M18, M24, M26 e M27. P1 Q6 e P2 Q7 marcadas como parciais, P2 Q3 como fora. Ver a seção do filtro mais abaixo.
- Figuras geométricas **redesenhadas em SVG inline** por `gen_svg.py` (os scans tinham marcas de caneta).
- ⚠️ Gabarito da P2T2 **não é oficial** (o arquivo é o caderno de prova) — as respostas foram resolvidas e conferidas e estão sinalizadas.
- ⚠️ O item 08 da Q8 da P2 saiu com enunciado incompleto; o material sinaliza e pede confirmação com o professor.

### 🧬 Biologia — `biologia_rec_t2.html` (RECUPERAÇÃO)
**Recuperação do Tri 2** — não existe material regular de Biologia; card com badge "🔁 Só recuperação".
- Bio A (Prof. Rafael) — M13 (ácidos nucleicos), M14 (pareamento e replicação), M15 (síntese proteica e código genético), M16 (biotecnologia), M17-18 (respiração celular), M19 (fermentação), M20-21 (fotossíntese e quimiossíntese).
- Bio B (Prof.ª Larissa) — M3 (tipos de ovos), M4 (mórula/blástula/gástrula, proto × deuterostômios), M5 (folhetos germinativos, neurulação, celoma), M7 (anexos embrionários), M8 (fecundação → organogênese, blastocisto, nidação), M9 (taxonomia e nomenclatura).
- Mesmas 10 abas. Paleta verde → azul-céu (`#22c55e` → `#38bdf8`). Sem KaTeX (não há matemática).
- 20 questões reais comentadas, 27 exercícios de reforço, simulado inédito de 10 questões. Após o filtro da PRT2 (22/08): **10 conceitos, 11 cards de Dicas, 33 flashcards**.
- 🔁 **Filtrado pela PRT2:** saíram Bio A M16 e Bio B M3, M4 e M5. P1 Q4, Q5 e Q6 marcadas como fora; Q10 como parcial; Q7 fica pelo M8. Ver a seção do filtro mais abaixo.
- Todas as figuras **redesenhadas em SVG inline** (`gen_svg.py`, `gen_svg2.py`, `gen_svg3.py`), incluindo o perfil de DNA da P1 Q5 — as 28 bandas foram extraídas do scan por detecção de blobs e reproduzidas altura por altura.
- ✅ **Gabaritos oficiais** nas duas provas (destaques do professor no modelo A) — única matéria em que isso aconteceu.
- ⚠️ A **Q8 da P1 saiu sem destaque no modelo A**; a resposta veio do caderno **modelo C**, onde a mesma questão aparece destacada. Lição: quando faltar destaque, procurar a questão nos outros modelos antes de inferir.
- ⚠️ Dois pontos de atenção sinalizados no material: a Q9 da P1 gera um códon de parada na 2ª posição (defeito do enunciado) e o item 02 da Q8 da P2 usa a explicação do ácido lático, hoje superada pela fisiologia — nos dois casos o material orienta responder pelo livro e confirmar com o professor.

### 🏛️ História — `historia_rec_t2.html` (RECUPERAÇÃO)
**Recuperação do Tri 2.** Convive com o material regular `estudo_historia_p2t2.html` — o card do hub tem os dois links (o `rec-link` deixou de ser "em breve").
- Professora Tâmyta nas duas provas.
- P1T2 — M12 (Império Bizantino), M13 (Islamismo), M15 (Reinos Bárbaros e Francos/Carolíngio), M16 (Feudalismo), M18 (Cruzadas). **Conteúdo novo**, não existia no hub.
- P2T2 — M19 a M23: Renascimento comercial, Crise do século XIV, Grandes Navegações, plantation e colônias inglesas, América pré-colombiana e espanhola, Reforma. **Mesmos módulos** do material regular de História P2.
- Mesmas 10 abas. Paleta vermelho → violeta (`#e94560` → `#9b6dff`).
- 20 questões reais comentadas, 24 exercícios de reforço, simulado inédito de 10 questões. Após o filtro da PRT2 (22/08): **10 conceitos, 11 cards de Dicas, 37 flashcards**.
- 🔁 **Filtrado pela PRT2:** saíram M12, M13, M21 e M22 — 6 das 20 questões ficaram fora (P1 Q1, Q5, Q10 · P2 Q3, Q9, Q10). A linha do tempo foi redesenhada (11 datas) e a Dica 4 virou "As três Reformas". Ver a seção do filtro mais abaixo.
- ✅ **Gabaritos oficiais nas duas provas** (destaques da professora no modelo A), confirmados pelos modelos C e E.
- As provas de História **não têm figuras** — todos os 15 SVGs são didáticos, criados do zero: linha do tempo com datas-âncora, cadeias causais (Revolução Agrícola → Cruzadas → Renascimento comercial), pirâmide feudal, contrato vassálico, servo × escravo, hierarquia da administração espanhola, entre outros.
- ⚠️ A alternativa d) da Q7 da P1 saiu impressa com erro de digitação ("unindo *a os* europeus cristãos"); reproduzida literalmente e sinalizada.
- 📌 **Lição da revisão adversarial:** eu tinha classificado o Cisma (1054) e as Cruzadas (1095) como Alta Idade Média. Pelo próprio roteiro (M19: "Baixa Idade Média, do século XI ao XV"), são **Baixa**. A linha do tempo foi corrigida e o material ganhou uma nota explícita sobre o corte.

### 🌏 Geopolítica — `geopolitica_p1t3.html` (P1 · Tri 3)
**Primeira matéria do 3º trimestre** — modelo de ESTUDO DE PROVA (não recuperação). Prof.ª Juliana.
- Não há livro: só o roteiro. Conteúdo montado por **pesquisa web com dados até set/2026**, cada bloco etiquetado pelo critério do roteiro (1.1, 1.2, 1.3, 2, 2.1, 2.2) e com fontes no rodapé.
- Escopo: apenas as aulas de 27/08 (China na Geopolítica Mundial) e 03/09 (Razões do crescimento chinês), conforme o roteiro. A Nova Rota da Seda entra pelo critério 2.2 (estratégia econômica e geopolítica).
- 11 abas: Visão Geral · Conteúdo · **Glossário** · Mapas Mentais · Flashcards (43) · Comparações · Linha do Tempo (31) · Radar de Armadilhas (11) · Exercícios do Roteiro · Treino Discursivo (9, imprimível com linhas) · Simulados (3×10, gabarito comentado).
- 📏 **Regra de linguagem (pedida pelo Percio em 22/09/2026):** o material não pode ficar técnico demais para um aluno de 1º ano. Todo termo é explicado na primeira vez que aparece, frases curtas, mais contexto ("por que isso importa") e nenhuma sigla órfã. O Conteúdo é **curto de propósito**: cada bloco tem "Em uma frase" + 3 a 5 tópicos + figura + "O que cai", e cabe em cerca de uma tela. Só entra o que explica o tema; exemplo extra, data secundária e episódio pontual vivem nas outras abas (Linha do Tempo, Comparações, Flashcards, Glossário) — não no corpo do texto. Regra prática: se a informação não muda o entendimento do tema, ela não fica no Conteúdo. Cuidado ao acrescentar conteúdo novo: flashcards, tabelas e simulados precisam usar o MESMO vocabulário do Conteúdo (foi onde os termos órfãos apareceram na 1ª versão).
- Paleta vermelho (China) → azul (EUA): `#ef4444` → `#60a5fa`.
- ⏳ **Pendente:** fotos do material impresso da aula de 27/08 (15 questões, códigos G1-01…G1-15) e das questões 1 e 2 discursivas da aula de 03/09 (G2-01, G2-02). A aba Roteiro está com placeholders; `imageMap` vazio pronto para receber as fotos.
- ⚠️ Assunto vivo: trégua comercial EUA–China vence em 10/nov/2026; encontro Trump–Xi em 24/09/2026. Revisar a seção 1.3 se a prova for depois de novidades.
- Hub: aba **3º Trimestre** ativada (agora é a aba padrão), card `.subject-card.geo`.

## Modalidade RECUPERAÇÃO (a partir de ago/2026)

Metodologia própria, definida pelo Percio. Difere do estudo regular de P1/P2:

- **Ponto de partida são as PROVAS que já caíram** no trimestre, não a teoria. Cada questão real vira uma aula: enunciado reproduzido → o que cobra → como interpretar → raciocínio passo a passo → análise alternativa por alternativa → conceito derivado → como pode cair de outro jeito.
- **Escopo**: se existir roteiro específico da recuperação, ele tem prioridade e filtra as questões. Se não existir, escopo = união dos roteiros de todas as provas do trimestre.
- **Priorização** por frequência nas provas + importância conceitual + dependência entre conteúdos. O material dedica proporcionalmente mais espaço ao topo da lista.
- **Conexões entre questões**: agrupar questões que dependem do mesmo conceito em "blocos", para reduzir o tamanho aparente do conteúdo.
- **Recuperação ativa** (retrieval practice): perguntas rápidas, V/F, "identifique o erro", "qual conceito uso aqui", "qual alternativa eliminaria primeiro".
- **Dicas** (aba dourada, pedida pelo Percio em 17/08/2026): o par prático dos Conceitos-chave. Enquanto Conceitos diz "o que é", Dicas diz "o que fazer na hora da prova". Um card grande por tipo de questão, com figura no topo, receita numerada curta, um exemplo real da prova e uma "cilada". Sem título de seção e sem parágrafo introdutório; o mínimo de texto e o máximo de visual. Fecha com uma **Cola de bolso** imprimível em uma página.
- **Reforço em 3 níveis**: N1 reconhecimento, N2 aplicação, N3 estilo prova. Questões inéditas, nunca cópia com números trocados.
- **Simulado final inédito** no padrão do professor (quantidade, formatos, distribuição de assuntos), imprimível.
- **Correção guiada** com classificação do tipo de erro + segundo ciclo de reforço só dos pontos fracos.
- **Padrão do professor** documentado (formatos recorrentes, tipos de distrator) — sem inventar padrões quando a evidência for insuficiente.

### Como a recuperação aparece no hub
Dentro do **trimestre correspondente** (a recuperação é trimestral). Cada card de matéria ganhou um **link secundário destacado em âmbar** "🔁 Recuperação do Nº tri" no rodapé do card — ou "em breve" quando ainda não existe material.

Para isso os cards deixaram de ser `<a>` e viraram `<div class="subject-card">` com:
- `<a class="card-overlay" href="..." aria-label="Abrir Matéria"></a>` como **primeiro filho** do card, com `position:absolute;inset:0;z-index:2` — é ele que mantém o card inteiro clicável;
- `<h2><a class="main-link" href="..." tabindex="-1">Matéria</a></h2>` só para o título;
- `<a class="rec-link">` com `z-index:4` por cima, para o link de recuperação funcionar.

⚠️ **Não** tente fazer o stretched link com `.main-link::after{inset:0}`: como `.subject-card h2` tem `position:relative`, o `inset:0` resolve contra o h2 e apenas o título fica clicável (foi exatamente o bug que apareceu na primeira versão).

Matérias **sem material regular** (caso de Química) entram com card próprio, badge "🔁 Só recuperação", e o link principal já aponta para a página de recuperação.

## Decisões importantes tomadas ao longo do projeto

1. **Enunciados dos exercícios do roteiro NÃO aparecem no card.** Só código + tags + botões. Isso porque:
   - O botão "Ver original" mostra a foto exata da página do livro.
   - Card fica compacto, cabe mais exercício por tela.
   - Evita divergência entre a paráfrase e o texto real do livro.

2. **Simulados são SEMPRE inventados por mim** (Claude), com estrutura similar às questões do livro mas números/contextos diferentes. Estes SIM têm enunciado completo + alternativas + SVG quando útil. O card mostra um botão "ℹ️ Sobre" que explica que são originais.

3. **SVGs criados por mim ficam SÓ nos simulados.** Nos exercícios do roteiro foram todos removidos — a foto original resolve.

4. **Impressão dos simulados** usa CSS `@media print` que preserva estrutura visual mas troca fundos escuros por branco. Cada questão tem espaço em branco pro aluno resolver à caneta.

5. **Modal com galeria** — cada módulo do resumo tem botão "📖 Ver páginas do livro" que abre o modal com navegação (‹ ›) entre as páginas de teoria do módulo.

## Hub central — `index.html`

Cards animados linkando pra cada matéria. Cada card tem gradiente próprio combinando com a paleta da matéria. Também tem estrelas ambiente animadas de fundo.

Cada página de matéria tem um "hub-bar" no topo com:
- `← Hub de matérias` (link pro index)
- Nome da matéria em destaque colorido
- Link pra outra matéria (varia por página)

## Estrutura de arquivos no GitHub

```
estudos-felipe/
├── index.html
├── calendario.html
├── estudo_historia_p2t1.html
├── estudo_historia_p2t2.html
├── fisica.html
├── estudo_fisica_p2t2.html
├── filosofia.html
├── matematica.html
├── quimica_rec_t2.html      (recuperação — Tri 2)
├── matematica_rec_t2.html   (recuperação — Tri 2)
├── biologia_rec_t2.html     (recuperação — Tri 2)
├── historia_rec_t2.html     (recuperação — Tri 2)
└── img/
    └── pages/         (81 fotos do livro de Matemática)
        ├── IMG_7260.jpg
        ├── IMG_7261.jpg
        └── ...
```

## Filtro do roteiro oficial da recuperação (PRT2) — aplicado em 22/08/2026

Chegou o **roteiro oficial da recuperação trimestral do 1º ano** (PDF do ClassApp, "PRT2 – CONTEÚDOS"). Ele **tem prioridade** sobre os roteiros de P1/P2, e é mais estreito. Os quatro materiais foram refiltrados segundo a regra definida pelo Percio:

> Remover o **conteúdo de estudo** dos módulos que saíram (conceitos, dicas, flashcards, reforço, simulado, cola). **Manter todas as questões das provas**, apenas marcando as que ficaram fora do roteiro.

Escopo oficial (1º ano, só as 4 matérias pedidas):

| Componente | Módulos da PRT2 |
|---|---|
| Química A | 11, 13, 14, 15, 17, 18, 19, 20, 21, 22, 23 |
| Química B | 6, 7, 8, 9, 10 |
| Matemática A | 9, 10, 11, 12, 13, 17, 18, 19, 20, 21, 23, 24 |
| Matemática B | 13, 14, 15, 16, 19, 20, 21, 22, 23, 25 |
| Biologia A | 13, 14, 15, 17, 18, 19, 20, 21 |
| Biologia B | 7, 8, 9 |
| História | 15, 16, 18, 19, 20, 23 |

### ⚗️ Química — nada a cortar
O escopo já batia exatamente. Só foi acrescentado um aviso na Visão Geral confirmando a conferência.

### 📐 Matemática — 3 questões marcadas
Fora: **Mat B M18** (ângulos em graus/minutos, complemento/replemento, relógio), **M24** (circunferência), **M26** (quadriláteros), **M27** (Tales). *Atenção: o M18 de Mat **A** continua no escopo — só o de Mat B saiu.*
- Marcadas: **P1 Q6** (parcial: itens I e II fora) · **P2 Q3** (fora) · **P2 Q7** (parcial: só itens 01 e 32).
- Ficaram **8 conceitos, 9 dicas** e 9 linhas de cola. Simulado S5 reescrito; S8 mudou de soma 51 → **43**.
- Os roteiros da **P1T2** de Matemática (VINNI = Mat A, DODL = Mat B) finalmente chegaram e estão incorporados na Visão Geral.

### 🧬 Biologia — 3 questões fora + 1 parcial
Fora: **Bio A M16** (biotecnologia) · **Bio B M3** (tipos de ovos), **M4** (protostômios×deuterostômios, tri×diblásticos), **M5** (folhetos, notocorda, celoma).
- *Detalhe que engana:* mórula, blástula, gástrula e nêurula **continuam no escopo**, porque o M8 pede a ordem completa dos eventos.
- Marcadas: **P1 Q4, Q5, Q6** (fora) · **P1 Q7** (fica, via M8) · **P1 Q10** (parcial).
- Ficaram **10 conceitos, 11 dicas**. Simulado: S4 e S5 substituídos, S10 item b reescrito.

### 🏛️ História — o corte mais pesado: 6 das 20 questões
Fora: **M12** (Bizâncio e Cisma do Oriente) · **M13** (Islamismo) · **M21** (plantation e colônias inglesas) · **M22** (pré-colombianos e América espanhola).
- Marcadas: **P1 Q1, Q5, Q10** · **P2 Q3, Q9, Q10**.
- Ficaram **10 conceitos, 11 dicas**. A **linha do tempo foi redesenhada** (14 → 11 datas) e a Dica 4 virou **"As três Reformas — e a resposta de Roma"** (luteranismo · calvinismo · anglicanismo · Contrarreforma), com figura nova.
- Simulado: S1, S2 e S9 substituídos; S8 e S10 reescritos em parte.

Todos os quatro passaram por revisão adversarial antes da entrega, que ainda encontrou e corrigiu erros reais (referências cruzadas desatualizadas, tabelas de gabarito não sincronizadas, "mediação papal" em Tordesilhas, contagens órfãs).

## O que está pendente / próximos passos possíveis

- **Q. 17 do M27 (Tales) do roteiro de Matemática** — não achei nas fotos, deixei sem mapear. O M27 saiu da PRT2, então virou irrelevante para a recuperação.
- **Gabarito oficial da P1T2 de Química** — o arquivo recebido era o caderno de prova, não a folha de respostas. As respostas da P1 no material foram resolvidas e conferidas manualmente. Se o gabarito oficial aparecer, conferir.
- **Recuperação das demais matérias do 1º ano** (Física, Geografia, Português, Filosofia, Literatura, Inglês, Redação, Geopolítica): o roteiro da PRT2 já traz os módulos de todas elas, mas o Percio disse em 22/08 que **só precisa de Matemática, Biologia, História e Química**. Se mudar de ideia, o roteiro está em memória.
- **Recuperação do T1** (Filosofia, Física, História): cards já existem no hub marcados "em breve". Faltam as provas para construir.
- **Próximas provas (P1 T3, P2 T3, etc.)** — cada nova prova ganha um HTML próprio ou vira aba adicional na página da matéria.

## Detalhes técnicos úteis

- **KaTeX** carregado via CDN: `<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.16.9/dist/katex.min.css">` + script.
- Delimitadores KaTeX: `$$...$$` para display, `$...$` para inline.
- Ícones: uso emojis (🏛️ 📐 ⚛️ 📚 etc.) — sem dependência externa.
- Fontes: Segoe UI (fallback pra system-ui) para texto, Cambria Math / Georgia para fórmulas.
- Estilo padrão do card de matéria:
  - Border-radius 14-20px
  - Sombra: `0 10px 30px rgba(0,0,0,.45-.55)`
  - Bordas transparentes brancas (5-8%)
  - Backgrounds em cores dark (#0a0d1a até #302b63)
