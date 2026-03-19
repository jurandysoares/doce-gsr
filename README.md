# doce-gsr

Documentação para disciplina Gerência e Segurança de Redes

## Instalação das ferramentas

1. `curl -LsSf https://astral.sh/uv/install.sh | sh`
1. `uv init`
1. `uv add mkdocs mkdocs-material`
1. `uv run mkdocs`
1. `uv run mkdocs new .`
   1. Edite o arquivo `mkdocs.yml` seguindo o exemplo [mkdocs.yml](https://github.com/jurandysoares/doce-gsr/blob/main/mkdocs.yml)
1. `uv run mkdocs serve`
1. `uv run mkdocs gh-deploy`
1. `git add .`
1. `git commit -m "MENSAGEM"`
1. `git push`

## Edição do programa da disciplina
   
1. `URL="https://gitea.mange.ifrn.edu.br/1577142/programa-disciplinas/raw/branch/main/docs/plano-gerencia-seguranca-redes.md"`
1. `curl -o docs/programa.md "${URL}"`
1. `code docs/programa.md`

Formate o programa da disciplina para ficar semelhante à versão PDF disponível em <https://mange.ifrn.edu.br/plano-disciplina/redes/gsr.pdf>.


