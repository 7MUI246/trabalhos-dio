Criando um repositório 
1 Passo : Criar uma Pasta na sua área de trabalho 
comando - mkdir 
2 Passo : Navegar dentro da pasta criada 
comando - cd xxx/ (xxx = nome da pasta)
3 Passo : Inicializar o repositório 
comando - git init 
*Para visualizar os arquivos dentro da pasta comando - ls 
Arquivos ocultos ls -a 
4 Passo : Navegar dentro dos arquivos ocultos 
comando cd .git/ e ls
5 Passo : Configurar o Git para se "conectar" ao GitHub 
Os usuários devem ser iguais para evitar erros 
comandos : git config --global user.email "xxx" (xxx = email do Git e  GitHub)
git config --global user.name "xxx"(xxx = usuário do Git e GitHub)
6 Passo : Adicionar o seu arquivo .md ao Git 
comando : git add * e git commit -m "commit inicial"
Verificar se o arquivo .md já está dentro da pasta 
comando : ls e git status
7 Passo : Criar subpasta 
comando : mkdir xxx (xxx= Nome da subpasta)
e verificar : ls 
8 Passo : Mover o Arquivo para a subpasta 
comando : mv XXX.md ./xxx/ (XXX= nome do arquivo e xxx= subpasta)
9 Passo :verificar se o arquivo está dentro da subpasta
comando : ls e cd xxx para navegar (xxx= subpasta)
10 : Verificar o status da subpasta 
comando : git status 
Ao realocar o arquivo em outra pasta, o GIT sub-entende que o mesmo foi deletado
é necessário adicioná-lo e commitá-lo novamente 
comando : git add XXX.md xxx/ (XXX= nome do arquivo e xxx= subpasta)
Git status para verificar se o arquivo foi commitado
11 Passo :Novo comando : git commit -m "cria pasta xxx, move arquivo para xxx"
git status para verificar se está ok
12 Passo : Criar README.md 
comando : ls e depois echo > README.md e ls novamente 
13 Passo : Para adicionar o README.md
comando : git add * e ls 
git status para verificar se está tudo ok 
git commit -m "adiciona index" 
14 Passo : Criar um novo repositório no Github com o mesmo nopme da pasta do Git 
Deixar público e copiar e url https
de volta ao git 
comando : git remote add origin + url 
comando : git remote -v 
comando : git status para verificar se está tudo ok
15 Passo : Comando Push para trazer todos os dados do repositório para o local 
comando : git push origin master (modo trabalhado)





