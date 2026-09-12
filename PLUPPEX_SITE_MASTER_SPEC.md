# PLUPPEX — SITE MASTER SPEC
## Blueprint de reconstrução da Landing Page com animações, efeitos e interações

> **OBJETIVO**
>
> Reconstruir a landing page da PLUPPEX exatamente de acordo com o blueprint visual fornecido junto deste arquivo.
>
> A imagem de referência é o **blueprint visual principal**. Não utilizar a imagem como uma imagem estática ocupando a página. O site deve ser reconstruído em componentes HTML/CSS/React reais, preservando a composição, hierarquia, atmosfera, proporções e linguagem visual do blueprint, mas transformando os elementos em uma experiência web viva, responsiva, interativa e animada.
>
> **Regra principal:** a referência visual define o resultado visual. Este documento define comportamento, conteúdo, arquitetura, animação e implementação.

---

# 01. DIREÇÃO CRIATIVA

A PLUPPEX deve parecer uma empresa de tecnologia e operação comercial de alto nível, e não uma agência tradicional.

A experiência precisa transmitir:

- tecnologia proprietária;
- inteligência;
- precisão;
- velocidade;
- operação;
- dados;
- conexão;
- crescimento;
- geração de receita.

A página inteira deve funcionar como uma **jornada**.

O visitante não deve simplesmente rolar por blocos institucionais. Ele deve sentir que está entrando na própria máquina de receita da PLUPPEX.

### Ideia central

**VENDER É CIÊNCIA, NÃO SORTE!**

### Conceito

**DO SINAL À RECEITA.**

A narrativa visual da página é:

```text
SINAL
↓
INFORMAÇÃO
↓
AÇÃO
↓
CONVERSÃO
↓
RECEITA
```

A máquina da PLUPPEX transforma sinais comerciais em dados, inteligência, ação e receita.

---

# 02. REGRA DE FIDELIDADE AO BLUEPRINT

A página deve reproduzir a linguagem visual do blueprint:

- fundo predominantemente preto;
- atmosfera tecnológica escura;
- gradientes discretos em roxo, azul e ciano;
- linhas de energia;
- pontos de dados;
- grids;
- partículas muito sutis;
- interfaces translúcidas;
- cards com bordas finas;
- brilho controlado;
- tipografia grande;
- muito espaço negativo;
- elementos centralizados e equilibrados;
- estética premium;
- sensação de sistema operacional comercial.

Não transformar o site em:

- cyberpunk;
- gamer;
- neon exagerado;
- dashboard SaaS genérico;
- landing page de agência;
- site cheio de stock photos;
- site excessivamente colorido.

A tecnologia deve parecer sofisticada, não chamativa.

---

# 03. PALETA

Usar como base:

```text
BLACK       #050505
WHITE       #F5F5F5
PURPLE      #743EE4
```

O roxo é a cor principal de ação.

O azul/ciano pode aparecer somente como extensão visual dos gradientes e estados tecnológicos da marca, sem competir com o roxo.

### Distribuição visual aproximada

```text
60% preto
30% branco
10% roxo / gradientes tecnológicos
```

Não introduzir novas cores sem necessidade.

---

# 04. TIPOGRAFIA

Usar **Inter**.

Hierarquia:

### H1
64–80px desktop
700–800 weight

### H2
42–56px
700–800 weight

### H3
22–28px
650–700 weight

### Body
17–19px
400–500 weight

### Labels
10–12px
600–700 weight
letter-spacing alto
uppercase

Mobile:

- H1: 38–48px
- H2: 32–40px
- body: 16–18px

---

# 05. HEADER

O header deve permanecer visualmente próximo ao blueprint.

### Estrutura

Esquerda:

**LOGO ORIGINAL DA PLUPPEX**

Centro:

- PARA SUA EMPRESA
- ATENDIMENTO AO CLIENTE

Direita:

**CONTRATE A PLUPPEX**

### Comportamento

