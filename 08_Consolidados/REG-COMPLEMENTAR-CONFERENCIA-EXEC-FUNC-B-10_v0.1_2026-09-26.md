# REGISTRO COMPLEMENTAR — CONFERÊNCIA DE EXEC-FUNC-B-10

**Projeto:** Dev_Ecossistema_Integrado_Gestao_Empresarial  
**Fase:** 05  
**Frente:** Consolidação do Projeto — Chat 91F  
**Ocorrência:** EXEC-FUNC-B-10  
**Versão:** v0.1  
**Data:** 2026-09-26  
**Classificação:** evidência complementar aceita; não substitui a linha mestre vigente

## 1. Resultado

A conferência cruzada dos seis arquivos conclusivos recebidos classificou a ocorrência **EXEC-FUNC-B-10 como CONFORME e APTO para homologação funcional do primeiro recorte sintético**.

Dentro desse recorte:

- EC-03, EC-04, EC-05 e EC-06 constam como concluídas;
- E7-04 registra 30 cenários únicos, T01 a T30, todos aprovados;
- a regressão funcional de B-09 registra 11 testes únicos, B09-R01 a B09-R11, todos aprovados;
- a validação OOXML registra 79 de 79 ocorrências temporais canônicas e ausência de fórmulas;
- a recuperação independente registra igualdade de bytes, SHA-256, inventário ZIP e CRC;
- não há falha aberta;
- nenhum artefato foi promovido para `04_OFICIAL`.

A classificação é restrita ao primeiro recorte sintético e não equivale à conclusão geral do ecossistema, à aceitação retroativa de B-08 ou à promoção para uso oficial.

## 2. Produtos conferidos

| Produto | Bytes | SHA-256 |
|---|---:|---|
| `EIGE_ARQ-OP_B10.xlsx` | 44.283 | `4b62d90735ba8ac2b2a50c0f9df632c4146b62439f9cccc6908c294ee4aaf51e` |
| `EIGE_ARQ-FIN_B10.xlsx` | 5.568 | `13ff153bf6d6cbd7397379db6422a7bd499e2e37783296e54082651b252e4e98` |
| `ENTREGA-B-10.zip` | 9.533.864 | `5146ac2fc9866efbcfa247da90f71ae660f866339f26a9c5d45e84dccb63f603` |

O pacote registra 94 entradas únicas com CRC conforme. As cópias histórica e de recuperação possuem o mesmo tamanho e SHA-256. As cópias de homologação dos dois XLSX coincidem com os produtos de construção.

A planilha financeira contém apenas referência de origem/versão ao núcleo Operacional e não implementa cálculos financeiros nesta ocorrência.

## 3. Conferência cruzada executada no 91F

Foram verificados:

1. validade sintática dos cinco arquivos JSON;
2. concordância entre relatório executivo, manifesto final, resultados T01–T30, regressão B-09, registro de falhas/correções e conferência do pacote;
3. presença de 30 identificadores únicos T01–T30, sem resultado diferente de `APROVADO`;
4. presença de 11 identificadores únicos B09-R01–B09-R11, sem resultado diferente de `APROVADO`;
5. coincidência de tamanho, SHA-256, quantidade de entradas, unicidade e CRC do pacote entre manifesto e conferência;
6. registro de zero falhas abertas e preservação das tentativas e correções;
7. manutenção da linha de base dos seis grupos protegidos.

Esta conferência do 91F validou a coerência dos arquivos conclusivos recebidos. O ZIP e os XLSX não foram transferidos ao 91F; portanto, o recálculo direto dos bytes desses três binários permanece sustentado pela recuperação independente registrada pelo executor técnico e pela concordância dos documentos conclusivos.

## 4. Integridade dos arquivos conclusivos recebidos

