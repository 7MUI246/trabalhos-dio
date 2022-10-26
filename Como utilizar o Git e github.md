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
7 Passo : Criar um novo repositório no GitHub com o mesmo nome da Pasta criada no Git 
Colocar na descrição o mesmo nome do arquivo e deixar público. 
Após a criação do repositório, copiar a URL HTTPS:
8 Passo: De volta ao Git 
Verificar se o arquivo .md já está dentro da pasta 
comando : ls e git status
9 Passo : Criar subpasta 
comando : mkdir xxx (xxx= Nome da subpasta)
e verificar : ls 
10 Passo : Mover o Arquivo para a subpasta 
comando : mv XXX.md ./xxx/ (XXX= nome do arquivo e xxx= subpasta)
11 Passo :verificar se o arquivo está dentro da subpasta
comando : ls e cd xxx para navegar (xxx= subpasta)
12 : Verificar o status da subpasta 
comando : git status 
Ao realocar o arquivo em outra pasta, o GIT sub-entende que o mesmo foi deltado
é necessário adicionálo e comitá-lo novamente 
git init 
