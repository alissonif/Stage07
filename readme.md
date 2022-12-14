# Stage 07 Git - Github - Search's

# Git

馃殌 Controle de vers茫o </br>
馃殌 Iniciando um reposit贸rio </br>
馃殌 O .git </br>
馃殌 Configurando o Git </br>
馃殌 Primeiro commit </br>
馃殌 Git log </br>
馃殌 Est谩gios do arquivo </br>
馃殌 Git Status </br>
馃殌 HEAD </br>
馃殌 Git Diff </br>
馃殌 Desfazendo modifica莽玫es </br>
馃殌 Restaurando da Staged </br>
馃殌 Corrigindo o 煤ltimo commit </br>
馃殌 Desfazendo o 煤ltimo commit </br>
馃殌 Source Control do VS Code

# 馃 O que aprendi ap贸s finalizar esse m贸dulo?

- [鉁匽 O que 茅 o Git;
- [鉁匽 O que 茅 controle de vers茫o;
- [鉁匽 Comando git log;
- [鉁匽 Comando git status;
- [鉁匽 O que 茅 o HEAD no Git;
- [鉁匽 Comando git diff;
- [鉁匽 Comando git restore;
- [鉁匽 Comando git 鈥攁mend;
- [鉁匽 Utilizar o Source Control do VS Code;

# Github

馃殌 Criando uma conta </br>
馃殌 Perfil P煤blico </br>
馃殌 P谩gina do usu谩rio </br>
馃殌 Criando reposit贸rio </br>
馃殌 Git push </br>
馃殌 Git ignore </br>
馃殌 Gitkeep </br>
馃殌 Hist贸rico Remoto </br>
馃殌 Git clone </br>
馃殌 Git pull </br>
馃殌 README </br>
馃殌 Mudar a visibilidade do projeto

# 馃 O que aprendi ap贸s finalizar esse m贸dulo?

- [鉁匽 O que 茅 o Github;
- [鉁匽 Criar conta no Github;
- [鉁匽 Editar perfil p煤blico;
- [鉁匽 Criar reposit贸rios;
- [鉁匽 Fazer push das altera莽玫es;
- [鉁匽 Utiliza莽茫o dos arquivos .gitignore e .gitkeep;
- [鉁匽 Visualizar hist贸rico de modifica莽玫es;
- [鉁匽 Utilizar o comando git clone;
- [鉁匽 Utilizar o comando git pull;
- [鉁匽 Mudar a visibilidade do reposit贸rio;
- [鉁匽 Criar e customizar o README;

# Como pesquisar ?

馃殌 Abertura </br>
馃殌 O f贸rum </br>
馃殌 O que perguntar </br>
馃殌 Antes de abrir um t贸pico </br>
馃殌 Pesquisando t贸picos </br>
馃殌 Abrir t贸pico </br>
馃殌 N茫o remova </br>
馃殌 MDN </br>
馃殌 Stack Overflow </br>
馃殌 Utilizando erros </br>
馃殌 Palavras-chave </br>
馃殌 Encerramento

# 馃 O que aprendi ap贸s finalizar esse m贸dulo?

- [鉁匽 Como pesquisar no f贸rum do Explorer
- [鉁匽 Como criar um t贸pico corretamente nos f贸runs da web
- [鉁匽 Como ler uma mensagem de erro
- [鉁匽 Como pesquisar solu莽玫es atrav茅s de palavras-chave

## Links 煤teis:

[Como criar um t贸pico ideal](https://www.notion.so/Como-criar-um-t-pico-ideal-408faa68bebc4f9590711ee935c9cac9)

[MDN Web Docs](https://developer.mozilla.org/pt-BR/)

[Stack Overflow em Portugu锚s](https://pt.stackoverflow.com/)

<h2 align="center">Neste Stage 7 usei 馃憞</h2>

<div align="center">

  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" width="52" alt="git logo"  />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" width="52" alt="github logo"   />
          
</div>

<h2 align="center">Anota莽oes das aulas 馃憞</h2>

<div align="left">

     *****Git-parte1*****

git init=inicia o git no projeto/pasta

git config --global user.name "Jos茅 Alisson"

git master 鈫? git config --global user.email "fulano@gmail.com"

git config --list  =lista todas as configura莽玫es do git

1 git add .=prepara os arquivos

3 git commit -m "created index.html"=salva um ponto na linha do tempo do github

git log=hist贸rico

git log oneline=hist贸rico sem mecionar o autor

git log -n 3=quantidades de registros que vc quer ver

2 git status=status do projeto

head=ultima altera莽茫o

main=master-->branch=ramifica莽茫o-linha do tempo

branch principal(main)

git diff =mostra linha a linha do que foi alterado

git restore .=restaura para o arquivo original

git restore index.html=restaura um arquivo espec铆fico

git restore --staged . ou git restore --stage index.html=desfazer uma altera莽茫o que j谩 foi para stage=ultima modifica莽茫o

git commit --amend -m 'change page index.html'=alterar a mensagem do commit anterior

git reset --soft HEAD~1=desfazendo o 煤ltimo comit

ultima aula de git =Source Control do VSCode->tudo pelo vscode, sem terminal

-----------------------------------------------------------------------------------
******Github-parte2*****

git add readme=add uma descri莽茫o

git branch - M main=muda do 'master' para o 'main'

git remote add origin https://git@github.com:alissonif/CSS-3.3.git = adiciona uma origem remota no nosso git e copia esse endere莽o para add essa  referencia da onde 茅 nosso repositorio remoto do github

consultar endere莽o remoto=git remoto --v

git push -u origin main=na primeira vez executa esse comando completo

git push =salva nosso c贸digo local no github

 origin =referencia do nosso reposit贸rio remoto onde ele estar no github

-u=memoriza na primeira  vez ai na proxima vez vc usa s贸 usa 'git push'

.gitignore=lista de arquivos e pasta que ser茫o ignorados pelo git 

git rm -r --cached .=git armazena em cache as pasta que tem que ser ignorada, por isso fazemos update no cache como se fosse o reset no cache

.gitkeep para registrar uma pasta vazia no github

hist贸rico remoto=pode ver todos os commits no github

git pull=busca por atualiza莽玫es l谩 no github e traz tudo isso para a sua m谩quina local

git remote --v=para ver a origem do reposit贸rio

um projeto tem que estar vinculado a um reposit贸rio

cuidado para n茫o fazer uma confus茫o de reposit贸rios

readme='leiame'=documenta莽茫o do projeto, site recomendado para ter id茅ias para construir o seu readme: 'reame.so/pt'

</div>


### Contato

<img align="left" src="https://www.github.com/alissonif.png?size=150">

### [**Jos茅 Alisson Ferreira Machado**](https://github.com/alissonif)

馃洜 `Web` Developer Jr. <br>
馃搷 Alagoas - Brazil

<a href="https://www.linkedin.com/in/josealissonif/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn Badge" height="25"></a>&nbsp;<a href="mailto:josealissonif@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white" alt="Gmail Badge" height="25"></a>&nbsp;<a href="#"><img src="https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white" title="josealisson#5744" alt="Discord Badge" height="25"></a>&nbsp;<a href="https://www.github.com/alissonif" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white" alt="GitHub Badge" height="25"></a>&nbsp;
<br clear="left"/>
