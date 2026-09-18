# E-ESC-03 — CATÁLOGO CONTROLADO DE ESTADOS E EVENTOS DO NÚCLEO TRANSVERSAL RASTREADO

## 1. Controle documental

| Atributo | Valor |
|---|---|
| Projeto | Dev_Ecossistema_Integrado_Gestao_Empresarial |
| Chat de continuidade | 91D_Consolidação do Projeto — Continuidade do Chat 91C |
| Fase | Fase 05 — Detalhamento / Especificação Técnica |
| Escopo pai | ESC-F05-01 — Fundação Transversal de Governança, Identidade, Proveniência e Rastreabilidade |
| Unidade | UT-F05-01-04 — Catálogo Controlado de Estados e Eventos do Núcleo Transversal Rastreado |
| Produto | E-ESC-03 — Catálogo de Estados e Eventos |
| Versão | v0.2 |
| Data | 2026-09-15 |
| Responsável humano | Eduardo Andrade Ramos |
| Nome físico | `E-ESC-03_CATALOGO-ESTADOS-E-EVENTOS_v0.2_2026-09-15_MINUTA.md` |
| Situação | **MINUTA CORRENTE PREPARADA — NÃO PUBLICADA — AGUARDANDO ACEITE EXPRESSO** |
| Natureza | catálogo documental transversal; sem efeito executivo, normativo, arquitetural, implementador ou publicador |
| Tamanho e SHA-256 | apurados externamente depois do fechamento dos bytes desta minuta |

Esta é a única criação documental da execução autorizada de UT-F05-01-04.

---

## 2. Conclusão executiva

Foram examinados integralmente os 182 detalhes correntes de E-ESC-02 v0.2, os 24 códigos de fonte `S01-A`–`S22` e os 387 vínculos diretos registrados naquela matriz. O exame resultou em 98 entradas semânticas transversais documentalmente sustentadas: estados e marcadores de qualidade, valores e ausências, classificações de fonte e operação, situações de disponibilidade e prática, qualidade de linhagem, dimensões e precisões temporais, tipos de nó, papéis empresariais e eventos transversais.

As 98 entradas não são um catálogo físico universal. Seus identificadores `CAT-*` são endereços internos desta minuta e não criam códigos de implementação. Termos literais já existentes foram preservados; candidatos textuais continuam candidatos; aplicabilidades dependentes de fonte permanecem `PARCIAL/CONDICIONADO`.

O catálogo não cria evento, transição, fluxo ou máquina de estados de domínio. As únicas seis regras de passagem registradas são as expressamente constantes das fontes correntes: três relativas à qualidade do dado, uma à classificação da fonte e duas à decisão sobre prática observada. Nenhuma passagem automática foi instituída.

A rastreabilidade é bidirecional: cada entrada aponta para detalhe(s) e fonte(s), e a matriz reversa indica, para todo o universo de 182 detalhes, se ele gera entrada, fornece metadado/regra/relação ou permanece condicionado. Não houve analogia para preencher lacuna.

A linha mestre v0.17/v0.21/v0.16 permanece inalterada; C-F05-05 permanece parcialmente atendida; o inventário permanece 67/67; PEN-AUD-013 permanece resolvida sem nova RN; 4M5-P010 permanece resolvida somente quanto à fonte/proveniência; nenhum `PT-*` foi avaliado.

---

## 3. Autoridade, alcance e limites

### 3.1 Cadeia autorizativa aplicável

| Ato | Alcance nesta execução | Qualificação |
|---|---|---|
| proposta autônoma `PROPOSTA-UT-F05-01-04...v0.1` | delimita identidade, produto, entradas, atividades, aceite e parada | aceita externamente; identidade física reconfirmada no §4 |
| aceite literal da proposta neste Chat 91D | aceita a delimitação autônoma da unidade | ato externo posterior aos registros mestres |
| autorização literal mais recente neste Chat 91D | executar exclusivamente UT-F05-01-04, preparar somente esta minuta, conferi-la, apresentá-la e parar | **ATO AUTORIZATIVO EXTERNO NÃO NUMERADO NESTA MINUTA** |

Não se atribui, reserva, sugere ou infere identificador `DEC` para esses atos. O REG-DECISOES v0.21 não é modificado.

### 3.2 Alcance positivo

A autorização cobre somente: reconfirmar as entradas; examinar o universo 182/24/387; separar estado, valor, ausência, classificação, situação, resultado e evento; registrar apenas semânticas transversais expressas; demonstrar aplicabilidade e rastreabilidade bidirecional; condicionar lacunas; aplicar C-F05-09; preservar C-F05-05 e o inventário 67/67; preparar e conferir esta minuta; apresentá-la para aceite.

### 3.3 Proibições operacionais

Permanecem proibidos: usar o mérito de E-ESC-03 v0.1; alterar E-ESC-01 ou E-ESC-02; criar ou alterar PF-01–PF-09, campos, restrições ou REL-01–REL-14; criar ou alterar RN, RF, CA ou arquitetura; criar semântica de domínio; instituir fluxo ou máquina de estados; definir tecnologia; publicar esta minuta; criar ou publicar E-ESC-04; alterar os registros mestres; avaliar `PT-*`; fechar o mapeamento lógico-físico; concluir ESC-F05-01; implementar; iniciar unidade posterior.

---

## 4. Reconciliação física das entradas obrigatórias

### 4.1 Entradas executivas e linha mestre

| # | Entrada observada | Bytes | SHA-256 observado | Uso | Resultado |
|---:|---|---:|---|---|---|
| 1 | `PROPOSTA-UT-F05-01-04_CATALOGO-CONTROLADO-DE-ESTADOS-E-EVENTOS-DO-NUCLEO-TRANSVERSAL-RASTREADO_v0.1_2026-09-15_MINUTA.md` | 31.370 | `5be73c8f38fe23574fce570d917ed5fa90605fee0fcb2606b2cf0265b8fbee17` | delimitação integral da unidade | **COINCIDE** |
| 2 | `E-ESC-01_ESPECIFICACAO-TRANSVERSAL_v0.2_2026-09-15.md` | 79.275 | `8bd83778fe7c9ed8c2dbd1041db487e05874bac942d611ceefd7ad09bc46ad44` | universo especificado corrente | **COINCIDE** |
| 3 | `E-ESC-02_MATRIZ-RASTREABILIDADE_v0.2_2026-09-15.md` | 84.727 | `8db091b15cd171e680e3e562f56211cf950cf6fe822e0dd2cdc1b923950081a3` | detalhes e vínculos correntes | **COINCIDE** |
| 4 | `REG-CONSOLIDACAO-CHATS_v0.17_2026-09-15.md` | 111.371 | `0cdae5ea176441626723ea7c058cdc4c4e6fd8962f7dcf5411088652071c5a51` | baseline e corte | **COINCIDE** |
| 5 | `REG-DECISOES_v0.21_2026-09-15.md` | 167.502 | `5865d5f2332dcbb0023deb34e64ec50b70ad1e49cc73b4081c583cde13e31ed4` | estado decisório incorporado | **COINCIDE** |
| 6 | `REG-PENDENCIAS_v0.16_2026-09-15.md` | 114.767 | `65dbaaa13bd9a9555d623eb39f64c081510d30adcafd1102b21aff76ed575c2e` | estados correntes de riscos e pendências | **COINCIDE** |

Resultado: **6/6 nomes, 6/6 tamanhos e 6/6 SHA-256 coincidentes; zero divergência material; barreira física superada**.

As referências internas de E-ESC-01 e E-ESC-02 ao estado existente quando seus bytes foram preparados são marcas históricas. Os atos externos posteriores qualificam ambos como publicados e aceitos sem exigir alteração de seus bytes.

### 4.2 Qualificação histórica de E-ESC-03 v0.1

| Atributo | Valor |
|---|---|
| Arquivo histórico | `E-ESC-03_CATALOGO-ESTADOS-E-EVENTOS_v0.1_2026-09-12_MINUTA.md` |
| Tamanho | 5.565 bytes |
| SHA-256 | `d55b12fc85c2bdf111ae996291df81c92d6b2b866267660e6a3368f98663c17e` |
| Estado | **MINUTA TÉCNICA HISTÓRICA — NÃO VIGENTE — NÃO PUBLICADA** |
| Uso realizado | existência, identidade, proveniência e sequência de versão |
| Uso vedado e não realizado | mérito, estrutura, catálogo, estados, eventos, transições, vínculos ou conclusões |

Nenhum conteúdo de mérito da v0.1 foi lido para compor, copiado, promovido ou usado para preencher esta v0.2.

---

## 5. Catálogo herdado das 24 fontes de mérito e governança

Os códigos abaixo são exatamente os 24 códigos `S` herdados de E-ESC-01 v0.2 e E-ESC-02 v0.2. A proposta, a autorização, E-ESC-01, E-ESC-02 e a identidade histórica de E-ESC-03 são entradas executivas desta unidade; não recebem novo código `S` e não alteram a contagem 24.

