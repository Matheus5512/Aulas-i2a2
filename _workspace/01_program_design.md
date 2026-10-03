# 01 — Desenho do Programa de Treino

> Autor: **program-architect** · Base: `00_input.md` · Referências: diretrizes ACSM/NSCA, skill `periodization-engine` (periodização linear para iniciantes, hipertrofia).

## Perfil

| Item | Valor |
|------|-------|
| Objetivo | Hipertrofia (ganho de massa muscular) |
| Experiência | Iniciante — sem histórico estruturado de treino |
| Disponibilidade | 4 sessões/semana, ~60 min/sessão |
| Equipamento | Academia completa (barras, halteres, máquinas, polias) |
| Dados físicos | Homem, 28 anos, 178 cm, 75 kg (IMC ≈ 23,7) |
| Lesões | Nenhuma informada |
| Programa atual | Nenhum |

## Análise do Objetivo

- **Hipertrofia em iniciante**: a resposta ao treino é rápida e quase qualquer estímulo bem executado gera ganho. O fator limitante é **técnica e consistência**, não volume extremo. Por isso o programa começa com volume baixo/moderado, prioriza o aprendizado motor e só depois sobe volume e intensidade.
- **Estímulo-alvo**: 8–14 séries semanais por grupo muscular (entre o "mínimo efetivo" de 6 e o "máximo recuperável" de 16 para iniciantes), cada grupo treinado **2×/semana**, maioria das séries a RPE 7–9 (1–3 repetições em reserva).
- **Faixas de repetição**: predominância de 6–15 reps, que é a faixa mais eficiente para hipertrofia; uma fase de intensificação (5–8 reps nos compostos) é incluída para ganhar força, o que permite usar cargas maiores no ciclo seguinte de volume.
- **Por que periodização linear**: é o modelo recomendado para iniciantes e objetivos de hipertrofia. É simples de seguir e de registrar, e a progressão de carga semana a semana é previsível.

## Visão Geral do Programa

- **Duração total**: 12 semanas
- **Divisão (split)**: Superior/Inferior (Upper/Lower), 4 dias — Superior A · Inferior A · Superior B · Inferior B
- **Frequência semanal**: 4 sessões (cada grupo muscular 2×/semana)
- **Duração da sessão**: ~60 min (8–10 min de aquecimento + 45–50 min de trabalho + 3–5 min de volta à calma)
- **Dias sugeridos**: Seg (Superior A) · Ter (Inferior A) · Qua (descanso) · Qui (Superior B) · Sex (Inferior B) · Sáb/Dom (descanso)

### Por que Superior/Inferior?

| Critério | Full body 3× | **Superior/Inferior 4×** | PPL / por grupo |
|---|---|---|---|
| Frequência por músculo | 3× | **2× (ideal p/ hipertrofia)** | 1–2× |
| Sessão cabe em 60 min | Difícil com 4 dias | **Sim** | Sim |
| Recuperação entre dias seguidos | Ruim (mesmos músculos) | **Boa (alterna metades do corpo)** | Boa |
| Simplicidade p/ iniciante | Alta | **Alta** | Média/baixa |

Com 4 dias disponíveis, a divisão Superior/Inferior é o padrão da skill `periodization-engine` e oferece a melhor relação entre frequência, volume por sessão e recuperação.

## Plano de Periodização (Macrociclo de 12 semanas)

| Fase | Semanas | Objetivo | Volume | Intensidade (%1RM estimado) | RPE alvo | Observações |
|------|---------|----------|--------|------------------------------|----------|-------------|
| **1. Adaptação** | 1–3 | Aprender técnica, adaptar tendões e articulações, encontrar cargas de trabalho | Baixo → moderado (52 → 64 séries/sem) | 60–67% | 6–7 | S1 = familiarização (2 séries por exercício). Nenhuma série perto da falha. |
| **2. Acumulação** | 4–7 | Maximizar estímulo hipertrófico pelo aumento de volume | Alto (82 → 86 séries/sem) | 67–77% | 7–8 (isoladores 8–9) | S6–7 = pico de volume do ciclo. Progressão principal por reps e séries. |
| **3. Intensificação** | 8–11 | Aumentar carga e força nos compostos mantendo volume moderado | Moderado (82 séries/sem, menos reps por série) | 77–85% | 8–9 | Compostos 5–8 reps. S10–11 = semanas mais pesadas. |
| **4. Deload** | 12 | Dissipar fadiga, consolidar ganhos, preparar o próximo ciclo | ~50% (≈40 séries/sem) | ~60% | 5–6 | Mesmos exercícios, metade das séries, cargas leves. Re-teste opcional no fim. |

### Mesociclos e microciclos

