# E7-02 — MAPEAMENTO FÍSICO PROPOSTO DO PRIMEIRO RECORTE

## MINUTA v0.2 — DECISÕES A/A/A/A INCORPORADAS — AGUARDANDO ACEITE — SEM IMPLEMENTAÇÃO

| Campo | Valor |
|---|---|
| Projeto | Dev_Ecossistema_Integrado_Gestao_Empresarial |
| Escopo / unidade | ESC-F05-07 / UT-F05-07-02 |
| Data documental | 20/09/2026 |
| Responsável humano | Eduardo Andrade Ramos |
| Recorte | A — identidade, evidência, histórico, segregação e qualidade do dado |
| Antecedente | E7-01 v0.3 aceito e publicado; UT-F05-07-01 concluída por autorização humana |
| Estado desta entrega | UT-02 iniciada; E7-02 v0.2 consolidado para aceite; unidade não concluída; não publicado |
| Linha mestre preservada | REG-CONSOLIDACAO-CHATS v0.22 / REG-DECISOES v0.26 / REG-PENDENCIAS v0.21 |

## 1. Autoridade e conclusão do antecedente

A manifestação humana “Autorizado a conclusão de UT-F05-07-01 e a prosseguir com à UT-F05-07-02, cuja execução documental já está autorizada” autoriza expressamente a conclusão de UT-01 e a continuidade documental. Fica formalizada a conclusão de UT-F05-07-01 neste registro de execução, sem alterar mestres ou atribuir DEC/PEN.

E7-01 v0.3 foi publicado em 04_Aprovadas/ no commit be67fdd7a9afa5296df1d0d5e2497597ddd3a46f, blob 7a5a480c665acbfd5b92db41cad3b68213a6bb71. Os 23.594 bytes publicados foram relidos e coincidem com os bytes aceitos. A autorização de conclusão e prosseguimento sucede esse resultado conferido; não se exige repetição do ato.

UT-F05-07-02 está iniciada. Após receber E7-02 v0.1, o humano manifestou “A/A/A/A”, adotando DF-01-A, DF-02-A, DF-03-A e DF-04-A, na ordem apresentada. Esta v0.2 incorpora essas quatro decisões expressas. A escolha não é tratada como aceite antecipado do documento consolidado, autorização de publicação ou conclusão da unidade.

## 2. Resultado executivo

Adota-se, no desenho documental, concentrar a escrita autoritativa do núcleo transversal no arquivo Operacional, com referências verificáveis a partir do Financeiro. Isso evita duas ocorrências editáveis do mesmo metadado. A alternativa de distribuição por arquivo proprietário permanece registrada na seção 12 como não selecionada.

A proposta transporta nominalmente os 123 campos de E2-03A, confrontados com a lista de E-ESC-01 e com E2-03B, e aplica complementos posteriores de E5-03. Os nove objetos PF são referências de origem; as projeções e associações propostas não equivalem a novos objetos de negócio ou promoções TRT.

Foram decididos: distribuição central no Operacional, associações por identidade tipada com conferência do alvo real, datas/instantes em texto canônico e valores antes/depois em JSON tipado, além de histórico por eventos apensos e versões com manifestos. Permanecem reservados a E7-03 os parâmetros e procedimentos concretos descritos na seção 11. A consolidação dessas escolhas não declara prontidão para construção.

## 3. Fontes e conferência das entradas

A árvore Git corrente foi consultada no commit be67fdd7a9afa5296df1d0d5e2497597ddd3a46f. E7-01 possui o blob e tamanho esperados. E2-03A/B foram recuperados e seus hashes coincidem com as identidades registradas na linha mestre. Não se declara nova presença remota autônoma dessas fontes quando sustentadas pela cadeia documental.

E-ESC-01 utiliza a ocorrência publicada expressamente escolhida pelo humano: 79.274 bytes, SHA-256 e90cab7766359d9a7528f0757a2e91de53fc05b8eed67f39aaae369bf2777d7e. A identidade histórica com LF adicional permanece distinta. Citações históricas de E2-03A/B a essa identidade antiga não são corrigidas.

As condições correntes de E5-03 prevalecem no seu alcance: UUIDv7 textual canônico, SHA-256 quando aplicável, famílias de vínculos com integridade tipada e extensões dos objetos já aprovados. A vigência funcional continua cumulativa com REV-FUNC-002/004 e decisões posteriores que limitam alertas a desvios operacionais verificáveis.

### Manifesto das fontes centrais

