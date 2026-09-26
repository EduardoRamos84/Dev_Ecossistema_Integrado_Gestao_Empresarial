# INSTRUÇÃO EXECUTÁVEL — EXEC-HOM-B-11

**Versão:** v0.1 — 26/09/2026  
**Projeto:** Dev_Ecossistema_Integrado_Gestao_Empresarial  
**Executor:** Codex Desktop no computador Windows autorizado  
**Natureza:** homologação técnica assistida, verificação de operabilidade e preparação condicional de candidatas limpas  
**Fonte:** EXEC-FUNC-B-10 encerrada como APTO PARA HOMOLOGAÇÃO DO PRIMEIRO RECORTE

## 1. Autorização e objetivo

O responsável humano autorizou o 91F a prosseguir sem novos pedidos de aceite mecânico e a criar a ocorrência necessária para avançar as planilhas.

Fica criada e autorizada a ocorrência `EXEC-HOM-B-11`.

Objetivos:

1. verificar, no ambiente local efetivo, se as planilhas de B-10 abrem, salvam, reabrem e permanecem íntegras;
2. comprovar se o primeiro recorte pode ser operado de maneira compreensível e reproduzível, sem ocultar dependência de scripts;
3. executar um ensaio funcional descartável de ponta a ponta;
4. preservar B-10 integralmente;
5. somente se os critérios forem atendidos, produzir candidatas limpas para homologação, sem dados sintéticos de ensaio e sem promoção para `04_OFICIAL`;
6. informar objetivamente se já existe planilha utilizável ou se ainda existe lacuna material de operação.

Não solicitar aceite intermediário ao usuário. Corrigir e retestar, dentro de B-11, falhas técnicas delimitadas que não alterem regras de negócio nem arquitetura aprovada.

## 2. Fontes obrigatórias e identidades

Raiz local:

`C:\Automacao_Integracao_Sistemas\01_Sistema_Integrado`

Fontes B-10, somente leitura:

- `03_HOMOLOGACAO\ENTREGA-B-10\EIGE_ARQ-OP_B10.xlsx`
  - 44.283 bytes;
  - SHA-256 `4b62d90735ba8ac2b2a50c0f9df632c4146b62439f9cccc6908c294ee4aaf51e`.
- `03_HOMOLOGACAO\ENTREGA-B-10\EIGE_ARQ-FIN_B10.xlsx`
  - 5.568 bytes;
  - SHA-256 `13ff153bf6d6cbd7397379db6422a7bd499e2e37783296e54082651b252e4e98`.
- `05_EVIDENCIAS\ENTREGA-B-10\ENTREGA-B-10.zip`
  - 9.533.864 bytes;
  - SHA-256 `5146ac2fc9866efbcfa247da90f71ae660f866339f26a9c5d45e84dccb63f603`;
  - 94 entradas únicas;
  - CRC conforme.

Antes da primeira escrita:

1. recalcular as três identidades;
2. conferir que B-10, B-09, B-08, B-07 e EVD-01 a EVD-03 continuam preservados;
3. inventariar eventuais objetos preexistentes com nome B-11;
4. gravar o manifesto inicial de B-11.

Divergência de fonte ou alteração de área protegida exige parada com relatório objetivo.

## 3. Áreas autorizadas

Criar e usar apenas áreas novas `ENTREGA-B-11` sob:

- `00_CONTROLE`;
- `01_CONSTRUCAO`, apenas para cópias de trabalho e eventual candidata limpa;
- `02_TESTES`;
- `03_HOMOLOGACAO`, somente para candidatas aprovadas;
- `05_EVIDENCIAS`;
- `99_HISTORICO`, somente para pacote fechado e recuperação.

Não sobrescrever qualquer arquivo existente. Se B-11 já existir, inventariar e usar tentativa numerada.

## 4. Preservação obrigatória

- Não alterar B-07, B-08, B-09 ou B-10.
- Não alterar EVD-01, EVD-02 ou EVD-03.
- Manter B-08 interrompida.
- Não aceitar B-08 retroativamente.
- Usar somente dados sintéticos novos nas cópias descartáveis.
- Criar UUIDv7 novos para os registros do ensaio B-11.
- Não usar dados reais.
- Não criar links externos.
- Não acessar OneDrive pessoal.
- Não publicar ou fazer upload de planilhas, pacotes ou dados.
- Não gravar em `04_OFICIAL`.

## 5. Gate A — abertura e compatibilidade no aplicativo

Trabalhar sobre cópias descartáveis de B-10.

Preferir Microsoft Excel Desktop instalado no computador. Pode usar automação COM/PowerShell para abrir, salvar e reabrir, desde que registre a versão do aplicativo e preserve as cópias antes/depois.

Confirmar separadamente nas duas planilhas:

1. abertura sem reparo, corrupção ou perda;
2. ausência de solicitação de atualização de links externos;
3. ausência de macros, consultas externas e conexões não autorizadas;
4. nomes das abas, tabelas nativas, filtros, cabeçalhos, larguras, congelamentos e leitura visual;
5. salvamento e reabertura sem alteração inesperada;
6. manutenção dos valores temporais como texto canônico no OOXML;
7. ausência de fórmulas inesperadas;
8. igualdade ou diferença de bytes explicada após o ciclo abrir–salvar–reabrir.

Se Microsoft Excel Desktop não estiver disponível ou não puder ser efetivamente acionado, não simular homologação nativa. Registrar a limitação e continuar apenas com os gates independentes possíveis.

## 6. Gate B — ensaio funcional descartável

Em cópias descartáveis, executar um fluxo integrado e rastreável com novos dados sintéticos:

1. criar organização;
2. criar empresa faturadora;
3. criar projeto;
4. vincular faturadora ao projeto;
5. criar executor técnico quando aplicável;
6. registrar identidades;
7. registrar evento de auditoria;
8. consultar estado corrente;
9. consultar histórico;
10. consultar por data de corte;
11. gerar alerta `NAO_COMPROVADA` como `atenção` / `ABERTO`, alvo `PROJETO`, não bloqueante;
12. comprovar inabilitação como crítica e bloqueante;
13. preservar os alertas contratuais críticos;
14. registrar ciência sem resolver indevidamente a condição;
15. salvar, fechar e reabrir;
16. confirmar referências, cardinalidades, UUIDv7, temporal OOXML, ausência de órfãos e ausência de colisões.

Reexecutar os 11 testes de regressão B-09 sobre o resultado do ensaio.

Não executar novamente os 30 cenários de E7-04, salvo caso afetado diretamente por correção de B-11. Qualquer repetição deve ser justificada e limitada.

## 7. Gate C — verificação de operabilidade

Determinar e demonstrar o modo real de operação:

- edição manual segura nas tabelas;
- uso de script;
- combinação dos dois;
- ou ausência de fluxo operacional utilizável.

Registrar:

1. quais ações um usuário comum consegue realizar sem editar código;
2. quais ações dependem de scripts;
3. como executar cada ação dependente;
4. se há validações suficientes para impedir referência inválida, duplicidade e temporal inadequado;
5. se o núcleo Operacional é compreensível sem consultar documentação extensa;
6. se a planilha Financeiro é apenas referência de origem/versão, sem cálculos financeiros;
7. quais funcionalidades do ecossistema completo ainda não existem.

Não classificar como “pronta para uso” uma estrutura que somente armazena evidências ou que exija intervenção técnica não documentada para operações ordinárias.

## 8. Candidatas limpas condicionais

Somente se Gates A, B e C forem aprovados e se for possível distinguir objetivamente dados de configuração de dados sintéticos de ensaio:

1. gerar:
   - `01_CONSTRUCAO\ENTREGA-B-11\EIGE_ARQ-OP_B11_LIMPA.xlsx`;
   - `01_CONSTRUCAO\ENTREGA-B-11\EIGE_ARQ-FIN_B11_LIMPA.xlsx`;
2. remover registros de teste e demonstração;
3. preservar integralmente esquema, tabelas, cabeçalhos, validações, estilos, larguras, congelamentos, referências normativas e metadados necessários;
4. não deixar órfãos, UUIDs de ensaio, alertas de ensaio ou histórico sintético;
5. repetir inspeção estrutural, OOXML, referências, abertura, salvamento e reabertura;
6. copiar byte a byte as candidatas aprovadas para:
   - `03_HOMOLOGACAO\ENTREGA-B-11`.

Se não for possível separar configuração de massa sintética sem inferência, não produzir candidata limpa. Registrar a lacuna de modo explícito.

## 9. Correções autorizadas

Dentro das cópias B-11, podem ser corrigidos sem novo aceite:

- serialização temporal;
- validação de dados já prevista;
- referência quebrada;
- largura, congelamento, filtro ou formatação que impeça uso;
- erro de script;
- conflito de nome;
- empacotamento;
- relatório incompleto;
- falha de teste causada por implementação divergente da regra já aprovada.

Para cada correção:

1. preservar tentativa reprovada;
2. registrar causa;
3. corrigir apenas B-11;
4. retestar o caso e dependências;
5. executar regressão final.

Parar se a correção exigir nova regra de negócio, novo requisito funcional, mudança da arquitetura ALT-04-B2 ou uso de dados reais.

## 10. Classificação final

Usar exatamente uma classificação:

### A. `HOMOLOGADA TECNICAMENTE PARA OPERAÇÃO ASSISTIDA`

Quando:

- Gates A e B aprovados;
- regressão B-09 em 11/11;
- Gate C demonstra fluxo operacional reproduzível;
- zero falha material aberta;
- áreas protegidas intactas;
- candidatas limpas produzidas e conferidas.

### B. `ESTRUTURA TÉCNICA VÁLIDA, MAS NÃO PRONTA PARA OPERAÇÃO`

Quando a estrutura e os testes permanecem válidos, porém falta interface, automação, documentação operacional mínima, separação segura da massa sintética ou outro elemento necessário ao uso ordinário.

### C. `NÃO HOMOLOGADA`

Quando houver corrupção, perda, referência inválida, falha funcional material, temporal numérico, regressão, alteração de área protegida ou recuperação inconclusiva.

Nenhuma classificação autoriza gravação em `04_OFICIAL`.

## 11. Saídas obrigatórias

Produzir:

- manifesto inicial e final;
- inventário das fontes e áreas protegidas;
- relatório do Gate A;
- relatório do Gate B;
- relatório do Gate C;
- regressão B-09;
- inventário de tentativas, falhas, correções e retestes;
- hashes de todos os arquivos novos;
- candidatas limpas, somente se autorizadas pelos critérios;
- pacote ZIP B-11;
- cópia histórica e recuperação separada;
- `REL-EXECUCAO_EXEC-HOM-B-11.md`.

## 12. Retorno ao 91F

Informar apenas:

1. classificação A, B ou C;
2. resultados dos Gates A, B e C;
3. placar da regressão B-09;
4. se as planilhas são realmente operáveis por usuário comum;
5. funcionalidades que ainda não existem;
6. caminhos, tamanhos e SHA-256 dos novos arquivos;
7. falhas e correções;
8. confirmação de preservação;
9. próximo ato material recomendado.

Não pedir aceite mecânico e não repetir B-10.
