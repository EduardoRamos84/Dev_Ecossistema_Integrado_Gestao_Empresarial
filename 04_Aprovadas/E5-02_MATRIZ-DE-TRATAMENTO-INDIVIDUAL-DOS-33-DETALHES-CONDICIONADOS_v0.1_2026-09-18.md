# E5-02 — MATRIZ DE TRATAMENTO INDIVIDUAL DOS 33 DETALHES CONDICIONADOS

**Projeto:** Dev_Ecossistema_Integrado_Gestao_Empresarial  
**Fase:** 05 — Arquitetura de dados e preparação controlada anterior à construção  
**Escopo:** `ESC-F05-05 — DEFINIÇÕES INTERNAS E CONSOLIDAÇÃO DOCUMENTAL DO MAPEAMENTO LÓGICO-FÍSICO DOS 33 DETALHES CONDICIONADOS`  
**Unidade:** `UT-F05-05-02 — TRATAMENTO INDIVIDUAL DOS 33 DETALHES CONDICIONADOS`  
**Produto:** `E5-02 — MATRIZ DE TRATAMENTO INDIVIDUAL DOS 33 DETALHES CONDICIONADOS`  
**Versão:** v0.1  
**Data:** 2026-09-18  
**Estado:** MINUTA PRODUZIDA — UNIDADE INICIADA — AGUARDANDO DECISÕES HUMANAS — UNIDADE NÃO CONCLUÍDA  
**Responsável humano:** Eduardo Andrade Ramos

---

## 1. Finalidade

Esta matriz executa exclusivamente o tratamento documental individual dos 33 detalhes preservados sob `ALT-04` e `C-F05-09`, conforme a sequência por dependência lógica adotada no aceite de `E5-01`.

O produto:

1. preserva nominalmente os 33 detalhes, sem ausência, acréscimo, fusão ou renumeração;
2. identifica as decisões humanas já emitidas e as escolhas técnicas ainda abertas;
3. apresenta alternativas documentalmente sustentadas e recomendações não autoexecutáveis;
4. descreve, em nível lógico e documental, comportamento, domínio, temporalidade, relações, restrições, exceções, alertas e evidências;
5. mantém separados o tratamento operacional `TRT-*` e o estado oficial dos detalhes;
6. prepara insumos para eventual `UT-F05-05-03`, sem iniciá-la;
7. não produz estrutura física real, implementação, migração, teste, homologação, implantação ou operação.

---

## 2. Atos humanos habilitadores e alcance

Foram registrados os seguintes atos humanos expressos:

1. adoção da Alternativa A de `E5-01` — tratamento por dependência lógica;
2. aceite de `E5-01 v0.1`;
3. autorização para concluir `UT-F05-05-01`;
4. autorização para iniciar imediatamente `UT-F05-05-02`;
5. autorização para produzir imediatamente `E5-02`.

Esses atos autorizam análise e preparação documental. Não autorizam aceitar esta minuta, concluir `UT-F05-05-02`, iniciar `UT-F05-05-03`, publicar o produto, alterar a linha mestre ou promover qualquer detalhe no estado oficial.

Nenhum identificador `DEC-*` ou `PEN-*` é criado, alterado, encerrado, renumerado ou atribuído por inferência.

---

## 3. Preservações vinculantes

Permanecem integralmente preservados:

1. o inventário fechado de 67 itens;
2. a matriz oficial de 182 detalhes, composta por 149 disponíveis e 33 condicionados;
3. os 33 detalhes sob `ALT-04` e `C-F05-09` no estado oficial de entrada;
4. `C-F05-05` como parcialmente atendida;
5. o mapeamento lógico-físico como minuta documentada e não encerrada;
6. zero portões `PT-*` avaliados ou declarados atendidos;
7. inexistência de estrutura física real e de implementação;
8. divergência histórica `63/64`, sem correção retroativa;
9. linha mestre publicada, aceita e vigente `v0.20/v0.24/v0.19`;
10. ressalvas vinculantes de `ESC-F05-03` e `ESC-F05-04`;
11. inexistência de validação externa obrigatória;
12. caráter gerencial e operacional do sistema, de uso exclusivo do responsável humano.

O sistema poderá produzir cálculo informativo de alíquota ou valor esperado, desde que registre fonte, vigência e premissas e não se apresente como apuração oficial. Alertas somente poderão decorrer de desvio operacional verificável, dado incoerente, obrigação interna vencida ou divergência em relação ao fluxo configurado. É proibido alertar por ausência de parecer, destinatário ou validação externa.

---

## 4. Linha mestre e fontes de controle

### 4.1 Linha mestre vigente

| Registro | Tamanho | SHA-256 | Função |
|---|---:|---|---|
| `REG-CONSOLIDACAO-CHATS_v0.20_2026-09-17.md` | 152.641 bytes | `5a63380b492c06dfba0492458adbb7d6f106543727c4ac73bf2b672a0922804c` | estado consolidado vigente |
| `REG-DECISOES_v0.24_2026-09-17.md` | 213.006 bytes | `104b1283701e46763872dc0fc000cab6f9fc98c33381268d4218260be1d17d1f` | decisões vigentes |
| `REG-PENDENCIAS_v0.19_2026-09-17.md` | 146.988 bytes | `94a5c8ac461d17136df6c86b28f1dcea4e5d36bfd42615f08ba26cd36896fd8a` | pendências vigentes |

### 4.2 Produtos imediatamente antecedentes

