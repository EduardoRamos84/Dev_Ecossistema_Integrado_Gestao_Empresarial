# E9-01 — PLANO, MANIFESTO DE ENTRADAS E MATRIZ DE ELEGIBILIDADE DE EC-02

## MINUTA v0.1 — PARA REVISÃO — EXCLUSIVAMENTE DOCUMENTAL — SEM AUTORIZAÇÃO TÉCNICA

| Campo | Valor |
|---|---|
| Projeto | Dev_Ecossistema_Integrado_Gestao_Empresarial |
| Fase | Fase 05 |
| Escopo | ESC-F05-09 — Preparação isolada do primeiro recorte e manifesto físico controlado |
| Unidade | UT-F05-09-01 — Entradas, subconjunto e condições de EC-02 |
| Produto | E9-01 — Plano, manifesto de entradas e matriz de elegibilidade de EC-02 |
| Data documental | 21/09/2026 |
| Responsável humano | Eduardo Andrade Ramos |
| Estado | UT-F05-09-01 iniciada; E9-01 em minuta; aceite, publicação e conclusão pendentes |
| Linha mestre vigente | REG-CONSOLIDACAO-CHATS v0.24 / REG-DECISOES v0.28 / REG-PENDENCIAS v0.23 |
| Estado de EC-02 | Não criado, não ativado e não autorizado |
| Executor técnico | Não designado |

## 1. Autoridade, objetivo e resultado desta produção

Em ato expresso, específico e separado, o Gestor criou e ativou `ESC-F05-09` exclusivamente no alcance documental preparatório das três primeiras unidades, designou Eduardo Andrade Ramos como responsável humano e iniciou `UT-F05-09-01`. O mesmo ato autorizou a preparação deste produto e manteve sua publicação dependente de aceite e autorização posteriores.

Esta minuta:

1. fixa o manifesto das entradas vigentes;
2. transporta sem alteração o universo de 175 linhas de E8-02;
3. delimita nominalmente 64 linhas como elegíveis somente para o planejamento documental de EC-02;
4. preserva nominalmente 111 linhas como diferidas;
5. registra as dependências residuais de L-01 a L-07;
6. estabelece critérios de entrada, integridade, parada e saída para o Portão A.

**RESULTADO PROPOSTO.** Considerar documentalmente fechado o universo de referência de E9-01 em 175 linhas, sendo 64 `ELEGIVEL_DOCUMENTAL_EC02` e 111 `DIFERIDA_EC02`. Essa classificação permite preparar E9-02 após os atos e portões próprios; não autoriza EC-02, ambiente, executor, dados, cópia, estrutura, identidade, escrita, implementação ou teste.

## 2. Regra de interpretação da elegibilidade

A classificação `ELEGIVEL_DOCUMENTAL_EC02` significa apenas que a linha:

- estava `APLICAVEL` no estado aceito de E8-02;
- não possui marca L-01 a L-07 na matriz antecedente;
- pode integrar o subconjunto nominal de referência para especificar ambiente, responsabilidades e manifesto em E9-02 e E9-03;
- permanece sem existência física comprovada;
- não poderá ser construída em EC-02, pois estruturas e identidade pertencem a EC-03.

A classificação `DIFERIDA_EC02` significa que a linha:

- conserva uma ou mais condições residuais de L-01 a L-07;
- fica fora do subconjunto elegível de E9-01;
- não pode ser promovida por inferência, conveniência técnica ou simples existência de decisão documental geral;
- só poderá ser reavaliada em versão ou produto futuro autorizado, com fonte e condição material suficientes.

Nenhuma linha desta matriz é objeto técnico autorizado. A elegibilidade é documental e não equivale a construído, copiável, executável, testável, carregável ou migrável.

## 3. Manifesto controlado das entradas

### 3.1 Linha mestre vigente

| Registro publicado em `08_Consolidados/` | Bytes | SHA-256 | Git blob | Função |
|---|---:|---|---|---|
| REG-CONSOLIDACAO-CHATS v0.24 | 212.664 | `dabd9f4dc4f30078f85c8ba4351fc8a123d0f325f37f79113d4e94895493d050` | `4b6789390fc8b3c80cef32e96de2d8038d16d7ae` | Estado corrente, sequência e limites |
| REG-DECISOES v0.28 | 267.781 | `764f64b173bfcd1e55ffacceba4752e00f9dba7289228f331b24bd656ffc865c` | `49e20dd4f4524fad7091cc2c19ecd104cb582217` | Decisões vigentes e ressalvas |
| REG-PENDENCIAS v0.23 | 202.885 | `9f91a4a7856939d1848b063d23eb057075a38e53cda01a1cb93aa08dc50652ba` | `ff9927f5406460cb6effe14bb9ba16680178dc62` | Pendências oficiais e fronteiras |

Publicação sincronizada: commit `2615e869628d910ae19edfd00c6edcef1e1dd50e`. Os três arquivos constituem a linha mestre vigente. Nenhum deles é alterado por E9-01.

### 3.2 Definição e governança de ESC-F05-09

| Documento | Identidade | Estado e função |
|---|---|---|
| PROPOSTA-DEFINICAO-FORMAL-DO-PROXIMO-ESCOPO-DA-FASE-05-POS-ESC-F05-08 v0.1 | 27.453 bytes; SHA-256 `18d9740fb656759adca1cb0a8b0bee0a705de70b7ae37b02e6b782ffe1f8c91e`; Git blob `e1e138701a6a4d7ab123304ec034b9001126e530`; commit `182f47f1437e224a2817b3ff30c298e5db65ab02` | Definição aceita, publicada e conferida |
| REG-CRIACAO-RESPONSABILIDADE-E-ATIVACAO-ESC-F05-09 v0.1 | Minuta preparada em conjunto com E9-01; identidade calculada após gravação final | Registra o ato humano; não é fonte de mérito da matriz |

