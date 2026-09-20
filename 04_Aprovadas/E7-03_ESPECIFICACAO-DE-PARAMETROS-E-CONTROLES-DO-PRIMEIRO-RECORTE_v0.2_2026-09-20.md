# E7-03 — ESPECIFICAÇÃO DE PARÂMETROS E CONTROLES DO PRIMEIRO RECORTE

## MINUTA v0.2 — PC-01-A A PC-04-A INCORPORADAS — AGUARDANDO ACEITE — SEM IMPLEMENTAÇÃO

| Campo | Valor |
|---|---|
| Projeto | Dev_Ecossistema_Integrado_Gestao_Empresarial |
| Escopo / unidade | ESC-F05-07 / UT-F05-07-03 |
| Data documental | 20/09/2026 |
| Responsável humano | Eduardo Andrade Ramos |
| Recorte | A — identidade, evidência, histórico, segregação e qualidade do dado |
| Antecedente | E7-02 v0.2 aceita e publicada; UT-F05-07-02 concluída |
| Estado | Unidade iniciada; produto consolidado para aceite; sem publicação ou conclusão |
| Linha mestre | REG-CONSOLIDACAO-CHATS v0.22 / REG-DECISOES v0.26 / REG-PENDENCIAS v0.21, preservados |

## 1. Autoridade, objetivo e alcance

**SITUAÇÃO ATUAL.** O humano aceitou E7-02 v0.2, autorizou sua publicação e a conclusão formal de UT-F05-07-02. A publicação foi realizada no commit e32de2a79192cfa969d2493708b91adc603be5f3, blob be80864dea495be42e23192364eb2550327fc344, em 04_Aprovadas/E7-02_MAPEAMENTO-FISICO-PROPOSTO-DO-PRIMEIRO-RECORTE_v0.2_2026-09-20.md. A releitura integral confirmou igualdade com os 44.318 bytes aceitos. UT-F05-07-02 está concluída documentalmente por esse ato expresso.

A autorização anterior permitiu executar UT-F05-07-03 e preparar E7-03 v0.1. Após receber essa minuta e sua tabela de decisões, o humano manifestou “A/A/A/A”, adotando PC-01-A, PC-02-A, PC-03-A e PC-04-A, nessa ordem. Esta v0.2 incorpora exclusivamente essas escolhas, inclusive seus limites e diferimentos. A manifestação não é tratada como aceite antecipado da versão consolidada, autorização de publicação ou conclusão da unidade.

**DECISÃO APROVADA.** DF-01-A: núcleo autoritativo no Operacional; DF-02-A: identidades e vínculos tipados com conferência do alvo real; DF-03-A: datas/instantes em texto canônico e antes/depois em JSON tipado; DF-04-A: eventos apensos e versões com manifestos, com limites do Excel explícitos. Essas decisões não são reabertas.

**FORA DE ESCOPO.** Criar planilhas reais, fórmulas, macros, scripts operacionais, controles ativos, usuários, permissões, diretórios operacionais, integrações, migração, carga ou testes da solução. E7-04 produzirá um plano de testes, sem executá-los. Não se especificam cálculo financeiro, alíquotas, saldos, prazos de negócio ou retenção legal por inferência.

## 2. Fontes e rastreabilidade

E7-02 §§5, 8, 10 e 11 atribuem a esta unidade domínios ativos, comprimentos, esquema tipado, normalização, precisão, controle de IDs, evidências, alertas e retenção. A definição formal de ESC-F05-07 §7 admite parâmetros decididos ou diferidos com impacto explícito; não exige prova física para concluir produto documental.

