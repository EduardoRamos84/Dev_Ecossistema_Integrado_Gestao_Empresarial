# REGISTRO CONSOLIDADO DA FASE 04 — ARQUITETURA DA SOLUÇÃO

**REG-FASE-04_ARQUITETURA-DA-SOLUCAO v0.1 | 07/09/2026**

**Projeto:** `Dev_Ecossistema_Integrado_Gestao_Empresarial`  
**Fase:** Fase 04 — Arquitetura da Solução  
**Linhagem:** `04 → 04B → 04_CONT`  
**Chat de conclusão substantiva:** `04_CONT_Arquitetura da Solução — Continuidade Controlada`  
**Situação do conteúdo:** ENCERRADO E APROVADO  
**Situação deste arquivo:** PRODUZIDO — AGUARDANDO ACEITE DOCUMENTAL  
**Situação da consolidação mestre pós-Fase 04:** MINUTAS PRODUZIDAS — PUBLICAÇÃO NÃO AUTORIZADA  
**Implementação, migração, piloto e produção:** NÃO AUTORIZADOS

## 1. FINALIDADE

Consolidar a arquitetura lógica, estrutural, física conceitual e operacional aprovada na Fase 04, preservando:

- decisões e aceites expressos;
- revisões funcionais e arquiteturais vigentes;
- versões históricas, propostas não aprovadas e erros de continuidade;
- limites entre arquitetura, especificação física e implementação;
- pendências, riscos, dependências e limitações transferidos;
- rastreabilidade com os requisitos funcionais e critérios de aceite da Fase 03;
- segregação entre ACPREV e CONGESPU;
- continuidade documental da linhagem `04 → 04B → 04_CONT`.

Este registro consolida o estado arquitetural vigente. Não substitui as transcrições como prova cronológica, não altera requisitos funcionais e não autoriza execução técnica.

## 2. ESTADO FORMAL DA FASE

- **Bloco final:** `4N — Conferência dos Entregáveis e Encerramento da Fase 04`.
- **Estado do Bloco 4N:** concluído integralmente.
- **Última unidade substantiva:** `4N.9 — Integridade, histórico e encerramento controlado da Fase 04`, aprovada expressamente.
- **Gate final:** `GATE-4N-08 — ATENDIDO`.
- **Checkpoint vigente:** `CHK-ARQ04-002`.
- **Checkpoint histórico:** `CHK-ARQ04-001`.
- **Checkpoint proibido:** `CHK-ARQ04-003` não deve ser criado.
- **Situação da Fase 04:** `CONTEÚDO ARQUITETURAL ENCERRADO E APROVADO — CONSOLIDAÇÃO DOCUMENTAL PENDENTE — TRANSIÇÃO EXTERNA CONDICIONADA — IMPLEMENTAÇÃO NÃO AUTORIZADA`.
- **Situação do 04_CONT:** conteúdo substantivo concluído; mantido disponível apenas para fluxo documental e eventuais registros de retorno.

O encerramento arquitetural não equivale ao encerramento documental completo nem abre automaticamente a fase seguinte.

## 3. FONTES E PRECEDÊNCIA

### 3.1. Linha de base funcional e de governança

1. `INSTR-PROJ v3.1.1 | 10/08/2026`.
2. `REG-CONSOLIDACAO-CHATS v0.9 | corte de 27/08/2026`, publicado em 07/09/2026.
3. `REG-DECISOES v0.13 | corte de 27/08/2026`, publicado em 07/09/2026.
4. `REG-PENDENCIAS v0.8 | corte de 27/08/2026`, publicado em 07/09/2026.
5. `CAT-REGRAS-NEGOCIO v0.3`.
6. `GLOSSARIO-FUNCIONAL v0.3`.
7. `MATRIZ-GENERALIZACAO v0.5`.
8. `REG-FASE-03_REQUISITOS-FUNCIONAIS v0.1 REV03`.
9. `CAT-REQUISITOS-FUNCIONAIS v0.1 REV03`.
10. `MATRIZ-RASTREABILIDADE-RN-RF v0.1 REV03`.

### 3.2. Fontes da linhagem arquitetural