| Fonte | Bytes | SHA-256 |
|---|---:|---|
| E7-01_PLANO-DE-ENTRADAS-E-ESPECIFICACAO-DO-PRIMEIRO-RECORTE_v0.3_2026-09-20_MINUTA.md | 23594 | 2f17665af2a01fbf5ffcca75c05b9d8141f29661794ed0a6ea79ef3c92f7fae0 |
| E2-03A_DICIONARIO-FISICO-DO-NUCLEO-TRANSVERSAL_v0.1_2026-09-16.md | 55879 | 06ae2e9c69525fb9a2b04c413181669b9b6a2ff64c342becbf64b338347beae4 |
| E2-03B_MAPA-LOGICO-FISICO-DO-NUCLEO-TRANSVERSAL_v0.1_2026-09-16.md | 53882 | bb951f7a7c768877d036718d4c807e7d80804f3249381885517a1992607f216e |
| e7_transversal.md | 79274 | e90cab7766359d9a7528f0757a2e91de53fc05b8eed67f39aaae369bf2777d7e |
| E5-03_CATALOGO-E-MAPA-LOGICO-FISICO-CONSOLIDADOS-EM-MINUTA_v0.1_2026-09-18.md | 41433 | 03048c54a80b29f211d8d8f52f2611b233d2161305faeb4525d089dd4440c9fc |

As demais fontes funcionais, arquiteturais e os três mestres conservam as identidades de E7-01 §3.1. Este produto não refaz as avaliações E6. O inventário abaixo trata de desenho proposto, sem recertificar o universo de 182 detalhes.

## 4. Distribuição por arquivo — DF-01-A ADOTADA DOCUMENTALMENTE

Arquivos adotados: EIGE_ARQ-OP_v0.1.xlsx e EIGE_ARQ-FIN_v0.1.xlsx. Estruturas nativas do Excel são autoritativas; Power Query continua auxiliar e não constitui requisito de execução deste recorte.

| Objeto de origem | Arquivo de escrita proposto | Aba / tabela candidata | Tratamento |
|---|---|---|---|
| PF-01 | Operacional | Objeto_Identidade / tbObjetoIdentidade | Identidade e versão; não duplica cadastro de domínio |
| PF-02 | Operacional | Referencia_Externa / tbReferenciaExterna | Referência compartilhável conforme E5-03 |
| PF-03 | Operacional | Fonte_Evidencia / tbFonteEvidencia | Fonte/evidência no mesmo contêiner com eixos de classificação distintos |
| PF-04 | Operacional | Vinculo_Evidencia / tbVinculoEvidencia | Associações tipadas, não simples par tipo+ID sem validação |
| PF-05 | Operacional | Evento_Auditoria / tbEventoAuditoria | Eventos apensos; consultas do estado corrente separadas |
| PF-06 | Operacional | Vinculo_Empresarial / tbVinculoEmpresarial | Identidade de empresa vinda do cadastro aprovado |
| PF-07 | Operacional | Dimensao_Temporal / tbDimensaoTemporal | Precisão e eixos temporais preservados |
| PF-08 | Operacional | Estado_Preenchimento / tbEstadoPreenchimento | Referência ao componente lógico, nunca à posição da célula |
| PF-09 / CAT-06 | Operacional | Linhagem / tbLinhagem | Elos; nós em projeção separada No_Linhagem / tbNoLinhagem |
| CAT-02 de E5-03 | Operacional | Vinculo_Referencia / tbVinculoReferencia | Associação objeto–referência compartilhável |
| ALERTA vigente | Operacional | Alerta / tbAlerta | Realização proposta do objeto existente, sem objeto paralelo |
| REL-03 de E5-03 | Operacional | Evento_Alerta / tbEventoAlerta | Associação explícita muitos-para-muitos |

São 13 tabelas candidatas: nove contêineres PF, projeção de nós, vínculo de referência, ALERTA e associação evento–alerta. DF-01-A/DF-02-A fixam essa distribuição no desenho consolidado. Nomes e campos estão submetidos ao aceite desta v0.2; não constituem estrutura executável autorizada.

O Financeiro referencia IDs e a versão publicada do conjunto transversal. Não contém segunda cópia autoritativa dessas tabelas nesta alternativa. Eventual visão de leitura conserva origem e versão; não é editável como substituição da fonte. O cadastro mestre permanece na localização já adotada em Projetos; este desenho não cria cadastro empresarial alternativo.

O recorte ainda não cria fatos financeiros. Na futura incorporação desses fatos, a solução deverá definir como o evento financeiro alimentará a trilha central; esta proposta não presume sincronização automática ou gravação cruzada. Se o recorte precisar dessa execução para funcionar, ampliar o desenho exige decisão de impacto antes de construir.

## 5. Tipos e representação — DF-03-A ADOTADA DOCUMENTALMENTE

