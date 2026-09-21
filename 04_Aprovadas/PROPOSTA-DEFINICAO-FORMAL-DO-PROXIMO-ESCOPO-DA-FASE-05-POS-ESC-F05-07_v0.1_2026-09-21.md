# PROPOSTA DE DEFINIÇÃO FORMAL DO PRÓXIMO ESCOPO DA FASE 05 PÓS-ESC-F05-07

## MINUTA v0.1 — AGUARDANDO ACEITE — ESCOPO NÃO CRIADO OU ATIVADO

| Campo | Valor |
|---|---|
| Projeto | Dev_Ecossistema_Integrado_Gestao_Empresarial |
| Data documental | 21/09/2026 |
| Natureza | Configuração documental proposta, não autoexecutável |
| Identificador recomendado | ESC-F05-08 — candidato, não atribuído |
| Nome recomendado | FECHAMENTO DOCUMENTAL DO PACOTE EC-01 E CONFIGURAÇÃO NOMINAL DO PRIMEIRO RECORTE |
| Responsável recomendado | Eduardo Andrade Ramos — designação pendente para este escopo |
| Linha mestre vigente | REG-CONSOLIDACAO-CHATS v0.23; REG-DECISOES v0.27; REG-PENDENCIAS v0.22 |
| Estado executivo | Nenhuma unidade criada, ativada ou iniciada; nenhum produto E8 produzido |

## 1. Autoridade, finalidade e efeito desta minuta

O humano aceitou as três minutas pós-ESC-F05-07 e autorizou sua publicação sincronizada. A publicação foi executada e conferida no commit `da2ee6d43b23141e49fcb9a2d6bc6e99b861969f`. Em seguida, o humano autorizou prosseguir. Esta minuta executa o próximo passo documental indicado na linha mestre: propor a formalização do fechamento do pacote `EC-01` de E7-04 e do tratamento nominal das lacunas nos marcos já aceitos.

Esta preparação não cria ou ativa `ESC-F05-08`, não atribui definitivamente esse identificador, não cria unidades de trabalho, não autoriza sua execução, não inicia construção e não modifica registros mestres ou fontes. O identificador é recomendado pela sequência após `ESC-F05-07` e depende de ato humano expresso.

O objeto desta minuta é deixar concreta e revisável a configuração do próximo trabalho. Aceite da definição, publicação, criação, designação de responsabilidade, ativação e execução das unidades continuam atos próprios.

## 2. Estado de entrada e fontes vigentes

`ESC-F05-07` está concluído exclusivamente no alcance documental, com todas as ressalvas vinculantes e o estado da Alternativa A de E7-05 v0.2. Suas cinco unidades estão concluídas e E7-01 a E7-05 foram aceitos e publicados. A Fase 05 permanece aberta, sem autorização de implementação.

| Registro mestre vigente publicado | Bytes | SHA-256 |
|---|---:|---|
| REG-CONSOLIDACAO-CHATS v0.23 | 198070 | e825d493aa391dbce6e62592256481d135dc6be29fb353af3b2ce8995a71c32d |
| REG-DECISOES v0.27 | 256539 | 5e70128119087ef6ddd741a8a62b2f397e66521e496fcc173a65ac455e04fb3c |
| REG-PENDENCIAS v0.22 | 191206 | 87a2da5bf480d11abccac32f0a2ad7a283c2c500c79aa373f4b1a0cab2c915b4 |

Os três objetos foram publicados sincronizadamente em `08_Consolidados/` e conferidos integralmente contra os bytes aceitos. As marcas internas de preparação são fotografias históricas qualificadas pelos atos posteriores de aceite e publicação.

Fontes primárias do escopo candidato:

1. E7-01 v0.3 — plano de entradas e especificação do primeiro recorte;
2. E7-02 v0.2 — mapeamento físico proposto;
3. E7-03 v0.2 — parâmetros e controles;
4. E7-04 v0.1 — plano de construção, testes e evidências;
5. E7-05 v0.2 — conferência e estado resultante;
6. linha mestre v0.23/v0.27/v0.22;
7. fontes funcionais e arquiteturais nominalmente citadas nos produtos E7, somente nas ocorrências vigentes já qualificadas.