1. `TRANSCRICAO_CHAT_04_Arquitetura_v1.0_2026-08-25.md` — 578.441 bytes — SHA-256 `b6e3ef7bcf04046609b8acc71b45de730feb2407033806072d3023a8398c6609`.
2. `TRANSCRICAO_CHAT_04B_Arquitetura_v1.0_2026-08-25.md` — 565.778 bytes — SHA-256 `18e6febc8621dad2daf2de567aaa75fe39fcbadaa8fd5c5666afcd180ebc018c`.
3. `REG-CHECKPOINT-CONTINUIDADE-CHAT-04 v0.3 | 25/08/2026` — checkpoint operacional de transição com ressalvas — 160.719 bytes — SHA-256 `17f9bcfe207a215680a7ff8d66edb26dec6681a188404ca044b262bd831c6258`.
4. `TRANSCRICAO_CHAT_04_CONT_Arquitetura v4.1 | 07/09/2026` — transcrição integral validada e vigente — 2.449.666 bytes — SHA-256 `f5a3559354b08136bd404781412bef68922703d3e8ea6b5b4a35997f995a61e6` — 356 mensagens visíveis e 12 arquivos associados.
5. fontes arquiteturais integrais ou revisões específicas citadas na transcrição, inclusive `ARQ04-4G.3-R04`, `ARQ04-4G.4-R01` e `ARQ04-4H-R01`.
6. `REV-FUNC-001` a `REV-FUNC-006`, todas aprovadas e materialmente incorporadas.

### 3.3. Regra de precedência

Em caso de divergência, aplica-se:

1. manifestação expressa posterior do usuário;
2. revisão arquitetural formal mais recente e aprovada da mesma unidade;
3. revisão funcional aprovada dentro de seu alcance material;
4. incorporação expressa da revisão em unidade arquitetural posterior;
5. conteúdo aprovado anterior naquilo que não foi alterado;
6. registros mestres para identificação e estado institucional;
7. transcrições e checkpoints como evidência documental, sem poder para criar decisão nova.

Ausência ou conflito de fonte deve permanecer identificado; conteúdo não pode ser completado por inferência.

## 4. ESCOPO E LIMITES

### 4.1. Escopo cumprido

A Fase 04 definiu:

- princípios e macroarquitetura;
- decomposição por domínios;
- arquitetura de arquivos e responsabilidades;
- modelo conceitual e lógico de dados;
- identidades, relacionamentos, cardinalidades, granularidades e temporalidade;
- fluxos negociais, operacionais e financeiros;
- integração controlada entre os arquivos e entre as empresas;
- segurança, integridade, backup, restauração, continuidade e auditoria;
- alternativas tecnológicas, sem contratação ou implantação;
- catálogo de decisões, histórico, riscos, pendências e plano de transição;
- conferência final e critérios de encerramento arquitetural.

### 4.2. Fora do escopo preservado

Não foram autorizados:

- construção ou alteração de planilhas de produção;
- definição de nomes físicos definitivos sem validação própria;
- implementação de fórmulas, Power Query, Office Scripts, VBA, Power Automate, n8n, APIs ou aplicação própria;
- contratação de infraestrutura ou licenças;
- migração ou saneamento de dados reais;
- testes funcionais, integrados, de segurança, desempenho, recuperação ou aceitação;
- implantação, piloto ou entrada em produção;
- criação, alteração ou complementação de regra funcional por inferência.

## 5. EVOLUÇÃO DA MACROARQUITETURA

### 5.1. Bloco 1 — princípios apresentados

`PA-04-001` a `PA-04-010` permanecem classificadas como `PROPOSTA APRESENTADA — APROVAÇÃO EXPRESSA NÃO LOCALIZADA`.

O encerramento da fase não ratifica essas propostas isoladamente. Princípios posteriormente aprovados em unidades substantivas próprias permanecem vigentes por essas decisões posteriores, e não por aprovação retroativa do Bloco 1.

### 5.2. Bloco 2 — alternativa selecionada

Foi escolhida expressamente `ALT-04-B2`, com separação entre gestão operacional e gestão financeira e integração controlada entre as camadas. As demais alternativas permanecem históricas.

