# Transcrição da sessão /grill-me

**Objeto:** Mapa de Atores da jornada "Atendimento ao Seguro-Desemprego pela URA da CAIXA" (0800 726 0207).
**Contexto:** `B_relatorio_assistente_v3.md` (catálogo A01–A93, RACI preliminar, fluxos F01–F19, atritos P01–P10, lacunas L01–L11).
**Metodologia:** Aula 03 (IDP), "Mapeamento de Atores em Diagnóstico de Serviço Público", pp. 29–46 e 59:

- Passo 0: propósito.
- Passo 1: listagem concêntrica em 7 categorias, mais vozes críticas.
- Passo 2: Matriz de Mendelow.
- Passo 3: incentivos e resistências.
- Passo 4: relações.
- Passo 5: 5–8 atores-chave e hipóteses.

**Dinâmica:** cada rodada traz as decisões cujo pré-requisito já está resolvido, cada uma com uma recomendação. "Sim" aceita a recomendação.

---

## Rodada 1

**Q1 — Propósito do mapa (Passo 0).** O mapa deve partir do propósito (a), com (b) e (c) como subcasos? As opções são:

- (a) recontato e encaminhamento errado: a URA da CAIXA atende um problema que é do MTE (P01, P04, P09);
- (b) acessibilidade (P05);
- (c) transição do defeso (P06).

Redação proposta: *"reduzir recontato e encaminhamento errado no 0800 726 0207, explicitando quem resolve cada tipo de problema"*.

➡️ Recomendação: (a). É o problema do meta-prompt ("jogado de um canal para outro") e se conecta com *failure demand* (pp. 11–19).
**Resposta:** Sim.

**Q2 — Recorte da jornada.** O mapa deve ter a URA 0207 no centro, as etapas 5–8 em detalhe e, das etapas 1–4, só os atores que geram demanda na URA (MTE, Dataprev, empregador/eSocial)?
➡️ Recomendação: sim.
**Resposta:** Sim.

**Q3 — Taxonomia.** Os atores devem ser reclassificados nas 7 categorias da aula, com "Vozes críticas" como grupo adicional? A sequência é Usuários → Operadores → Gestores/Decisores → Controle → Fornecedores → Intermediários → Normatizadores/Judiciário. URA, roteamento e motor de regras entram como **Operadores automatizados (IA/automação)**.
➡️ Recomendação: sim. Segue a expansão concêntrica (p. 34) e atende ao critério "humanos e de IA".
**Resposta:** Sim.

**Q4 — Atores hipotéticos.** Devem entrar, com marcação visual de hipótese, só os hipotéticos essenciais ao propósito? São eles:

- A50, roteamento;
- A58, gestor da fila 0207;
- A20, terceirizado de contact center;
- A44, golpistas.

Os demais ficam de fora.
➡️ Recomendação: sim.
**Resposta:** Sim.

**Q5 — Formato dos diagramas (Passo 4).** A entrega deve trazer duas peças em mermaid?

- (1) cebola em `flowchart`, com camadas concêntricas e setas tipadas: informação, dinheiro, decisão, encaminhamento e conflito;
- (2) `quadrantChart` de Mendelow.

➡️ Recomendação: sim. A cebola é o formato detalhado na aula (GOV.UK, p. 41).
**Resposta:** Sim.

**Q6 — Registro.** Cada rodada deve ser gravada na íntegra neste arquivo, sem commit até ordem expressa?
➡️ Recomendação: sim.
**Resposta:** Sim.

---

## Rodada 2

**Q7 — Lista de atores (Passo 1).** Proposta de 37 atores nas 7 categorias, mais as vozes críticas:

- **Usuários:** A01, A03, A45 [H], A46.
- **Operadores humanos:** A07, A20 [H], A15, A11+A63, A62.
- **Operadores automatizados (IA):** A06, A50 [H], A48, A49, A47, A10, A12, A14+A91.
- **Gestores/Decisores:** A29 (fundindo A87–A89), A32, A58 [H], A53.
- **Controle:** A39, A40, A37, A42.
- **Fornecedores:** A21, A23, A28.
- **Intermediários:** A33, A35, A36 [H], A60 [H], A64 [H], A44 [H].
- **Normatizadores/Judiciário:** A30+A31, A66, A67, A38, A55.
- **Vozes críticas:** A09, A56+A57, A41, A43, A54.

