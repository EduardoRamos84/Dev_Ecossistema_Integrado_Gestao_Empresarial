# E6-02 — RELATÓRIO DE AVALIAÇÃO DOCUMENTAL DE PT-DOC-01 E PT-ESC-01

## 1. Controle do documento

| Campo | Valor |
|---|---|
| Projeto | `Dev_Ecossistema_Integrado_Gestao_Empresarial` |
| Fase | `FASE 05 — PROJETO FÍSICO, CONSTRUÇÃO, TESTES E IMPLANTAÇÃO` |
| Escopo | `ESC-F05-06 — AVALIAÇÃO DOCUMENTAL CONTROLADA DOS PORTÕES PT-DOC-01, PT-ESC-01, PT-FUN-01 E PT-ARQ-01` |
| Unidade | `UT-F05-06-02 — AVALIAÇÃO DOCUMENTAL DE PT-DOC-01 E PT-ESC-01` |
| Produto | `E6-02 — RELATÓRIO DE AVALIAÇÃO DOCUMENTAL DE PT-DOC-01 E PT-ESC-01` |
| Versão | `v0.1` |
| Data documental | `2026-09-19` |
| Responsável humano do escopo | `Eduardo Andrade Ramos` |
| Estado | `MINUTA DOCUMENTAL — AGUARDANDO ACEITE — UT-F05-06-02 INICIADA E NÃO CONCLUÍDA` |
| Natureza | avaliação exclusivamente documental, separada e não autoexecutável de dois portões |
| Linha mestre vigente | `v0.21/v0.25/v0.20` — preservada e inalterada |

---

## 2. Autoridade, autorização e limites

Este produto decorre de atos humanos expressos e separados que:

1. aceitaram `E6-01 v0.1` e o resultado de sua publicação;
2. autorizaram a conclusão de `UT-F05-06-01`;
3. escolheram a Alternativa A apresentada após essa conclusão;
4. autorizaram o início de `UT-F05-06-02`;
5. autorizaram a produção de `E6-02`.

A execução permite exclusivamente:

1. delimitar o corpus documental aplicável;
2. avaliar individualmente `DOC-01` a `DOC-08`;
3. delimitar os escopos e unidades aplicáveis;
4. avaliar individualmente `ESC-01` a `ESC-08`;
5. propor, separadamente, o estado de `PT-DOC-01` e de `PT-ESC-01`;
6. registrar evidências, ressalvas, lacunas, riscos e decisões humanas ainda necessárias.

A execução não permite:

1. aceitar ou publicar automaticamente esta minuta;
2. concluir automaticamente `UT-F05-06-02`;
3. iniciar `UT-F05-06-03`, `UT-F05-06-04` ou `UT-F05-06-05`;
4. produzir `E6-03`, `E6-04` ou `E6-05`;
5. avaliar `PT-FUN-01` ou `PT-ARQ-01`;
6. converter os resultados propostos em decisão oficial sem aceite humano;
7. declarar `C-F05-05` integralmente atendida;
8. reclassificar qualquer dos 149 ou dos 33 detalhes;
9. alterar `33/33 em TRT-04`, `zero TRT-05`, `ALT-04` ou `C-F05-09`;
10. encerrar o mapeamento lógico-físico;
11. alterar o inventário fechado de 67 itens;
12. criar, alterar, encerrar ou renumerar `PEN-*`;
13. atribuir qualquer `DEC-*` por inferência;
14. atualizar ou substituir a linha mestre;
15. criar estrutura física real ou construir, implementar, migrar, testar, homologar, implantar ou operar a solução.

---

## 3. Resultado executivo

Foram inventariados **15 documentos controlados** no corpus direto, além dos atos humanos expressos desta execução. Foram avaliados separadamente os oito critérios de `PT-DOC-01` e os oito critérios de `PT-ESC-01`.

Resultado proposto:

| Portão | Critérios comprovados | Comprovados com ressalva | Não comprovados | Resultado proposto |
|---|---:|---:|---:|---|
| `PT-DOC-01` | 4 | 4 | 0 | `ATENDIDO` — com ressalvas documentais não impeditivas |
| `PT-ESC-01` | 5 | 3 | 0 | `ATENDIDO` — com ressalvas documentais não impeditivas |

As ressalvas concentram-se em dois pontos:

