# E8-03 — CATÁLOGO DE DECISÕES E TRATAMENTO DE L-01 A L-07

## MINUTA CONSOLIDADA v0.2 — ALTERNATIVAS A INCORPORADAS — AGUARDANDO ACEITE — SEM IMPLEMENTAÇÃO

**Projeto:** Dev_Ecossistema_Integrado_Gestao_Empresarial  
**Fase:** Fase 05  
**Escopo:** ESC-F05-08 — Fechamento documental do primeiro pacote de configuração controlada  
**Unidade:** UT-F05-08-03 — Decisões de configuração e lacunas  
**Produto:** E8-03 — Catálogo de decisões e tratamento de L-01 a L-07  
**Responsável humano:** Eduardo Andrade Ramos  
**Data:** 21/09/2026  
**Estado:** MINUTA CONSOLIDADA PARA ACEITE  

---

## 1. Autoridade e objeto desta revisão

O Gestor manifestou `A/A/A/A/A/A/A` em resposta ao catálogo E8-03 v0.1. A sequência corresponde, na ordem, aos pacotes `D8-L01`, `D8-L02`, `D8-L03`, `D8-L04`, `D8-L05`, `D8-L06` e `D8-L07`.

Esta v0.2 incorpora exclusivamente essas sete escolhas. A manifestação decide o mérito documental das alternativas, mas não constitui aceite antecipado desta versão consolidada, não autoriza sua publicação, não conclui UT-F05-08-03 e não autoriza implementação.

## 2. Estado de entrada conferido

E8-02 v0.1 foi aceito, publicado e conferido no caminho `04_Aprovadas/E8-02_MATRIZ-NOMINAL-DE-REALIZACAO-DO-PRIMEIRO-RECORTE_v0.1_2026-09-21.md`, commit `0d581bd88b7f7b85b53fcfa8491711c7a1c589af`, Git blob `021598b13051a91e04632415c64cf3dcc05566bd`, com 114.158 bytes e SHA-256 `2ecfa1fff3578b1c4d3221e5181cc11bc808aaee931e8e39df563dab671a6851`.

UT-F05-08-01 e UT-F05-08-02 estão concluídas. UT-F05-08-03 está iniciada exclusivamente no alcance documental.

| Controle de E8-02 | Estado |
|---|---:|
| Detalhes oficiais | 123/123, únicos |
| Condição de origem | 56 O / 67 C |
| Complementos controlados | 52 |
| Contêineres candidatos representados | 13/13 |
| Linhas oficiais `APLICAVEL` | 41 |
| Linhas oficiais `DIFERIDO` | 82 |
| Cenários executados | 0/30 |
| Estruturas físicas criadas | 0 |

## 3. Regra de incorporação e interpretação

As alternativas A foram adotadas individualmente. Elas formam o estado documental resultante de E8-03, sem eliminar condições materiais que dependem de fonte, ambiente, cadastro, ferramenta, capacidade ou prova futura.

Para cada ocorrência de E8-02:

1. o identificador da linha e sua correspondência nominal permanecem inalterados;
2. a marca `L-01` a `L-07` remete ao tratamento correspondente deste documento;
3. a parcela sustentada por fonte vigente pode seguir documentalmente conforme o tratamento adotado;
4. a parcela sem fonte, alvo, ambiente ou prova permanece `INATIVA` ou `DIFERIDA`;
5. nenhuma escolha converte desenho documental em funcionamento comprovado;
6. nenhuma lacuna é preenchida por valor, relação, calendário, destino ou regra presumidos.

Uma mesma linha pode acumular tratamentos. Todos os tratamentos incidentes devem ser satisfeitos para que sua parcela dependente deixe de estar diferida.

## 4. Quadro consolidado das decisões

| Ordem | Pacote | Incidências em E8-02 | Escolha humana | Estado documental resultante |
|---:|---|---:|:---:|---|
| 1 | D8-L01 — Alvos materiais | 31 | A | registro fechado por relação; alvo sem fonte nominal permanece inativo |
| 2 | D8-L02 — Vocabulários | 40 | A | compilação literal por campo/fonte/versão; domínio não sustentado permanece inativo |
| 3 | D8-L03 — UUIDv7 e escrita | 13 | A | requisitos do gerador local fixados; seleção e prova material permanecem futuras |
| 4 | D8-L04 — Calendário | 9 | A | revisão por uso preservada; calendário somente por fonte concreta e decisão própria |
| 5 | D8-L05 — Destino e recuperação | 2 | A | requisitos de isolamento, independência e recuperação fixados; ambiente não criado |
| 6 | D8-L06 — Retenção | 8 | A | preservação integral durante EC-01 a EC-06 e até política operacional aceita |
| 7 | D8-L07 — Autoridade temporal | 38 | A | evento/ocorrência como autoridade; estado corrente e visões como derivações |