| Produto | Tamanho | SHA-256 | Uso |
|---|---:|---|---|
| `E4-01_PLANO-DE-VALIDACOES-ESPECIALIZADAS-COMPETENCIAS-E-EVIDENCIAS_v0.1_2026-09-17.md` | 55.072 bytes | `88584bafdfd9cedf1fe5ee8ac480f38a951e14cce9847b9846741a56bd0c03a7` | inventário histórico de matérias e perguntas |
| `E4-02_DOSSIE-CONTROLADO-DE-MANIFESTACOES-ESPECIALIZADAS_v0.3_2026-09-17.md` | 17.944 bytes | `0e7a26b026e607ebd8a7fdb2b5594a4c18e8b57a3f9e68bd6d950f634430e25a` | correção vinculante: uso próprio e validação externa não obrigatória |
| `E4-03_MATRIZ-CONSOLIDADA-DE-VALIDACOES-E-DOS-33-DETALHES-CONDICIONADOS_v0.1_2026-09-17.md` | 29.679 bytes | `93fc793854caf90678bbd2ce383bf8bee18daf61bac776e6fec1d329ccfca82d` | universo nominal, fontes e matéria interna remanescente |
| `E4-04_RELATORIO-DE-REVERIFICACAO-DE-C-F05-05-DO-MAPEAMENTO-E-DA-PRONTIDAO-DOCUMENTAL-PARA-PT_v0.1_2026-09-17.md` | 34.517 bytes | `4d1617c1e2ab49ad23f60ea908d7dc159cc0f273a706c9df03efd65bd37214a5` | estado de C-F05-05 e do mapeamento |
| `E4-05_RELATORIO-DE-CONFERENCIA-E-PROPOSTA-DE-ESTADO-RESULTANTE-DE-ESC-F05-04_v0.1_2026-09-17.md` | 42.866 bytes | `def2b12b5e5f63d29d556505d02043898f23f60b0c022e02c177362ce7a51923` | estado resultante aceito de ESC-F05-04 |
| `E5-01_PLANO-DE-DEFINICOES-INTERNAS-MODELAGEM-E-EVIDENCIAS_v0.1_2026-09-18_MINUTA.md` | 30.835 bytes | `16d8680a49a6826f73b4fdfda69f406bec278fe768fb515716576d136d512905` | método, taxonomia, sequência e critérios desta unidade |

As fontes funcionais e arquiteturais `S02`, `S04`, `S07`, `S08`, `S12`, `S13`, `S14`, `S15`, `S16`, `REV-FUNC-006`, os RF/CA e as decisões `4M2-D*` permanecem referenciadas pelo alcance consolidado em `E4-03` e não são reescritas por esta matriz.

---

## 5. Decisões humanas preexistentes incorporadas

As decisões abaixo já foram expressamente emitidas pelo responsável humano e são tratadas como entradas, não como novas decisões desta minuta:

| Código interno | Decisão humana registrada | Alcance principal |
|---|---|---|
| `DH-E5-02-01` | o sistema é gerencial e operacional e será usado exclusivamente por Eduardo Andrade Ramos | todos os grupos |
| `DH-E5-02-02` | o sistema não substitui contabilidade, apuração fiscal oficial ou assessoria jurídica | G6 e G7 |
| `DH-E5-02-03` | o sistema poderá calcular alíquota e valor esperado apenas de modo informativo, com fonte, vigência e premissas | G6 |
| `DH-E5-02-04` | consultas a contador ou advogado ocorrerão somente quando houver caso concreto, e a informação resultante será cadastrada pelo usuário | G1, G4, G6 e G7 |
| `DH-E5-02-05` | nenhuma validação externa permanente será exigida | todos os grupos |
| `DH-E5-02-06` | alertas serão emitidos somente para desvios operacionais verificáveis e jamais pela ausência de validação externa | G5 e G6 |
| `DH-E5-02-07` | alertas devem limitar e informar; não devem bloquear a operação | G5 e G6 |

Essas decisões não encerram os detalhes correspondentes e não substituem as escolhas técnicas indicadas na seção 7.

---

## 6. Ordem efetivamente aplicada

Foi aplicada a sequência aprovada:

1. G1 — referência externa;
2. G3 — identidade e vigência;
3. G2 — linhagem;
4. G4 — evidência, integridade e precedência;
5. G5 — eventos de auditoria;
6. G6 — estimativa e temporalidade;
7. G7 — empresa e intercompany.

Dependências posteriores não foram usadas para decidir silenciosamente dependências anteriores.

---

## 7. Pacotes de decisão humana ainda necessários

As alternativas abaixo são materialmente diferentes. A letra recomendada é proposta, não decisão. O responsável humano poderá aceitar o pacote recomendado integralmente ou indicar exceções por código.

### 7.1 `PD-G1` — referência externa

**Alternativa A — registro limitado e extensível — RECOMENDADA.** Criar catálogo mínimo somente para referências efetivamente usadas: `DOCUMENTO`, `IDENTIFICADOR_EXTERNO`, `URL_FONTE`, `ORIENTACAO_CASO_CONCRETO` e `OUTRO_DECLARADO`; situações `ATIVA`, `SUBSTITUIDA`, `INATIVA` e `NAO_CONFIRMADA`; unicidade composta por tipo, origem/emissor, valor e escopo normalizados; relação opcional de um objeto para zero ou várias referências.

**Alternativa B — texto livre.** Registrar tipo e situação sem catálogo controlado, com menor esforço inicial e maior risco de duplicidade e pesquisa inconsistente.

**Alternativa C — catálogo amplo antecipado.** Criar taxonomia extensa de documentos e emissores, com risco de inventar domínios que o sistema ainda não usa.

### 7.2 `PD-G3` — identidade e vigência

**Alternativa A — identificador lógico UUIDv7 e vigência explícita — RECOMENDADA.** Identificador interno canônico UUIDv7, textual em minúsculas e com 36 caracteres; capacidade lógica máxima de 64 caracteres para interoperabilidade futura, preservando documentalmente a divergência histórica `63/64`; situações `RASCUNHO`, `VIGENTE`, `SUBSTITUIDO`, `ENCERRADO` e `CANCELADO`; início de vigência obrigatório quando `VIGENTE`, fim opcional e exigido no encerramento.

**Alternativa B — ULID.** Identificador de 26 caracteres, ordenável, mas diferente das referências historicamente consideradas e dependente de biblioteca específica.

