# E9-02 — ESPECIFICAÇÃO DO AMBIENTE ISOLADO, RESPONSABILIDADES E DADOS SINTÉTICOS

## MINUTA v0.1 — PARA REVISÃO — EXCLUSIVAMENTE DOCUMENTAL — SEM PREPARAÇÃO DE AMBIENTE OU AUTORIZAÇÃO TÉCNICA

| Campo | Valor |
|---|---|
| Projeto | Dev_Ecossistema_Integrado_Gestao_Empresarial |
| Fase | Fase 05 |
| Escopo | ESC-F05-09 — Preparação isolada do primeiro recorte e manifesto físico controlado |
| Unidade | UT-F05-09-02 — Ambiente, executor, acessos e dados sintéticos |
| Produto | E9-02 — Especificação do ambiente isolado, responsabilidades e dados sintéticos |
| Data documental | 21/09/2026 |
| Responsável humano | Eduardo Andrade Ramos |
| Estado | UT-F05-09-01 concluída documentalmente; Portão A confirmado; UT-F05-09-02 iniciada exclusivamente no alcance documental; E9-02 em minuta |
| Linha mestre vigente | REG-CONSOLIDACAO-CHATS v0.24 / REG-DECISOES v0.28 / REG-PENDENCIAS v0.23 |
| Estado de EC-02 | Não criado, não ativado e não autorizado |
| Executor técnico | `NÃO DESIGNADO` |
| Ambiente físico | Não criado, não preparado e não acessado |
| Dados sintéticos | Somente especificados; nenhum conjunto gerado, aprovado para uso ou utilizado |

## 1. Autoridade, finalidade e limite desta produção

O Gestor aceitou integralmente o resultado da publicação sincronizada de `REG-CRIACAO-RESPONSABILIDADE-E-ATIVACAO-ESC-F05-09 v0.1` e de `E9-01 v0.1`, realizada no commit `f92dfc549fc0f1cb07c533e37e351e0dfa8d9bd0`, tendo como antecedente direto o commit `182f47f1437e224a2817b3ff30c298e5db65ab02`. O aceite confirmou que os dois arquivos correspondem integralmente às minutas aceitas, que o commit contém somente as duas inclusões autorizadas e que nenhuma versão anterior foi alterada, substituída ou excluída.

Em ato posterior, o Gestor autorizou prosseguir com a sequência documental proposta: concluir `UT-F05-09-01` exclusivamente no alcance documental, confirmar o Portão A e iniciar `UT-F05-09-02` apenas para preparar esta minuta.

Esta produção possui três finalidades exclusivas:

1. especificar um ambiente isolado candidato, sem criá-lo ou prepará-lo;
2. delimitar responsabilidades, acessos, operações, segurança, recuperação e evidências, sem designar executor técnico nem conceder acesso;
3. especificar o conjunto e o método de dados sintéticos, sem gerar, copiar, carregar ou utilizar qualquer dado.

Esta minuta não constitui cartão de autorização construtiva, manifesto físico inicial, ordem de serviço, roteiro executável ou comprovação de prontidão técnica. Seu aceite ou sua eventual publicação não cria ou ativa `EC-02`, não satisfaz o Portão B e não autoriza `UT-F05-09-04`.

## 2. Estado de entrada e atendimento do Portão A

### 2.1 Identidades publicadas que sustentam o avanço documental

| Documento publicado em `04_Aprovadas/` | Bytes | SHA-256 | Git blob |
|---|---:|---|---|
| REG-CRIACAO-RESPONSABILIDADE-E-ATIVACAO-ESC-F05-09 v0.1 | 8.945 | `c33b2d8d731e9fe4f9dd9d4833fea5bf2fd92ef327aeb3e9a0f098d10413e8d7` | `8513a487ef4e6e62045460c5f058dfec2dcd8b7c` |
| E9-01 v0.1 | 49.866 | `f5751119d37f9e26f18c396bbe7df7b65eb31f4db0f0fb7f558a0d3b5ee39875` | `02a86450a63aca2292cad561d1c2062ae9207ed8` |

### 2.2 Conferência do Portão A

