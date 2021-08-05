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
- git status -> Visualizar os arquivos novos, modificados e qual seu estágio atual (untracked, modified, staged).

### Junção
- git merge -> Cria o commit no horário, mantendo histórico, porém cria outro commit unindo (merge). Sempre terá um commit "extra".
- git rebase -> Coloca o commit como último da fila, mantendo um histórico linear.

### Reset (Cuidado ao utilizar)
- git reset --soft -> Deleta o commit e volta os arquivos prontos (staged) para commit novamente.
- git reset --mixed -> Deleta o commit e volta os arquivos modificados (modified) para adicionar (add).
- git reset --hard -> Deleta o commit por completo, junto com os arquivos criados e, ou, modificados.

### Extras
- git config --global alias.[tecla] [função] -> Caso queira adicionar teclas de atalhos, passar a tecla, e qual a função.
- git tag -> Adicionar versão da release.
- git push origin main --tags -> Enviar as tags(release) para o GitHub.
- git stash -> Guardar os arquivos modificados em um espaço reservado, caso não queira perder o que tenha feito, e não poderá subir no momento.
- git stash apply/pop/clear -> Apply utilizado para receber o que esta no stash, porém não deleta o stash. O pop puxa o conteúdo e deleta do stash. O clear limpa todo o stash.