- **Macrociclo**: 12 semanas, um único objetivo (hipertrofia) com uma janela de força (S8–11).
- **Mesociclos**: as 4 fases acima. Cada uma tem parâmetros fixos de séries/reps/RPE por categoria de exercício (ver tabela abaixo e o `02_weekly_schedule.md`).
- **Microciclo (semana)**: Sup A → Inf A → descanso → Sup B → Inf B → 2 dias de descanso. Nunca mais de 2 dias seguidos de treino.

### Parâmetros por categoria de exercício e fase

Cada exercício do programa pertence a uma categoria:
- **P** = Principal (composto, primeiro da sessão)
- **S** = Secundário (composto ou multiarticular de apoio). **S1** é o primeiro secundário da sessão.
- **A** = Acessório (isolador)
- **C** = Core (estabilização)

| Categoria | Adaptação (S1–3) | Acumulação (S4–7) | Intensificação (S8–11) | Deload (S12) |
|---|---|---|---|---|
| **P** | 3×10–12 @RPE 6–7 · desc. 2 min | 4×8–10 @RPE 7–8 · desc. 2–2,5 min | 4×5–7 @RPE 8 (S8–9) → 8–9 (S10–11) · desc. 2,5–3 min | 2×6–8 @RPE 5–6 · desc. 2 min |
| **S** | 3×10–12 @RPE 6–7 · desc. 90 s | 3×10–12 @RPE 7–8 · desc. 90–120 s · **S1 faz 4 séries nas S6–7** | 3×6–8 @RPE 8–9 · desc. 90–120 s | 2×8–10 @RPE 6 · desc. 90 s |
| **A** | 2×12–15 @RPE 7 · desc. 60 s | 3×12–15 @RPE 8–9 · desc. 60–75 s | 3×10–12 @RPE 8–9 (última série pode ir a 9–10 em máquina) · desc. 75–90 s | 1×12 @RPE 6 · desc. 60 s |
| **C** | 2× 20–30 s (ou 8–10 reps/lado) | 3× 30–45 s (ou 10–12 reps/lado) | 3× 40–60 s (ou 12–15 reps/lado) | 2× 20–30 s |

**Semana 1 (familiarização)**: todos os exercícios fazem **2 séries**, com os parâmetros de reps/RPE da Adaptação.

### Volume semanal total (séries de trabalho)

| Semana | 1 | 2–3 | 4–5 | 6–7 | 8–11 | 12 |
|---|---|---|---|---|---|---|
| Séries/semana | 52 | 64 | 82 | 86 | 82 | 40 |
| Séries/sessão (média) | 13 | 16 | 20–21 | 21–22 | 20–21 | 10 |

> Os aumentos de séries ficam concentrados nas viradas de fase (S1→S2 e S3→S4). Para compensar, a **primeira semana de cada fase usa o limite inferior do RPE alvo**. Nas viradas, as reps por série também caem (10–12 → 8–10 nos compostos), então o volume em reps totais cresce bem menos que o número de séries.

## Estrutura da Divisão

| Dia | Sessão | Grupos musculares principais | Exercícios-chave |
|-----|--------|------------------------------|------------------|
| Seg | **Superior A** (ênfase horizontal) | Peito, costas (espessura), ombros, braços | Supino reto com barra, Remada curvada com barra, Desenvolvimento com halteres |
| Ter | **Inferior A** (ênfase quadríceps) | Quadríceps, posteriores, panturrilha, core | Agachamento livre com barra, Leg press 45° |
| Qua | Descanso | — | Caminhada leve/cardio Z2 opcional (20–30 min) + mobilidade |
| Qui | **Superior B** (ênfase inclinada/vertical) | Peito superior, dorsais (largura), deltoide posterior, braços | Supino inclinado com halteres, Puxada supinada, Remada sentada no cabo |
| Sex | **Inferior B** (ênfase cadeia posterior) | Posteriores, glúteos, quadríceps, panturrilha, core | Levantamento terra romeno, Agachamento búlgaro, Elevação pélvica |
| Sáb/Dom | Descanso | — | Atividade leve opcional |

Se a semana do usuário mudar: manter a ordem Sup A → Inf A → Sup B → Inf B e **pelo menos 1 dia de descanso entre os blocos de 2 sessões**. Uma sessão perdida é feita no próximo dia livre; não se compensam duas sessões no mesmo dia.

## Diretrizes de Volume e Intensidade (por grupo muscular)

Séries de trabalho diretas por semana (Adaptação S2–3 / Acumulação S6–7 / Intensificação):

