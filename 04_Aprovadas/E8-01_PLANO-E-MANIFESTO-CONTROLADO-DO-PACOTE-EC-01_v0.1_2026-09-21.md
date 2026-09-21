# E8-01 — PLANO E MANIFESTO CONTROLADO DO PACOTE EC-01

## MINUTA v0.1 — PARA REVISÃO — EXCLUSIVAMENTE DOCUMENTAL

| Campo | Valor |
|---|---|
| Projeto | Dev_Ecossistema_Integrado_Gestao_Empresarial |
| Escopo / unidade | ESC-F05-08 / UT-F05-08-01 |
| Data documental | 21/09/2026 |
| Responsável humano pelo aceite | Eduardo Andrade Ramos |
| Objeto | Manifesto de entradas, universo controlado e modelo de configuração de EC-01 |
| Estado | UT-F05-08-01 iniciada; E8-01 em minuta; aceite, publicação e conclusão pendentes |
| Linha mestre vigente | REG-CONSOLIDACAO-CHATS v0.23 / REG-DECISOES v0.27 / REG-PENDENCIAS v0.22 |

## 1. Autoridade, objetivo e resultado desta produção

O humano aceitou a definição de `ESC-F05-08`, seu identificador, nome, responsabilidade, unidades e produtos, e autorizou sua publicação, criação, ativação e execução exclusivamente documental. A definição foi publicada e conferida no commit `f649a513b4d66b1f11e3602164f4f691ec34541b`. O registro próprio formaliza o escopo como criado e ativado e inicia `UT-F05-08-01`.

Este produto fixa as entradas de `EC-01`, delimita o universo que E8-02 deverá tratar, estabelece o modelo obrigatório de configuração nominal e define controles de completude, rastreabilidade e parada. Ele não preenche antecipadamente a matriz nominal, não decide `L-01` a `L-07` e não cria estruturas executáveis.

**RESULTADO PROPOSTO.** Considerar o conjunto de entradas identificado nas seções 2 e 3 suficiente para iniciar a correspondência nominal de E8-02, condicionado ao aceite e à publicação deste produto e à conclusão formal de `UT-F05-08-01`. A suficiência é documental e limitada ao manifesto; não equivale à prontidão para `EC-02`.

## 2. Manifesto principal das entradas

### 2.1 Linha mestre vigente

| Caminho publicado em 08_Consolidados/ | Bytes | SHA-256 | Papel em EC-01 |
|---|---:|---|---|
| REG-CONSOLIDACAO-CHATS_v0.23_2026-09-21.md | 198070 | e825d493aa391dbce6e62592256481d135dc6be29fb353af3b2ce8995a71c32d | Estado corrente, sequência e limites |
| REG-DECISOES_v0.27_2026-09-21.md | 256539 | 5e70128119087ef6ddd741a8a62b2f397e66521e496fcc173a65ac455e04fb3c | Decisões vigentes e ausência de nova numeração inferida |
| REG-PENDENCIAS_v0.22_2026-09-21.md | 191206 | 87a2da5bf480d11abccac32f0a2ad7a283c2c500c79aa373f4b1a0cab2c915b4 | Pendências oficiais e distinção das lacunas locais |

Publicação sincronizada: commit `da2ee6d43b23141e49fcb9a2d6bc6e99b861969f`. A conferência publicada registrou igualdade integral dos três arquivos com os bytes aceitos.

### 2.2 Produtos de ESC-F05-07

| Produto publicado em 04_Aprovadas/ | Bytes | SHA-256 | Git blob conferido | Função no pacote |
|---|---:|---|---|---|
| E7-01 v0.3 | 23594 | 2f17665af2a01fbf5ffcca75c05b9d8141f29661794ed0a6ea79ef3c92f7fae0 | 7a5a480c665acbfd5b92db41cad3b68213a6bb71 | Recorte A, três RF, 14 CA, inclusões, exclusões e fontes |
| E7-02 v0.2 | 44318 | a36c658342d534640c0b51414d0ab1289a8547abb82b51a9d87ce7668fd3b570 | be80864dea495be42e23192364eb2550327fc344 | Nove PF, 123 detalhes, 13 tabelas candidatas, DF-01-A a DF-04-A |
| E7-03 v0.2 | 30324 | 4a9fec4d2d3b081455d32aa2a37fbed31804c73f712613bba9730d6fdaa46c41 | a924226d0cb7425e39b792d76dfc7e4d018d2c13 | PC-01-A a PC-04-A, CT-01 a CT-11, L-01 a L-07 |
| E7-04 v0.1 | 23532 | b0ab3bc49392eda71f3d900e702a2923bd65a93ba481aac1bf80d613f84c871f | e1e15179a1c99211369f54939a977f74a5e70c5b | EC-01 a EC-06 e 30 cenários não executados |
| E7-05 v0.2 | 19354 | 8fd91e871a0abfae0c554396ad87f66036085f8896d718e12e4fa87d264b44ab | 7cd60aa6fd88faf61dc48385e216e81d6b82da0a | Conferência, Alternativa A e encaminhamento de EC-01 |