Header fixo/sticky.

No início:

- transparente;
- integrado ao fundo do hero.

Ao rolar:

- fundo preto semitransparente;
- blur;
- borda inferior extremamente discreta.

### CTA

Gradiente roxo → azul/ciano muito sutil.

Hover:

- brilho aumenta;
- botão sobe 1–2px;
- sombra suave.

Não exagerar.

---

# 06. HERO — PRESERVAR COMO REFERÊNCIA PRINCIPAL

A primeira dobra deve seguir o blueprint visual.

### Headline

**VENDER É CIÊNCIA, NÃO SORTE!**

### Texto

**Conectamos tráfego pago, tecnologia proprietária, CRM sob medida e automações com inteligência artificial para otimizar seu tempo, gerar mais oportunidades e transformar conversas em contratos fechados e dinheiro no caixa.**

### CTA

**CONTRATE A PLUPPEX**

---

# 07. FUNDO DO HERO

Usar o símbolo/X/rocket da PLUPPEX como elemento visual central.

O símbolo deve aparecer:

- grande;
- parcialmente oculto;
- atrás do conteúdo;
- com baixa opacidade;
- com glow discreto;
- integrado ao fundo.

Adicionar:

- partículas;
- linhas diagonais;
- pontos;
- pequenos grids;
- pequenos sinais luminosos.

### Movimento

O fundo deve possuir movimento extremamente lento.

Exemplos:

- partículas deslocando poucos pixels;
- linhas de energia percorrendo o fundo;
- glow pulsando lentamente;
- símbolo fazendo parallax muito sutil.

Nada deve competir com o texto.

---

# 08. JOURNEY TRACKER

Na parte inferior do hero:

### Título

**A JORNADA DO SEU CLIENTE — DO SINAL À RECEITA**

Linha horizontal:

```text
SINAL
──────
INFORMAÇÃO
──────
AÇÃO
──────
CONVERSÃO
──────
RECEITA
```

Cada etapa possui:

### SINAL

Alguém demonstra interesse na sua empresa.

### INFORMAÇÃO

O sinal entra na operação e vira dado.

### AÇÃO

A equipe age no momento certo.

### CONVERSÃO

A oportunidade avança e fecha.

### RECEITA

O contrato entra no caixa.

### Animação

Ao carregar a página:

1. linha aparece;
2. pontos aparecem;
3. uma energia percorre a linha;
4. cada etapa acende;
5. RECEITA termina destacada.

No scroll, o tracker deve poder reagir ao progresso da página.

---

# 09. SEÇÃO — SUA EMPRESA JÁ TEM SINAIS

Após o hero, reduzir a intensidade visual.

### Label

**PROBLEMA REAL**

### Headline

**SUA EMPRESA JÁ TEM SINAIS.**

### Destaque

**O problema é que eles estão espalhados.**

### Texto

Leads no anúncio. Conversas no WhatsApp. Oportunidades no CRM. Follow-ups na cabeça do vendedor. Dados em planilhas. Decisões baseadas em sensação.

### Frase final

**A PLUPPEX CONECTA TUDO ISSO.**

---

# 10. DIAGRAMA DE DADOS

À direita da seção anterior, criar uma composição tecnológica.

Cards independentes:

```text
META ADS
WHATSAPP
INSTAGRAM
PLANILHAS
CRM
RELATÓRIOS
VENDEDORES
```

Todos conectados por linhas ao centro.

No centro:

### PLUPPEX

com o símbolo/X.

As linhas devem parecer fluxos de informação.

### Animação

Quando o usuário chega na seção:

- cards entram em sequência;
- linhas são desenhadas;
- pequenos pontos percorrem as linhas;
- o centro acende;
- tudo fica conectado.

---

# 11. CTA DE DIAGNÓSTICO

Botão:

**ISSO PARECE COM A SUA REALIDADE? →**

Ao clicar:

abrir modal ou levar suavemente para o diagnóstico.