| Grupo muscular | Exercícios que contam | Séries/semana | Faixa de reps | RPE | Descanso |
|---|---|---|---|---|---|
| Peito | Supino reto, Supino inclinado, Crucifixo máquina | 8 / 11 / 11 | 5–15 (conforme fase) | 6–9 | 60 s – 3 min |
| Costas (dorsais/meio) | Remada curvada, Puxada aberta, Puxada supinada, Remada sentada | 12 / 14 / 12 | 6–12 | 6–9 | 90 s – 2 min |
| Deltoides (ant./lat.) | Desenvolvimento c/ halteres, Elevação lateral | 5 / 6 / 6 (+ indireto dos supinos) | 8–15 | 6–9 | 60–120 s |
| Deltoide posterior | Face pull (+ remadas indiretas) | 2 / 3 / 3 | 10–15 | 7–9 | 60–90 s |
| Bíceps | Rosca direta EZ, Rosca martelo | 4 / 6 / 6 (+ indireto das puxadas) | 10–15 | 7–9 | bi-set |
| Tríceps | Tríceps corda, Tríceps francês | 4 / 6 / 6 (+ indireto dos supinos) | 10–15 | 7–9 | bi-set |
| Quadríceps | Agachamento, Leg press, Cadeira extensora, Búlgaro | 11 / 15 / 13 | 5–15 | 6–9 | 60 s – 3 min |
| Posteriores de coxa | Terra romeno, Mesa flexora, Cadeira flexora sentada | 7 / 10 / 10 | 5–15 | 6–9 | 60 s – 3 min |
| Glúteos | Elevação pélvica, Búlgaro (+ agachamento/terra romeno) | 6 / 7 / 6 diretas + muito indireto | 6–12 | 6–9 | 90–120 s |
| Panturrilhas | Panturrilha em pé, Panturrilha sentada | 4 / 6 / 6 | 10–15 | 7–9 | 60–90 s |
| Core | Prancha frontal, Pallof press | 4 / 6 / 6 | tempo/reps | — | 45–60 s |

Todos os grupos ficam dentro da faixa recomendada para iniciantes (6–16 séries/semana). O pico de quadríceps (15 na S6–7) é aceitável porque parte do búlgaro também estimula os glúteos.

### Referência de intensidade

- O iniciante **não testa 1RM**. A intensidade é controlada por **RPE / repetições em reserva (RIR)**: RPE 7 = 3 reps sobrando; RPE 8 = 2; RPE 9 = 1.
- Os %1RM da tabela de fases são **estimados**: 1RM estimado (e1RM) pela fórmula de Epley `1RM = carga × (1 + reps/30)`, calculado sobre a melhor série dos exercícios **P** ao fim das semanas 3, 7 e 11.
- **Teto de esforço**: nos compostos livres (agachamento, supino reto, terra romeno, remada curvada) o RPE máximo é **9**, sem falha. A falha (RPE 10) só é permitida na **última série de acessórios em máquina/polia** durante a Intensificação.

## Estratégia de Sobrecarga Progressiva

### Regra principal: dupla progressão (dentro da faixa de reps da fase)

1. Escolha uma carga que permita fazer o **limite inferior** da faixa no RPE alvo.
2. A cada sessão, tente somar reps com a mesma carga.
3. Quando **todas as séries** atingirem o **limite superior** da faixa sem passar do RPE alvo → aumente a carga na sessão seguinte e volte ao limite inferior.

| Tipo de exercício | Incremento de carga |
|---|---|
| Compostos de membros inferiores com barra (agachamento, terra romeno, elevação pélvica) | +2,5 a 5 kg |
| Compostos de membros superiores com barra (supino reto, remada curvada) | +2 a 2,5 kg |
| Halteres | próximo par (+1 a 2 kg por halter) |
| Máquinas e polias | próxima placa / menor incremento disponível |

- **Ritmo esperado (iniciante)**: aumento de carga a cada 1–2 semanas nos compostos e a cada 2–3 semanas nos isoladores. Teto de **+5%/semana** de carga por exercício. Volume semanal: no máximo +10% fora das viradas de fase.
- **Ordem de prioridade das variáveis** (`periodization-engine`): 1) séries (já programadas por fase) → 2) reps → 3) carga → 4) cadência (excêntrica de 3 s) → 5) menor descanso. Iniciantes usam quase só 2) e 3).
- **Autorregulação por RPE**:
  - RPE real ≥ 1 ponto **acima** do alvo → repetir a carga na próxima sessão; se acontecer 2× seguidas, reduzir 5%.
  - RPE real ≥ 1 ponto **abaixo** do alvo com reps no topo → subir carga já na próxima sessão (pode usar o incremento maior).
- **Viradas de fase**: a carga inicial da nova fase sai do e1RM da última semana da fase anterior:
  - Acumulação (S4): ~70% do e1RM para 8–10 reps
  - Intensificação (S8): ~78–80% do e1RM para 5–7 reps
  - Deload (S12): ~60% do e1RM
  - Para S e A, que não usam e1RM: reduzir 5–10% da carga ao subir a faixa de reps e aumentar 5–10% ao descer.