### 3.3 Produtos antecedentes de EC-01

| Produto vigente | Bytes | SHA-256 | Função nesta minuta |
|---|---:|---|---|
| E8-01 v0.1 | 18.893 | `a9e567736d395ce203359dc166f081135d2e680704a1629b059b0351bf9046fd` | Manifesto das entradas e universo controlado de EC-01 |
| E8-02 v0.1 | 114.158 | `2ecfa1fff3578b1c4d3221e5181cc11bc808aaee931e8e39df563dab671a6851` | Fonte nominal das 175 linhas e dos estados `APLICAVEL`/`DIFERIDO` |
| E8-03 v0.2 | 17.211 | `1b9e83cc6e25ab6bf35c83fbcd1ac62ac32dedfd5b7039262c786bd745aecaac` | D8-L01-A a D8-L07-A e condições residuais |
| E8-04 v0.1 | 17.260 | `e0d697a073c9ccff8d7a4b601cf92b6047407902488f35c076a40da380682ba9` | Coerência, rastreabilidade e prontidão exclusivamente documental |
| E8-05 v0.2 | 18.870 | `a8db9107f933eb15d76cc4ffb2a29b274c6ef7fe0356f6bf29f7425d67644baa` | Estado resultante, fechamento documental de EC-01 e condições para eventual EC-02 |

Também permanecem fontes vinculantes E7-01 v0.3, E7-02 v0.2, E7-03 v0.2, E7-04 v0.1 e E7-05 v0.2, nos limites e ocorrências já conferidos em E8. A classificação nominal abaixo é transportada de E8-02 e qualificada pelas decisões e ressalvas posteriores; não reabre nem reescreve os produtos antecedentes.

## 4. Controles de integridade do universo

| Controle | Resultado conferido |
|---|---:|
| Total de linhas | 175 |
| Detalhes oficiais | 123 |
| Complementos controlados | 52 |
| Linhas `APLICAVEL` em E8-02 | 64 |
| Linhas `DIFERIDO` em E8-02 | 111 |
| Detalhes oficiais elegíveis documentalmente | 41 |
| Complementos elegíveis documentalmente | 23 |
| Detalhes oficiais diferidos | 82 |
| Complementos diferidos | 29 |
| IDs duplicados | 0 |
| Interseção entre elegíveis e diferidos | 0 |
| Linhas sem classificação E9-01 | 0 |
| Cenários executados | 0 de 30 |

A matriz é exaustiva e mutuamente exclusiva no universo transportado. As contagens não autorizam promoção, construção ou prova física.

## 5. Matriz nominal de elegibilidade de EC-02