1. os registros autônomos de criação e ativação de `ESC-F05-05` possuem nome, tamanho e SHA-256 declarados e reconfirmados em `E5-01`, mas não foram localizados como arquivos autônomos no repositório oficial consultado;
2. alguns documentos preservam em seus próprios bytes cabeçalhos históricos como `MINUTA — NÃO PUBLICADO`; o estado posterior de aceite, publicação e vigência é comprovado por atos humanos, registros sucessores, conferências e commits, sem alteração retroativa desses bytes.

Essas limitações não eliminam a evidência obrigatória porque:

- `ESC-01` admite registro de criação **ou ato humano equivalente**;
- a criação, a ativação, os limites, o responsável, as unidades e os produtos de `ESC-F05-05` estão reiterados de modo convergente em `E5-01`, `E5-05` e na linha mestre vigente;
- a sucessão temporal explica os cabeçalhos históricos e impede que sejam confundidos com o estado corrente;
- não foi identificado conflito material entre consolidação, decisões, pendências e produtos vigentes.

Nenhum resultado se torna oficial por esta minuta. A adoção de cada resultado depende de decisão humana expressa.

---

## 4. Método aplicado

Foram aplicadas as regras de `E6-01 v0.1`:

1. avaliação por critério, sem média numérica;
2. não compensação entre critérios essenciais;
3. evidência complementar não substitui evidência obrigatória;
4. ressalva registrada com impacto explícito;
5. portões avaliados separadamente;
6. precedência documental sem aprovação automática de outro portão;
7. distinção entre estado contido nos bytes e eventos posteriores de governança;
8. preservação integral das ressalvas vinculantes;
9. proibição de inferir aceite, vigência, conclusão ou autorização;
10. apresentação em tela das decisões materiais.

Classes de evidência utilizadas:

| Código | Evidência |
|---|---|
| `EV-ID` | nome, versão, tamanho e SHA-256 |
| `EV-VIG` | vigência, sucessão e substituição documental |
| `EV-ACE` | aceite humano expresso |
| `EV-PUB` | publicação e conferência pós-publicação |
| `EV-RAS` | rastreabilidade entre fonte, produto, unidade e escopo |
| `EV-CRU` | conferência cruzada entre registros e produtos |
| `EV-RES` | preservação de ressalvas, lacunas e efeitos proibidos |
| `EV-HUM` | ato humano expresso, específico e separado |

---

## 5. Universo documental de PT-DOC-01

### 5.1 Delimitação

Integram o corpus direto desta avaliação:

1. a linha mestre vigente `v0.21/v0.25/v0.20`;
2. os dois registros de governança de `ESC-F05-05` identificados em `E5-01`;
3. `E5-01` a `E5-05` publicados e aceitos;
4. as duas propostas aceitas que fundamentaram `ESC-F05-06`;
5. os registros publicados de criação e ativação de `ESC-F05-06`;
6. `E6-01 v0.1`, aceito, publicado e conferido.

Documentos históricos anteriores permanecem como cadeia de proveniência incorporada pela linha mestre, mas não foram reabertos nem submetidos novamente à conferência física integral nesta unidade.

### 5.2 Inventário controlado

