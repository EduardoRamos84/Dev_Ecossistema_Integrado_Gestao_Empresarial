# E7-04 — PLANO DE CONSTRUÇÃO, TESTES E EVIDÊNCIAS DO PRIMEIRO RECORTE

## MINUTA v0.1 — PLANO DOCUMENTAL PARA ACEITE — SEM EXECUÇÃO DA SOLUÇÃO

| Campo | Valor |
|---|---|
| Projeto | Dev_Ecossistema_Integrado_Gestao_Empresarial |
| Escopo / unidade | ESC-F05-07 / UT-F05-07-04 |
| Data documental | 20/09/2026 |
| Responsável pelo aceite | Eduardo Andrade Ramos |
| Antecedente | E7-03 v0.2 aceita, publicada, resultado aceito; UT-F05-07-03 concluída |
| Estado corrente | UT-04 iniciada; E7-04 em minuta; não publicado; unidade não concluída |
| Linha mestre preservada | REG-CONSOLIDACAO-CHATS v0.22 / REG-DECISOES v0.26 / REG-PENDENCIAS v0.21 |

## 1. Autoridade e resultado desta produção

**SITUAÇÃO ATUAL.** O humano aceitou o resultado da publicação de E7-03 v0.2 e autorizou a conclusão de UT-F05-07-03. A unidade está concluída documentalmente. A publicação de E7-03 foi conferida integralmente: commit c86db8b7f685689d99a4e620f2952a467d856ac8, blob a924226d0cb7425e39b792d76dfc7e4d018d2c13, 30.324 bytes iguais aos aceitos. O arquivo publicado em 04_Aprovadas/ conserva os bytes da minuta aceita; seus enunciados de estágio são históricos da preparação, não revogam os atos posteriores.

A manifestação “Autorizado a prosseguir com UT-F05-07-04” permite produzir este plano documental. A definição formal de ESC-F05-07 prevê sequência por dependência, entradas por identidade, cenários, resultados esperados, segurança, migração quando aplicável, aceite e retorno, sem execução.

**PROPOSTA.** Este plano organiza a futura construção em seis etapas dependentes e descreve 30 cenários. Todos estão NÃO EXECUTADOS. As condições de aprovação aqui formuladas serão submetidas ao aceite do plano; não há declaração de desempenho, funcionamento, recuperação ou conformidade física.

**DECISÕES APROVADAS.** Recorte A; DF-01-A a DF-04-A de E7-02; PC-01-A a PC-04-A de E7-03; CT-01 a CT-11 e diferimentos L-01 a L-07 preservados. Não se solicita nova escolha desses parâmetros.

## 2. Entradas documentais fixadas

| Arquivo local de referência, com bytes aceitos | Bytes | SHA-256 |
|---|---:|---|
| E7-01_PLANO-DE-ENTRADAS-E-ESPECIFICACAO-DO-PRIMEIRO-RECORTE_v0.3_2026-09-20_MINUTA.md | 23594 | 2f17665af2a01fbf5ffcca75c05b9d8141f29661794ed0a6ea79ef3c92f7fae0 |
| E7-02_MAPEAMENTO-FISICO-PROPOSTO-DO-PRIMEIRO-RECORTE_v0.2_2026-09-20_MINUTA.md | 44318 | a36c658342d534640c0b51414d0ab1289a8547abb82b51a9d87ce7668fd3b570 |
| E7-03_ESPECIFICACAO-DE-PARAMETROS-E-CONTROLES-DO-PRIMEIRO-RECORTE_v0.2_2026-09-20_MINUTA.md | 30324 | 4a9fec4d2d3b081455d32aa2a37fbed31804c73f712613bba9730d6fdaa46c41 |

A conferência desta produção confirmou as três identidades locais acima. Não constitui nova avaliação de portões. E7-01/E7-02/E7-03 carregam as fontes funcionais, arquiteturais e mestres vigentes; os anexos antigos v0.15/v0.19/v0.14 não substituem a linha mestre corrente.

Antes de qualquer execução futura, o pacote deverá fixar também as identidades das fontes complementares efetivamente usadas e da configuração compilada. A versão aceita de E7-04 deverá entrar no manifesto posterior por seus bytes e hash; este documento não contém seu próprio hash autorreferente.