| Fonte | Identidade / uso |
|---|---|
| E7-01 v0.3 | Recorte A e dependências; SHA-256 2f17665af2a01fbf5ffcca75c05b9d8141f29661794ed0a6ea79ef3c92f7fae0 |
| E7-02 v0.2 | 44.318 bytes; SHA-256 a36c658342d534640c0b51414d0ab1289a8547abb82b51a9d87ce7668fd3b570; arquivo local conferido nesta produção |
| E5-03 v0.1 | Tipos, famílias de vínculos, alertas e retenção; 41.433 bytes; SHA-256 03048c54a80b29f211d8d8f52f2611b233d2161305faeb4525d089dd4440c9fc |
| REV-FUNC-004 v1.0 | §10: situações, ciência, persistência e resolução de alertas; aplicação cumulativa com limites posteriores de E5-03 |
| REV-FUNC-002 v1.0 | Modelo de autoridade; Gestor único, origens contextuais opcionais |
| INSTR-PROJ v3.1.1 | Método, proporcionalidade, antissuposição e separação entre proposta e decisão |
| Definição formal de ESC-F05-07 v0.1 | Escopo de UT-03, parâmetros com justificativa e impacto; SHA-256 cd1b67c22d42cdf4b82bce0c80b1f6545697478e46a88fa11380bf0a05020565 |

A cadeia de fontes de E7-01/E7-02 permanece aplicável. As identidades divergentes históricas de E-ESC-01 e E2-03C continuam distintas, usando-se as ocorrências publicadas expressamente escolhidas. Esta produção não refaz os portões E6, não recertifica fontes remotas nem substitui os mestres por anexos antigos.

## 3. Convenção de parâmetros

**DECISÃO APROVADA.** Os códigos PC-01 a PC-04 agrupam escolhas materiais locais adotadas pelo humano; não são DEC/PEN oficiais. CT identifica controles documentais e L identifica lacunas locais. Nenhum desses códigos altera o inventário oficial.

Uma futura configuração deverá registrar: código do parâmetro, valor aceito, unidade quando aplicável, versão, vigência, fonte do aceite e responsável. Mudança de parâmetro cria versão; não reinterpreta silenciosamente registros históricos. Parâmetro ausente significa configuração incompleta, não valor padrão presumido.

## 4. PC-01 — Perfil de representação e qualidade adotado documentalmente

### 4.1 Comprimentos e excedentes

**DECISÃO APROVADA PC-01-A.** Limites de projeto iniciais adotados documentalmente, sujeitos à futura prova de compatibilidade. Não são apresentados como limites técnicos do Excel nem como limites do negócio.

| Classe / campos | Limite adotado | Justificativa e tratamento |
|---|---:|---|
| Identidade UUIDv7 nova | 36 caracteres canônicos | Herdado de E5-03; capacidade lógica 64 e divergência histórica 63/64 preservadas |
| SHA-256 | 64 caracteres hexadecimais | Herdado; comparação exata sobre os bytes |
| Código controlado | 64 caracteres | Margem explícita para os códigos do recorte; lista fechada continua obrigatória |
| Nome, denominação, emissor, identificador externo e texto curto | 255 caracteres | Perfil inicial legível e proporcional; número externo continua texto |
| Descrição, motivo, justificativa, providência, URL e referência verificável | 4.000 caracteres | Permite fundamentação e referências extensas sem tornar a célula depósito irrestrito |
| JSON tipado de antes/depois | 16.000 caracteres por ocorrência | Reserva maior para valor e metadados; não autoriza embutir documentos inteiros |

Contagem adotada: pontos de código Unicode do conteúdo lógico, sem contar delimitadores externos de transporte. A construção deverá demonstrar que o mecanismo escolhido mede essa unidade, inclusive com caracteres fora do plano básico. Não presumir equivalência entre a contagem adotada e qualquer função nativa.

Se houver excedente, preservar o conteúdo integral recebido, registrar a condição e solicitar revisão do limite ou referência a evidência integral quando isso for semanticamente permitido. Nunca truncar, fracionar automaticamente ou substituir o valor por resumo. Até a solução específica, a ocorrência não é declarada conforme; outras operações válidas continuam possíveis. Limites financeiros de precisão/escala permanecem fora deste recorte.

### 4.2 Normalização contextual

Critério conservador adotado: preservar literalmente valor_referencia e emissor_ou_origem. Comparação autoritativa de unicidade usa tipo + emissor + valor + escopo, com comparação textual exata e sensível a diferenças. Ausência de componente relevante impede declarar unicidade comprovada. Códigos de domínio usam sua grafia autorizada.

