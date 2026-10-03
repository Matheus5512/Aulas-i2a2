# Handoff — nutrition-linker

> Substitui SendMessage. Fonte: `04_nutrition_plan.md`.

## Para template-builder

**Resumo das metas** (perfil: homem, 28 anos, 178 cm, 75 kg; GET ≈ 2.680 kcal; lean bulk ≈ GET+300):

| Fase | Semanas | Dia de treino (Seg/Ter/Qui/Sex) | Dia de descanso (Qua/Sáb/Dom) |
|---|---|---|---|
| Adaptação | 1–3 | 3.100 kcal · P 160 g · C 445 g · G 75 g | 2.820 kcal · P 160 · C 355 · G 85 |
| Acumulação | 4–7 | **3.200 kcal** · P 160 · **C 470** · G 75 | 2.820 kcal (igual) |
| Intensificação | 8–11 | 3.200 kcal · P 160 · C 470 · G 75 | 2.820 kcal |
| Deload | 12 | 3.100 kcal (volta à Fase 1, **sem corte**) | 2.820 kcal |

Água: 3,0–3,5 L (treino) / 2,6–3,0 L (descanso). Ganho alvo: **+0,2 a +0,4 kg/semana**.

### Itens a rastrear

| Item | Unidade / formato | Frequência | Meta / regra de alerta |
|---|---|---|---|
| **Peso corporal** (jejum, após urinar) | kg (1 casa decimal) | **Diário** (mínimo 3×/semana) | Base para a média semanal |
| **Média semanal de peso** (calculada) | kg + variação vs. semana anterior | Semanal | Meta +0,2 a +0,4 kg/sem. **Alertas** (tendência de 2 semanas): < +0,1 → "+150 kcal"; > +0,5 → "−150 kcal". **Ignorar S1–2** (água/glicogênio/creatina) |
| **Calorias ingeridas** | kcal | Diário | Comparar com a meta do tipo de dia (treino/descanso) e da fase. OK = ±10% |
| **Proteína** | g (e g/kg calculado) | Diário | **≥ 150 g** (alvo 160 g ≈ 2,1 g/kg). Alerta se < 140 g em 2+ dias da semana |
| **Carboidrato** | g | Diário (pelo menos nos dias de treino) | Treino 445/470 g · descanso 355 g |
| **Gordura** | g | Diário (opcional) | 75 g (treino) / 85 g (descanso). Mínimo 60 g |
| **Tipo de dia** | Treino / Descanso / Descanso + cardio Z2 | Diário | Define qual meta usar. Cardio Z2: +150 kcal |
| **Refeição pré-treino feita?** | Sim/Não + horário | Por sessão (Seg/Ter/Qui/Sex) | Sim, 1,5–2 h antes. Cruzar com "energia pré-treino (1–5)" do architect |
| **Proteína pós-treino em até 2 h?** | Sim/Não | Por sessão | Sim |
| **Água** | L (ou nº de garrafas) | Diário | ≥ 3,0 L (treino) / ≥ 2,6 L (descanso) |
| **Cor da urina** (opcional) | Clara / Amarela / Escura | Diário | "Escura" → beber mais |
| **Creatina tomada** | ✔/✘ | Diário (incluir descanso e deload) | 3–5 g/dia. Aderência ≥ 90% |
| **Whey** | Nº de doses | Diário (opcional) | 0–1 dose. Entra no total de proteína |
| **Cafeína pré-treino** | mg + horário | Por sessão (se usar) | 200–450 mg, 30–60 min antes. **≥ 6–8 h antes de dormir**. Total diário ≤ 400 mg. Pausar no deload |
| **Sono** (já pedido pelo architect) | h | Diário → média semanal | ≥ 7 h. Cruzar com o uso de cafeína |
| **Variação de peso no treino** (opcional) | kg antes/depois | 1–2 sessões por fase | Perda > 1,5 kg (> 2%) → reforçar a hidratação. Repor 1,25–1,5 L por kg perdido |
| **Circunferência da cintura** (na altura do umbigo) | cm | A cada 4 semanas (**S3, S7, S11, S12**), junto com as medidas do architect | Alerta se > +1 cm/mês com força estagnada → "−150 kcal" |
| **Aderência à dieta** (calculada) | % de dias dentro de ±10% das kcal e com proteína ≥ 150 g | Semanal | Meta ≥ 80% |
| **Ajuste calórico aplicado** | ±kcal + data + motivo | Quando ocorrer (máx. 1 a cada 2 semanas) | Histórico de ajustes |
| **Álcool** (opcional) | Nº de doses | Semanal | ≤ 1–2 doses, máx. 1×/semana |

### Sugestões de layout
- **Diário**: incluir no log diário um bloco "Nutrição": tipo de dia, kcal, proteína, carboidrato, água, creatina ✔, pré/pós ✔, cafeína (mg/horário).
- **Resumo semanal**: média de peso + variação, média de kcal e proteína, aderência %, sono médio e o campo "ação da balança" (manter / +150 / −150), preenchido pela regra da seção 10 de `04_nutrition_plan.md`.
- **Avaliação de 4 semanas (S3/S7/S11/S12)**: peso médio, cintura, fotos (já pedidas pelo architect), e1RM dos P e a pergunta "força ↑ e cintura estável?" (sim = superávit correto).
- **Metas por fase**: mostrar automaticamente a meta do dia (tabela acima) conforme a semana (1–12) e o tipo de dia.
