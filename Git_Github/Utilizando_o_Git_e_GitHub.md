# Como utilizar o Git e GitHub

O objetivo principal destas anotações é dar base ao aprendizado e elucidar os principais comandos e suas funcionalidades, possibilitando a utilização fluida do Git e GitHub.

Atualmente o GitHub, também é utilizado como uma mídia social, sendo utilizado por recrutadores e empresas afim de entender e verificar o portfólio de desenvolvedores, bem como seu nível de conhecimento.

## Git

O Git possui um algoritmo de encriptação (SHA1) que é único e serve como identificação, gerando uma chave para as modificação (Blobs, Trees e Commits).

### Principais Comandos

- `git init` - Inicia um repositório do Git;
- `git add` -  Move os arquivos do staging para commit (* o asterisco move todos os arquivos para staging);
- `git commit -m` -  Move para a "produção" os arquivos (devemos sempre comentar após o commit entre " " o que estamos mudando no código);
- `git status` -  Mostra se há arquivos ou modificações no staging (que não estão sendo rastreados)  para commitar;
- `mkdir` - Cria uma pasta diretamente pelo terminal;
- `mv` - Move o arquivo ou pasta para outro repositório;

- `git hash`  - Retorna a encriptação (SHA1) do arquivo (Blob, Tree ou Commit) que é refletido em todo rastreamento do arquivo;
- `Ctrl+l` - Limpa os dados da tela;
- `git clone` - Através do http do projeto no GitHub, podemos criar um clone do repositório do GitHub no nosso Git local, afim de colaborar ou manter o versionamento do código;
- `git remote add origin` - Passando o link do GitHub verificamos que não temos nenhuma pendência no repositório;
- `git remote -v`- Lista os repositórios que temos no GitHub;
- `git push origin`- Utilizando a Branch (master) enviamos o repositório local para o GitHub (necessita de autenticação);

- `ls` - Lista os arquivos da pasta;
- `ls -a` - Lista os arquivos ocultos da pasta;
- `git config --global` - Configura os dados de autor;
- `git pull` -  Dado que já temos o clone do repositório ou o repositório em nosso Git, podemos utilizar o comando para puxar a última versão do projeto que está no GitHub;

## GitHub



Para que possamos compartilhar o nosso repositório do Git precisamos criar a conta no GitHub, para que outros desenvolvedores possam colaborar com nosso código.  Logo para que isso ocorra é importante que deixemos o repositório como público.

- É necessário criar um repositório no GitHub com o mesmo nome do repositório no Git;
- O Readme. conta a história/introdução do repositório;

### Principais Comandos

- No GitHub podemos criar os códigos como no Git, todavia temos que tomar cuidado na resolução de conflitos ao fazer o pull e push do Git para o GitHub;