Espaços, acentos, caixa, pontuação, zeros iniciais e composição Unicode não são removidos da fonte. Uma comparação auxiliar que desconsidere espaços nas extremidades e caixa pode apenas apontar POSSÍVEL duplicidade para revisão; não funde registros nem decide equivalência. A forma de comparação exata deve ser demonstrada na construção, sem presumir que a comparação padrão da planilha seja suficiente.

Identidade UUIDv7 nova segue a grafia canônica já aprovada. Identificadores históricos, RN/RF/CA e números externos não são convertidos em UUID. Hash não é normalizado junto com o texto do documento.

### 4.3 Temporalidade

| Precisão declarada | Forma textual adotada | Condição |
|---|---|---|
| Ano | AAAA | Não inventar mês ou dia |
| Competência mensal | AAAA-MM | Não converter em primeiro dia do mês |
| Data civil | AAAA-MM-DD | Validar calendário; sem hora implícita |
| Hora conhecida até minuto | AAAA-MM-DDThh:mm com deslocamento, quando conhecido | Não acrescentar segundos fictícios |
| Hora conhecida até segundo | AAAA-MM-DDThh:mm:ss com deslocamento, quando conhecido | Fração somente se declarada pela fonte |
| Fração de segundo | Preservar dígitos declarados | Excedente ao perfil suportado exige tratamento explícito, sem arredondamento |

A ocorrência deve permitir recuperar precisão e fuso informado. Sem fuso conhecido, manter a lacuna identificável e não comparar como instante absoluto. Z somente para UTC conhecido. Conversão de exibição não altera o valor autoritativo. Validade, competência, fato, registro e captura são eixos distintos. Não adotar tolerância temporal de negócio. Início posterior ao fim só é desvio confirmado quando os valores forem comparáveis no mesmo eixo e precisão suficiente.

Os metadados necessários ficam nos atributos temporais de PF-07 e no valor tipado. A escolha de referência PF-07 ou valor embutido será nominal por atributo no plano de construção; só uma ocorrência será autoritativa. Até esse fechamento não se criam colunas redundantes.

### 4.4 Esquema documental de JSON tipado

**DECISÃO APROVADA PC-01-A.** Versão de esquema local `E7-VAL-1`. Cada ocorrência declara os membros abaixo. Esses membros são representação do valor já previsto, não novos campos de negócio.

| Membro | Regra adotada |
|---|---|
| esquema | E7-VAL-1 |
| tipo | TEXTO, CODIGO, INTEIRO, DECIMAL, BOOLEANO, ANO, COMPETENCIA, DATA, INSTANTE ou REFERENCIA |
| valor | Texto literal para valores exatos/textuais; booleano nativo apenas para BOOLEANO; null quando não houver valor, com qualificação explícita |
| qualificacao | CONHECIDO, NAO_INFORMADO, PENDENTE ou NAO_APLICAVEL, como códigos de representação; não substituem o domínio funcional de PF-08 |
| unidade | Unidade declarada quando necessária; null quando inaplicável |
| dominio | Código/versionamento do vocabulário para CODIGO; null quando inaplicável |
| precisao e fuso | Obrigatórios quanto ao sentido temporal; null quando inaplicáveis ou desconhecidos, distinguindo os casos pela qualificação/contexto |
| referencia | Para REFERENCIA: tipo do alvo, ID e versão aplicável; nos demais casos null |

Zero é valor conhecido, não qualificação de ausência. Texto vazio só é valor quando deliberadamente declarado; não significa automaticamente desconhecido. Decimal, quando necessário para representar um valor histórico, preserva texto exato e unidade; esta representação não aprova operações financeiras ou arredondamento. Tipo desconhecido deve ficar pendente, sem conversão por inferência.

Antes/depois devem ser compatíveis com o atributo afetado. Uma mudança legítima de tipo deve ser explicitada; não forçar ambos a texto genérico para esconder incompatibilidade. Payload que exceda o limite não será truncado. Sintaxe e preservação devem ser demonstradas em E7-04/construção futura; nenhum parser foi implementado.