**Alternativa C — sequência numérica.** Simples e legível, mas menos adequada a importações, reconciliações e geração distribuída futura.

### 7.3 `PD-G2` — linhagem

**Alternativa A — elos explícitos e consultáveis — RECOMENDADA.** Cada elo liga exatamente dois nós comprovados; tipos mínimos `DERIVA_DE`, `SUBSTITUI`, `IMPORTADO_DE`, `GERADO_POR` e `CORRIGE`; nenhum elo é criado por semelhança; consulta por ascendentes, descendentes e caminho; relação documental `1 elo → 2 nós`.

**Alternativa B — histórico textual por objeto.** Mais simples, porém sem navegação confiável nem verificação estrutural.

**Alternativa C — grafo universal antecipado.** Mais flexível, mas amplia indevidamente tecnologia e escopo antes da necessidade real.

### 7.4 `PD-G4` — evidência, integridade e precedência

**Alternativa A — integridade proporcional e precedência contextual — RECOMENDADA.** Registrar SHA-256 quando houver arquivo; preservar nome, tamanho, origem e data de captura; vínculos a elementos por tipo e finalidade; situações `ATIVO`, `SUBSTITUIDO`, `INVALIDADO` e `REMOVIDO_LOGICAMENTE`; precedência por finalidade, vigência, versão e origem, sem autoridade universal; anexo não equivale automaticamente a prova.

**Alternativa B — somente metadados descritivos.** Menor esforço, mas incapaz de detectar alteração de bytes.

**Alternativa C — assinatura ou certificação obrigatória.** Controle mais forte, porém desproporcional ao uso próprio e dependente de infraestrutura inexistente.

### 7.5 `PD-G5` — eventos de auditoria e alertas

**Alternativa A — catálogo mínimo orientado a mudança — RECOMENDADA.** Tipos `CRIACAO`, `ALTERACAO`, `RETIFICACAO`, `ESTORNO`, `CANCELAMENTO`, `IMPORTACAO`, `VINCULO`, `DESVINCULO`, `PAGAMENTO`, `RECEBIMENTO` e `ALERTA_OPERACIONAL`; resultado `CONCLUIDO`, `CONCLUIDO_COM_ALERTA`, `FALHOU` ou `CANCELADO`; autor padrão Eduardo, origem técnica quando importado; antes/depois opcionais conforme o evento; retenção lógica sem sobrescrita destrutiva; alertas somente por desvio operacional.

**Alternativa B — evento genérico com descrição livre.** Menor catálogo, mas pior pesquisa, conferência e automação.

**Alternativa C — catálogo universal por todos os domínios.** Excesso de antecipação e risco de duplicar eventos materiais de origem.

### 7.6 `PD-G6` — estimativa e temporalidade

**Alternativa A — estimativa informativa rastreável — RECOMENDADA.** Indicador booleano de estimativa; fundamento obrigatório quando verdadeiro; origem `CALCULO_INTERNO`, `FONTE_PUBLICADA`, `INFORMACAO_DO_USUARIO` ou `ORIENTACAO_CASO_CONCRETO`; referência temporal por tipo e valor; coerência gera alerta não bloqueante; cálculo de alíquota/valor esperado registra base, percentual, fonte, vigência e fórmula e nunca substitui valor oficial.

**Alternativa B — somente valor informado pelo usuário.** Reduz modelagem, mas perde rastreabilidade das premissas e comparação entre esperado e realizado.

**Alternativa C — cálculo tratado como apuração oficial.** Incompatível com o escopo e, portanto, não recomendável.

### 7.7 `PD-G7` — empresa e intercompany

**Alternativa A — vínculo operacional concreto — RECOMENDADA.** Cada vínculo identifica empresa de origem e de destino, ambas existentes e distintas; registra finalidade operacional e, quando aplicável, projeto, contrato, parcela, pagamento ou reembolso; admite informação de contador ou advogado somente como origem declarada em caso concreto; não produz efeito contábil, fiscal ou jurídico por si.

**Alternativa B — descrição textual sem duas pontas estruturadas.** Mais simples, mas insuficiente para conciliação e dupla contagem.

**Alternativa C — regras contábeis e fiscais automáticas.** Fora do escopo e incompatível com as decisões vinculantes.

---

## 8. Matriz individual — identidade, fontes, dependências e decisão

Legenda de onda: `O1` G1; `O2` G3; `O3` G2; `O4` G4; `O5` G5; `O6` G6; `O7` G7.

