# Aula Github Terça

### Te amo

Git push = enviar/subir

Git pull = baixar/atualizar

Git checkout main

git commit -m "" -m ""

nano main.py

git checkout

git checkout -b <nome-da-branch>

git checkout <nome-da-branch>

Commits no Particípio Passado

feat/nome-branch ou feature/nome-branch: "feat" é feature, nova funcionalidade;

chore/nome-branch: "chore": atualização, nova biblioteca adicionada, outros recursos que não tem a ver com código;

ref/nome-branch: "ref": refatoração no código;

bugfix/nome-branch: "bugfix": problema encontrado nos testes ou em desenvolvimento;

hotfix/nome-branch: "hotfix": problema encontrado em produção ou quando estiver na branch main;

Manter documentação atualizada;

main ->> develop: a branch develop deve sempre estar atualizada com base na main

develop -->> {feature, ref, chore}/<nome>: Para criar novas branchs é necessário usar a branch develop como base

develop -->> bugfix/<nome>: quando for corrigir algum problema que está acontecendo em desenvolvimento ou teste

main ->> hotfix/<nome>: Apenas o professor orientador irá corrigir problemas graves

develop -->> main: Apenas o professor orientador irá fazer merge da branch develop dentro da main