## 5. PC-02 — Domínios ativos, alvos e identidade

**DECISÃO APROVADA PC-02-A.** Adotar documentalmente a lista técnica restrita do núcleo abaixo, sem ativar entidades de negócio adicionais. As referências a empresa, Gestor e objeto material de origem dependem do cadastro vigente, não de linhas fictícias.

| Tipo técnico candidato | Contêiner de E7-02 | Chave |
|---|---|---|
| REFERENCIA_EXTERNA | tbReferenciaExterna | id_referencia_externa |
| FONTE_EVIDENCIA | tbFonteEvidencia | id_fonte_evidencia |
| VINCULO_EVIDENCIA | tbVinculoEvidencia | id_vinculo_evidencia |
| EVENTO_AUDITORIA | tbEventoAuditoria | id_evento |
| VINCULO_EMPRESARIAL | tbVinculoEmpresarial | Chave própria prevista em PF-06 |
| DIMENSAO_TEMPORAL | tbDimensaoTemporal | Chave própria prevista em PF-07 |
| ESTADO_PREENCHIMENTO | tbEstadoPreenchimento | Chave própria prevista em PF-08 |
| LINHAGEM | tbLinhagem | Chave própria prevista em PF-09 |
| NO_LINHAGEM | tbNoLinhagem | id_no, como projeção do alvo existente |
| VINCULO_REFERENCIA | tbVinculoReferencia | id_vinculo_referencia |
| ALERTA | tbAlerta | id_alerta |

A nomenclatura técnica acima é a convenção local adotada para a lista de tipos; não redefine nomes lógicos. tbObjetoIdentidade resolve a identidade de cada alvo elegível, sem criar uma segunda identidade do fato. tbEventoAlerta é relação pelo par id_evento/id_alerta, sem UUID independente inventado. A projeção de nós não gera nova identidade de negócio.

A presença na lista não autoriza todas as combinações de vínculo. Cada atributo possui alvo esperado: id_evento aponta EVENTO_AUDITORIA; id_fonte_evidencia aponta FONTE_EVIDENCIA; id_referencia_externa aponta REFERENCIA_EXTERNA; id_no aponta NO_LINHAGEM; id_alerta aponta ALERTA. Relações objeto–evidência, evento–objeto e objeto–empresa exigem tipo elegível de objeto material previamente aprovado. Relações entre metadados só serão admitidas quando previstas pela fonte, não por estarem na lista.

**PENDÊNCIA L-01.** Resolver nominalmente contêiner, chave e tipos de objetos materiais de origem, empresa e responsável antes de construir relações dependentes. E7-02 preserva o cadastro mestre em Projetos, mas não fornece autorização para criar um cadastro alternativo. Se o alvo exigir novo módulo, é decisão de ampliação; não ativar tipo genérico irrestrito. A lacuna permite continuar o desenho documental e o planejamento, mas impede declarar configuração executável completa dessas relações.

### 5.1 Vocabulários fechados herdados

| Grupo | Domínio ativo no recorte |
|---|---|
| Vigência, quando versionável | RASCUNHO, VIGENTE, SUBSTITUIDO, ENCERRADO, CANCELADO |
| Referência externa | DOCUMENTO, IDENTIFICADOR_EXTERNO, URL_FONTE, ORIENTACAO_CASO_CONCRETO, OUTRO_DECLARADO |
| Situação da referência | ATIVA, SUBSTITUIDA, INATIVA, NAO_CONFIRMADA |
| Evento | CRIACAO, ALTERACAO, RETIFICACAO, CANCELAMENTO, VINCULO, DESVINCULO, ALERTA_OPERACIONAL |
| Resultado de evento | CONCLUIDO, CONCLUIDO_COM_ALERTA, FALHOU, CANCELADO |
| Procedência da autoridade_evento | TITULAR, SISTEMA, FONTE_DECLARADA; sem conferir autoridade humana a sistema/terceiro |
| Linhagem aplicável | DERIVA_DE, SUBSTITUI, GERADO_POR, CORRIGE; IMPORTADO_DE fica fora da ativação deste recorte |
| Situação do alerta | ABERTO, CIENTE, RESOLVIDO, NÃO APLICÁVEL, ENCERRADO COM JUSTIFICATIVA |
| Severidade | informativa, atenção, crítica |

