# 04 — Tabela de Integração Nutricional

> Autor: **nutrition-linker** · Base: `00_input.md`, `01_program_design.md`, `02_weekly_schedule.md`, `handoff_architect.md` (seção "Para nutrition-linker").
> Referências: posicionamentos da ISSN (International Society of Sports Nutrition) sobre proteína e exercício (2017), timing de nutrientes (2017), creatina (2017), cafeína (2021) e dietas/composição corporal (2017); ACSM/AND/DC — *Nutrition and Athletic Performance* (2016); valores de alimentos aproximados pela Tabela TACO/rótulos.

> ⚠️ **Aviso**: este plano é **educacional e genérico**, montado a partir de um perfil de referência (homem, 28 anos, 178 cm, 75 kg, iniciante, sem doenças informadas). **Não substitui** consulta individual com nutricionista (CRN) ou médico. Pessoas com doença renal, hepática, cardiovascular, diabetes, hipertensão, transtornos alimentares, uso de medicamentos ou alergias devem procurar avaliação profissional antes de seguir qualquer parte dele, principalmente a de suplementos.

---

## 1. Perfil e objetivo nutricional

| Item | Valor |
|---|---|
| Perfil | Homem, 28 anos, 178 cm, 75 kg (IMC ≈ 23,7), iniciante |
| Objetivo | Hipertrofia com **superávit moderado** ("lean bulk": ganhar músculo com pouca gordura) |
| Treino | Superior/Inferior 4×/semana, ~60 min — **Seg (Sup A), Ter (Inf A), Qui (Sup B), Sex (Inf B)** |
| Descanso | Qua, Sáb, Dom (cardio Z2 opcional de 20–30 min, até 2×/semana) |
| Ritmo de ganho alvo | **+0,25 a +0,5% do peso/semana ≈ +0,2 a +0,4 kg/semana** (≈ 1–1,5 kg/mês). Iniciantes toleram a ponta de cima dessa faixa |

---

## 2. Cálculo de gasto energético

### 2.1 Taxa metabólica basal (TMB) — Mifflin-St Jeor (homens)

```
TMB = (10 × peso kg) + (6,25 × altura cm) − (5 × idade) + 5
TMB = (10 × 75) + (6,25 × 178) − (5 × 28) + 5
TMB = 750 + 1.112,5 − 140 + 5
TMB ≈ 1.728 kcal/dia
```

Conferência com Harris-Benedict revisada: 88,4 + (13,4 × 75) + (4,8 × 178) − (5,68 × 28) ≈ **1.788 kcal**. As duas fórmulas ficam próximas. Usamos Mifflin-St Jeor por ser a mais precisa em adultos não obesos.

### 2.2 Gasto energético total (GET/TDEE)

| Fator de atividade | Situação | GET |
|---|---|---|
| 1,375 (leve) | Semana de deload / trabalho sentado sem nenhuma outra atividade | 1.728 × 1,375 ≈ 2.376 kcal |
| **1,55 (moderado)** | **4 sessões de musculação de 60 min + rotina normal** | **1.728 × 1,55 ≈ 2.680 kcal** |
| 1,725 (alto) | Trabalho físico em pé + treino | 1.728 × 1,725 ≈ 2.980 kcal |

**GET médio estimado: ≈ 2.680 kcal/dia.** Toda fórmula tem erro de ±10% (±250 kcal). O número real vem da balança (seção 10), não da fórmula.

### 2.3 Meta calórica (GET + 300)

- **Média semanal alvo: ≈ 2.980 kcal/dia** (2.680 + 300).
- Distribuição (*carb cycling* leve): mais energia e carboidrato nos 4 dias de treino, menos nos 3 de descanso, com a **mesma média semanal**:

```
(4 dias × 3.100) + (3 dias × 2.820) = 12.400 + 8.460 = 20.860 kcal/semana
20.860 ÷ 7 ≈ 2.980 kcal/dia  →  GET (2.680) + 300 ✔
```

---

## 3. Metas nutricionais (Fase 1 — Adaptação, S1–3)