| ID | Fonte | Bytes | SHA-256 | Uso nesta unidade |
|---|---|---:|---|---|
| `S01-A` | `REG-CONSOLIDACAO-CHATS v0.17` | 111.371 | `0cdae5ea176441626723ea7c058cdc4c4e6fd8962f7dcf5411088652071c5a51` | baseline e corte |
| `S01-B` | `REG-DECISOES v0.21` | 167.502 | `5865d5f2332dcbb0023deb34e64ec50b70ad1e49cc73b4081c583cde13e31ed4` | sequência interna e estado decisório |
| `S01-C` | `REG-PENDENCIAS v0.16` | 114.767 | `65dbaaa13bd9a9555d623eb39f64c081510d30adcafd1102b21aff76ed575c2e` | estados correntes e camada externa |
| `S02` | `INSTRUCOES-INICIAIS-FASE-05 v0.2` | 16.323 | `8efe8794490fd29c481d68afa4cab82953a4154040f129d07de0ac747a25a6be` | trilha ES; C-F05-03/04/05/08/09 |
| `S03` | `PROPOSTA-PRIMEIRO-ESCOPO-FASE-05 v0.2` | 19.304 | `b6222f83c77916db8394ceb8ea361044ee8c13ae7449d786339652b6d870a34a` | finalidade de E-ESC-03 e exclusão de domínio |
| `S04` | `REG-ABERTURA-ADMINISTRATIVA-FASE-05 v0.2` | 11.702 | `a926f81b6c919b89222a99bc735de8a2328702cc2d706c266b5ad14645e311e6` | abertura e governança da fase |
| `S05` | `REL-SANEAMENTO-ENTRADAS-ESC-F05-01 v0.1` | 29.590 | `090fcee4809c6743f2c5699c59015c5a6a1847f343cbd35e33efa89cf2ba5184` | barreira SD–ES e disponibilidade |
| `S06` | `PROPOSTA-UT-F05-01-02 v0.1` | 23.109 | `911fdb09ae667d70e0a4fb54d96d54c230e71e627a84573aacb521d5e9914135` | atomicidade dos produtos |
| `S07` | `CAT-REGRAS-NEGOCIO v0.3` | 33.151 | `f2e5977053d775f56c8a1146a1ce490b83aa4c7f1c81a26635b1e2e1caab3b03` | RNs existentes; vedação de nova RN |
| `S08` | `CAT-REQUISITOS-FUNCIONAIS v0.1 REV04` | 192.409 | `05de0e3036459cd83b54935dd3ba2fefad47eeed4b8cc3e34ee0195af3005cb5` | RF-03-001, RF-03-004, RF-03-050, CAs e taxonomia não bloqueante |
| `S09` | `MATRIZ-RASTREABILIDADE-RN-RF v0.1 REV04` | 128.020 | `95fc33ff4bf29994faa6dbae91e98e62d008991f6887d483a3e4ab42acf911b5` | baseline RN–RF atual |
| `S10` | `MATRIZ-RASTREABILIDADE-RN-RF v0.1 REV03` | 125.787 | `d7a82f115b4e359db53a3afa0771b682b2463f11c978f32ac854665ea892ece4` | fonte histórica qualificada |
| `S11` | `REG-FASE-03_REQUISITOS-FUNCIONAIS v0.1 REV03` | 33.364 | `8c0d172e490b5bc0618c07fe112f105f8a475775fcb47e4ff14178c83a947b31` | decisões funcionais aplicáveis |
| `S12` | `CATALOGO-DECISOES-ARQUITETURAIS v0.2` | 32.606 | `9c18b8be6343649fd16d88a910a50b59708ac1b8f56a5542eab82530dac031de` | D003/D017/D018/D021/D022/D023/D024 |
| `S13` | `MODELO-CONCEITUAL-E-LOGICO-DE-DADOS v0.2` | 189.938 | `622575b89c8e5e30947721ac5b3022eca86b239b2b9f4568409099c286f37333` | identidade, granularidade e temporalidade |
| `S14` | `MAPA-COMPONENTES-INTEGRACOES-E-FLUXOS v0.2`, especialmente `4L.7` | 116.930 | `6508df5083142e33b2d9326af4886ea20599000630f95710a7943cd1391dd92c` | estados de fonte/linhagem, evento, evidência e limites |
| `S15` | `MATRIZ-RASTREABILIDADE-RF-CA-ARQUITETURA v0.2` | 22.044 | `5b9f98937efe5783378f9b699f49beb645da352cf96767c23af5c3406e7c4377` | cobertura RF/CA/arquitetura |
| `S16` | `REG-INVENTARIO-AUTONOMO-RISCOS-E-PENDENCIAS ... AUD94-012 v0.1` | 56.508 | `a540261ae42edd632e84c3685dbf0ab9799665d1d04ce8634dd84ac7e49ca340` | universo fechado de 67 itens |
| `S17` | atos externos `DEC-91-171–DEC-91-181` no Chat 91C | não aplicável | não aplicável | autoridade prospectiva e qualificação temporal |
| `S18` | `PROPOSTA-ABERTURA-CONTROLADA-FASE-05 v0.2` | 23.604 | `e153fe1cfbbdbf432c48fe7a1b796d6b6e99bb51abbf0ca79805a1e39dcf6d85` | limites da abertura |
| `S19` | `REL-CONFERENCIA-PACOTE-PREPARATORIO-ABERTURA-FASE-05 v0.2` | 16.407 | `a6a62c0f90f0279301d93c5d1ecf3e31f12d0e2cdc051dbc359dd18af9d8f1ac` | integridade do pacote preparatório |
| `S20` | `PROPOSTA-UT-F05-01-01 v0.1` | 19.595 | `77a305998e5498cfb69c49912c76658d1f66af5d2b32d6c2df943ba1bb9f2b3d` | identidade e limites da predecessora |
| `S21` | `REG-FASE-04_ARQUITETURA-DA-SOLUCAO v0.1` | 29.210 | `f6ec9c42ed69e02a4c72e0a8f35f3895e1e9d278bd47a4e03b79b1ee8fd6f604` | proveniência da arquitetura vigente |
| `S22` | `REG-ENCERRAMENTO-FASE-04_ARQUITETURA-DA-SOLUCAO v0.1` | 12.596 | `2afe426318a912290afc1e27492509f2173f5b4f88c8fdd83840696faa94ec28` | encerramento da fase anterior |

Os 24 códigos foram examinados no contexto dos 387 vínculos de E-ESC-02. Somente `S08`, `S09`, `S11`, `S12`, `S13` e `S14` fornecem mérito semântico direto às entradas deste catálogo; os demais fornecem governança, identidade, corte, rastreabilidade, limites ou confirmação negativa. Isso não retira nenhum código nem vínculo da matriz corrente.

---

## 6. Convenções vinculantes de leitura

### 6.1 Naturezas semânticas

| Natureza | Regra de leitura |
|---|---|
| estado | condição controlada que pode ser registrada ou derivada somente conforme a fonte |
| valor | conteúdo material conhecido; zero continua valor e não se transforma em ausência |
| ausência | falta permitida ou inexistência; não recebe automaticamente uma linha de estado |
| classificação | categoria controlada; mudança não ocorre sem evento quando a fonte assim exige |
| situação | condição observável cujo catálogo pode ser completo ou condicionado |
| resultado | efeito registrado de evento ou retenção de resultado dependente; não equivale a aprovação |
| evento | ocorrência histórica imutável e correlacionável; não é fluxo, comando nem estado de domínio |

### 6.2 Identificadores internos

Os identificadores `CAT-*`, `EVT-*` e `TR-*` organizam este documento. Não são códigos físicos, não reservam enumerações, não criam tabela e não substituem os literais documentados. Quando o termo aparece entre crases, sua grafia é preservada da fonte. Quando aparece em linguagem natural, continua candidato semântico e não código implementável.

### 6.3 Classificação C-F05-09

| Classificação | Efeito |
|---|---|
| `DISPONÍVEL` | termo e semântica possuem suporte expresso suficiente neste núcleo documental |
| `PARCIAL/CONDICIONADO` | aplicação, catálogo concreto, autoridade, metadado ou regra depende de fonte competente futura |
| `EXCLUÍDO` | matéria fora do núcleo transversal ou dependente de regra indisponível; não gera entrada |

Uma entrada `DISPONÍVEL` continua não implementável enquanto candidata. Disponibilidade documental não equivale a vigência física, autorização de automação ou aplicabilidade universal.

---

## 7. Exame integral do universo 182/24/387

### 7.1 Controle quantitativo

| Universo | Quantidade examinada | Resultado |
|---|---:|---|
| objetos `DET-PF-nn-O` | 9 | 9 âncoras de aplicabilidade |
| campos `DET-PF-nn-Fnn` | 123 | 29 catalogáveis; 94 de metadado, referência ou condição |
| restrições `DET-PF-nn-Rnn` | 36 | 28 regras aplicáveis; 8 limites condicionados |
| relações `DET-REL-nn` | 14 | 9 disponíveis; 5 condicionadas |
| **detalhes** | **182** | **182/182 classificados; zero omissão** |
| códigos de fonte | 24 | 24/24 examinados |
| vínculos diretos fonte→detalhe | 387 | 387/387 examinados; nenhum alterado ou ampliado |

### 7.2 Classificação reversa dos 182 detalhes

Os intervalos são inclusivos. Cada identificador aparece em exatamente uma linha abaixo.

| Classe de pertinência | Detalhes abrangidos | Qtde. | Tratamento neste catálogo |
|---|---|---:|---|
| âncoras de objeto | `DET-PF-01-O`–`DET-PF-09-O` | 9 | definem aplicação; não se tornam estados/eventos |
| campos catalogáveis | `DET-PF-01-F06`; `DET-PF-02-F03/F09`; `DET-PF-03-F03/F11–F13/F16/F20`; `DET-PF-04-F03/F05/F08`; `DET-PF-05-F07/F10/F12–F13/F16–F17/F23/F30`; `DET-PF-06-F04`; `DET-PF-07-F03–F04/F10`; `DET-PF-08-F04`; `DET-PF-09-F02/F04/F06/F09` | 29 | geram entradas ou pontos condicionados explícitos |
| campos de suporte | `DET-PF-01-F01–F05`; `DET-PF-02-F01–F02/F04–F08`; `DET-PF-03-F01–F02/F04–F10/F14–F15/F17–F19/F21`; `DET-PF-04-F01–F02/F04/F06–F07`; `DET-PF-05-F01–F06/F08–F09/F11/F14–F15/F18–F22/F24–F29/F31–F33`; `DET-PF-06-F01–F03/F05–F09`; `DET-PF-07-F01–F02/F05–F09/F11–F14`; `DET-PF-08-F01–F03/F05–F10`; `DET-PF-09-F01/F03/F05/F07–F08/F10–F13` | 94 | metadados, identidade, autoridade, evidência, motivo, tempo e correlação; não geram novos termos |
| regras aplicáveis | `DET-PF-01-R01–R03`; `DET-PF-03-R01–R05`; `DET-PF-04-R01–R02`; `DET-PF-05-R01–R03/R06`; `DET-PF-06-R01–R03`; `DET-PF-07-R01`; `DET-PF-08-R01–R08`; `DET-PF-09-R01–R02` | 28 | governam entrada, passagem, preservação ou proibição |
| limites condicionados | `DET-PF-01-R04`; `DET-PF-02-R01`; `DET-PF-03-R06`; `DET-PF-05-R04–R05`; `DET-PF-06-R04`; `DET-PF-07-R02`; `DET-PF-09-R03` | 8 | permanecem `PARCIAL/CONDICIONADO`; não são completados |
| relações disponíveis | `DET-REL-01/03/04/07–10/12/14` | 9 | aplicabilidade e correlação sustentadas |
| relações condicionadas | `DET-REL-02/05/06/11/13` | 5 | cardinalidade, catálogo ou materialidade futura |
| **Total** | universo fechado | **182** | **182/182** |

### 7.3 Resultado de pertinência

Os 29 campos catalogáveis não produzem necessariamente um termo: `situacao_conflito`, `situacao_vinculo`, `tipo_evento`, `resultado_evento`, `tipo_relacao_linhagem`, indicador de estimativa, vigência e tipos condicionados permanecem pontos abertos porque as fontes não fornecem catálogo universal. Os 94 campos de suporte são pertinentes para metadados e provas, mas não autorizam criar 94 estados. Os 36 comandos e as 14 relações controlam o uso das entradas sem gerar domínio novo.

---

## 8. Catálogo de qualidade, valor, ausência e operação não bloqueante

### 8.1 Estado de qualidade, valor e ausência