Nenhum anexo antigo ou cópia fisicamente distinta substitui a ocorrência vigente. Divergência física em fonte obrigatória interrompe o objeto afetado até decisão competente.

## 3. Objetivo formal recomendado

Fechar documentalmente o pacote `EC-01` previsto em E7-04, por meio de uma configuração nominal completa e rastreável do primeiro recorte, cobrindo os 123 detalhes de campo e seus complementos, distinguindo realização direta, associação e projeção derivada, e submetendo as decisões necessárias sobre `L-01` a `L-07` ao Gestor.

O resultado esperado é um pacote de entradas e correspondências que permita ao humano decidir posteriormente se existe base suficiente para autorizar, limitar ou rejeitar `EC-02 — Preparação isolada`. O resultado não constrói planilhas, tabelas, fórmulas, consultas, integrações, mecanismos de identidade, backups ou ambiente de teste.

## 4. Alcance incluído

O escopo candidato inclui exclusivamente:

1. conferir a identidade e a vigência das fontes usadas pelo pacote `EC-01`;
2. consolidar o modelo obrigatório do anexo de configuração;
3. inventariar os 123 detalhes de campo transportados e seus complementos posteriores;
4. classificar cada realização como direta, associação ou projeção derivada;
5. registrar, por item aplicável, origem lógica, nome físico, arquivo, aba, tabela, chave, tipo, limite, domínio, transformação, alvo, aplicabilidade e condição de pendência;
6. formular e submeter ao humano as decisões documentais necessárias sobre `L-01` a `L-07`;
7. identificar quais itens permanecem inativos, diferidos ou bloqueados no alcance dependente;
8. conferir rastreabilidade com Recorte A, `DF-01-A` a `DF-04-A`, `PC-01-A` a `PC-04-A` e `CT-01` a `CT-11`;
9. preparar manifesto do pacote, relatório de coerência e proposta de estado resultante;
10. apresentar recomendação não autoexecutável sobre eventual avanço a `EC-02`.

## 5. Exclusões vinculantes

Permanecem fora do escopo:

- criação ou alteração dos arquivos `EIGE_ARQ-OP_v0.1.xlsx` e `EIGE_ARQ-FIN_v0.1.xlsx`;
- construção de tabelas, colunas, fórmulas, Power Query, código, integrações ou infraestrutura;
- geração ou demonstração técnica de UUIDv7;
- uso, cópia, migração ou carga de dados reais;
- execução dos 30 cenários de E7-04;
- teste de backup, restauração, segurança, desempenho ou operação;
- homologação, implantação, promoção operacional ou uso produtivo;
- alteração de RN, RF, CA, arquitetura, fonte, registro mestre, `PEN-*` ou `DEC-*`;
- promoção de `TRT-04` a `TRT-05`, alteração da matriz `149/33`, encerramento de `C-F05-05`, `ALT-04`, `C-F05-09`, mapeamento global ou Fase 05;
- reavaliação dos portões já avaliados ou atribuição automática de atendimento aos portões remanescentes.

## 6. Unidades e produtos candidatos