| Item | Dia de treino (Seg/Ter/Qui/Sex) | Dia de descanso (Qua/Sáb/Dom) | Base |
|---|---|---|---|
| **Calorias** | **3.100 kcal** | **2.820 kcal** | GET 2.680 + ~300 na média semanal |
| **Proteína** | **160 g (2,1 g/kg)** — 640 kcal | **160 g (2,1 g/kg)** — 640 kcal | ISSN: 1,6–2,2 g/kg para hipertrofia. Igual todos os dias: a síntese proteica continua elevada 24–48 h após o treino |
| **Carboidratos** | **445 g (5,9 g/kg)** — ~1.780 kcal | **355 g (4,7 g/kg)** — ~1.420 kcal | ISSN/ACSM: 4–7 g/kg para treino de força com volume moderado-alto. Mais nos dias de treino para glicogênio e desempenho |
| **Gordura** | **75 g (1,0 g/kg)** — 675 kcal (~22%) | **85 g (1,1 g/kg)** — 765 kcal (~27%) | ≥ 0,8–1,0 g/kg (20–30% das kcal) para saúde hormonal. Sobe no descanso para compensar o carboidrato |
| Fibras | 30–40 g | 30–40 g | Saúde intestinal. Evitar excesso na refeição pré-treino |
| Água | ~3,0–3,5 L | ~2,6–3,0 L | Seção 8 |

**Distribuição da proteína**: 4–6 refeições com **~0,3–0,5 g/kg (25–40 g) cada**, a cada 3–4 h. Fontes de alto valor biológico: ovos, frango, carne bovina magra, peixe, leite, iogurte, queijo, whey. Feijão + arroz completam a proteína vegetal do dia.

**Dias de membros inferiores (Ter/Sex)**: gastam mais (agachamento, terra romeno, leg press, búlgaro). Opcional: transferir **~25 g de carboidrato** (ex.: ½ concha de arroz ou 1 banana) dos dias de superior (Seg/Qui) para Ter/Sex. A média semanal não muda.

---

## 4. Timing de nutrientes nos dias de treino

> Horário de referência: **treino às 18:30–19:30** (após o trabalho). Para treino de manhã, ver 4.5.

### 4.1 Pré-treino (1,5–2 h antes ≈ 17:00)
- **Objetivo**: chegar com glicogênio cheio e aminoácidos disponíveis. O almoço (12:30) foi há ~6 h, então esta refeição é **obrigatória**.
- **Quantidade**: **carboidratos 1–1,5 g/kg (75–110 g)** + **proteína 0,25–0,3 g/kg (~20–25 g)**, pouca gordura e pouca fibra (digestão rápida).
- **Macros do exemplo**: Carb ~76 g · Prot ~20 g · Gord ~2 g · ~400 kcal.
- **Exemplo**: tapioca (60 g de goma) com 60 g de frango desfiado + 1 banana-prata.
- **Alternativas**: 2 pães franceses com 2 fatias de peito de peru + 1 copo de suco de laranja · cuscuz nordestino (100 g de flocão) com 1 ovo + 1 banana · vitamina de banana com aveia e leite.
- Se faltarem só 30–45 min: apenas 1 banana ou 2 col. (sopa) de mel/geleia (~30 g de carboidrato) + água.

### 4.2 Intra-treino (durante a sessão)
- **Objetivo**: hidratação. Sessões de ~60 min de musculação **não precisam de carboidrato intra-treino** quando a refeição pré-treino foi feita.
- **Recomendação**: **água, 150–250 ml a cada 15–20 min** (~500–750 ml na sessão).
- **Exceção — Intensificação (S8–11)**: os descansos de 2,5–3 min nos exercícios P podem levar a sessão a **70–80 min**. Se passar de 75 min, ou se a pré-treino tiver sido pequena, usar uma bebida com **~30 g de carboidrato** (ex.: 500 ml de água + 2 col. (sopa) de suco concentrado/mel + 1 pitada de sal, ou isotônico comercial).
- Academia quente (verão, sem ar-condicionado) e suor intenso: incluir sódio (~300–600 mg/L) na garrafa (isotônico ou água com 1 pitada de sal + suco).

