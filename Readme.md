# Git Course

[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/samuelfalico)](https://github.com/samuelfalico)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/samuelfalico/)](https://www.linkedin.com/in/samuelfalico/)

Repositório para aprender como funciona o Git e o GitHub.

## Commands

### Utils (Mais utilizados)
- git add -> Utilizado para adicionar os arquivos para staged, à serem enviados no commit.
- git diff -> Utilizado para comparar o que foi modificado com o estado original (apenas antes do commit).
- git checkout -> Utilizado para restaurar o arquivo caso não tenha sido realizado o commit, e para trocar de branch.
- git log -> Visualização de todas alterações feitas no repositório.
- git push -> Empurrar os arquivos para o repositório.
- git shortlog -> Visualização do log de uma forma curta, apenas o usuário e os seus commits.
- git status -> Visualizar os arquivos novos, modificados e qual seu estágio atual (untracked, modified, staged)

### Reset (Cuidado ao utilizar)
- git reset --soft -> Deleta o commit e volta os arquivos prontos (staged) para commit novamente.
- git reset --mixed -> Deleta o commit e volta os arquivos modificados (modified) para adicionar (add).
- git reset --hard -> Deleta o commit por completo, junto com os arquivos criados e, ou, modificados.