Não sair da página.

---

# 12. SEÇÃO — A SOLUÇÃO

### Label

**SOLUÇÃO PLUPPEX**

### Headline

**UMA OPERAÇÃO COMERCIAL CONECTADA PARA GERAR, CONVERTER E ESCALAR RECEITA.**

Texto:

**A Pluppex conecta aquisição, tecnologia, inteligência e operação para transformar sinais em receita.**

CTA:

**CONHEÇA A MÁQUINA**

---

# 13. FLUXO DA MÁQUINA

Criar uma linha horizontal tecnológica:

```text
AQUISIÇÃO
↓
S.P.Y. | CRM
↓
AURORA
↓
OPERAÇÃO
↓
RECEITA
```

### AQUISIÇÃO

Gera oportunidades.

### S.P.Y. | CRM

Organiza a operação.

### AURORA

Entende, recomenda e age.

### OPERAÇÃO

A equipe executa.

### RECEITA

Oportunidades viram negócios.

### Interação

Ao passar o mouse sobre cada etapa:

- etapa aumenta;
- glow aparece;
- descrição fica mais forte;
- linha de conexão acende;
- informação contextual aparece.

No mobile, transformar em fluxo vertical.

---

# 14. SEÇÃO — O QUE FAZ A MÁQUINA FUNCIONAR?

### Label

**CONHEÇA AS SOLUÇÕES**

### Headline

**O QUE FAZ A MÁQUINA FUNCIONAR?**

Subheadline:

**Tudo o que sua empresa precisa, conectado.**

Criar tabs:

```text
AQUISIÇÃO
S.P.Y. | CRM
AURORA
OPERAÇÃO
```

A aba ativa utiliza roxo.

---

# 15. ABA AQUISIÇÃO

### Headline

**MAIS OPORTUNIDADES ENTRANDO.**

Texto:

Tráfego pago, criativos, landing pages, funis e estratégias de geração de demanda para colocar novas oportunidades na operação.

Lista:

- Tráfego pago
- Criativos que convertem
- Landing pages
- Funis de vendas
- Estratégia de aquisição
- Otimização de campanhas

CTA:

**QUERO GERAR MAIS OPORTUNIDADES**

### Visual

Criar uma interface de campanha / aquisição.

Pode conter:

- leads gerados;
- conversões;
- campanhas;
- gráfico;
- anúncio;
- celular com anúncio.

Os números devem ser apresentados como **dados demonstrativos**, nunca como resultados reais da PLUPPEX.

---

# 16. ABA S.P.Y. | CRM

### Headline

**NENHUMA OPORTUNIDADE DEVERIA DESAPARECER.**

Texto:

O S.P.Y. organiza leads, oportunidades, conversas, follow-ups e processos em uma única operação comercial.

### Visual

Usar a interface real do S.P.Y. quando disponibilizada.

Não inventar funcionalidades.

Criar animação de:

- lead entrando;
- oportunidade criada;
- mudança de estágio;
- follow-up;
- vendedor recebendo ação.

---

# 17. ABA AURORA

### Headline

**SUA OPERAÇÃO TAMBÉM PRECISA PENSAR.**

Texto:

A Aurora transforma dados, conversas e eventos da operação em inteligência, recomendações e ações.

Lista:

- Análise de conversas
- Detecção de oportunidades
- Priorização
- Recomendação de ações
- Alertas
- Automação inteligente

Frase:

**SEU CRM NÃO DEVERIA APENAS LEMBRAR. DEVERIA PERCEBER.**

---

# 18. AURORA EM AÇÃO

Esta deve ser uma das seções mais impressionantes do site.

### Headline

**SUA OPERAÇÃO RESPONDE A VOCÊ.**

Subheadline:

**Pergunte. Consulte. Solicite.**

Criar uma interface de chat.

### Exemplo de interação

Usuário:

> Quantos leads entraram esta semana?

Aurora:

> 147 oportunidades entraram na operação.
> 38 ainda não receberam contato.
> 11 apresentam alta intenção.

Usuário:

> Quais oportunidades estão paradas?

Aurora:

> Encontrei 17 oportunidades sem interação nos últimos 3 dias.
> 6 apresentam sinais recentes de intenção.

Usuário:

> Cria um follow-up para essas oportunidades.

Aurora:

> Follow-ups preparados.
> 6 oportunidades priorizadas.

### Animação

As mensagens devem aparecer uma por vez.

O cursor deve piscar.

A resposta deve ter pequeno efeito de processamento.

Não usar efeito de digitação exageradamente lento.

---

# 19. WHATSAPP → AURORA → S.P.Y. → RECEITA

### Label

**DO WHATSAPP AO CAIXA**

### Headline

**A OPERAÇÃO PODE COMEÇAR COM UMA MENSAGEM.**

Texto:

O cliente fala. A Aurora entende. O S.P.Y. organiza. Sua equipe age. A receita acontece.

Criar fluxo visual:

```text
CLIENTE
↓
WHATSAPP
↓
AURORA
↓
S.P.Y. | CRM
↓
EQUIPE
↓
RECEITA
```

---

# 20. EXEMPLO DE CONVERSA

Cliente:

> Queria saber se ainda tem disponibilidade para começar esse mês.

Aurora interpreta:

```text
NOVA OPORTUNIDADE

INTENÇÃO: ALTA
ESTÁGIO: DECISÃO
AÇÃO: CONTATO IMEDIATO
```

S.P.Y.:

```text
NOVO LEAD
EM ACOMPANHAMENTO
PROPOSTA ENVIADA
NEGOCIAÇÃO
FECHADO
```

Receita:

**CONTRATO**

### Animação

A mensagem deve literalmente viajar pelo fluxo.

Um ponto luminoso representa a oportunidade.

---

# 21. RADAR DE OPORTUNIDADES

### Headline

**A AURORA ENXERGA O QUE PODE PASSAR DESPERCEBIDO.**

Cards:

### OPORTUNIDADE DETECTADA

Lead respondeu.

**Alta intenção detectada.**

---

### FOLLOW-UP

Oportunidade sem contato há 4 dias.

**Follow-up recomendado.**

---

### SINAL DE COMPRA

Conversa apresenta sinal de decisão.

**Prioridade comercial aumentada.**

Os cards aparecem conforme o usuário entra na seção.

---

# 22. OPERAÇÃO

### Headline

**FAZEMOS A MÁQUINA DE RECEITA FUNCIONAR.**

Texto:

RevOps, processos, tecnologia, integrações, automações, BI e gestão da performance.

### Cards

- Processos comerciais
- Tecnologia
- Integrações
- Automação
- Business Intelligence
- Indicadores
- Gestão da performance
- Gestão financeira comercial

Frase:

**UMA OPERAÇÃO QUE MELHORA CONTINUAMENTE.**

---

# 23. MODELOS DE ENTREGA

### Headline

**VOCÊ NÃO PRECISA CONTRATAR TUDO.**

Texto:

A Pluppex entra onde sua operação precisa.

Quatro cards:

### PROJETO

Para resolver um problema específico.

### MÓDULO

Para adicionar uma capacidade à operação.

### OPERAÇÃO

Para ter a Pluppex atuando junto com sua equipe.

### MÁQUINA COMPLETA

Para conectar aquisição, tecnologia, inteligência e operação.

Cada card deve possuir:

- borda;
- pequeno ícone;
- hover;
- descrição curta;
- CTA.

---

# 24. CONFIGURADOR

### Headline

**MONTE A MÁQUINA QUE SUA EMPRESA PRECISA.**

Pergunta:

**O que você precisa resolver?**

Opções:

- Gerar mais oportunidades
- Organizar o comercial
- Automatizar tarefas
- Melhorar conversão
- Enxergar os números
- Escalar a operação

O visitante pode selecionar múltiplas opções.