| ID interno | Termo sustentado | Natureza e definição controlada | Representação / metadados | Detalhe(s) E-ESC-02 | Fonte competente | C-F05-09 / limite |
|---|---|---|---|---|---|---|
| `CAT-QD-001` | `INCOMPLETO` | estado de qualidade de campo obrigatório ainda incompleto | linha PF-08; referência ao componente; evento de registro; conclusão local não definitiva | `DET-PF-08-F03–F04/F09–F10`; `DET-PF-08-R01/R04/R07`; `DET-REL-08` | `S08 RF-03-001`, `CA-01`; `S09`; `S11` | `DISPONÍVEL`; não autoriza dado fictício nem trava global |
| `CAT-QD-002` | `PENDENTE` | estado de qualidade em que a informação depende de providência identificada | linha PF-08 com motivo, responsável e data; evento de registro/resolução | `DET-PF-08-F03–F07/F09–F10`; `DET-PF-08-R02/R04/R07`; `DET-REL-08` | `S08 RF-03-001`, `CA-03`; `S09`; `S11` | `DISPONÍVEL`; não pode existir sem os três metadados |
| `CAT-QD-003` | `NAO_APLICAVEL` | estado de qualidade admitido somente quando o RF do objeto excluir a incidência | linha PF-08 com fundamento; evento de registro/resolução | `DET-PF-08-F03–F04/F08–F10`; `DET-PF-08-R03/R05/R07`; `DET-REL-08` | `S08 RF-03-001`, `VAL-RF001-04`; `S09`; `S11` | `DISPONÍVEL`; aplicabilidade ao domínio é `PARCIAL/CONDICIONADO` |
| `CAT-QD-004` | `COMPLETO` | condição de qualidade alcançada quando o dado exigido está materialmente completo | valor permanece no objeto material; não há linha PF-08 ativa para representar completude | `DET-PF-08-F04/F10`; `DET-PF-08-R01/R07`; `DET-REL-08` | `S08 RF-03-001`, regra de transição | `DISPONÍVEL` como condição de saída; **não é valor armazenável de PF-08** |
| `CAT-VA-001` | valor conhecido diferente de zero | valor material efetivamente conhecido | valor tipado no objeto; nenhuma linha PF-08 se completo | `DET-PF-08-O/F02–F04`; `DET-PF-08-R01/R07`; `DET-REL-08` | `S08 RF-03-001`; `S09` | `DISPONÍVEL`; não duplicar como pendência |
| `CAT-VA-002` | valor conhecido igual a zero | valor material `0`, distinto de branco e de inexistência | `0` no campo material; nenhuma linha usada para representar ausência | `DET-PF-08-O/F02–F04`; `DET-PF-08-R01/R06–R07`; `DET-REL-08` | `S08 CA-RF-03-001-02`; `S09`; `S11` | `DISPONÍVEL`; zero nunca vira ausência |
| `CAT-VA-003` | branco permitido pelo RF de domínio | ausência simples em campo cuja omissão é permitida | campo material ausente; sem zero e sem estado fictício | `DET-PF-08-F03–F04`; `DET-PF-08-R01/R05–R07`; `DET-REL-08` | `S08 RF-03-001`; `S09` | `PARCIAL/CONDICIONADO` ao RF do domínio |
| `CAT-VA-004` | objeto ou evento inexistente | inexistência de ocorrência; expressamente um não estado | nenhuma linha do objeto e nenhuma linha vazia PF-08 | `DET-PF-08-O/F01–F04`; `DET-PF-08-R05–R07`; `DET-REL-08` | `S08 CA-RF-03-001-04`; `S09`; `S11` | `DISPONÍVEL`; proibido fabricar registro vazio ou pendência |

### 8.2 Taxonomia transversal de operação não bloqueante

| ID interno | Código e termo sustentado | Definição controlada | Detalhe(s) E-ESC-02 | Fonte competente | C-F05-09 / limite |
|---|---|---|---|---|---|
| `CAT-OP-001` | `IE-L — Impedimento Estrutural Local` | impede somente campo, chave, vínculo ou registro estruturalmente inválido; não bloqueia operação independente | `DET-PF-01-R01–R03`; `DET-PF-04-R02`; `DET-PF-05-R01/R03`; `DET-PF-08-R07`; `DET-REL-01/03/04/08/09` | `S08 REV-FUNC-004`, §§6.1–6.4; `S09`; `S11` | `DISPONÍVEL`; não cria validação física |
| `CAT-OP-002` | `AD-NB — Alerta de Negócio Não Bloqueante` | qualifica ausência, divergência ou incompatibilidade de negócio e preserva o fato estruturalmente válido | `DET-PF-03-F12/F16`; `DET-PF-05-F33`; `DET-PF-05-R06`; `DET-PF-09-F09–F11` | `S08 REV-FUNC-004`, §§6.1–6.4; `S14 4L.7 §§18, 34, 41–42` | `DISPONÍVEL`; critérios concretos de alerta ficam condicionados |
| `CAT-OP-003` | `RD-NP — Resultado Dependente Não Produzido ou Não Definitivo` | retém resultado dependente sem base confiável, sem impedir outros registros e sem fabricar resultado | `DET-PF-05-F30/F33`; `DET-PF-05-R06`; `DET-PF-08-R04`; `DET-PF-09-F09–F11` | `S08 REV-FUNC-004`, §§6.1–6.4; `S11`; `S14 4L.7 §§34, 41–42` | `DISPONÍVEL`; o catálogo concreto de `resultado_evento` permanece condicionado |
| `CAT-OP-004` | `PAI — Proibição de Automação ou Inferência` | veda apagar, fundir, compensar, reclassificar, transferir, selecionar, concluir ou criar vínculo por inferência | `DET-PF-03-R02/R05`; `DET-PF-05-R01–R04`; `DET-PF-06-R02–R03`; `DET-PF-09-R01–R02`; `DET-REL-09/11/13` | `S08 REV-FUNC-004`, §§6.1–6.4; `S12 D003/D018/D024`; `S14 4L.7` | `DISPONÍVEL`; é proibição, não evento nem estado de domínio |

`IE-L`, `AD-NB`, `RD-NP` e `PAI` não autorizam este documento a classificar casos de domínio. O catálogo preserva somente suas definições transversais e os pontos de aplicação já rastreados.

---

## 9. Catálogo de fonte, evidência, prática, derivação e linhagem

### 9.1 Natureza da fonte

| ID interno | Literal | Definição controlada | Detalhe E-ESC-02 | Fonte | C-F05-09 |
|---|---|---|---|---|---|
| `CAT-NF-001` | `MODELO_EXCEL` | fonte cuja natureza é o modelo Excel, sem precedência automática | `DET-PF-03-F03`; `DET-PF-03-R03`; `DET-REL-10/11` | `S08 RF-03-050`, CAs 01/04/05; `S09` | `DISPONÍVEL` |
| `CAT-NF-002` | `SAIDA` | saída ou representação produzida, distinta da fonte e do fato | `DET-PF-03-F03/F20–F21`; `DET-PF-03-R01/R03`; `DET-REL-10` | `S08 RF-03-050`, CA-02; `S14 4L.7 §17` | `DISPONÍVEL` |
| `CAT-NF-003` | `OFICIAL` | documento oficial com natureza própria, não substituível automaticamente por planilha | `DET-PF-03-F03`; `DET-PF-03-R03–R05`; `DET-REL-11` | `S08 RF-03-050`, CA-05; `S09` | `DISPONÍVEL` |
| `CAT-NF-004` | `PRATICA` | prática observada, distinta de regra e dependente de decisão para aprovação/descarte | `DET-PF-03-F03/F13–F14`; `DET-PF-03-R02`; `DET-REL-14` | `S08 RF-03-050`, CA-06; `S09`; `S12 D024` | `DISPONÍVEL` |

### 9.2 Situação de classificação da fonte

| ID interno | Literal | Definição controlada | Metadados/condição | Detalhe(s) | Fonte | C-F05-09 |
|---|---|---|---|---|---|---|
| `CAT-FC-001` | `CLASSIFICACAO_PENDENTE` | fonte ainda não classificada no catálogo competente | identidade da fonte, momento e responsável; mudança exige evento | `DET-PF-03-F09–F11`; `DET-PF-05-F16–F17/F25/F31`; `DET-REL-03/09/14` | `S08 RF-03-050`; `S14 4L.7 §§6, 10` | `DISPONÍVEL` |
| `CAT-FC-002` | `CLASSIFICADA` | fonte cuja classificação foi concluída e preservada historicamente | classificação anterior/posterior, executor e fonte do evento | `DET-PF-03-F11`; `DET-PF-05-F16–F17/F21/F26/F31`; `DET-REL-03/09/14` | `S08 RF-03-050`; `S14 4L.7 §§6, 10` | `DISPONÍVEL`; não equivale a aprovação de conteúdo |

### 9.3 Situação de disponibilidade da fonte ou evidência

| ID interno | Termo sustentado | Semântica | Detalhe(s) | Fonte | C-F05-09 / limite |
|---|---|---|---|---|---|
| `CAT-DF-001` | disponível | fonte recuperável e utilizável para a finalidade declarada | `DET-PF-03-F05/F12`; `DET-PF-03-R01`; `DET-PF-04-F05–F06` | `S14 4L.7 §§14–18` | `DISPONÍVEL`; não é aprovação material |
| `CAT-DF-002` | parcialmente disponível | somente parcela identificada está disponível | `DET-PF-03-F05/F12`; `DET-PF-04-F05–F06`; `DET-PF-09-F09–F11` | `S14 4L.7 §§15, 18, 41–42` | `DISPONÍVEL`; escopo da parcela deve ser explícito |
| `CAT-DF-003` | indisponível | fonte identificada não está disponível | `DET-PF-03-F05/F12`; `DET-PF-05-F33`; `DET-PF-09-F09–F11` | `S14 4L.7 §§16, 18, 34, 41–42` | `DISPONÍVEL`; não autoriza evidência fictícia |
| `CAT-DF-004` | ilegível | fonte existe, mas não é legível de modo confiável | `DET-PF-03-F05/F12`; `DET-PF-05-F33`; `DET-PF-09-F09–F11` | `S14 4L.7 §18` | `DISPONÍVEL`; conteúdo não é inferido |
| `CAT-DF-005` | divergente | fontes ou representações apresentam divergência preservada | `DET-PF-03-F12/F16–F19`; `DET-PF-03-R05`; `DET-REL-11` | `S08 RF-03-050`; `S14 4L.7 §18` | `DISPONÍVEL`; nenhuma prevalência silenciosa |
| `CAT-DF-006` | inconsistente | fonte possui inconsistência que deve permanecer visível | `DET-PF-03-F12/F16`; `DET-PF-05-F33`; `DET-PF-09-F09–F11` | `S14 4L.7 §§18, 34, 41–42` | `DISPONÍVEL`; não autoriza correção automática |
| `CAT-DF-007` | substituída | fonte foi sucedida, preservando-se a identidade anterior e a derivação | `DET-PF-03-F07/F12/F20–F21`; `DET-PF-05-F31–F32`; `DET-REL-09/10` | `S14 4L.7 §§10–12, 17–18` | `DISPONÍVEL`; fonte anterior não é apagada |
| `CAT-DF-008` | cancelada | fonte cancelada permanece histórica | `DET-PF-03-F07/F12`; `DET-PF-05-F31–F32`; `DET-REL-09` | `S12 D018`; `S14 4L.7 §§11–12, 18` | `DISPONÍVEL`; cancelamento não reutiliza identidade |
| `CAT-DF-009` | não aplicável | disponibilidade não incide para a finalidade explicitamente fundamentada | `DET-PF-03-F04/F12`; `DET-PF-04-F05–F06` | `S14 4L.7 §18` | `PARCIAL/CONDICIONADO` à finalidade competente |

### 9.4 Situação da prática