| Classe | Armazenamento proposto | Preservação/limite |
|---|---|---|
| UUIDv7 interno | Texto, 36 caracteres canônicos em minúsculas | Decisão lógica herdada de E5-03; não gerar por linha, posição ou fórmula volátil; IDs históricos não serão reescritos |
| Referência a ID | Texto com alvo tipado e existente | Identidade de origem preservada; não forçar UUID em RN/RF/CA ou número externo |
| Código de domínio | Texto de vocabulário controlado | Vocabulários já aprovados; extensões exigem decisão |
| Texto e referência externa | Texto literal | Não converter número externo, zeros à esquerda ou conteúdo em fórmula |
| DATA | Texto canônico AAAA-MM-DD, validado como data civil | Escolha física adotada em DF-03-A; não inventar horário; visão derivada pode apresentar formato local |
| INSTANTE | Texto com precisão e deslocamento informados | Preservar fuso; ausência de fuso não autoriza Z ou deslocamento presumido |
| COMPETENCIA | Ano e mês declarados, sem dia artificial | Não converter competência em primeiro dia do mês |
| Hash | Texto hexadecimal SHA-256 de 64 caracteres | Não confere autoria ou validade material |
| Antes/depois variável | Texto JSON tipado, com tipo, unidade/domínio e versão de esquema | Realização proposta da classe E5-03; nunca truncar ou interpretar como fórmula; esquema concreto em E7-03 |
| Quantidade de bytes | Inteiro exato não negativo representado como texto decimal | Comparação numérica só com conversão conferida; ausência não vira zero |

Não são fixados valores monetários, escalas financeiras ou tolerâncias neste recorte. A forma JSON é metadado documental, não código executado. Comprimentos máximos de textos e tratamento de excedentes permanecem decisões de E7-03; nenhuma truncagem silenciosa é admitida.

## 6. Dicionário de transporte dos 123 campos

Cada linha mantém o identificador do detalhe de E2-03A. Tabela/arquivo de destino seguem a seção 4. “Base” conserva a classe de origem e não redefine a matriz oficial; “Proposta” especifica o armazenamento deste desenho. As regras da seção 7 prevalecem nos campos especializados por E5-03.