| # | Detalhe | Grupo/onda | Elemento afetado | Fontes e fundamento consolidados | Lacuna e dependências | Decisão/pacote | Alternativas | Recomendação | TRT atual |
|---:|---|---|---|---|---|---|---|---|---|
| 1 | `DET-PF-02-O` | G1/O1 | objeto `Referencia_Externa` | S07, S08, S12–S15; RF-03-004/050; D022/D024 | campos e domínio; antecede 4, 5, 22 e 29 | `PD-G1` | A/B/C | A | `TRT-02` |
| 2 | `DET-PF-09-O` | G2/O3 | objeto `Linhagem` | S02, S08, S12, S14–S16; REV-FUNC-006; RF-03-004/050; D024/D021/D023 | nós, elos e consulta; depende de G1/G3 e antecede 20, 28, 33 | `PD-G2` | A/B/C | A | `TRT-02` |
| 3 | `DET-PF-01-F06` | G3/O2 | `situacao_vigencia` | S13–S15; RF-03-004 e CA-01/-02; D022/D018/D023 | catálogo e transições; depende de 21 | `PD-G3` | A/B/C | A | `TRT-02` |
| 4 | `DET-PF-02-F03` | G1/O1 | `tipo_referencia` | S13, S15; RF-03-004/050; D022/D024 | catálogo limitado; depende de 1 | `PD-G1` | A/B/C | A | `TRT-02` |
| 5 | `DET-PF-02-F09` | G1/O1 | `situacao_referencia` | S14, S15; RF-03-004/050; D022/D024 | situações e transições; depende de 1 e 4 | `PD-G1` | A/B/C | A | `TRT-02` |
| 6 | `DET-PF-03-F06` | G4/O4 | `referencia_integridade` | S14–S16; RF-03-050 e CA; D024 | mecanismo de integridade; antecede 23 | `PD-G4` | A/B/C | A | `TRT-02` |
| 7 | `DET-PF-04-F03` | G4/O4 | `tipo_elemento_sustentado` | S12, S14, S15; RF-03-004/050; D024 | tipos sustentáveis; antecede 30 | `PD-G4` | A/B/C | A | `TRT-02` |
| 8 | `DET-PF-04-F08` | G4/O4 | `situacao_vinculo` | S14, S15; RF-03-004/050; D024 | ciclo do vínculo; depende de 7 e antecede 30 | `PD-G4` | A/B/C | A | `TRT-02` |
| 9 | `DET-PF-05-F07` | G5/O5 | `tipo_evento` | S08, S14, S15, REV-FUNC-006; RF-03-004 CA-01/-04; D018/D024/D021 | catálogo mínimo; antecede 10–16 e 24 | `PD-G5` | A/B/C | A | `TRT-02` |
| 10 | `DET-PF-05-F11` | G5/O5 | `valor_temporal_afetado_ref` | S13–S15, REV-FUNC-006; RF-03-004 CA-01/-04; D018/D024/D021 | referência temporal; depende de 9 e G6 | `PD-G5` + `PD-G6` | A/B/C | A/A | `TRT-02` |
| 11 | `DET-PF-05-F14` | G5/O5 | `valor_anterior_ref` | S08, S12, S14, S15, REV-FUNC-006; RF-03-004; D018/D024/D021 | representação polimórfica; depende de 9 | `PD-G5` | A/B/C | A | `TRT-02` |
| 12 | `DET-PF-05-F15` | G5/O5 | `valor_posterior_ref` | mesmas bases do item 11 | representação e exceções; depende de 9 e 11 | `PD-G5` | A/B/C | A | `TRT-02` |
| 13 | `DET-PF-05-F20` | G5/O5 | `ref_autor` | S14, S15 e E4-02 v0.3; RF-03-004; D018/D024/D021 | representação técnica do autor | `DH-E5-02-01` + `PD-G5` | decisão funcional já emitida; técnica A/B/C | A | `TRT-03` |
| 14 | `DET-PF-05-F22` | G5/O5 | `ref_autoridade` | S08, S14, S15, S04 governança e E4-02 v0.3 | autoridade por origem/ato | `DH-E5-02-04/05` + `PD-G5` | decisão funcional já emitida; técnica A/B/C | A | `TRT-03` |
| 15 | `DET-PF-05-F30` | G5/O5 | `resultado_evento` | S12, S14, S15, REV-FUNC-006; RF-03-004; D018/D024/D021 | catálogo de resultados; depende de 9 | `PD-G5` | A/B/C | A | `TRT-02` |
| 16 | `DET-PF-05-F33` | G5/O5 | `referencia_alertas_pendencias` | S02, S14–S16 e E4-02 v0.3; RF-03-004; D018/D024/D021 | ligação técnica a alerta operacional | `DH-E5-02-06/07` + `PD-G5` | decisão funcional já emitida; técnica A/B/C | A | `TRT-03` |
| 17 | `DET-PF-07-F10` | G6/O6 | `indicador_estimativa` | S13, S15, REV-FUNC-006 e E4-02 v0.3; RF-03-004; D017/D018 | indicador técnico | `DH-E5-02-02/03` + `PD-G6` | decisão funcional já emitida; técnica A/B/C | A | `TRT-03` |
| 18 | `DET-PF-07-F11` | G6/O6 | `fundamento_estimativa` | mesmas bases do item 17 | fundamento e premissas; depende de 17 | `DH-E5-02-03/05` + `PD-G6` | decisão funcional já emitida; técnica A/B/C | A | `TRT-03` |
| 19 | `DET-PF-07-F12` | G6/O6 | `ref_responsavel_ou_origem_estimativa` | mesmas bases do item 17; CC | origem/responsável; depende de 17 | `DH-E5-02-01/04/05` + `PD-G6` | decisão funcional já emitida; técnica A/B/C | A | `TRT-03` |
| 20 | `DET-PF-09-F06` | G2/O3 | `tipo_relacao_linhagem` | S12, S14, S15, REV-FUNC-006; RF-03-004/050; D024/D021/D023 | catálogo de elos; depende de 2 | `PD-G2` | A/B/C | A | `TRT-02` |
| 21 | `DET-PF-01-R04` | G3/O2 | identidade, formato e comprimento | S02, S12, S13, S15; RF-03-004 CA-01/-02; D022/D018/D023 | gerador e divergência 63/64; antecede G2 | `PD-G3` | A/B/C | A | `TRT-02` |
| 22 | `DET-PF-02-R01` | G1/O1 | unicidade de referência | S08, S12–S15; RF-03-004/050; D022/D024 | chave de unicidade; depende de 1 e 4 | `PD-G1` | A/B/C | A | `TRT-02` |
| 23 | `DET-PF-03-R06` | G4/O4 | integridade de fonte/evidência | S02, S14–S16; RF-03-050 e CA; D024 | integridade, retenção e repositório; depende de 6 | `PD-G4` | A/B/C | A | `TRT-02` |
| 24 | `DET-PF-05-R04` | G5/O5 | controle dos tipos de evento | S02, S08, S14, S15, REV-FUNC-006; RF-03-004; D018/D024/D021 | validação interna do catálogo; depende de 9 | `PD-G5` | A/B/C | A | `TRT-02` |
| 25 | `DET-PF-05-R05` | G5/O5 | retenção, alteração e observabilidade | S02, S12, S14–S16; RF-03-004; D018/D024/D021 | política técnica futura; depende de 9 e G4 | `PD-G5` + `PD-G4` | A/B/C | A/A | `TRT-02` |
| 26 | `DET-PF-06-R04` | G7/O7 | cardinalidade empresarial | S02, S12, S14, S15, REV-FUNC-006 e E4-02 v0.3; CA-RF-03-004-03; D003/D018 | duas pontas e multiplicidade; antecede 31 | `PD-G7` | A/B/C | A | `TRT-02` |
| 27 | `DET-PF-07-R02` | G6/O6 | coerência temporal | S02, S12, S13, S15, REV-FUNC-006 e E4-02 v0.3; RF-03-004; D017/D018 | regras executáveis e alerta; depende de 17–19 | `DH-E5-02-06/07` + `PD-G6` | decisão funcional já emitida; técnica A/B/C | A | `TRT-03` |
| 28 | `DET-PF-09-R03` | G2/O3 | consulta de linhagem | S02, S12, S14–S16; RF-03-004/050; D024/D021/D023 | navegação; depende de 2, 20 e 33 | `PD-G2` | A/B/C | A | `TRT-02` |
| 29 | `DET-REL-02` | G1/O1 | objeto → referência externa | S12, S13, S15; RF-03-050; D022/D024 | cardinalidade e integridade; depende de 1 e 22 | `PD-G1` | A/B/C | A | `TRT-02` |
| 30 | `DET-REL-05` | G4/O4 | elemento → vínculo de evidência | S14, S15; RF-03-050; D024 | cardinalidade e materialidade; depende de 7 e 8 | `PD-G4` | A/B/C | A | `TRT-02` |
| 31 | `DET-REL-06` | G7/O7 | vínculo operacional intercompany | S12, S14, S15, REV-FUNC-006 e E4-02 v0.3; CA-RF-03-004-03; D003 | duas empresas e fluxo real; depende de 26 | `DH-E5-02-02/04/05` + `PD-G7` | decisão funcional já emitida; técnica A/B/C | A | `TRT-03` |
| 32 | `DET-REL-11` | G4/O4 | precedência de fontes | S08 e CA, S15, REV-FUNC-006 e E4-02 v0.3; RF-03-050; D024 | regra contextual; depende de 6, 7 e 23 | `DH-E5-02-04/05` + `PD-G4` | decisão funcional já emitida; técnica A/B/C | A | `TRT-03` |
| 33 | `DET-REL-13` | G2/O3 | elo de linhagem | S12, S14–S16, REV-FUNC-006; RF-03-004/050; D024/D021/D023 | exatamente dois nós comprovados; depende de 2 e 20 | `PD-G2` | A/B/C | A | `TRT-02` |