| ID | Documento | Bytes | SHA-256 | Função e estado considerados |
|---|---|---:|---|---|
| `S01` | `REG-CONSOLIDACAO-CHATS_v0.21_2026-09-19.md` | 164.009 | `ae7b9962c5e6cedae00b1c52fce9851360ff321cb15a28ad0eac63da80f652a2` | consolidação vigente; publicada e aceita |
| `S02` | `REG-DECISOES_v0.25_2026-09-19.md` | 222.318 | `eccd48c5b74ced41f1e4468c240be2e8d197fb1bade99d867baf9199a3e13e03` | decisões vigentes; publicado e aceito |
| `S03` | `REG-PENDENCIAS_v0.20_2026-09-19.md` | 156.757 | `0667290c28f0876d361c3bb890a88098188f2d87050d4d3ff8da8edb079dcfa1` | pendências vigentes; publicado e aceito |
| `S04` | `REG-CRIACAO-FORMAL-ESC-F05-05_v0.1_2026-09-18.md` | 10.740 | `7f80753b836e83455bd28fe714b56a02b66d8c8a2195e17651b24f09d8e60b3a` | identidade reconfirmada em `E5-01`; arquivo autônomo não localizado no repositório consultado |
| `S05` | `REG-ATIVACAO-ESC-F05-05_v0.1_2026-09-18.md` | 6.723 | `e9ca1355c3fb4f4469a082c6c0d7309ff3b09a6f9b31065d88866692124b3741` | identidade reconfirmada em `E5-01`; arquivo autônomo não localizado no repositório consultado |
| `S06` | `E5-01_PLANO-DE-DEFINICOES-INTERNAS-MODELAGEM-E-EVIDENCIAS_v0.1_2026-09-18.md` | 30.835 | `16d8680a49a6826f73b4fdfda69f406bec278fe768fb515716576d136d512905` | produto publicado, aceito e conferido |
| `S07` | `E5-02_MATRIZ-DE-TRATAMENTO-INDIVIDUAL-DOS-33-DETALHES-CONDICIONADOS_v0.1_2026-09-18.md` | 38.689 | `fa98657e7bbc16a07d5e4d03b7c9fbd8cd874c04aece50df5f6193f06b7261b4` | produto publicado, aceito e conferido |
| `S08` | `E5-03_CATALOGO-E-MAPA-LOGICO-FISICO-CONSOLIDADOS-EM-MINUTA_v0.1_2026-09-18.md` | 41.433 | `03048c54a80b29f211d8d8f52f2611b233d2161305faeb4525d089dd4440c9fc` | produto publicado e aceito; mapeamento substantivamente em minuta |
| `S09` | `E5-04_RELATORIO-DE-REVERIFICACAO-DE-C-F05-05-DA-MATRIZ-149-33-E-DA-PRONTIDAO-PRE-PT_v0.1_2026-09-18.md` | 40.091 | `3b10c140121108592a07a22712950ad24221e9ae8fc7105509b16f3e623cbf31` | produto publicado, aceito e conferido |
| `S10` | `E5-05_RELATORIO-DE-CONFERENCIA-E-PROPOSTA-DE-ESTADO-RESULTANTE-DE-ESC-F05-05_v0.1_2026-09-18.md` | 54.494 | `d68e9c4bbd47f910a9382d18e6d2a909a3825a772918d3ba5a202f2a9c2215da` | produto publicado, aceito e conferido |
| `S11` | `PROPOSTA-CONTINUIDADE-CONTROLADA-DA-FASE-05-POS-ESC-F05-05_v0.1_2026-09-19.md` | 15.519 | `2a6100d0fc1d870b4f4ef890945bfa513a82f5f9c1b74eb8758aa396ad8271d2` | proposta aceita e publicada |
| `S12` | `PROPOSTA-DEFINICAO-FORMAL-DO-EVENTUAL-PROXIMO-ESCOPO-DA-FASE-05-POS-ESC-F05-05_v0.1_2026-09-19.md` | 23.006 | `1900271fa5c9270d494541719e46a1774fa61d671f12bda2410bb3bd2b46b1a8` | definição aceita e publicada |
| `S13` | `REG-CRIACAO-FORMAL-ESC-F05-06_v0.1_2026-09-19.md` | 9.811 | `87839cd8ed7294b7e1db8077d9f9aec7783d9f775835b1c06a9503124b07ab12` | criação formal publicada |
| `S14` | `REG-ATIVACAO-ESC-F05-06_v0.1_2026-09-19.md` | 6.974 | `67997209eb841cc08fb6d7917d8689656ba92867aaf093ec7453f07158a93cc3` | ativação formal publicada |
| `S15` | `E6-01_PLANO-E-MATRIZ-CONTROLADA-DE-CRITERIOS-E-EVIDENCIAS_v0.1_2026-09-19.md` | 33.470 | `22e8267bf9a4d4578e7ea09f79b28654d57b4acf4b7ba73c1c8ee9e45238d7f5` | aceito, publicado e conferido |

Referências de publicação consideradas:

| Conjunto | Referência |
|---|---|
| linha mestre `v0.21/v0.25/v0.20` | commit sincronizado `dae06cd0f6a248dbc64ce7e7bac8d29aba30856b` |
| `E5-01` a `E5-05` | commit sincronizado `f3f2fc5f250584a2c0d5c867aa89fac504e182a4` |
| propostas e governança publicada de `ESC-F05-06` | estado verificável no repositório oficial, inclusive no corte `8f80ca3f9b97c15391ce8e96caa9e9f2d1a343e2` |
| `E6-01 v0.1` | commit `4043de30922e1285c616f91908c753c964064e45` |

