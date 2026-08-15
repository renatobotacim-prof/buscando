GUIA PARA AUTENTICAR O GITHUB NO TERMINAL

sudo dnf install gh -y

gh auth login

selecione as opçoes com as setinha e confirme com o ENTER

GitHub.com

HTTPS

escreva "y" e de ENTER

Login with a web browser

aperte ENTER para abrir o navegador e logue na sua conta do github e depois escreva o codigo que apareceu no seu terminal
-------------------------------------------------------------------------------------------------------------------------------
Guia para fazer Commits

crie/navegue pelo terminal até a pasta onde vc vai fazer o projeto do GitHub

execute os comandos a seguir:

git init

git remote add origin https://github.com/renatobotacim-prof/buscando.git

agora faça a tarefa que você quer subir para o github

git add .

git commit -m "explicação do commit"

se for a primeira vez que esta comitando nesse computador ou na VM digite os seguintes comandos{

git branch -M main

git push -u origin main
 }