---

## 9. Matriz individual — especificação documental proposta

Em todos os itens, `ALT-04` e `C-F05-09` permanecem aplicáveis no estado oficial. A coluna “proposta posterior” não é autoexecutável.

| # | Detalhe | Comportamento e dados propostos | Relações, restrições e temporalidade | Evidências e casos de borda | Alertas permitidos | Efeitos proibidos | Proposta posterior / próximo ato |
|---:|---|---|---|---|---|---|---|
| 1 | `DET-PF-02-O` | registro interno de referência efetivamente usada, com ID, objeto, tipo, valor, origem, escopo, fonte, evento e situação | existência facultativa por objeto; datas da fonte separadas da data de cadastro | `EV-FNT/FUN/ARQ/MOD/RAS`; origem desconhecida, referência substituída e valor ausente | referência malformada, duplicada ou órfã | catálogo universal; efeito externo presumido | aceitar `PD-G1-A`; depois `TRT-04` |
| 2 | `DET-PF-09-O` | registro de elo entre nós comprovados, com tipo, origem, destino, evidência e evento gerador | um elo exige origem e destino distintos e existentes; sem elo inferido | `EV-FNT/FUN/ARQ/MOD/EXC/RAS`; nó excluído, ciclo e origem ausente | elo quebrado, ciclo proibido ou nó inexistente | relação material por semelhança | aceitar `PD-G2-A`; depois `TRT-04` |
| 3 | `DET-PF-01-F06` | domínio `RASCUNHO/VIGENTE/SUBSTITUIDO/ENCERRADO/CANCELADO` | transições explícitas; vigência não retroage sem registro de correção | `EV-FNT/FUN/ARQ/DHU/MOD/EXC`; datas coincidentes e cancelamento | transição inválida ou data incoerente | eficácia jurídica/fiscal automática | aceitar `PD-G3-A`; depois `TRT-04` |
| 4 | `DET-PF-02-F03` | domínio limitado de tipos de referência de `PD-G1-A` | obrigatório quando houver referência | `EV-FNT/FUN/MOD/RAS`; tipo não previsto usa `OUTRO_DECLARADO` com descrição | tipo ausente ou incompatível | taxonomia global antecipada | aceitar `PD-G1-A`; depois `TRT-04` |
| 5 | `DET-PF-02-F09` | domínio `ATIVA/SUBSTITUIDA/INATIVA/NAO_CONFIRMADA` | situação interna; mudança registra evento e momento | `EV-FNT/MOD/EXC/RAS`; fonte sem situação declarada | uso de referência inativa/substituída quando o fluxo esperava ativa | declaração de validade externa | aceitar `PD-G1-A`; depois `TRT-04` |
| 6 | `DET-PF-03-F06` | SHA-256 do arquivo quando houver bytes; metadados quando não houver arquivo | hash não obrigatório para referência sem arquivo; algoritmo identificado | `EV-FNT/ARQ/MOD/EXC`; URL, texto declarado e arquivo ausente | hash divergente ou arquivo trocado | afirmar assinatura/certificado | aceitar `PD-G4-A`; depois `TRT-04` |
| 7 | `DET-PF-04-F03` | tipos limitados `REGISTRO`, `CAMPO`, `EVENTO`, `CALCULO`, `DOCUMENTO` e `RELACAO` | tipo obrigatório em cada vínculo | `EV-FUN/ARQ/MOD/RAS`; elemento removido ou tipo futuro | elemento inexistente ou tipo incompatível | catálogo universal | aceitar `PD-G4-A`; depois `TRT-04` |
| 8 | `DET-PF-04-F08` | situação `ATIVO/SUBSTITUIDO/INVALIDADO/REMOVIDO_LOGICAMENTE` | mudança preserva histórico e evento | `EV-ARQ/MOD/EXC/RAS`; vínculo duplicado ou evidência substituída | vínculo inválido, duplicado ou órfão | apagar histórico; criar efeito material | aceitar `PD-G4-A`; depois `TRT-04` |
| 9 | `DET-PF-05-F07` | catálogo mínimo de `PD-G5-A`, extensível somente por decisão posterior | obrigatório; evento transversal não duplica evento material de domínio | `EV-FUN/ARQ/DHU/MOD/RAS`; importação e evento específico futuro | tipo ausente ou incompatível com a operação | catálogo universal; duplicação de ocorrência | aceitar `PD-G5-A`; depois `TRT-04` |
| 10 | `DET-PF-05-F11` | referência tipada à dimensão temporal afetada, não um texto ambíguo | opcional; obrigatória quando o evento alterar data, competência ou vigência | `EV-FUN/ARQ/MOD/EXC`; evento sem eixo temporal | referência a dimensão inexistente | inventar precisão/calendário | aceitar `PD-G5-A/G6-A`; depois `TRT-04` |
| 11 | `DET-PF-05-F14` | valor anterior serializado com tipo lógico e unidade/domínio | opcional; obrigatório em alteração, retificação, estorno ou cancelamento quando houver estado anterior | `EV-FUN/ARQ/MOD/EXC`; criação sem anterior e dado sigiloso | tipo ou unidade incompatível | tipo material único universal | aceitar `PD-G5-A`; depois `TRT-04` |
| 12 | `DET-PF-05-F15` | valor posterior no mesmo formato tipado do anterior | opcional em exclusão/cancelamento; compatível com o campo afetado | `EV-FUN/ARQ/MOD/EXC`; remoção lógica e valor nulo | par anterior/posterior incoerente | exigir par em todo evento | aceitar `PD-G5-A`; depois `TRT-04` |
| 13 | `DET-PF-05-F20` | referência padrão ao operador Eduardo; origem técnica identificada em importação | obrigatório, salvo evento técnico com origem identificada | `EV-DHU/MOD/RAS`; importação automática futura | autor/origem ausente | criar usuários e papéis desnecessários | matéria funcional `TRT-03`; aceitar técnica `PD-G5-A` |
| 14 | `DET-PF-05-F22` | autoridade `TITULAR`, `SISTEMA` ou `FONTE_DECLARADA`; prestador não vira aprovador | obrigatória conforme tipo de evento; fonte externa é origem documental | `EV-DHU/FNT/MOD/EXC`; orientação em caso concreto | autoridade incompatível com origem | transformar contador/advogado em validador obrigatório | matéria funcional `TRT-03`; aceitar técnica `PD-G5-A` |
| 15 | `DET-PF-05-F30` | domínio `CONCLUIDO/CONCLUIDO_COM_ALERTA/FALHOU/CANCELADO` | obrigatório ao fechar evento; pode evoluir de em processamento em modelo posterior | `EV-FUN/MOD/EXC/RAS`; falha parcial | evento fechado sem resultado | resultado universal por domínio | aceitar `PD-G5-A`; depois `TRT-04` |
| 16 | `DET-PF-05-F33` | referência opcional a alerta ou obrigação interna relacionada | um evento pode apontar zero ou várias ocorrências; alerta é não bloqueante | `EV-DHU/FUN/MOD/EXC/RAS`; alerta resolvido ou duplicado | somente desvio verificável, vencimento, valor divergente ou dado incoerente | alerta por falta de validação externa | matéria funcional `TRT-03`; aceitar técnica `PD-G5-A` |
| 17 | `DET-PF-07-F10` | booleano `e_estimativa`; falso por padrão | quando verdadeiro aciona obrigatoriedade dos itens 18 e 19 | `EV-DHU/FUN/MOD/RAS`; valor inicialmente estimado e depois confirmado | estimativa usada como se oficial | confundir estimativa e valor oficial | matéria funcional `TRT-03`; aceitar técnica `PD-G6-A` |
| 18 | `DET-PF-07-F11` | texto estruturado ou referência contendo base, fórmula, percentual, fonte e vigência | obrigatório quando `e_estimativa=true`; versionado quando premissas mudarem | `EV-DHU/FNT/FUN/MOD/EXC`; fonte expirada ou fórmula incompleta | fundamento ausente, desatualizado ou incompatível | exigir parecer externo; apuração oficial | matéria funcional `TRT-03`; aceitar técnica `PD-G6-A` |
| 19 | `DET-PF-07-F12` | origem `CALCULO_INTERNO/FONTE_PUBLICADA/INFORMACAO_DO_USUARIO/ORIENTACAO_CASO_CONCRETO` e referência correspondente | obrigatória quando estimativa; Eduardo continua responsável pela entrada | `EV-DHU/FNT/MOD/RAS`; origem não verificável ou mista | origem ausente ou referência quebrada | converter origem em aprovação | matéria funcional `TRT-03`; aceitar técnica `PD-G6-A` |
| 20 | `DET-PF-09-F06` | domínio de elos de `PD-G2-A` | obrigatório; extensível por ato documentado | `EV-FUN/ARQ/MOD/EXC`; relação futura não prevista | tipo ausente ou incompatível | dedução material não comprovada | aceitar `PD-G2-A`; depois `TRT-04` |
| 21 | `DET-PF-01-R04` | UUIDv7 canônico de 36 caracteres; capacidade lógica máxima 64 | geração interna; comparação sem distinção de maiúsculas; importado externo fica em referência, não substitui ID interno | `EV-FNT/ARQ/DHU/MOD/EXC`; colisão e ID legado; divergência 63/64 preservada historicamente | formato inválido ou colisão | corrigir retroativamente a divergência 63/64 | aceitar `PD-G3-A`; depois `TRT-04` |
| 22 | `DET-PF-02-R01` | unicidade composta por tipo, origem/emissor, valor e escopo normalizados | não universal; valores nulos tratados explicitamente | `EV-FUN/ARQ/MOD/EXC`; mesmo número em emissores distintos | duplicidade composta | unicidade global | aceitar `PD-G1-A`; depois `TRT-04` |
| 23 | `DET-PF-03-R06` | verificação de SHA-256 quando houver arquivo; metadados mínimos sempre | retenção lógica e repositório são desenho posterior; nenhuma implementação declarada | `EV-ARQ/MOD/EXC/RAS`; arquivo ausente, corrompido ou substituído | divergência de integridade | afirmar controle físico já existente | aceitar `PD-G4-A`; depois `TRT-04` |
| 24 | `DET-PF-05-R04` | somente tipos do catálogo aceito; extensão exige registro humano posterior | validação interna no cadastro; sem revisão externa | `EV-DHU/FUN/MOD/EXC`; novo tipo necessário | tipo fora do catálogo | catálogo universal | aceitar `PD-G5-A`; depois `TRT-04` |
| 25 | `DET-PF-05-R05` | eventos não são sobrescritos; correção por novo evento correlacionado | retenção lógica integral no sistema; política física e backup ficam para arquitetura executável | `EV-ARQ/MOD/EXC/RAS`; erro de lançamento e dado sensível | tentativa de alteração destrutiva | afirmar imutabilidade ou recuperação implementada | aceitar `PD-G5-A/G4-A`; manter ressalva física |
| 26 | `DET-PF-06-R04` | cada vínculo tem uma origem e um destino; empresa pode ter zero ou vários vínculos | origem ≠ destino; empresas existentes; cardinalidade física futura não inferida | `EV-DHU/FUN/ARQ/MOD/EXC`; empresa encerrada e vínculo unilateral | ponta ausente ou iguais | exigir parecer; efeito contábil/jurídico | aceitar `PD-G7-A`; depois `TRT-04` |
| 27 | `DET-PF-07-R02` | regras mínimas: início ≤ fim; competência compatível com período; pagamento/recebimento não anterior ao fato sem justificativa | divergência gera alerta não bloqueante e pode ser justificada | `EV-DHU/FUN/ARQ/MOD/EXC`; antecipação legítima, fuso e data incompleta | incoerência temporal verificável | bloquear operação; exigir validação externa | matéria funcional `TRT-03`; aceitar técnica `PD-G6-A` |
| 28 | `DET-PF-09-R03` | consulta por origem, destino, ascendentes, descendentes e caminho | somente elos persistidos; desempenho e índice físico futuros | `EV-ARQ/MOD/EXC/RAS`; caminho ausente e ciclo | elo quebrado ou caminho inconsistente | declarar índice/desempenho físico | aceitar `PD-G2-A`; depois `TRT-04` |
| 29 | `DET-REL-02` | um objeto pode ter zero ou várias referências; cada referência pertence ao objeto indicado e pode ser reutilizada apenas por novo vínculo explícito | integridade referencial lógica; exclusão preserva histórico | `EV-FUN/ARQ/MOD/EXC/RAS`; referência compartilhada e objeto inativo | vínculo órfão ou duplicado | presumir domínio/emissor/efeito | aceitar `PD-G1-A`; depois `TRT-04` |
| 30 | `DET-REL-05` | um elemento pode ter zero ou vários vínculos; cada vínculo aponta uma fonte/evidência e declara finalidade | cardinalidade `1 elemento → 0..* vínculos`; vínculo não prova automaticamente conteúdo | `EV-FUN/ARQ/MOD/EXC/RAS`; múltiplas evidências conflitantes | vínculo órfão ou evidência invalidada | transformar anexo em prova automática | aceitar `PD-G4-A`; depois `TRT-04` |
| 31 | `DET-REL-06` | vínculo intercompany identifica duas empresas e objeto operacional relacionado | origem e destino distintas; nenhum efeito fiscal/contábil/jurídico automático | `EV-DHU/FUN/ARQ/MOD/EXC/RAS`; reembolso, rateio ou operação sem orientação externa | ponta ausente, dupla contagem ou valor divergente | criar regra contábil/fiscal; exigir parecer permanente | matéria funcional `TRT-03`; aceitar técnica `PD-G7-A` |
| 32 | `DET-REL-11` | precedência determinada por finalidade, vigência, versão e origem; conflito fica explícito | zero ou uma fonte prevalente por finalidade; histórico preservado | `EV-DHU/FNT/ARQ/MOD/EXC/RAS`; duas fontes vigentes conflitantes | conflito não resolvido ou fonte expirada usada | autoridade universal; validação externa obrigatória | matéria funcional `TRT-03`; aceitar técnica `PD-G4-A` |
| 33 | `DET-REL-13` | cada elo liga exatamente um nó de origem e um de destino | `1 elo → 2 nós`; nós distintos e comprovados; ciclo conforme tipo | `EV-FUN/ARQ/MOD/EXC/RAS`; autociclo e nó removido | nó inexistente, elo duplicado ou ciclo proibido | criar elo por inferência | aceitar `PD-G2-A`; depois `TRT-04` |