---

## 6. Atos humanos desta unidade

Para a rastreabilidade interna de `E6-02`, são utilizados os seguintes eventos, sem criação de novos `DEC-*` ou `PEN-*`:

| Referência local | Ato humano |
|---|---|
| `AH-01` | aceite de `E6-01 v0.1` e autorização decorrente para publicação conforme regra operacional vigente |
| `AH-02` | aceite do resultado da publicação de `E6-01` |
| `AH-03` | autorização expressa para concluir `UT-F05-06-01` |
| `AH-04` | escolha da Alternativa A e autorização específica para iniciar `UT-F05-06-02` |
| `AH-05` | autorização específica para produzir `E6-02` |

Essas referências existem apenas dentro deste relatório e não constituem identificadores oficiais adicionais.

---

## 7. Avaliação de PT-DOC-01

| ID | Critério e obrigação | Fontes e evidências | Análise objetiva | Ressalva ou impedimento | Resultado | Impacto, dependência e decisão | Efeito não produzido |
|---|---|---|---|---|---|---|---|
| `DOC-01` | universo documental aplicável inventariado — essencial | `S01` a `S15`; `EV-ID`, `EV-VIG`, `EV-RAS` | O corpus direto foi delimitado por função, estado e vínculo. Antecedentes remotos permanecem incorporados pela linha mestre, sem reabertura. | nenhuma ausência material identificada no universo definido | `COMPROVADO` | sustenta o exame dos demais critérios; aceite humano necessário para adotar o resultado | não declara completude de toda a documentação histórica do projeto |
| `DOC-02` | identidade física verificável — essencial | tabela da seção 5.2; `EV-ID`; conferências publicadas | Nome, versão, tamanho e SHA-256 estão registrados para os 15 itens. Treze possuem verificação direta ou publicação confirmada; `S04` e `S05` têm identidade reconfirmada em `S06`. | `S04` e `S05` não foram localizados como arquivos autônomos no repositório consultado | `COMPROVADO COM RESSALVA` | ressalva não impeditiva porque a identidade e a função são reiteradas por fontes vigentes; decisão humana sobre aceitação da ressalva | não presume publicação autônoma de `S04` ou `S05` |
| `DOC-03` | vigência e sucessão determinadas — essencial | `S01` a `S03`, `S06`, `S10`, `S11`, `S12`, `S15`; `EV-VIG`, `EV-CRU` | A linha corrente e as sucessões estão determinadas. Minuta, versão aceita, publicação e vigência são eventos distinguíveis. | cabeçalhos históricos de alguns arquivos permanecem nos bytes e exigem leitura conjunta com atos posteriores | `COMPROVADO COM RESSALVA` | ressalva não impeditiva e necessária à preservação de bytes; aceite humano necessário | não altera retroativamente cabeçalhos históricos |
| `DOC-04` | aceite e autoridade comprovados — essencial | linha mestre; `S10` a `S15`; `AH-01` a `AH-05`; `EV-ACE`, `EV-HUM` | Eduardo Andrade Ramos está identificado como autoridade humana; os atos relevantes foram expressos e separados. | nenhuma | `COMPROVADO` | confirma legitimidade dos eventos usados; não substitui decisão sobre esta minuta | não infere aceite de `E6-02` |
| `DOC-05` | publicação e preservação comprovadas — obrigatório quando aplicável | commits da seção 5.2; `EV-PUB`, `EV-ID` | Linha mestre, `E5-01` a `E5-05`, propostas de continuidade, governança de `ESC-F05-06` e `E6-01` possuem publicação verificável e histórico preservado. | não foi comprovada publicação autônoma de `S04` e `S05`; sua função permanece comprovada por documentos publicados equivalentes | `COMPROVADO COM RESSALVA` | não impede o portão porque a obrigação de publicação desses dois registros não foi convertida em condição material exclusiva; decisão humana sobre a ressalva | não cria nem publica cópia substitutiva de `S04` ou `S05` |
| `DOC-06` | rastreabilidade entre fontes, produtos e registros — essencial | `S01` a `S15`; matrizes e sequências em `S06`, `S10`, `S12`, `S13`, `S15`; `EV-RAS` | Há encadeamento entre linha mestre, propostas, criação, ativação, unidades, produtos, aceitações, publicações e conclusões. Nenhum produto do corpus ficou órfão. | nenhuma lacuna material identificada no alcance definido | `COMPROVADO` | sustenta `PT-ESC-01`, sem aprová-lo automaticamente | não comprova mérito funcional ou arquitetural |
| `DOC-07` | coerência entre linha mestre e produtos vigentes — essencial | `S01` a `S03` cruzados com `S06` a `S15`; `EV-CRU` | Quantitativos, ressalvas, estados e sequência são convergentes. Não foi encontrado conflito material não resolvido. | textos internos anteriores preservam o estado do momento da produção; o estado corrente depende da cadeia posterior | `COMPROVADO COM RESSALVA` | ressalva temporal não impeditiva; decisão humana sobre adoção do resultado | não reescreve produtos anteriores para refletir eventos posteriores |
| `DOC-08` | ressalvas, lacunas e estados históricos preservados — essencial | `S01`, `S03`, `S08` a `S15`; `EV-RES` | Permanecem explícitos `33/33 em TRT-04`, zero `TRT-05`, matriz `149/33`, `C-F05-05` parcial, mapeamento não encerrado e inexistência física. | nenhuma supressão identificada | `COMPROVADO` | impede leitura de completude material; aceite humano necessário | não promove estado, detalhe, critério ou mapeamento |