### 5.3. Bloco 3 — decomposição aprovada e refinamento físico

O Bloco 3 foi aprovado. A topologia histórica inicialmente descrita com três arquivos foi refinada prospectivamente para dois arquivos principais:

1. **Arquivo Operacional**, que incorpora o Cadastro Mestre;
2. **Arquivo Financeiro**, que contém o Livro Financeiro único para ACPREV e CONGESPU, com segregação lógica rígida.

Não existe terceiro arquivo vigente independente para o Cadastro Mestre.

## 6. INVENTÁRIO DOS BLOCOS ARQUITETURAIS

### 6.1. Blocos de domínio

- **4A — Cadastros, papéis, caso negocial, Projeto e relações empresariais:** organizações, pessoas, designações, autoridade, continuidade do fluxo, histórico, formação do Projeto, Empresa Faturadora, Contratante, Contratada, identificadores e integridade.
- **4B — Levantamentos, relatórios e estudos:** ciclo de levantamento, proveniência, classificação RPPS/RGPS, grupos mínimos, revisão, relatório técnico, estudo, entrega e regra temporal de reaproveitamento.
- **4C — Orçamentos, rodadas, cenários e consolidação:** identidades, valor mensal médio, Orçamento-Base, Orçamento Definido, Consolidado da Equipe, composição econômica, precisão, arredondamento, seleção, congelamento e histórico.
- **4D — Serviços, Itens de Entrega e homem-hora:** catálogo e seleção de serviços, itens, pesos, valoração, perfis, composição teórica, horas finais, ajuste controlado e fechamento sem dupla contagem.
- **4E — Propostas, contratação, Projeto e parcelas:** identidade e versionamento da Proposta, aceite, contratação, constituição e ciclo do Projeto, planejamento de parcelas, integração com o Livro Financeiro e alterações contratuais.
- **4F — Faturamento, Notas Fiscais, recebimentos e registros tributários:** fatos separados, vínculos NF–Parcela e Recebimento–NF, Simples por empresa e competência, estados, baixas, diferenças, cancelamentos, substituições, estornos, conferências e oito saídas lógicas.
- **4G — Distribuições, remunerações, despesas, provisões, saldos e reservas:** camadas de valor, distribuição planejada e vigente, pagamentos, Destinação Vinculada ao Projeto, Despesa, Alocação Gerencial da Despesa, alertas e histórico.
- **4H — Fluxos de caixa e relatórios financeiros:** contas, movimentações, conciliação bancária, saldos bancário, reservado, vinculado e livre, intercompany inicial, relatórios por empresa, projeto, conta e período.

### 6.2. Blocos transversais e físicos

- **4I — Arquitetura física e governança dos arquivos:** topologia de dois arquivos, Cadastro Mestre interno ao Arquivo Operacional, Livro Financeiro único, camadas internas, chaves, versões, fonte oficial, publicação, concorrência, arquivamento e retenção.
- **4J — Segurança, integridade e continuidade operacional:** identidades e perfis, proteção de arquivos e credenciais, validações, evidências, auditoria, backup, restauração, incidentes, contingência, operação degradada, monitoramento e testes futuros.
- **4K — Integrações, publicações e evolução tecnológica:** contratos de dados, fontes e destinos, circulação entre arquivos, importação, exportação, reprocessamento, lotes, manifestos, confirmação, falhas, alternativas tecnológicas, capacidade e escalabilidade.
- **4L — Modelo consolidado de dados e fluxos:** catálogo de domínios e objetos, identidades, granularidades, temporalidade, transições, reconciliações, dupla contagem, linhagem, evidências e visões consolidadas.
- **4M — Decisões, riscos, pendências e plano de transição:** decisões vigentes, histórico, riscos, pendências, criticidade, prioridades, portões, entregáveis e sequência de transição.
- **4N — Conferência e encerramento:** inventário, cobertura, precedência, pendências, coerência, prontidão, produtos documentais, checklist e encerramento controlado.