| Detalhe | PF | Campo | Tipo proposto | Condição de origem | Tratamento |
|---|---|---|---|---|---|
| `DET-PF-01-F01` | `PF-01` | `id_objeto` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-01-F02` | `PF-01` | `tipo_objeto` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-01-F03` | `PF-01` | `id_objeto_principal` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-01-F04` | `PF-01` | `identificador_versao` | Texto de versão | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-01-F05` | `PF-01` | `id_antecessor` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-01-F06` | `PF-01` | `situacao_vigencia` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-02-F01` | `PF-02` | `id_referencia_externa` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-02-F02` | `PF-02` | `id_objeto` | Texto ID tipado | O | Migra para tbVinculoReferencia conforme E5-03; visão legada somente derivada |
| `DET-PF-02-F03` | `PF-02` | `tipo_referencia` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-02-F04` | `PF-02` | `valor_referencia` | Texto literal | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-02-F05` | `PF-02` | `emissor_ou_origem` | Texto verificável | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-02-F06` | `PF-02` | `escopo_referencia` | Texto literal | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-02-F07` | `PF-02` | `id_fonte_evidencia` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-02-F08` | `PF-02` | `id_evento_registro` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-02-F09` | `PF-02` | `situacao_referencia` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-03-F01` | `PF-03` | `id_fonte_evidencia` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F02` | `PF-03` | `nome_ou_denominacao` | Texto literal | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F03` | `PF-03` | `natureza_fonte` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F04` | `PF-03` | `finalidade_fonte` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F05` | `PF-03` | `referencia_verificavel` | Texto verificável | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F06` | `PF-03` | `referencia_integridade` | Texto verificável | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-03-F07` | `PF-03` | `versao_fonte` | Texto de versão | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F08` | `PF-03` | `corte_fonte` | Texto literal | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F09` | `PF-03` | `momento_captura` | Texto temporal com precisão/fuso | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F10` | `PF-03` | `ref_responsavel_captura` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F11` | `PF-03` | `situacao_classificacao` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F12` | `PF-03` | `situacao_disponibilidade` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F13` | `PF-03` | `situacao_pratica` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F14` | `PF-03` | `id_decisao_pratica` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F15` | `PF-03` | `id_conjunto_equivalencia` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F16` | `PF-03` | `situacao_conflito` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F17` | `PF-03` | `finalidade_precedencia` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F18` | `PF-03` | `id_fonte_prevalente` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F19` | `PF-03` | `id_decisao_excecao` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F20` | `PF-03` | `tipo_derivacao` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-03-F21` | `PF-03` | `id_fonte_derivada_de` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-04-F01` | `PF-04` | `id_vinculo_evidencia` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-04-F02` | `PF-04` | `id_fonte_evidencia` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-04-F03` | `PF-04` | `tipo_elemento_sustentado` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-04-F04` | `PF-04` | `id_elemento_sustentado` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-04-F05` | `PF-04` | `finalidade_do_vinculo` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-04-F06` | `PF-04` | `escopo_de_aplicacao` | Texto literal | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-04-F07` | `PF-04` | `id_evento_vinculo` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-04-F08` | `PF-04` | `situacao_vinculo` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-05-F01` | `PF-05` | `id_evento` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F02` | `PF-05` | `dominio_atingido` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F03` | `PF-05` | `tipo_objeto_atingido` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F04` | `PF-05` | `id_objeto_atingido` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F05` | `PF-05` | `identificador_versao_atingida` | Texto de versão | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F06` | `PF-05` | `id_vinculo_atingido` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F07` | `PF-05` | `tipo_evento` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-05-F08` | `PF-05` | `instante_evento` | Texto temporal com precisão/fuso | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F09` | `PF-05` | `instante_registro` | Texto temporal com precisão/fuso | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F10` | `PF-05` | `tipo_dimensao_afetada` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F11` | `PF-05` | `valor_temporal_afetado_ref` | Texto verificável | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-05-F12` | `PF-05` | `estado_anterior` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F13` | `PF-05` | `estado_posterior` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F14` | `PF-05` | `valor_anterior_ref` | JSON tipado ou referência tipada | C | Compatibilizar com JSON-TIPADO de E5-03; preservar tipo e origem; condicionamento histórico preservado |
| `DET-PF-05-F15` | `PF-05` | `valor_posterior_ref` | JSON tipado ou referência tipada | C | Compatibilizar com JSON-TIPADO de E5-03; preservar tipo e origem; condicionamento histórico preservado |
| `DET-PF-05-F16` | `PF-05` | `classificacao_anterior` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F17` | `PF-05` | `classificacao_posterior` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F18` | `PF-05` | `id_vinculo_anterior` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F19` | `PF-05` | `id_vinculo_posterior` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F20` | `PF-05` | `ref_autor` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-05-F21` | `PF-05` | `ref_executor` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F22` | `PF-05` | `ref_autoridade` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-05-F23` | `PF-05` | `natureza_execucao` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F24` | `PF-05` | `ref_origem_instrucao` | Texto verificável | C | Origem contextual opcional; ausência não impede operação |
| `DET-PF-05-F25` | `PF-05` | `justificativa` | Texto literal | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F26` | `PF-05` | `id_fonte_principal` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F27` | `PF-05` | `ref_regra_ou_decisao` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F28` | `PF-05` | `versao_regra_ou_decisao` | Texto de versão | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F29` | `PF-05` | `id_correlacao` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F30` | `PF-05` | `resultado_evento` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-05-F31` | `PF-05` | `id_evento_anterior` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-05-F32` | `PF-05` | `id_evento_substituto_ou_desfazimento` | Texto ID tipado | C | Referência reversa derivada de evento posterior; não reescrever evento original |
| `DET-PF-05-F33` | `PF-05` | `referencia_alertas_pendencias` | Texto verificável | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-06-F01` | `PF-06` | `id_vinculo_empresarial` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-06-F02` | `PF-06` | `id_objeto` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-06-F03` | `PF-06` | `id_empresa` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-06-F04` | `PF-06` | `papel_empresa` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-06-F05` | `PF-06` | `id_dimensao_temporal_inicio` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-06-F06` | `PF-06` | `id_dimensao_temporal_fim` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-06-F07` | `PF-06` | `id_evento_inicio` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-06-F08` | `PF-06` | `id_evento_fim_ou_correcao` | Texto ID tipado | C | Referência reversa derivada de evento posterior; não reescrever evento original |
| `DET-PF-06-F09` | `PF-06` | `id_fonte_evidencia` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F01` | `PF-07` | `id_dimensao_temporal` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F02` | `PF-07` | `id_objeto` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F03` | `PF-07` | `tipo_dimensao` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F04` | `PF-07` | `precisao_temporal` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F05` | `PF-07` | `valor_ano` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F06` | `PF-07` | `valor_mes` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F07` | `PF-07` | `valor_data` | Texto data civil | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F08` | `PF-07` | `valor_instante` | Texto temporal com precisão/fuso | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F09` | `PF-07` | `fuso_ou_deslocamento_informado` | Texto literal | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F10` | `PF-07` | `indicador_estimativa` | Texto de domínio | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-07-F11` | `PF-07` | `fundamento_estimativa` | Texto literal | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-07-F12` | `PF-07` | `ref_responsavel_ou_origem_estimativa` | Texto verificável | C | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-07-F13` | `PF-07` | `id_evento_registro` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-07-F14` | `PF-07` | `id_evento_confirmacao_ou_correcao` | Texto ID tipado | C | Referência reversa derivada de evento posterior; não reescrever evento original |
| `DET-PF-08-F01` | `PF-08` | `id_estado_preenchimento` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-08-F02` | `PF-08` | `id_objeto` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-08-F03` | `PF-08` | `referencia_componente` | Texto verificável | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-08-F04` | `PF-08` | `estado_qualidade` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-08-F05` | `PF-08` | `motivo_pendencia` | Texto literal | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-08-F06` | `PF-08` | `ref_responsavel_pendencia` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-08-F07` | `PF-08` | `data_pendencia` | Texto data civil | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-08-F08` | `PF-08` | `fundamento_nao_aplicavel` | Texto literal | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-08-F09` | `PF-08` | `id_evento_registro` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-08-F10` | `PF-08` | `id_evento_resolucao_ou_alteracao` | Texto ID tipado | C | Referência reversa derivada de evento posterior; não reescrever evento original |
| `DET-PF-09-F01` | `PF-09` | `id_linhagem` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F02` | `PF-09` | `tipo_no_origem` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F03` | `PF-09` | `id_no_origem` | Texto verificável | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F04` | `PF-09` | `tipo_no_destino` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F05` | `PF-09` | `id_no_destino` | Texto verificável | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F06` | `PF-09` | `tipo_relacao_linhagem` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7; condicionamento histórico preservado |
| `DET-PF-09-F07` | `PF-09` | `id_evento_registro` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F08` | `PF-09` | `id_fonte_evidencia` | Texto ID tipado | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F09` | `PF-09` | `qualidade_linhagem` | Texto de domínio | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F10` | `PF-09` | `ponto_interrupcao` | Texto verificável | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F11` | `PF-09` | `justificativa_lacuna` | Texto literal | C | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F12` | `PF-09` | `momento_registro` | Texto temporal com precisão/fuso | O | Regra de origem preservada; precedência das seções 5/7 |
| `DET-PF-09-F13` | `PF-09` | `ref_responsavel_registro` | Texto ID tipado | O | Regra de origem preservada; precedência das seções 5/7 |