As versões publicadas foram conferidas no fluxo de ESC-F05-07. Os textos internos de minuta registram seus respectivos momentos de preparação e são qualificados pelos atos posteriores de aceite, publicação e conclusão.

### 2.3 Governança específica de ESC-F05-08

| Documento | Bytes | SHA-256 / Git blob | Estado |
|---|---:|---|---|
| PROPOSTA-DEFINICAO-FORMAL-DO-PROXIMO-ESCOPO-DA-FASE-05-POS-ESC-F05-07 v0.1 | 18403 | SHA-256 f28dc20f6edab207839757aea2b920dccf99e7573429b18fa49e7b15337278cb; blob 9340b3a4cb45d47201ed124b9344091660563dae | aceita, publicada e conferida |
| REG-CRIACAO-RESPONSABILIDADE-E-ATIVACAO-ESC-F05-08 v0.1 | identidade externa apresentada com esta entrega | calculada após gravação final | registro de criação/ativação; não tratado como fonte de mérito |

### 2.4 Fontes funcionais e arquiteturais transportadas

E8-02 utilizará as ocorrências já qualificadas por E7-01/E7-02, com precedência dos produtos aceitos posteriores onde houver refinamento:

1. `E-ESC-01_ESPECIFICACAO-TRANSVERSAL v0.2`, na ocorrência publicada adotada;
2. `E-ESC-02_MATRIZ-RASTREABILIDADE v0.2`;
3. `E2-03A`, `E2-03B` e a ocorrência publicada de `E2-03C`, com a cópia local distinta preservada;
4. `E5-03_CATALOGO-E-MAPA-LOGICO-FISICO-CONSOLIDADOS-EM-MINUTA v0.1`;
5. CAT-REGRAS-NEGOCIO v0.3;
6. CAT-REQUISITOS-FUNCIONAIS v0.1 REV03 e qualificações posteriores aceitas;
7. MATRIZ-RASTREABILIDADE-RN-RF v0.1 REV03;
8. MATRIZ-RASTREABILIDADE-RF-CA-ARQUITETURA v0.1;
9. CATALOGO-DECISOES-ARQUITETURAIS v0.1;
10. MODELO-CONCEITUAL-E-LOGICO-DE-DADOS v0.1;
11. MAPA-COMPONENTES-INTEGRACOES-E-FLUXOS v0.1;
12. decisões funcionais e arquiteturais posteriores já incorporadas em E5/E7.

E8-02 deverá registrar a fonte efetivamente incidente em cada linha. Uma fonte listada no manifesto não se aplica automaticamente a todos os detalhes. Caso seja necessária fonte não identificada ou versão não conferida, interromper o item e atualizar o manifesto por versão sucessora ou complemento aceito.

## 3. Universo controlado para E8-02

### 3.1 Núcleo dos 123 detalhes

O dicionário de E7-02 §6 contém 123 identificadores distintos e foi conferido contra E2-03A/E2-03B. A distribuição por objeto é:

| Objeto | Intervalo lógico | Quantidade | Obrigatórios de origem | Condicionais de origem |
|---|---|---:|---:|---:|
| PF-01 — Objeto e identidade | DET-PF-01-F01 a F06 | 6 | 2 | 4 |
| PF-02 — Referência externa | DET-PF-02-F01 a F09 | 9 | 5 | 4 |
| PF-03 — Fonte e evidência | DET-PF-03-F01 a F21 | 21 | 9 | 12 |
| PF-04 — Vínculo de evidência | DET-PF-04-F01 a F08 | 8 | 7 | 1 |
| PF-05 — Evento de auditoria | DET-PF-05-F01 a F33 | 33 | 8 | 25 |
| PF-06 — Vínculo empresarial | DET-PF-06-F01 a F09 | 9 | 5 | 4 |
| PF-07 — Dimensão temporal | DET-PF-07-F01 a F14 | 14 | 5 | 9 |
| PF-08 — Estado de preenchimento | DET-PF-08-F01 a F10 | 10 | 5 | 5 |
| PF-09 — Linhagem | DET-PF-09-F01 a F13 | 13 | 10 | 3 |
| **Total** |  | **123** | **56** | **67** |