---

## 10. Totalização do tratamento

| Estado operacional nesta minuta | Quantidade | Identificadores |
|---|---:|---|
| `TRT-02 — decisão humana requerida` | 24 | 1–12, 15, 20–26, 28–30 e 33 |
| `TRT-03 — decisão humana registrada` | 9 | 13, 14, 16, 17, 18, 19, 27, 31 e 32 |
| `TRT-04` ou superior | 0 | nenhuma decisão técnica recomendada foi ainda aceita nesta minuta |

Para evitar ambiguidade: a soma individual da tabela da seção 8 é `24 TRT-02 + 9 TRT-03 = 33`. O estado oficial permanece `33 condicionados`; nenhuma contagem oficial foi alterada.

---

## 11. Cobertura do registro mínimo definido em E5-01

| Requisito de E5-01 | Local de atendimento em E5-02 |
|---|---|
| número, identificador, grupo, onda e elemento afetado | seção 8 |
| fontes e fundamentos | seções 4 e 8 |
| lacunas e dependências | seção 8 |
| decisão necessária, alternativas e recomendação | seções 7 e 8 |
| decisão humana já emitida | seção 5 e linhas `TRT-03` |
| comportamento, dados, domínio, obrigatoriedade e temporalidade | seção 9 |
| relações, cardinalidades e restrições | seção 9 |
| evidências e casos de borda | seção 9 |
| alertas operacionais e efeitos proibidos | seções 3, 7 e 9 |
| estado `TRT-*`, proposta oficial e próximo ato | seções 8–10 |
| `ALT-04` e `C-F05-09` | seções 3 e 9 |

