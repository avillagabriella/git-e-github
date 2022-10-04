
#  Git e GitHub

<p>Repositório criado com comandos de Git e Github.
<br/> Abaixo irei listar os comandos úteis do Git e GitHub.
</p> 

<h3>Funcionalidades:</h3>

<p>
        git config --global user.name "nome"(configura usuário) <br>
        git config --global user.email "email" (configura email de usuário) <br/>
        git status (mostra o status do git) <br>
        git init (inicia repositório vazio) <br>
        git add "arquivo" (move uma alteração de untracked para staged, pronta para o commit) <br>
        git add . (move todas as alterações de untracked para staged, prontas para o commit) <br> 
        git rm --cached "arquivo" (remove uma alteração de staged para untracked) <br>
        git commit -m "comentário" (registra a alteração por commit) <br>
        git log (mostra informações sobre os commits criados) <br>
        git branch (mostra as versões existentes) <br>
        git branch "nome da branch" (cria uma versão) <br>
        git checkout "nome da branch" (navega entre versões) <br>
        git checkout -b "nome da branch" (cria uma versão e navega para ela) <br>
        git branch -d "nome da branch" (deleta uma versão) <br>
        git merge "nome da branch a ser importada" (unifica as versões) <br>
        git clone "chave SSH" (clona um repositório remoto para a sua máquina) <br>
        git remote -v (mostra repositório de origem) <br> 
        git push (envia as alterações para o repositório remoto) <br>
        git stash –include-untracked (salva alterações sem commit) <br>
        git stash pop (restaura alterações salvas) <br>
        git stash pop stash@{1} (aplica stash especifico) <br>
        git stash list (lista stashes) <br>
        git revert "4 primeiros dígitos do hash do commit" (inverte as mudanças de um commit e gera um novo commit com o conteúdo invertido) 

</p>