Demais eixos de classificação, disponibilidade, prática, qualidade e preenchimento permanecem os de E-ESC-01/E2-03A, com especializações de E5-03 e E7-02. Não os fundir com vigência. A compilação literal desses vocabulários por campo e versão será entrada obrigatória do plano de construção; qualquer domínio sem fonte nominal fica inativo até esclarecimento (L-02). Não se escolhe um valor por padrão para preencher lacuna.

### 5.2 CT-01 — Controle de identidade e escrita correlata

Novas identidades internas obedecem UUIDv7; rejeitar localmente formato inválido ou colisão antes de confirmar a ocorrência. O método gerador precisa ser explicitamente selecionado e demonstrado em construção autorizada (L-03); não gerar por número de linha, contagem ou fórmula volátil. IDs reservados não são reciclados em caso de interrupção.

Procedimento documental: conferir a entrada; identificar o objeto e a versão; reservar identidade; formar objeto e evento correlatos; conferir referências; conferir contagens e integridade; confirmar o conjunto. Se interrompido, conservar os registros incompletos identificáveis; retomar pela mesma identidade e reconciliar o que já existe antes de acrescentar linhas. Não prometer transação atômica no Excel.

Sem alvo material validado, uma ocorrência não se torna vínculo válido. Informação de negócio faltante recebe a qualificação cabível; UUID informado e inexistente é falha estrutural local. A validação não pode excluir a operação válida de outro objeto.

## 6. PC-03 — Alertas operacionais e atualização de fontes

**DECISÃO APROVADA PC-03-A.** Gatilhos determinísticos abaixo, verificados na entrada/alteração relevante e antes de liberar uma versão do conjunto. A periodicidade é por evento de trabalho; não é tarefa agendada. Não há prazo de resolução presumido.

| Controle | Condição verificável | Severidade adotada | Resposta |
|---|---|---|---|
| CT-02 | Bytes disponíveis diferem do hash registrado da mesma ocorrência | crítica | Preservar ambas as ocorrências e impedir apenas a declaração de integridade daquela evidência |
| CT-03 | Referência informada não encontra alvo do tipo esperado, ou encontra mais de um | crítica | Não confirmar o vínculo inválido; manter correção local visível |
| CT-04 | Chave de identidade repetida ou chave contextual comprovadamente duplicada | crítica para identidade; atenção para possível duplicidade contextual | Não fundir nem apagar; investigar ocorrência e intenção |
| CT-05 | Início/fim ou abertura/resolução comparáveis e contraditórios | atenção | Registrar incoerência; revisão expressa sem substituir data |
| CT-06 | Tipo antes/depois incompatível com atributo, sem mudança tipada declarada | atenção | Preservar a entrada e solicitar correção ou explicação |
| CT-07 | Resolução sem providência ou sem momento/evidência exigível | atenção | Manter alerta ativo; ciência não resolve |
| CT-08 | Fonte materialmente utilizada teve mudança confirmada de versão/conteúdo | atenção | Preservar ocorrência anterior, avaliar impacto e registrar nova ocorrência antes de substituição |

Erro sem objeto válido ainda existente não gera ALERTA com alvo fictício. Ele permanece ocorrência de conferência do lote; somente quando existir alvo admissível pode receber vínculo na tbAlerta. Isso não autoriza nova tabela de negócio.

Mesma condição ainda ativa no mesmo alvo e regra atualiza sua trilha de observações por eventos, sem criar alertas repetidos por mera releitura. Condição nova após resolução gera ocorrência nova relacionada ao histórico. Resolução: comprovação do tratamento e evento correspondente. NÃO APLICÁVEL e ENCERRADO COM JUSTIFICATIVA exigem justificativa do Gestor; nenhum significa regularidade por inferência.