---

## 12. Critérios propostos de aceitação de E5-02

`E5-02` poderá ser aceito somente se houver ato humano expresso que confirme:

1. a presença exata dos 33 identificadores;
2. a manutenção das sete ondas e dependências;
3. a correção das decisões humanas preexistentes registradas;
4. a escolha dos pacotes `PD-G1` a `PD-G7`, integralmente ou com exceções explícitas;
5. a suficiência do comportamento e das exceções propostas;
6. a limitação de alertas a desvios operacionais não bloqueantes;
7. a separação entre cálculo informativo e apuração oficial;
8. a inexistência de validação externa obrigatória;
9. a manutenção dos 33 detalhes no estado oficial condicionado;
10. a preservação de 149/33, C-F05-05 parcial, mapeamento não encerrado e zero `PT-*` avaliados;
11. a inexistência de estrutura física real ou implementação;
12. a identidade física, tamanho e SHA-256 desta minuta.

Aceitar `E5-02` não conclui automaticamente `UT-F05-05-02`.

---

## 13. Critérios propostos de conclusão de UT-F05-05-02

`UT-F05-05-02` somente poderá ser declarada concluída quando, cumulativamente:

1. `E5-02` tiver sido produzido e sua integridade conferida;
2. os 33 detalhes estiverem individualizados sem alteração do universo;
3. os sete pacotes de decisão tiverem decisão humana expressa;
4. as eventuais exceções do responsável humano tiverem sido incorporadas em versão controlada;
5. `E5-02` tiver sido expressamente aceito;
6. não houver conflito material ou regressão documental pendente dentro da unidade;
7. as preservações vinculantes tiverem sido reconfirmadas;
8. houver autorização humana expressa e separada para concluir `UT-F05-05-02`.