| ID interno | Literal | Definição controlada | Metadados/condição | Detalhe(s) | Fonte | C-F05-09 |
|---|---|---|---|---|---|---|
| `CAT-PR-001` | `OBSERVADA` | prática registrada como observação, sem natureza de regra ou aprovação | natureza `PRATICA`, fonte, momento e responsável | `DET-PF-03-F03/F09–F14`; `DET-PF-03-R01–R02`; `DET-REL-14` | `S08 RF-03-050`, CA-06; `S09` | `DISPONÍVEL` |
| `CAT-PR-002` | `APROVADA` | prática promovida somente por decisão expressa competente | `id_decisao_pratica`, evento, autoridade, justificativa e antes/depois | `DET-PF-03-F13–F14/F19`; `DET-PF-03-R02`; `DET-PF-05-F12–F13/F20–F28`; `DET-REL-03/09/14` | `S08 RF-03-050`, CA-06 e `AUT-RF050-01`; `S12 D024` | `DISPONÍVEL`; não cria a decisão |
| `CAT-PR-003` | `DESCARTADA` | prática rejeitada para a finalidade por decisão expressa, preservando o histórico | mesmos metadados da decisão; a observação não é apagada | `DET-PF-03-F13–F14/F19`; `DET-PF-03-R02`; `DET-PF-05-F12–F13/F20–F28`; `DET-REL-03/09/14` | `S08 RF-03-050`, CA-06 e `AUT-RF050-01`; `S12 D024` | `DISPONÍVEL`; descarte não equivale a apagar a fonte |

### 9.5 Tipo de derivação

| ID interno | Termo sustentado | Semântica controlada | Detalhe(s) | Fonte | C-F05-09 / limite |
|---|---|---|---|---|---|
| `CAT-DV-001` | original | fonte de origem da cadeia considerada | `DET-PF-03-F20–F21`; `DET-REL-10` | `S14 4L.7 §17` | `DISPONÍVEL` |
| `CAT-DV-002` | cópia | reprodução que aponta à origem e não cria automaticamente evidência material nova | `DET-PF-03-F20–F21`; `DET-REL-10` | `S14 4L.7 §17` | `DISPONÍVEL` |
| `CAT-DV-003` | transformada | fonte resultante de transformação identificada | `DET-PF-03-F20–F21`; `DET-PF-09-F02–F06`; `DET-REL-10/13` | `S14 4L.7 §§3.1, 17` | `DISPONÍVEL`; lógica da transformação não é definida |
| `CAT-DV-004` | convertida | fonte convertida, ainda vinculada à origem | `DET-PF-03-F20–F21`; `DET-REL-10` | `S14 4L.7 §17` | `DISPONÍVEL` |
| `CAT-DV-005` | extrato | recorte derivado cujo escopo precisa ser identificável | `DET-PF-03-F20–F21`; `DET-PF-04-F05–F06`; `DET-REL-10` | `S14 4L.7 §§15, 17` | `DISPONÍVEL`; não presume integralidade |
| `CAT-DV-006` | visual | representação visual derivada, distinta do valor e da fonte oficial | `DET-PF-03-F20–F21`; `DET-PF-03-R01/R03`; `DET-REL-10` | `S08 CA-RF-03-050-02`; `S14 4L.7 §17` | `DISPONÍVEL`; número visual não vira caso funcional |
| `CAT-DV-007` | publicada | versão publicada derivada de fonte identificada | `DET-PF-03-F07/F20–F21`; `DET-REL-10` | `S14 4L.7 §17` | `DISPONÍVEL`; publicação não aprova mérito por si |
| `CAT-DV-008` | exportada | saída exportada que mantém referência à origem | `DET-PF-03-F20–F21`; `DET-REL-10` | `S14 4L.7 §17` | `DISPONÍVEL` |

### 9.6 Qualidade da linhagem

| ID interno | Termo sustentado | Definição controlada | Metadados exigidos | Detalhe(s) | Fonte | C-F05-09 |
|---|---|---|---|---|---|---|
| `CAT-LQ-001` | completa | elo possui cadeia verificável no alcance declarado | nós, relação, evento, momento e responsável | `DET-PF-09-F02–F09/F12–F13`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§40–42` | `DISPONÍVEL` |
| `CAT-LQ-002` | parcial | somente parte da cadeia é demonstrável | ponto de interrupção e justificativa da lacuna | `DET-PF-09-F09–F11`; `DET-PF-09-R01`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§41–42` | `DISPONÍVEL` |
| `CAT-LQ-003` | pendente | elo aguarda elemento identificado da cadeia | ponto de interrupção e justificativa | `DET-PF-09-F09–F11`; `DET-PF-09-R01`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§41–42` | `DISPONÍVEL` |
| `CAT-LQ-004` | indisponível | cadeia ou elemento necessário não está disponível | ponto de interrupção e justificativa | `DET-PF-09-F09–F11`; `DET-PF-09-R01`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§41–42` | `DISPONÍVEL`; não reconstruir |
| `CAT-LQ-005` | divergente | elos ou fontes da cadeia divergem | divergência e ponto correspondente permanecem visíveis | `DET-PF-09-F08–F11`; `DET-PF-09-R01`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§41–42` | `DISPONÍVEL`; nenhuma escolha silenciosa |
| `CAT-LQ-006` | inconsistente | cadeia possui inconsistência identificada | justificativa e evento de registro/correção | `DET-PF-09-F07/F09–F11`; `DET-PF-09-R01`; `DET-REL-13` | `S12 D018/D024`; `S14 4L.7 §§41–42` | `DISPONÍVEL` |
| `CAT-LQ-007` | interrompida | cadeia termina em ponto de interrupção conhecido | ponto de interrupção obrigatório e justificativa | `DET-PF-09-F09–F11`; `DET-PF-09-R01`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§41–42` | `DISPONÍVEL`; inferência proibida |
| `CAT-LQ-008` | N/A | qualidade de linhagem não incide no alcance fundamentado | fundamento verificável; nenhum transporte automático | `DET-PF-09-F09–F11`; `DET-PF-09-R01`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §41` | `PARCIAL/CONDICIONADO` à fonte aplicável |

---

## 10. Catálogo de execução, empresa, temporalidade e nós de linhagem

### 10.1 Natureza de execução do evento

| ID interno | Termo sustentado | Definição controlada | Detalhe(s) | Fonte | C-F05-09 / limite |
|---|---|---|---|---|---|
| `CAT-NE-001` | manual | execução material realizada por pessoa identificável | `DET-PF-05-F20–F24`; `DET-PF-05-R03` | `S14 4L.7 §§6–9` | `DISPONÍVEL`; execução não confere autoridade |
| `CAT-NE-002` | sistêmica | execução técnica realizada por sistema | `DET-PF-05-F20–F24`; `DET-PF-05-R03` | `S12 D024`; `S14 4L.7 §§6–9` | `DISPONÍVEL`; automação decisória não é autorizada |
| `CAT-NE-003` | importada | ocorrência proveniente de importação, distinta da criação nativa | `DET-PF-05-F07/F23–F24/F26/F29–F30`; `DET-PF-05-R03`; `DET-REL-14` | `S14 4L.7 §§6–9` | `DISPONÍVEL`; conteúdo importado não é aprovado automaticamente |
| `CAT-NE-004` | integrada | ocorrência oriunda de integração identificada | `DET-PF-05-F23–F24/F26/F29–F30`; `DET-PF-05-R03`; `DET-REL-14` | `S12 D021`; `S14 4L.7 §§6–9` | `PARCIAL/CONDICIONADO`; contrato, fluxo e reprocessamento ficam excluídos |

### 10.2 Papel da empresa no vínculo transversal

| ID interno | Literal | Definição controlada | Detalhe(s) | Fonte | C-F05-09 / limite |
|---|---|---|---|---|---|
| `CAT-PE-001` | `RESPONSAVEL` | empresa responsável pelo objeto/fato quando a fonte exigir | `DET-PF-06-F02–F04`; `DET-PF-06-R01–R04`; `DET-REL-06` | `S12 D003/D022`; `S14 4L.7 §43` | `DISPONÍVEL`; objetos aplicáveis dependem da fonte de domínio |
| `CAT-PE-002` | `ORIGEM` | empresa de origem preservada, inclusive em visão consolidada | `DET-PF-06-F02–F04`; `DET-PF-06-R02–R04`; `DET-REL-06` | `S12 D003`; `S14 4L.7 §43` | `DISPONÍVEL`; não cria efeito intercompany |

### 10.3 Precisão temporal

| ID interno | Literal | Definição controlada | Representação compatível | Detalhe(s) | Fonte | C-F05-09 |
|---|---|---|---|---|---|---|
| `CAT-PT-001` | `ANO` | precisão limitada ao ano informado | `valor_ano`; não inventar mês, dia ou hora | `DET-PF-07-F04–F09`; `DET-PF-07-R01` | `S13 4L.4 §59` | `DISPONÍVEL` |
| `CAT-PT-002` | `COMPETENCIA_MENSAL` | precisão de ano e mês | `valor_ano` + `valor_mes`; não inventar dia | `DET-PF-07-F04–F09`; `DET-PF-07-R01` | `S13 4L.4 §§5, 59` | `DISPONÍVEL` |
| `CAT-PT-003` | `DATA` | data civil informada | `valor_data`; sem horário fictício | `DET-PF-07-F04–F09`; `DET-PF-07-R01` | `S13 4L.4 §§12, 59–61` | `DISPONÍVEL` |
| `CAT-PT-004` | `DATA_HORA` | data e hora informadas, sem elevar precisão ou inventar fuso | `valor_instante` no limite disponível | `DET-PF-07-F04/F08–F09`; `DET-PF-07-R01` | `S13 4L.4 §§59–60` | `DISPONÍVEL` |
| `CAT-PT-005` | `DATA_HORA_FUSO` | instante com fuso/deslocamento informado | `valor_instante` + fuso/deslocamento preservado | `DET-PF-07-F04/F08–F09`; `DET-PF-07-R01` | `S13 4L.4 §§59–60` | `DISPONÍVEL` |

Ausência de hora não autoriza `00:00`; ausência de data não autoriza `01/01/1900`, `00/00/0000`, data atual ou data de importação. Estimativa somente existe se o RF permitir e exige fundamento e responsável/origem (`DET-PF-07-F10–F12`, `DET-PF-07-R02`), permanecendo `PARCIAL/CONDICIONADO` sem criar novo valor de catálogo.

### 10.4 Tipo de dimensão temporal

| ID interno | Termo sustentado | Distinção preservada | Detalhe(s) | Fonte | C-F05-09 / limite |
|---|---|---|---|---|---|
| `CAT-TD-001` | referência | eixo temporal de referência | `DET-PF-07-F03`; `DET-REL-07/12` | `S12 D017`; `S13 4L.4 §§2, 11` | `DISPONÍVEL`; aplicação por objeto condicionada |
| `CAT-TD-002` | competência | período ao qual o conteúdo compete | `DET-PF-07-F03`; `DET-REL-07/12` | `S12 D017`; `S13 4L.4 §§2, 11` | `DISPONÍVEL`; não se confunde com registro |
| `CAT-TD-003` | previsão | valor temporal previsto, distinto do realizado | `DET-PF-07-F03/F10–F12`; `DET-REL-07` | `S12 D017`; `S13 4L.4 §§2, 11, 62` | `PARCIAL/CONDICIONADO` quando estimado |
| `CAT-TD-004` | vencimento | data/competência de vencimento | `DET-PF-07-F03`; `DET-REL-07` | `S12 D017`; `S13 4L.4 §§2, 11` | `DISPONÍVEL`; regra material excluída |
| `CAT-TD-005` | emissão | momento/data de emissão | `DET-PF-07-F03`; `DET-REL-07` | `S12 D017`; `S13 4L.4 §§2, 11` | `DISPONÍVEL` |
| `CAT-TD-006` | ocorrência | momento/data do fato ou evento | `DET-PF-05-F08–F10`; `DET-PF-07-F03`; `DET-REL-03/07` | `S12 D017`; `S13 4L.4 §§2–4, 11` | `DISPONÍVEL` |
| `CAT-TD-007` | pagamento | eixo temporal de pagamento, sem regra financeira criada | `DET-PF-07-F03`; `DET-REL-07` | `S12 D017`; `S13 4L.4 §§2, 11` | `DISPONÍVEL`; domínio financeiro excluído |
| `CAT-TD-008` | recebimento | eixo temporal de recebimento, sem fluxo criado | `DET-PF-07-F03`; `DET-REL-07` | `S12 D017`; `S13 4L.4 §§2, 11` | `DISPONÍVEL`; domínio financeiro excluído |
| `CAT-TD-009` | registro | momento em que a informação foi registrada | `DET-PF-05-F09–F10`; `DET-PF-07-F03/F13`; `DET-REL-03/07` | `S12 D017/D018`; `S13 4L.4 §§3–4` | `DISPONÍVEL`; não substitui ocorrência |
| `CAT-TD-010` | confirmação | momento da confirmação autorizada | `DET-PF-05-F08–F10/F22`; `DET-PF-07-F03/F14`; `DET-REL-03/07` | `S12 D017/D018`; `S13 4L.4 §§2, 21` | `DISPONÍVEL`; autoridade continua necessária |
| `CAT-TD-011` | alteração | momento da alteração auditável | `DET-PF-05-F08–F10`; `DET-PF-07-F03/F14`; `DET-REL-03/07/09` | `S12 D017/D018`; `S13 4L.4 §§2, 21` | `DISPONÍVEL`; evento anterior preservado |
| `CAT-TD-012` | cancelamento | momento do cancelamento auditável | `DET-PF-05-F08–F10/F31–F32`; `DET-PF-07-F03/F14`; `DET-REL-03/07/09` | `S12 D017/D018`; `S13 4L.4 §§2, 21` | `DISPONÍVEL`; cancelamento não apaga ocorrência |
| `CAT-TD-013` | Data-Base | eixo temporal nominal `Data-Base` preservado como distinto | `DET-PF-07-F03`; `DET-REL-07` | `S12 D017`; `S13 4L.4 §§2, 11` | `DISPONÍVEL`; cálculo ou regra de domínio não criada |

### 10.5 Tipo de nó de linhagem

| ID interno | Termo sustentado | Aplicação controlada | Detalhe(s) | Fonte | C-F05-09 / limite |
|---|---|---|---|---|---|
| `CAT-NO-001` | RN | nó para regra de negócio existente | `DET-PF-09-F02–F06`; `DET-REL-13` | `S02 §10`; `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL`; nenhuma RN criada |
| `CAT-NO-002` | RF | nó para requisito funcional existente | `DET-PF-09-F02–F06`; `DET-REL-13` | `S02 §10`; `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL`; nenhum RF criado |
| `CAT-NO-003` | CA | nó para critério de aceitação existente | `DET-PF-09-F02–F06`; `DET-REL-13` | `S02 §10`; `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL`; nenhum CA criado |
| `CAT-NO-004` | decisão | nó para decisão existente e verificável | `DET-PF-09-F02–F06`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL`; nenhum identificador inferido |
| `CAT-NO-005` | objeto lógico | nó para objeto lógico aprovado | `DET-PF-09-F02–F06`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL`; não cria objeto de domínio |
| `CAT-NO-006` | detalhe candidato | nó para detalhe candidato identificável | `DET-PF-09-F02–F06`; `DET-REL-13` | `S02 §10`; `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL` |
| `CAT-NO-007` | evento | nó para ocorrência PF-05 existente | `DET-PF-09-F02–F07`; `DET-REL-03/09/13` | `S12 D018/D024`; `S14 4L.7 §§3.1, 3.5, 6` | `DISPONÍVEL` |
| `CAT-NO-008` | origem | nó que identifica a origem da cadeia | `DET-PF-09-F02–F06`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL` |
| `CAT-NO-009` | transformação | nó de transformação identificada, sem definir sua lógica | `DET-PF-09-F02–F06`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL`; lógica excluída |
| `CAT-NO-010` | destino | nó que identifica o destino da cadeia | `DET-PF-09-F02–F06`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL` |
| `CAT-NO-011` | relatório | nó para relatório identificável | `DET-PF-09-F02–F06`; `DET-REL-13` | `S12 D024`; `S14 4L.7 §§3.1, 3.5` | `DISPONÍVEL`; não cria relatório novo |
| `CAT-NO-012` | evidência | nó para evidência PF-03/PF-04 identificável | `DET-PF-09-F02–F08`; `DET-REL-04/05/13/14` | `S12 D024`; `S14 4L.7 §§3.1, 3.5, 14–16` | `DISPONÍVEL`; evidência não é fato |
| `CAT-NO-013` | alteração | nó para alteração posterior identificável | `DET-PF-09-F02–F07`; `DET-REL-09/13` | `S12 D018/D024`; `S14 4L.7 §§3.1, 3.5, 10` | `DISPONÍVEL`; não substitui evento tipado |