As incidências não são somáveis, porque uma linha pode depender de mais de uma lacuna.

## 5. DECISÃO D8-L01-A — Registro fechado por relação

**Decisão incorporada.** Cada campo de referência usará uma lista fechada de tipos, contêineres, chaves e fontes autorizadoras. Não haverá alvo genérico irrestrito.

### 5.1 Tipos técnicos admitidos

| Tipo técnico | Contêiner | Chave |
|---|---|---|
| REFERENCIA_EXTERNA | tbReferenciaExterna | id_referencia_externa |
| FONTE_EVIDENCIA | tbFonteEvidencia | id_fonte_evidencia |
| VINCULO_EVIDENCIA | tbVinculoEvidencia | id_vinculo_evidencia |
| EVENTO_AUDITORIA | tbEventoAuditoria | id_evento |
| VINCULO_EMPRESARIAL | tbVinculoEmpresarial | chave própria prevista em PF-06 |
| DIMENSAO_TEMPORAL | tbDimensaoTemporal | chave própria prevista em PF-07 |
| ESTADO_PREENCHIMENTO | tbEstadoPreenchimento | chave própria prevista em PF-08 |
| LINHAGEM | tbLinhagem | chave própria prevista em PF-09 |
| NO_LINHAGEM | tbNoLinhagem | id_no, como projeção do alvo existente |
| VINCULO_REFERENCIA | tbVinculoReferencia | id_vinculo_referencia |
| ALERTA | tbAlerta | id_alerta |

### 5.2 Efeito vinculante

- `id_evento`, `id_fonte_evidencia`, `id_referencia_externa`, `id_no` e `id_alerta` apontam apenas ao tipo nominal esperado;
- empresa, responsável, autor, executor, autoridade e objeto material somente podem ser associados quando uma fonte vigente identificar ocorrência, contêiner e chave;
- cadastro mestre em Projetos permanece preservado; esta decisão não cria cadastro alternativo;
- tipo material fora da lista ou dependente de novo módulo exige ato de ampliação ou revisão arquitetural;
- relação sem alvo material nominal permanece inativa, preservando a parcela independente da linha.

**Resultado:** L-01 recebe tratamento documental suficiente para EC-01, com condicionamento explícito das relações materiais ainda sem fonte. Não há resolução física nem autorização de criação de alvo.

## 6. DECISÃO D8-L02-A — Compilação fechada e inativação seletiva

**Decisão incorporada.** Cada campo de domínio deverá possuir fonte autoritativa, ocorrência ou versão, lista literal e regra de aplicabilidade. Valor não será escolhido por conveniência ou como padrão para preencher ausência.

### 6.1 Grupos já admitidos, sem ampliação

Permanecem os grupos fechados de E7-03: vigência; referência externa; situação da referência; evento; resultado de evento; procedência da autoridade do evento; linhagem aplicável; situação do alerta; severidade.

Esses grupos somente são aplicados aos campos aos quais a fonte os vincula. Não se fundem vigência, classificação, disponibilidade, prática, qualidade ou preenchimento.

### 6.2 Efeito vinculante

- fonte e versão devem acompanhar cada compilação literal;
- conflito entre ocorrências exige reconciliação ou decisão humana;
- domínio sem fonte nominal permanece `INATIVO_L02`;
- ausência de um domínio não invalida a parcela independente da linha;
- lista candidata ou inferida não se torna domínio ativo.

**Resultado:** L-02 recebe regra documental de fechamento por campo. As ocorrências sem vocabulário literal sustentado permanecem inativas até complemento de fonte, sem impedir a avaliação das demais parcelas.

## 7. DECISÃO D8-L03-A — Gerador local controlado e prova futura

**Decisão incorporada.** Novas identidades internas permanecem em UUIDv7 canônico. O mecanismo futuro deverá ser local ao ambiente autorizado e atender, no mínimo:

- implementação e versão identificadas;
- geração fora de número de linha, contagem ou fórmula volátil;
- validação de formato canônico antes da confirmação;
- verificação local de colisão;
- registro do mecanismo e da ocorrência de escrita;
- preservação de identificador reservado após interrupção;
- retomada pela mesma identidade, com reconciliação anterior a novas linhas.

A escolha não nomeia biblioteca, produto ou serviço, porque o ambiente construtivo não foi autorizado. Seleção concreta, geração, escrita e demonstração permanecem exigências futuras.