| ID_CONTROLE | NATUREZA | PF_ORIGEM | CAMPO_ORIGEM | CONTÊINER CANDIDATO DE E8-02 | LACUNA E8-02 | ESTADO E8-02 | ELEGIBILIDADE E9-01 | LIMITE |
|---|---|---|---|---|---|---|---|---|
| DET-PF-01-F01 | DETALHE_OFICIAL | PF-01 | id_objeto | Objeto_Identidade / tbObjetoIdentidade | L-01,L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-03 preservada; fora do subconjunto elegível |
| DET-PF-01-F02 | DETALHE_OFICIAL | PF-01 | tipo_objeto | Objeto_Identidade / tbObjetoIdentidade | L-01,L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-02 preservada; fora do subconjunto elegível |
| DET-PF-01-F03 | DETALHE_OFICIAL | PF-01 | id_objeto_principal | Objeto_Identidade / tbObjetoIdentidade | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-01-F04 | DETALHE_OFICIAL | PF-01 | identificador_versao | Objeto_Identidade / tbObjetoIdentidade | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-01-F05 | DETALHE_OFICIAL | PF-01 | id_antecessor | Objeto_Identidade / tbObjetoIdentidade | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-01-F06 | DETALHE_OFICIAL | PF-01 | situacao_vigencia | Objeto_Identidade / tbObjetoIdentidade | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-02-F01 | DETALHE_OFICIAL | PF-02 | id_referencia_externa | Referencia_Externa / tbReferenciaExterna | L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-03 preservada; fora do subconjunto elegível |
| DET-PF-02-F02 | DETALHE_OFICIAL | PF-02 | id_objeto | Vinculo_Referencia / tbVinculoReferencia | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-02-F03 | DETALHE_OFICIAL | PF-02 | tipo_referencia | Referencia_Externa / tbReferenciaExterna | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-02-F04 | DETALHE_OFICIAL | PF-02 | valor_referencia | Referencia_Externa / tbReferenciaExterna | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-02-F05 | DETALHE_OFICIAL | PF-02 | emissor_ou_origem | Referencia_Externa / tbReferenciaExterna | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-02-F06 | DETALHE_OFICIAL | PF-02 | escopo_referencia | Referencia_Externa / tbReferenciaExterna | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-02-F07 | DETALHE_OFICIAL | PF-02 | id_fonte_evidencia | Referencia_Externa / tbReferenciaExterna | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-02-F08 | DETALHE_OFICIAL | PF-02 | id_evento_registro | Referencia_Externa / tbReferenciaExterna | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-02-F09 | DETALHE_OFICIAL | PF-02 | situacao_referencia | Referencia_Externa / tbReferenciaExterna | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-03-F01 | DETALHE_OFICIAL | PF-03 | id_fonte_evidencia | Fonte_Evidencia / tbFonteEvidencia | L-03,L-04 | DIFERIDO | DIFERIDA_EC02 | Dependência L-03,L-04 preservada; fora do subconjunto elegível |
| DET-PF-03-F02 | DETALHE_OFICIAL | PF-03 | nome_ou_denominacao | Fonte_Evidencia / tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-03-F03 | DETALHE_OFICIAL | PF-03 | natureza_fonte | Fonte_Evidencia / tbFonteEvidencia | L-02,L-04 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-04 preservada; fora do subconjunto elegível |
| DET-PF-03-F04 | DETALHE_OFICIAL | PF-03 | finalidade_fonte | Fonte_Evidencia / tbFonteEvidencia | L-02,L-04 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-04 preservada; fora do subconjunto elegível |
| DET-PF-03-F05 | DETALHE_OFICIAL | PF-03 | referencia_verificavel | Fonte_Evidencia / tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-03-F06 | DETALHE_OFICIAL | PF-03 | referencia_integridade | Fonte_Evidencia / tbFonteEvidencia | L-05 | DIFERIDO | DIFERIDA_EC02 | Dependência L-05 preservada; fora do subconjunto elegível |
| DET-PF-03-F07 | DETALHE_OFICIAL | PF-03 | versao_fonte | Fonte_Evidencia / tbFonteEvidencia | L-04,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-04,L-07 preservada; fora do subconjunto elegível |
| DET-PF-03-F08 | DETALHE_OFICIAL | PF-03 | corte_fonte | Fonte_Evidencia / tbFonteEvidencia | L-04 | DIFERIDO | DIFERIDA_EC02 | Dependência L-04 preservada; fora do subconjunto elegível |
| DET-PF-03-F09 | DETALHE_OFICIAL | PF-03 | momento_captura | Fonte_Evidencia / tbFonteEvidencia | L-04,L-06,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-04,L-06,L-07 preservada; fora do subconjunto elegível |
| DET-PF-03-F10 | DETALHE_OFICIAL | PF-03 | ref_responsavel_captura | Fonte_Evidencia / tbFonteEvidencia | L-01,L-04 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-04 preservada; fora do subconjunto elegível |
| DET-PF-03-F11 | DETALHE_OFICIAL | PF-03 | situacao_classificacao | Fonte_Evidencia / tbFonteEvidencia | L-02,L-06 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-06 preservada; fora do subconjunto elegível |
| DET-PF-03-F12 | DETALHE_OFICIAL | PF-03 | situacao_disponibilidade | Fonte_Evidencia / tbFonteEvidencia | L-02,L-05,L-06 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-05,L-06 preservada; fora do subconjunto elegível |
| DET-PF-03-F13 | DETALHE_OFICIAL | PF-03 | situacao_pratica | Fonte_Evidencia / tbFonteEvidencia | L-02,L-06 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-06 preservada; fora do subconjunto elegível |
| DET-PF-03-F14 | DETALHE_OFICIAL | PF-03 | id_decisao_pratica | Fonte_Evidencia / tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-03-F15 | DETALHE_OFICIAL | PF-03 | id_conjunto_equivalencia | Fonte_Evidencia / tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-03-F16 | DETALHE_OFICIAL | PF-03 | situacao_conflito | Fonte_Evidencia / tbFonteEvidencia | L-02,L-06 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-06 preservada; fora do subconjunto elegível |
| DET-PF-03-F17 | DETALHE_OFICIAL | PF-03 | finalidade_precedencia | Fonte_Evidencia / tbFonteEvidencia | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-03-F18 | DETALHE_OFICIAL | PF-03 | id_fonte_prevalente | Fonte_Evidencia / tbFonteEvidencia | L-04 | DIFERIDO | DIFERIDA_EC02 | Dependência L-04 preservada; fora do subconjunto elegível |
| DET-PF-03-F19 | DETALHE_OFICIAL | PF-03 | id_decisao_excecao | Fonte_Evidencia / tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-03-F20 | DETALHE_OFICIAL | PF-03 | tipo_derivacao | Fonte_Evidencia / tbFonteEvidencia | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-03-F21 | DETALHE_OFICIAL | PF-03 | id_fonte_derivada_de | Fonte_Evidencia / tbFonteEvidencia | L-04 | DIFERIDO | DIFERIDA_EC02 | Dependência L-04 preservada; fora do subconjunto elegível |
| DET-PF-04-F01 | DETALHE_OFICIAL | PF-04 | id_vinculo_evidencia | Vinculo_Evidencia / tbVinculoEvidencia | L-01,L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-03 preservada; fora do subconjunto elegível |
| DET-PF-04-F02 | DETALHE_OFICIAL | PF-04 | id_fonte_evidencia | Vinculo_Evidencia / tbVinculoEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-04-F03 | DETALHE_OFICIAL | PF-04 | tipo_elemento_sustentado | Vinculo_Evidencia / tbVinculoEvidencia | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-04-F04 | DETALHE_OFICIAL | PF-04 | id_elemento_sustentado | Vinculo_Evidencia / tbVinculoEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-04-F05 | DETALHE_OFICIAL | PF-04 | finalidade_do_vinculo | Vinculo_Evidencia / tbVinculoEvidencia | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-04-F06 | DETALHE_OFICIAL | PF-04 | escopo_de_aplicacao | Vinculo_Evidencia / tbVinculoEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-04-F07 | DETALHE_OFICIAL | PF-04 | id_evento_vinculo | Vinculo_Evidencia / tbVinculoEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-04-F08 | DETALHE_OFICIAL | PF-04 | situacao_vinculo | Vinculo_Evidencia / tbVinculoEvidencia | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-05-F01 | DETALHE_OFICIAL | PF-05 | id_evento | Evento_Auditoria / tbEventoAuditoria | L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-03 preservada; fora do subconjunto elegível |
| DET-PF-05-F02 | DETALHE_OFICIAL | PF-05 | dominio_atingido | Evento_Auditoria / tbEventoAuditoria | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-05-F03 | DETALHE_OFICIAL | PF-05 | tipo_objeto_atingido | Evento_Auditoria / tbEventoAuditoria | L-01,L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-02 preservada; fora do subconjunto elegível |
| DET-PF-05-F04 | DETALHE_OFICIAL | PF-05 | id_objeto_atingido | Evento_Auditoria / tbEventoAuditoria | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-05-F05 | DETALHE_OFICIAL | PF-05 | identificador_versao_atingida | Evento_Auditoria / tbEventoAuditoria | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-05-F06 | DETALHE_OFICIAL | PF-05 | id_vinculo_atingido | Evento_Auditoria / tbEventoAuditoria | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-05-F07 | DETALHE_OFICIAL | PF-05 | tipo_evento | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F08 | DETALHE_OFICIAL | PF-05 | instante_evento | Evento_Auditoria / tbEventoAuditoria | L-06,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-06,L-07 preservada; fora do subconjunto elegível |
| DET-PF-05-F09 | DETALHE_OFICIAL | PF-05 | instante_registro | Evento_Auditoria / tbEventoAuditoria | L-06,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-06,L-07 preservada; fora do subconjunto elegível |
| DET-PF-05-F10 | DETALHE_OFICIAL | PF-05 | tipo_dimensao_afetada | Evento_Auditoria / tbEventoAuditoria | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-05-F11 | DETALHE_OFICIAL | PF-05 | valor_temporal_afetado_ref | Evento_Auditoria / tbEventoAuditoria | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-05-F12 | DETALHE_OFICIAL | PF-05 | estado_anterior | Evento_Auditoria / tbEventoAuditoria | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-05-F13 | DETALHE_OFICIAL | PF-05 | estado_posterior | Evento_Auditoria / tbEventoAuditoria | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-05-F14 | DETALHE_OFICIAL | PF-05 | valor_anterior_ref | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F15 | DETALHE_OFICIAL | PF-05 | valor_posterior_ref | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F16 | DETALHE_OFICIAL | PF-05 | classificacao_anterior | Evento_Auditoria / tbEventoAuditoria | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-05-F17 | DETALHE_OFICIAL | PF-05 | classificacao_posterior | Evento_Auditoria / tbEventoAuditoria | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-05-F18 | DETALHE_OFICIAL | PF-05 | id_vinculo_anterior | Evento_Auditoria / tbEventoAuditoria | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-05-F19 | DETALHE_OFICIAL | PF-05 | id_vinculo_posterior | Evento_Auditoria / tbEventoAuditoria | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-05-F20 | DETALHE_OFICIAL | PF-05 | ref_autor | Evento_Auditoria / tbEventoAuditoria | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-05-F21 | DETALHE_OFICIAL | PF-05 | ref_executor | Evento_Auditoria / tbEventoAuditoria | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-05-F22 | DETALHE_OFICIAL | PF-05 | ref_autoridade | Evento_Auditoria / tbEventoAuditoria | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-05-F23 | DETALHE_OFICIAL | PF-05 | natureza_execucao | Evento_Auditoria / tbEventoAuditoria | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-05-F24 | DETALHE_OFICIAL | PF-05 | ref_origem_instrucao | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F25 | DETALHE_OFICIAL | PF-05 | justificativa | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F26 | DETALHE_OFICIAL | PF-05 | id_fonte_principal | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F27 | DETALHE_OFICIAL | PF-05 | ref_regra_ou_decisao | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F28 | DETALHE_OFICIAL | PF-05 | versao_regra_ou_decisao | Evento_Auditoria / tbEventoAuditoria | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-05-F29 | DETALHE_OFICIAL | PF-05 | id_correlacao | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F30 | DETALHE_OFICIAL | PF-05 | resultado_evento | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F31 | DETALHE_OFICIAL | PF-05 | id_evento_anterior | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-05-F32 | DETALHE_OFICIAL | PF-05 | id_evento_substituto_ou_desfazimento | Evento_Auditoria / tbEventoAuditoria | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-05-F33 | DETALHE_OFICIAL | PF-05 | referencia_alertas_pendencias | Evento_Auditoria / tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-06-F01 | DETALHE_OFICIAL | PF-06 | id_vinculo_empresarial | Vinculo_Empresarial / tbVinculoEmpresarial | L-01,L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-03 preservada; fora do subconjunto elegível |
| DET-PF-06-F02 | DETALHE_OFICIAL | PF-06 | id_objeto | Vinculo_Empresarial / tbVinculoEmpresarial | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-06-F03 | DETALHE_OFICIAL | PF-06 | id_empresa | Vinculo_Empresarial / tbVinculoEmpresarial | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-06-F04 | DETALHE_OFICIAL | PF-06 | papel_empresa | Vinculo_Empresarial / tbVinculoEmpresarial | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-06-F05 | DETALHE_OFICIAL | PF-06 | id_dimensao_temporal_inicio | Vinculo_Empresarial / tbVinculoEmpresarial | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-06-F06 | DETALHE_OFICIAL | PF-06 | id_dimensao_temporal_fim | Vinculo_Empresarial / tbVinculoEmpresarial | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-06-F07 | DETALHE_OFICIAL | PF-06 | id_evento_inicio | Vinculo_Empresarial / tbVinculoEmpresarial | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-06-F08 | DETALHE_OFICIAL | PF-06 | id_evento_fim_ou_correcao | Vinculo_Empresarial / tbVinculoEmpresarial | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-06-F09 | DETALHE_OFICIAL | PF-06 | id_fonte_evidencia | Vinculo_Empresarial / tbVinculoEmpresarial | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-07-F01 | DETALHE_OFICIAL | PF-07 | id_dimensao_temporal | Dimensao_Temporal / tbDimensaoTemporal | L-03,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-03,L-07 preservada; fora do subconjunto elegível |
| DET-PF-07-F02 | DETALHE_OFICIAL | PF-07 | id_objeto | Dimensao_Temporal / tbDimensaoTemporal | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-07-F03 | DETALHE_OFICIAL | PF-07 | tipo_dimensao | Dimensao_Temporal / tbDimensaoTemporal | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-07-F04 | DETALHE_OFICIAL | PF-07 | precisao_temporal | Dimensao_Temporal / tbDimensaoTemporal | L-02,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-07 preservada; fora do subconjunto elegível |
| DET-PF-07-F05 | DETALHE_OFICIAL | PF-07 | valor_ano | Dimensao_Temporal / tbDimensaoTemporal | L-02,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-07 preservada; fora do subconjunto elegível |
| DET-PF-07-F06 | DETALHE_OFICIAL | PF-07 | valor_mes | Dimensao_Temporal / tbDimensaoTemporal | L-02,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-07 preservada; fora do subconjunto elegível |
| DET-PF-07-F07 | DETALHE_OFICIAL | PF-07 | valor_data | Dimensao_Temporal / tbDimensaoTemporal | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-07-F08 | DETALHE_OFICIAL | PF-07 | valor_instante | Dimensao_Temporal / tbDimensaoTemporal | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-07-F09 | DETALHE_OFICIAL | PF-07 | fuso_ou_deslocamento_informado | Dimensao_Temporal / tbDimensaoTemporal | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-07-F10 | DETALHE_OFICIAL | PF-07 | indicador_estimativa | Dimensao_Temporal / tbDimensaoTemporal | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-07-F11 | DETALHE_OFICIAL | PF-07 | fundamento_estimativa | Dimensao_Temporal / tbDimensaoTemporal | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-07-F12 | DETALHE_OFICIAL | PF-07 | ref_responsavel_ou_origem_estimativa | Dimensao_Temporal / tbDimensaoTemporal | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-07-F13 | DETALHE_OFICIAL | PF-07 | id_evento_registro | Dimensao_Temporal / tbDimensaoTemporal | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-07-F14 | DETALHE_OFICIAL | PF-07 | id_evento_confirmacao_ou_correcao | Dimensao_Temporal / tbDimensaoTemporal | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-08-F01 | DETALHE_OFICIAL | PF-08 | id_estado_preenchimento | Estado_Preenchimento / tbEstadoPreenchimento | L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-03 preservada; fora do subconjunto elegível |
| DET-PF-08-F02 | DETALHE_OFICIAL | PF-08 | id_objeto | Estado_Preenchimento / tbEstadoPreenchimento | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-08-F03 | DETALHE_OFICIAL | PF-08 | referencia_componente | Estado_Preenchimento / tbEstadoPreenchimento | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-08-F04 | DETALHE_OFICIAL | PF-08 | estado_qualidade | Estado_Preenchimento / tbEstadoPreenchimento | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-08-F05 | DETALHE_OFICIAL | PF-08 | motivo_pendencia | Estado_Preenchimento / tbEstadoPreenchimento | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-08-F06 | DETALHE_OFICIAL | PF-08 | ref_responsavel_pendencia | Estado_Preenchimento / tbEstadoPreenchimento | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| DET-PF-08-F07 | DETALHE_OFICIAL | PF-08 | data_pendencia | Estado_Preenchimento / tbEstadoPreenchimento | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-08-F08 | DETALHE_OFICIAL | PF-08 | fundamento_nao_aplicavel | Estado_Preenchimento / tbEstadoPreenchimento | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-08-F09 | DETALHE_OFICIAL | PF-08 | id_evento_registro | Estado_Preenchimento / tbEstadoPreenchimento | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-08-F10 | DETALHE_OFICIAL | PF-08 | id_evento_resolucao_ou_alteracao | Estado_Preenchimento / tbEstadoPreenchimento | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-09-F01 | DETALHE_OFICIAL | PF-09 | id_linhagem | Linhagem / tbLinhagem | L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-03 preservada; fora do subconjunto elegível |
| DET-PF-09-F02 | DETALHE_OFICIAL | PF-09 | tipo_no_origem | No_Linhagem / tbNoLinhagem + tbLinhagem | L-02,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-07 preservada; fora do subconjunto elegível |
| DET-PF-09-F03 | DETALHE_OFICIAL | PF-09 | id_no_origem | No_Linhagem / tbNoLinhagem + tbLinhagem | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-09-F04 | DETALHE_OFICIAL | PF-09 | tipo_no_destino | No_Linhagem / tbNoLinhagem + tbLinhagem | L-02,L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-07 preservada; fora do subconjunto elegível |
| DET-PF-09-F05 | DETALHE_OFICIAL | PF-09 | id_no_destino | No_Linhagem / tbNoLinhagem + tbLinhagem | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-09-F06 | DETALHE_OFICIAL | PF-09 | tipo_relacao_linhagem | Linhagem / tbLinhagem | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-09-F07 | DETALHE_OFICIAL | PF-09 | id_evento_registro | Linhagem / tbLinhagem | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-09-F08 | DETALHE_OFICIAL | PF-09 | id_fonte_evidencia | Linhagem / tbLinhagem | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-09-F09 | DETALHE_OFICIAL | PF-09 | qualidade_linhagem | Linhagem / tbLinhagem | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| DET-PF-09-F10 | DETALHE_OFICIAL | PF-09 | ponto_interrupcao | Linhagem / tbLinhagem | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-09-F11 | DETALHE_OFICIAL | PF-09 | justificativa_lacuna | Linhagem / tbLinhagem | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| DET-PF-09-F12 | DETALHE_OFICIAL | PF-09 | momento_registro | Linhagem / tbLinhagem | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| DET-PF-09-F13 | DETALHE_OFICIAL | PF-09 | ref_responsavel_registro | Linhagem / tbLinhagem | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| CMP-VR-01 | ASSOCIACAO | PF-02 | id_vinculo_referencia | tbVinculoReferencia | L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-03 preservada; fora do subconjunto elegível |
| CMP-VR-02 | ASSOCIACAO | PF-02 | id_objeto | tbVinculoReferencia | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| CMP-VR-03 | ASSOCIACAO | PF-02 | id_referencia_externa | tbVinculoReferencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-VR-04 | ASSOCIACAO | PF-02 | finalidade | tbVinculoReferencia | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| CMP-VR-05 | ASSOCIACAO | PF-02 | situacao_vinculo | tbVinculoReferencia | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| CMP-VR-06 | ASSOCIACAO | PF-02 | id_evento_origem | tbVinculoReferencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-REF-01 | ESPECIALIZACAO | PF-02 | url_fonte | tbReferenciaExterna | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-REF-02 | ESPECIALIZACAO | PF-02 | descricao_outro | tbReferenciaExterna | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-REF-03 | ESPECIALIZACAO | PF-02 | data_documento | tbReferenciaExterna | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| CMP-REF-04 | ESPECIALIZACAO | PF-02 | inicio_vigencia_fonte | tbReferenciaExterna | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| CMP-REF-05 | ESPECIALIZACAO | PF-02 | fim_vigencia_fonte | tbReferenciaExterna | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| CMP-EVD-01 | ESPECIALIZACAO | PF-03 | tipo_evidencia | tbFonteEvidencia | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| CMP-EVD-02 | ESPECIALIZACAO | PF-03 | id_referencia_externa | tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-EVD-03 | ESPECIALIZACAO | PF-03 | nome_arquivo | tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-EVD-04 | ESPECIALIZACAO | PF-03 | tamanho_bytes | tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-EVD-05 | ESPECIALIZACAO | PF-03 | tipo_midia | tbFonteEvidencia | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| CMP-EVD-06 | ESPECIALIZACAO | PF-03 | algoritmo_integridade | tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-EVD-07 | ESPECIALIZACAO | PF-03 | valor_integridade | tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-EVD-08 | ESPECIALIZACAO | PF-03 | origem_evidencia | tbFonteEvidencia | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-EVD-09 | ESPECIALIZACAO | PF-03 | situacao_evidencia | tbFonteEvidencia | L-02,L-06 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02,L-06 preservada; fora do subconjunto elegível |
| CMP-EVT-01 | ESPECIALIZACAO | PF-05 | autoridade_evento | tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-EVT-02 | ESPECIALIZACAO | PF-05 | origem_tecnica | tbEventoAuditoria | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-NO-01 | PROJECAO | PF-09 | id_no | tbNoLinhagem | L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-03 preservada; fora do subconjunto elegível |
| CMP-NO-02 | PROJECAO | PF-09 | tipo_alvo | tbNoLinhagem | L-01,L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-02 preservada; fora do subconjunto elegível |
| CMP-NO-03 | PROJECAO | PF-09 | id_alvo | tbNoLinhagem | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| CMP-NO-04 | PROJECAO | PF-09 | classe | tbNoLinhagem | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| CMP-NO-05 | PROJECAO | PF-09 | origem | tbNoLinhagem | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-NO-06 | PROJECAO | PF-09 | situacao | tbNoLinhagem | L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-02 preservada; fora do subconjunto elegível |
| CMP-LIN-01 | ESPECIALIZACAO | PF-09 | id_no_origem | tbLinhagem | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-LIN-02 | ESPECIALIZACAO | PF-09 | id_no_destino | tbLinhagem | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-ALT-01 | ESPECIALIZACAO | ALERTA | id_alerta | tbAlerta | L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-03 preservada; fora do subconjunto elegível |
| CMP-ALT-02 | ESPECIALIZACAO | ALERTA | tipo_alvo | tbAlerta | L-01,L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-02 preservada; fora do subconjunto elegível |
| CMP-ALT-03 | ESPECIALIZACAO | ALERTA | id_alvo | tbAlerta | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| CMP-ALT-04 | ESPECIALIZACAO | ALERTA | id_empresa | tbAlerta | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| CMP-ALT-05 | ESPECIALIZACAO | ALERTA | severidade | tbAlerta | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-ALT-06 | ESPECIALIZACAO | ALERTA | situacao | tbAlerta | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-ALT-07 | ESPECIALIZACAO | ALERTA | aberto_em | tbAlerta | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| CMP-ALT-08 | ESPECIALIZACAO | ALERTA | motivo | tbAlerta | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-ALT-09 | ESPECIALIZACAO | ALERTA | ref_regra | tbAlerta | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-ALT-10 | ESPECIALIZACAO | ALERTA | ciencia_em | tbAlerta | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| CMP-ALT-11 | ESPECIALIZACAO | ALERTA | providencia | tbAlerta | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-ALT-12 | ESPECIALIZACAO | ALERTA | justificativa | tbAlerta | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-ALT-13 | ESPECIALIZACAO | ALERTA | resolvido_em | tbAlerta | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| CMP-EA-01 | ASSOCIACAO | REL-03 | id_evento | tbEventoAlerta | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-EA-02 | ASSOCIACAO | REL-03 | id_alerta | tbEventoAlerta | NENHUMA | APLICAVEL | ELEGIVEL_DOCUMENTAL_EC02 | Planejamento documental somente; nenhuma ação física autorizada |
| CMP-VIG-01 | ESPECIALIZACAO | OBJETO_VERSIONAVEL | id_interno | objeto aplicável | L-01,L-03 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-03 preservada; fora do subconjunto elegível |
| CMP-VIG-02 | ESPECIALIZACAO | OBJETO_VERSIONAVEL | inicio_vigencia | objeto/PF-07 | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| CMP-VIG-03 | ESPECIALIZACAO | OBJETO_VERSIONAVEL | fim_vigencia | objeto/PF-07 | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| CMP-ID-01 | PROJECAO | IDENTIDADE | tipo_alvo | tbObjetoIdentidade | L-01,L-02 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01,L-02 preservada; fora do subconjunto elegível |
| CMP-ID-02 | PROJECAO | IDENTIDADE | id_alvo | tbObjetoIdentidade | L-01 | DIFERIDO | DIFERIDA_EC02 | Dependência L-01 preservada; fora do subconjunto elegível |
| CMP-FIN-01 | PROJECAO | FINANCEIRO | origem_conjunto_transversal | visão/referência no Financeiro | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |
| CMP-FIN-02 | PROJECAO | FINANCEIRO | versao_conjunto_transversal | visão/referência no Financeiro | L-07 | DIFERIDO | DIFERIDA_EC02 | Dependência L-07 preservada; fora do subconjunto elegível |