### 7.1 Proposta para PT-DOC-01

Todos os oito critérios obrigatórios aplicáveis possuem evidência suficiente. Quatro apresentam ressalvas documentais explícitas, mas nenhuma é materialmente impeditiva no alcance delimitado.

**Resultado proposto:**

`PT-DOC-01 — ATENDIDO — COM RESSALVAS DOCUMENTAIS NÃO IMPEDITIVAS — CORPUS DIRETO DE 15 DOCUMENTOS INVENTARIADO — IDENTIDADES CONTROLADAS — VIGÊNCIA E SUCESSÃO DETERMINADAS — ACEITES, PUBLICAÇÕES E RASTREABILIDADE COMPROVADOS — DOIS REGISTROS DE GOVERNANÇA DE ESC-F05-05 SEM ARQUIVO AUTÔNOMO LOCALIZADO NO REPOSITÓRIO CONSULTADO, MAS COM IDENTIDADE E CONTEÚDO FUNCIONAL REITERADOS POR FONTES VIGENTES — CABEÇALHOS HISTÓRICOS PRESERVADOS E DISTINGUIDOS DOS EVENTOS POSTERIORES — SEM EFEITO SOBRE PT-FUN-01, PT-ARQ-01, CONSTRUÇÃO OU IMPLEMENTAÇÃO`.

---

## 8. Universo de escopos de PT-ESC-01

### 8.1 Escopos diretamente avaliados

O corpus direto de `PT-ESC-01` compreende:

| Escopo | Justificativa de aplicabilidade | Unidades abrangidas |
|---|---|---|
| `ESC-F05-05` | escopo antecedente imediato que formou e consolidou as entradas documentais para os portões | `UT-F05-05-01` a `UT-F05-05-05` |
| `ESC-F05-06` | escopo corrente que criou o processo controlado de avaliação dos portões | `UT-F05-06-01` concluída; `UT-F05-06-02` iniciada; `UT-F05-06-03` a `UT-F05-06-05` aprovadas e não iniciadas |

`ESC-F05-01` a `ESC-F05-04` permanecem antecedentes de proveniência consolidados pela linha mestre e pelos produtos de `ESC-F05-05`. Eles não foram reabertos nem individualmente reavaliados nesta unidade, pois o objeto direto é conferir a cadeia imediatamente aplicável à abertura e à execução de `ESC-F05-06`.

### 8.2 Correspondência unidade-produto

| Escopo | Unidade | Produto | Estado considerado nesta avaliação |
|---|---|---|---|
| `ESC-F05-05` | `UT-F05-05-01` | `E5-01` | concluída; produto aceito, publicado e conferido |
| `ESC-F05-05` | `UT-F05-05-02` | `E5-02` | concluída; produto aceito, publicado e conferido |
| `ESC-F05-05` | `UT-F05-05-03` | `E5-03` | concluída; produto aceito, publicado e conferido |
| `ESC-F05-05` | `UT-F05-05-04` | `E5-04` | concluída; produto aceito, publicado e conferido |
| `ESC-F05-05` | `UT-F05-05-05` | `E5-05` | concluída; produto aceito, publicado e conferido |
| `ESC-F05-06` | `UT-F05-06-01` | `E6-01` | concluída; produto aceito, publicado e conferido |
| `ESC-F05-06` | `UT-F05-06-02` | `E6-02` | iniciada; produto produzido por esta minuta; aceite pendente |
| `ESC-F05-06` | `UT-F05-06-03` | `E6-03` | aprovada; não iniciada; não produzido |
| `ESC-F05-06` | `UT-F05-06-04` | `E6-04` | aprovada; não iniciada; não produzido |
| `ESC-F05-06` | `UT-F05-06-05` | `E6-05` | aprovada; não iniciada; não produzido |