| Condição obrigatória | Evidência documental | Estado |
|---|---|---|
| E9-01 aceito, publicado e conferido | aceite humano do resultado do commit `f92dfc549fc0f1cb07c533e37e351e0dfa8d9bd0` | ATENDIDA |
| Universo elegível nominalmente fechado | 175 linhas classificadas sem duplicidade, interseção ou ausência de classificação | ATENDIDA |
| Itens diferidos preservados | 111 linhas `DIFERIDA_EC02`, sem promoção por inferência | ATENDIDA |
| Ausência de divergência física não tratada nas fontes obrigatórias | conferência integral dos bytes publicados e ausência de conflito impeditivo declarado no aceite | ATENDIDA NO ALCANCE DOCUMENTAL |
| Ausência de nova RN, RF, CA, revisão arquitetural ou ampliação do Recorte A | E9-01 apenas transporta e classifica o universo vigente | ATENDIDA |

**RESULTADO DO PORTÃO A.** O Portão A está confirmado exclusivamente para o início documental de `UT-F05-09-02`. A confirmação não constitui prova física, autorização construtiva, criação de ambiente, autorização de EC-02 ou atendimento do Portão B.

## 3. Universo e limites transportados de E9-01

| Dimensão | Estado preservado |
|---|---|
| Universo total | 175 linhas |
| Detalhes oficiais | 123 |
| Complementos controlados | 52 |
| Elegíveis somente no sentido documental | 64 linhas `ELEGIVEL_DOCUMENTAL_EC02` |
| Diferidas | 111 linhas `DIFERIDA_EC02` |
| Duplicidades | 0 |
| Interseções entre elegíveis e diferidas | 0 |
| Linhas sem classificação | 0 |
| Cenários executados | 0 de 30 |

As 64 linhas elegíveis podem ser referenciadas por esta especificação apenas para delimitar ambiente, responsabilidades, operações futuras e evidências esperadas. Nenhuma delas pode ser instanciada, copiada, transformada, carregada, escrita ou testada sob a autorização corrente.

As 111 linhas diferidas permanecem integralmente fora de qualquer preparação técnica futura enquanto persistir a condição incidente. Nenhum campo, relação, domínio, identidade, regra temporal ou mecanismo poderá ser completado por inferência.

## 4. Classificação das definições deste produto

| Item | Classificação | Efeito |
|---|---|---|
| Ambiente local isolado descrito neste produto | PROPOSTA | candidato documental para revisão; não existe como ambiente aprovado ou preparado |
| Eduardo Andrade Ramos como responsável humano | DECISÃO APROVADA | mantém a responsabilidade humana já formalmente atribuída ao escopo |
| Executor técnico | PENDÊNCIA | permanece `NÃO DESIGNADO`; impede Portão B e qualquer ação técnica |
| Caminho físico exato | PENDÊNCIA | deverá ser definido e conferido antes de E9-03; nenhum diretório é criado por esta minuta |
| Recurso de cópia independente | PENDÊNCIA | deverá ser nominalmente identificado, ter capacidade e acesso conferidos e permanecer separado do destino primário |
| Dados sintéticos | PROPOSTA | método, limites e proibições definidos; geração e uso permanecem não autorizados |
| Credenciais e segredos | FORA DE ESCOPO DOCUMENTAL | não serão inseridos em E9-02 ou E9-03; somente referências controladas poderão ser registradas |
| Preparação física, estruturas, identidade e escrita | FORA DE ESCOPO | dependem de Portão B e autorização construtiva específica; estruturas e identidade permanecem reservadas a EC-03 |

## 5. Ambiente isolado candidato

### 5.1 Identificação lógica

