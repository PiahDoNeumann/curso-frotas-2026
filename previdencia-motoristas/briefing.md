# Briefing: A sua aposentadoria, explicada sem enrolação

**Fonte:** Relatório de Gestão Atuarial do ToledoPrev, exercício 2026 (pdf convertido em md) — `references/relatorio-de-gestao-atuarial_toledo-2026.md`
**Fonte secundária:** `references/_tema.md`
**Data da extração:** 11/08/2026
**Público:** motoristas do transporte do Município de Toledo
**Duração alvo:** 60 minutos

## Essência em uma frase

Todo mês sai 14% do contracheque do motorista para o ToledoPrev, e este relatório mostra, em números auditados, para onde vai esse dinheiro, quando ele volta em forma de aposentadoria e se o fundo tem como pagar.

## Conceitos-chave (candidatos a slide)

1. **O desconto de 14% não é imposto, é poupança coletiva** — o servidor confunde desconto previdenciário com tributo. É a base emocional de tudo. — visual: d3-fluxo (contracheque → fundo → aposentadoria)
2. **O Município põe mais que o servidor: 21% contra 14%** — para cada R$ 1 descontado do motorista, a Prefeitura põe R$ 1,50. — visual: comparacao (duas colunas de moedas)
3. **A conta em 2020 mudou: de 11% para 14%** — doeu no bolso, mas segurou o déficit. É honestidade com a plateia. — visual: timeline
4. **Quem é o ToledoPrev: 5.998 pessoas** — 4.357 ativos, 1.447 aposentados, 194 pensionistas. O motorista é uma dessas bolinhas. — visual: metricas / cardume de pontos
5. **A proporção 2,66** — 2,66 pessoas trabalhando para cada uma recebendo. Explica por que o sistema depende de quem está na ativa. — visual: d3-fluxo (balança)
6. **Quando dá para aposentar: 56,87 anos em média** — a projeção caiu de 59 para 56,87. Regras da EC 103/2019. — visual: timeline de vida
7. **Quanto vem no fim: R$ 6.271,93 de média do aposentado contra R$ 4.809,60 de média do ativo** — dado contraintuitivo e forte, o aposentado do ToledoPrev recebe em média mais que o ativo (efeito de carreira e integralidade das regras antigas). — visual: comparacao de barras
8. **Pensão por morte: R$ 3.184,87 de média, 194 famílias** — o que a família recebe se o motorista morrer. Ninguém explica isso ao servidor. — visual: metricas
9. **Compensação previdenciária: o tempo de INSS não some** — quem trabalhou registrado antes do concurso tem esse tempo contado, e o INSS devolve dinheiro ao fundo. R$ 10,5 milhões em 2025, 156% acima do projetado. — visual: d3-fluxo (INSS → ToledoPrev)
10. **O cofre está enchendo: cobertura 27,09% → 32,40% → 37,22%** — em dois anos, o fundo saiu de cobrir 27% das contas futuras para 37%. — visual: metricas / barra de progresso animada
11. **Solvência de 219,86%** — em 2025 entrou R$ 272,5 milhões e saiu R$ 123,9 milhões. Entra mais que o dobro do que sai. — visual: comparacao (dois canos)
12. **O dinheiro trabalha: rendeu 14,78% contra meta de 9,20%** — o fundo não fica parado, é investido. Rendeu 59% acima do mínimo. — visual: metricas
13. **A parte difícil: o déficit de R$ 1,19 bilhão** — o buraco existe, é a diferença entre o que o fundo deve pagar a vida toda e o que tem hoje. Está diminuindo, mas existe. É o slide da credibilidade. — visual: comparacao (o que temos x o que devemos)
14. **Por que o buraco diminuiu: a taxa de juros atuarial subiu de 5,12% para 5,81%** — traduzir como "mudou a régua de cálculo e ficou mais realista". — visual: timeline
15. **A despesa cresce mais rápido que o previsto: 10,96% acima em média** — mais gente se aposentando do que a conta previa. — visual: metricas
16. **O aporte de amortização: R$ 69,8 milhões por ano** — a Prefeitura paga uma parcela extra só para cobrir o buraco do passado. — visual: d3-fluxo
17. **Quem cuida disso: conselhos, atuária e auditoria** — o dinheiro não fica na mão de uma pessoa só. Resolução 026/2025, Conselho de Administração, atuária com registro MIBA. — visual: comparacao / organograma simples

## Dados e números

**O grupo segurado (2026)**
| Grupo | Quantidade | Média mensal |
|---|---|---|
| Ativos | 4.357 | R$ 4.809,60 |
| Aposentados | 1.447 | R$ 6.271,93 |
| Pensionistas | 194 | R$ 3.184,87 |
| **Total** | **5.998** | — |

- Crescimento dos ativos em um ano: +10,67% (3.937 → 4.357)
- Idade média do ativo: 42,21 anos
- Idade média do aposentado: 65,14 anos
- Idade média projetada para aposentadoria: 56,87 anos (era 59 em 2024)
- Proporção ativos / inativos: 2,66 (era 2,51)

