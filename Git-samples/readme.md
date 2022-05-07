- Criando alguns atalho para melhor desenvolvimento com o git

- Níves de configuração do git
-- System ( Todo o sistema geral )
-- Global ( do usuário para qualquer projeto )
-- Local ( Do projeto )


 git config --list
    git config --global --edit
        git config --global core.editor code
            git config --global --edit


  git log --pretty=format:'%cn'
    -- para trazer o nome da pessoa que fez o commit

  git log --pretty=format:'%cr'
    -- data relativa ao commit

  git log --pretty=format:'%H'
    -- mostra a Hash do commit (id)

  git log --pretty=format:'%h'
    -- Hash reduzida




/*  gitConfig    */

[user]
	email = seu@emai...
	name = Seu nome
[core]
	editor = code
[alias]
	s = !git status -s
	c = !git add --all && git commit -m
	l = !git log