| Campo | Especificação proposta |
|---|---|
| Identificador lógico | `AMB-EC02-CAND-A` |
| Natureza | área local temporária e dedicada, em equipamento Windows 11 controlado pelo responsável humano |
| Finalidade exclusiva | eventual preparação técnica mínima de EC-02, limitada a cópias controladas, diretórios vazios, configurações autorizadas e conferências previstas no futuro E9-03 |
| Autoridade | nenhuma até autorização construtiva humana específica |
| Estado atual | inexistente ou não conferido; não criar, procurar, reservar ou preparar sob esta autorização |
| Vigência proposta | temporária, do início técnico expressamente autorizado até decisão humana de preservação, retorno ou encerramento |
| Dados permitidos | somente conjunto sintético previamente aprovado e manifestado; zero dado real |
| Relação com EC-03 | nenhuma estrutura, tabela, relacionamento, chave, identidade persistente ou escrita funcional poderá ser criada |

### 5.2 Topologia candidata

A topologia proposta é local, simples e proporcional ao baixo volume e ao uso por uma pessoa. Ela deverá manter três zonas logicamente distintas, sem que esta minuta crie qualquer uma delas:

| Zona | Função | Estado e limite |
|---|---|---|
| `Z0-FONTES-SOMENTE-LEITURA` | receber somente cópias manifestadas de artefatos documentais aprovados | não criada; nenhum acesso às fontes originais é autorizado; nenhuma planilha legada ou base real poderá ingressar |
| `Z1-TRABALHO-ISOLADO` | eventual área transitória para operações técnicas listadas em E9-03 | não criada; não poderá estar sob sincronização automática; nenhuma operação está autorizada |
| `Z2-EVIDENCIAS` | eventual armazenamento de logs, inventários, hashes e relatórios da preparação | não criada; conteúdo sensível e credenciais são proibidos; destino definitivo depende de E9-03 |

Uma pasta com nome distinto não comprova isolamento. Antes de qualquer autorização técnica, E9-03 deverá identificar o equipamento, a conta operacional, o volume, o caminho absoluto, a situação de sincronização, as permissões e os recursos externos que permanecem fora da fronteira.

### 5.3 Separação obrigatória

O ambiente candidato deverá, antes do Portão B, demonstrar cumulativamente:

1. caminho físico fora de qualquer pasta sincronizada pelo OneDrive ou por serviço equivalente;
2. ausência de vínculo com arquivos oficiais, pastas de trabalho corrente, bases produtivas ou recursos de homologação;
3. conta operacional sem privilégios administrativos permanentes, salvo ato específico e operação manifestada que demonstre necessidade;
4. sincronização automática, indexação remota e compartilhamento desabilitados para a área de trabalho isolada;
5. ausência de conectores, consultas, links externos, macros, scripts, tarefas agendadas ou credenciais herdadas das fontes;
6. proibição de rede por padrão durante a manipulação de dados sintéticos, admitindo exceção somente se nominalmente autorizada e registrada;
7. possibilidade de inventariar integralmente conteúdo, tamanho, hashes, permissões e operações;
8. separação entre destino primário e cópia independente.

### 5.4 Localização física

O caminho físico exato permanece `NÃO DEFINIDO`. Para futura deliberação em E9-03, propõe-se o padrão lógico:

