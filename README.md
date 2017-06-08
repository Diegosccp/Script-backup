# Script-backup
Aluno: Diego Miranda Figueira

Como criar um backup do PostGres, use um lingaguem SHELL

1 ° - Passo

Incluir como variáveis de ambiente "pg_dump" e "pg_restore" do postgres

2 ° - Passo

Realizar como mudança de dados do arquivo como:
#! / Bin / bash

Exportar PGPASSWORD = "SENHA_DO_POSTEGRES"

Pg_dump -U USUÁRIO_POSTGRES -h LOCAL_BANCO_DE_DADOS -O -o -b -F c NOME_BANCO_DADOS> NOME_DO_BACKUP.backup

Pg_restore -U USUÁRIO_POSTGRES -h LOCAL_BANCO_DE_DADOS -d NOME_BANCO_DADOS NOME_DO_BACKUP.backup

3 ° - Passo


Realize a execução do arquivo Shell.