Todos os blocos `4A–4N` foram concluídos. A conferência final registrou oito blocos sem ressalva e cinco com ressalva controlada (`4A`, `4C`, `4D`, `4E` e `4G`), sem inconsistência material impeditiva.

## 7. ARQUITETURA VIGENTE DA SOLUÇÃO

### 7.1. Topologia de primeiro nível

**Arquivo Operacional**

- fonte oficial dos dados cadastrais, negociais, documentais e operacionais;
- contém oportunidades, levantamentos, estudos, orçamentos, Propostas, contratos, Projetos, parcelas e acompanhamentos operacionais;
- contém o Cadastro Mestre;
- publica ao Arquivo Financeiro somente referências e objetos necessários;
- não mantém fatos financeiros paralelos.

**Arquivo Financeiro**

- contém o Livro Financeiro único do Grupo;
- registra os fatos financeiros de ACPREV e CONGESPU;
- exige empresa responsável em cada fato;
- mantém segregação lógica, saldos e relatórios próprios por empresa;
- recebe referências controladas do Arquivo Operacional;
- não mantém Cadastro Mestre concorrente.

**Documentos e evidências externos**

Contratos, Notas Fiscais, comprovantes, extratos e outras evidências podem permanecer fora dos dois arquivos, desde que possuam referência, localização, proveniência e vínculo lógico controlados.

### 7.2. Fonte oficial e circulação

Cada dado possui uma única fonte oficial por domínio. A presença de uma cópia de consulta em outro arquivo:

- não transfere autoridade;
- não cria segunda fonte oficial;
- não permite edição concorrente;
- deve preservar identificador, origem, versão, data e resultado da publicação.

As integrações deverão operar por lotes ou execuções rastreáveis, com manifesto, contagens, rejeições, idempotência ou prevenção equivalente de repetição e possibilidade de reprocessamento controlado.

### 7.3. Segregação empresarial

ACPREV e CONGESPU compartilham o Livro Financeiro em uma única arquitetura física, mas todo fato financeiro conserva:

- empresa responsável;
- conta financeira própria;
- data, competência e origem;
- valor e tipo de evento;
- vínculos e evidências;
- histórico de alteração.

Consolidação analítica não significa fusão de saldos, transferência, compensação, reembolso ou operação intercompany automática.

### 7.4. Autoridade

O **Gestor Administrativo do Grupo** é a única autoridade humana sistêmica para atos administrativos que exigem decisão. A origem da determinação é opcional e não bloqueante, salvo regra específica. Validações contábil, fiscal, jurídica ou contratual permanecem independentes. O `SIS` aplica cálculos e controles, mas não aprova, inventa, presume ou encerra pendência por conta própria.

### 7.5. Operação não bloqueante

Inconsistências de negócio são registradas, alertadas e acompanhadas. Somente invalidade estrutural local ou hipótese expressamente aprovada bloqueia o registro. Ciência, visualização ou passagem do tempo não encerram alerta.

## 8. MODELO CONCEITUAL E LÓGICO CONSOLIDADO

### 8.1. Objetos centrais por domínio

**Cadastro e autoridade:** `ORGANIZACAO`, `PESSOA`, `PAPEL_ORGANIZACAO`, `DESIGNACAO`, `EMPRESA_FATURADORA` e referências de autoridade/vigência.

**Fluxo negocial:** `FLUXO_PROJETO` ou caso negocial contínuo, `OPORTUNIDADE`, `PROJETO`, `CONTRATO`, `ADITIVO` e relações entre Cliente Final, Parceiro, Contratante e Contratada.

**Levantamento e estudo:** `CICLO_LEVANTAMENTO`, `LEVANTAMENTO`, `REVISAO_LEVANTAMENTO`, `RELATORIO_TECNICO`, `ESTUDO_TECNICO`, `RELATORIO_ESTUDO` e `ENTREGA_ESTUDO`.

**Orçamento:** `RODADA`, `ORCAMENTO`, `CENARIO`, `SELECAO_ORCAMENTO_BASE`, `ORCAMENTO_DEFINIDO`, `CONSOLIDADO_EQUIPE`, `ALOCACAO_EQUIPE_ORCAMENTO` e `DESPESA_ORCAMENTO`.