Não há alerta por ausência de contador, advogado, parecer, validação externa genérica, COO/LDE ou origem contextual opcional. Severidade não cria trava geral. Falta de evidência obrigatória para uma declaração específica impede apenas afirmar que essa declaração foi comprovada.

### 6.1 Fontes informativas

Antes de usar uma fonte numa alteração relevante, identificar versão/corte e verificar se há mudança conhecida. Arquivo capturado conserva bytes, metadados, data e hash; fonte sem arquivo conserva referência e captura verificável. Falha de acesso significa verificação não realizada, nunca confirmação de atualização ou falsidade da informação anterior.

Fonte informativa não altera automaticamente valor, regra ou vigência. Atualização exige nova ocorrência, comparação de impacto e decisão competente quando material. Não há atualização automática de alíquotas ou parâmetros financeiros neste recorte. A necessidade de revisão periódica por calendário fica diferida até haver fonte e frequência de uso concretas (L-04); a alternativa recomendada cobre revisão por uso, não monitoramento contínuo.

## 7. PC-04 — Acesso, evidências, retenção e recuperação

**DECISÃO APROVADA PC-04-A.** Procedimento proporcional ao editor único e ao volume baixo, para futura execução autorizada.

### 7.1 CT-09 — Acesso e autoridade

Eduardo é o responsável pela escrita autoritativa e aceite. Referências a executor técnico não criam novo decisor. Arquivo Operacional contém o núcleo; Financeiro consome referência com origem/versão. Versão publicada será tratada como leitura, com cópia de trabalho separada. Conflito de sincronização deve ser reconciliado antes de nova versão; nunca sobrescrever arbitrariamente a ocorrência concorrente.

Proteção de células reduz edição acidental, mas não comprova autenticação, imutabilidade ou segregação de acesso. Quem lê um arquivo que contém dados das duas empresas pode ter acesso a ambas; filtros não são controle de confidencialidade. Se surgir leitor com acesso restrito a uma empresa, será necessária avaliação específica antes do compartilhamento.

Permissões efetivas, criptografia, conta, destino e mecanismo de proteção dependem do ambiente que será autorizado (L-05). Nenhuma configuração ou compartilhamento foi feito. Não presume que histórico de OneDrive equivale a backup independente.

### 7.2 CT-10 — Evidência e retenção

Captura de arquivo: manter nome original, identificador da ocorrência, origem, momento, responsável, tamanho, algoritmo SHA-256 e valor observado. Hash é dos bytes originais; não normalizar LF/CRLF, codificação ou espaços. Texto equivalente com bytes diferentes permanece ocorrência distinta. Fonte sem bytes não recebe hash inventado.

Retenção adotada documentalmente para o ciclo documental e futura validação: preservar todas as ocorrências de evidência, eventos, manifestos e versões liberadas até ato expresso que estabeleça descarte. Não há descarte automático por idade. Isso não fixa prazo legal nem autoriza conservar dados pessoais sem avaliação aplicável ao uso real. Duração e escopo de retenção operacional definitiva permanecem L-06, com impacto explícito antes de uso real.

Substituição de fonte preserva a predecessora; retirada lógica conserva motivo e vínculo. Arquivos de evidência ficam referenciados, não embutidos por conveniência em células JSON. Destino físico e capacidade serão definidos antes da execução, sem criar pastas operacionais nesta unidade.

### 7.3 CT-11 — Backup e restauração

Pontos adotados documentalmente: cópia recuperável antes de cada sessão de alteração e cópia verificada após cada versão liberada. Meta inicial: poder retornar ao último conjunto liberado e conferido; trabalho posterior pode exigir reconciliação. Não se promete perda máxima em horas ou tempo de recuperação ainda não medido.

O conjunto recuperável deverá conter arquivo autoritativo, referências financeiras aplicáveis, evidências necessárias, configuração e manifesto com versão, IDs, caminhos, tamanhos e hashes. Pelo menos uma cópia deve estar fora do mesmo conjunto de sincronização sujeito à mesma sobrescrita. Destino específico e disponibilidade são L-05; não declarar backup existente sem prova.