### Manejo de platô

- **2 sessões seguidas** sem progresso (nem reps nem carga) num exercício → checar sono (≥7 h), alimentação (proteína/calorias), técnica e descanso entre séries.
- **3 sessões seguidas** → reduzir a carga 10% e reconstruir com dupla progressão. Se não resolver, trocar pela variação equivalente sugerida pelo exercise-guide no mesociclo seguinte.
- **Estagnação em vários exercícios por 2+ semanas** com sinais de fadiga → antecipar o deload (ver abaixo).

### Critérios de deload

- **Planejado**: semana 12 (iniciantes: a cada 8–12 semanas). Tipo: **deload de volume** (−50% das séries, cargas ~60% e1RM, RPE 5–6).
- **Reativo (antecipado)**: aplicar uma semana com os parâmetros da S12 se houver **≥2** destes sinais por mais de 1 semana:
  - queda de desempenho em ≥3 exercícios
  - fadiga crônica ou sono ruim
  - dor articular persistente (não confundir com dor muscular tardia)
  - perda de motivação ou vontade de faltar
  - frequência cardíaca de repouso elevada (+5 bpm sobre a média)
  Depois do deload reativo, retomar a fase no ponto onde parou.
- **Após a S12**: novo ciclo de 12 semanas reiniciando a Acumulação com cargas re-estimadas (o e1RM deve estar maior). Avaliar a mudança para modelo intermediário (ondulatório) depois de 2 ciclos.

## Precauções

Não há lesões informadas, então nenhum exercício foi excluído. Valem as precauções gerais para iniciantes:

1. **Triagem**: responder ao PAR-Q antes de começar. Qualquer sintoma (dor no peito, tontura, falta de ar desproporcional, hipertensão não controlada) → **avaliação médica antes de treinar**.
2. **Técnica antes da carga**: nas semanas 1–3 a carga só sobe se a execução estiver estável. Filmar as séries de agachamento, terra romeno, supino e remada curvada ajuda a corrigir.
3. **Coluna lombar neutra** no terra romeno, na remada curvada e no agachamento. Se a lombar arredondar, a série termina ali.
4. **Ombros no supino**: escápulas retraídas e deprimidas, cotovelos a ~45–70° do tronco, barra descendo na linha do esterno inferior.
5. **Segurança**: no agachamento livre e no supino reto, usar barras de segurança no rack e/ou ajudante (spotter), principalmente nas S8–11.
6. **Falha**: proibida nos compostos livres. Permitida apenas na última série de isoladores em máquina na Intensificação.
7. **Regra da dor**: dor aguda, em pontada ou articular → interromper o exercício e usar a substituição do exercise-guide. Dor que dura mais de 1 semana → procurar profissional de saúde (ortopedista/fisioterapeuta).
8. **Aquecimento obrigatório**: 5 min de cardio leve + mobilidade específica + 2–3 séries de aproximação no exercício P (ex.: 50% × 8, 70% × 5, 85% × 2–3 da carga de trabalho).
9. **Recuperação**: 7–9 h de sono. Os dias de descanso podem ter cardio leve (Z2, 20–30 min, até 2×/semana), mas nunca HIIT intenso antes de uma sessão de membros inferiores.

## Notas para o Exercise Guide

- O programa tem **26 exercícios** (lista completa e categorias em `handoff_architect.md`). É preciso guia de execução e substituição para todos.
- Prioridade de detalhe técnico (padrões de maior risco e técnica mais exigente): Agachamento livre com barra, Levantamento terra romeno, Remada curvada com barra, Supino reto com barra, Agachamento búlgaro.
- Bi-sets: Rosca direta EZ + Tríceps corda (Sup A) e Rosca martelo + Tríceps francês (Sup B).

## Notas para o Nutrition Coordinator

- Objetivo: hipertrofia com **superávit calórico moderado** (ganho de massa com pouca gordura).
- Dias de treino: Seg, Ter, Qui, Sex. Os dias de membros inferiores (Ter/Sex) têm maior gasto energético.
- Maior demanda de volume: **S4–7, pico nas S6–7**. Maior demanda neural e de carga: **S8–11**. Na **S12 (deload)** manter calorias e proteína, sem cortar.

## Notas para o Template Builder

- Registrar por série: carga, reps, RPE. Por sessão: duração, séries totais, sensação geral. Por semana: peso corporal médio, e1RM dos 4 exercícios P, aderência.
- Pontos de avaliação: fim das S3, S7, S11 e S12 (re-teste). Detalhes em `handoff_architect.md`.