**Proposta e composição:** `SERVICO`, `ITEM_ENTREGA`, `PERFIL`, composições de serviço, item e homem-hora, `PROPOSTA`, `VERSAO_PROPOSTA`, `CONTRATACAO` e `PARCELA_PREVISTA`.

**Faturamento e recebimento:** `NOTA_FISCAL`, `NOTA_FISCAL_PARCELA`, `RECEBIMENTO`, `RECEBIMENTO_NOTA_FISCAL`, `APURACAO_SIMPLES_NACIONAL` e `ESTORNO_RECEBIMENTO`.

**Distribuição e despesa:** `DISTRIBUICAO`, itens de distribuição, `DESTINACAO_VINCULADA_PROJETO`, registros de remuneração/pagamento, `DESPESA` e `ALOCACAO_GERENCIAL_DESPESA`.

**Caixa:** `CONTA_FINANCEIRA`, `MOVIMENTACAO_FINANCEIRA`, vínculos de conciliação e posições de saldo por empresa, conta, projeto e período.

### 8.2. Relações estruturantes

1. `Oportunidade → Levantamento → Relatório Técnico → Estudo → Relatório/Entrega do Estudo → Rodada → Orçamento → Cenário → Orçamento-Base → Orçamento Definido → Proposta → Contratação → Projeto`.
2. Um Projeto possui Empresa Faturadora vigente por intervalo temporal; substituição excepcional cria nova vigência e preserva a anterior.
3. Contrato e Aditivo permanecem objetos distintos; vínculo pendente ou ambíguo não produz efeito material automático.
4. `Nota Fiscal N ↔ N Parcela Prevista`, por `NOTA_FISCAL_PARCELA`, com valor de vínculo explícito.
5. `Recebimento N ↔ N Nota Fiscal`, por `RECEBIMENTO_NOTA_FISCAL`, com valor aplicado explícito.
6. Uma Nota Fiscal pertence a exatamente uma Empresa Faturadora e pode estar vinculada a zero ou um Projeto no modelo vigente; NF de vários Projetos permanece pendência futura.
7. Uma Despesa possui uma única empresa responsável; pode possuir zero a várias alocações gerenciais. A alocação não cria novo fato financeiro.
8. Uma movimentação de caixa pertence a uma empresa e conta; sua conciliação com fato de negócio não cria terceiro fato financeiro.

### 8.3. Temporalidade e histórico

Datas de referência, competência, previsão, vencimento, emissão, ocorrência, recebimento, pagamento, registro, confirmação, alteração e cancelamento permanecem distintas. Alteração ou correção gera evento posterior, sem apagar o estado anterior. Identificadores lógicos são permanentes; nome, posição de linha ou número externo não substituem o ID interno.

### 8.4. Integridade e prevenção de dupla contagem

- previsão não é faturamento;
- Nota Fiscal não é recebimento;
- recebimento não é movimentação bancária;
- distribuição, destinação, despesa, pagamento, provisão e saldo são fatos ou posições distintos;
- tabelas associativas representam vínculo ou decomposição, não novo valor econômico;
- relatórios somam o fato na granularidade adequada e preservam empresa, período e origem;
- cancelamento, substituição e estorno preservam o original e ajustam somente a posição determinável.

## 9. SEGURANÇA, CONTINUIDADE E TECNOLOGIA

### 9.1. Controles arquiteturais

Foram definidos controles para:

- autenticação e autorização por escopo;
- segregação de funções e empresas;
- proteção de arquivos, credenciais e ambientes;
- validação de integridade e alertas;
- registro de atividade e evidências;
- backup, restauração e recuperação;
- incidentes, contingência e operação degradada;
- concorrência de edição e sincronização no OneDrive;
- monitoramento, testes e revisão de continuidade.

Sincronização não equivale a backup. A existência de uma cópia não comprova restauração; os testes físicos permanecem pendentes para a fase de execução.

### 9.2. Preferência tecnológica

Ordem arquitetural de avaliação:

1. recursos nativos do Excel;
2. Power Query;
3. Office Scripts;
4. VBA, apenas se estritamente necessário.