À direita, construir visualmente:

```text
SUA MÁQUINA

✓ AQUISIÇÃO
✓ S.P.Y. | CRM
✓ AURORA
✓ OPERAÇÃO
```

Resultado:

**Sua operação precisa de uma combinação de aquisição, organização comercial e inteligência.**

CTA:

**VER SUGESTÃO PARA MINHA EMPRESA**

Não apresentar preço.

O objetivo é diagnóstico e geração de lead.

---

# 25. SEGMENTAÇÃO

### Headline

**CADA EMPRESA ESTÁ EM UM MOMENTO.**

Três estados:

### CRESCER

Para empresas que precisam gerar mais oportunidades.

### ORGANIZAR

Para empresas que precisam colocar a operação em ordem.

### ESCALAR

Para empresas que precisam crescer sem aumentar a complexidade na mesma proporção.

Ao selecionar cada opção, o site deve mudar visualmente o fluxo recomendado.

---

# 26. PROVA / CASES

Reservar espaço visual para provas reais.

### Headline

**RESULTADOS REAIS. OPERAÇÕES MAIS FORTES.**

Não inventar números.

Não inventar depoimentos.

Não inventar logos de clientes.

Usar apenas dados, logos, prints e depoimentos fornecidos posteriormente.

Enquanto os cases não forem inseridos, manter a seção preparada para receber:

- logo;
- problema;
- solução;
- resultado;
- depoimento;
- screenshot;
- métricas.

---

# 27. SOBRE A PLUPPEX

Manter curto.

### Headline

**NÃO SOMOS UMA AGÊNCIA.**

Texto:

Também não somos apenas uma empresa de tecnologia.

Construímos e operamos máquinas de receita conectando marketing, tecnologia, inteligência artificial, CRM e operação comercial.

CTA:

**CONHECER A PLUPPEX**

---

# 28. CTA FINAL

A página deve desacelerar visualmente.

Fundo predominantemente preto.

Poucos elementos.

### Headline

**DESCUBRA O QUE ESTÁ TRAVANDO SUA RECEITA.**

Texto:

Vamos olhar para sua operação, identificar o principal gargalo e mostrar qual estrutura faz sentido para o seu momento.

CTA:

**CONTRATE A PLUPPEX**

Abaixo:

**VENDER É CIÊNCIA, NÃO SORTE!**

---

# 29. FOOTER

Logo PLUPPEX.

Links:

- Para sua empresa
- O que fazemos
- Como funciona
- S.P.Y. | CRM
- Aurora
- Sobre

Contato:

- Instagram
- LinkedIn
- WhatsApp

Rodapé:

**© 2026 PLUPPEX. Todos os direitos reservados.**

Links legais:

- Política de Privacidade
- Termos de Uso

---

# 30. SISTEMA DE ANIMAÇÕES

A página deve ser animada, mas elegante.

## Scroll reveal

Elementos entram com:

- opacity;
- translateY;
- scale muito sutil.

Duração:

400–800ms.

Easing:

ease-out.

Nunca utilizar animações exageradas.

---

## Parallax

Usar somente em:

- símbolo/X;
- linhas;
- partículas;
- elementos de fundo.

Amplitude pequena.

---

## Data flow

Criar pequenos pontos luminosos viajando por:

- linhas;
- conexões;
- fluxos;
- jornada;
- CRM → Aurora → operação.

A velocidade deve ser lenta e natural.

---

## Hover

Cards:

- border glow;
- translateY(-2px);
- sombra sutil.

Buttons:

- brilho;
- pequena elevação;
- seta desloca poucos pixels.

---

## Scroll progress

A jornada:

```text
SINAL
→ INFORMAÇÃO
→ AÇÃO
→ CONVERSÃO
→ RECEITA
```

deve reagir ao progresso do usuário.

---

# 31. TRANSIÇÕES ENTRE SEÇÕES

As seções não devem parecer blocos independentes.