### 4.3 Pós-treino (até 1–2 h depois ≈ 20:00)
- **Objetivo**: estimular a síntese de proteína muscular e repor o glicogênio para o treino do **dia seguinte**. Segunda → terça e quinta → sexta são dias seguidos de treino, então o jantar pós-treino de **Seg e Qui** é o que abastece as sessões de pernas (agachamento na Ter, terra romeno na Sex).
- **Quantidade**: **proteína 0,4–0,5 g/kg (30–40 g)** + **carboidratos 1–1,2 g/kg (75–90 g)**.
- **Macros do exemplo**: Carb ~86 g · Prot ~46 g · Gord ~17 g · ~700 kcal.
- **Exemplo**: prato brasileiro clássico (arroz + feijão + patinho moído + legumes refogados).
- A "janela anabólica de 30 min" é pouco relevante quando houve pré-treino (ISSN 2017). Basta comer em até ~2 h. Se o jantar for demorar mais, tomar **1 dose de whey (25–30 g) com 1 fruta** logo após o treino.

### 4.4 Antes de dormir (ceia)
- **20–40 g de proteína de digestão lenta** (caseína do leite, iogurte, queijo cottage), que ajuda a recuperação noturna. No cardápio: leite com aveia e pasta de amendoim.

### 4.5 Se o treino for de manhã (ex.: 7:00)
- Ao acordar (6:00): lanche leve com 40–60 g de carboidrato + 15–20 g de proteína (ex.: 1 pão francês com ovo + 1 banana, ou iogurte com aveia e mel).
- Pós-treino = café da manhã completo (o "Café" + "Lanche" do cardápio juntos).
- O restante do dia segue o mesmo total de macros.

### 4.6 Ênfase por sessão

| Dia | Sessão | Exercícios mais exigentes | Ênfase nutricional |
|---|---|---|---|
| **Seg** | Superior A | Supino reto, Remada curvada | Pré-treino padrão. **Jantar pós-treino caprichado no carboidrato** (prepara o agachamento da Ter) |
| **Ter** | Inferior A | **Agachamento livre, Leg press** | Maior gasto da semana. Pré-treino com carboidrato no limite superior (~100 g). Café/cafeína opcional |
| **Qua** | Descanso | — | Dieta de descanso. Se fizer cardio Z2, ver 4.7 |
| **Qui** | Superior B | Supino inclinado c/ halteres, Puxada supinada | Pré-treino padrão. **Jantar pós-treino caprichado no carboidrato** (prepara o terra romeno da Sex) |
| **Sex** | Inferior B | **Terra romeno, Búlgaro, Elevação pélvica** | 2º dia seguido de treino: pré-treino com carboidrato no limite superior. Hidratação reforçada |
| **Sáb/Dom** | Descanso | — | Dieta de descanso. Domingo: manter a proteína e o carboidrato perto do alvo (segunda é treino) |

### 4.7 Cardio Z2 opcional (dias de descanso)
- 20–30 min de caminhada/bike leve gastam **~120–180 kcal**. Nesse dia, somar **1 fruta + 2 col. (sopa) de aveia (~150 kcal)** para não diminuir o superávit.

---

## 5. Cardápio exemplo (comida brasileira)

Valores aproximados (TACO/rótulos, ±10%). Pesos de arroz, feijão e carnes são **cozidos/prontos**. Trocas equivalentes na seção 5.3.

### 5.1 Comparativo por refeição

