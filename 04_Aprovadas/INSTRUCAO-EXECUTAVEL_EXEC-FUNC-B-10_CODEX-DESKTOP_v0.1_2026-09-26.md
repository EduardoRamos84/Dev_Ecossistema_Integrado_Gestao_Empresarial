# INSTRUÇÃO EXECUTÁVEL — EXEC-FUNC-B-10

**Versão:** v0.1 — 26/09/2026  
**Projeto:** Dev_Ecossistema_Integrado_Gestao_Empresarial  
**Executor:** Codex Desktop no computador Windows autorizado  
**Natureza:** ocorrência técnica isolada, corretiva, construtiva e de validação integral do primeiro recorte sintético  
**Abrangência:** EC-03 a EC-06 no recorte de E7-04  

## 1. Autorização e objetivo

O responsável humano autorizou expressamente o 91F a decidir o identificador, o escopo e a condução da nova ocorrência técnica, incluindo correções e repetições necessárias, com a finalidade de avançar até planilhas funcionais e reduzir novos pedidos de autorização.

Fica criada e autorizada a ocorrência `EXEC-FUNC-B-10`.

Objetivo: partir da planilha final conferida de B-09, construir o que faltar no primeiro recorte sintético, executar os 30 cenários de E7-04, repetir os 11 testes dirigidos de B-09, corrigir defeitos dentro desta mesma ocorrência, comprovar recuperação e entregar candidatas de homologação com relatório conclusivo.

Esta autorização cobre as operações descritas nesta instrução, inclusive tentativas, diagnóstico, correção, reexportação, reteste afetado, empacotamento e cópia para homologação quando os critérios forem atendidos. Não solicitar aceite intermediário ao usuário.

## 2. Estado de entrada obrigatório

Raiz local autorizada:

`C:\Automacao_Integracao_Sistemas\01_Sistema_Integrado`

Fonte construtiva principal, somente leitura:

`01_CONSTRUCAO\ENTREGA-B-09\EIGE_ARQ-OP_B09.xlsx`

Identidade esperada da fonte:

- tamanho: 16.111 bytes;
- SHA-256: `610425bf9fd5ffb9bcdf8f0a9a2daa43c8a228a3b0d43de3e3f24e4662544583`;
- estrutura: 3 abas, 11 tabelas nativas, nenhuma fórmula;
- temporal OOXML: 26 valores textuais e 0 valores seriais numéricos.

Pacote B-09 esperado: 257.610 bytes; SHA-256 `bd0703c3ace3af3a5c44b9c73aaf95d6966ad3daee1a27953e2976cb313d7a85`; 24 entradas; CRC íntegro; manifesto com 23 arquivos de carga.

Plano de testes oficial:

`04_Aprovadas/E7-04_PLANO-DE-CONSTRUCAO-TESTES-E-EVIDENCIAS-DO-PRIMEIRO-RECORTE_v0.1_2026-09-20.md`

Identidade publicada de E7-04: 23.532 bytes; SHA-256 `b0ab3bc49392eda71f3d900e702a2923bd65a93ba481aac1bf80d613f84c871f`.

Preservações obrigatórias:

- B-07, B-08 e B-09 completos;
- EVD-01, EVD-02 e EVD-03;
- manifesto, adendo, planilha tentativa, auxiliar, prévia e UUIDs de B-08;
- primeira exportação, diagnóstico, auxiliar, planilha final, pacote e UUIDs de B-09;
- todos os documentos e evidências anteriores.

B-08 permanece interrompida. Não corrigir, completar ou aceitar B-08. B-10 usa B-09 como fonte de leitura.

## 3. Áreas autorizadas

Criar e usar exclusivamente áreas novas `ENTREGA-B-10` sob:

- `00_CONTROLE`;
- `01_CONSTRUCAO`;
- `02_TESTES`;
- `03_HOMOLOGACAO`;
- `05_EVIDENCIAS`;
- `99_HISTORICO` somente para o pacote fechado e sua cópia de recuperação.

Antes da primeira escrita:

1. conferir as identidades da fonte B-09, do pacote B-09 e das áreas protegidas;
2. inventariar conflitos de nome nas áreas B-10;
3. gravar `MANIFESTO-INICIAL_EXEC-FUNC-B-10.json` em `00_CONTROLE\ENTREGA-B-10`;
4. copiar a fonte B-09 para uma tentativa B-10, mantendo a fonte intacta.