---

## 9. Avaliação de PT-ESC-01

| ID | Critério e obrigação | Fontes e evidências | Análise objetiva | Ressalva ou impedimento | Resultado | Impacto, dependência e decisão | Efeito não produzido |
|---|---|---|---|---|---|---|---|
| `ESC-01` | cada escopo aplicável possui criação formal — essencial | `S04`, `S06`, `S10`, `S12`, `S13`; linha mestre; `EV-HUM`, `EV-RAS` | `ESC-F05-05` e `ESC-F05-06` possuem criação formal comprovada. Para `ESC-F05-05`, atos equivalentes e fontes convergentes preservam a criação; para `ESC-F05-06`, há registro publicado próprio. | `S04` não foi localizado como arquivo autônomo no repositório consultado | `COMPROVADO COM RESSALVA` | ressalva não impede a prova do ato de criação; decisão humana sobre aceitação | não cria retroativamente qualquer escopo |
| `ESC-02` | nome, objetivo, limites e exclusões fixados — essencial | `S06`, `S10`, `S12`, `S13`, `S14`; `EV-RAS`, `EV-CRU` | Os dois escopos possuem nome, objetivo, inclusões, exclusões e efeitos proibidos determinados. | para `ESC-F05-05`, a prova direta usa fontes reiteradoras porque `S04` não está autônomo no repositório | `COMPROVADO COM RESSALVA` | fronteira material permanece determinada; decisão humana sobre a ressalva | não amplia o objeto de nenhum escopo |
| `ESC-03` | responsável humano e governança definidos — essencial | `S06`, `S10`, `S12` a `S15`; `AH-01` a `AH-05`; `EV-HUM` | Eduardo Andrade Ramos está expressamente designado; decisões, aceitações, publicações e conclusões exigem atos próprios. | nenhuma | `COMPROVADO` | confirma autoridade e regras decisórias | não designa terceiro nem delega poder decisório |
| `ESC-04` | ativação e início das unidades autorizados — essencial | `S05`, `S06`, `S10`, `S14`, `S15`; linha mestre; `AH-03` a `AH-05`; `EV-HUM`, `EV-RAS` | Ambos os escopos foram ativados. As unidades executadas possuem sequência de autorização verificável. Em `ESC-F05-06`, somente `UT-01` e `UT-02` foram iniciadas; as demais permanecem não iniciadas. | nenhuma | `COMPROVADO` | comprova regularidade da sequência sem autorizar continuidade automática | não inicia `UT-F05-06-03` a `UT-F05-06-05` |
| `ESC-05` | unidades e produtos correspondem ao escopo aprovado — essencial | seção 8.2; `S06`, `S10`, `S12` a `S15`; `EV-RAS` | As cinco unidades e cinco produtos de cada escopo possuem correspondência nominal. Não foi identificado produto órfão ou unidade fora dos limites. | nenhuma | `COMPROVADO` | confirma aderência formal; não avalia mérito dos produtos futuros | não produz `E6-03` a `E6-05` |
| `ESC-06` | execução, aceite, publicação e conclusão distinguíveis — essencial | `S01` a `S15`; commits; `AH-01` a `AH-05`; `EV-VIG`, `EV-ACE`, `EV-PUB` | Os eventos são separados na cronologia e nos estados. Cabeçalhos históricos não foram atualizados retroativamente; atos posteriores registram a mudança de estado. | a leitura isolada de cabeçalho histórico pode divergir do estado corrente sem a cadeia de sucessão | `COMPROVADO COM RESSALVA` | ressalva não impeditiva e protege a imutabilidade dos bytes | não funde aceite, publicação e conclusão |
| `ESC-07` | ressalvas e efeitos proibidos preservados — essencial | `S01`, `S03`, `S08` a `S15`; `EV-RES` | Permanecem todas as ressalvas vinculantes: 149/33 preservado, 33/33 em TRT-04, zero TRT-05, `C-F05-05` parcial, mapeamento não encerrado, ausência de realidade física e de implementação. | nenhuma | `COMPROVADO` | impede expansão do objeto e condiciona qualquer continuidade | não declara qualquer `PT-*` oficialmente atendido por consequência |
| `ESC-08` | estado resultante coerente e não autoexecutável — essencial | `S10` a `S15`; seção 8.2; `AH-01` a `AH-05`; `EV-CRU`, `EV-HUM` | A cadeia encerra `ESC-F05-05`, mantém `ESC-F05-06` ativo e distingue unidade concluída, unidade iniciada e unidades futuras. Cada passo depende de ato humano. | nenhuma | `COMPROVADO` | sustenta proposta própria de resultado; adoção depende de aceite humano | não conclui `UT-F05-06-02` nem o escopo |