| Ordem | Unidade candidata | Produto candidato | Saída necessária |
|---:|---|---|---|
| 1 | UT-F05-08-01 — Manifesto de entradas e modelo de configuração | E8-01 — Plano e manifesto controlado do pacote EC-01 | Fontes por versão, bytes e hash; modelo de linha; universo dos 123 detalhes e complementos; critérios de parada e de completude |
| 2 | UT-F05-08-02 — Correspondência nominal dos detalhes | E8-02 — Matriz nominal de realização do primeiro recorte | Uma linha por detalhe realizado ou tratado; classificação direta/associação/projeção; origem, destino, tipo, limite, domínio, transformação, aplicabilidade e pendência |
| 3 | UT-F05-08-03 — Decisões de configuração e lacunas | E8-03 — Catálogo de decisões e tratamento de L-01 a L-07 | Alternativas com recomendação e impacto; decisões humanas incorporadas; itens inativos ou diferidos explicitamente |
| 4 | UT-F05-08-04 — Conferência cruzada do pacote | E8-04 — Relatório de coerência, rastreabilidade e prontidão documental de EC-01 | Cobertura dos 123 detalhes e complementos; consistência com E7; lacunas residuais; ausência de dependência ocultada; sem executar testes |
| 5 | UT-F05-08-05 — Estado resultante | E8-05 — Relatório de conferência e proposta de continuidade | Proposta de conclusão ou interrupção de ESC-F05-08; condições para eventual EC-02; ressalvas, impedimentos e próximos atos humanos |

Todos os identificadores e produtos desta tabela são candidatos. Nenhuma unidade está criada ou iniciada e nenhum produto foi produzido por esta definição.

Cada unidade depende da conclusão da antecedente, do aceite e da publicação de seu produto e de autorização específica de execução. Ajuste material em produto aceito exige versão sucessora e análise de impacto nos dependentes.

## 7. Conteúdo mínimo do anexo de configuração

A matriz de E8-02 deverá conter, no mínimo:

| Grupo | Conteúdo mínimo |
|---|---|
| Identidade lógica | ID do detalhe, objeto de origem, RF/CA incidente e referência a E5/E7 |
| Realização | direta, associação ou projeção derivada, com justificativa |
| Local físico proposto | arquivo, aba, tabela e nome físico do campo ou relação |
| Chave e alvo | chave, tipo de identidade, contêiner do alvo e validação do alvo real |
| Representação | tipo, limite, precisão, escala, formato canônico e regra para excedente |
| Domínio | vocabulário literal, fonte, versão, valores permitidos e aplicabilidade |
| Derivação | origem autoritativa, transformação e condição de atualização |
| Temporalidade | autoridade temporal, precisão, fuso e regra de reconstrução corrente/histórica |
| Controle | CT aplicável, evidência requerida e cenário planejado relacionado |
| Estado | decidido, aplicável, inativo, diferido ou interrompido, com motivo e marco |

Uma contagem preenchida não basta. A cobertura deve ser nominal e rastreável. Campo sem fonte obrigatória não recebe domínio inventado; relação sem alvo material decidido não recebe contêiner fictício; projeção não se torna segunda fonte autoritativa.

## 8. Tratamento das sete lacunas

| Lacuna | Tratamento documental no escopo candidato | Limite preservado |
|---|---|---|
| L-01 — Alvos materiais, empresa e responsável | Propor e decidir tipos, contêineres, chaves e fonte autorizadora por relação dependente | Nenhum alvo será criado fisicamente |
| L-02 — Vocabulários literais por campo | Compilar fonte, versão, valores e aplicabilidade; indicar domínio inativo quando não houver fonte | Nenhum vocabulário será inferido de conveniência técnica |
| L-03 — Gerador UUIDv7 e escrita | Comparar alternativas admissíveis e registrar escolha ou diferimento, método futuro de prova e impacto | Seleção documental não demonstra geração ou escrita |
| L-04 — Revisão por calendário | Identificar fontes sujeitas a calendário, alternativas de frequência e autoridade para decidir | Não prometer monitoramento ou rotina ativa |
| L-05 — Destino, acesso, capacidade e recuperação | Especificar requisitos e opções de destino isolado, acesso, cópia independente, capacidade e recuperação | Nenhum backup ou restauração será declarado ativo |
| L-06 — Retenção e descarte | Propor classes, marcos, exceções e autoridade; manter preservação enquanto não houver decisão | Nenhum descarte será executado |
| L-07 — Autoridade temporal e reconstrução | Definir correspondência nominal por objeto/atributo e regra de corrente/histórico | Impedir duplicidade autoritativa e reconstrução ambígua |