Divergência de bytes em entrada fixada interrompe o uso daquela entrada até decisão competente. Texto visualmente igual não dispensa a conferência. Permanecem as ocorrências publicadas de E-ESC-01 e E2-03C escolhidas pelo humano; não normalizar cópias para fazer hashes coincidirem.

## 3. Alcance e barreira de execução

Planeja-se o núcleo transversal no Operacional e a referência com origem/versão a partir do Financeiro, conforme E7-02. Os 123 campos transportados e suas especializações são base de correspondência, não promessa de 123 colunas físicas nem criação de objetos de negócio novos. As 13 tabelas candidatas não existem por força deste plano.

**FORA DE ESCOPO.** Implementação agora; criação dos dois arquivos Excel; fórmulas, automação, serviços, configurações de acesso; migração de legados; uso de dados reais; importação de saldos; cálculos e efeitos financeiros; implantação. O plano não autoriza ações por conter verbos de execução futura.

A futura autorização deverá identificar executor, ambiente, caminhos permitidos, saída, versão, conjunto de dados de teste e operações permitidas. O aceite documental de E7-04 não substitui esse ato. A autorização das unidades documentais de ESC-F05-07 não é autorização construtiva.

## 4. Sequência futura por dependência

| Etapa local | Entradas / dependências | Trabalho futuro previsto | Saída verificável / condição de avanço |
|---|---|---|---|
| EC-01 — Fechamento do pacote | E7-01/02/03 e fontes vigentes | Compilar configuração nominal e resolver lacunas necessárias à construção | Pacote de entradas e correspondências aceito; nenhuma dependência ocultada |
| EC-02 — Preparação isolada | EC-01 e autorização construtiva específica | Preparar destinos de teste, cópias, acesso e mecanismo selecionado | Ambiente identificado e separado, manifesto inicial, ausência de dados reais |
| EC-03 — Estruturas e identidade | EC-02; L-01/02/03/07 tratadas no alcance dependente | Realizar estruturas aprovadas, tipos, identidade, referências e escrita correlata | Inventário físico ligado ao lógico; controles de integridade passíveis de prova |
| EC-04 — Evidência, histórico e consultas | EC-03; reconstrução de estado definida | Realizar evidências, eventos, linhagem, estados, alertas e consultas do recorte | Dados sintéticos rastreáveis; tratamento de falhas e limites visíveis |
| EC-05 — Verificação e recuperação | EC-04; destino de backup disponível | Executar cenários autorizados e prova de restauração separada | Resultados observados e evidências; falhas sem ocultação; nenhum aceite automático |
| EC-06 — Revisão e retorno | EC-05 | Entregar relatório, limitações, diferenças e proposta de promoção | Decisão humana de aceite/rejeição; promoção operacional exige ato próprio |

As etapas EC são rótulos deste plano, não novas UT ou escopos criados. Não fixam calendário ou prazo sem estimativa baseada no pacote resolvido. EC-01 pode demandar novo complemento documental; E7-04 não declara que ele já existe. Uma lacuna que exija ampliar o recorte volta ao humano antes de alterar o desenho.

## 5. Tratamento obrigatório de L-01 a L-07

| Lacuna herdada | Conteúdo necessário | Momento limite / efeito enquanto aberta |
|---|---|---|
| L-01 | Tipos materiais, contêineres e chaves de objeto, empresa e responsável; fonte autorizadora | Antes da autorização da construção das relações dependentes; nenhum alvo fictício |
| L-02 | Anexo de vocabulários literais por campo, fonte/versão, aplicabilidade e valores permitidos | EC-01, antes de realizar campos dependentes; domínio sem fonte não fica ativo |
| L-03 | Seleção do gerador UUIDv7 e mecanismo de escrita; método de verificação | Seleção antes da implementação dependente; prova antes da carga autorizada; sem gerador improvisado |
| L-04 | Fontes que exigem revisão por calendário e frequência | Antes de prometer monitoramento; revisão por uso continua conforme PC-03-A |
| L-05 | Destinos, acesso, cópia independente, capacidade e recuperação | Antes de executar controles dependentes; impossibilita declarar backup ou prontidão ativos |
| L-06 | Retenção operacional definitiva e condições de descarte | Antes do uso real e de qualquer eliminação; preservação sem descarte automático mantida |
| L-07 | Autoridade temporal por atributo e regra de reconstrução por objeto/versionamento | EC-01 antes de construir visões dependentes; impedir cópias autoritativas concorrentes |

