# Offline-first SDD

Local first.

SQLite é usado para operações do utilizador.
Alterações geram itens de sync queue.
Sincronização acontece na abertura, retorno ao foreground, recuperação de conectividade e mutations importantes.

Conflito MVP:
Last Write Wins pelo timestamp do servidor.

Falhas:
retry com exponential backoff.