O campo `tipo_relacao_linhagem` (`DET-PF-09-F06`) continua `PARCIAL/CONDICIONADO`: esta minuta não inventa relações como soma, compensação, deduplicação ou vínculo material. Cada elo exige relação comprovada.

---

## 11. Catálogo de eventos transversais comprovados

### 11.1 Regras comuns a todo evento

Toda entrada `EVT-*` abaixo é uma classe semântica transversal, não código físico universal. Sua ocorrência somente é legítima quando existe objeto ou vínculo aplicável e fonte competente. Cada ocorrência PF-05 deve preservar, conforme incidência: identificador imutável; objeto/vínculo atingido; tipo; instante do evento e do registro quando distintos; antes/depois; autor, executor, autoridade e origem sem fusão; justificativa; fonte/evidência; regra/decisão e versão; correlação; resultado; evento anterior ou substituto.

O executor técnico não adquire autoridade empresarial por executar. Fonte e evidência não se tornam fato, valor, decisão ou aprovação. A ausência de evidência gera lacuna, alerta ou `RD-NP`, jamais evidência fictícia.

### 11.2 Entradas de evento

| ID interno | Evento sustentado | Gatilho/efeito transversal permitido | Metadados distintivos | Detalhe(s) E-ESC-02 | Fonte competente | C-F05-09 / proibição |
|---|---|---|---|---|---|---|
| `EVT-TR-001` | criação | registra o nascimento auditável de objeto ou vínculo já autorizado | identidade, objeto/vínculo, instante, executor, origem e fonte quando exigida | `DET-PF-02-F08`; `DET-PF-04-F07`; `DET-PF-05-F01–F09/F20–F29`; `DET-PF-06-F07`; `DET-PF-09-F07`; `DET-REL-03/04/06/09/13/14` | `S08 RF-03-004`; `S12 D018`; `S14 4L.7 §§5–13` | `PARCIAL/CONDICIONADO`; não cria objeto de domínio |
| `EVT-TR-002` | importação | registra ingresso por importação, distinguindo origem e execução | natureza `importada`, fonte, instante, correlação e resultado aplicável | `DET-PF-05-F07–F09/F23–F30`; `DET-PF-05-R03`; `DET-REL-03/14` | `S14 4L.7 §§6–9`; parcela de `S12 D021` | `PARCIAL/CONDICIONADO`; importar não aprova conteúdo |
| `EVT-TR-003` | registro de informação | registra informação ou situação sem alegar confirmação material | conteúdo antes/depois quando aplicável, executor, fonte e momento de registro | `DET-PF-02-F08`; `DET-PF-05-F08–F17/F21/F26`; `DET-PF-07-F13`; `DET-PF-08-F09`; `DET-PF-09-F07/F12–F13`; `DET-REL-03/07/08/13/14` | `S08 RF-03-004`; `S12 D018`; `S13 4L.4 §§3–4`; `S14 4L.7 §§6, 22` | `PARCIAL/CONDICIONADO`; registro não é aprovação |
| `EVT-TR-004` | confirmação de informação | confirma informação somente por autoridade competente | autoridade, regra/decisão, justificativa, estado/valor/classificação confirmado | `DET-PF-05-F12–F17/F20–F28`; `DET-PF-07-F14`; `DET-REL-03/07/09/14` | `S08 RF-03-004`; `S12 D018`; `S13 4L.4 §21`; `S14 4L.7 §§7, 35` | `PARCIAL/CONDICIONADO`; autoridade material não é criada |
| `EVT-TR-005` | alteração de informação | registra alteração material preservando antes/depois | estado, valor ou classificação anterior/posterior, executor, motivo e fonte | `DET-PF-05-F12–F19/F21/F25–F28/F31`; `DET-PF-07-F14`; `DET-PF-08-F10`; `DET-REL-03/07/08/09/14` | `S08 RF-03-004`; `S12 D018`; `S14 4L.7 §§6, 10` | `PARCIAL/CONDICIONADO`; nenhuma transição de domínio inferida |
| `EVT-TR-006` | correção | nova ocorrência que corrige informação sem sobrescrever a anterior | evento anterior, antes/depois, justificativa, executor/autoridade e fonte | `DET-PF-02-F08`; `DET-PF-05-F12–F32`; `DET-PF-06-F08`; `DET-PF-07-F14`; `DET-PF-08-F10`; `DET-PF-09-F07`; `DET-PF-05-R01–R03`; `DET-REL-09` | `S08 RF-03-004`, CA-02; `S12 D018`; `S14 4L.7 §§10–12` | `PARCIAL/CONDICIONADO`; correção nunca reescreve o original |
| `EVT-TR-007` | cancelamento | nova ocorrência que cancela a aplicabilidade futura sem apagar o histórico | evento anterior/substituto, estado antes/depois, autoridade, justificativa e fonte | `DET-PF-05-F12–F13/F20–F32`; `DET-PF-05-R01–R03`; `DET-REL-09` | `S08 RF-03-004`; `S12 D018`; `S14 4L.7 §§11–12` | `PARCIAL/CONDICIONADO`; efeitos materiais dependem da fonte |
| `EVT-TR-008` | substituição | nova ocorrência que aponta sucessor e preserva o substituído | evento anterior e substituto, correlação, motivo, autoridade e fonte | `DET-PF-03-F07/F12/F20–F21`; `DET-PF-05-F20–F32`; `DET-PF-05-R01–R03`; `DET-REL-09/10` | `S12 D018`; `S14 4L.7 §§11–12, 17–18` | `PARCIAL/CONDICIONADO`; não reutiliza identidade |
| `EVT-TR-009` | desfazimento | nova ocorrência correlata que desfaz efeito autorizado, mantendo a ocorrência original | evento anterior/substituto, antes/depois, autoridade, justificativa e fonte | `DET-PF-04-F07`; `DET-PF-05-F12–F32`; `DET-PF-05-R01–R03`; `DET-REL-09` | `S12 D018`; `S14 4L.7 §§11–13` | `PARCIAL/CONDICIONADO`; efeito de domínio não é definido |
| `EVT-TR-010` | reabertura | nova ocorrência correlata que reabre somente quando regra competente permitir | estado anterior/posterior, autoridade, decisão/regra, justificativa e correlação | `DET-PF-05-F12–F13/F20–F32`; `DET-PF-05-R01–R04`; `DET-REL-09` | `S08 RF-03-004`; `S12 D018`; `S14 4L.7 §§10–12` | `PARCIAL/CONDICIONADO`; não cria reabertura de ciclo de domínio |
| `EVT-TR-011` | criação de vínculo | registra vínculo transversal explicitamente sustentado | vínculo atingido, evento, fonte/evidência, instante e executor | `DET-PF-04-F01–F07`; `DET-PF-06-F01–F07`; `DET-PF-09-F01–F08`; `DET-REL-04–06/12–14` | `S12 D003/D018/D024`; `S14 4L.7 §13` | `PARCIAL/CONDICIONADO`; não inventa cardinalidade ou relação material |
| `EVT-TR-012` | alteração de vínculo | registra nova configuração sem apagar o vínculo anterior | vínculo anterior/posterior, evento anterior, motivo, fonte e autoridade quando exigida | `DET-PF-04-F04–F08`; `DET-PF-05-F18–F19/F31`; `DET-PF-06-F05–F09`; `DET-PF-09-F03–F08`; `DET-REL-05/06/09/12/13` | `S12 D003/D018/D024`; `S14 4L.7 §13` | `PARCIAL/CONDICIONADO`; aplicabilidade depende da fonte |
| `EVT-TR-013` | retirada ou desfazimento de vínculo | registra retirada por nova ocorrência, conservando vínculo retirado no histórico | vínculo anterior, evento correlato, motivo, autoridade e evidência | `DET-PF-04-F07–F08`; `DET-PF-05-F18/F31–F32`; `DET-PF-06-F08`; `DET-PF-09-F07`; `DET-REL-05/06/09/13` | `S12 D018/D024`; `S14 4L.7 §§11–13` | `PARCIAL/CONDICIONADO`; retirada não apaga o elo histórico |
| `EVT-TR-014` | aprovação de prática | registra decisão expressa que conduz `OBSERVADA` a `APROVADA` | decisão de prática, autoridade, finalidade, justificativa, fonte e antes/depois | `DET-PF-03-F13–F14/F17–F19`; `DET-PF-03-R02`; `DET-PF-05-F12–F17/F20–F28/F31`; `DET-REL-09/11/14` | `S08 RF-03-050`, CA-06 e `AUT-RF050-01`; `S12 D024` | `PARCIAL/CONDICIONADO`; este documento não profere decisão |
| `EVT-TR-015` | descarte de prática | registra decisão expressa que conduz `OBSERVADA` a `DESCARTADA` | mesmos metadados da aprovação; fonte observada permanece histórica | `DET-PF-03-F13–F14/F17–F19`; `DET-PF-03-R02`; `DET-PF-05-F12–F17/F20–F28/F31`; `DET-REL-09/11/14` | `S08 RF-03-050`, CA-06 e `AUT-RF050-01`; `S12 D024` | `PARCIAL/CONDICIONADO`; não apaga nem transforma prática em regra |

