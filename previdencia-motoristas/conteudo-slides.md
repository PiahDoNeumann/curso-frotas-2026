# Conteúdo dos slides: A sua aposentadoria, sem enrolação

Fontes: (1) Relatório de Gestão Atuarial do ToledoPrev, exercício 2026 (Athena Atuarial, atuária Michele Dall'Agnol, MIBA 2.991), aprovado pela Resolução 026/2025 do Conselho de Administração; (2) Cartilha Previdenciária do ToledoPrev, gestão 2019 a 2021, de onde vêm todas as regras de aposentadoria, pensão, dependentes, contribuição e contatos. Tema light-minimal. Template aula-capitulo. Público: motoristas do transporte do Município de Toledo. Duração alvo: 60 minutos. Linguagem coloquial. Sem travessão.

> **Revisão de 11/08/2026:** a cartilha entrou como segunda fonte. O deck foi de 30 para 38 e depois condensado para **34 slides**. Novos: os 14% não caem sobre tudo, as quatro portas de saída, regra permanente, regras de transição, de onde sai o valor do benefício, quem são os seus dependentes, como pedir o benefício. Atualizados: agenda, média não é regra, pensão por morte, quem vigia o dinheiro, o que fazer essa semana, perguntas e fontes (telefones).
>
> **Fato confirmado com o cliente:** o Município **não fez a adequação da EC 103/2019** na lei municipal. Logo, as regras da cartilha são as vigentes. O slide dedicado ao aviso foi eliminado e virou uma linha afirmativa dentro de "As quatro portas de saída". O rodapé de fontes também deixou de pedir confirmação e passou a afirmar a vigência.
>
> **Condensações aplicadas (4 slides a menos):**
> 1. "A conta que sustenta tudo (2,66)" + "As idades da casa" viraram **A casa em números**: tabela dos três grupos, mais o 2,66 e o aviso de que a média junta todos os cargos, lado a lado.
> 2. "De 27% para 37%" absorveu "O que o fundo faz com o dinheiro guardado": as três barras de cobertura mais três números compactos (R$ 794,4 mi guardados, 14,78% de rendimento, R$ 94,6 mi de sobra).
> 3. "Três motivos para a melhora" virou uma lista de três linhas dentro do slide do déficit.
> 4. O slide da EC 103/2019 saiu, conforme acima.
>
> **Tempo:** 34 slides em 60 minutos dá 1,75 minuto por slide. Com os quatro divisores levando 15 segundos cada, sobram uns 6 a 8 minutos para perguntas.

Sem vídeo de header: a pasta `mira-templates/videos_header/` está vazia nesta instalação. Se quiser vídeo de fundo, rodar `/mira-get-videos` antes do build.

---

## Slide 1: Capa
- Template: card_citacao
- Título: A sua aposentadoria, sem enrolação
- Subtítulo: O que o relatório do ToledoPrev diz sobre o seu dinheiro
- Ícone: piggy-bank
- Conteúdo: "Todo mês some 14% do seu contracheque. Hoje você vai ver exatamente para onde esse dinheiro vai, e quando ele volta." Linha de apoio: dados do Relatório de Gestão Atuarial 2026, aprovado pelo Conselho de Administração em junho de 2026.

## Slide 2: Agenda
- Template: card_lista
- Título: O roteiro de hoje
- Subtítulo: Seis paradas, uma hora, nenhum palavrão técnico sem tradução
- Conteúdo (6 blocos):
  1. Para onde vai o desconto do seu contracheque
  2. Quem somos nós, os 5.998 do ToledoPrev
  3. Quando você sai e com quanto
  4. O fundo tem dinheiro para pagar?
  5. A parte que ninguém gosta de contar
  6. Quem vigia esse dinheiro

## Slide 3: O desconto que ninguém entende
- Template: card_imagem (mockup HTML de contracheque em papel branco)
- Título: Aquela linha no fim do contracheque
- Subtítulo: "Contribuição previdenciária: 14%"
- Conteúdo: mockup de holerite fictício de motorista, com a linha do desconto destacada em laranja. Exemplo: salário base R$ 4.809,60, desconto previdenciário R$ 673,34. Selo "EXEMPLO FICTÍCIO". Frase de baixo: isso não é imposto. Imposto some. Isso volta.

## Slide 4: Não é imposto, é poupança de grupo
- Template: card_d3 (fluxo animado do dinheiro)
- Título: O caminho do seu dinheiro
- Subtítulo: Do contracheque ao ToledoPrev, e do ToledoPrev de volta para você
- Conteúdo: D3 com moedas saindo de três origens (Você 14%, Prefeitura 21%, Rendimento dos investimentos) caindo num cofre "ToledoPrev", e do cofre saindo um fluxo contínuo para "Aposentadoria" e "Pensão da família". Loop perpétuo. Nota: o dinheiro não entra no caixa da Prefeitura, é fundo separado com conselho próprio.

## Slide 5: Você põe 14, a Prefeitura põe 21
- Template: card_destaques
- Título: Você não está sozinho nessa conta
- Subtítulo: Para cada R$ 1 que sai do seu bolso, o Município põe R$ 1,50
- Conteúdo (2 colunas):
  - Você, servidor: 14% sobre a sua base de cálculo. Em 2025, os ativos juntos contribuíram R$ 37,1 milhões.
  - O Município, patronal: 21%. No mesmo ano, R$ 55,6 milhões. E mais R$ 69,8 milhões de aporte extra para cobrir o buraco do passado.
- Nota de rodapé: a conta do ano fechou em R$ 272,5 milhões de entrada.

## Slide 6: CTA
- Template: card_cta
- Título: Vamos abrir o cofre
- Subtítulo: Os próximos slides são só número, mas todo número aqui é o seu
- Conteúdo: Botão "Abrir o cofre".

## Slide 7: Em 2020 doeu, e valeu
- Template: card_timeline
- Título: Por que subiu de 11% para 14%
- Subtítulo: A mudança que ninguém comemorou e todo mundo precisava
- Conteúdo (etapas):
  - Até 2019: servidor contribuía com 11%. O fundo entrava menos dinheiro do que saía de compromisso.
  - 2019: Emenda Constitucional 103 muda as regras da previdência no país inteiro.
  - 2020: a alíquota do servidor vai para 14%, a patronal fica em 21%.
  - Hoje: o relatório é direto, sem essa mudança o rombo seria maior. Doeu no contracheque, segurou o fundo.

## Slide 8: Divisor, quem somos nós
- Template: card_citacao
- Título: Quem somos nós
- Subtítulo: Divisor de seção
- Ícone: users
- Conteúdo: "Você não é um número no relatório. Você é um dos 5.998."

## Slide 9: Os 5.998 do ToledoPrev
- Template: card_d3 (nuvem de pontos animada, cada ponto uma pessoa)
- Título: Somos 5.998 pessoas nessa conta
- Subtítulo: Quem está na ativa, quem já se aposentou e quem recebe pensão
- Conteúdo: D3 com pontos se agrupando em três blocos, contagem animada: 4.357 ativos (você está aqui), 1.447 aposentados, 194 pensionistas. Loop com respiração dos grupos. Nota: em um ano entraram 420 servidores novos na ativa, crescimento de 10,67%.

## Slide 10: 2,66 trabalhando para cada 1 recebendo
- Template: card_progresso
- Título: A conta que sustenta tudo
- Subtítulo: A proporção entre quem contribui e quem recebe
- Conteúdo: barra/medidor mostrando 2,66. Comparativo dos anos: 2022 com 2,50, 2023 com 2,53, 2024 com 2,51, 2025 com 2,66. Tradução: quanto mais gente na ativa por aposentado, mais folgada fica a conta. Em 2025 melhorou.

## Slide 11: A idade de cada grupo
- Template: card_tabela
- Título: As idades da casa
- Subtítulo: Onde você está nessa régua
- Conteúdo: tabela com Grupo / Quantidade / Idade média / Média mensal:
  - Ativos: 4.357, 42,21 anos, R$ 4.809,60
  - Aposentados: 1.447, 65,14 anos, R$ 6.271,93
  - Pensionistas: 194, 60,79 anos, R$ 3.184,87
- Aviso importante em destaque: essas médias são de todos os servidores do Município, não só dos motoristas. O relatório não separa por cargo. Não use isso para calcular a sua aposentadoria.

## Slide 12: Divisor, quando você sai
- Template: card_citacao
- Título: Quando você sai, e com quanto
- Subtítulo: Divisor de seção
- Ícone: calendar-clock
- Conteúdo: "Essa é a parte que interessa. A partir daqui é o seu futuro na tela."

## Slide 13: 56 anos e 10 meses
- Template: card_d3 (linha do tempo de vida animada)
- Título: A idade em que a média sai
- Subtítulo: Projeção de aposentadoria: 56,87 anos
- Conteúdo: D3 com uma régua de vida percorrida por um marcador: entrada no serviço, 42,21 anos (idade média de hoje), 56,87 anos (saída projetada), 65,14 anos (idade média de quem já está aposentado). Nota: a projeção caiu de 59 anos em 2024 para 56,87 agora.

## Slide 14: Atenção com a regra
- Template: card_destaques
- Título: Média não é regra
- Subtítulo: O que o relatório diz e o que ele não diz
- Conteúdo (2 colunas):
  - O que o relatório traz: a idade média projetada do conjunto dos servidores e o comportamento do fundo. É estatística, serve para planejar o fundo.
  - O que ele não traz: a sua regra pessoal de aposentadoria, idade mínima, tempo de contribuição, pedágio da EC 103/2019, regra de transição, aposentadoria especial. Isso é conversa individual no ToledoPrev, com a sua matrícula na mão.

## Slide 15: Quanto cai na conta depois
- Template: card_d3 (barras comparativas animadas)
- Título: Quanto recebe quem já saiu
- Subtítulo: Média do aposentado contra média de quem está na ativa
- Conteúdo: D3 com duas barras crescendo: ativo R$ 4.809,60 e aposentado R$ 6.271,93. Explicação em uma linha: aposentado ganha mais na média porque quem se aposenta é quem fez carreira inteira, com progressões e regras antigas de integralidade. Não é promessa, é retrato de hoje.

## Slide 16: Se você faltar
- Template: card_grid
- Título: A pensão que fica para a família
- Subtítulo: 194 famílias recebem hoje pelo ToledoPrev
- Conteúdo (4 itens):
  - Quem recebe: dependentes habilitados, conforme a lei municipal e a EC 103/2019.
  - Quanto é hoje: média de R$ 3.184,87 por mês.
  - Quanto o fundo paga por mês: R$ 617.864,78 só em pensões.
  - O que fazer agora: manter os dependentes atualizados no cadastro. Cadastro errado atrasa a vida da família na pior hora.

## Slide 17: O tempo de INSS não some
- Template: card_d3 (fluxo animado INSS para ToledoPrev)
- Título: Trabalhou de carteira assinada antes? Conta
- Subtítulo: Compensação previdenciária
- Conteúdo: D3 com dois cofres, INSS e ToledoPrev, e um fluxo de moedas indo do INSS para o ToledoPrev quando um servidor se aposenta. Números na tela: em 2025 o fundo recebeu R$ 10.573.328,13 do INSS, quando esperava R$ 4.125.555,96, ou seja 156% acima. Recado prático: guarde carteira de trabalho, PIS, contratos antigos. Esse papel vira dinheiro no seu tempo de contribuição.

## Slide 18: Divisor, o fundo tem dinheiro?
- Template: card_citacao
- Título: Mas o fundo tem dinheiro para pagar?
- Subtítulo: Divisor de seção
- Ícone: landmark
- Conteúdo: "A pergunta que todo mundo faz no corredor. A resposta está em três números."

## Slide 19: Entra mais do que sai
- Template: card_d3 (dois canos, entrada e saída)
- Título: Em 2025 entrou o dobro do que saiu
- Subtítulo: Solvência financeira de 219,86%
- Conteúdo: D3 com um cano grosso entrando (R$ 272,5 milhões) e um cano fino saindo (R$ 123,9 milhões), sobrando R$ 148,6 milhões no caixa. Loop contínuo. Tradução da palavra difícil: solvência acima de 100% quer dizer que entrou mais do que saiu.

## Slide 20: Quatro anos no azul
- Template: card_tabela
- Título: Não foi sorte de um ano só
- Subtítulo: Receita, despesa e sobra, de 2022 a 2025
- Conteúdo: tabela com Ano / Entrou / Saiu / Sobrou / Solvência:
  - 2022: R$ 146,2 mi / R$ 89,6 mi / R$ 56,6 mi / 163,17%
  - 2023: R$ 194,8 mi / R$ 101,4 mi / R$ 93,3 mi / 192,04%
  - 2024: R$ 210,3 mi / R$ 112,8 mi / R$ 97,5 mi / 186,45%
  - 2025: R$ 272,5 mi / R$ 123,9 mi / R$ 148,6 mi / 219,86%

## Slide 21: O cofre está enchendo
- Template: card_progresso
- Título: De 27% para 37% em dois anos
- Subtítulo: Índice de cobertura das reservas
- Conteúdo: três barras de progresso animadas: 2024 com 27,09%, 2025 com 32,40%, 2026 com 37,22%. Tradução: de cada R$ 100 que o fundo vai precisar pagar lá na frente, ele já tem R$ 37,22 guardados hoje. Há dois anos tinha R$ 27,09. Está enchendo.

## Slide 22: O dinheiro não dorme
- Template: card_grid
- Título: O que o fundo faz com o dinheiro guardado
- Subtítulo: R$ 794,4 milhões investidos
- Conteúdo (4 itens):
  - Quanto está guardado: R$ 794.377.995,25 em ativos garantidores, contra R$ 552,1 milhões em 2024.
  - Quanto rendeu em 2025: 14,78%.
  - Quanto precisava render: 9,20%, a meta atuarial.
  - Sobrou de rendimento: 59,12% acima do mínimo exigido, ou R$ 94,6 milhões no ano.

## Slide 23: Divisor, a parte difícil
- Template: card_citacao
- Título: Agora a parte que ninguém gosta de contar
- Subtítulo: Divisor de seção
- Ícone: alert-triangle
- Conteúdo: "Se alguém só te contar a parte boa, desconfie. Aqui vai a conta inteira."

## Slide 24: O buraco de R$ 1,19 bilhão
- Template: card_destaques
- Título: O déficit existe, e está diminuindo
- Subtítulo: O que o fundo tem hoje contra tudo o que vai ter que pagar
- Conteúdo (2 colunas):
  - O que tem no cofre hoje: R$ 794,4 milhões.
  - O que vai precisar pagar ao longo dos anos: R$ 2,13 bilhões em reservas (benefícios já concedidos mais os que ainda vão ser). A diferença é o déficit de R$ 1,19 bilhão.
- Rodapé: era R$ 1,33 bilhão em 2024 e R$ 1,21 bilhão em 2025. Está caindo. Não é dívida vencida, é conta de longo prazo, e por isso existe o aporte anual de R$ 69,8 milhões.

## Slide 25: Por que o buraco diminuiu
- Template: card_lista
- Título: Três motivos para a melhora
- Subtítulo: O que mudou entre 2024 e 2026
- Conteúdo:
  1. A régua de cálculo ficou mais realista: a taxa de juros atuarial subiu de 4,90% para 5,81%, porque o fundo bateu a meta de rendimento.
  2. O dinheiro rendeu acima do esperado: 14,78% contra meta de 9,20%.
  3. Entrou mais gente na ativa: 420 servidores a mais em um ano, ou seja, mais contribuição entrando todo mês.

## Slide 26: O alerta honesto
- Template: card_progresso
- Título: A despesa cresce mais rápido que a conta previa
- Subtítulo: Média de 10,96% acima do projetado nos últimos 4 anos
- Conteúdo: barras comparando projetado e executado por ano: 2022 com 18,60%, 2023 com 9,76%, 2024 com 7,98%, 2025 com 7,51% acima do previsto. Explicação: mais gente se aposentou do que a conta esperava, e benefício concedido não volta atrás. Por isso o relatório recomenda continuar estudando as regras.

## Slide 27: Quem vigia o seu dinheiro
- Template: card_grid
- Título: Não é uma pessoa decidindo sozinha
- Subtítulo: A governança do ToledoPrev
- Conteúdo (4 itens):
  - Atuária independente: Michele Dall'Agnol, registro MIBA 2.991, da Athena Atuarial, faz a conta todo ano.
  - Conselho de Administração e Conselho Fiscal: analisaram e aprovaram em reunião conjunta de 23/06/2026, pela Resolução 026/2025.
  - Certificação: conselheiros com certificação CP RPPS, exigida por lei.
  - Pró-Gestão do Ministério da Previdência: o relatório existe para cumprir o requisito 3.2.3 do programa nacional de boas práticas.

## Slide 28: O que você faz com isso amanhã
- Template: card_lista
- Título: Quatro coisas para fazer essa semana
- Subtítulo: Sai da sala e resolve
- Conteúdo:
  1. Confira a linha do desconto no seu contracheque e veja se a base está certa.
  2. Ache a sua carteira de trabalho e os papéis de emprego antigo. Esse tempo vira dinheiro na compensação.
  3. Atualize os seus dependentes no cadastro. É o que garante a pensão da sua família.
  4. Antes de decidir quando sair, peça a sua simulação no ToledoPrev. Média de relatório não é a sua regra.

## Slide 29: Resumo em cinco números
- Template: card_lista
- Título: Se você só levar cinco números daqui
- Subtítulo: Fechamento
- Conteúdo:
  1. 14% seu e 21% da Prefeitura, todo mês.
  2. 5.998 segurados, sendo 4.357 na ativa.
  3. 56,87 anos: idade média projetada de saída.
  4. 219,86% de solvência: entrou mais que o dobro do que saiu em 2025.
  5. 37,22% de cobertura, contra 27,09% dois anos atrás. O cofre está enchendo.

## Slide 30: Perguntas e fontes
- Template: card_cta
- Título: Agora é com vocês
- Subtítulo: Perguntas, e onde conferir tudo isso
- Conteúdo: Botão "Perguntas". Fontes na tela: Relatório de Gestão Atuarial do ToledoPrev, exercício 2026, Athena Atuarial. Resolução 026/2025 do Conselho de Administração, Processo SEI 01.01.023957/2026-33. ToledoPrev, Rua Raimundo Leonardi, 1586, Toledo/PR. toledoprev@toledo.pr.gov.br. Site: toledoprev.toledo.pr.gov.br. Nota: os valores em holerite e documentos exibidos são exemplos fictícios.

---

## Mapa final do deck (34 slides no index.html)

As fichas detalhadas acima seguem a numeração do plano original de 30 slides. A ordem que está no HTML hoje é esta:

| # | Slide | Fonte |
|---|---|---|
| 1 | Capa | ambas |
| 2 | O roteiro de hoje | ambas |
| 3 | Aquela linha no fim do contracheque | cartilha |
| 4 | O caminho do seu dinheiro (D3) | ambas |
| 5 | Você não está sozinho nessa conta, 14% e 21% | ambas |
| 6 | **Os 14% não caem sobre tudo** (hora extra, noturno, insalubridade fora da base) | cartilha |
| 7 | CTA, vamos abrir o cofre | — |
| 8 | Por que subiu de 11% para 14% | relatório |
| 9 | Divisor, quem somos nós | — |
| 10 | Somos 5.998 pessoas (D3) | relatório |
| 11 | **A casa em números** (tabela dos 3 grupos + 2,66 + aviso da média) | relatório |
| 12 | Divisor, quando você sai | — |
| 13 | A idade em que a média sai, 56,87 (D3) | relatório |
| 14 | Média não é regra | ambas |
| 15 | **As quatro portas de saída** (com o aviso de que a EC 103 ainda não vale em Toledo) | cartilha |
| 16 | **A regra permanente** (tabela homem/mulher) | cartilha |
| 17 | **Entrou faz tempo? Regras de transição** (EC 41 arts. 2º e 6º, EC 47 art. 3º, paridade) | cartilha |
| 18 | **De onde sai o valor do seu benefício** (até 31/12/2003 x depois, piso, teto, abono) | cartilha |
| 19 | Quanto recebe quem já saiu (D3) | relatório |
| 20 | A pensão que fica para a família (100% até o teto + 70% do excedente) | ambas |
| 21 | **Quem o ToledoPrev considera seu dependente** (3 classes, união estável) | cartilha |
| 22 | Trabalhou de carteira assinada antes? Compensação (D3) | relatório |
| 23 | **O caminho do pedido, passo a passo** | cartilha |
| 24 | Divisor, o fundo tem dinheiro? | — |
| 25 | Em 2025 entrou o dobro do que saiu (D3) | relatório |
| 26 | Não foi sorte de um ano só (tabela 2022 a 2025) | relatório |
| 27 | **De 27% para 37% em dois anos** (+ guardado, rendimento e sobra) | relatório |
| 28 | Divisor, a parte difícil | — |
| 29 | **O déficit existe, e está diminuindo** (+ os três motivos da melhora) | relatório |
| 30 | A despesa cresce mais rápido que a conta previa | relatório |
| 31 | Não é uma pessoa decidindo sozinha (TCE-PR, CRP, conselhos eleitos) | ambas |
| 32 | Quatro coisas para fazer essa semana | ambas |
| 33 | Se você só levar cinco números daqui | relatório |
| 34 | Agora é com vocês, contatos e fontes | cartilha |

**Se ainda precisar cortar:** slide 8 (histórico do 11% para 14%) e slide 33 (resumo de cinco números, se o 32 já fechou bem). Ficam 32 slides.

**Bloco inegociável:** 14 a 18 e 20 a 23. É o que o motorista veio ouvir e é o que a cartilha responde.

## Recursos e observações do deck

- Média de 1,5 minuto por slide. Os divisores (9, 13, 26, 31) levam 15 segundos cada, o que devolve tempo para os blocos densos.
- Animações D3 nos slides 4, 9, 13, 15, 17 e 19, todas com loop interno perpétuo (regra zero do Mira).
- Mockup de holerite (slide 3) em estilo papel branco, combinando com o tema light-minimal, sempre com selo "EXEMPLO FICTÍCIO".
- Aviso obrigatório de que as médias são do conjunto dos servidores, não dos motoristas, nos slides 11 e 14.
- Sem vídeo de header nesta instalação (pasta de vídeos vazia).
