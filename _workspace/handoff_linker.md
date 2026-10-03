# Handoff — nutrition-linker

> Substitui SendMessage. Fonte: `04_nutrition_plan.md` (03/10/2026).

## Para template-builder

**Contexto:** o plano que vale é o da nutricionista **Mariana Muñoz (CRN3 34962), de 08/05/2026**, e ele **não tem meta de kcal nem de macros**. Por isso o template **não deve pedir contagem de calorias nem de macros**. Use checklists de aderência por refeição, água, proteína por refeição e indulgências. As estimativas abaixo são só referência para o resumo da nutricionista, não metas.

| Referência (estimativa) | Valor |
|---|---|
| GET | ≈ 2.600 kcal/dia (2.450–2.750) |
| Déficit moderado de referência | 300–500 kcal → ~2.100–2.300 kcal/dia |
| Proteína estimada no plano | ≈ 120 g/dia (105–140) ≈ 1,5 g/kg · referência ISSN 128–176 g (1,6–2,2 g/kg) |
| Ritmo de peso esperado | −0,25 a −0,5 kg/semana |
| Água | 3 L (base do plano) · ~3,5 L em dia de musculação/natação |

### Itens a rastrear

| Item | Unidade / formato | Frequência | Meta / regra de alerta |
|---|---|---|---|
| **Café 07:00 feito conforme o plano** | ✔/✘ | Diário | — |
| **Almoço 12:00 conforme o plano** (marmita com 150 g de proteína) | ✔/✘ | Diário | — |
| **Lanche 16:00 conforme o plano** | ✔/✘ + opção escolhida (texto curto) | Diário | — |
| **Jantar 21:30** | Padrão / Rap-pão sírio / Petiscos / Pizza / Fora do plano | Diário | Em dia de musculação (Seg/Qua/Sex), preferir "Padrão". Alerta suave se "Fora do plano" ≥ 2x/semana |
| **Porção de proteína feita** (150 g no almoço, 150 g no jantar) | Almoço ✔/✘ · Jantar ✔/✘ | Diário | Alerta se faltar em ≥ 3 refeições na semana (reduz a proteína do dia em ~45 g cada) |
| **Proteína no café/lanche** (opcional) | ✔/✘ "tinha fonte de proteína?" | Diário | Só informativo. Levar à nutricionista (P3) |
| **Aderência ao plano** (calculada) | % de refeições ✔ na semana (4 refeições × 7 dias = 28) | Semanal | Meta ≥ 80% (≥ 23/28). Alerta se < 70% por 2 semanas |
| **Talento/bombom** | Contador (0–7) | Semanal (marcar no dia) | **≤ 3/semana**. Alerta se ≥ 4 |
| **Pizza** | Nº de pedaços por ocasião | Quando ocorrer | **≤ 2 pedaços**. Alerta se > 2 |
| **Água** | L (ou nº de garrafas) | Diário | **≥ 3 L** (todo dia) · **≥ 3,5 L** em dia de musculação/natação. Alerta se < 2,5 L em 2+ dias da semana |
| **Água na natação** | ✔/✘ "levou garrafa e bebeu entre os blocos?" | Por sessão de natação (Ter/Sáb) | Alerta se ✘ (na piscina se sua sem perceber) |
| **Cor da urina** (opcional) | Clara / Amarela / Escura | Diário | "Escura" → beber mais |
| **Pré-treino feito** | ✔/✘ + horário (fruta no cenário manhã; lanche 16:00 no cenário noite) | Por sessão (musculação e natação) | Cruzar com "energia" do diário. Alerta se energia baixa em ≥ 2 sessões com pré ✘ |
| **Pós-treino** | Horário da refeição seguinte (almoço ou jantar) | Por sessão | Ideal ≤ 2–3 h depois do fim do treino. Só informativo |
| **Horário do treino** | Manhã / Noite + hora | Por sessão | Define qual cenário de timing usar (A manhã / B noite) |
| **Peso corporal** (jejum, após urinar, sem roupa) | kg (1 casa) | Diário ou ≥ 3x/semana | Base para a média semanal |
| **Média semanal de peso** (calculada) | kg + variação vs. semana anterior | Semanal | Esperado −0,25 a −0,5 kg/sem. **Alerta → levar à nutricionista** se < −0,75 kg/sem por 2 semanas, ou se estável (±0,1) por 4 semanas junto com a cintura estável |
| **Variação de peso na sessão** (opcional) | kg antes/depois (sem roupa, seco) | 1–2 sessões de musculação e 1–2 de natação no período | Perda > 1,5 kg → reforçar a hidratação. Repor 1,25–1,5 L por kg perdido |
| **Cintura** (já pedida pelo orquestrador) | cm | S1, S3, S5, S6 | Meta < 94 cm |
| **Bioimpedância** (já pedida) | Campos padrão | S1 e S6, mesmas condições | Alerta se % músculo esquelético cair → rever proteína/energia com a nutricionista |
| **Suplemento** (somente se a nutricionista liberar) | ✔/✘ por suplemento + **data de início** | Diário | Creatina: registrar a data de início em relação à bioimpedância da S1 (retém água e altera peso/leitura) |
| **Sono** (já pedido) | h | Diário | ≥ 7 h |

### Sugestões de layout
- **Bloco diário "Nutrição"**: 4 caixas (café / almoço / lanche / jantar) ✔/✘, tipo de jantar, "150 g de proteína: almoço ✔ jantar ✔", água (L), Talento/bombom (✔ no dia), pré-treino ✔ e horário do treino.
- **Resumo semanal**: aderência % (x/28), contador de Talento/bombom (x/3), pizza (pedaços), média de água, média de peso + variação e alertas acionados.
- **Resumo para a nutricionista (S6)**: aderência média, média de água, nº de refeições sem a porção de proteína, tendência de peso e cintura, bioimpedância S1 × S6 e a lista de perguntas P1–P12 da seção 11 de `04_nutrition_plan.md`, com espaço para as respostas.
- **Não incluir** campos de kcal, carboidrato ou gordura. Isso só entra se a nutricionista definir metas.