Obrigatoriedade O/C de origem não representa bloqueio de negócio. Se houver dado de negócio faltante, preservam-se registro possível e alerta cabível; ID informado inexistente, formato estrutural inválido ou duplicidade estrutural são tratados localmente, sem bloquear todo o sistema. A tabela transporta nomes candidatos com a representação de tipos adotada em DF-03-A, preservando as especializações da seção 7.

## 7. Complementos e especializações de E5-03

Não se reapresentam como pendentes decisões já adotadas: UUIDv7 e SHA-256 são entradas. O que segue propõe a localização física de atributos posteriores, sem apagar os campos de origem.

### 7.1 Referência externa

PF-02 deixa de carregar diretamente um único id_objeto autoritativo. Essa associação passa a tbVinculoReferencia (E5-03 §§7.2–7.3). Colunas propostas da associação: id_vinculo_referencia, id_objeto, id_referencia_externa, finalidade, situacao_vinculo e id_evento_origem. São nomes físicos propostos para identidade/finalidade/histórico já previstos pela família CAT-02.

Na referência: origem_emissor especializa emissor_ou_origem; id_evento_cadastro corresponde a id_evento_registro. Acrescentar url_fonte, descricao_outro, data_documento, inicio_vigencia_fonte e fim_vigencia_fonte conforme E5-03. Vocabulário tipo_referencia: DOCUMENTO, IDENTIFICADOR_EXTERNO, URL_FONTE, ORIENTACAO_CASO_CONCRETO e OUTRO_DECLARADO. Situação: ATIVA, SUBSTITUIDA, INATIVA, NAO_CONFIRMADA.

Unicidade contextual: tipo + emissor + valor + escopo, após regra de normalização aprovada. Não definir normalização por inferência nem retirar ocorrência só por semelhança. E7-03 deve fixar a normalização antes da execução dessa verificação.

### 7.2 Evidência e classificação

Na tbFonteEvidencia, id_fonte_evidencia realiza id_evidencia de E5-03; nome_ou_denominacao não substitui nome_arquivo. Acrescentar tipo_evidencia, id_referencia_externa, nome_arquivo, tamanho_bytes, tipo_midia, algoritmo_integridade, valor_integridade, origem_evidencia e situacao_evidencia. capturado_em corresponde a momento_captura.

natureza_fonte, situacao_classificacao, situacao_pratica, disponibilidade e situacao_evidencia são eixos distintos. Não fundir CLASSIFICADA com ATIVA, nem tornar PRATICA em OFICIAL. referencia_integridade passa a ser apresentação derivada de algoritmo/valor, sem segunda cópia editável do hash.