Não foram catalogados como eventos: cálculo, conciliação, pagamento, recebimento, faturamento, oportunidade, projeto, contrato, rateio, distribuição, tributo, contabilização, migração, reprocessamento ou qualquer outra ocorrência material de domínio. A presença de palavras semelhantes em fontes arquiteturais não autoriza sua incorporação nesta unidade.

---

## 12. Passagens expressamente sustentadas e ausência de máquina de estados

| ID | Origem | Evento/condição exigida | Destino | Detalhe(s) | Fonte | Limite vinculante |
|---|---|---|---|---|---|---|
| `TR-QD-001` | `INCOMPLETO` | resolução/alteração comprovada do dado obrigatório, registrada por evento | `COMPLETO` | `DET-PF-08-F04/F09–F10`; `DET-PF-08-R01/R04/R07`; `DET-REL-08/09` | `S08 RF-03-001`; `S12 D018` | `COMPLETO` não gera linha PF-08 ativa |
| `TR-QD-002` | `INCOMPLETO` | pendência identificada com motivo, responsável e data | `PENDENTE` | `DET-PF-08-F04–F07/F09–F10`; `DET-PF-08-R02/R04/R07`; `DET-REL-08/09` | `S08 RF-03-001`, CA-03; `S09`; `S11` | não autoriza passagem sem metadados |
| `TR-QD-003` | `PENDENTE` | requalificação registrada, preservando a ocorrência anterior | `INCOMPLETO` | `DET-PF-08-F04–F07/F09–F10`; `DET-PF-08-R02/R04/R07`; `DET-REL-08/09` | `S08 RF-03-001` (`INCOMPLETO ↔ PENDENTE`); `S12 D018` | não implica passagem direta a `COMPLETO` |
| `TR-QD-004` | `INCOMPLETO` | RF aplicável admite N/A, com fundamento e evento | `NAO_APLICAVEL` | `DET-PF-08-F04/F08–F10`; `DET-PF-08-R03/R05/R07`; `DET-REL-08/09` | `S08 RF-03-001`, `VAL-RF001-04`; `S09`; `S11` | aplicação ao domínio permanece condicionada |
| `TR-FC-001` | `CLASSIFICACAO_PENDENTE` | classificação por evento auditável, com ator, data, finalidade e justificativa quando aplicável | `CLASSIFICADA` | `DET-PF-03-F11`; `DET-PF-05-F16–F17/F20–F31`; `DET-REL-03/09/14` | `S08 RF-03-050`; `S14 4L.7 §§6, 10` | classificar não aprova conteúdo |
| `TR-PR-001` | `OBSERVADA` | decisão expressa competente + `EVT-TR-014` | `APROVADA` | `DET-PF-03-F13–F14/F19`; `DET-PF-03-R02`; `DET-PF-05-F12–F17/F20–F31`; `DET-REL-09/14` | `S08 RF-03-050`, CA-06 e `AUT-RF050-01`; `S12 D024` | promoção automática proibida |
| `TR-PR-002` | `OBSERVADA` | decisão expressa competente + `EVT-TR-015` | `DESCARTADA` | `DET-PF-03-F13–F14/F19`; `DET-PF-03-R02`; `DET-PF-05-F12–F17/F20–F31`; `DET-REL-09/14` | `S08 RF-03-050`, CA-06 e `AUT-RF050-01`; `S12 D024` | descarte não apaga a observação |

São sete linhas de passagem porque a relação bidirecional `INCOMPLETO ↔ PENDENTE` foi atomizada em dois sentidos; o conteúdo-fonte continua formado por seis regras expressas: três regras de qualidade (`→ COMPLETO`, `↔ PENDENTE`, `→ NAO_APLICAVEL`), uma de classificação e duas de prática.

Nenhuma passagem foi definida para disponibilidade da fonte, qualidade da linhagem, situação de conflito, vigência, situação de vínculo, resultado do evento ou domínio material. Alterações nesses pontos dependem da fonte competente, devem ser auditáveis quando aplicáveis e permanecem `PARCIAL/CONDICIONADO`. Este quadro é um inventário de regras expressas, não uma máquina de estados.

---

## 13. Matriz de aplicabilidade por objeto e detalhe

| Objeto corrente | Entradas aplicáveis | Detalhes de aplicação e suporte | Resultado C-F05-09 |
|---|---|---|---|
| `PF-01 — ESC01_OBJETO_IDENTIDADE` | `CAT-OP-001/004`; `EVT-TR-001/003–010`; `CAT-NO-005/007/013` | `DET-PF-01-F01–F06/R01–R04`; `DET-PF-05-F03–F05/F07/F12–F32`; `DET-REL-01/03/09/13` | identidade e preservação histórica disponíveis; `situacao_vigencia`, formato de ID e aplicação de evento permanecem condicionados |
| `PF-02 — ESC01_REFERENCIA_EXTERNA` | `CAT-OP-001/002/004`; `EVT-TR-001/003/005–006`; `CAT-NO-008/012` | `DET-PF-02-F01–F09/R01`; `DET-PF-04-F01–F08`; `DET-PF-05-F06–F07/F18–F19`; `DET-REL-02/04/05/14` | referência qualificada disponível; tipo, cardinalidade, unicidade e situação concreta condicionados |
| `PF-03 — ESC01_FONTE_EVIDENCIA` | `CAT-NF-*`; `CAT-FC-*`; `CAT-DF-*`; `CAT-PR-*`; `CAT-DV-*`; `CAT-OP-002/004`; `EVT-TR-003–010/014–015`; `CAT-NO-008/012/013` | `DET-PF-03-O/F01–F21/R01–R06`; `DET-PF-05-F07/F12–F32`; `DET-REL-04/09–11/14` | catálogos expressos disponíveis; finalidade, conflito, precedência, integridade e aplicação permanecem limitados/condicionados |
| `PF-04 — ESC01_VINCULO_EVIDENCIA` | `CAT-DF-*` quando a fonte vinculada o portar; `EVT-TR-011–013`; `CAT-OP-001/002/004`; `CAT-NO-012` | `DET-PF-04-O/F01–F08/R01–R02`; `DET-PF-05-F06/F18–F19/F31–F32`; `DET-REL-04/05/09/14` | vínculo explícito disponível; tipo de elemento e situação física do vínculo condicionados |
| `PF-05 — ESC01_EVENTO_AUDITORIA` | `CAT-NE-*`; `CAT-OP-*`; `EVT-TR-001–015`; pares antes/depois de `CAT-QD-*`, `CAT-FC-*`, `CAT-PR-*`; resultado `CAT-OP-003` | `DET-PF-05-O/F01–F33/R01–R06`; `DET-REL-03/09/14` | metamodelo de evento disponível; catálogo físico universal, resultado concreto, papéis e tecnologia condicionados |
| `PF-06 — ESC01_VINCULO_EMPRESARIAL` | `CAT-PE-*`; `CAT-TD-*` quando houver vigência; `EVT-TR-011–013`; `CAT-OP-004` | `DET-PF-06-O/F01–F09/R01–R04`; `DET-REL-06/09/12` | segregação e papéis do núcleo disponíveis; aplicabilidade, cardinalidade e sobreposição por domínio condicionadas |
| `PF-07 — ESC01_DIMENSAO_TEMPORAL` | `CAT-PT-*`; `CAT-TD-*`; `EVT-TR-003–006`; `CAT-OP-004` | `DET-PF-07-O/F01–F14/R01–R02`; `DET-PF-05-F08–F11`; `DET-REL-07/09/12` | eixos e precisões disponíveis; estimativa, vigência e regra material condicionadas |
| `PF-08 — ESC01_ESTADO_PREENCHIMENTO` | `CAT-QD-*`; `CAT-VA-*`; `CAT-OP-*`; `EVT-TR-003/005–006`; `TR-QD-*` | `DET-PF-08-O/F01–F10/R01–R08`; `DET-PF-05-F12–F17/F25/F31`; `DET-REL-08/09` | semântica de qualidade/ausência disponível; incidência do RF de domínio condicionada |
| `PF-09 — ESC01_LINHAGEM` | `CAT-LQ-*`; `CAT-NO-*`; `CAT-OP-002/004`; `EVT-TR-003/005–006/011–013`; `CAT-DV-003` | `DET-PF-09-O/F01–F13/R01–R03`; `DET-REL-09/13` | tipos de nó e qualidades disponíveis; tipo de relação, índices e vínculo material condicionados |

Esta matriz não altera o estado dos objetos de E-ESC-01. Ela apenas relaciona as 98 entradas ao universo corrente.

---

## 14. Rastreabilidade bidirecional