O anexo de configuração exigido por EC-01 deverá conter uma linha por campo realizado: ID lógico de origem, nome físico, arquivo/aba/tabela, chave, tipo, limite, domínio, aplicabilidade, alvo permitido, origem da regra e condição de pendência. Para campos derivados, indicar origem autoritativa e transformação; para atributo especializado, indicar a correspondência de E5-03/E7-02. O anexo deve cobrir os 123 detalhes de campo, distinguindo realização direta, associação e projeção derivada, e os complementos posteriores. Não se cria esse anexo por extrapolação neste plano.

Aceitar o diferimento mantém a lacuna aberta. E7-05 deverá levar as sete lacunas ao resultado do escopo com seus impactos, sem confundir falta de fonte/configuração com prova que só pode surgir após construção autorizada.

## 6. Dados de teste e preparação dos cenários

**PROPOSTA.** Usar exclusivamente dados sintéticos, sem cópia de nomes, documentos, contratos, valores ou identidades reais das planilhas legadas. Os rótulos O1/O2, E1/E2, V1/V2 e A1/A2 abaixo são símbolos documentais, não IDs persistíveis nem objetos novos aprovados. A instanciação só poderá usar tipos materialmente aprovados após L-01. Novos UUIDs serão gerados pelo mecanismo selecionado, sem reaproveitar esses rótulos como chave.

Cada cenário começa de uma base sintética conhecida e isolada. Cenários destrutivos de teste operam em cópias descartáveis autorizadas; a base e as evidências de tentativas anteriores permanecem. Reexecutar um caso gera tentativa identificada, sem substituir a falha anterior.

Pacotes sintéticos previstos: objeto versionável elegível O1; outro objeto O2; duas empresas de teste em tipos aprovados; evidência sintética com bytes conhecidos; fonte sem arquivo; eventos de criação e correção; par de referências semelhantes; instantes com precisão/fuso distintos; alertas nas situações previstas. A criação desses pacotes não foi executada. Não fabricar dados para ocultar lacunas de schema.

Pré-condição comum de todos os cenários: autorização específica, configuração resolvida no alcance do caso, ambiente isolado e entrada identificada. Caso sem pré-condição terá resultado NÃO EXECUTADO — DEPENDÊNCIA, nunca aprovado.

## 7. Catálogo de cenários e resultados esperados

Cada linha descreve entrada, ação futura e critério observável. Todas compartilham responsável de aceite Eduardo Andrade Ramos e estado atual NÃO EXECUTADO. A coluna evidência especifica o que deverá ser coletado, não um artefato já existente.