Evidência com arquivo exige metadados de bytes e SHA-256 quando aplicável; evidência sem arquivo não recebe hash fictício. A integridade deve ser calculada sobre os bytes capturados, sem normalização textual. Política de preservação e nova ocorrência de evidência alterada: E7-03.

### 7.3 Eventos e histórico

id_objeto_primario de E5-03 corresponde ao alvo de PF-05; ocorrido_em/registrado_em correspondem a instante_evento/instante_registro. registrado_em passa a ser sempre identificável na ocorrência; se desconhecido historicamente, registrar a lacuna, não copiar automaticamente ocorrido_em.

Acrescentar autoridade_evento (TITULAR, SISTEMA, FONTE_DECLARADA) e origem_tecnica. Esses códigos qualificam procedência conforme E5-03; SISTEMA não vira autoridade humana nem FONTE_DECLARADA confere poder a terceiro. Preservar ref_autor, ref_executor, ref_autoridade e origem contextual separadamente.

Tipos de evento cabíveis ao recorte: CRIACAO, ALTERACAO, RETIFICACAO, CANCELAMENTO, VINCULO, DESVINCULO e ALERTA_OPERACIONAL. ESTORNO, IMPORTACAO, PAGAMENTO e RECEBIMENTO constam da fonte global, mas não autorizam processos fora deste recorte. Resultado: CONCLUIDO, CONCLUIDO_COM_ALERTA, FALHOU ou CANCELADO quando aplicável.

O campo anterior/posterior é uma ocorrência preservada. A referência do original ao evento que o sucedeu deve ser derivada por consulta ao sucessor, nunca preenchida editando o original imutável. Correção de um erro na própria trilha gera evento correlato. A trilha não exige registrar recursivamente um novo evento apenas por gravar o evento anterior.

### 7.4 Linhagem

tbNoLinhagem propõe id_no, tipo_alvo, id_alvo, classe, origem e situacao. É projeção referencial do objeto existente, com zero duplicação de fato de negócio. tbLinhagem mantém os campos PF-09 e acrescenta id_no_origem/id_no_destino conforme E5-03; identificadores e tipos legados de nós passam a projeções derivadas.

Cada elo tem exatamente dois nós distintos. DERIVA_DE, SUBSTITUI, IMPORTADO_DE, GERADO_POR e CORRIGE são tipos herdados; usar apenas os aplicáveis ao recorte. IMPORTADO_DE não autoriza importação. Não criar elo inverso duplicado para navegação reversa. Autociclo é rejeitado localmente; ciclos maiores precisam ser avaliados por tipo e não removidos por suposição.

### 7.5 ALERTA e associação com evento

tbAlerta realiza o objeto ALERTA vigente. Colunas propostas com base em REV-FUNC-004 §10 e E5-03 §7.9: id_alerta, tipo_alvo, id_alvo, id_empresa, severidade, situacao, aberto_em, motivo, ref_regra, ciencia_em, providencia, justificativa e resolvido_em. Referências a Projeto só serão usadas se existir contexto aprovado; nenhum Projeto fictício será criado.

tbEventoAlerta: id_evento e id_alerta, par único. Se a associação exigir alteração histórica, sua retirada será evento de desvínculo, não apagamento. Severidade não determina bloqueio. Ciencia não resolve. Resolvido exige tratamento subjacente; encerramento com justificativa não equivale a regularidade.

Gatilhos deste recorte: referência inválida, integridade divergente, possível duplicidade e incoerência temporal verificáveis. A parametrização exata por regra e severidade é de E7-03. Nenhum alerta por ausência de contador, advogado, parecer ou validação externa genérica.

### 7.6 Vigência e valores temporais

Os atributos transversais de E5-03 §6.4 aplicam-se somente quando o objeto for versionável. id_interno corresponde à chave própria, não a uma segunda identidade. inicio/fim_vigencia poderão ser referências a PF-07 ou valores físicos tipados conforme decisão DF-03; não manter duas fontes editáveis do mesmo instante.

RASCUNHO, VIGENTE, SUBSTITUIDO, ENCERRADO e CANCELADO qualificam vigência; não substituem os estados próprios de fonte, prática, alerta ou negócio. Ano/mês/data/instante devem corresponder à precisão declarada. Ausência de horário não é meia-noite; ano não é data em 1º de janeiro. A comparação de instantes sem fuso suficiente deve informar indeterminação.

## 8. Integridade referencial — DF-02-A ADOTADA DOCUMENTALMENTE

Adota-se registro central de identidades com tipo controlado e validação do alvo real. Ele é uma projeção de identidade, não novo cadastro material. Relações genéricas só são admissíveis com contrato fechado de tipos, teste documental de existência e correspondência com o contêiner específico.