| Arquivo | SHA-256 |
|---|---|
| `REL-EXECUCAO_EXEC-FUNC-B-10.md` | `6a78bac5cf23a15894f8b1067d808f9f137f0d766c7dfffa051cfbe8be551f85` |
| `MANIFESTO-FINAL_EXEC-FUNC-B-10.json` | `34d70860d620052de0e298c282bc6855c3701f5b232fae9c24391d58e30e78f3` |
| `resultados_cenarios_T01_T30.json` | `fd00bf072baede8501b803d5ad6a80595078335c10de9f9fa1e71d038d231f9b` |
| `resultados_regressao_B09.json` | `8e333cf4c12d80f35d2d7908e75109ede4a6779dcab856512f0a08ac0100eec4` |
| `falhas_e_correcoes.json` | `61cd6b81ced95b39a6c796458eac417a5b8113fb6bbbf2693addf4a10880a8d9` |
| `conferencia_pacote.json` | `e7fbef9f102b83f192f273d7147d1f6ddfaa943ff72adccf7a3b0e7dd3c6a0d8` |

## 5. Falhas e correções preservadas

O histórico registra e não oculta:

- falha inicial de acesso ao workspace, corrigida antes da produção dos artefatos;
- falha de resolução do runtime na reabertura independente;
- tentativas 01 e 02 com coerção numérica de instantes;
- tentativa 03 corrigida com texto temporal canônico;
- regra inicial incompleta do validador OOXML, corrigida e retestada;
- critério inicialmente excessivo do T10, corrigido sem alterar as planilhas;
- agregação inicialmente incompleta da regressão B-09, corrigida para os quatro recortes físicos;
- rejeições adversas esperadas em T27, T29 e T30.

Todas constam com correção e reteste aprovados. Falhas abertas: zero.

## 6. Preservação

| Grupo | Arquivos | Hash agregado |
|---|---:|---|
| B-07 | 32 | `71f8264aa92035c85c02e104bf5ef0afbb1059618d6fc4def4f0522db522dc06` |
| B-08 | 9 | `072826a806849ecda7166d4ed61f4355699f044928f2e354ad9e09c76071315a` |
| B-09 | 26 | `d32dd34a65a4c51736a9bed8b5b180a5088f0993ab62c08ae842e91ae2ed25ac` |
| EVD-01 | 16 | `3e48181746c87a0f5cc2b04f47684fd23e56e53c581b5d55074a8cd32fe10dce` |
| EVD-02 | 29 | `2986c5538515d5df7525e6698e703430b23955d234787c4401ad6b0bd453e7e4` |
| EVD-03 | 33 | `1045aa8986610eed6f277fbf9d98b1e47ec55cb8933a4b1c89ec763d0958ea0a` |

A contagem global externa a B-10 permaneceu em 279 arquivos. O hash agregado global inicial não foi reproduzido por ambiguidade do recorte original. A limitação permanece registrada e não substitui os seis controles determinísticos acima, todos conformes. Essa ressalva não bloqueia a classificação do recorte, mas não deve ser usada para alegar identidade de um conjunto global cuja seleção inicial não foi formalizada.

## 7. Estado após o fechamento

- B-08 permanece interrompida e não foi aceita retroativamente.
- B-09 permanece aceita conforme sua conferência própria.
- EXEC-FUNC-B-10 fica encerrada tecnicamente como **APTA PARA HOMOLOGAÇÃO FUNCIONAL**.
- As cópias de homologação permanecem em `03_HOMOLOGACAO/ENTREGA-B-10`.
- `04_OFICIAL` permanece sem promoção.
- A linha mestre oficial permanece `REG-CONSOLIDACAO-CHATS v0.23`, `REG-DECISOES v0.27` e `REG-PENDENCIAS v0.22`; as versões posteriores continuam classificadas como minutas até ato expresso de consolidação.

## 8. Próximo ato material

O próximo ato é a **homologação funcional humana do primeiro recorte** nas cópias já colocadas em `03_HOMOLOGACAO/ENTREGA-B-10`.

A conferência técnica não substitui a validação de usabilidade e aderência ao trabalho real. Somente após essa homologação deve ser tomada a decisão material de promover uma cópia limpa para `04_OFICIAL` ou abrir correção delimitada. Não há motivo técnico para repetir EXEC-FUNC-B-10.