Power Automate, n8n, APIs, aplicações próprias e infraestrutura externa permanecem alternativas futuras. `Hostinger KVM 2 + n8n` não constitui contratação, arquitetura fechada ou autorização de implantação.

## 10. DECISÕES, REVISÕES E HISTÓRICO

### 10.1. Decisões arquiteturais vigentes

O catálogo `4M2-D001–4M2-D024` permanece aprovado e vigente:

1. arquitetura modular Operacional e Financeira;
2. dois arquivos principais;
3. segregação empresarial forte;
4. OneDrive como repositório operacional oficial;
5. autoridade humana sistêmica única;
6. Confirmação Operacional do Registro;
7. operação não bloqueante e alertas persistentes;
8. aprovação somente por manifestação expressa;
9. hierarquia dos orçamentos;
10. vinculação da Proposta ao Orçamento Definido;
11. separação entre previsão contratual e execução financeira;
12. distinção entre eventos financeiros;
13. distribuições variáveis e fixas;
14. Destinação Vinculada ao Projeto;
15. Despesa e Alocação Gerencial da Despesa;
16. operações intercompany não presumidas;
17. separação das dimensões temporais;
18. preservação do histórico;
19. segurança e continuidade como condicionantes;
20. evolução tecnológica gradual;
21. integrações controladas e rastreáveis;
22. identidades lógicas permanentes;
23. consolidação sem dupla contagem;
24. linhagem e evidência de ponta a ponta.

Esses identificadores são referências internas da Fase 04 e não substituem IDs `DEC` do registro mestre.

### 10.2. Revisões funcionais incorporadas

- `REV-FUNC-001`: separa componente de despesa do orçamento, Despesa efetiva e Destinação Vinculada ao Projeto.
- `REV-FUNC-002`: estabelece o Gestor Administrativo do Grupo como autoridade humana sistêmica e preserva validações especializadas.
- `REV-FUNC-003`: regula a substituição excepcional da Empresa Faturadora, com vigência e histórico.
- `REV-FUNC-004`: estabelece operação predominantemente não bloqueante e alertas persistentes; substitui parcialmente `REV-FUNC-002` apenas nos aspectos incompatíveis de bloqueio operacional, preservando seu modelo de autoridade.
- `REV-FUNC-005`: institui Alocação Gerencial da Despesa sem duplicidade, finalidade `MISTA` ou intercompany automático.
- `REV-FUNC-006`: consolida a fórmula integral do Saldo Livre, com saldos reservado e vinculado, sobreposição, indisponibilidade única, disponibilidade positiva e déficit.

### 10.3. Precedência das revisões arquiteturais

- `ARQ04-4A-R01` é vigente; o estado intermediário de aprovação parcial permanece histórico; `R02` inexiste.
- `ARQ04-4G.2-R01` é vigente; apresentações anteriores sem numeração formal permanecem históricas.
- `ARQ04-4G.3-R04` é vigente; `R01`, `R02` e `R03` permanecem históricas.
- `ARQ04-4G.4-R01` é vigente e encerrada; versões iniciais de `4G.4.3–4G.4.5` foram substituídas; `PROVISAO_GERENCIAL_DESPESA` não foi aprovada.
- `ARQ04-4H-R01` é a unidade vigente do Bloco 4H e incorpora `REV-FUNC-006`.

### 10.4. Histórico não vigente

`4M3-H001–4M3-H017` preservam decisões substituídas, propostas não aprovadas, alternativas adiadas, erros de continuidade e fontes observacionais. Entre os conteúdos não vigentes estão:

- ordem editorial antiga de 4J/4K;
- bloqueios generalizados;
- obrigatoriedade genérica da origem da determinação;
- `PROVISAO_GERENCIAL_DESPESA`;
- responsabilidade empresarial `MISTA`;
- rateio, compensação, reembolso ou intercompany automático;
- aprovação automática pelo `SIS`;
- cancelamento tácito de `4F.8` e `4F.9`;
- criação de `4E.10`;
- aprovação antecipada de blocos futuros;
- planilhas e transcrições tratadas como fonte normativa automática.

