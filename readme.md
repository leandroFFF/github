Olá este projeto ensina você a usar o Git:desktop_computer:

# Comandos Básicos #

* git --version   =>  mostra a versão do git instalado na máquina;
* git status  =>  Mostra o status da branch que está logado;
* git clone <link do github>  =>  Baixa uma cópia do repositório remoto;



### Branches ###

* git branch  =>  Mostra todos os Branchs(ramificações do código);
* git branch <nome-da-branch>  =>  cria uma branch local;
* git branch -d <nome-da-branch>  => deleta uma branch;
* git push -u <remote> <nome-da-branch>  =>  upar a nova branch para o repositório;
* git checkout  <nome-da-branch-destino>  =>  Muda de branch;
* git checkout -b  <nome-da-nova-branch>  =>  cria e vai para um branch de uma só vez;



###  Commitar para o repositório remoto ###

primeiro navegar até a pasta desejada, e digitar no git bash os comandos abaixo:

* git init  => cria um repositório vazio ou transforma uma pasta em um repositório;
* git add <arquivo>  =>  inclui apenas o arquivo para o próximo commit;
* git add . ou git add -A  =>  inclui tudo para o próximo commit;
* git commit -m "mensagem da alteração no código"  =>  registro da alteração;
* git push <origin> <nome-da-branch>  =>  envia e salva as alterações no repositório remoto;
* git pull <remoto>  =>  obtém atualização do repositório remoto (git fetch + git merge);
* git revert  'número-da-hash'  =>  desfaz os commits;
* git log --oneline  =>  mostra o número da hash;

### Para aparecer no github ###

caso não foi criado um repositório remoto, criar o mesmo para mostrar os commits enviados

* criar repositório no github.
* clica em repositórios > new > dá um nome e descrição > publico ou privado > criar repositório;



### Exemplo de envio ###

navegar até a pasta e digitar no git bash:

* git init
* git add .
* git commit -m "Mensagem"
* git push origin master