| Refeição | Dia de treino (treino 18:30) | kcal | Dia de descanso | kcal |
|---|---|---|---|---|
| **Café da manhã** (07:00) | 2 pães franceses (100 g) + 2 ovos mexidos na manteiga (5 g) + café com 150 ml de leite semidesnatado + 1 banana-prata | ~635 (C 92 · P 28 · G 20) | 1 pão francês + 3 ovos mexidos na manteiga (5 g) + café com 150 ml de leite semidesnatado + 200 g de mamão | ~540 (C 57 · P 30 · G 24) |
| **Lanche da manhã** (10:00) | Iogurte natural integral (170 g) + 30 g de aveia + 1 col. (sopa) de mel + 150 g de mamão | ~325 (C 52 · P 11 · G 7) | Iogurte natural integral (170 g) + 1 banana + 1 col. (sopa) de mel | ~250 (C 46 · P 7 · G 5) |
| **Almoço** (12:30) | 200 g de arroz branco + 1 concha cheia de feijão carioca (150 g) + 100 g de peito de frango grelhado + salada de folhas e tomate com 1 col. (sopa) de azeite + 1 laranja | ~695 (C 93 · P 46 · G 14) | 200 g de arroz + 150 g de feijão + **120 g** de frango grelhado + salada com 1 col. (sopa) de azeite + 1 laranja | ~725 (C 93 · P 52 · G 14) |
| **Lanche da tarde / Pré-treino** (17:00) | **Pré-treino**: tapioca (60 g de goma) com 60 g de frango desfiado + 1 banana-prata | ~400 (C 76 · P 20 · G 2) | 2 fatias de pão integral + 40 g de queijo minas frescal + 1 maçã | ~290 (C 38 · P 12 · G 10) |
| **Treino** (18:30–19:30) | Água (500–750 ml). Opcional: café/cafeína às 17:45 (seção 7) | — | — | — |
| **Jantar** (20:00) | **Pós-treino**: 200 g de arroz + 150 g de feijão + 90 g de patinho moído refogado + 150 g de legumes (abobrinha, cenoura, chuchu) com 2 col. (chá) de azeite | ~700 (C 86 · P 46 · G 17) | 200 g de arroz + 150 g de feijão + 100 g de patinho + 150 g de legumes com 2 col. (chá) de azeite | ~725 (C 86 · P 50 · G 18) |
| **Ceia** (22:30) | 200 ml de leite semidesnatado + 30 g de aveia + 100 g de manga + 20 g de pasta de amendoim (pode virar vitamina) | ~380 (C 48 · P 15 · G 15) | 200 ml de leite semidesnatado + 30 g de aveia + 15 g de pasta de amendoim | ~285 (C 30 · P 14 · G 13) |
| **Total do dia** | | **≈ 3.135 kcal · C 447 g · P 166 g · G 75 g** | | **≈ 2.820 kcal · C 350 g · P 165 g · G 84 g** |
| **Meta** | | 3.100 · C 445 · P 160 · G 75 | | 2.820 · C 355 · P 160 · G 85 |

> A proteína do cardápio fica em ~165 g (2,2 g/kg) porque arroz, feijão, pão, aveia e leite somam ~60 g de proteína "escondida". Isso está dentro da faixa da ISSN. Se preferir ficar em 150–160 g, basta tirar o frango do pré-treino e pôr mais 1 col. (sopa) de mel.

### 5.2 Como os dias se diferenciam
- **Treino**: mais carboidrato no café, no pré-treino e no jantar pós-treino (2 bananas, tapioca, mel, aveia). Gordura menor perto do treino para facilitar a digestão.
- **Descanso**: ~90 g a menos de carboidrato (menos pão, sem tapioca), um pouco mais de gordura (ovo extra, queijo) e a **mesma proteína**.

### 5.3 Trocas equivalentes (≈ mesma quantidade de macros)

| Grupo | Porção de referência | Pode trocar por |
|---|---|---|
| Carboidrato (~45 g C) | 200 g de arroz branco cozido | 250 g de batata-inglesa · 200 g de macarrão cozido · 180 g de mandioca/aipim cozido · 220 g de batata-doce · 100 g de cuscuz de milho (flocão, peso seco ~70 g) · 1,5 pão francês |
| Proteína (~30 g P) | 100 g de peito de frango grelhado | 90 g de patinho/alcatra/músculo magro · 130 g de tilápia · 4 ovos inteiros (gordura mais alta) · 1 lata de atum em água + 1 ovo · 1 dose de whey + 200 ml de leite |
| Leguminosa | 150 g de feijão carioca | Feijão preto · lentilha · grão-de-bico (mesma porção) |
| Gordura (~10 g G) | 1 col. (sopa) de azeite | 15 g de pasta de amendoim · 3 castanhas-do-pará · ⅓ de abacate pequeno |
| Fruta (~25 g C) | 1 banana-prata | 1 manga pequena · 2 laranjas · 1 xícara de uvas · 1 pera |