**Alíquotas**
- Servidor: 14% (era 11% até 2020)
- Município (patronal): 21%
- Aporte de amortização do déficit: R$ 69.769.881,12 em 2025

**Folhas mensais**
- Ativos: R$ 20.955.427,20
- Aposentados: R$ 9.075.482,71
- Pensionistas: R$ 617.864,78

**Saúde do fundo**
| Indicador | 2024 | 2025 | 2026 |
|---|---|---|---|
| Índice de cobertura das reservas | 27,09% | 32,40% | 37,22% |
| Taxa de juros atuarial | 4,90% | 5,12% | 5,81% |
| Ativos garantidores (R$) | 552,1 mi | 645,5 mi | 794,4 mi |
| Resultado atuarial / déficit (R$) | 1,332 bi | 1,211 bi | 1,194 bi |

**Caixa (execução)**
| Ano | Receita | Despesa | Resultado | Solvência |
|---|---|---|---|---|
| 2022 | 146,2 mi | 89,6 mi | 56,6 mi | 163,17% |
| 2023 | 194,8 mi | 101,4 mi | 93,3 mi | 192,04% |
| 2024 | 210,3 mi | 112,8 mi | 97,5 mi | 186,45% |
| 2025 | 272,5 mi | 123,9 mi | 148,6 mi | 219,86% |

**Rentabilidade 2025:** 14,78% auferida contra meta atuarial de 9,20% (59,12% acima do mínimo esperado)
**Compensação previdenciária recebida em 2025:** R$ 10.573.328,13 (projetado: R$ 4.125.555,96, ou seja, +156,29%)
**Despesa executada média acima do projetado (4 anos):** 10,96%
**Reajuste dos vencimentos no período:** 6,27% de INPC + 2,095850% de aumento real

**Governança**
- Relatório elaborado pela Athena Atuarial, atuária Michele Dall'Agnol (MIBA 2.991)
- Aprovado pela Resolução nº 026/2025 do Conselho de Administração, reunião conjunta com o Conselho Fiscal em 23/06/2026
- Processo SEI nº 01.01.023957/2026-33
- Base legal: Lei Municipal nº 1.929/2006, EC nº 103/2019, Portaria MPS nº 1.467/2022, Pró-Gestão

## Trechos de código emblemáticos

Não se aplica: a fonte é um relatório técnico, não um projeto de software.

## Narrativa sugerida (arco de 60 minutos)

**Bloco 0, abertura (5 min)** — "Você já olhou a linha do desconto no seu contracheque?" Abre com o contracheque e a pergunta que ninguém responde.

**Bloco 1, para onde vai o seu dinheiro (12 min)** — o 14%, o 21% da Prefeitura, a mudança de 2020, para onde o dinheiro vai (não é caixa da Prefeitura, é fundo separado com CNPJ e conselho).

**Bloco 2, quem somos nós (8 min)** — os 5.998, a proporção 2,66, quantos motoristas já se aposentaram, as idades. O motorista se localiza no mapa.

**Bloco 3, quando e com quanto você sai (15 min)** — idade projetada 56,87, EC 103/2019, médias de benefício, pensão por morte para a família, compensação previdenciária do tempo de INSS. Bloco mais longo e mais importante: é o bolso dele.

**Bloco 4, o fundo tem dinheiro? (12 min)** — solvência 219,86%, cobertura subindo 27% → 37%, rentabilidade 14,78% contra meta 9,20%, ativos garantidores de R$ 794 milhões.

**Bloco 5, a parte que ninguém conta (6 min)** — o déficit de R$ 1,19 bilhão, a despesa crescendo 10,96% acima do previsto, o aporte anual de R$ 69,8 milhões. Honestidade: está melhorando, mas não está resolvido.

**Bloco 6, quem vigia o seu dinheiro (4 min)** — conselhos, atuária, auditoria, Pró-Gestão, transparência.

**Encerramento (3 min)** — o que o motorista faz com isso: conferir contracheque, guardar carteira de trabalho antiga (compensação), procurar o ToledoPrev antes de fazer conta de padaria com a própria aposentadoria. Espaço para perguntas.

## Lacunas

- **Não há dado por categoria funcional.** O relatório não separa motoristas dos demais servidores: não dá para dizer "o motorista médio recebe X". Todo número é do conjunto dos 5.998 segurados. Isso precisa ser dito no slide, sob risco de o motorista fazer a conta errada com a própria vida.
- **Regras de aposentadoria em detalhe** (idade mínima, tempo de contribuição, pedágio, regras de transição da EC 103/2019 e da lei municipal) não estão no relatório. Se o público esperar isso, é preciso material do ToledoPrev ou da lei municipal.
- **Não há dado sobre aposentadoria especial** por atividade de risco ou insalubridade, tema provável entre motoristas.
- **Não há valor de teto nem regra de reajuste dos benefícios** já concedidos.
- **Contatos e canais de atendimento do ToledoPrev** para o slide final: só consta o endereço institucional (Rua Raimundo Leonardi, 1586) e o e-mail toledoprev@toledo.pr.gov.br. Não há telefone nem horário.