Para cada referência interna, o desenho exige: tipo esperado, ID existente no registro de identidades, ocorrência correspondente no contêiner daquele tipo e chave única. Validar apenas a existência do UUID em qualquer tabela é insuficiente. A lista nominal de tipos permitidos e seus contêineres será fixada em E7-03, como domínio físico ativo, e deverá estar aceita antes de qualquer construção autorizada. A decisão DF-02-A aprova o mecanismo documental, sem ativar tipos de domínio não selecionados.

Referência ainda desconhecida permanece qualificada como pendente quando permitido. Referência informada e inválida é erro estrutural local. Não usar ID zero, “a definir” ou identidade aleatória como FK.

| Relação | Cardinalidade preservada | Realização documental proposta |
|---|---|---|
| Objeto–versões | 1 para 0..* | id_objeto_principal; predecessor sem sobrescrita |
| Objeto–referências | 1 para 0..* vínculos | tbVinculoReferencia; referência compartilhada sem cópia |
| Evidência–elemento | muitos para muitos | tbVinculoEvidencia com alvo tipado, finalidade e situação |
| Objeto–eventos | 1 para 0..* | alvo existente; origem e autor separados |
| Objeto–empresa | 1 para 0..* vínculos | empresa de cadastro aprovado; não inferir papel de faturadora |
| Objeto–tempo/qualidade | 1 para 0..* | dimensão/componente identificados; aplicabilidade preservada |
| Evento–correção | 1 para 0..* sucessores | sucessor aponta original; reverso derivado |
| Fonte–derivação | 1 para 0..* | derivação explícita; cópia técnica não é novo fato |
| Fonte prevalente | zero ou uma por finalidade/contexto | conflito pendente se não houver escolha competente |
| Elo–nós | 1 origem e 1 destino distintos | projeção referencial validada; sem inverso duplicado |
| Evento–alerta | muitos para muitos | associação explícita sem duplicar evento/alerta |

As 14 relações de E2-03A §9 permanecem rastreáveis; a tabela acima agrupa sua realização e incorpora relações de E5-03, sem reclassificar seus detalhes. Cardinalidades de negócio continuam condicionadas às fontes de domínio.

## 9. Sequência de formação e consultas descritas

Sequência documental proposta: identificar o objeto válido de origem; reservar sua identidade estável; registrar o objeto e seu evento de origem como conjunto correlato; associar evidência/vínculo depois que os alvos existirem; conferir referências antes de publicar o conjunto. Registro central não deve criar uma versão falsa do negócio para satisfazer a trilha.

No Excel sem mecanismo transacional implementado, não se promete atomicidade. O estado intermediário precisa ser identificável como incompleto, e uma interrupção precisa permitir retomada sem duplicar IDs. O procedimento concreto e seus cenários ficam em E7-03/E7-04. Aceitar o desenho documental não comprova que colar dados não contorne validações.

Consultas previstas, sem fórmulas executáveis: resolver referência por tipo+ID+versão; localizar eventos do objeto; localizar sucessores do evento original; listar evidências por alvo/finalidade; comparar hash observado e registrado; consultar antecessores/descendentes de linhagem; listar alertas ativos; distinguir valor conhecido, zero, ausência, pendência e N/A. Falta de informação não produz dado preenchido por inferência.

## 10. Preservação de histórico — DF-04-A ADOTADA DOCUMENTALMENTE

Adota-se separar tabelas de eventos apensos das visões correntes e publicar versões documentadas do conjunto, com manifesto de integridade e proteção contra alteração acidental. A proteção da planilha não será apresentada como imutabilidade, autenticação ou trilha inviolável.

Correções ficam em novos eventos. As visões correntes poderão ser reconstruídas da sequência válida conforme regra aprovada. Cópias publicadas e seus manifestos devem permitir confronto posterior; a política de retenção, pasta de evidências, backup e restauração será proposta em E7-03. Nenhum snapshot ou controle novo foi executado nesta unidade.

Se o nível de garantia exigido pressupuser registro automático inviolável, o desenho nativo manual não é suficiente; deverá ser reavaliado antes da construção, em ato próprio. Nenhuma macro, script, serviço externo ou integração recebe autorização por esta proposta.

## 11. Rastreabilidade de cobertura e diferimentos

| Âncora | Realização proposta | Limite |
|---|---|---|
| CA-RF-03-001-01 a 04 | PF-08; campos tipados; metadados de incompletude | Zero permanece no valor material; domínio completo fora do recorte |
| CA-RF-03-004-01/02 | Identidade, evento apenso, predecessor e reverso derivado | Garantia técnica e teste de recuperação ainda não demonstrados |
| CA-RF-03-004-03/04 | Vínculo empresarial e classificação de prática | Sem consolidação financeira nem promoção automática de regra |
| CA-RF-03-050-01 a 04 | Evidência, equivalência, finalidade e precedência | Modelo distinto não recebe precedência; conflito permanece explícito |
| CA-RF-03-050-05/06 | Natureza oficial/prática e decisão correlata | Sem apuração oficial ou validação material inferida |

