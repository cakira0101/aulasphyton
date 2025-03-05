para acessar use o GIT BASH 

- ver o status
git status

- Inicializar a pasta
git init

- incluir 1 arquivo para o git rastrear
git add .

- comitar o arquivo
git commit -a -m "primeiro comit"

- identificar "logar"
git config --global user.email "cakira0101@gmail.com"
git config --global user.name "Akira"

ir para o GitHub e criar o repositório na WEB

ir na linha abaixo copiar o comando e executar no cmd
git remote add origin https://github.com/cakira0101/aulasphyton.git

-- comando para enviar o ultimo commit para o gitweb
git push origin master

- vai  abrir uma autenticador, coloque a senha e ele vai enviar os aquivos para a web

- para clonar  o seu repositório em outro micro
git clone https://github.com/cakira0101/aulasphyton.git

- para enviar tudo para o web novamente
git add .
git commit -a -m "copiando tudo"
git push origin master

==> como recuperar da WEB para o seu micro
git pull origin master