Ficam de fora os sistemas internos de baixo nível (A22, A25, A72–A82, A90, A92, A93), A52 e A13.
➡️ Recomendação: sim.
**Resposta:** Sim, com acréscimo: *"adicionar a usuários os usuários comuns, que são a maioria e que precisam também ser contemplados."*

**Q8 — Subgrupos de usuários.** O trabalhador formal é o usuário-referência, o pescador entra como subcaso de rota (P06) e A45/A46 como subgrupos de acesso. Doméstico, resgatado e qualificação ficam em nota de rodapé.
➡️ Recomendação: sim. Para o propósito, o que diferencia os usuários é a rota e a capacidade de uso da URA.
**Resposta:** Sim.

**Q9 — Vozes críticas ausentes.** Devem ser incluídos, como nó "vozes ausentes" marcado como lacuna, os grupos que a aula pede e o v3 não traz: conselhos de usuários (Lei 13.460/2017), controle social organizado e jornalismo de dados.
➡️ Recomendação: sim. A ausência é achado de diagnóstico (p. 35).
**Resposta:** Sim.

**Q10 — Pontuação Mendelow (Passo 2).** Cada ator recebe notas de 0 a 1 em Poder e Interesse, marcadas [INFERIDO], com justificativa de uma linha. Ambas são ancoradas no propósito da Q1:

- **Interesse:** o quanto o ator é afetado por recontato e encaminhamento errado no 0207.
- **Poder:** a capacidade de mudar o roteiro, os dados ou as regras.

➡️ Recomendação: sim.
**Resposta:** Sim.

**Q11 — Eixo da RACI.** As linhas passam a ser os motivos da ligação, cada um com a coluna "onde a URA deveria encaminhar". Os motivos são:

1. status da parcela;
2. crédito não localizado;
3. cartão/senha/saque;
4. indeferimento/suspensão/revisão;
5. dado do empregador divergente;
6. defeso legado;
7. atendimento acessível;
8. reclamação do canal;
9. suspeita de golpe.

➡️ Recomendação: sim.
**Resposta:** Sim.

---

## Rodada 3

**Q12 — Quem é o "usuário comum".** Há três leituras possíveis:

- (a) O usuário comum do Seguro-Desemprego: trabalhador formal típico, maioria das ligações, com celular e algum acesso digital e sem barreira específica. Seria a linha de base, distinta de A45/A46, e A01 passaria a ser esse ator.
- (b) Usuários comuns da central 0207 (PIS, FGTS, Bolsa Família), que disputam a mesma URA e a mesma fila.
- (c) As duas.

➡️ Recomendação: (c).
**Resposta:** (a). A01 passa a ser "Trabalhador formal — usuário comum (maioria)", linha de base distinta dos subgrupos A03, A45 e A46.

**Q13 — Escopo do Passo 3.** A análise de incentivos (manutenção, resistência, alavanca) cobre os atores de alto poder e alto interesse e também os de alto poder e baixo interesse com influência sobre a URA: TCU, CODEFAT/FAT, Dataprev e empregador.
➡️ Recomendação: sim. A fricção estrutural vem do controle e da TI (pp. 37–38).
**Resposta:** Sim.

**Q14 — Conflitos no diagrama (Passo 4).** Cinco conflitos entram como setas tracejadas:

1. A32 × A29: a CAIXA atende sobre decisão alheia (P01).
2. A06 × usuário: beco sem saída e acesso a humano (Downe #8, #14).
3. A33 × trabalhador: dado divergente ou omitido (P02).
4. A58/A20 × resolução: metas de TMA × FCR [H].
5. A44 × usuário: exploração da confusão entre canais (P07).

➡️ Recomendação: sim, com o 4 marcado como hipótese (L02/L03).
**Resposta:** Sim.

**Q15 — Dono do encaminhamento.** Na RACI, o "A" da passagem entre canais (URA CAIXA → MTE/158/CTD) é registrado como "⚠ ausente", e isso é tratado como achado central.
➡️ Recomendação: sim.
**Resposta:** Sim.

**Q16 — Rastreabilidade.** Os IDs do v3 se mantêm e os atores novos são numerados a partir de A94.
➡️ Recomendação: sim.
**Resposta:** Sim.

---

## Rodada 4

**Q17 — Atores automatizados fora da Matriz de Mendelow.** URA, roteamento, motor de regras, antifraude, WhatsApp, CTD, 158 e CAIXA Tem ficam fora da matriz e aparecem só na cebola e na RACI. O poder deles é atribuído aos donos: A06/A50/A47/A14 → CAIXA/A58; A48/A49/A12/A10 → MTE/Dataprev.
➡️ Recomendação: sim. Pontuar "interesse" de um sistema seria antropomorfizar.
**Resposta:** Sim.

**Q18 — Notas de Mendelow.** Esta questão passou por quatro iterações.

1. **Proposta inicial.** Notas de 0 a 1 atribuídas por julgamento holístico. O usuário perguntou: *"quais os critérios vc usou para atribuir as notas?"* O assistente reconheceu que as notas vinham da coluna "Poder de influência" do v3 e de padrões da aula, e que o interesse não tinha fonte.
2. **Rubrica de alavancas.** Quatro alavancas por eixo (P1–P4, I1–I4). Resposta do usuário: *"ainda parece mero 'chute', quero uma atribuição de valores com base em uma avaliação mais objetiva, ainda que seja apenas observacional."*
3. **Índice documental.** Um script contou, nas tabelas do v3, as participações em RACI, fluxos, atritos e etapas. O resultado era reproduzível, mas distorcido: idosos, pessoas surdas e golpistas caíram em "Monitorar" e o pescador ficou com mais interesse que o usuário comum. O índice mede quanto o v3 fala do ator, não o poder real. Em seguida foi proposta uma rubrica binária por evidência. Resposta do usuário: *"um critério objetivo para um resultado errado é um critério ruim, concorda? Vamos voltar ao básico e justificar as atribuições das notas por avaliação subjetiva vinculada ao processo, lembrar sempre que o ponto focal é melhorar o serviço para o usuário, então o usuário deve ser alguém relevante nesse processo. Refaça a pontuação."*
4. **Versão final.** Avaliação subjetiva justificada pelo processo da ligação.
   - **Poder:** o que o ator consegue mudar antes, durante e depois da ligação.
   - **Interesse:** quanto o recontato o afeta.
   - **Princípio:** o usuário tem três alavancas reais (volume e escolha de canal, voz pela Lei 13.460, escalada) e sobe para "gerenciar de perto". Isso diverge do slide da p. 36 com base na armadilha nº 1 da p. 44.
   - **Quadrantes (corte 0,5):**
     - **Gerenciar de perto:** A01 (0,65; 1,00), A45 (0,50; 1,00), A46 (0,50; 1,00), A03 (0,50; 0,95), A32 (0,95; 0,85), A29 (0,95; 0,70), A58 [H] (0,70; 0,85).
     - **Manter satisfeito:** A30/31 (0,80; 0,25), A39 (0,75; 0,25), A21 (0,70; 0,30), A33 (0,60; 0,25), A37 (0,55; 0,20), A40 (0,55; 0,40), A38 (0,55; 0,15), A67 (0,50; 0,20).
     - **Manter informado:** A07 (0,35; 0,90), A09 (0,40; 0,75), A20 [H] (0,40; 0,75), A44 [H] (0,30; 0,75), A64 [H] (0,35; 0,70), A60 [H] (0,15; 0,70), A56/57 (0,35; 0,65), A11/63 (0,25; 0,60), A62/08 (0,20; 0,60), A94 (0,15; 0,60), A36 [H] (0,25; 0,55), A43 (0,45; 0,55), A35 (0,35; 0,50).
     - **Monitorar:** A15 (0,25; 0,45), A41 (0,30; 0,45), A55 (0,30; 0,40), A53 (0,40; 0,35), A54 (0,15; 0,40), A28 (0,30; 0,35), A23 (0,40; 0,15), A42 (0,40; 0,15), A66 (0,45; 0,10).

**Resposta:** Sim.

**Q19 — RACI por motivo de ligação.** As linhas são:

- **0. Passagem entre canais:** A = ⚠ ausente.
- **1. Status da parcela:** A = A32.
- **2. Crédito não localizado:** A = A32.
- **3. Cartão/senha/saque:** A = A32.
- **4. Indeferimento/revisão:** A = A29.
- **5. Dado do empregador:** A = A29, R = A33.
- **6. Defeso legado:** A = A53 ou A29, conforme a data.
- **7. Atendimento acessível:** A = A32, R = A62/A08 e A47.
- **8. Reclamação:** A = A32 com R = A09, ou A29 com R = A56/57.
- **9. Golpe:** A = A32.

Cada linha traz a coluna "para onde a URA deveria encaminhar". C e I são [INFERIDO]. A08 entra junto com A62.
**Resposta:** Sim.

**Q20 — Estrutura do `C_mapa_atores.md`.** As seções seguem os passos da aula:

1. Propósito e recorte.
2. Catálogo.
3. Mendelow (tabela + `quadrantChart`).
4. Incentivos.
5. Cebola com conflitos.
6. RACI.
7. Atores-chave e hipóteses.
8. Armadilhas da p. 44 e lacunas.

**Resposta:** Sim.

---

## Rodada 5

**Q21 — Incentivos (Passo 3), [INFERIDO].** A análise cobre 11 atores. Para cada um, o primeiro item é a manutenção (o que ganha hoje com o serviço como está), o segundo é a resistência (o que perde com a mudança) e o terceiro é a alavanca (o que ganha com a mudança).

- **A01:**
  - Manutenção: telefone sem login.
  - Resistência: hábito.
  - Alavanca: resolver em 1 contato (P01, P04).
- **A45/A46:**
  - Manutenção: nada.
  - Resistência: nada.
  - Alavanca: autonomia e paridade (P05, S05).
- **A03:**
  - Alavanca: rota pela data do defeso (P06, S06).
- **A32:**
  - Manutenção: URA genérica barata; "procure o MTE" encerra a chamada.
  - Resistência: custo de integração; responder por decisão alheia.
  - Alavanca: menos recontato (P01).
- **A29:**
  - Manutenção: o custo da dúvida recai na CAIXA (externalidade).
  - Resistência: explicar motivos; expor a qualidade dos dados (P02).
  - Alavanca: menos recurso mal direcionado e menos demanda no 158/SRTE.
- **A58 [H]:**
  - Manutenção: metas de TMA e transbordo cumpridas.
  - Resistência: FCR pode piorar o TMA.
  - Alavanca: indicador de recontato (S08).
- **A30/31:**
  - Alavanca: menos devolução ao FAT (F11).
- **A39:**
  - Manutenção: controles redundantes.
  - Alavanca: rastreabilidade (aliado condicional).
- **A21:**
  - Manutenção: contratos de sustentação.
  - Resistência: risco de SLA.
  - Alavanca: contrato de integração.
- **A33:**
  - Manutenção: não retificar não tem custo.
  - Resistência: obrigação de correção.
  - Alavanca: nada direto (exige incentivo regulatório).

➡️ Recomendação: sim. A análise evidencia a externalidade MTE→CAIXA e a meta de TMA.
**Resposta:** Sim.

**Q22 — Atores-chave (Passo 5).** Os sete atores-chave são:

1. A01, como representante de A45, A46 e A03.
2. A32.
3. A29.
4. A58 [H].
5. A07.
6. A21.
7. A33.

O TCU entra como aliado condicional, fora da lista.
➡️ Recomendação: sim. A lista cobre causa (A33, A21, A29), canal (A32, A58, A07) e efeito (A01).
**Resposta:** Sim.

**Q23 — Camadas da cebola (Passo 4).** A cebola tem cinco camadas:

- **Centro:** usuários.
- **Anel 1:** ponto de contato (operadores humanos e automatizados).
- **Anel 2:** decisão e retaguarda (gestores e fornecedores).
- **Anel 3:** regras e controle.
- **Faixa lateral:** intermediários e vozes críticas.

O diagrama desenha só os fluxos e os 5 conflitos que tocam os atores-chave. A relação completa fica em tabela.
➡️ Recomendação: sim.
**Resposta:** Sim.

---

## Rodada 6

**Q24 — Hipóteses de diagnóstico (Passo 5).** Cada hipótese tem um indicador do framework de métricas da aula (pp. 20–25).

- **H1 — Externalidade MTE→CAIXA.** Ninguém é dono da passagem entre canais, e o cidadão volta a ligar.
  - Atores: A32, A29, A01.
  - Indicador: recontato em 7 dias nos motivos 4 e 5.
  - Dimensão: volume.
  - Vínculos: P01, P04, S01, S04.
- **H2 — Metas de TMA/transbordo favorecem encerrar a chamada em vez de resolver.**
  - Atores: A58 [H], A20 [H], A07.
  - Indicador: FCR × TMA por motivo.
  - Dimensão: qualidade.
  - Vínculos: L02, L03, S08.
- **H3 — Defasagem e vocabulário do status.**
  - Atores: A21, A29, A32.
  - Indicador: tempo entre lote e URA; recontato nos motivos 1 e 2.
  - Dimensão: eficiência temporal.
  - Vínculos: P03, L04, S03, F15.
- **H4 — Dado do empregador divergente gera indeferimento cujo motivo não chega à URA.**
  - Atores: A33, A29, A01.
  - Indicador: % de indeferimentos por divergência que geram ligação.
  - Dimensão: custo/retrabalho.
  - Vínculos: P02, S02.
- **H5 — URA só de voz exclui A45/A46**, que passam a depender de A60 e ficam expostos a A44.
  - Indicador: abandono e conclusão por perfil e canal.
  - Dimensão: acesso.
  - Vínculos: P05, P07, S05, S07.
- **H6 — Não há ciclo de retorno do atendente para A58/A29.**
  - Atores: A07, A58, A29.
  - Indicador: taxonomia de motivos e % de ligações classificadas.
  - Dimensão: volume.
  - Vínculos: P08, S08, L05.

➡️ Recomendação: sim. H1 é a hipótese central. H2 e H6 dependem de validação (L02, L03, L05).
**Resposta:** Sim.

**Q25 — Fechamento.** Gerar o `C_mapa_atores.md` com as 8 seções, os diagramas mermaid e a RACI, validar a sintaxe mermaid e registrar a rodada 6. Não fazer commit sem ordem expressa.
➡️ Recomendação: sim.
**Resposta:** Sim.

---

**Errata registrada na geração do mapa.** A Q7 anunciou "37 atores", mas a lista aprovada soma 44 atores. Com A94 (vozes ausentes), aprovado na Q9, o total é 45. Os 37 da Q18 são os 45 menos os 8 automatizados excluídos da matriz pela Q17. Nenhuma decisão muda.

**Árvore de decisões encerrada:** 6 rodadas, Q1–Q25, com 4 iterações na Q18.

---

## Rodada 7 — Revisão crítica do mapa (perguntas abertas, sem recomendação)

> A pedido do aluno, as rodadas de revisão crítica trazem uma **provocação** (contraponto) no lugar da resposta recomendada. Cada resposta deve vir com justificativa.

**Q26 — Os 7 atores-chave estão certos?** A lista era: A01, A32, A29, A58 [H], A07, A21, A33. O TCU estava fora, como aliado condicional.

> Provocação: A58 é hipotético e sustenta H2 e H6, o que fragiliza o diagnóstico.

**Resposta:** *"Estamos falando de atores-chave, nesse contexto quero apenas os atores que podem impedir ou dificultar as ações de mudanças na operação, nesse contexto a CEF não me parece um ator que tenha poder de veto no tocante à FORMA de atuação ou operação do sistema."*

**Q26.2 — A CAIXA realmente não tem veto?** O 0207 é uma central multisserviço da própria CAIXA, e o contrato MTE–CAIXA não comprova que o MTE pode impor mudanças à URA (E02, L10). A CAIXA pode adiar ou deixar de priorizar uma mudança, o que é veto de fato.
**Resposta:** *"vc está correto, vamos manter a Caixa."*

**Q26.1 — Pelo critério de veto, usuário e atendente saem?** Isso choca com o princípio da Q18 (usuário relevante) e com a armadilha nº 1 da aula.
**Resposta:** *"usuário e atendente ficam, porque, apesar de não terem poder de impedir os avanços, eles fazem parte essencial da operação."*
→ Critério consolidado: **é ator-chave quem pode impedir ou dificultar a mudança, ou quem é parte essencial da operação.**

**Q26.3 — Quem mais entra?** Candidatos: TCU, ANPD, CODEFAT, terceirizado e empregador.
**Respostas:**

- **TCU:** *"Não vejo o TCU como um ator que, apesar de poder intervir, viria a intervir nesse particular de desenho de processos internos."* → sai. Coerente com F13: os acórdãos tratam de pagamento e dados.
- **Demais:** *"ANPD não entra, está muito distante, CODEFAT sai, terceirizado fica pelo mesmo motivo da CAIXA, ele é quem vai executar o desenho do código, empregador fica porque é peça fundamental."*

**Q26.4 — Qual terceirizado?** No v3, A20 é a operação **humana** de contact center. Quem constrói e altera a URA é A84 (fornecedores de URA/ACD/gravação/TTS), hipotético e excluído na Q4. As opções eram: (a) A20, (b) A84, (c) os dois.
**Resposta:** (b). **A84 entra no mapa** como ator-chave hipotético e substitui A20 na lista de chave. A20 permanece no mapa como ator não-chave.

**Resultado da Q26 — 8 atores-chave:**

| Ator | Critério |
|---|---|
| A01 Usuário comum | Operação |
| A07 Atendente | Operação |
| A32 CAIXA | Veto de fato + operação |
| A29 MTE | Veto + operação |
| A21 Dataprev | Veto (integração) |
| A58 Gestor da fila [H] | Veto + operação |
| A84 Fornecedor de tecnologia da URA [H] | Executa o desenho |
| A33 Empregador | Peça fundamental (origina o dado) |

Ficam de fora o TCU, a ANPD e o CODEFAT.

**Q26.5 — Posição do A84 na Matriz de Mendelow.** Proposta: Poder 0,55 e Interesse 0,35, quadrante "manter satisfeito".

- **Poder:** implementa qualquer mudança na árvore e nas integrações, e pode atrasá-la ou condicioná-la a aditivo contratual. Não decide o que muda.
- **Interesse:** não sente o recontato; ganha com projetos de mudança.

**Resposta:** *"concordo com as notas do A84"*.

**Q27 — O que o cidadão realmente quer quando liga?**

> Provocação: talvez a maioria seja só "quando vou receber?". Nesse caso, a *failure demand* estaria na clareza da informação, e não na passagem entre canais.

**Resposta:** *"o cidadão quer atendimento E resolução do seu problema e não apenas ser direcionado para outros lugares, é importante para o cidadão ver que existe intenção real do serviço em atender o seu pedido. Um segundo motivo é tentar resolver uma questão que ficou pendente anteriormente."*

A resposta recusa a provocação e traz dois deslocamentos:

1. **De "encaminhar" para "resolver".** A coluna da RACI "para onde a URA deveria encaminhar" parte de uma premissa que o aluno rejeita: para o cidadão, ser encaminhado não é ser atendido.
2. **Um motivo novo: retomar pendência de contato anterior.** É o próprio recontato visto pelo lado do cidadão. Esse motivo não existe na RACI.

**Q27.1 — O que "resolver" significa quando a CAIXA não tem competência legal (motivos 4 e 5)?** Opções:

- (a) transferência com contexto ao 158;
- (b) a CAIXA como porta única, abrindo a demanda no MTE com protocolo;
- (c) retorno ativo do MTE.

> Provocação: (b) obriga a CAIXA a responder por processo que não controla (conflito C1).

**Resposta:** *"b, a CAIXA como porta única com protocolo, com certeza."*

**Q27.3 — Por que a CAIXA aceitaria ser porta única?** Opções: aditivo contratual, remuneração por protocolo, redução do próprio recontato.

> Provocação: se a alavanca for só o contrato, a mudança depende de o MTE querer exigir.

**Resposta:** *"A Caixa ou quem seja o gestor da URA deve ser capaz de receber e resolver as demandas, não é razoável que um agente destinado a receber as demandas não possa ser capaz de resolvê-las, viraria apenas uma telefonista, e não é esse o objetivo. Se o problema é competência, que haja a delegação de competências."*

A resposta não escolhe entre as alavancas oferecidas e reformula a questão. O problema não é o incentivo da CAIXA. O problema é que **quem recebe a demanda não tem competência para resolvê-la**, e a saída proposta é a **delegação de competências** do MTE ao gestor da URA. O papel da URA e do atendente muda de "telefonista" (encaminhar) para "resolutor" (decidir ou executar).

**Q27.4 — Até onde vai a delegação?** Três tipos de ato:

- (i) **Operacionais:** abrir revisão, corrigir cadastro, reemitir parcela (R07b art. 21 §2º), desbloquear, registrar recurso.
- (ii) **Instrução:** consultar e explicar o motivo do indeferimento; pedir retificação ao empregador.
- (iii) **Mérito:** deferir ou indeferir recurso, rever habilitação.

> Provocação: parar em (i) e (ii) ainda deixa o cidadão esperando o MTE. Ir até (iii) levanta a pergunta de quem responde pelo erro de mérito.

**Resposta:** *"i e ii delegados; mérito continua com o MTE."*
→ A CAIXA/gestor da URA **executa e instrui**; o MTE **decide o mérito**. Por consequência, o "A" da linha 10 da RACI (retomar pendência anterior) é da **CAIXA/gestor da URA**, dona do protocolo e da continuidade. Essa consequência não foi contestada.

**Q28 — Causa raiz.** As respostas anteriores apontam como causa raiz **a separação entre quem recebe a demanda e quem tem competência para resolvê-la**. Isso reformula H1, que estava escrita como "externalidade de custo MTE→CAIXA". Os demais candidatos (linguagem das cartas e dos status, acesso a humano, desenho do menu) seriam causas secundárias ou sintomas?

**Resposta:** *"seriam causas secundárias e precisam entrar na equação de resolução."*

→ **H1 é reformulada:** causa raiz = separação entre recepção e competência. A externalidade de custo passa a ser o mecanismo que a mantém.
→ **Causas secundárias** (linguagem, acesso a humano, menu) não são descartadas. Entram na solução ao lado da delegação. Ficam como H1a–H1c, ligadas a H3 (status), H5 (acesso) e S01 (triagem por objeto).

**Q27.5 — Quem garante que o MTE decida o mérito no prazo?** Opções: SLA bilateral no contrato MTE–CAIXA, norma do CODEFAT, prazos da Lei 13.460, outro.

> Provocação: sem prazo, a porta única troca "ligar para o 158" por "esperar o protocolo", e o recontato reaparece como cobrança.

**Resposta:** *"SLA no contrato MTE–CAIXA seria uma inovação formidável."*
→ Entra no mapa uma **relação contratual bilateral** entre A29 e A32: o MTE delega os atos (i) e (ii) e se obriga a decidir o mérito em prazo; a CAIXA se obriga a resolver e acompanhar. A L10 (contrato 07/2026 sem instrumento verificado) passa a ser a lacuna crítica dessa solução.

**Q27.6 — O CODEFAT volta para os atores-chave? O TCU muda?**

**Resposta:** *"CODEFAT volta, TCU continua fora."*
→ **A30/31 volta aos atores-chave** como dono do ato normativo que viabiliza a delegação. O TCU segue fora: o aluno mantém o juízo da Q26.3.

**Q29 — Nove atores-chave excedem o intervalo de 5 a 8 da aula (p. 43).** Opções:

- (a) fundir A58 (gestor da fila, hipotético) na CAIXA (A32);
- (b) fundir A84 em A58;
- (c) manter 9 e justificar a exceção.

> Provocação: com (a), H2 e H6 passam a ser atribuídas à CAIXA como um todo. Ficam mais robustas, porque o ator existe, e mais vagas, porque não se sabe quem muda as metas.

**Resposta:** (a). **A58 é absorvido por A32** em todo o mapa: catálogo, Mendelow, cebola e RACI. A gestão da fila 0207 passa a ser função interna da CAIXA.

**Atores-chave finais (8):** A01 Usuário comum · A07 Atendente · A32 CAIXA (incl. gestão da fila) · A29 MTE · A21 Dataprev · A84 Fornecedor da URA [H] · A33 Empregador · A30/31 CODEFAT.

**Fim da rodada 7.** A revisão crítica mudou o mapa em seis pontos:

1. **Critério de ator-chave:** quem impede ou dificulta a mudança, ou quem é parte essencial da operação.
2. **Atores:** entra A84; A58 é fundido em A32; saem TCU e ANPD; CODEFAT volta.
3. **RACI-alvo:** resolver em vez de encaminhar. A CAIXA vira porta única com protocolo e com delegação dos atos operacionais e de instrução. O mérito fica com o MTE. Entra a linha 10 (pendência anterior).
4. **SLA bilateral** no contrato MTE–CAIXA.
5. **H1 reformulada:** a causa raiz é a separação entre recepção e competência.
6. **Causas secundárias** (H1a–c) entram na solução.

**Rodadas registradas:** 7 (Q1–Q29).