`<VOLUME_LOCAL_NAO_SINCRONIZADO>:\EIGE_ISOLADO\ESC-F05-09\EC-02\`

O padrão é ilustrativo e não autoriza sua criação. O volume, a unidade, o caminho absoluto, o proprietário e a prova de que o local está fora da sincronização deverão ser registrados sem inferência no manifesto físico inicial.

## 6. Capacidade, duração e limites quantitativos

| Controle | Valor proposto | Condição antes de ação técnica |
|---|---:|---|
| Capacidade mínima livre do destino primário | maior entre 5 GB e 5 vezes o total de bytes dos objetos manifestados | conferência física e evidência obrigatórias em E9-03/E9-04 |
| Capacidade mínima livre da cópia independente | igual ou superior à capacidade ocupada pelo pacote autorizado e por suas evidências | recurso independente nominalmente identificado |
| Quantidade máxima de arquivos de entrada | somente os objetos fechados no manifesto E9-03 | nenhum arquivo adicional por conveniência |
| Registros sintéticos por contêiner autorizado | máximo de 5 | geração depende de autorização posterior |
| Registros sintéticos totais | máximo de 65 | teto documental; não constitui autorização de geração |
| Vigência inicial do ambiente | até 30 dias corridos após eventual autorização técnica | prorrogação exige ato humano próprio |
| Retenção durante EC-02 | preservação integral, sem descarte automático | descarte permanece proibido até decisão posterior |

Os limites quantitativos são propostas conservadoras para revisão. Caso o manifesto E9-03 demonstre necessidade diferente, a alteração deverá ser expressa, justificada e aceita antes do Portão B; não poderá ser feita durante a execução por conveniência técnica.

## 7. Papéis e responsabilidades

| Papel | Identidade | Responsabilidades | Restrições |
|---|---|---|---|
| Gestor e autoridade final | Eduardo Andrade Ramos | aceitar ou rejeitar produtos; designar executor; aprovar ambiente, acessos, dados sintéticos, manifesto, Portão B e eventual autorização construtiva | o aceite documental não substitui autorização técnica específica |
| Responsável humano pelo escopo | Eduardo Andrade Ramos | manter limites, decidir paradas, preservar ressalvas e confirmar evidências submetidas | não se presume executor técnico |
| Proprietário do equipamento candidato | `NÃO CONFIRMADO` | autorizar uso do equipamento e assegurar separação de recursos | identidade e anuência obrigatórias antes do Portão B |
| Responsável por conceder acesso | `NÃO DESIGNADO` | criar, revisar e revogar acesso conforme lista fechada | não poderá conceder privilégio além do manifestado |
| Executor técnico | `NÃO DESIGNADO` | executar somente operações autorizadas, registrar evidências e interromper diante de critério de parada | não poderá decidir ampliação de escopo, substituir fonte ou aprovar o próprio trabalho |
| Conferente técnico | `NÃO DESIGNADO` | confrontar autorização, manifesto, inventário e evidências | preferencialmente distinto do executor; eventual acumulação exige aceite expresso e controle compensatório |
| Custodiante da cópia independente | `NÃO DESIGNADO` | guardar a cópia, controlar acesso e apoiar futura restauração | não poderá alterar conteúdo ou declarar restauração sem prova |

Nenhuma identidade pendente será completada por suposição. Se uma mesma pessoa vier a acumular papéis, E9-03 deverá registrar expressamente a acumulação, o risco e o controle compensatório.

## 8. Modelo de acesso

### 8.1 Princípios

1. acesso mínimo necessário e temporário;
2. negação por padrão;
3. identidade nominal, sem conta compartilhada;
4. ausência de credencial no documento;
5. prazo e revogação definidos antes da concessão;
6. proibição de acesso a fontes reais, produção, homologação e pastas oficiais;
7. trilha de criação, uso administrativo excepcional e revogação;
8. separação entre executar, conferir e aceitar sempre que materialmente possível.

### 8.2 Matriz candidata de permissões

| Papel | Z0 | Z1 | Z2 | Administração do equipamento |
|---|---|---|---|---|
| Gestor | leitura de evidências quando necessário | sem operação técnica presumida | leitura e aceite | nenhuma permissão técnica presumida |
| Executor técnico | leitura dos objetos manifestados | criar/copiar/configurar somente conforme E9-03 | criar evidências sem alterar registros encerrados | proibida por padrão |
| Conferente técnico | leitura | leitura para conferência; escrita proibida salvo anotação segregada | leitura e emissão de relatório | proibida |
| Custodiante da cópia | sem acesso ordinário | sem acesso ordinário | leitura necessária à cópia e restauração autorizada | proibida |

Esta matriz é documental e não concede qualquer permissão. Conta, caminho, duração e privilégio deverão constar nominalmente de E9-03.

## 9. Operações permitidas e proibidas

### 9.1 Lista candidata de operações que poderão ser submetidas à autorização futura

Somente após Portão B e autorização construtiva específica poderão ser consideradas:

1. criar a árvore vazia de diretórios previamente manifestada;
2. copiar bytes exatos de objetos documentais aprovados e manifestados para `Z0`, sem modificar a origem;
3. conferir nome, versão, tamanho, SHA-256, origem e destino da cópia;
4. criar arquivos vazios ou configurações não funcionais expressamente listados no manifesto;
5. gerar conjunto sintético pelo método aprovado, dentro dos limites quantitativos;
6. registrar logs, inventários, hashes, diferenças e evidências em `Z2`;
7. produzir cópia independente dos objetos e evidências autorizados;
8. executar verificação de restauração somente se houver autorização própria no cartão construtivo.

### 9.2 Operações proibidas

Permanecem proibidos:

- acessar, copiar, abrir, consultar, exportar, transformar, mascarar ou migrar dado real;
- acessar planilha oficial, pasta produtiva, recurso de homologação ou fonte não manifestada;
- criar tabela, relacionamento, chave, identidade persistente, UUID, evento, alerta ou projeção funcional;
- executar fórmula, regra de negócio, consulta, integração, macro, script funcional ou automação;
- instalar software, serviço, agente, conector ou dependência sem autorização própria;
- habilitar sincronização, compartilhamento, publicação, envio externo ou acesso remoto;
- usar credencial pessoal em arquivo, script, planilha, log ou evidência;
- executar qualquer dos 30 cenários de E7-04;
- modificar fonte, antecedente, registro mestre ou produto aprovado;
- ampliar o conjunto de 64 linhas ou promover qualquer das 111 diferidas;
- realizar implementação, teste funcional, migração, homologação, implantação ou promoção operacional.

Operação ausente da lista fechada de E9-03 será proibida, ainda que pareça necessária ou de baixo risco.

## 10. Especificação dos dados sintéticos

### 10.1 Princípio e estado

O conjunto sintético será um artefato artificial, inequivocamente marcado e incapaz de reproduzir pessoa, empresa, projeto, contrato, documento, valor, contato, identificador ou combinação reconhecível existente nas fontes reais. Nesta minuta, ele é somente especificado. Nenhum dado é gerado ou aprovado para uso.

### 10.2 Regras de geração propostas

| Dimensão | Regra proposta |
|---|---|
| Origem | geração do zero; nenhuma leitura, amostragem, transformação ou mascaramento de dado real |
| Identificação | todo valor textual livre deverá iniciar com `SINT_EC02_` quando o domínio permitir |
| Pessoas e empresas | usar somente entidades fictícias padronizadas, como `SINT_EC02_PESSOA_001` e `SINT_EC02_EMPRESA_001`; nunca nomes plausíveis completos |
| Documentos e contatos | não gerar CPF, CNPJ, e-mail, telefone, conta bancária, endereço ou identificador com aparência válida, salvo futura necessidade aprovada e método próprio seguro |
| Valores | sequências artificiais simples e declaradas; não derivar valores de contratos, notas, despesas ou receitas reais |
| Datas | usar janela artificial explicitamente marcada e não vinculada à cronologia real; a janela exata deverá constar de E9-03 |
| Identidades técnicas | nenhuma geração de UUID ou chave persistente em EC-02; referências provisórias, se aprovadas, usarão rótulos textuais sintéticos não funcionais |
| Domínios | somente valores cuja fonte e versão estejam identificadas; domínio condicionado por L-02 permanece inativo |
| Autoridade temporal | nenhuma reconstrução histórica; campos condicionados por L-07 permanecem ausentes ou diferidos |
| Relações | nenhuma relação cujo alvo, contêiner ou chave esteja condicionado por L-01 ou L-03 |
| Quantidade | máximo de 5 registros por contêiner e 65 no total |
| Marcação | cabeçalho, nome de arquivo e metadados deverão declarar `DADOS_EXCLUSIVAMENTE_SINTETICOS — SEM ORIGEM REAL` |

### 10.3 Método de comprovação de ausência de dado real

Antes de eventual uso, o método deverá produzir evidências cumulativas de:

1. declaração do gerador de que nenhuma fonte real foi utilizada;
2. registro da regra, semente ou procedimento determinístico, quando aplicável;
3. lista fechada dos arquivos e campos gerados;
4. busca negativa por nomes de empresas, projetos, pessoas e identificadores constantes das fontes reais, executada sem incorporar esses conteúdos ao conjunto sintético;
5. validação de que não existem padrões válidos de CPF, CNPJ, e-mail, telefone, conta bancária ou endereço real;
6. validação de prefixos e marcações sintéticas obrigatórias;
7. contagem por arquivo, contêiner e total;
8. cálculo de tamanho e SHA-256 do conjunto;
9. conferência independente ou controle compensatório aprovado;
10. interrupção diante de correspondência, dúvida ou impossibilidade de comprovação.

A especificação do método não autoriza sua execução. O roteiro exato, a ferramenta, o executor, a entrada, a saída e as evidências deverão ser fechados em E9-03.

## 11. Segurança e proteção de segredos

| Controle | Exigência |
|---|---|
| Credenciais | não incorporar valor de senha, token, chave ou segredo a qualquer produto documental |
| Referências de acesso | registrar somente identificador controlado, titular, finalidade, vigência e responsável pela revogação |
| Privilégios | padrão sem administração; elevação excepcional somente por operação manifestada, tempo limitado e evidência própria |
| Rede | bloqueada ou desnecessária por padrão; exceção exige destino, protocolo, finalidade e duração expressos |
| Sincronização | proibida na área isolada |
| Compartilhamento | proibido até ato específico |
| Proteção local | utilizar controles nativos compatíveis com o equipamento, sem presumir configuração já existente |
| Registro | ação técnica futura deverá possuir data/hora, executor, objeto, operação, resultado, diferença e evidência |
| Incidente | interromper imediatamente, preservar evidências e submeter ao Gestor |

Nenhum controle será declarado existente com base apenas em disponibilidade teórica do sistema operacional.

## 12. Cópia independente e recuperação planejada

### 12.1 Requisitos da cópia independente

O destino da cópia independente permanece `NÃO IDENTIFICADO`. Antes do Portão B, deverá ser definido recurso que:

1. não compartilhe o mesmo volume físico ou a mesma falha provável do destino primário;
2. tenha capacidade conferida;
3. possua custodiante e acesso nominalmente delimitados;
4. não seja pasta sincronizada ou compartilhada sem autorização;
5. preserve bytes, nomes, tamanhos, hashes e estrutura manifestada;
6. mantenha retenção provisória sem descarte automático;
7. permita futura restauração controlada sem tocar fontes oficiais.

### 12.2 Plano de recuperação proposto

O plano deverá prever, sem executá-lo nesta unidade:

1. seleção do pacote autorizado pelo hash do manifesto;
2. restauração para diretório vazio e isolado distinto do destino primário;
3. conferência de contagem, tamanho e SHA-256;
4. registro de ausência, diferença ou corrupção;
5. proibição de sobrescrita silenciosa;
6. aceite humano do resultado.

Backup ou restauração não poderão ser declarados comprovados antes de evidência física produzida sob autorização específica.

## 13. Evidências exigidas para E9-03 e eventual UT-F05-09-04

| Grupo | Evidência mínima futura |
|---|---|
| Equipamento | identificador controlado, sistema, proprietário e condição de uso autorizada |
| Fronteira | volume, caminho absoluto, situação de sincronização e recursos expressamente excluídos |
| Capacidade | espaço total e livre do destino primário e da cópia independente |
| Acesso | identidade, papel, permissões, início, término e responsável pela revogação |
| Objetos | nome, versão, origem, destino, tamanho e SHA-256 |
| Operações | lista fechada com autoridade, executor, duração e resultado esperado |
| Dados sintéticos | método, limites, marcação, arquivo, contagem, tamanho, hash e prova de ausência de dado real |
| Segurança | controles efetivamente verificados, exceções e riscos residuais |
| Recuperação | destino independente, custodiante, retenção e roteiro aprovado |
| Execução | data/hora, executor, ação, resultado, diferença, parada e conferente |

Capturas de tela poderão complementar, mas não substituirão identidade física, tamanho, hash, permissão ou conteúdo quando esses forem requisitos do controle.

## 14. Tratamento de L-01 a L-07

| Condição | Aplicação nesta especificação | Limite preservado |
|---|---|---|
| L-01 — alvos materiais | nenhuma relação é autorizada sem alvo, contêiner e chave sustentados | nenhum alvo fictício ou estrutura relacional criada |
| L-02 — vocabulários | somente domínios com fonte e versão poderão ser considerados em dados sintéticos | nenhum vocabulário inventado por conveniência |
| L-03 — UUIDv7 e escrita | nenhum gerador é selecionado ou executado; rótulos provisórios não serão identidade persistente | nenhuma escrita funcional ou UUID gerado |
| L-04 — calendário | nenhuma agenda, rotina ou monitoramento é ativado | frequência sem fonte e autoridade permanece inativa |
| L-05 — destino e recuperação | destino primário, cópia independente, capacidade, acesso e restauração permanecem requisitos bloqueantes | nenhum backup ou recuperação declarados comprovados |
| L-06 — retenção | preservação integral durante EC-02; descarte automático proibido | política definitiva continua futura |
| L-07 — autoridade temporal | nenhum histórico é reconstruído e nenhum campo condicionado é preenchido | autoridade histórica e corrente permanecem conforme decisões vigentes |

## 15. Pendências explícitas e efeito bloqueante

| ID local | Pendência | Efeito |
|---|---|---|
| E9-02-P01 | confirmar o equipamento candidato e seu proprietário | bloqueia definição física do ambiente |
| E9-02-P02 | definir volume e caminho absoluto fora de sincronização | bloqueia E9-03 completo e Portão B |
| E9-02-P03 | designar executor técnico | bloqueia qualquer operação técnica |
| E9-02-P04 | designar responsável por acesso e revogação | bloqueia concessão de acesso |
| E9-02-P05 | designar conferente técnico ou aprovar controle compensatório | bloqueia plano de conferência |
| E9-02-P06 | identificar destino e custodiante da cópia independente | bloqueia recuperação planejada |
| E9-02-P07 | aprovar método, janela temporal e roteiro de geração sintética | bloqueia geração e uso de dados |
| E9-02-P08 | fechar em E9-03 objetos, operações, acessos, duração e evidências | bloqueia autorização construtiva |

Os identificadores `E9-02-P01` a `E9-02-P08` são controles locais desta minuta. Não constituem novos `PEN-*` e não alteram `REG-PENDENCIAS v0.23`.

## 16. Critérios de parada

Interromper o objeto afetado e submetê-lo ao Gestor se ocorrer:

1. tentativa de preencher equipamento, caminho, executor, acesso, custodiante ou evidência por inferência;
2. impossibilidade de demonstrar separação da sincronização, das fontes oficiais ou de ambientes reais;
3. risco de ingresso de dado real ou de identificador reconhecível;
4. necessidade de acessar fonte real para gerar ou validar o conjunto sintético;
5. tentativa de promover qualquer das 111 linhas diferidas;
6. necessidade de nova RN, RF, CA, revisão arquitetural ou ampliação do Recorte A;
7. objeto ou operação ausente da lista fechada de E9-03;
8. ausência de capacidade, cópia independente ou recuperação delimitadas;
9. pedido de criação de estrutura, geração de identidade, escrita ou teste funcional;
10. tentativa de executar qualquer ação técnica antes do Portão B e da autorização construtiva específica;
11. tentativa de tratar aceite ou publicação desta minuta como criação ou autorização de EC-02;
12. divergência entre fonte, versão, tamanho, hash, caminho ou autoridade documental.

A parada deverá registrar objeto, evidência, impacto, trabalho independente preservado e decisão humana necessária.

## 17. Critérios propostos de aceitação de E9-02

E9-02 poderá ser aceito documentalmente se o Gestor considerar que:

1. o ambiente candidato e sua fronteira estão especificados sem declarar existência física;
2. papéis, acessos e segregações estão definidos, mantendo identidades ausentes como pendências explícitas;
3. operações candidatas e proibições formam lista suficientemente fechada para preparar E9-03;
4. o método e os limites dos dados sintéticos estão definidos sem uso de fonte real;
5. segurança, cópia independente, retenção e recuperação estão especificadas sem alegar comprovação;
6. L-01 a L-07, as 111 linhas diferidas e todas as ressalvas anteriores permanecem preservadas;
7. as pendências materiais estão visíveis e bloqueiam corretamente o Portão B;
8. nenhuma ação física ou técnica foi executada.

O aceite documental poderá reconhecer a suficiência desta especificação para preparar E9-03, mas não eliminará as pendências que exigem decisão nominal ou comprovação física.

## 18. Estado resultante proposto

**PROPOSTA DE RESULTADO DE UT-F05-09-02:** considerar E9-02 documentalmente suficiente para definir o modelo candidato de ambiente isolado, responsabilidades, acessos, operações, dados sintéticos, segurança e recuperação, mantendo explícitas e bloqueantes as identidades e evidências ainda ausentes.

Se esta minuta vier a ser aceita, publicada e conferida, a conclusão formal de `UT-F05-09-02` dependerá de ato humano posterior. Somente depois poderão ser avaliados a confirmação do portão interno aplicável e o início exclusivamente documental de `UT-F05-09-03`, para preparar E9-03.

E9-03 deverá converter as propostas aceitas em cartão de autorização construtiva e manifesto inicial fechado, identificando sem ambiguidade equipamento, caminho, executor, conferente, acessos, cópia independente, objetos, operações, dados sintéticos, duração e evidências. Sua produção não realizará a preparação técnica.

## 19. Preservações vinculantes e não autorizações

Permanecem integralmente preservados:

- linha mestre `v0.24/v0.28/v0.23`;
- `ESC-F05-08` concluído exclusivamente no alcance documental;
- `EC-01` fechado documentalmente;
- `EC-02` não criado, não ativado e não autorizado;
- `UT-F05-09-03` autorizada documentalmente, mas não iniciada;
- `UT-F05-09-04` não autorizada e não iniciada;
- `UT-F05-09-05` não iniciada;
- 123 detalhes oficiais e 52 complementos controlados;
- 64/175 linhas elegíveis somente no sentido documental e 111/175 diferidas;
- matriz oficial `149/33`, os mesmos 33 detalhes em `TRT-04` e zero promoção a `TRT-05`;
- 30 cenários não executados;
- condições residuais de L-01 a L-07;
- `C-F05-05` parcialmente atendida, `ALT-04`, `C-F05-09`, limitação `4H.5`, mapeamento lógico-físico global não encerrado e inventário de 67 itens;
- ocorrências físicas distintas de E2-03C e E-ESC-01, sem normalização retrospectiva;
- todas as ressalvas cumulativas de E6, E7, E8 e E9-01;
- ausência de novo `DEC-*` ou `PEN-*`;
- Fase 05 aberta.

Esta minuta e a autorização que permitiu sua preparação:

- não autorizam sua publicação;
- não concluem `UT-F05-09-02`;
- não iniciam `UT-F05-09-03`, `UT-F05-09-04` ou `UT-F05-09-05`;
- não satisfazem o Portão B;
- não designam executor técnico, conferente ou custodiante;
- não criam, ativam ou autorizam `EC-02`;
- não criam, procuram, acessam ou preparam ambiente;
- não concedem, solicitam ou utilizam acesso;
- não criam ou copiam arquivos técnicos;
- não geram ou utilizam dados sintéticos ou reais;
- não criam estruturas, diretórios, bancos, tabelas, registros ou identidades;
- não autorizam geração de UUID, escrita ou persistência;
- não autorizam implementação, testes, migração, homologação, implantação ou promoção operacional;
- não autorizam `EC-03` a `EC-06`;
- não alteram os registros mestres nem criam novo `DEC-*` ou `PEN-*`;
- não encerram `ESC-F05-09` ou a Fase 05.

**ESTADO DE SAÍDA DESTA MINUTA:** `UT-F05-09-01` concluída exclusivamente no alcance documental; Portão A confirmado apenas para avanço documental; `UT-F05-09-02` iniciada exclusivamente no alcance documental; E9-02 preparada para revisão; executor técnico não designado; ambiente não criado ou preparado; dados sintéticos não gerados ou utilizados; Portão B não satisfeito; `EC-02` não criado, não ativado e não autorizado; Fase 05 aberta.