Se uma área B-10 já existir, não sobrescrever. Inventariá-la e criar uma tentativa numerada dentro dela.

## 4. Saídas obrigatórias

Produzir, quando tecnicamente compatível com as fontes aprovadas:

- `01_CONSTRUCAO\ENTREGA-B-10\EIGE_ARQ-OP_B10.xlsx`;
- `01_CONSTRUCAO\ENTREGA-B-10\EIGE_ARQ-FIN_B10.xlsx`;
- scripts e configurações usados, com versão e hash;
- massa exclusivamente sintética;
- relatório individual de T01 a T30;
- relatório de regressão dos 11 testes de B-09;
- inventários inicial e final;
- manifesto final com tamanho e SHA-256 de cada arquivo;
- pacote ZIP fechado da ocorrência;
- relatório executivo `REL-EXECUCAO_EXEC-FUNC-B-10.md`;
- planilhas aprovadas, byte a byte idênticas às construídas, em `03_HOMOLOGACAO\ENTREGA-B-10`.

A planilha Financeiro deve implementar somente a referência rastreável de origem e versão do núcleo Operacional prevista em DF-01-A e T26. Não criar cálculo financeiro, saldo, faturamento ou regra de negócio não aprovada.

## 5. Construção autorizada — EC-03 e EC-04

Completar no alcance sintético necessário aos testes:

- identidades tipadas e UUIDv7 novos para B-10;
- alvos, referências, chaves, empresa e responsável somente onde houver fonte aprovada;
- eventos apensos, versões, antes/depois tipados, correções correlatas e linhagem;
- representação explícita de zero, não informado, pendente, não aplicável e objeto inexistente;
- textos e payloads nos limites definidos em E7-04;
- valores temporais canônicos como texto, preservando precisão e fuso;
- alertas, ciência, tratamento, resolução, encerramento justificado e deduplicação;
- consultas por estado corrente, histórico e data de corte;
- referência Operacional–Financeiro com origem e versão, sem segunda fonte editável do núcleo.

Todo instante persistido em XLSX deve ser conferido diretamente no OOXML antes dos testes: tipo textual, nenhum serial numérico nos campos temporais do recorte.

Nenhum dado real pode ser usado. Nenhuma fórmula originada de texto de teste pode ser executada. Valores que começam por `=`, `+`, `-` ou `@` devem permanecer dados literais quando o campo for textual.

## 6. Catálogo obrigatório de E7-04

Executar e registrar separadamente os 30 casos oficiais, preservando o resultado esperado de E7-04:

| ID | Núcleo do teste |
|---|---|
| T01 | manifesto, igualdade de bytes e divergência por LF |
| T02 | UUIDv7 válido, formato inválido e colisão |
| T03 | reserva interrompida e retomada idempotente |
| T04 | referência válida, inexistente e tipo errado |
| T05 | duplicidade exata, possível e chave incompleta |
| T06 | zero, não informado, pendente e não aplicável |
| T07 | metadados conhecidos e responsável desconhecido |
| T08 | objeto inexistente e atributo pendente |
| T09 | limites 255/256, 4.000/4.001 e 16.000/16.001 Unicode |
| T10 | zeros iniciais, fórmula literal e JSON com escapes |
| T11 | antes/depois válido, incompatível e esquema desconhecido |
| T12 | ano, competência, data, instante e fuso insuficiente |
| T13 | início posterior ao fim e eixos não comparáveis |
| T14 | V1, V2, antecessor e estado corrente |
| T15 | correção por evento correlato e navegação reversa derivada |
| T16 | segregação por empresa e empresa inexistente |
| T17 | prática, documento oficial e fórmula como evidência |
| T18 | equivalência somente por finalidade comprovada |
| T19 | exceção limitada e modelos sem equivalência |
| T20 | evidência por bytes, alteração e referência sem arquivo |
| T21 | elo válido, autociclo, nó ausente e elo duplicado |
| T22 | deduplicação de alerta e ciência sem resolver condição |
| T23 | resolução sem providência, tratamento válido e encerramento justificado |
| T24 | ausências opcionais e desvio crítico real |
| T25 | fonte alterada e fonte inacessível |
| T26 | consulta pelo Financeiro sem autoridade concorrente |
| T27 | conflito de sincronização e reconciliação antes de liberar versão |
| T28 | cópias anterior/posterior, configuração e conjunto recuperável |
| T29 | restauração separada válida, divergente e incompleta |
| T30 | cenário ausente, falha preservada, correção e reteste identificado |

