# REGISTRO COMPLEMENTAR — CONFERÊNCIA DO PACOTE EXEC-FUNC-B-09 E STATUS DA LINHA MESTRE

**Versão:** v0.1 — 26/09/2026  
**Classificação:** registro complementar de conferência técnica e esclarecimento de status; não substitui os registros mestres.  
**Frente:** continuidade controlada da consolidação do projeto.

## 1. Autoridade e propósito

Este registro consolida o retorno de conferência técnica somente de leitura do pacote EXEC-FUNC-B-09, comunicado pelo responsável humano em 26/09/2026, e a manifestação expressa do mesmo dia sobre a linha mestre vigente e a preservação das minutas candidatas.

Não cria fase ou frente, não altera regra de negócio ou arquitetura, não reabre fase encerrada e não substitui os registros mestres.

## 2. Conferência do pacote B-09

**Resultado informado:** CONFORME no escopo conferido, sem divergências de bytes, inventário, CRC, referências ou OOXML.

| Objeto | Resultado conferido |
|---|---|
| ZIP | 257.610 bytes; SHA-256 `bd0703c3ace3af3a5c44b9c73aaf95d6966ad3daee1a27953e2976cb313d7a85`; 24 entradas, nomes únicos, inventário exato e CRC íntegro |
| Manifesto | 23 arquivos de carga com tamanho e SHA-256 coincidentes; hash local e interno `0653efaefa481dd6d1c310f5bf50346bc108d3746970fa56be87c85f58ec95cb` |
| Conferência local | SHA-256 `64f9a9c0ef36599ff18dbbc6e4fa3731a84787a948f321079f6bc9c0883d0c92`; produzida após a conferência e não incluída no ZIP |
| Planilha B-09 | 16.111 bytes; SHA-256 `610425bf9fd5ffb9bcdf8f0a9a2daa43c8a228a3b0d43de3e3f24e4662544583`; bytes locais e internos idênticos |
| OOXML temporal | 26 valores temporais armazenados como texto (`str`), 0 valores seriais numéricos; Cadastro!D26:D27, Trilha!F36:G45 e Qualidade!G8:G11 |
| Testes dirigidos | 11 aprovados, 0 reprovados. Os testes 6 e 9 foram aprovados por evidência estática preservada; não foram reexecutados |
| Cenários E7-04 | 0/30 artefatos de execução presentes no pacote; essa constatação não prova ausência de eventual execução externa |

A primeira exportação foi preservada: 15.962 bytes, SHA-256 `260c1438cbf53c1de977d6981d862e75d240a40e055d4fcb44de006eacf481f2`. A inspeção confirmou valores seriais em Qualidade!G10 e G11, em conformidade com o diagnóstico `NAO_CONFORME`.

O auxiliar NDJSON preservado tem 153.325 bytes, SHA-256 `8b339e20fdc2452ea4856da77c151abdb74e9891ca9ee6e26904a225d83dddd5`; 477/477 linhas são JSON válido. A tentativa corrigida tem o mesmo SHA-256 da planilha final; o diagnóstico consta como `CONFORME`, com zero células numéricas.

Os inventários protegidos foram recalculados e coincidem com a evidência: B-07 — 32 arquivos, SHA-256 `71f8264aa92035c85c02e104bf5ef0afbb1059618d6fc4def4f0522db522dc06`; B-08 — 9 arquivos, `072826a806849ecda7166d4ed61f4355699f044928f2e354ad9e09c76071315a`; EVD-01 — 16, `3e48181746c87a0f5cc2b04f47684fd23e56e53c581b5d55074a8cd32fe10dce`; EVD-02 — 29, `2986c5538515d5df7525e6698e703430b23955d234787c4401ad6b0bd453e7e4`; EVD-03 — 33, `1045aa8986610eed6f277fbf9d98b1e47ec55cb8933a4b1c89ec763d0958ea0a`.

A conferência confirma o conteúdo e os hashes informados para o pacote. Não reexecuta testes funcionais ou consulta por data de corte; para esses pontos, preserva a classificação de evidência estática acima.

## 3. Limites de estado

B-08 permanece interrompida por sua falha própria em G10/G11. A conferência e o resultado B-09 não aprovam B-08 retroativamente.

B-09 não conclui EC-03, não elimina lacuna geral, não encerra ESC-F05-09 ou a Fase 05 e não autoriza outra execução. Nenhum pacote ou planilha foi carregado neste registro.

## 4. Linha mestre e minutas preservadas

Por manifestação expressa do responsável humano em 26/09/2026, a linha mestre oficial vigente permanece:

- REG-CONSOLIDACAO-CHATS v0.23;
- REG-DECISOES v0.27;
- REG-PENDENCIAS v0.22.

Permanecem como minutas candidatas de sucessão, não aceitas e não vigentes:

- REG-CONSOLIDACAO-CHATS v0.24;
- REG-DECISOES v0.28;
- REG-PENDENCIAS v0.23.

Os conteúdos, a estrutura e o histórico dessas minutas devem ser preservados integralmente para revisão futura. Não excluir, sobrescrever, renumerar nem tratar sua presença física no GitHub como aceite ou vigência.

O commit `2615e869628d910ae19edfd00c6edcef1e1dd50e`, cuja mensagem diz “Publica linha mestre pós-ESC-F05-08”, permanece intacto como histórico. A manifestação humana posterior esclarece o status atual; esta correção não reescreve a mensagem nem os bytes de arquivos históricos.

## 5. Efeito

Este registro é complementar. Não constitui aceite funcional da planilha para uso operacional, não altera os mestres, não muda regra de negócio, não aceita B-08 e não autoriza EC-03, publicação da planilha ou nova execução técnica.