Lacuna sem decisão suficiente permanece aberta com impacto nominal. Esta configuração poderá concluir documentalmente com diferimentos aceitos somente quando os itens dependentes estiverem claramente inativos ou impedidos de avançar. Não se usa diferimento para ocultar dependência necessária a `EC-02`.

## 9. Critérios de entrada recomendados

Antes da ativação do eventual escopo:

1. aceite desta definição ou de versão substitutiva;
2. eventual publicação dos bytes aceitos mediante autorização própria;
3. atribuição expressa do identificador, nome, objetivo e limites;
4. designação do responsável humano;
5. criação e aprovação das cinco unidades e produtos;
6. ativação expressa do escopo;
7. preservação da linha mestre e conferência das fontes de entrada.

Antes de cada unidade: autorização específica; fontes obrigatórias disponíveis; produto antecedente aceito e publicado; unidade antecedente concluída. Fonte ausente, divergência física, conflito de autoridade ou necessidade de ampliar mérito causa interrupção do objeto afetado.

## 10. Critérios de aceitação dos produtos

Cada produto deverá apresentar identificação, versão, data, autoridade, escopo, fontes por identidade física, rastreabilidade, decisões separadas de propostas, lacunas, impactos, exclusões, critérios de parada e próximo ato humano.

- E8-01 exige universo e modelo de configuração fechados documentalmente.
- E8-02 exige cobertura nominal dos 123 detalhes e complementos, sem contagem substitutiva.
- E8-03 exige decisões do Gestor ou diferimentos com efeito explícito para cada lacuna incidente.
- E8-04 exige correspondência bidirecional entre detalhe, realização, decisão, controle e fonte, além da indicação de qualquer dependência oculta ou conflito.
- E8-05 exige estado resultante não autoexecutável e condições objetivas para eventual `EC-02`.

Nenhum produto poderá declarar prontidão técnica com base apenas na completude documental. Ausência de prova física futura não invalida por si só a conclusão documental, mas impede a afirmação correspondente sobre funcionamento.

## 11. Critérios de conclusão do eventual escopo

A conclusão documental exigirá:

1. cinco unidades formalmente concluídas;
2. cinco produtos aceitos, publicados e conferidos;
3. manifesto de entradas sem divergência não tratada;
4. cobertura nominal dos 123 detalhes e complementos;
5. decisões ou diferimentos explícitos para L-01 a L-07, com itens dependentes identificados;
6. conferência cruzada com E7-01 a E7-05;
7. proposta de continuidade ou parada;
8. ato humano separado de conclusão do escopo.

O estado resultante poderá ser suficiente para propor `EC-02`, suficiente somente para subconjunto nominal ou insuficiente com impedimentos. Nenhuma dessas alternativas autoriza construção automaticamente.

## 12. Etapas ainda faltantes da Fase 05 a partir deste corte

| Ordem lógica | Etapa | Estado atual | Autorização necessária |
|---:|---|---|---|
| 1 | Formalizar e executar documentalmente EC-01 | Próxima necessidade; somente esta proposta preparada | Aceite/publicação da definição, criação/ativação do escopo e autorizações das unidades |
| 2 | EC-02 — Preparação isolada | Planejada; não iniciada | Autorização construtiva específica, pacote EC-01 suficiente, executor, ambiente e dados delimitados |
| 3 | EC-03 — Estruturas e identidade | Planejada; não iniciada | Conclusão de EC-02 e tratamento de L-01/L-02/L-03/L-07 no alcance dependente |
| 4 | EC-04 — Evidência, histórico e consultas | Planejada; não iniciada | Estruturas aprovadas e regra de reconstrução definida |
| 5 | EC-05 — Verificação e recuperação | Planejada; 30 cenários não executados | EC-04 concluída, destino de backup e execução de testes expressamente autorizados |
| 6 | EC-06 — Revisão e retorno | Planejada; não iniciada | Evidências de EC-05 e relatório submetido ao humano |
| 7 | Avaliar PT-DAD-01, PT-SEG-01 e PT-BCP-01 | Não avaliados no estado corrente | Evidências pertinentes antes de dados reais |
| 8 | Avaliar PT-TEC-01, PT-HOM-01 e PT-OPE-01 | Não avaliados no estado corrente | Construção, homologação e operação nos momentos próprios |
| 9 | Migração, homologação, implantação e promoção operacional | Não iniciadas e não autorizadas | Atos próprios após os portões e evidências aplicáveis |
| 10 | Encerramento da Fase 05 | Fase aberta | Satisfação das condições vigentes e declaração humana separada |

