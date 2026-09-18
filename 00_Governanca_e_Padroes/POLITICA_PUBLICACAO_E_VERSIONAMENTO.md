# POLÍTICA DE PUBLICAÇÃO E VERSIONAMENTO

**Projeto:** Dev_Ecossistema_Integrado_Gestao_Empresarial  
**Versão desta política:** v0.2  
**Data:** 17/09/2026

## 1. Fluxo aprovado

CONVERSA  
↓  
TRABALHO EM DESENVOLVIMENTO  
↓  
MINUTA  
↓  
APROVAÇÃO EXPRESSA DE EDUARDO  
↓  
GITHUB

## 2. Regra de publicação

Somente após aprovação expressa de Eduardo o produto correspondente poderá ser publicado como arquivo oficial no GitHub.

Cada publicação oficial deverá preservar, quando aplicável:

- arquivo oficial;
- commit correspondente;
- data da publicação;
- versão do documento;
- histórico de alterações.

## 3. Regra de atualização documental

Quando um documento oficial receber nova versão aprovada:

1. a nova versão aprovada deverá ser publicada no GitHub;
2. a nova versão passa a ser a versão vigente somente após a publicação correspondente;
3. a versão anterior permanece obrigatoriamente preservada no histórico de commits do GitHub;
4. quando houver substituição documental explícita ou quando a rastreabilidade histórica materialmente exigir arquivo autônomo, a versão anterior deverá também ser arquivada em `09_Auditoria/Historico/`;
5. nenhuma versão anterior deverá ser apagada de forma a eliminar a trilha documental;
6. a publicação deverá registrar mensagem de commit suficientemente descritiva para identificar a atualização;
7. a mudança de versão não autoriza alteração de conteúdo além do que tiver sido aprovado;
8. divergências entre versões não serão reconciliadas por inferência.

## 4. Tratamento por estágio

### 4.1. Em desenvolvimento

Conteúdos ainda em construção devem permanecer em `02_Em_Desenvolvimento/`, quando houver necessidade de persistência no repositório.

### 4.2. Revisão e validação

Produtos aguardando conferência, revisão ou aceite permanecem em `03_Revisao_e_Validacao/`.

### 4.3. Aprovados

Produtos expressamente aprovados e ainda não consolidados em registro mestre podem ser publicados em `04_Aprovadas/`.

### 4.4. Consolidados

Registros mestres, registros consolidados de fase e documentos vigentes de consolidação ficam em `08_Consolidados/`.

### 4.5. Histórico e auditoria

Versões substituídas que exigirem preservação documental autônoma ficam em `09_Auditoria/Historico/`.

O histórico nativo do GitHub continua sendo trilha obrigatória mesmo quando houver cópia física da versão substituída.

## 5. Regra para minutas

Minutas, estudos intermediários e trabalhos em desenvolvimento não se tornam documentos oficiais por mera criação.

Arquivos identificados como `_MINUTA` não podem ser promovidos, renomeados ou tratados como aprovados por inferência. A oficialização depende de aprovação expressa de Eduardo e posterior publicação no repositório.

## 6. Estrutura oficial

- `00_Governanca_e_Padroes/`
- `01_Modelos_e_Templates/`
- `02_Em_Desenvolvimento/`
- `03_Revisao_e_Validacao/`
- `04_Aprovadas/`
- `05_Rejeitadas/`
- `06_Arquivos_Referencia/`
- `07_Relatorios/`
- `08_Consolidados/`
- `09_Auditoria/`
- `09_Auditoria/Historico/`
- `10_Transcricoes/`

## 7. Princípio de preservação

A fonte vigente deve ser claramente identificável, mas a substituição de versão nunca elimina a rastreabilidade das versões anteriores.

A combinação de:

- arquivo vigente;
- versão;
- commit;
- data;
- histórico Git;
- arquivo histórico autônomo, quando aplicável;

constitui o mecanismo padrão de versionamento documental do projeto.
