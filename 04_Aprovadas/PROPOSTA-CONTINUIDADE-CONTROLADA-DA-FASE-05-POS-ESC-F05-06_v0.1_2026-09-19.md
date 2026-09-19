# PROPOSTA DE CONTINUIDADE CONTROLADA DA FASE 05 PÓS-ESC-F05-06

Versão v0.1 | 19/09/2026 | MINUTA — NÃO PUBLICADA — AGUARDANDO ACEITE E ESCOLHA HUMANA

## 1. Objetivo, autoridade e alcance

Projeto: Dev_Ecossistema_Integrado_Gestao_Empresarial. Responsável humano: Eduardo Andrade Ramos.

O humano aceitou o resultado da publicação sincronizada da linha mestre v0.22/v0.26/v0.21 e autorizou prosseguir, solicitando também a identificação das etapas remanescentes. Esta autorização fundamenta a presente proposta documental e o roteiro de continuidade. Não autoriza implementação, criação/ativação automática de novo escopo, edição dos registros mestres ou publicação desta minuta.

Objetivo: indicar o próximo trabalho útil e distinguir decisões documentais remanescentes de construção, evidência física, homologação e operação. Esta proposta não repete as avaliações concluídas e não modifica decisões de negócio ou arquitetura.

## 2. Situação atual aceita

- ESC-F05-06 concluído exclusivamente documentalmente, com ressalvas vinculantes.
- Cinco unidades concluídas; E6-01 a E6-05 aceitos, publicados e conferidos.
- PT-DOC-01, PT-ESC-01, PT-FUN-01 e PT-ARQ-01 atendidos individualmente no alcance documental, com ressalvas.
- Publicação sincronizada dos três registros mestres concluída e seu resultado aceito pelo humano nesta continuidade.
- Linha mestre vigente: REG-CONSOLIDACAO-CHATS v0.22; REG-DECISOES v0.26; REG-PENDENCIAS v0.21.
- Fase 05 aberta administrativamente; construção e implementação não autorizadas.

A linha mestre também preserva o estado de PT-AMB-01 adotado por DEC-91-138: ATENDIDO, COM RESSALVAS OPERACIONAIS NÃO IMPEDITIVAS. Esse estado não foi reavaliado por ESC-F05-06 e não deve ser colocado novamente como portão nunca avaliado. Sua validade operacional futura deverá ser considerada diante de mudanças concretas no ambiente, sem repetir automaticamente a avaliação.

Há ambiente de trabalho e evidências históricas de diretórios/snapshot; isso não equivale à estrutura física da solução de negócio. A ausência de planilhas operacionais construídas é compatível com a existência do ambiente previamente preparado.

## 3. Fontes e precedência

Fontes primárias: trio mestre recém-publicado, commit bcf1baeff0403440ac20e9cb70e74e5a37384054, partes prospectivas e encadeamento histórico preservado; E6-05 v0.1 §§7–11; E5-03 v0.1 §18; E5-04 v0.1 §§7, 10 e 13. E5-04 foi recuperado no commit citado. Os produtos E6 e a linha mestre já foram conferidos na publicação anterior, aceita pelo humano.

O PLANO-TRANSICAO-PARA-CONSTRUCAO v0.1 de 08/09/2026, anexo histórico consultado, fornece as categorias TR-07 a TR-10, EXE-01 a EXE-06 e a sequência geral dos portões. Seus estados iniciais e referências antigas de repositório/validação externa não prevalecem sobre os atos posteriores da linha mestre. Sua publicação autônoma corrente no Git não foi comprovada nesta consulta; não se usa esse anexo para atribuir estado vigente a portão ou restabelecer decisão superada.

| Fonte vigente | Bytes | SHA-256 |
|---|---:|---|
| REG-CONSOLIDACAO-CHATS v0.22 | 179543 | 94d56af3bfafac119c3f96b0ca9b2b85c56da2cd9ac1d27ba2ab1f38430c9a1b |
| REG-DECISOES v0.26 | 238002 | 35bcacee52fa07418ea968c251275751ffd5490beab29de0771e232bce05c590 |
| REG-PENDENCIAS v0.21 | 172681 | 8648ed7a3cd6cdba56a7d9a57b690abc8321016d21880adf767427174d6412a8 |
| E6-05 v0.1 | 26645 | 53bb8851a8c954d6f775e45c3f94efd9f64c68eba512b55a3b9481c9c9be7844 |
| E5-03 v0.1 | 41433 | 03048c54a80b29f211d8d8f52f2611b233d2161305faeb4525d089dd4440c9fc |
| E5-04 v0.1 | 40091 | 3b10c140121108592a07a22712950ad24221e9ae8fc7105509b16f3e623cbf31 |

