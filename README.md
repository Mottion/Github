# git e Github

* `git init` - inicia uma linha do tempo;
* `git add` - adiciona ou atualiza mudanças para irem para a linha do tempo;
* `git commit` - adiciona um ponto na linha do temp. `git commit -m "msg"` - adiciona um ponto na linha do tempo com descrição;
* `git log` - vizualiza os pontos na linha do tempo, apresentando **nome**, **data de alteração** e **ID** do commit;
* `git status` - informa o estado das alterações no nosso projeto;
* `git show [id]` - apresenta determinado ponto na história, caso falte o **ID**, ele busca o ultimo ponto da história.
* `git branch [branch name]` - cria novas **branchs**(rotas), a rota principal é chama de **master**. Caso falte o **branch name**, ele mostra todas as branchs que o projeto possue. `git branch -D [branch name]` dele a branch especificada.
* `git checkout [branch name]` - altera para uma **branch** existente.
* `git merge [branch name]` - une a **branch** especificada com a branch atual.