Os totais 56/67 foram conferidos sobre a coluna de condição de origem do dicionário de E7-02. E8-02 deverá reproduzir o valor individual `O` ou `C`; a tabela acima não substitui a conferência linha a linha.

### 3.2 Treze contêineres candidatos

| Origem / complemento | Arquivo proposto | Aba / tabela candidata | Classe de realização |
|---|---|---|---|
| PF-01 | Operacional | Objeto_Identidade / tbObjetoIdentidade | realização direta |
| PF-02 | Operacional | Referencia_Externa / tbReferenciaExterna | realização direta, com vínculo separado |
| PF-03 | Operacional | Fonte_Evidencia / tbFonteEvidencia | realização direta |
| PF-04 | Operacional | Vinculo_Evidencia / tbVinculoEvidencia | associação |
| PF-05 | Operacional | Evento_Auditoria / tbEventoAuditoria | realização direta com visões derivadas |
| PF-06 | Operacional | Vinculo_Empresarial / tbVinculoEmpresarial | associação |
| PF-07 | Operacional | Dimensao_Temporal / tbDimensaoTemporal | realização direta |
| PF-08 | Operacional | Estado_Preenchimento / tbEstadoPreenchimento | realização direta |
| PF-09 | Operacional | Linhagem / tbLinhagem | associação de linhagem |
| Projeção de nós | Operacional | No_Linhagem / tbNoLinhagem | projeção referencial |
| CAT-02 de E5-03 | Operacional | Vinculo_Referencia / tbVinculoReferencia | associação |
| ALERTA vigente | Operacional | Alerta / tbAlerta | realização do objeto existente |
| REL-03 de E5-03 | Operacional | Evento_Alerta / tbEventoAlerta | associação muitos-para-muitos |

O arquivo Financeiro referencia origem e versão do núcleo. Não recebe segunda ocorrência editável das tabelas transversais. O cadastro mestre permanece em Projetos conforme a arquitetura adotada; nenhum cadastro empresarial alternativo é criado pelo pacote.

### 3.3 Complementos obrigatórios posteriores

Além dos 123 IDs, E8-02 deverá incluir linhas ou vínculos de complemento, sem inventar novos detalhes oficiais:

- vínculo objeto–referência e atributos adicionais da referência externa;
- identidade, classificação, integridade e equivalência de fonte/evidência;
- autoridade e origem técnica de eventos, além da correlação e correção por evento posterior;
- projeção de nós e elos de linhagem;
- objeto ALERTA e associação evento–alerta;
- atributos de vigência para objetos versionáveis;
- registro de identidades tipadas e correspondência com o contêiner material;
- projeções de leitura no Financeiro com origem/versão e sem autoridade concorrente.

Cada complemento deve apontar sua fonte, seu relacionamento com os 123 detalhes e sua natureza: especialização, associação, projeção ou atributo adicional. A ausência de um novo ID oficial não autoriza omissão.

## 4. Modelo obrigatório da matriz nominal

E8-02 deverá usar uma linha controlada por detalhe ou complemento, com as seguintes colunas mínimas:

| Coluna | Conteúdo e regra |
|---|---|
| ID_CONTROLE | ID do detalhe oficial ou ID local estável do complemento, sem promover classificação oficial |
| NATUREZA | DETALHE_OFICIAL, ESPECIALIZACAO, ASSOCIACAO ou PROJECAO |
| PF_ORIGEM | PF-01 a PF-09 ou referência complementar |
| CAMPO_ORIGEM | Nome aceito no dicionário ou atributo complementar |
| CONDICAO_ORIGEM | O, C ou N/A com justificativa |
| REALIZACAO | DIRETA, ASSOCIACAO ou PROJECAO_DERIVADA |
| ARQUIVO | Operacional, Financeiro somente como referência/visão, ou INATIVO |
| ABA_TABELA | Nome candidato aceito ou PENDENTE_L01 |
| CAMPO_FISICO | Nome candidato aceito ou PENDENTE, sem criação efetiva |
| CHAVE | Chave própria, composta ou referência; fonte da decisão |
| TIPO | Tipo técnico proposto conforme PC-01/PC-02 |
| LIMITE_PRECISAO | Limite, escala, precisão temporal ou N/A justificado |
| DOMINIO | Vocabulário literal e versão, ou INATIVO_L02 |
| ALVO_PERMITIDO | Tipo, contêiner e chave do alvo, ou PENDENTE_L01 |
| ORIGEM_AUTORITATIVA | Fonte editável única ou fonte externa declarada |
| TRANSFORMACAO | Regra de projeção/derivação; vazio somente para realização direta sem transformação |
| AUTORIDADE_TEMPORAL | Regra corrente/histórica ou PENDENTE_L07 |
| CONTROLE_CT | CT-01 a CT-11 aplicável, podendo haver mais de um |
| CENARIO_E7_04 | T01 a T30 planejado, N/A justificado ou CASO_ADICIONAL_NECESSARIO |
| RF_CA | RF e CA incidentes ou N/A justificado |
| FONTE_VERSAO | Documento, seção e versão que sustentam a linha |
| LACUNA | L-01 a L-07 incidente ou NENHUMA |
| ESTADO | DECIDIDO, APLICAVEL, INATIVO, DIFERIDO ou INTERROMPIDO |
| MOTIVO_MARCO | Justificativa e momento máximo para resolução |