## 6. Fechamento por agrupamento

| Origem | Elegíveis documentais | Diferidas | Total |
|---|---:|---:|---:|
| PF-01 | 1 | 5 | 6 |
| PF-02 | 11 | 9 | 20 |
| PF-03 | 11 | 19 | 30 |
| PF-04 | 4 | 4 | 8 |
| PF-05 | 13 | 22 | 35 |
| PF-06 | 1 | 8 | 9 |
| PF-07 | 3 | 11 | 14 |
| PF-08 | 4 | 6 | 10 |
| PF-09 | 8 | 13 | 21 |
| ALERTA | 6 | 7 | 13 |
| REL-03 | 2 | 0 | 2 |
| OBJETO_VERSIONAVEL | 0 | 3 | 3 |
| IDENTIDADE | 0 | 2 | 2 |
| FINANCEIRO | 0 | 2 | 2 |
| **Total** | **64** | **111** | **175** |

As origens ALERTA, REL-03, OBJETO_VERSIONAVEL, IDENTIDADE e FINANCEIRO correspondem a complementos controlados e não são promovidas a detalhes oficiais.

## 7. Condições residuais de L-01 a L-07

As incidências abaixo podem se sobrepor na mesma linha; por isso, sua soma não representa quantidade de linhas distintas.