Os atos de aceite da publicação e autorização desta proposta são evidência humana desta continuidade, sem criação de DEC-* por inferência. O SHA-256 e tamanho desta minuta constam externamente na entrega.

## 4. Decisões que não precisam ser refeitas

A cadeia vigente já adotou os nomes futuros EIGE_ARQ-OP_v0.1.xlsx e EIGE_ARQ-FIN_v0.1.xlsx, o modelo híbrido controlado, estruturas nativas do Excel como camada autoritativa e Power Query auxiliar quando aplicável, editor único, proibição de sobrescrita e publicação somente após validação e autorização humana.

Essas decisões delimitam o próximo desenho; não comprovam que tabelas, fórmulas, associações e controles já existem. As menções genéricas a tecnologia e nomes futuros nos relatórios de lacunas devem ser lidas com essa distinção. Não se propõe reabrir a escolha da plataforma ou renomear os dois arquivos; faltam escolhas de realização concreta no recorte a construir.

Também não devem ser refeitos ESC-F05-01 a ESC-F05-06, as cinco unidades de ESC-F05-06, suas 36 avaliações individuais ou os aceites de publicação já consumados.

## 5. Etapas remanescentes — roteiro proposto

Os seis grupos abaixo organizam o trabalho; não são novos escopos ou unidades formalmente criados, nem estimativa de quantidade de entregas. A sequência depende das decisões e da aplicabilidade de cada requisito ao primeiro recorte.

| Grupo | O que falta | Resultado esperado e condição de saída |
|---|---|---|
| 1. Delimitação da primeira construção | Fixar módulos, operações, dados, inclusões/exclusões, dependências e critérios de aceite; identificar regras residuais que afetam exatamente esse recorte | Especificação documental revisável da primeira versão ou lote, sem construção |
| 2. Desenho físico e parâmetros do recorte | Mapear objetos para arquivos/tabelas/campos; definir nomes internos, associações, integridade, precisão, escala, comprimentos, tolerâncias, retenção, alertas, evidências e fontes informativas pertinentes | Mapeamento físico proposto e decisões expressas, preservando lacunas e condicionantes |
| 3. Preparação e autorização da execução | Reunir entradas versionadas, backup, roteiro de construção, cenários de teste, critérios de aprovação, limites de alteração e publicação; conferir aplicabilidade do ambiente já aprovado | Pacote de execução aceito e autorização expressa para um lote limitado; nenhum início automático |
| 4. Construção controlada e verificação técnica | Criar somente os componentes autorizados, em ambiente de construção/testes, com registro de alterações e evidências | Estruturas e controles reais verificados; avaliação própria de PT-TEC-01 quando houver evidência suficiente |
| 5. Dados, segurança, continuidade e homologação | Preparar migração quando aplicável, comprovar proteção e acesso, backup/restauração, reconciliações e cenários funcionais; obter aceite operacional | PT-DAD-01, PT-SEG-01 e PT-BCP-01 tratados antes do uso de dados reais; PT-HOM-01 avaliado com evidências e decisão humana |
| 6. Entrada em operação e fechamento administrativo cabível | Identificar versão oficial, tratar riscos residuais, definir retorno, obter autorização de operação e decidir sobre encerramento da fase no alcance aplicável | PT-OPE-01 e autorização expressa; eventual conclusão da Fase 05 em ato próprio, não presumida |

Dados, segurança e continuidade devem ser planejados desde os grupos 1–3. O grupo 5 não autoriza deixar seus controles para depois do primeiro uso de dados reais. Testes com dados sintéticos também exigem autorização dentro do lote. Migração só será executada se o recorte exigir e houver autorização; a inaplicabilidade de qualquer portão depende de justificativa e decisão própria, nunca é presumida.

## 6. Pendências que atravessam o roteiro

### C-F05-05 e cadeia 4H.5

E5-04 reverificou onze eixos: 1, 8, 10 e 11 conformes documentalmente; 2, 3, 4, 6 e 7 com ressalva material; 5 e 9 parcialmente verificáveis. O primeiro elo autônomo final de 4H.5 continua não comprovado. Não se reconstrói esse elo por inferência nem se declara sua prova suprida por uma implementação futura.