**Resultado:** L-03 está tratada documentalmente quanto aos critérios de seleção e prova. As 13 incidências continuam condicionadas à demonstração material antes de qualquer carga autorizada.

## 8. DECISÃO D8-L04-A — Calendário específico por fonte

**Decisão incorporada.** Revisão por uso permanece a regra geral. Uma fonte somente recebe revisão calendárica se houver, cumulativamente:

1. fonte nominalmente aprovada;
2. necessidade concreta de atualização por tempo;
3. frequência justificada para aquela fonte;
4. marco inicial e evento de revisão;
5. responsável pela execução futura e autoridade humana para decidir impacto.

Não há frequência universal, agenda criada ou monitoramento contínuo prometido. Fonte sem frequência aprovada continua sujeita à revisão por captura, uso, substituição ou liberação de versão.

**Resultado:** L-04 recebe tratamento documental por fonte. As nove incidências não autorizam rotina ativa e permanecem condicionadas à identificação concreta da fonte e da frequência quando aplicável.

## 9. DECISÃO D8-L05-A — Destino isolado e cópia independente

**Decisão incorporada.** Antes de qualquer execução dependente, o ambiente deverá satisfazer:

- destino de trabalho separado da ocorrência publicada;
- acesso nominal e autoridade de escrita;
- capacidade verificada para o conjunto e suas evidências;
- cópia recuperável fora do mesmo conjunto de sincronização sujeito à mesma sobrescrita;
- manifesto com versão, identificadores, caminhos, tamanhos e hashes;
- cópia anterior a cada sessão de alteração e cópia verificada após versão liberada;
- restauração somente em destino separado, preservando a ocorrência atual;
- conferência de hashes, contagens, vínculos e configuração antes de promoção humana.

Histórico de sincronização isoladamente não equivale a backup independente. Esta decisão não escolhe fornecedor, não cria conta, não define permissões efetivas, não mede capacidade e não executa cópia ou restauração.

**Resultado:** L-05 recebe requisitos documentais fechados para EC-01. As duas incidências permanecem sem prova operacional e impedem afirmar backup ativo, recuperação comprovada ou prontidão de ambiente.

## 10. DECISÃO D8-L06-A — Preservação integral durante EC-01 a EC-06

**Decisão incorporada.** Todas as ocorrências abrangidas de evidência, eventos, manifestos, versões liberadas, predecessoras e retiradas lógicas serão preservadas durante EC-01 a EC-06 e até que política operacional específica seja aceita antes do uso real.

Não haverá descarte automático por idade. Retirada lógica preservará motivo e vínculo. A decisão:

- não fixa prazo legal;
- não autoriza retenção de dados pessoais sem avaliação aplicável;
- não executa descarte;
- não cria rotina de eliminação;
- exige ato humano próprio antes de qualquer eliminação futura.

**Resultado:** L-06 recebe tratamento documental conservador para as oito incidências. A retenção operacional definitiva permanece condicionada ao uso real, mas a ausência dessa política não autoriza perda no ciclo atual.

## 11. DECISÃO D8-L07-A — Autoridade histórica e corrente derivada

**Decisão incorporada.** Evento e ocorrência autoritativa sustentam o histórico. Estado corrente, reversos, projeções e visão Financeiro serão derivados, sem autoridade concorrente.

Para cada objeto e atributo temporal, a configuração deverá registrar:

- fonte autoritativa;
- precisão observada e fuso quando presente;
- início e fim de vigência quando aplicáveis;
- evento ou ocorrência que alterou o estado;
- regra de ordenação e critério de empate;
- corte e versão do conjunto liberado;
- transformação usada para obter estado corrente ou visão.

Data parcial permanece parcial; partes ausentes não são completadas. Conflito ou empate sem regra interrompe a linha afetada. Visões e projeções não podem substituir o histórico nem gravar segunda verdade. A visão Financeiro continua consumidora de referência com origem e versão explícitas.

**Resultado:** L-07 recebe modelo documental de autoridade única e reconstrução. As 38 incidências sem mapeamento nominal completo permanecem diferidas até que fonte e regra estejam registradas, sem autorizar reconstrução executada.

## 12. Aplicação às linhas de E8-02

E8-02 permanece a matriz nominal vigente; esta v0.2 não a reescreve. O tratamento aplicável é obtido pela coluna `LACUNA` de cada linha:

| Marca em E8-02 | Tratamento obrigatório | Condição residual |
|---|---|---|
| L-01 | §5 — relação fechada | alvo material sem fonte permanece inativo |
| L-02 | §6 — vocabulário literal | domínio sem fonte/versão permanece inativo |
| L-03 | §7 — requisitos do gerador | geração/escrita aguardam ferramenta e prova |
| L-04 | §8 — calendário por fonte | rotina aguarda fonte/frequência concretas |
| L-05 | §9 — destino e recuperação | ambiente, capacidade e restauração aguardam prova |
| L-06 | §10 — preservação integral | política operacional definitiva permanece futura |
| L-07 | §11 — autoridade e derivação | campo sem fonte/regra nominal permanece diferido |
| NENHUMA | E8-02 permanece aplicável | prova física continua futura quando indicada |

Linhas com múltiplas marcas acumulam todas as condições. A adoção das alternativas A não converte automaticamente as 82 linhas oficiais antes marcadas `DIFERIDO` em `APLICAVEL`: cada parcela somente muda de estado quando suas condições nominais estiverem satisfeitas. Essa avaliação cruzada pertence a E8-04 e não será antecipada aqui.

## 13. Decisões adotadas e alternativas encerradas

| Pacote | Decisão adotada | Alternativas não adotadas |
|---|---|---|
| D8-L01 | A — registro fechado por relação | associação especializada por classe; diferimento integral |
| D8-L02 | A — compilação fechada e inativação seletiva | vocabulário candidato; diferimento integral |
| D8-L03 | A — gerador local controlado e prova futura | serviço controlado; ausência de novas identidades |
| D8-L04 | A — calendário específico por fonte | calendário uniforme; somente revisão por uso |
| D8-L05 | A — destino isolado e cópia independente | repositório administrado definido antecipadamente; controles integralmente inativos |
| D8-L06 | A — preservação integral no ciclo | política por classes antecipada; congelamento indefinido sem marco |
| D8-L07 | A — histórico autoritativo e corrente derivada | instantâneo autoritativo; ausência de visão corrente |

As alternativas não adotadas permanecem somente como histórico comparativo da v0.1. Não são caminhos simultaneamente ativos.

## 14. Rastreabilidade e não criação de registros oficiais

As escolhas `D8-L01-A` a `D8-L07-A` são identificadores locais deste produto. Não criam automaticamente decisões `DEC-*`, pendências `PEN-*`, regras de negócio, requisitos funcionais ou componentes arquiteturais. Qualquer atualização futura dos registros mestres observará o princípio do único publicador e dependerá do marco próprio.

Linha mestre preservada: `REG-CONSOLIDACAO-CHATS v0.23`, `REG-DECISOES v0.27` e `REG-PENDENCIAS v0.22`.

## 15. Critérios de parada e preservações

Interromper a parcela afetada diante de:

- divergência física ou identidade não conferida;
- ausência de fonte obrigatória;
- conflito material não reconciliado;
- necessidade de nova RN, RF ou CA;
- revisão arquitetural ou ampliação do Recorte A;
- tentativa de criar estrutura, dado, agenda, cópia ou controle real;
- tentativa de executar teste, migração ou implantação.

Permanecem preservados: matriz oficial `149/33`; 33 detalhes em `TRT-04`; zero em `TRT-05`; `C-F05-05` parcialmente atendida; `ALT-04`; `C-F05-09`; 4H.5 não comprovado; mapeamento global aberto; inventário de 67 itens; estados dos portões; ocorrências físicas distintas de E2-03C e E-ESC-01; todas as ressalvas vinculantes de E6/E7.

## 16. Resultado proposto e próximo ato humano

**PROPOSTA DE RESULTADO DE UT-F05-08-03:** as sete decisões requeridas foram manifestadas pelo Gestor e incorporadas com efeitos, inativações, diferimentos e marcos explícitos. E8-03 v0.2 está apto à revisão humana, sem declarar configuração executável completa.

O próximo ato é aceitar, solicitar ajuste ou rejeitar E8-03 v0.2. Em caso de aceite, a publicação exige autorização expressa. A conclusão formal de UT-F05-08-03 exige ato humano próprio após a publicação conferida. UT-F05-08-04 permanece autorizada, mas não se inicia antes da conclusão da antecedente.

**Estado de saída:** UT-F05-08-01 e UT-F05-08-02 concluídas; UT-F05-08-03 iniciada; E8-03 v0.2 em minuta consolidada, aguardando aceite; `D8-L01-A` a `D8-L07-A` incorporadas documentalmente; UT-F05-08-04 e UT-F05-08-05 autorizadas e não iniciadas por dependência; 30 cenários não executados; Fase 05 aberta; sem implementação.