Valores `PENDENTE_*`, `INATIVO_*` e `DIFERIDO` são estados documentais explícitos. Não constituem preenchimento válido quando a dependência for necessária ao avanço. Campos vazios sem justificativa não contam como cobertura.

## 5. Regras de formação da matriz

1. Reproduzir os 123 IDs exatamente como E7-02 §6.
2. Preservar nome, PF e condição de origem antes de acrescentar a correspondência nominal.
3. Não transformar campo lógico em coluna física automaticamente; justificar associação e projeção.
4. Não criar tabela material para projeção que possa permanecer consulta derivada, salvo decisão posterior expressa.
5. Preservar uma única fonte autoritativa do núcleo no Operacional; Financeiro somente referencia origem/versão.
6. Validar referências por tipo, ID e ocorrência no contêiner específico; UUID existente em tipo errado permanece inválido.
7. Manter datas e instantes em texto canônico com precisão e fuso explícitos, conforme DF-03-A/PC-01-A.
8. Manter valores anterior/posterior em JSON tipado compatível com E7-VAL-1; conteúdo não vira fórmula.
9. Tratar eventos como apensos; reversos e estado corrente são derivados sem editar o original.
10. Preservar alerta como não bloqueante, exceto integridade estrutural local do próprio objeto.
11. Não inventar domínio, chave, contêiner, responsável, periodicidade, retenção ou destino de backup.
12. Registrar conflito e interromper somente o item dependente, preservando linhas independentes válidas.

## 6. Cobertura de decisões e controles

E8-02 deverá evidenciar, por linha aplicável:

| Âncora | Aplicação obrigatória |
|---|---|
| Recorte A | Restringir a identidade, evidência, histórico, empresa, tempo, qualidade, linhagem e alertas existentes |
| DF-01-A | Núcleo autoritativo no Operacional; referência controlada no Financeiro |
| DF-02-A | Identidade tipada e alvo real no contêiner específico |
| DF-03-A | Texto canônico temporal e JSON tipado |
| DF-04-A | Eventos apensos, corrente derivada e manifestos de versão |
| PC-01-A | Limites, excedentes, comparação literal, Unicode e E7-VAL-1 |
| PC-02-A | Lista técnica restrita e diferimentos L-01/L-02/L-03/L-07 |
| PC-03-A | Gatilhos por entrada, alteração, uso e liberação; calendário somente após L-04 |
| PC-04-A | Preservação sem descarte automático; cópias e restauração dependentes de L-05/L-06 |
| CT-01 a CT-11 | Controle aplicável e evidência futura esperada, sem declarar execução |

Uma linha poderá depender de mais de uma âncora. A matriz deve permitir percurso detalhe → realização → decisão → controle → fonte e o inverso fonte/controle → detalhes afetados.

## 7. Tratamento das lacunas em E8-02 e E8-03

| Lacuna | Registro exigido em E8-02 | Encaminhamento a E8-03 |
|---|---|---|
| L-01 | alvo, empresa, responsável, tipo, contêiner e chave pendentes por relação | alternativas nominais e recomendação por classe de alvo |
| L-02 | domínio pendente por campo e fonte esperada | vocabulários por fonte/versão e decisão de aplicabilidade |
| L-03 | campos que dependem de geração/escrita UUIDv7 | alternativas de mecanismo e método futuro de prova |
| L-04 | fontes que requerem calendário | alternativas de frequência e autoridade de decisão |
| L-05 | controles que dependem de destino/acesso/capacidade/recuperação | requisitos, opções e impacto; prova futura separada |
| L-06 | registros sujeitos a retenção/descarte | classes e marcos; preservação enquanto não decidido |
| L-07 | campos/visões com autoridade temporal ou reconstrução | regra nominal por objeto/atributo e impedimento de fontes concorrentes |