Restauração futura: escolher versão; preservar ocorrência atual para análise; restaurar em destino separado; conferir hashes, contagens, vínculos e configuração; registrar lacunas; obter aceite do Gestor antes de promover a cópia restaurada. Nunca restaurar por cima do único original. E7-04 descreverá o cenário de prova. A aprovação desta política não executa restauração nem autoriza dados reais.

## 8. Lacunas locais e impacto

| Código | Lacuna / responsável por decidir | Impacto e marco de tratamento |
|---|---|---|
| L-01 | Alvos materiais, empresa e responsável: contêiner/chave e tipos exatos; Gestor com proposta técnica | Impede construção das relações dependentes; nominalizar antes da autorização construtiva |
| L-02 | Compilação literal dos demais vocabulários por campo; executor documental, Gestor decide divergências | E7-04 deve exigir anexo de configuração conferido; nenhum valor fora de fonte fica ativo |
| L-03 | Gerador UUIDv7 e controles de escrita tecnicamente demonstráveis; Gestor seleciona na frente construtiva | Desenho aceito não autoriza gerador nem garante trilha; escolher e provar antes da carga autorizada |
| L-04 | Fontes sujeitas a revisão por calendário e frequência; Gestor | Sem monitoramento periódico prometido; revisão por uso adotada permanece aplicável |
| L-05 | Destino independente, acesso, recuperação e capacidade efetiva; Gestor | Impede afirmar prontidão operacional e backup ativo; resolver antes da execução dependente |
| L-06 | Retenção operacional definitiva e descarte; Gestor | Sem descarte automático; resolver antes de uso real e qualquer rotina de eliminação |
| L-07 | Mapeamento nominal de metadados temporais e regra de reconstrução de estado por objeto | E7-04 deve exigir correspondência sem duplicação; não construir visão corrente ambígua |

Esses diferimentos não autorizam deixar controles incompletos em produção. O humano adotou o tratamento desses diferimentos ao escolher PC-01-A a PC-04-A. As lacunas permanecem abertas, com os marcos e impactos descritos; a escolha não as resolve. Elas serão carregadas em E7-04/E7-05 e não impedem o aceite de uma especificação exclusivamente documental com esses limites explícitos. Não promovem os 33 detalhes TRT-04 nem encerram o mapeamento global.

## 9. Matriz de encaminhamento a E7-04

| Origem | Parâmetro/controle | Evidência futura a planejar |
|---|---|---|
| E7-02 §5; E5-03 §6.2 | PC-01 | Limite/excedente, Unicode, preservação literal, zero/ausência, precisão e fuso |
| E7-02 §8; E5-03 QD-01/03/05 | PC-02 / CT-01 | Colisão, alvo errado, vínculo órfão, interrupção/retomada, nó inexistente |
| RF-03-001 / PF-08 | PC-01 / CT-06 | Valor zero distinto de ausente, pendente e não aplicável; sem preenchimento inferido |
| RF-03-004 / PF-05/06 | CT-01 / CT-09/11 | Correção sem sobrescrita, empresa sem inferência, recuperação e limite do editor único |
| RF-03-050 / PF-02/03/04 | CT-02/08/10 | Mesmos textos com bytes diferentes, fonte inacessível, equivalência não automática |
| REV-FUNC-004 §10; E5-03 §7.9 | PC-03 / CT-07 | Ciência sem encerramento, resolução incompleta, ausência de profissional sem alerta |
| E7-02 §10; E5-03 §11 | PC-04 / CT-11 | Manifesto divergente, restauração separada, conjunto incompleto e rejeição de promoção |

Os cenários são exigências para o plano; não são resultados de testes. Cobertura permanece restrita ao recorte transversal, sem satisfação integral automática dos três RF e 14 CAs de referência.

## 10. Decisões materiais adotadas pelo humano