### 14.1 Entrada → detalhe → fonte

As tabelas dos §§8–11 constituem a direção principal. Cada uma das 98 entradas contém: identificador interno; termo sustentado; definição; detalhe(s) E-ESC-02; fonte competente; classificação/limite C-F05-09. Nenhuma entrada existe sem detalhe e fonte indicados.

| Grupo | IDs | Qtde. | Detalhes centrais | Fontes centrais |
|---|---|---:|---|---|
| qualidade do dado | `CAT-QD-001–004` | 4 | PF-08; PF-05; REL-08/09 | `S08`, `S09`, `S11`, `S12` |
| valor e ausência | `CAT-VA-001–004` | 4 | PF-08; REL-08 | `S08`, `S09`, `S11` |
| operação não bloqueante | `CAT-OP-001–004` | 4 | PF-01/03/04/05/06/08/09; relações correlatas | `S08`, `S09`, `S11`, `S12`, `S14` |
| natureza/classificação/disponibilidade/prática da fonte | `CAT-NF-001–004`, `CAT-FC-001–002`, `CAT-DF-001–009`, `CAT-PR-001–003` | 18 | PF-03; PF-04; PF-05; REL-04/09–11/14 | `S08`, `S09`, `S12`, `S14` |
| derivação | `CAT-DV-001–008` | 8 | PF-03; PF-04; PF-09; REL-10/13 | `S08`, `S14` |
| qualidade de linhagem | `CAT-LQ-001–008` | 8 | PF-09; REL-13 | `S12`, `S14` |
| natureza de execução | `CAT-NE-001–004` | 4 | PF-05; REL-14 | `S12`, `S14` |
| papel empresarial | `CAT-PE-001–002` | 2 | PF-06; REL-06 | `S12`, `S14` |
| precisão temporal | `CAT-PT-001–005` | 5 | PF-07 | `S13` |
| dimensão temporal | `CAT-TD-001–013` | 13 | PF-05; PF-07; REL-07/12 | `S12`, `S13`, `S14` |
| tipo de nó | `CAT-NO-001–013` | 13 | PF-09; REL-13 | `S02`, `S12`, `S14` |
| eventos transversais | `EVT-TR-001–015` | 15 | PF-02/03/04/05/06/07/08/09; REL-03–14 aplicáveis | `S08`, `S12`, `S13`, `S14` |
| **Total** |  | **98** | nenhum detalhe criado | nenhuma fonte inferida |

### 14.2 Detalhe → entrada

| Origem no universo 182 | Retorno ao catálogo |
|---|---|
| 29 campos catalogáveis | retornam às entradas identificadas nas tabelas dos §§8–11 ou aos pontos condicionados do §15 |
| 94 campos de suporte | retornam como identidade, metadado, referência, autoridade, motivo, tempo, fonte, evidência, versão ou correlação nas mesmas tabelas; não são convertidos em novos estados |
| 28 regras aplicáveis | retornam como requisito de preservação, entrada, saída, metadado ou proibição nos §§8–12 |
| 8 limites condicionados | retornam ao §15; nenhum recebeu conteúdo inferido |
| 9 objetos | retornam à matriz de aplicabilidade do §13 |
| 9 relações disponíveis | retornam às colunas de detalhe e aplicabilidade dos §§8–13 |
| 5 relações condicionadas | retornam ao §15; nenhuma cardinalidade ou semântica material foi fechada |

A enumeração exata dos identificadores de cada classe está no §7.2. Assim, qualquer detalhe permite localizar sua função no catálogo sem pressupor que todo detalhe de suporte deva virar entrada semântica.

### 14.3 Fonte → entrada → detalhe

| Fonte | Entradas alcançadas | Detalhes alcançados | Resultado |
|---|---|---|---|
| `S02` | `CAT-NO-*` nos tipos nominalmente previstos e limites C-F05-09 | PF-09; relações de linhagem; restrições condicionadas | vínculo preservado; não cria tipo adicional |
| `S08` | `CAT-QD-*`, `CAT-VA-*`, `CAT-OP-*`, `CAT-NF-*`, `CAT-FC-*`, `CAT-PR-*`, parcelas `CAT-DV-*`, `EVT-TR-*`, `TR-*` | PF-01/02/03/05/06/08/09 e relações rastreadas | mérito funcional primário |
| `S09` | qualidade/ausência, fonte/prática e cobertura RN–RF já existente | PF-03/PF-08 e restrições correspondentes | baseline de rastreabilidade; nenhuma RN nova |
| `S11` | decisões funcionais que sustentam zero, pendência, N/A, inexistência e leitura não bloqueante | PF-05/PF-08 | cobertura sem RN própria |
| `S12` | `CAT-OP-*`, `CAT-DF-*`, `CAT-LQ-*`, `CAT-NE-*`, `CAT-PE-*`, `CAT-TD-*`, `CAT-NO-*`, `EVT-TR-*` | PF-01/03–09; REL-01/03–14 aplicáveis | decisões D003/D017/D018/D021/D022/D023/D024, só no limite autorizado |
| `S13` | `CAT-PT-*`, `CAT-TD-*`, suporte de identidade/versão | PF-01/PF-05/PF-06/PF-07; REL-01/07/12 | sem regra temporal de domínio |
| `S14` | `CAT-DF-*`, `CAT-DV-*`, `CAT-LQ-*`, `CAT-NE-*`, `CAT-NO-*`, `EVT-TR-*`, limites de resultado/vínculo | PF-02–09; relações aplicáveis | mérito arquitetural transversal 4L.7; sem catálogo físico universal |
| `S01-A/S01-B/S01-C`, `S03–S07`, `S10`, `S15–S22` | nenhuma entrada de mérito autônoma | governança, identidade, corte, histórico, limites, inventário e confirmação negativa dos 182 detalhes | 17 códigos preservados; ausência de entrada nova não equivale a omissão |

Os grupos acima cobrem os 24 códigos: sete com contribuição semântica direta e dezessete com função de governança, suporte ou limite. A contagem e os 387 vínculos originais de E-ESC-02 não são reescritos por esta síntese.

---

## 15. Pontos parciais, condicionados e excluídos por C-F05-09

### 15.1 Catálogos ou aplicações não fechados

| # | Ponto condicionado | Detalhe(s) | Razão documental | Efeito desta minuta |
|---:|---|---|---|---|
| 1 | `situacao_vigencia` e estados de vigência por objeto | `DET-PF-01-F06`; `DET-PF-06-F05–F06`; `DET-REL-12` | somente se a fonte do objeto sustentar; não há catálogo transversal universal | nenhuma entrada de vigência criada |
| 2 | tipo e situação de referência externa | `DET-PF-02-F03/F09`; `DET-PF-02-R01`; `DET-REL-02` | emissor, domínio, cardinalidade e unicidade não fechados | referência continua condicionada |
| 3 | finalidade da fonte, conflito e precedência concreta | `DET-PF-03-F04/F15–F19`; `DET-PF-03-R03–R05`; `DET-REL-11` | dependem do mesmo modelo, finalidade e decisão competente | nenhuma finalidade, conflito ou precedência inferida |
| 4 | integridade, assinatura, certificado, retenção e repositório | `DET-PF-03-F06`; `DET-PF-03-R06`; `DET-PF-05-R05` | tecnologia e política fora da unidade | nenhum mecanismo criado |
| 5 | tipo de elemento, finalidade e situação física do vínculo de evidência | `DET-PF-04-F03/F05/F08`; `DET-PF-04-R02`; `DET-REL-05` | catálogo e materialidade dependem do elemento sustentado | somente eventos genéricos de vínculo catalogados |
| 6 | catálogo físico universal de `tipo_evento` | `DET-PF-05-F07`; `DET-PF-05-R04` | a fonte proíbe catálogo universal | `EVT-TR-*` são classes documentais condicionadas |
| 7 | catálogo concreto de `resultado_evento` | `DET-PF-05-F30`; `DET-PF-05-R06` | resultado depende do evento; integração não aprova conteúdo | somente `RD-NP` preservado como resultado transversal expresso |
| 8 | modelo de autor, executor, autoridade e origem | `DET-PF-05-F20–F24`; `DET-PF-05-R03` | referências genéricas; papéis materiais dependem de fonte própria | distinção preservada, modelo não criado |
| 9 | catálogo e tratamento de alerta/pendência | `DET-PF-05-F33`; `DET-PF-05-R06` | somente referência a item existente | `AD-NB` preservado; critérios concretos excluídos |
| 10 | objetos sujeitos a papel empresarial, cardinalidade e sobreposição | `DET-PF-06-F02–F06`; `DET-PF-06-R04`; `DET-REL-06/12` | aplicação por domínio e C-F05-05 | somente `RESPONSAVEL`/`ORIGEM` preservados |
| 11 | indicador e uso de estimativa | `DET-PF-07-F10–F12`; `DET-PF-07-R02` | RF do objeto deve admitir estimativa | nenhum novo valor criado |
| 12 | incidência de branco permitido e N/A | `DET-PF-08-F04/F08`; `DET-PF-08-R03/R05` | depende do RF aplicável | sem transporte entre módulos |
| 13 | tipo de relação de linhagem | `DET-PF-09-F06`; `DET-PF-09-R02`; `DET-REL-13` | somente relação comprovada; vínculo material não pode ser inferido | nenhum catálogo de relação criado |
| 14 | índices, consulta e navegação física inversa | `DET-PF-09-R03`; `DET-REL-13` | escolha tecnológica futura | navegabilidade sem implementação |
| 15 | representação de valor anterior/posterior | `DET-PF-05-F14–F15` | tipo material do domínio não é definido aqui | somente exigência de antes/depois preservada |
| 16 | metadados de integração e deduplicação | `DET-PF-05-F29–F30`; `DET-PF-09-F06`; parcelas D021/D023 | só núcleo de origem, destino, lote, momento, resultado e identidade/granularidade | contrato, fluxo, reprocessamento, fórmula e consolidação excluídos |

### 15.2 Exclusões integrais

| Matéria excluída | Resultado obrigatório |
|---|---|
| estados, eventos, resultados, transições e máquinas de estado de oportunidade, projeto, proposta, contrato, orçamento, faturamento, finanças, distribuição, remuneração, contabilidade, tributação, atuária ou outro domínio | **ZERO ENTRADA CRIADA** |
| fluxos materiais 4A–4H; arquitetura física preexistente 4I automaticamente adotada; implementação de 4J; contratos, fluxos, ferramentas e reprocessamento 4K | **EXCLUÍDOS** |
| fórmulas, consultas, cálculos, arredondamentos, saldos, rateios, dupla contagem material, consolidação e efeitos intercompany | **EXCLUÍDOS** |
| papéis e autoridades materiais além das referências genéricas do evento | **EXCLUÍDOS** |
| dados reais/legados, migração, limpeza, carga e reconciliação operacional | **EXCLUÍDOS** |
| log, retenção, assinatura, criptografia, acesso, observabilidade, backup, restauração e desempenho | **EXCLUÍDOS** |
| arquivo operacional, planilha, tabela, consulta, banco, SQL, DDL, script, API, integração ou código | **EXCLUÍDOS** |
| teste, homologação, piloto, implantação, operação e compra/configuração tecnológica | **EXCLUÍDOS** |
| mérito de qualquer E-ESC v0.1 histórico | **EXCLUÍDO** |
| qualquer entrada sem regra, fonte ou validação disponível | **CONDICIONADA OU EXCLUÍDA; NUNCA INFERIDA** |