E8-03 receberá alternativas e recomendações somente após E8-02 identificar a incidência nominal. Nenhuma decisão genérica deverá apagar diferenças entre objetos ou campos.

## 8. Controles de completude

E8-02 será documentalmente completa somente se satisfizer simultaneamente:

1. 123/123 IDs oficiais presentes e únicos;
2. totais por PF iguais a 6, 9, 21, 8, 33, 9, 14, 10 e 13;
3. 56 `O` e 67 `C` preservados nas linhas oficiais;
4. todos os complementos da seção 3.3 identificados;
5. todos os 13 contêineres candidatos cobertos ou explicitamente inativos/diferidos;
6. nenhuma linha sem fonte e versão;
7. nenhuma associação sem alvo/pendência nominal;
8. nenhuma projeção sem origem autoritativa e transformação;
9. nenhuma lacuna incidente omitida;
10. percursos diretos e inversos possíveis;
11. nenhuma alteração da matriz oficial `149/33` ou promoção `TRT-05`;
12. nenhum resultado de teste ou implementação declarado.

Contagem correta com conteúdo material incompleto não satisfaz o critério. Divergência de universo, duplicidade de ID ou fonte obrigatória ausente interrompe a parcela afetada e deve ser registrada.

## 9. Critérios de parada

Interromper o objeto afetado diante de:

- divergência física entre ocorrência prevista e publicada;
- detalhe ausente, duplicado ou renomeado sem autoridade;
- conflito entre E7-02 e fonte vigente que não possa ser resolvido por precedência já aceita;
- necessidade de nova RN, RF, CA ou decisão arquitetural;
- necessidade de ampliar o Recorte A;
- tipo, domínio, alvo ou autoridade temporal sem alternativa documental admissível;
- tentativa de preencher lacuna por inferência de planilha legada;
- tentativa de construir ou testar durante a correspondência documental.

A parada deve indicar ID, fonte, conflito, efeito e decisão necessária. Ela não invalida automaticamente outros detalhes independentes.

## 10. Preservações vinculantes

Permanecem a matriz `149/33`, os mesmos 33 detalhes em `TRT-04`, zero `TRT-05`, `C-F05-05` parcialmente atendida, `ALT-04`, `C-F05-09`, mapeamento global não encerrado, inventário de 67 itens, 4H.5 não comprovado e todas as ressalvas de E6/E7.

Os portões PT-DOC-01, PT-ESC-01, PT-FUN-01 e PT-ARQ-01 conservam atendimento no alcance documental com ressalvas; PT-AMB-01 conserva atendimento com ressalvas operacionais não impeditivas. PT-DAD-01, PT-SEG-01, PT-BCP-01, PT-TEC-01, PT-HOM-01 e PT-OPE-01 não recebem novo estado.

As ocorrências publicadas de E2-03C e E-ESC-01 permanecem as selecionadas; cópias distintas são preservadas. Não se normalizam bytes. Gestor permanece autoridade humana sistêmica; COO/LDE são contextuais e opcionais. Ausência de contador, advogado ou parecer não gera alerta ou bloqueio automático.

## 11. Resultado e próxima decisão

**PROPOSTA DE RESULTADO DE UT-F05-08-01:** manifesto e modelo considerados documentalmente suficientes para preparar E8-02, sem resolver antecipadamente as lacunas ou afirmar prontidão construtiva.

Se E8-01 for aceito e publicado, a conclusão de `UT-F05-08-01` dependerá de ato humano próprio. `UT-F05-08-02` já está autorizada no plano geral, mas só será iniciada após a conclusão formal da unidade antecedente.

Não há necessidade de nova escolha material nesta versão. A decisão humana corrente é aceitar, solicitar ajuste ou rejeitar E8-01 v0.1 e, em caso de aceite, autorizar sua publicação. O registro de criação/ativação acompanha esta entrega como evidência de governança e não substitui o produto.

**Estado de saída:** ESC-F05-08 criado e ativado; UT-F05-08-01 iniciada; E8-01 v0.1 em minuta para revisão; UT-F05-08-02 a UT-F05-08-05 autorizadas e não iniciadas por dependência; L-01 a L-07 abertas; 30 cenários não executados; Fase 05 aberta; sem implementação.