| ID | Entrada / ação futura | Resultado esperado | Evidência futura / âncora |
|---|---|---|---|
| T01 | Conferir manifesto com um arquivo idêntico e outro com um LF adicional | Igualdade apenas no primeiro; divergência explícita no segundo, sem normalização | Hashes/tamanhos e decisão de parada; E7-04 §2 |
| T02 | Registrar O1 com identidade nova válida; tentar formato inválido e colisão deliberada | Primeiro aceito; inválidos não confirmados localmente; O1 preservado | Chaves, contagens e respostas; CT-01 |
| T03 | Reservar ID e interromper entre objeto/evento; retomar duas vezes | Incompletude identificada; mesma identidade reconciliada, sem duplicação ou reciclagem | Estados antes/interrupção/depois; CT-01 |
| T04 | Informar referência existente no tipo errado, inexistente e válida | Só a relação válida é confirmada; demais mantidas como erro local | Alvo/tipo/contêiner e alerta ou ocorrência do lote; CT-03 |
| T05 | Comparar referência exata repetida, variação de caixa/espaço e chave contextual incompleta | Duplicidade exata distinguida de possível; nenhuma fusão; incompleta não prova unicidade | Valores originais/comparações; PC-01, CT-04 |
| T06 | Usar zero conhecido, não informado, pendente e não aplicável no mesmo atributo elegível | Quatro estados distinguíveis; zero preservado; ausência não vira zero | Valor e qualificação; PC-01, CA-RF-03-001-01/02 |
| T07 | Registrar pendência com motivo, responsável e data conhecidos; repetir com responsável desconhecido | Metadados conhecidos preservados; desconhecido explícito sem inventar ocupante | PF-08 e origem; CA-RF-03-001-03 |
| T08 | Distinguir inexistência de objeto de atributo pendente em objeto existente | Não criar linha vazia para simular objeto inexistente | Contagens/consulta; CA-RF-03-001-04 |
| T09 | Textos de 255/256, 4.000/4.001 e payloads de 16.000/16.001 pontos de código; incluir Unicode fora do plano básico | Limites medidos corretamente; excedentes preservados e identificados sem truncagem | Entrada integral, contagem e resposta; PC-01 |
| T10 | Inserir texto literal com zeros iniciais e conteúdo semelhante a fórmula, além de JSON com aspas e escapes | Valor preservado como dado; nenhuma fórmula avaliada a partir do conteúdo | Valor armazenado e tipo da célula; E7-02 §5, PC-01 |
| T11 | Antes/depois tipados válidos; depois incompatível sem declaração; esquema desconhecido | Compatibilidade no válido; demais explicitamente não conformes sem conversão silenciosa | Payload integral e motivo; CT-06, E7-VAL-1 |
| T12 | Ano, competência, data civil, instante até minuto, instante sem fuso | Precisão preservada; sem dia/segundo/fuso fictício; comparação absoluta indeterminada quando insuficiente | Valores e metadados; PC-01, L-07 |
| T13 | Início posterior ao fim em mesmo eixo comparável; repetir em eixos não comparáveis | Primeiro gera atenção; segundo não recebe conclusão temporal falsa | Comparação e motivo; CT-05 |
| T14 | Criar V1 e V2 de objeto elegível; consultar antecessor e estado corrente | V1 preservada e distinguível; corrente conforme regra nominal de L-07 | Histórico e consulta; CA-RF-03-004-01 |
| T15 | Corrigir evento anterior por evento correlato; consultar ambos os sentidos | Original preservado; sucessor aponta original; reverso derivado sem editar original | Conteúdo anterior/depois e relações; CA-RF-03-004-02 |
| T16 | Vincular O1 a empresa de teste A e O2 a B; informar empresa inexistente | Segregação e origem explícitas; vínculo inválido local; nenhum papel financeiro inferido | Vínculos/consultas; CA-RF-03-004-03, CT-03 |
| T17 | Classificar prática observada e documento oficial; registrar fórmula apenas como evidência de prática | Eixos distintos; nenhuma promoção a regra ou validação material automática | Classificação e fonte; CA-RF-03-004-04, CA-RF-03-050-05/06 |
| T18 | Duas representações sintéticas do mesmo modelo comprovado, com finalidade visual e conteúdo | Equivalência e precedência somente para finalidade sustentada; imagem não vira caso numérico obrigatório | Vínculo/finalidade/origem; CA-RF-03-050-01/02 |
| T19 | Exceção expressa sintética limitada a um caso; outro caso e outro modelo sem equivalência | Exceção não generalizada; modelos distintos sem precedência automática | Decisão vinculada, escopo e conflito; CA-RF-03-050-03/04 |
| T20 | Evidência com bytes capturados, mesmos bytes, bytes alterados e referência sem arquivo | Hash confere só nos mesmos bytes; alteração é ocorrência distinta; sem arquivo não há hash inventado | Bytes/hash/metadados; CT-02/10 |
| T21 | Elo com dois nós existentes distintos; autociclo, nó ausente e elo duplicado | Elo válido navegável nos dois sentidos sem duplicar inverso; inválidos identificados localmente | Nós/elos e consulta; E7-02 §7.4, CT-03 |
| T22 | Detectar mesma condição de alerta ativo duas vezes; declarar ciência | Não duplicar por mera releitura; ciência mantém condição ativa e história | IDs/eventos/situações; PC-03 |
| T23 | Resolver alerta sem providência; depois com tratamento/evidência; encerrar outro com justificativa | Primeira resolução recusada; resolução válida registrada; encerramento justificado não equivale a regularidade | Trilha e evidência de tratamento; CT-07 |
| T24 | Caso válido sem contador/advogado/parecer/COO/LDE; outro com desvio real crítico | Ausências opcionais não geram alerta/trava; desvio real visível sem bloqueio geral de outras operações válidas | Motivos e resultados de ambos; PC-03, CT-09 |
| T25 | Fonte usada com mudança confirmada; outra inacessível | Nova ocorrência/impacto no primeiro; segundo é verificação não realizada, sem atualização fictícia | Versões, captura e lacuna; CT-08, L-04 |
| T26 | Consultar núcleo pelo Financeiro e tentar tratar visão como origem autoritativa | Origem/versão rastreáveis; não existir segunda fonte editável do núcleo | Inventário e referências; DF-01-A, CT-09 |
| T27 | Produzir conflito de sincronização em cópias autorizadas | Preservar ocorrências; não liberar nova versão antes da reconciliação | Cópias, diferenças e decisão; CT-09 |
| T28 | Conferir cópia anterior à sessão e posterior à versão, incluindo evidências/configuração | Conjunto recuperável identificado; cópia independente comprovada, não apenas presumida pela sincronização | Manifestos, destinos e conferências; CT-10/11, L-05 |
| T29 | Restaurar versão válida em destino separado; repetir com hash divergente ou evidência faltante | Válida fica candidata a aceite; incompleta/divergente não promovida; original não sobrescrito | Manifestos, contagens, vínculos e decisão; CT-11 |
| T30 | Revisar pacote de retorno com cenário ausente e com tentativa falha seguida de correção | Ausente não conta como aprovado; falha anterior preservada; reteste identificado; sem promoção automática | Relatório e decisões; E7-04 §§8–10 |