Exclusão não equivale a descarte, resolução, aceitação de risco ou encerramento de pendência.

---

## 16. Reconciliação do inventário 67/67

| Faixa fechada herdada de S16 | Quantidade | Tratamento nesta unidade |
|---|---:|---|
| `4M4-R001–4M4-R024` | 24 | estados e efeitos preservados; nenhuma mitigação material ou reclassificação |
| `4M5-P001–4M5-P017` | 17 | estados e destinos preservados; P010 somente com qualificação já aceita |
| `4M5-I001–4M5-I006` | 6 | implementação continua não iniciada |
| `4M5-D001–4M5-D008` | 8 | dependências preservadas; nenhum portão superado |
| `4M5-G001–4M5-G006` | 6 | lacunas preservadas; G003 não é encerrada por este catálogo documental |
| `4M5-L001–4M5-L006` | 6 | limitações preservadas |
| **Total** | **67** | **67 IDs únicos; 0 omitido; 0 adicionado; 0 estado alterado** |

| Item especial | Estado corrente preservado | Efeito nesta unidade |
|---|---|---|
| `PEN-AUD-013` | **RESOLVIDA — TRATAMENTO FUNCIONAL FORMALIZADO, SEM CRIAÇÃO DE NOVA RN** | sustenta as semânticas PF-08 já aprovadas; nenhuma RN criada |
| `4M5-P010` | **RESOLVIDA EXCLUSIVAMENTE QUANTO À FONTE/PROVENIÊNCIA DE PEN-AUD-013** | permanece no universo 67/67; nenhuma outra lacuna é reclassificada |
| `4M5-G003` | ausência de catálogo físico definitivo para implementação | este catálogo é documental e candidato; a lacuna física não é declarada encerrada |
| `4M5-G005` | ausência de validação final dos entregáveis | esta minuta depende de aceite e não substitui E-ESC-04 |

---

## 17. Preservação de C-F05-05 e portões

| Controle | Estado preservado |
|---|---|
| `C-F05-05` | **PARCIALMENTE ATENDIDA — NÃO DECLARADA SATISFEITA** |
| verificação especializada de fórmulas, arredondamentos, vínculos, bordas, contratos, imagens e integrações | não realizada; fora da unidade |
| `C-F05-09` | aplicado a cada entrada e ponto candidato nos §§8–15 |
| inventário | 67/67, sem alteração de estado |
| `PT-*` | nenhum avaliado ou reavaliado |
| mapeamento lógico-físico | não fechado |
| ESC-F05-01 | não concluído |

O catálogo documental não substitui a futura conferência especializada e não autoriza implementação.

---

## 18. Conferência unitária de UT-F05-01-04

### 18.1 Critérios cumulativos de aceitação

| # | Critério da proposta aceita | Resultado | Evidência nesta minuta |
|---:|---|---|---|
| 1 | linha mestre v0.17/v0.21/v0.16 usada sem alteração | **CONFORME** | §§4.1, 17 e 19 |
| 2 | E-ESC-01 v0.2 exato, 79.275 bytes e hash registrado | **CONFORME** | §4.1 |
| 3 | E-ESC-02 v0.2 exato, 84.727 bytes e hash registrado | **CONFORME** | §4.1 |
| 4 | E-ESC-03 v0.1 somente como identidade/proveniência histórica | **CONFORME** | §4.2 |
| 5 | produção exclusiva da nova minuta E-ESC-03 v0.2 | **CONFORME** | §§1 e 19 |
| 6 | exame integral dos 182 detalhes correntes | **CONFORME** | §7: 182/182 |
| 7 | detalhes pertinentes e não geradores de entrada explicitados | **CONFORME** | §§7.2–7.3 e 14.2 |
| 8 | distinção entre estado, valor, ausência, classificação, situação, resultado e evento | **CONFORME** | §6.1; §§8–12 |
| 9 | zero conhecido preservado como valor | **CONFORME** | `CAT-VA-002` |
| 10 | inexistência preservada como não estado, sem registro vazio | **CONFORME** | `CAT-VA-004` |
| 11 | pendência e N/A com metadados exigidos | **CONFORME** | `CAT-QD-002/003`; §12 |
| 12 | eventos limitados aos documentalmente comprovados | **CONFORME** | 15 entradas `EVT-TR-*`, §11 |
| 13 | nenhum estado ou evento de domínio criado | **CONFORME** | §§11.2, 15.2 e 19 |
| 14 | nenhuma transição automática ou máquina de estados inferida | **CONFORME** | §12: somente regras expressas; automação vedada |
| 15 | aplicabilidade por objeto/detalhe comprovada ou condicionada | **CONFORME** | §13 |
| 16 | correção e sucessão preservam ocorrência anterior | **CONFORME** | `EVT-TR-006–010`; REL-09 |
| 17 | autor, executor, autoridade e origem distintos | **CONFORME** | §§10.1 e 11.1; PF-05-R03 |
| 18 | fonte/evidência distintas de fato, valor, decisão e aprovação | **CONFORME** | §§9, 11.1 e 15 |
| 19 | rastreabilidade bidirecional entrada↔detalhe↔fonte | **CONFORME** | §§8–14 |
| 20 | nenhum vínculo preenchido por analogia ou inferência | **CONFORME** | §§2, 7.3, 12 e 15 |
| 21 | toda lacuna condicionada ou excluída | **CONFORME** | §15 |
| 22 | C-F05-09 aplicada a cada entrada candidata | **CONFORME** | coluna própria nos §§8–11; §§15 e 17 |
| 23 | C-F05-05 preservada como parcialmente atendida | **CONFORME** | §17 |
| 24 | inventário 67/67 sem alteração de estados | **CONFORME** | §16 |
| 25 | PEN-AUD-013 preservada sem nova RN | **CONFORME** | §16 |
| 26 | 4M5-P010 somente quanto à fonte/proveniência | **CONFORME** | §16 |
| 27 | nenhuma RN, RF, CA ou arquitetura criada/alterada | **CONFORME** | §§3.3, 15.2 e 19 |
| 28 | nenhum E-ESC-04 criado | **CONFORME** | §§3.3 e 19 |
| 29 | nenhum `PT-*` avaliado | **CONFORME** | §17 |
| 30 | nenhum mapeamento lógico-físico fechado | **CONFORME** | §17 |
| 31 | nenhuma implementação realizada | **CONFORME** | §§15.2, 17 e 19 |
| 32 | nenhum identificador DEC inferido | **CONFORME** | §3.1 |
| 33 | produto apresentado como minuta não publicada | **CONFORME** | §§1 e 20 |
| 34 | parada imediata após a apresentação | **CONFORME, SUJEITO À PARADA EXTERNA** | §20 e apresentação no Chat 91D |

### 18.2 Controles quantitativos e negativos

| Controle | Esperado | Observado | Resultado |
|---|---:|---:|---|
| entradas catalogadas | somente as sustentadas | 98 | **CONFORME** |
| regras-fonte de passagem | somente as expressas | 6 regras; 7 linhas após atomizar `↔` | **CONFORME** |
| objetos examinados | 9 | 9 | **CONFORME** |
| campos examinados | 123 | 123 | **CONFORME** |
| restrições examinadas | 36 | 36 | **CONFORME** |
| relações examinadas | 14 | 14 | **CONFORME** |
| detalhes examinados | 182 | 182 | **CONFORME** |
| códigos de fonte examinados | 24 | 24 | **CONFORME** |
| vínculos diretos examinados | 387 | 387 | **CONFORME** |
| itens do inventário | 67 | 67 | **CONFORME** |
| estados/eventos de domínio criados | 0 | 0 | **CONFORME** |
| máquinas/fluxos de estado criados | 0 | 0 | **CONFORME** |
| RN/RF/CA/decisões arquiteturais criadas ou alteradas | 0 | 0 | **CONFORME** |
| objetos/campos/restrições/relações criados ou alterados | 0 | 0 | **CONFORME** |
| registros mestres alterados | 0 | 0 | **CONFORME** |
| `PT-*` avaliados | 0 | 0 | **CONFORME** |
| implementações | 0 | 0 | **CONFORME** |
| outros produtos criados | 0 | 0 | **CONFORME** |

### 18.3 Resultado unitário

`UT-F05-01-04 — CONFORME NO LIMITE DOCUMENTAL AUTORIZADO — E-ESC-03 v0.2 PREPARADO EM MINUTA — NÃO PUBLICADO — AGUARDANDO ACEITE EXPRESSO`.

Esse resultado não conclui ESC-F05-01, não satisfaz C-F05-05, não fecha o mapeamento lógico-físico e não inicia atividade posterior.

---

## 19. Ausência de efeitos não autorizados

| Efeito potencial | Resultado verificado |
|---|---|
| alteração de E-ESC-01 ou E-ESC-02 | não ocorreu |
| uso de mérito de E-ESC-03 v0.1 | não ocorreu |
| publicação ou renomeação desta minuta | não ocorreu |
| criação ou publicação de E-ESC-04 | não ocorreu |
| alteração de REG-CONSOLIDACAO, REG-DECISOES ou REG-PENDENCIAS | não ocorreu |
| atribuição de novo identificador DEC | não ocorreu |
| criação/alteração de RN, RF, CA, objeto, campo, restrição, relação ou arquitetura | não ocorreu |
| criação de estado, evento, resultado, transição, fluxo ou máquina de domínio | não ocorreu |
| avaliação de `PT-*` | não ocorreu |
| fechamento do mapeamento lógico-físico | não ocorreu |
| conclusão de ESC-F05-01 | não ocorreu |
| construção, implementação, teste, homologação, implantação ou operação | não ocorreu |
| início de unidade posterior | não ocorreu |

---

## 20. Estado final e critério de parada

| Elemento | Estado após esta execução |
|---|---|
| UT-F05-01-04 | executada somente no limite documental autorizado; conferência unitária conforme; aguardando aceite do resultado |
| E-ESC-03 v0.2 | minuta preparada; não publicada; aguardando aceite expresso |
| E-ESC-03 v0.1 | histórica, não vigente, não publicada e preservada sem uso de mérito |
| E-ESC-01 v0.2 | publicado, aceito, vigente no limite de UT-F05-01-02 e inalterado |
| E-ESC-02 v0.2 | publicado, aceito, vigente no limite de UT-F05-01-03 e inalterado |
| E-ESC-04 | não criado |
| linha mestre | v0.17/v0.21/v0.16 inalterada |
| C-F05-05 | parcialmente atendida |
| C-F05-09 | aplicada no limite desta unidade |
| inventário | 67/67 preservado |
| PEN-AUD-013 | resolvida sem nova RN |
| 4M5-P010 | resolvida somente quanto à fonte/proveniência |
| `PT-*` | não avaliados |
| mapeamento lógico-físico | não encerrado |
| ESC-F05-01 | não concluído |
| implementação | não iniciada |
| identificador DEC da autorização | não atribuído |

Ponto de parada: apresentar exclusivamente esta minuta, seu nome físico, tamanho, SHA-256 e a conferência unitária no Chat 91D; em seguida, **parar imediatamente e aguardar aceite expresso**.

Nenhuma publicação, alteração, continuidade executiva ou nova unidade decorre automaticamente desta minuta ou de sua apresentação.