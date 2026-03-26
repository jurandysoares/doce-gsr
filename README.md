# doce-gsr

Documentação para disciplina Gerência e Segurança de Redes

## Instalação das ferramentas

1. `curl -LsSf https://astral.sh/uv/install.sh | sh`
1. `exit`

Abra um novo terminal e volte a executar os comandos. Caso tenha aberto o VS Code, feche-o e abra-o novamente. Tais procedimentos servem para atualizar a variável de ambiente `PATH`.

1. `uv init`
1. `uv add zensical`
1. `uv run zensical`
1. `uv run mkdocs new`
   1. Edite o arquivo `zensical.toml` seguindo o exemplo [zensical.toml](https://github.com/jurandysoares/doce-gsr/blob/main/zensical.toml)
   
1. `uv run zensical serve`
   1. Abra a URL <http://localhost:8000>, caso esteja editando o projeto em sua máquina local. No Codespace do GitHub, clique no botão que aparece "Abrir no Navegador".
   1. Pressione, simultaneamente, as teclas `Ctrl`+`C` para interromper o servidor HTTP local

Edite as páginas de sua documentação, que ficarão salvas em arquivos com extensão ".md" dentro do diretório <./docs>.

1. `git add .`
1. `git commit -m "MENSAGEM"`
1. `git push`

## Edição do programa da disciplina
   
1. `URL="https://gitea.mange.ifrn.edu.br/1577142/programa-disciplinas/raw/branch/main/docs/plano-gerencia-seguranca-redes.md"`
1. `curl -o docs/programa.md "${URL}"`
1. `code docs/programa.md`

Formate o programa da disciplina para ficar semelhante à versão PDF disponível em <https://mange.ifrn.edu.br/plano-disciplina/redes/gsr.pdf>.