Os portões `PT-DOC-01`, `PT-ESC-01`, `PT-FUN-01` e `PT-ARQ-01` conservam atendimento no alcance documental com ressalvas. `PT-AMB-01` permanece atendido com ressalvas operacionais não impeditivas. Esta minuta não os reavalia.

## 13. Preservações obrigatórias

Permanecem preservados:

- matriz oficial `149/33`, com os mesmos 33 detalhes em `TRT-04` e zero promoção a `TRT-05`;
- `C-F05-05` parcialmente atendida;
- `ALT-02` no alcance adotado, `ALT-04` e `C-F05-09`;
- mapeamento lógico-físico global não encerrado e inventário de 67 itens;
- 36 critérios dos quatro portões de E6, sendo 19 comprovados e 17 comprovados com ressalva;
- limitação de proveniência `4H.5` e demais ressalvas de E6/E7;
- ocorrência publicada de E2-03C e cópia local com LF adicional como objetos distintos;
- ocorrência publicada de E-ESC-01 adotada e cópia distinta preservada;
- Gestor como autoridade humana sistêmica, com COO/LDE contextuais e opcionais;
- operação não bloqueante, cálculos somente informativos e alertas restritos a desvios operacionais verificáveis;
- fonte nativa autoritativa e Power Query auxiliar;
- sete lacunas L como controles locais, sem criação automática de sete `PEN-*`.

## 14. Critérios de parada

Interromper o objeto afetado diante de:

1. divergência física não tratada;
2. fonte obrigatória ausente;
3. conflito material entre fontes, autoridade ou decisões vigentes;
4. necessidade de criar nova regra de negócio ou rever arquitetura;
5. parâmetro material sem alternativa admissível;
6. necessidade de ampliar o Recorte A;
7. tentativa de construir, testar, migrar ou operar sem autorização específica;
8. tentativa de alterar fonte ou registro mestre para contornar a interrupção.

A interrupção deve identificar objeto, evidência, impacto e decisão humana necessária, preservando o trabalho independente já válido.

## 15. Decisão humana pendente e sequência proposta

Recomenda-se aceitar esta configuração candidata com:

- identificador `ESC-F05-08`;
- nome `FECHAMENTO DOCUMENTAL DO PACOTE EC-01 E CONFIGURAÇÃO NOMINAL DO PRIMEIRO RECORTE`;
- Eduardo Andrade Ramos como responsável humano;
- cinco unidades `UT-F05-08-01` a `UT-F05-08-05`;
- cinco produtos `E8-01` a `E8-05`;
- alcance exclusivamente documental;
- manutenção integral das ressalvas e ausência de autorização construtiva.

Após eventual aceite desta definição, sua publicação dependerá de autorização expressa. Criação, responsabilidade, ativação e execução documental das unidades poderão ser formalizadas por ato humano próprio. O início de `UT-F05-08-01` dependerá de autorização específica.

**Estado de saída desta minuta:** definição formal preparada; `ESC-F05-08` somente candidato; responsável somente recomendado; cinco unidades e cinco produtos somente propostos; nenhuma unidade iniciada; EC-02 a EC-06 permanecem planejadas; 30 cenários não executados; Fase 05 aberta; sem implementação.