Criar continuidade visual através de:

- linhas;
- gradientes;
- partículas;
- pontos;
- conexões;
- elementos que atravessam a borda das seções.

A sensação deve ser de uma única máquina contínua.

---

# 32. EFEITO DE PROFUNDIDADE

Usar camadas:

```text
BACKGROUND
↓
GRID / PARTICLES
↓
ENERGY LINES
↓
BRANDING
↓
UI
↓
TEXT
↓
CTA
```

O conteúdo principal deve permanecer sempre legível.

---

# 33. RESPONSIVIDADE

Desktop primeiro, mas construir corretamente para mobile.

No mobile:

- header vira menu;
- fluxo horizontal vira vertical;
- tabs viram accordion ou swipe;
- dashboards podem receber scroll horizontal controlado;
- textos não devem ficar pequenos;
- CTA permanece fácil de tocar;
- animações são reduzidas;
- partículas diminuem;
- nenhum elemento deve causar overflow horizontal.

---

# 34. PERFORMANCE

Não criar efeitos pesados que prejudiquem carregamento.

Preferir:

- CSS;
- SVG;
- Framer Motion ou equivalente;
- transforms;
- opacity;
- requestAnimationFrame quando necessário.

Evitar:

- vídeos pesados;
- dezenas de canvases;
- partículas excessivas;
- efeitos 3D desnecessários.

Respeitar:

```css
prefers-reduced-motion
```

para usuários que preferem menos animação.

---

# 35. IMPLEMENTAÇÃO

Stack recomendada:

- React
- TypeScript
- Tailwind CSS
- Framer Motion

Componentizar:

```text
Header
Hero
JourneyTracker
SignalProblem
ConnectedOperation
MachineFlow
SolutionsTabs
AcquisitionPanel
SpyPanel
AuroraPanel
AuroraDemo
WhatsappFlow
OpportunityRadar
OperationSection
DeliveryModels
MachineConfigurator
GrowthStages
Cases
About
FinalCTA
Footer
```

Cada componente deve ser reutilizável.

---

# 36. INTERAÇÕES IMPORTANTES

O site deve ter interações reais.

### CTA

Todos os CTAs de contratação devem abrir o mesmo fluxo de contato/diagnóstico.

### Tabs

As abas devem alterar conteúdo sem recarregar a página.

### Aurora

O chat deve simular conversa.

### Configurador

As escolhas devem alterar o resultado.

### Journey

O fluxo deve reagir ao scroll.

### Cards

Hover deve gerar feedback visual.

---

# 37. FORMULÁRIO DE DIAGNÓSTICO

Quando o usuário clicar em:

**CONTRATE A PLUPPEX**

abrir uma experiência curta de diagnóstico.

Perguntas:

### 01

**O que você precisa melhorar hoje?**

- Gerar oportunidades
- Converter mais
- Organizar o comercial
- Automatizar
- Enxergar os números
- Escalar

### 02

**Como sua operação comercial funciona hoje?**

Campo aberto.

### 03

**Qual o melhor contato?**

Nome + WhatsApp + e-mail.

CTA final:

**QUERO DIAGNOSTICAR MINHA OPERAÇÃO**

---

# 38. MICROCOPY

Usar frases curtas ao longo da experiência.

Exemplos:

**SINAL DETECTADO**

**DADO RECEBIDO**

**ANÁLISE EM ANDAMENTO**

**OPORTUNIDADE IDENTIFICADA**

**AÇÃO RECOMENDADA**

**FOLLOW-UP NECESSÁRIO**

**CONVERSÃO**

**RECEITA GERADA**

Essas mensagens podem aparecer em pequenas interfaces e estados.

---

# 39. REGRAS DE COPY

Tom:

- direto;
- inteligente;
- confiante;
- tecnológico;
- comercial;
- sem exagero;
- sem buzzwords vazias.

Não usar frases como:

- “revolucionamos o mercado”;
- “solução 360°”;
- “ecossistema disruptivo”;
- “tecnologia de ponta” sem explicar;
- “IA que transforma tudo”.

Sempre mostrar **o que acontece**.

---

# 40. REGRA SOBRE A AURORA

Não apresentar Aurora como um produto separado da PLUPPEX.

A arquitetura correta é:

```text
PLUPPEX
   ↓
MÁQUINA DE RECEITA
   ↓
S.P.Y. | CRM + AURORA
```

**S.P.Y. é onde a equipe opera.**

**Aurora é a inteligência que opera por trás.**

A experiência pode mostrar os dois separadamente para explicar a tecnologia, mas nunca comunicar que são dois produtos concorrentes ou duas plataformas independentes.

---

# 41. REGRA SOBRE A IMAGEM DE REFERÊNCIA

A imagem fornecida deve ser tratada como **referência visual de alta fidelidade**.

Não substituir a composição por um template genérico.

Não reduzir a página a uma coleção de cards.

Não criar uma landing page SaaS padrão.

Não usar a imagem inteira como background.

Reconstruir os elementos.

Quando houver dúvida entre “criar algo novo” e “seguir o blueprint”, seguir o blueprint.

---

# 42. RESULTADO ESPERADO

Quando o site estiver pronto, o visitante deve conseguir entender em poucos segundos:

### O QUE É A PLUPPEX

Uma empresa que constrói e opera máquinas de receita.

### O QUE ELA FAZ

Conecta aquisição, CRM, tecnologia, inteligência e operação.

### COMO FUNCIONA

```text
SINAL
→ DADO
→ INTELIGÊNCIA
→ AÇÃO
→ CONVERSÃO
→ RECEITA
```

### O QUE É O S.P.Y.

O ambiente onde a operação comercial acontece.

### O QUE É A AURORA

A inteligência que entende os dados e ajuda a operação a agir.

### COMO CONTRATAR

Projeto, Módulo, Operação ou Máquina Completa.

### QUAL É O PRÓXIMO PASSO

**CONTRATE A PLUPPEX.**

---

# 43. CRITÉRIO FINAL DE QUALIDADE

Antes de considerar o site pronto, verificar:

- [ ] O primeiro viewport parece com o blueprint.
- [ ] O logo original foi preservado.
- [ ] A paleta está correta.
- [ ] O Head está exatamente com a copy aprovada.
- [ ] A jornada Sinal → Receita está visualmente presente.
- [ ] A página possui continuidade visual.
- [ ] O site parece tecnológico sem parecer gamer.
- [ ] O site parece uma empresa de tecnologia/operação, não uma agência.
- [ ] O S.P.Y. aparece como produto real.
- [ ] A Aurora possui uma demonstração interativa.
- [ ] Existe fluxo WhatsApp → Aurora → S.P.Y. → Receita.
- [ ] O configurador funciona.
- [ ] Os CTAs funcionam.
- [ ] O formulário funciona.
- [ ] Não existem números ou resultados inventados.
- [ ] Não existem cases inventados.
- [ ] O mobile funciona.
- [ ] Não existe overflow horizontal.
- [ ] As animações são suaves.
- [ ] `prefers-reduced-motion` é respeitado.
- [ ] A página mantém performance adequada.

---

# INSTRUÇÃO FINAL PARA O AGENTE

**Não entregue apenas uma réplica visual estática.**

Construa uma experiência web completa.

A imagem é o blueprint.

O código deve transformar o blueprint em uma **máquina visual interativa**.

Cada seção deve ter propósito dentro da jornada.

Cada animação deve reforçar a ideia de:

**SINAL → INFORMAÇÃO → INTELIGÊNCIA → AÇÃO → CONVERSÃO → RECEITA**

O visitante deve terminar a página pensando:

> **“Eu não preciso de mais uma ferramenta. Preciso organizar e fazer minha operação funcionar.”**

E então:

**CONTRATE A PLUPPEX.**