Testes de ciclos maiores de linhagem dependem da regra por tipo, não de remoção arbitrária. Se a configuração permitir tais relações, acrescentar caso específico antes de autorizar o teste correspondente. A enumeração de 30 cenários não substitui os casos adicionais que um complemento material aprovado exigir.

## 8. Cobertura e critérios de aprovação propostos

| Âncora | Cenários | Alcance |
|---|---|---|
| CA-RF-03-001-01/02 | T06 | Ausência e zero |
| CA-RF-03-001-03 | T07 | Metadados da pendência |
| CA-RF-03-001-04 | T08 | Inexistência distinta de pendência |
| CA-RF-03-004-01 | T14 | Preservação de versão |
| CA-RF-03-004-02 | T15 | Correção posterior |
| CA-RF-03-004-03 | T16 | Empresa e origem |
| CA-RF-03-004-04 | T17 | Prática distinta de regra |
| CA-RF-03-050-01/02 | T18 | Equivalência por finalidade/layout |
| CA-RF-03-050-03/04 | T19 | Exceção limitada/modelos distintos |
| CA-RF-03-050-05/06 | T17 | Oficial/prática sem promoção |
| CT-01 | T02/03 | Identidade e retomada |
| CT-02/03/04/05/06 | T20; T04/16/21; T05; T13; T11 | Integridade e qualidade |
| CT-07/08/09/10/11 | T23; T25; T24/26/27; T20/28; T28/29 | Alertas, fontes, acesso e recuperação |

Cobertura é documental de cenários, não atendimento comprovado dos critérios. Os três RF e 14 CAs permanecem limitados ao alcance transversal. Não concluir o atendimento global de um RF pela aprovação desses casos.

**PROPOSTA de aceite futuro do lote:** cada caso aplicável com resultado observado igual ao esperado e evidência suficiente; nenhuma perda de conteúdo, identidade ambígua, sobrescrita histórica ou promoção sem autorização aceita como simples ressalva técnica. Caso não aplicável exige justificativa vinculada ao recorte e aceite humano. Caso não executado não satisfaz cobertura.