Vegetarianos ou pessoas com restrição: avisar o orquestrador. A meta de proteína é possível com ovos, laticínios, leguminosas, tofu e proteína vegetal em pó, mas o cardápio precisa ser refeito.

---

## 6. Ajustes por fase da periodização

| Fase | Semanas | Volume / intensidade (architect) | Dia de treino | Dia de descanso | Média semanal | Observações |
|---|---|---|---|---|---|---|
| **1. Adaptação** | 1–3 | 52 → 64 séries · RPE 6–7 | 3.100 kcal · C 445 · P 160 · G 75 | 2.820 kcal · C 355 · P 160 · G 85 | ≈ 2.980 (GET+300) | Instalar os hábitos: pesar a comida por 2–3 semanas, bater a proteína todos os dias e fazer o pré-treino. Iniciar a creatina. **Aumento de 0,5–1,5 kg nas S1–2 é esperado** (glicogênio + água + creatina) e não é gordura |
| **2. Acumulação** | 4–7 | 82 → 86 séries (pico S6–7) · RPE 7–9 | **3.200 kcal** · **C 470** · P 160 · G 75 (+25 g de carboidrato no pré-treino e no pós-treino) | 2.820 kcal (igual) | ≈ 3.040 | **Maior demanda de volume e recuperação.** Os +100 kcal vão para carboidrato em volta do treino (ex.: +½ concha de arroz no jantar + 1 col. (sopa) de mel no pré-treino). Nas S6–7 (pico) priorizar sono de 7–9 h e não pular a ceia |
| **3. Intensificação** | 8–11 | 82 séries, 5–7 reps nos P · 77–85% · RPE 8–9 | 3.200 kcal · C 470 · P 160 · G 75 (manter a Acumulação) | 2.820 kcal | ≈ 3.040 | **Carboidrato pré-treino é prioridade** (cargas mais altas). Sessões de 70–80 min: usar a regra intra-treino (4.2). Cafeína pode ajudar nas sessões P mais pesadas (S10–11). Ter/Sex: pré-treino com ~100–110 g de carboidrato |
| **4. Deload** | 12 | 40 séries (−50%) · ~60% · RPE 5–6 | **3.100 kcal** · C 445 · P 160 · G 75 (volta à Fase 1) | 2.820 kcal | ≈ 2.980 | **Não cortar calorias nem proteína** (indicação do architect): é a semana em que a recuperação acontece. Só retira o extra da Acumulação. Pausar a cafeína (ajuda a resensibilizar). Re-teste opcional no fim da S12: manter o pré-treino completo nesse dia |

**Recalcular a base**: nas S7 e S12, refazer a conta do GET com o peso novo (ex.: a 77 kg, TMB ≈ 1.748 e GET ≈ 2.710 kcal). Na prática, os ajustes da balança (seção 10) já corrigem isso semana a semana.

**Deload reativo** (antecipado pelo architect): aplicar as calorias da linha "Deload" e voltar às da fase em andamento quando o treino for retomado.

---

## 7. Suplementos (somente os com evidência forte)

> **Comida primeiro.** O cardápio da seção 5 já atinge todas as metas **sem nenhum suplemento**. Os três abaixo são opcionais, têm grau de evidência **A** (ISSN) e são seguros para adultos saudáveis nas doses indicadas.