A próxima especificação deverá explicitar se e como essa limitação alcança o primeiro recorte. Se a fonte faltante for obrigatória para uma decisão ou comprovação, o item deve parar para obtenção da fonte ou decisão humana sobre tratamento documental admissível. Isso não cria bloqueio geral novo para todo o projeto e não declara a limitação resolvida.

C-F05-05 permanece parcialmente atendida. Seu atendimento integral e o encerramento do mapeamento exigem processo próprio, evidências pertinentes e ato humano. Não se exige prova de construção inexistente para declarar que há apenas uma proposta de desenho; tampouco se aceita desenho como prova física.

### Matriz 149/33 e TRT-04

Os 33 detalhes permanecem oficialmente condicionados e em TRT-04. A construção ou o detalhamento futuro não os promove automaticamente a TRT-05. Se houver proposta de mudança, deverá ser nominal, rastreável, conferida e submetida a decisão própria. A matriz 149/33 continua intacta até esse ato.

### Pendências funcionais e arquiteturais

As pendências já registradas continuam com seus estados. Antes de construir uma função afetada, deve-se distinguir regra aprovada, parâmetro ainda a decidir, exceção não coberta e evidência ausente. Não é necessário inventar solução para todas as possibilidades futuras para delimitar um primeiro lote; qualquer exclusão deve ser explícita e não ocultar dependência essencial.

Permanecem as ressalvas de proveniência/publicação, inventário de 67 itens, divergência histórica 63/64 e ocorrências distintas de E2-03C. Não se cria novo PEN-* ou DEC-* por esta proposta.

## 7. Próximo trabalho recomendado

**Alternativa A — recomendada: preparar a definição formal de um próximo escopo documental para especificar o primeiro recorte de construção e seu desenho físico controlado.**

A definição deverá propor objetivo, limites, responsável, unidades, produtos, fontes, critérios de entrada/aceite/conclusão e paradas. Deve aproveitar as decisões de plataforma e os resultados documentais já aceitos. Seu foco é produzir decisões e especificações que permitam um pacote executável posterior, e não uma nova rodada geral de avaliação dos quatro portões.

Conteúdo mínimo recomendado para esse futuro trabalho:

1. recorte funcional inicial e suas exclusões, dependências e critérios de aceite;
2. correspondência concreta entre objetos lógicos e estruturas dos dois arquivos Excel já previstos;
3. decisões materiais sobre parâmetros e controles necessários ao recorte;
4. rastreabilidade das pendências que afetam o lote, incluindo a limitação 4H.5;
5. plano de evidências e testes, segurança, backup/restauração e eventual migração;
6. condições explícitas para autorização posterior da primeira construção.

Esses seis tópicos são conteúdo recomendado, não seis unidades já aprovadas. Nenhum identificador de novo escopo, unidade ou produto é atribuído nesta minuta. Aceitar a direção permite preparar sua definição; criação, ativação e execução do escopo terão atos próprios conforme o fluxo vigente.

**Alternativa B — pausa controlada:** manter a linha mestre e o estado concluído de ESC-F05-06, sem iniciar nova definição. É possível solicitar ajuste desta proposta antes de escolher a direção. A pausa não desfaz avaliações ou conclusões já aceitas.

## 8. Limites e critérios de parada

Esta proposta não publica documentos; não altera fontes, registros mestres, regras, arquitetura, nomes oficiais futuros, PEN-* ou DEC-*; não reabre fases ou escopos concluídos; não inicia planilha operacional, fórmula executável, consulta, integração, migração, teste ou operação. Não declara C-F05-05 integralmente atendida, não encerra o mapeamento ou a Fase 05 e não promove TRT-04.

Divergência de identidade, conflito material de autoridade, fonte obrigatória ausente, regra de negócio nova, alteração da arquitetura adotada ou necessidade de construção fora do recorte exigem apresentação ao humano e parada do objeto afetado. Não se contorna lacuna com hipótese plausível.

## 9. Aceite e estado de entrega

Critérios de aceite: reconhecer a linha mestre vigente e o aceite da publicação; distinguir etapas já concluídas das futuras; preservar PT-AMB-01 e decisões técnicas já adotadas; apresentar roteiro dependente de evidências e autorizações; explicitar condicionantes sem inventar soluções; manter o alcance exclusivamente propositivo.

Estado: proposta v0.1 preparada, não publicada; roteiro apresentado; nenhuma nova configuração formal criada ou ativada; nenhuma implementação autorizada. Decisão pendente: aceitar ou ajustar esta proposta e escolher A ou B. O aceite não equivale à criação, ativação ou autorização de construção de um novo escopo.