Falha suspende o avanço da parte dependente, preserva evidência e exige correção/reteste direcionado. Uma divergência que resulte de regra documental insuficiente retorna para decisão; não mudar o resultado esperado depois da execução apenas para aprovar a solução. Repetir somente os casos afetados e suas dependências justificadas. Severidade de defeito de teste não altera a severidade do alerta de negócio nem cria trava geral.

## 9. Evidências e relatório de retorno

Cada tentativa futura deverá registrar: cenário, tentativa, data/hora e precisão, executor, ambiente/versão, entradas por identidade, pré-condições, passos efetivos, resultado esperado, resultado observado, diferenças, arquivos de evidência com tamanho/hash, conclusão e responsável pelo aceite. Captura de tela auxilia a leitura, mas não substitui arquivo/valor/versão quando a prova é de integridade ou preservação.

Estados de resultado propostos: NÃO EXECUTADO, APROVADO, REPROVADO, NÃO CONCLUSIVO e NÃO APLICÁVEL JUSTIFICADO. NÃO EXECUTADO — DEPENDÊNCIA qualifica a razão, não é aprovação. Campos observados ficam explicitamente sem execução neste plano; não preencher antecipadamente com o esperado.

Pacote futuro de retorno: inventário físico realizado e diferenças frente a E7-02; configuração aceita; dados sintéticos usados; relatório por cenário/tentativa; evidências e manifestos; prova de recuperação; lacunas remanescentes; recomendação técnica separada da decisão humana. Tamanho/hash serão calculados sobre os arquivos efetivos, nunca inventados neste plano.

Publicação do resultado, transferência para pasta de uso e disponibilização para usuários exigem alcance autorizado. A aceitação de teste não autoriza migração ou operação real. O responsável humano pela decisão é Eduardo; o executor técnico será nomeado no ato construtivo. Não atribuir responsabilidade a integrante da equipe por memória ou inferência.

## 10. Migração, promoção e retorno seguro

Migração não integra a execução aqui planejada para o recorte. Planilhas legadas permanecem fontes de conhecimento. Se futuramente solicitada, exigirá plano próprio com origem/destino, mapeamento aceito, dados permitidos, reconciliação, tratamento de duplicidade, cópia de segurança e retorno, antes de qualquer carga real. Não copiar o legado para preencher lacunas de tipos ou regras.

A promoção de um conjunto testado exige pacote conferido e decisão humana específica sobre a versão e o uso. Nenhum arquivo de teste é automaticamente versão operacional. Se houver rejeição, preservar resultados e retornar à cópia/base autorizada; não apagar trilha nem restaurar sobre o único original. Restauração segue PC-04-A/CT-11 e o aceite da cópia candidata.

## 11. Conferência documental e estado resultante

Esta produção conferiu as identidades de E7-01/02/03, a existência de 30 identificadores de cenário distintos, referências aos 11 controles e aos 14 CAs do recorte, e o transporte das sete lacunas. Essa conferência diz respeito ao plano escrito; zero cenários foram executados na solução.

Não foram acrescentados parâmetros materiais para reabrir DF/PC. Sequência, cenários e critérios de aceite constituem a proposta de E7-04 a ser aceita como documento. Nenhuma fonte ou mestre foi alterado. Preservam-se matriz oficial 149/33, 33 detalhes TRT-04, C-F05-05 parcialmente atendida, ALT-04, C-F05-09 e todas as ressalvas vinculantes de ESC-F05-06/07. Fase 05 permanece aberta; mapeamento global não encerrado.

Estado: UT-F05-07-01/02/03 CONCLUÍDAS DOCUMENTALMENTE; UT-F05-07-04 INICIADA; E7-04 v0.1 EM MINUTA PARA ACEITE; UT-F05-07-05 AUTORIZADA, NÃO INICIADA POR DEPENDÊNCIA. Não há construção, teste, migração ou implantação autorizados por este produto.

Próximo passo: aceite e autorização humana de publicação de E7-04; publicação e conferência dos bytes; conclusão de UT-04 mediante ato humano; execução documental de E7-05 para conferência cruzada e proposta de resultado, sem autoencerramento do escopo ou liberação construtiva.