| Condição | Incidências nas 111 linhas diferidas | Tratamento documental vigente | Condição residual para EC-02 |
|---|---:|---|---|
| L-01 — alvos materiais | 31 | D8-L01-A — registro fechado por relação | alvo, tipo, contêiner e chave sem fonte nominal mantêm a linha fora do subconjunto |
| L-02 — vocabulários | 40 | D8-L02-A — compilação literal por campo, fonte e versão | domínio sem fonte e versão permanece inativo |
| L-03 — UUIDv7 e escrita | 13 | D8-L03-A — gerador local controlado e prova futura | seleção e demonstração material continuam futuras; nenhuma identidade é gerada em E9-01 |
| L-04 — calendário | 9 | D8-L04-A — calendário específico por fonte | rotina depende de fonte, frequência e autoridade concretas |
| L-05 — destino e recuperação | 2 | D8-L05-A — destino isolado e cópia independente | ambiente, capacidade, acesso e restauração ainda carecem de prova |
| L-06 — retenção | 8 | D8-L06-A — preservação integral durante EC-01 a EC-06 | política operacional definitiva permanece futura; descarte não autorizado |
| L-07 — autoridade temporal | 38 | D8-L07-A — histórico autoritativo e corrente derivada | fonte e regra nominal incompletas mantêm a linha diferida |