### 9.1 Proposta para PT-ESC-01

Todos os oito critérios obrigatórios aplicáveis possuem evidência suficiente. Três apresentam ressalvas documentais explícitas, sem fronteira indeterminada, produto órfão, execução não autorizada ou consequência automática.

**Resultado proposto:**

`PT-ESC-01 — ATENDIDO — COM RESSALVAS DOCUMENTAIS NÃO IMPEDITIVAS — ESC-F05-05 E ESC-F05-06 DELIMITADOS COMO CORPUS DIRETO — CRIAÇÃO, DEFINIÇÃO, RESPONSÁVEL, ATIVAÇÃO, UNIDADES, PRODUTOS E SEQUÊNCIA COMPROVADOS — EVENTOS DE EXECUÇÃO, ACEITE, PUBLICAÇÃO E CONCLUSÃO DISTINGUIDOS — RESSALVAS E EFEITOS PROIBIDOS PRESERVADOS — REGISTRO AUTÔNOMO DE CRIAÇÃO DE ESC-F05-05 NÃO LOCALIZADO NO REPOSITÓRIO CONSULTADO, MAS SUBSTITUÍDO COMO PROVA POR ATOS HUMANOS E FONTES VIGENTES CONVERGENTES — SEM EFEITO SOBRE MÉRITO FUNCIONAL, ARQUITETURAL, CONSTRUÇÃO OU IMPLEMENTAÇÃO`.

---

## 10. Conferência cruzada dos dois portões

| Relação | Resultado |
|---|---|
| identidade das fontes → escopos | suficiente para vincular cada ato e produto ao escopo correspondente |
| vigência documental → sequência de governança | suficiente, com ressalva sobre cabeçalhos históricos preservados |
| publicação → preservação dos bytes | comprovada para a linha mestre, `E5-01` a `E5-05`, propostas e governança publicada de `ESC-F05-06` e `E6-01` |
| escopo → unidades → produtos | correspondência nominal completa no universo direto |
| ressalvas → estados resultantes | coerentes e sem promoção automática |

O resultado de `PT-DOC-01` foi usado apenas para confirmar a confiabilidade documental das fontes de `PT-ESC-01`. Não houve aprovação automática de `PT-ESC-01` por dependência.

---

## 11. Riscos e controles remanescentes

| Risco | Controle aplicado | Efeito residual |
|---|---|---|
| leitura isolada de cabeçalho histórico | exigir cadeia de vigência e eventos posteriores | ressalva documental permanente enquanto os bytes forem preservados |
| perda do registro autônomo de criação/ativação de `ESC-F05-05` | preservar nome, tamanho, hash e conteúdo funcional em fontes vigentes | não impede esta avaliação; recomenda preservação futura sem reconstrução inferida |
| resultado documental confundido com prontidão material | repetir efeitos não produzidos em cada portão | nenhum portão funcional ou arquitetural avaliado |
| sequência futura iniciada por consequência | parada obrigatória e autorização específica por unidade e produto | `UT-F05-06-03` permanece não iniciada |
| ressalvas arquiteturais apagadas por resultado documental | manter matriz 149/33, 33/33 em TRT-04, `C-F05-05` parcial e mapeamento aberto | nenhuma alteração material produzida |

---

## 12. Critérios de aceitação de E6-02

`E6-02` poderá ser aceito se o responsável humano confirmar que:

1. o corpus direto de 15 documentos está corretamente delimitado;
2. `ESC-F05-05` e `ESC-F05-06` constituem o universo direto adequado de `PT-ESC-01`;
3. os 16 critérios foram avaliados individualmente;
4. as ressalvas sobre `S04`, `S05` e cabeçalhos históricos estão corretamente descritas;
5. `PT-DOC-01` pode ser proposto como atendido com ressalvas não impeditivas;
6. `PT-ESC-01` pode ser proposto como atendido com ressalvas não impeditivas;
7. nenhum efeito funcional, arquitetural, físico ou executivo foi inferido;
8. as ressalvas vinculantes permaneceram integrais.

---

## 13. Critérios de conclusão de UT-F05-06-02

`UT-F05-06-02` somente poderá ser declarada concluída após:

1. produção integral de `E6-02`;
2. apresentação do nome físico, tamanho e SHA-256 da minuta;
3. apresentação em tela das propostas para os dois portões e das alternativas humanas;
4. aceite humano expresso de `E6-02`;
5. decisão humana expressa sobre o resultado proposto de `PT-DOC-01`;
6. decisão humana expressa sobre o resultado proposto de `PT-ESC-01`;
7. publicação decorrente do aceite, conforme a regra operacional vigente;
8. conferência pós-publicação da identidade do arquivo;
9. autorização humana expressa e separada para concluir a unidade.

O aceite desta minuta não inicia automaticamente `UT-F05-06-03` nem autoriza `E6-03`.

---

## 14. Alternativas documentalmente sustentadas

### Alternativa A — recomendada

Aceitar `E6-02 v0.1` e adotar separadamente:

1. `PT-DOC-01 — ATENDIDO`, com ressalvas documentais não impeditivas;
2. `PT-ESC-01 — ATENDIDO`, com ressalvas documentais não impeditivas.

Essa alternativa reconhece a suficiência do núcleo probatório sem apagar a ausência dos dois arquivos autônomos de governança de `ESC-F05-05` no repositório consultado nem os cabeçalhos históricos preservados.

### Alternativa B

Aceitar o relatório, mas adotar `PARCIALMENTE ATENDIDO` para um ou para ambos os portões, identificando expressamente qual ressalva é considerada materialmente impeditiva.

### Alternativa C

Solicitar ajuste da minuta ou evidência complementar antes de decidir os portões. Essa alternativa mantém ambos sem resultado adotado e impede a conclusão da unidade até nova apresentação.

### Alternativa D

Rejeitar `E6-02 v0.1`. Nenhum resultado de portão será adotado e a unidade permanecerá iniciada e não concluída.

---

## 15. Estado proposto e parada obrigatória

Estado desta execução:

`UT-F05-06-02 — INICIADA — EXECUÇÃO DOCUMENTAL REALIZADA — E6-02 v0.1 PRODUZIDO EM MINUTA — CORPUS DIRETO DE 15 DOCUMENTOS INVENTARIADO — ESC-F05-05 E ESC-F05-06 DELIMITADOS COMO UNIVERSO DIRETO DE ESCOPO — DOC-01 A DOC-08 AVALIADOS — ESC-01 A ESC-08 AVALIADOS — PT-DOC-01 PROPOSTO COMO ATENDIDO COM RESSALVAS DOCUMENTAIS NÃO IMPEDITIVAS — PT-ESC-01 PROPOSTO COMO ATENDIDO COM RESSALVAS DOCUMENTAIS NÃO IMPEDITIVAS — RESULTADOS NÃO ADOTADOS — PT-FUN-01 E PT-ARQ-01 NÃO AVALIADOS — LINHA MESTRE v0.21/v0.25/v0.20 INALTERADA — 33/33 EM TRT-04 — ZERO TRT-05 — MATRIZ 149/33 PRESERVADA — C-F05-05 PARCIALMENTE ATENDIDA — MAPEAMENTO NÃO ENCERRADO — SEM ESTRUTURA FÍSICA REAL OU IMPLEMENTAÇÃO — UT-F05-06-02 NÃO CONCLUÍDA`.

**PARADA OBRIGATÓRIA:** apresentar a minuta, sua identidade física, os dois resultados propostos e as alternativas. Aguardar aceite e decisões humanas expressas. Nenhuma publicação, conclusão de unidade ou continuidade automática é produzida por esta minuta.
