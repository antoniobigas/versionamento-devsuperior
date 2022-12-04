# Nivelamento Git-hub


Primeiro passo para versionamento e principais comandos...

Abrir a pasta, clicar em gui bash here.

git init | Inicia um novo repositorio na pasta que voce deseja

git add . | Enviar o projeto para o Stage

git commit -m "Mensagem" | comando para salvar no repositorio e uma mensagem explicativa 

git status | mostra o status do projeto

git branch -M main | garantir que esta como main

git remote add origin git@github@.com:seuusuario/seurepositorio.git  || Para adicionar um repositorio

No caso deste exemplo:

git remote add origin git@github.com:antoniobigas/nivelamento-versionamento.git

git push -u origin main | Envia para o github o que você deseja.

se ficar dando erro isso aqui resolveu pra mim.

git remote set-url origin https://github.com/usuario/repositorio



forcar o push 
git push --force origin master


