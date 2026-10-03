# 00 — Entrada (Orquestrador / Fase 1)

> Execução: orquestrador `fitness-program` (harness-100 / 74-fitness-program) · Data: 03/10/2026
> Execução anterior (cenário genérico de teste) arquivada em `_arquivo_cenario_referencia/`.

## Perfil

| Campo | Valor |
|---|---|
| Nome | Matheus Martins de Oliveira |
| Sexo / idade | Masculino, 26 anos (nasc. 25/09/1999) |
| Altura / peso | 173 cm / 80,2 kg (08/05/2026) |
| Cidade | São Paulo |
| Rotina | Trabalho de escritório, sedentário; pausas a cada 40 min sentado |

## Objetivo

Recomposição corporal: reduzir gordura corporal (foco em gordura visceral e %GC) mantendo/ganhando massa magra.

## Nível

Iniciante. Musculação com personal desde nov/2025; rotina atual PPL "iniciante".

## Recursos

- Academia com máquinas articuladas, **3x/semana** (PPL)
- Cardio: **natação** (substitui o vôlei de areia)
- Equipe: personal trainer + nutricionista Mariana Muñoz (CRN3 34962, Novamed Santo Amaro)

## Lesão / restrições: condropatia femoropatelar bilateral

| # | Regra |
|---|---|
| R1 | **PROIBIDO**: cadeira extensora (qualquer variação) |
| R2 | Agachamento: amplitude máxima 90°; **nunca isométrico em ângulo fechado** |
| R3 | Sem avanço/afundo/lunge (inclusive afundo no Smith) |
| R4 | Leg press (se usado): pés altos na plataforma, sem passar de 90° |
| R5 | Flexoras (cadeira/mesa/vertical): rolo na tíbia distal/tornozelo, **nunca na patela** |
| R6 | Cuidado em prancha/abdominais com carga sobre joelhos fletidos |
| R7 | Alternativas aprovadas: elevação pélvica (máquina/barra), agachamento búlgaro (pés fixos), abdutora/adutora, panturrilha |
| R8 | Sempre: parar se houver dor; encaminhar a ortopedista/fisioterapeuta |

## Composição corporal (bioimpedância)

| | 27/03/2026 | 08/05/2026 |
|---|---|---|
| Peso (kg) | 81,6 (fev: 84) | 80,2 |
| IMC | 27,26 | 26,8 |
| Cintura (cm) | 96 | 94 |
| % gordura | 26 | 25,8 |
| % músculo esquelético | 35,4 | 35,4 |
| Gordura visceral | 9 (fev: 10) | 9 |
| Metabolismo basal (kcal) | 1800 | 1779 |
| Idade biológica | 45 | 43 |

Diagnóstico: sobrepeso; circunferência abdominal com risco cardiovascular aumentado; %gordura "muito ruim" (Pollock e Willmore).

## Programa existente

PPL iniciante do personal, 3x/semana, válido até **14/11/2026**. Ver `01_program_design.md`.

## Nutrição existente

Plano de Mariana Muñoz (08/05/2026), sem meta calórica/macros explícita. Ver `04_nutrition_plan.md` (o linker integra ao treino, sem substituir o plano).

## Modo de execução

**Full Pipeline**, com programa existente → copiado para `01_program_design.md` e **architect pulado** (regra "Using existing files" do orquestrador). O orquestrador escreve o `02_weekly_schedule.md` a partir do programa do personal, sem redesenhá-lo.

Ordem: orquestrador (00, 01, 02, handoff) → exercise-guide ∥ nutrition-linker → template-builder → integração.

Requisito extra: **cruzar TODO exercício contra as restrições de joelho (R1–R8)**.
Idioma: português (pt-BR).

## Fora do escopo

Prescrição de reabilitação (trabalho do fisioterapeuta), alteração do plano da nutricionista e substituição do personal. Os documentos dão apoio e levantam pontos para discutir com esses profissionais.