Cada tentativa deve registrar entrada, passos executados, esperado, observado, evidências, tamanho, SHA-256, conclusão e vínculos com tentativas anteriores.

## 7. Regressão B-09

Reexecutar os 11 controles conferidos em B-09. Os testes que antes tinham apenas evidência estática, especialmente inabilitação comprovada e consulta por data de corte, devem ser executados funcionalmente nesta ocorrência.

Confirmar ainda:

- alerta `NAO_COMPROVADA` como `atenção` / `ABERTO`, alvo `PROJETO`, sem bloqueio;
- faturadora identificada pela associação existente;
- inabilitação comprovada como crítica e bloqueante;
- alertas contratuais críticos preservados;
- identidades B-10 novas e sem colisão com B-08/B-09;
- três abas e 11 tabelas da fonte preservadas ou diferenças construtivas explicitamente inventariadas;
- 26 valores temporais originais de B-09 ainda textuais.

## 8. Correções e repetição dentro da mesma ocorrência

Falha técnica corrigível não encerra automaticamente B-10. Executar este ciclo:

1. preservar a tentativa e sua evidência;
2. diagnosticar a causa;
3. corrigir somente na área B-10;
4. registrar a alteração;
5. repetir o caso afetado e as dependências justificadas;
6. executar regressão final.

Não corrigir silenciosamente. Não apagar tentativa reprovada. Não alterar resultado esperado para aprovar a implementação.

Parar somente diante de:

- fonte obrigatória ausente ou com identidade divergente;
- alteração observada em B-07, B-08, B-09 ou EVD-01–03;
- conflito real entre decisões aprovadas que exija nova regra de negócio;
- necessidade inevitável de dados reais;
- impossibilidade técnica de preservar os artefatos anteriores.

Nesse caso, produzir relatório de parada com o bloqueio exato e preservar tudo já realizado.

## 9. Critério de encerramento

Classificar o resultado:

- `APTO PARA HOMOLOGAÇÃO DO PRIMEIRO RECORTE`: T01–T30 aprovados, 11/11 regressões aprovadas, recuperação aprovada, 0 falhas abertas e 0 divergências de preservação;
- `APTO COM RESSALVAS EXPLÍCITAS`: somente casos não aplicáveis com justificativa demonstrável, sem falha material aberta;
- `NÃO APTO`: qualquer falha material aberta, referência inconsistente, perda de conteúdo, temporal numérico, colisão, sobrescrita histórica ou recuperação não comprovada.

Somente no primeiro resultado, copiar as duas planilhas para `03_HOMOLOGACAO\ENTREGA-B-10`. No segundo, manter as candidatas em `01_CONSTRUCAO` e submeter as ressalvas no relatório. No terceiro, preservar tentativas e não promover.

## 10. Limites

- Não alterar ou excluir B-07, B-08, B-09 ou EVD-01–03.
- Não usar dados reais.
- Não migrar legados.
- Não gravar em `04_OFICIAL`.
- Não publicar planilhas, pacotes ou dados no GitHub, Google Drive ou outro serviço.
- O acesso ao GitHub, se necessário, é somente leitura para obter documentos aprovados.
- Não acessar OneDrive pessoal. Se o OneDrive corporativo for necessário para conferir fonte já existente, usar exclusivamente a conta `eduardo.ramos@congespu.com` e não criar upload sem necessidade técnica registrada.
- Não declarar o ecossistema integral concluído. O resultado se limita ao primeiro recorte transversal sintético.

## 11. Retorno ao 91F

Ao final, informar de forma objetiva:

1. classificação final;
2. caminhos, tamanhos e SHA-256 das duas planilhas;
3. placar T01–T30;
4. placar da regressão 11/11;
5. falhas, correções e retestes preservados;
6. resultado da recuperação;
7. identidade do ZIP e do manifesto;
8. confirmação dos inventários protegidos;
9. limitações materiais remanescentes;
10. próximo ato técnico concreto, sem solicitar aceite mecânico.