| Suplemento | Grau | Dose (75 kg) | Timing | Efeito | Observações |
|---|---|---|---|---|---|
| **Creatina monohidratada** | **A** | **3–5 g/dia, todos os dias** (inclusive descanso e deload). Saturação opcional: 0,3 g/kg/dia ≈ **20–25 g/dia em 4 doses de 5 g por 5–7 dias**, depois 3–5 g/dia | Qualquer hora. Mais conveniente no pós-treino ou numa refeição. A constância importa mais que o horário | +força, +volume de treino, +massa magra (~1–2 kg a mais que o treino sozinho em 8–12 semanas) | Sem saturação, os estoques enchem em ~3–4 semanas. Aumenta ~0,5–1,5 kg de água **intramuscular** (não é "inchaço"). Segura para pessoas saudáveis (ISSN 2017). Quem tem doença renal: só com aval médico. Preferir creatina monohidratada pura com selo de qualidade (ex.: *Creapure*) |
| **Whey protein** (concentrado ou isolado) | **A** (como fonte de proteína) | **25–40 g/dose** (≈ 20–30 g de proteína). Na prática, 1 dose/dia | Pós-treino quando o jantar demorar mais de 2 h, ou para completar a meta num dia corrido | Leucina alta (~2,5–3 g/dose), digestão rápida, estímulo forte à síntese proteica | **É comida, não "suplemento mágico"**: dispensável se a meta de proteína for atingida com alimentos. Intolerância à lactose: whey isolado ou proteína vegetal (ervilha+arroz). Conta na meta diária de proteína |
| **Cafeína** | **A** | **3–6 mg/kg = 225–450 mg**. Começar por **~3 mg/kg (~200–225 mg)**. Teto diário (adultos saudáveis): 400 mg somando café, chá, refrigerante e pré-treino | **30–60 min antes do treino** (17:45 para treino às 18:30) | +força/potência, +reps até a falha, −percepção de esforço | **Sono primeiro**: treino à noite + cafeína atrapalha o sono e a recuperação. Parar **≥ 6–8 h antes de dormir**. Se dormir pior, usar só nas sessões mais pesadas (Ter/Sex na Intensificação) ou não usar. Café coado forte (~200 ml ≈ 80–120 mg) é uma alternativa barata. Evitar se houver hipertensão, arritmia ou ansiedade. Pausar no deload |

### Não recomendados para este perfil (gastos sem retorno)
- **BCAA / glutamina**: redundantes com a ingestão adequada de proteína (2 g/kg).
- **"Pré-treinos" com blend proprietário**: dose de cafeína muitas vezes não declarada direito e mistura de ingredientes sem evidência. Melhor usar cafeína isolada ou café.
- **"Termogênicos", "boosters de testosterona", "pró-hormônios"**: sem benefício comprovado e com **risco real de contaminação por substâncias proibidas ou hormônios**.
- Outros (vitamina D, ômega-3, ferro etc.): só com **exame e indicação profissional**.

### Precauções de segurança e doping
- Creatina, whey e cafeína **não são proibidos pela WADA/ABCD**. A cafeína está no programa de monitoramento, sem restrição.
- Suplementos podem estar **contaminados** (estimulantes, anabolizantes). Se a pessoa competir, ou por segurança em geral, escolher produtos **regularizados na ANVISA** e, se possível, com certificação de terceiros (*Informed Sport*, *NSF Certified for Sport*). Desconfiar de promessas exageradas.
- Este plano **não aborda** e não recomenda nenhum recurso farmacológico (esteroides anabolizantes, SARMs etc.): isso está fora do escopo do pipeline.

---

## 8. Plano de hidratação

Base: **~35–40 ml/kg/dia ≈ 2,6–3,0 L** + reposição do treino. Total estimado: **~3,0–3,5 L nos dias de treino** e **~2,6–3,0 L no descanso** (conta a água dos alimentos, de sucos, do leite e do café).

| Momento | Quantidade | Observações |
|---|---|---|
| Ao acordar | 300–500 ml | Antes ou junto com o café da manhã |
| Ao longo do dia | ~250 ml a cada 1–2 h | Garrafa de 1 L no trabalho: meta de 2 garrafas até as 17:00 |
| Pré-treino (2–4 h antes) | **5–7 ml/kg ≈ 375–525 ml** | Junto com a refeição pré-treino (17:00) |
| Durante o treino | **150–250 ml a cada 15–20 min** (≈ 500–750 ml/sessão) | Água. Calor ou sessão > 75 min: isotônico ou água com sódio (seção 4.2) |
| Pós-treino | **1,25–1,5 L para cada 1 kg perdido** no treino | Para estimar: pesar-se sem roupa antes e depois de 1–2 treinos. Perda > 2% do peso (> 1,5 kg) = hidratação insuficiente |
| Com a creatina | Sem necessidade de "litros extras" | Só manter a meta diária. A creatina não desidrata (ISSN) |