E7-03 deverá fixar: domínios físicos ativos, comprimentos, esquema de valor tipado, normalização contextual, precisão temporal, controle de IDs, política de arquivos/evidências, parâmetros de alertas e retenção. E7-04 deverá descrever os cenários de carga interrompida, duplicidade, referência ausente, correção de evento, equivalência indevida e recuperação. Nenhum desses testes foi executado.

Os 33 detalhes permanecem TRT-04. A enumeração de campos e complementos não altera 149/33, não cria novo inventário oficial e não conclui C-F05-05. 4H.5 não é reconstruída; não se especificam fórmulas de saldo neste recorte. Mapeamento global e Fase 05 permanecem abertos.

## 12. Decisões materiais adotadas pelo humano

Os rótulos DF-01 a DF-04 são locais deste produto; não são DEC/PEN oficiais.

| Decisão | Alternativa A — adotada | Alternativa B — não selecionada | Efeito da escolha |
|---|---|---|---|
| DF-01 — Distribuição | Núcleo autoritativo central no Operacional; Financeiro referencia origem/versão | Cada arquivo mantém os metadados de seus próprios objetos; consultas unificadas somente derivadas | B exige definir propriedade, referências cruzadas e evitar dupla identidade antes de consolidar |
| DF-02 — Vínculos | Registro de identidades tipadas com conferência do alvo no contêiner específico | Tabelas de associação distintas por tipo de alvo | A reduz tabelas mas exige validação tipada completa; B amplia quantidade e explicita FKs por tipo |
| DF-03 — Datas e valores | Datas/instantes como texto canônico com precisão explícita; antes/depois em JSON tipado | Datas civis nativas e valores variáveis decompostos por tipo, mantendo fuso/precisão separados | B exige esquema de colunas adicional; nenhuma opção autoriza perda de precisão |
| DF-04 — Histórico | Eventos apensos, visões correntes e versões publicadas com manifestos; limites do Excel explícitos | Adiar aceitação do mecanismo até desenho de automação de trilha em escopo próprio | A permite detalhamento documental atual; B não autoriza implementar automação |

A manifestação humana “A/A/A/A” adotou expressamente as quatro alternativas A. A presente v0.2 consolida seus efeitos nas seções 4, 5, 8 e 10. As alternativas B ficam preservadas apenas como histórico comparativo; não são caminhos ativos. Os parâmetros de E7-03 deverão respeitar as quatro decisões, sem reabri-las por inferência.

## 13. Conferência, aceite e estado resultante

Conferência documental desta produção: 123 IDs de campo distintos transportados de E2-03A; todos encontrados em E2-03B; nove objetos de origem preservados. Identidades físicas de E2-03A/B coincidem com as registradas; E7-01 coincide com seu blob publicado. A cobertura de três RF/14 CAs permanece parcial no alcance transversal.

Consolidação realizada: decisões da seção 12 recebidas; destinos documentais fixados conforme DF-01-A/DF-02-A; representação de dados e histórico compatibilizada com DF-03-A/DF-04-A; campos e associações preservados; dependências de E7-03/E7-04 explícitas. Permanecem necessários o aceite de E7-02 v0.2, a autorização e conferência de sua publicação e a conclusão formal de UT-F05-07-02.

Estado: UT-F05-07-01 CONCLUÍDA DOCUMENTALMENTE; UT-F05-07-02 INICIADA; E7-02 v0.2 EM MINUTA CONSOLIDADA, AGUARDANDO ACEITE; DF-01-A, DF-02-A, DF-03-A E DF-04-A ADOTADAS DOCUMENTALMENTE; UT-03 A UT-05 AUTORIZADAS, NÃO INICIADAS POR DEPENDÊNCIA. SEM PUBLICAÇÃO DESTA MINUTA, ALTERAÇÃO DE MESTRES OU IMPLEMENTAÇÃO.

### 13.1 Controle desta revisão

Antecedente preservado: E7-02_MAPEAMENTO-FISICO-PROPOSTO-DO-PRIMEIRO-RECORTE_v0.1_2026-09-20_MINUTA.md, 42.731 bytes, SHA-256 c140a9f49fa2a1d31bf60b5d1072e2f9acf8edfb8f7631d73f0cb225627f75df.

Esta revisão incorpora exclusivamente a escolha A/A/A/A e explicita os diferimentos já atribuídos a E7-03. O dicionário dos 123 campos e as especializações de E5-03 foram preservados. Não houve nova avaliação de portões, alteração de fonte, registro mestre ou classificação TRT. A linha mestre v0.22/v0.26/v0.21 e todas as ressalvas vinculantes permanecem.