A conclusão da unidade não inicia `UT-F05-05-03` e não autoriza `E5-03`.

---

## 14. Critérios de parada

A execução deve parar para decisão humana quando houver:

1. rejeição ou alteração de qualquer pacote `PD-G*`;
2. solicitação de nova alternativa não coberta;
3. divergência entre decisão preexistente e entendimento do responsável humano;
4. tentativa de converter alerta em bloqueio geral;
5. tentativa de tornar validação externa obrigatória;
6. tentativa de produzir efeito contábil, fiscal ou jurídico automático;
7. necessidade de alterar a matriz 149/33, o inventário de 67 itens ou a linha mestre;
8. necessidade de avaliar `PT-*`, construir ou implementar;
9. conflito de fonte, vigência, autoridade ou precedência sem regra aceita;
10. divergência de nome, tamanho ou SHA-256 do produto.

---

## 15. Decisão humana requerida em tela

Para continuidade documental, submeter expressamente ao responsável humano:

1. `PD-G1`: escolher A, B ou C para referência externa — recomendação A;
2. `PD-G3`: escolher A, B ou C para identidade e vigência — recomendação A;
3. `PD-G2`: escolher A, B ou C para linhagem — recomendação A;
4. `PD-G4`: escolher A, B ou C para evidência, integridade e precedência — recomendação A;
5. `PD-G5`: escolher A, B ou C para eventos e alertas — recomendação A;
6. `PD-G6`: escolher A, B ou C para estimativa e temporalidade — recomendação A;
7. `PD-G7`: escolher A, B ou C para empresa e intercompany — recomendação A;
8. aceitar ou rejeitar `E5-02 v0.1`;
9. se aceita e após incorporação de eventuais ajustes, autorizar ou não a conclusão de `UT-F05-05-02` em ato separado.

Até esses atos, `UT-F05-05-02` permanece iniciada e não concluída; `E5-02` permanece em minuta; `UT-F05-05-03` permanece não iniciada; `E5-03` permanece não produzido.

---

## 16. Estado resultante desta produção

1. `UT-F05-05-02`: **INICIADA POR AUTORIZAÇÃO HUMANA EXPRESSA — NÃO CONCLUÍDA**;
2. `E5-02 v0.1`: **PRODUZIDO EM MINUTA — AGUARDANDO DECISÕES E ACEITE HUMANOS**;
3. 33/33 detalhes: **TRATADOS INDIVIDUALMENTE NO PLANO DOCUMENTAL, SEM RECLASSIFICAÇÃO OFICIAL**;
4. matriz oficial: **149 disponíveis / 33 condicionados — INALTERADA**;
5. `C-F05-05`: **PARCIALMENTE ATENDIDA — INALTERADA**;
6. mapeamento lógico-físico: **MINUTA NÃO ENCERRADA**;
7. `PT-*`: **ZERO AVALIADOS**;
8. estrutura física real e implementação: **INEXISTENTES**;
9. linha mestre `v0.20/v0.24/v0.19`: **INALTERADA**;
10. próximo ato: **DECISÃO HUMANA SOBRE `PD-G1` A `PD-G7` E ACEITE DE E5-02**.