**Checagem rápida**: urina amarelo-clara = OK · amarelo-escuro = beber mais · sede durante o treino = já está atrasado.
**Eletrólitos**: com uma alimentação normal (arroz, feijão, sal de cozinha, frutas) não há necessidade de suplementar. Só considerar no verão, em academia sem climatização ou com suor muito intenso (manchas de sal na roupa).

---

## 9. Hábitos que sustentam o plano
- **Sono de 7–9 h**: dormir mal reduz a síntese proteica e piora o desempenho, e nenhuma dieta compensa isso.
- **Álcool**: limitar (≤ 1–2 doses, no máximo 1×/semana). Ele prejudica a síntese proteica e o sono e acrescenta calorias vazias, principalmente nas noites pós-treino.
- **Preparo**: cozinhar arroz, feijão e proteínas 2×/semana (domingo e quarta) facilita a aderência.
- **Regra 80/20**: se ~80% das refeições seguirem o plano, sobra espaço para refeições sociais sem culpa, desde que a proteína do dia seja mantida.

---

## 10. Ajuste semanal pela balança

**Como pesar**: ao acordar, depois de urinar, em jejum e sem roupa, na mesma balança. **Pelo menos 3×/semana** (ideal: todos os dias). Usar a **média semanal** e comparar com a média da semana anterior. Pesagens isoladas oscilam ±1 kg por sal, carboidrato e intestino.

| Variação da média semanal (avaliar a tendência de **2 semanas**) | Interpretação | Ação |
|---|---|---|
| **S1–2: +0,5 a +1,5 kg** | Glicogênio + água + creatina | **Nenhuma.** Não conta para a regra. A referência passa a ser a média da S2 |
| **< +0,1 kg/sem** (ou perda) | Superávit insuficiente | **+150 kcal/dia** (≈ +35–40 g de carboidrato: ex. +1 banana + 1 col. de mel, ou +100 g de arroz), primeiro nos dias de treino |
| **+0,2 a +0,4 kg/sem** | ✅ Na meta | Manter |
| **+0,4 a +0,5 kg/sem** | Limite superior | Manter, mas vigiar a cintura |
| **> +0,5 kg/sem** por 2 semanas | Ganho de gordura excessivo | **−150 kcal/dia** (tirar carboidrato/gordura dos dias de descanso primeiro). **Nunca reduzir a proteína** |
| Cintura **> +1 cm/mês** com força estagnada | Ganho de gordura acima do de músculo | −150 kcal e conferir aderência/porções |
| Peso subindo bem, mas desempenho caindo + sinais de fadiga | Recuperação, não calorias | Conferir sono e pré-treino. Ver os critérios de deload reativo do architect |

**Regras gerais**:
- No máximo **1 ajuste a cada 2 semanas**, sempre de **±100–150 kcal**.
- Ajustar via **carboidrato** (preferência) ou gordura. A proteína fica fixa em ~2 g/kg.
- Avaliação completa (peso médio, cintura, fotos e e1RM do architect) **nas S3, S7, S11 e S12**. Se a força nos exercícios P sobe e a cintura fica estável, o superávit está correto.
- Ganho esperado em 12 semanas: **~+2,5 a +4,5 kg** (sendo ~1 kg de água/glicogênio/creatina no início).

---

## 11. Notas para o Template Builder

Ver `handoff_linker.md` → seção "Para template-builder" (itens a rastrear, frequência e regras de alerta).

---

> ⚠️ **Lembrete**: valores calculados para um perfil de referência e baseados em estimativas populacionais. A resposta individual varia. Para um plano personalizado (exames, preferências, condições clínicas), procure um **nutricionista (CRN)**. Diante de qualquer sintoma ou condição de saúde, consulte um **médico**.