## 11. RISCOS, PENDÊNCIAS, DEPENDÊNCIAS E LIMITAÇÕES

### 11.1. Inventários preservados

- riscos `4M4-R001–4M4-R024`;
- pendências `4M5-P001–4M5-P017`;
- matérias de implementação `4M5-I001–4M5-I006`;
- dependências `4M5-D001–4M5-D008`;
- lacunas `4M5-G001–4M5-G006`;
- limitações `4M5-L001–4M5-L006`;
- criticidades `CRIT-1–CRIT-4` e `CRIT-P`;
- prioridades `PR-0–PR-4`.

Uma mesma matéria pode aparecer em mais de um inventário; as contagens não representam ocorrências mutuamente exclusivas.

### 11.2. Atualizações de estado reconhecidas no encerramento

- `4M5-P001` e `4M5-P002`: resolvidas pela aprovação posterior de `4F.8` e `4F.9`.
- `4M5-P003`: resolvida no alcance arquitetural por `REV-FUNC-006`; implementação e teste permanecem pendentes.
- `4M5-P014`: atualização dos registros mestres em preparação neste fluxo documental.
- `4M5-P016`: pacote de encerramento em produção autorizada.
- `4M5-P017`: superada quanto à criação de novo checkpoint; `CHK-ARQ04-003` não deve ser criado.
- `PEN-03-024`: resolvida funcionalmente no alcance da fórmula do Saldo Livre; formalização mestre permanece pendente até publicação do corte pós-Fase 04.
- `PEN-03-020`: resolvida apenas quanto à precedência gerencial do Simples; matérias fiscais mais amplas permanecem abertas.
- `PEN-03-028`: resolvida funcionalmente por `REV-FUNC-003` quanto à autoridade, aos critérios e aos efeitos gerenciais da substituição excepcional da Empresa Faturadora; bordas jurídicas, contratuais, contábeis e fiscais permanecem transferidas.
- `PEN-03-001`, `PEN-03-002`, `PEN-03-014`, `PEN-03-023`, `PEN-03-026` e `PEN-03-027`: atualizadas somente quanto à autoridade sistêmica ou à superação do ajuste manual por `REV-FUNC-002`; as matérias residuais permanecem transferidas.
- `PEN-03-030`: resolvida funcionalmente quanto à autoridade sistêmica; regras matemáticas e implementação permanecem em controles próprios.
- `PEND-02-A`: autoridade operacional e agente de cálculo definidos; método de apropriação gerencial do Simples continua pendente.
- `PEN-AUD-013`: permanece sob governança e proveniência; nenhuma RN, RF ou CA será criada por inferência.

### 11.3. Pendências transferidas e não bloqueantes para o encerramento arquitetural

- nomes físicos de arquivos, tabelas, campos e intervalos;
- fórmulas, consultas, scripts e automações;
- catálogo físico definitivo e catálogo exaustivo de testes;
- catálogo detalhado, uniforme e validado de categorias de despesas realizadas, distinto das categorias do componente orçamentário;
- parâmetros e validações fiscais, contábeis, jurídicas e contratuais;
- tratamentos intercompany complexos;
- critérios finais de migração e saneamento de legados;
- política física de retenção;
- critérios quantitativos de desempenho;
- implementação, homologação, backup, restauração e operação;
- atualização e publicação do corte mestre pós-Fase 04.

Nenhuma dessas matérias será resolvida por inferência durante a execução futura.

## 12. RASTREABILIDADE E ENTREGÁVEIS

### 12.1. Cobertura funcional

A matriz complementar `MATRIZ-RASTREABILIDADE-RF-CA-ARQUITETURA v0.1 | 07/09/2026` relaciona os 50 RFs e os 187 CAs da REV03 aos blocos, objetos e controles arquiteturais responsáveis. A cobertura é arquitetural; não comprova implementação ou resultado de teste.

### 12.2. Correspondência com os entregáveis originalmente previstos