As decisões D8-L01-A a D8-L07-A são locais ao produto E8-03. Não constituem novos `DEC-*` ou `PEN-*`, não eliminam a condição residual e não transformam uma linha diferida em elegível por si sós.

## 8. Regras para o subconjunto elegível

As 64 linhas elegíveis:

1. podem ser referenciadas em E9-02 e E9-03 somente para delimitação documental do ambiente, dos objetos candidatos, das operações futuras e das evidências esperadas;
2. não podem ser instanciadas, copiadas, transformadas, carregadas ou testadas sob a autorização corrente;
3. não autorizam criação dos contêineres candidatos listados em E8-02;
4. não autorizam geração de chaves, UUID, dados, eventos, alertas ou projeções;
5. não autorizam acesso a fonte real ou uso de dado real;
6. permanecem sujeitas às dependências estruturais do contêiner e aos portões B e C;
7. deixam de integrar o subconjunto se surgir divergência de identidade, fonte, arquitetura ou recorte antes do portão técnico;
8. não autorizam EC-03, mesmo se E9-01 a E9-03 forem aceitos e publicados.

A elegibilidade de um atributo não prova que seu contêiner, chave ou relação possa ser construído. Quando a estrutura antecedente necessária estiver diferida ou não autorizada, a linha permanece somente como referência documental.