| Decisão | A — adotada | B — não selecionada | Razão e impacto |
|---|---|---|---|
| PC-01 | Perfil completo da seção 4: limites 255/4.000/16.000, comparação exata conservadora, precisão preservada e E7-VAL-1 | Diferir limites e esquema concreto até amostra documental específica, mantendo texto canônico/JSON já aceitos | A fornece parâmetros revisáveis sem inventar dados; B posterga configuração e casos de limite, sem reabrir DF-03-A |
| PC-02 | Lista técnica restrita e controles da seção 5, aceitando L-01/L-02/L-03/L-07 com os marcos explícitos | Exigir resolução documental dos alvos e vocabulários antes de aceitar E7-03 | A permite avançar no planejamento com limites; B exige complemento de fontes/escopo antes do aceite |
| PC-03 | Gatilhos/severidades e verificação por entrada, alteração, uso da fonte e liberação de versão | Manter as severidades e a frequência como pendências para decisão posterior | A dá comportamento verificável; B impede considerar parametrizado o painel, mas não altera operação não bloqueante |
| PC-04 | Preservação sem descarte automático até ato próprio, cópias antes da sessão/após versão e destino independente a resolver | Diferir o perfil de preservação/backup até escolher ambiente e destino | A fixa procedimento documental e limites; B amplia lacuna de prontidão, sem desfazer DF-04-A |

**DECISÃO APROVADA:** a manifestação humana “A/A/A/A”, em resposta à apresentação de E7-03 v0.1, adotou PC-01-A, PC-02-A, PC-03-A e PC-04-A. Trata-se de ato próprio para E7-03, distinto da escolha anterior de E7-02. As alternativas B permanecem apenas como histórico comparativo e não são caminhos ativos. A versão consolidada preserva valores, regras e limites das alternativas escolhidas, sem acrescentar parâmetros materiais.

## 11. Conferência e estado resultante

Conferência documental: os quatro grupos de decisões físicas aceitas em E7-02 foram preservados; os parâmetros de E7-03 foram consolidados conforme a escolha humana, preservando as lacunas com impacto; as situações de alerta foram confrontadas com REV-FUNC-004 e o limite posterior de E5-03; não se criaram regras financeiras nem exigências profissionais bloqueantes.

Permanecem: matriz oficial 149/33; 33 detalhes TRT-04; C-F05-05 parcialmente atendida; ALT-04 e C-F05-09 preservadas; ESC-F05-06 concluído apenas documentalmente com ressalvas; Fase 05 aberta. A linha mestre não foi alterada. A numeração PC/CT/L é local, sem novos DEC/PEN oficiais.

Estado: UT-F05-07-01 e UT-F05-07-02 CONCLUÍDAS DOCUMENTALMENTE; UT-F05-07-03 INICIADA; E7-03 v0.2 EM MINUTA CONSOLIDADA, AGUARDANDO ACEITE; PC-01-A A PC-04-A ADOTADAS DOCUMENTALMENTE; L-01 A L-07 ABERTAS COM DIFERIMENTO EXPLÍCITO; UT-F05-07-04/05 AUTORIZADAS, NÃO INICIADAS POR DEPENDÊNCIA. Nenhum teste, controle real, migração ou implantação foi executado.

Próximo passo: obter aceite de E7-03 v0.2 e autorização de publicação; publicar e conferir os bytes aceitos; concluir UT-03 conforme autorização e resultado; prosseguir ao plano documental E7-04. Aceitar diferimentos não concede autorização de construção.

### 11.1 Controle desta revisão

Antecedente preservado: E7-03_ESPECIFICACAO-DE-PARAMETROS-E-CONTROLES-DO-PRIMEIRO-RECORTE_v0.1_2026-09-20_MINUTA.md, 28.893 bytes, SHA-256 e2a5d630caf27ac8b9641759e82eda8e8d1943187c63e3a0536fb1e96b0c62ca.

A v0.2 incorpora o ato humano A/A/A/A. Foram atualizados o enquadramento das escolhas, os títulos e o estado documental. Permanecem os limites numéricos, o esquema E7-VAL-1, os controles CT-01 a CT-11, as lacunas L-01 a L-07 e os destinos de rastreabilidade. Nenhuma fonte, registro mestre ou documento publicado foi alterado.