- `REG-FASE-04_ARQUITETURA-DA-SOLUCAO`: este arquivo.
- `DOC-ARQUITETURA-DA-SOLUCAO`: consolidado nas seções 5 a 9 deste arquivo.
- `MODELO-CONCEITUAL-E-LOGICO-DE-DADOS`: consolidado na seção 8.
- `MAPA-COMPONENTES-INTEGRACOES-E-FLUXOS`: consolidado nas seções 6, 7, 8 e 9.
- `MATRIZ-RASTREABILIDADE-RF-CA-ARQUITETURA`: arquivo separado autorizado.
- `CATALOGO-DECISOES-ARQUITETURAIS`: consolidado nas seções 10 e 11.
- `PLANO-TRANSICAO-PARA-CONSTRUCAO`: consolidado na seção 13.
- `REG-ENCERRAMENTO-FASE-04_ARQUITETURA-DA-SOLUCAO`: arquivo separado autorizado.

A consolidação em seções não elimina o conteúdo aprovado nem cria documentos faltantes por inferência.

## 13. PLANO DE TRANSIÇÃO E PORTÕES

### 13.1. Sequência `TR-01–TR-10`

O plano aprovado distingue: conclusão dos blocos; conferência; pacote documental; validações externas condicionais; atualização mestre; preparação da execução; construção; testes e homologação; entrada em operação.

Neste corte:

- `TR-01–TR-03`: concluídos;
- `TR-04`: produção documental autorizada e em execução;
- `TR-05`: não acionado automaticamente;
- `TR-06`: minutas mestres em preparação, publicação não autorizada;
- `TR-07–TR-10`: não autorizados ou não iniciados.

### 13.2. Portões anteriores à execução

`PT-ARQ-01`, `PT-DOC-01`, `PT-FUN-01`, `PT-ESC-01`, `PT-AMB-01`, `PT-DAD-01`, `PT-SEG-01`, `PT-BCP-01`, `PT-TEC-01`, `PT-HOM-01` e `PT-OPE-01` permanecem definidos. O encerramento arquitetural não os declara automaticamente atendidos para construção, uso de dados reais ou produção.

### 13.3. Próxima etapa

Depois do aceite documental deste pacote e da publicação expressamente autorizada dos registros mestres, deverá ser preparado o termo de transição. A abertura do Chat 94, da Fase 05 ou de qualquer frente executiva permanece proibida até autorização específica.

## 14. RESULTADO DA CONFERÊNCIA FINAL

Os controles `4N8-C01–C16` e os gates `GATE-4N-01–08` demonstraram:

- cobertura arquitetural de primeiro nível completa;
- inexistência de conflito material vigente entre revisões;
- coerência de identidades, granularidades, temporalidade e segregação empresarial;
- pendências e riscos identificados e transferíveis;
- arquitetura suficientemente definida para futura especificação física;
- ausência de autorização para implementação;
- necessidade de concluir o fluxo documental antes da transição externa.

Não foi identificado bloqueador arquitetural material para o encerramento substantivo da Fase 04.

## 15. PONTOS PARA VALIDAÇÃO

1. reconhecimento deste arquivo como registro consolidado da Fase 04;
2. preservação da linhagem `04 → 04B → 04_CONT` e do `CHK-ARQ04-002` como único checkpoint vigente;
3. confirmação de `ARQ04-4G.3-R04`, `ARQ04-4G.4-R01` e `ARQ04-4H-R01` como referências vigentes em seus escopos;
4. reconhecimento de `REV-FUNC-001–006` como aprovadas e incorporadas;
5. aceitação da arquitetura de dois arquivos, com Cadastro Mestre dentro do Arquivo Operacional e Livro Financeiro único segregado no Arquivo Financeiro;
6. aceitação do inventário de blocos, decisões, histórico, riscos e pendências consolidados;
7. aceitação da correspondência entre este registro e os entregáveis inicialmente previstos;
8. manutenção das pendências transferidas e dos portões de execução sem solução por inferência;
9. manutenção da publicação do corte mestre pós-Fase 04, do Chat 94, da Fase 05 e de qualquer implementação como não autorizadas.

O aceite desta seção tornará este arquivo formalmente aceito como produto da Fase 04. Não autorizará a publicação das minutas mestres pós-Fase 04 nem qualquer execução técnica.