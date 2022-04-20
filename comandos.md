# principais comandos git

## inicializar repositorio:
`git init`

## adiciona o arquivo ao git (coloca o stash) (use o mesmo comando caso quiser fazer alguma modificação no arquivo)
`git add nome-arquivo`

## adiciona varios arquivos ao git (coloca na memoria)
`git add .`

## mostra o status geral do uso do git
`git status`

## mostra o historico de commits
`git log`

## realizar commit com uma mensagem
`git commit -m "mensagem desejada"`

## mudar nome de branch de master pra main (basta fazer apenas 1x)
`git branch -M main`

## fazer clone de um repositorio
`git clone endereço-repositorio.git`

## adiciona uma referencia do repositorio remoto no ambiente local
`git remote add origin https://github.com/DR4CH3N/Exemplo-cli.git`

## fazendo push (envio para o repositorio remoto) (com -u somente 1x)
`git push -u origin main`

## para mais informações de comandos
https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/ <-- PT-BR

https://training.github.com/downloads/github-git-cheat-sheet/ <-- EN