## 9. Critérios do Portão A

E9-01 propõe considerar documentalmente demonstrados:

- universo total de 175 linhas fechado;
- subconjunto de 64 linhas elegíveis nominalmente identificado;
- 111 linhas diferidas nominalmente preservadas;
- dependências incidentes registradas;
- ausência de criação de nova RN, RF, CA ou revisão arquitetural nesta produção;
- preservação do Recorte A e dos produtos E7/E8;
- critérios de parada explícitos.

O Portão A não se abre pela simples preparação desta minuta. Antes de iniciar UT-F05-09-02, deverão ocorrer cumulativamente:

1. aceite humano de E9-01;
2. autorização expressa de publicação;
3. publicação e conferência integral dos bytes;
4. aceite humano do resultado da publicação;
5. conclusão formal de UT-F05-09-01;
6. confirmação humana do atendimento do Portão A e autorização de início de UT-F05-09-02.

## 10. Critérios de parada

Interromper o objeto afetado e submetê-lo ao Gestor diante de:

- divergência entre a identidade física conferida e a ocorrência adotada;
- ausência de fonte obrigatória ou conflito material não reconciliado;
- diferença entre os 175 IDs desta matriz e o universo aceito de E8-02;
- tentativa de promover qualquer das 111 linhas diferidas por inferência;
- necessidade de inventar domínio, alvo, autoridade, frequência, identidade, caminho, executor, ambiente ou evidência;
- necessidade de nova RN, RF, CA, revisão arquitetural ou ampliação do Recorte A;
- tentativa de tratar `ELEGIVEL_DOCUMENTAL_EC02` como autorização construtiva;
- tentativa de iniciar UT-F05-09-02 sem os atos do Portão A;
- tentativa de iniciar UT-F05-09-04 sem Portão B e autorização construtiva específica;
- presença ou risco de ingresso de dado real;
- tentativa de preparar ambiente, copiar arquivo, criar estrutura, gerar identidade, escrever, testar, migrar, homologar, implantar ou promover operação.

A parada deverá preservar o trabalho independente válido e registrar objeto, fonte, conflito, impacto e decisão humana necessária.

## 11. Preservações vinculantes

Permanecem integralmente preservados:

- linha mestre `v0.24/v0.28/v0.23`;
- `ESC-F05-08` concluído exclusivamente no alcance documental;
- `EC-01` fechado documentalmente;
- `EC-02` não criado, não ativado e não autorizado;
- `UT-F05-09-04` não autorizada e não iniciada;
- 123 detalhes oficiais e 52 complementos controlados;
- 64/175 linhas elegíveis somente no sentido documental e 111/175 diferidas;
- 30 cenários não executados;
- matriz oficial `149/33`, os mesmos 33 detalhes em `TRT-04` e zero `TRT-05`;
- `C-F05-05` parcialmente atendida, `ALT-04`, `C-F05-09`, limitação `4H.5`, mapeamento global não encerrado e inventário de 67 itens;
- ocorrências físicas distintas de E2-03C e E-ESC-01, sem normalização retrospectiva;
- todas as ressalvas cumulativas de E6, E7 e E8;
- ausência de novo `DEC-*` ou `PEN-*`;
- Fase 05 aberta.

## 12. Resultado e próximo ato humano

**PROPOSTA DE RESULTADO DE UT-F05-09-01:** E9-01 é documentalmente suficiente para fechar o universo nominal de referência de EC-02 em 64 linhas elegíveis e 111 diferidas, sem autorizar qualquer ação física.

Este resultado somente poderá sustentar o Portão A após aceite, publicação, conferência, aceite do resultado da publicação, conclusão formal de UT-F05-09-01 e confirmação humana própria. UT-F05-09-02 permanece autorizada documentalmente, porém não iniciada.

O registro de criação, responsabilidade e ativação de ESC-F05-09 acompanha esta entrega como minuta separada. A aceitação ou a publicação de um arquivo não será presumida para o outro.

**Estado de saída:** ESC-F05-09 CRIADO E ATIVADO EXCLUSIVAMENTE NO ALCANCE DOCUMENTAL PREPARATÓRIO; UT-F05-09-01 INICIADA; E9-01 v0.1 EM MINUTA PARA REVISÃO; UT-F05-09-02 E UT-F05-09-03 AUTORIZADAS DOCUMENTALMENTE E NÃO INICIADAS; UT-F05-09-04 NÃO AUTORIZADA E NÃO INICIADA; UT-F05-09-05 NÃO INICIADA; EC-02 NÃO CRIADO, NÃO ATIVADO E NÃO AUTORIZADO; 64/175 LINHAS ELEGÍVEIS SOMENTE DOCUMENTALMENTE; 111/175 LINHAS DIFERIDAS; 0/30 CENÁRIOS EXECUTADOS; FASE 05 ABERTA; SEM IMPLEMENTAÇÃO, TESTES, MIGRAÇÃO OU IMPLANTAÇÃO.

O tamanho e o SHA-256 desta ocorrência serão apresentados no recibo de entrega, calculados após a gravação final. Não se insere hash autorreferente no conteúdo.

